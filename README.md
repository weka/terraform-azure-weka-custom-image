### Create azure custom image:
```shell
export SUBSCRIPTION_ID="..."
export CLIENT_ID="..."
export CLIENT_SECRET="..."
export TENANT_ID="..."
export IMAGE_RG_NAME="weka-images"

packer build ubuntu20.json
```