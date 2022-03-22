# docker-registry

This project is a example for showing that using MinIO as S3 backend for
registry.

```shell
  s3:
    region: us-east-1
    bucket: harbor
    accesskey: FGLS3AA51N1CZQERYLEW
    secretkey: rO7spyVjU4Va73e7qEap644jKEEeaA7iM5v64HUm
    regionendpoint: http://IP:9000 # This is important because we use MinIO as S3 instead of real S3.
    secure: false    
```