  # Backup Configuration  
  # backup:
  #   retentionPolicy: 30d
  #   barmanObjectStore: &barmanObjectStore
  #     data:
  #       compression: bzip2
  #     wal:
  #       compression: bzip2
  #       maxParallel: 8
  #     destinationPath: s3://cloudnative-pg/
  #     endpointURL: https://604128bd389364580b3208006c949072.r2.cloudflarestorage.com
  #     # Note: serverName version needs to be incremented
  #     # when recovering from an existing cnpg cluster
  #     serverName: &currentCluster postgres16-v1
  #     s3Credentials:
  #       accessKeyId:
  #         name: cloudnative-pg-secret
  #         key: aws-access-key-id
  #       secretAccessKey:
  #         name: cloudnative-pg-secret
  #         key: aws-secret-access-key

  # Note: previousCluster needs to be set to the name of the previous
  # cluster when recovering from an existing cnpg cluster
  # bootstrap:
  #   recovery:
  #     source: &previousCluster postgres16-v0
  # bootstrap:
  #   initdb:
  #     database: app
  #     owner: app
  #     secret:
  #       name: cloudnative-pg-secret

  # Note: externalClusters is needed when recovering from an existing cnpg cluster
  # externalClusters:
  #   - name: *previousCluster
  #     barmanObjectStore:
  #       <<: *barmanObjectStore
  #       serverName: *previousCluster
