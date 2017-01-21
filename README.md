A docker image for s3fs-fuse https://github.com/s3fs-fuse/s3fs-fuse


Download the secret file template.

./s3fs-secret.yaml

use base64 to encode values.


```
kubectl create -f s3fs-secret.yaml
kubectl create -f https://raw.githubusercontent.com/c4po/docker-s3fs/master/s3fs-kubernetes.yaml
```

