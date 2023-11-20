# raghudevopsb75/tf-module-app

```bash
aws kms create-grant \
  --region us-east-1 \
  --key-id arn:aws:kms:us-east-1:739561048503:key/e8e78cec-c8e2-4f7d-a525-554ed53015d2 \
  --grantee-principal "arn:aws:iam::739561048503:role/aws-service-role/autoscaling.amazonaws.com/AWSServiceRoleForAutoScaling" \
  --operations "Encrypt" "Decrypt" "ReEncryptFrom" "ReEncryptTo" "GenerateDataKey" "GenerateDataKeyWithoutPlaintext" "DescribeKey" "CreateGrant"
```