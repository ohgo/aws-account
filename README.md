# aws-account
Per-account AWS setup for e.g. roles, vpc, etc.

## Deploy

```sh
aws cloudformation deploy \
  --stack-name aws-account \
  --template-file cf.yaml \
  --capabilities CAPABILITY_IAM \
  --no-fail-on-empty-changeset
```
