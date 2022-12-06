# Code Catalyst

Deploy the following role for use with Code Catalyst.

```bash
aws cloudformation deploy \
    --template-file role.yml \
    --stack-name devopstar-ops-codecatalyst-role \
    --region us-west-2 \
    --capabilities CAPABILITY_NAMED_IAM
```
