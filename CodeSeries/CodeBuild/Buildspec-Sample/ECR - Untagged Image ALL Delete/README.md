## Buildspec - ECR Untagged Image All Delete
---
### Buildspec Secsion
- pre_build
    - Environment AccountID
    - Environment Product ECR Name
    - Environment Stress ECR Name
    - Login ECR
    - Environment Product ECR URL
    - Environment Stress ECR URL
    - Environment Product Image Delete
    - Environment Stress Image Delete
    - Environment Image Tag
- build
    - Docker Build Product Image
    - Docker Build Stress Image
- post_build
    - Docker Push ECR Product
    - Docker Push ECR Stress
    - Product ECR Delete UnTagged Image
    - Stress ECR Delete UnTagged Image