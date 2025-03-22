# Ingress Controller

REGION_CODE=us-east-1
CLUSTER_NAME=expense
ACC_ID=339713057882

### Permissions

* ODIC provider
---
eksctl utils associate-iam-oidc-provider \
    --region $REGION_CODE \
    --cluster $CLUSTER_NAME \
    --approve
---