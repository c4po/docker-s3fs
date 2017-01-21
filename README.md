A docker image for s3fs-fuse https://github.com/s3fs-fuse/s3fs-fuse




```
docker run \
    -e SFTP_USER=xxx \
    -e SFTP_PASSWORD=yyy \
    -e AWS_ACCESSKEY=abcd1234 \
    -e AWS_SECRETKEY=abcd1234 \
    -e S3_BUCKET=abc \
    -e S3_KEY=/ \
    -e SSH_KEY=xxx \
    -p 2222:22 \
    -d \
    sftp-to-s3
```

