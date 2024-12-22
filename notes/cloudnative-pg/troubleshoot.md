postgres@postgres17-1:~/data/pgdata$ cat pg_hba.conf

#
# FIXED RULES
#

# Grant local access ('local' user map)
local all all peer map=local

# Require client certificate authentication for the streaming_replica user
hostssl postgres streaming_replica all cert
hostssl replication streaming_replica all cert
hostssl all cnpg_pooler_pgbouncer all cert

#
# USER-DEFINED RULES
#





#
# DEFAULT RULES
#
host all all all scram-sha-256













initContainers:
    - name: bootstrap-controller
      image: ghcr.io/cloudnative-pg/cloudnative-pg:1.24.1
      command:
        - /manager
        - bootstrap
        - /controller/manager
        - '--log-level=info'
      resources:
        limits:
          hugepages-2Mi: 2Gi
          memory: 4Gi
        requests:
          cpu: 500m
          hugepages-2Mi: 2Gi
          memory: 4Gi
      volumeMounts:
        - name: pgdata
          mountPath: /var/lib/postgresql/data
        - name: scratch-data
          mountPath: /run
        - name: scratch-data
          mountPath: /controller
        - name: shm
          mountPath: /dev/shm
        - name: kube-api-access-2z4x6
          readOnly: true
          mountPath: /var/run/secrets/kubernetes.io/serviceaccount
      terminationMessagePath: /dev/termination-log
      terminationMessagePolicy: File
      imagePullPolicy: IfNotPresent
      securityContext:
        capabilities:
          drop:
            - ALL
        privileged: false
        runAsNonRoot: true
        readOnlyRootFilesystem: true
        allowPrivilegeEscalation: false
        seccompProfile:
          type: RuntimeDefault