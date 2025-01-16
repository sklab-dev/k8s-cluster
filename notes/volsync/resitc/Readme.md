```
services:
  restic:
    name: restic
    image: docker pull ghcr.io/restic/restic:0.17.3@sha256:b89484687c77dfe09d7415a0ced4ad1e820bfba0f8e5c97881e697299d6b734b
    restart: unless-stopped
    labels:
      com.example.service: restic
      com.example.version: "0.17.3"
    environment:
      RESTIC_REPOSITORY: /repository
      RESTIC_PASSWORD: ""
      RESTIC_PROGRESS_FPS: 2
      RESTIC_COMPRESSION: auto
    ports:
      - '8000:22'
    volumes:
      - mnt/storage/k8s.sklab.dev/volsync:/repository

```