# gitlab-runner

A simple Gitlab runner to deploy on AWS.

## Build the AMI

```sh
packer build \
    -var 'access_key=...' \
    -var 'secret_key=...' \
    -var 'region=eu-west-3' \
    packer.json
```
