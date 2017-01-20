


```
docker run \
    -e SFTP_USER=xxx \
    -e SFTP_PASSWORD=yyy \
    -e S3_IDENTITY=abcd1234 \
    -e S3_CREDENTIAL=abcd1234 \
    -e S3_BUCKET=abc \
    -e S3_KEY=/ \
    -e SSH_KEY=xxx \
    -p 2222:22 \
    -d \
    sftp-to-s3
```