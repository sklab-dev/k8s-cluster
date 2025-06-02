Research this what exactly this does
```
    ingress:
      main:
        enabled: true
        primary: true
        className: external-nginx
        annotations:
          external-dns.alpha.kubernetes.io/target: "ingress.skylab.fi"
        hosts:
          - host: "${HOSTNAME}"
            paths:
              - path: /
                pathType: Prefix
                service:
                  name: main
                  port: http
        tls:
          - hosts:
              - "${HOSTNAME}"
      int:
        enabled: true
        className: internal-nginx
        hosts:
          - host: "${HOSTNAME}"
            paths:
              - path: /
                pathType: Prefix
                service:
                  name: main
                  port: http
        tls:
          - hosts:
              - "${HOSTNAME}"
```
