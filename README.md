# AWS DevOps Deployment Pipeline

End-to-end AWS deployment automation using GitHub Actions.

## Project Scope
- Deploy simple app to EC2
- Dockerize app, push to ECR, deploy to ECS using EC2
- Redeploy app to S3 and CloudFront

     The static site was successfully deployed to Amazon S3 and served through the S3 website endpoint.
     CloudFront creation is currently blocked by AWS account verification on this account. A support request has been submitted to AWS. Once verification is completed, the CloudFront distribution will be created and the invalidation step will be enabled in the workflow.

- Deploy resume app to Elastic Beanstalk using PHP platform
- Use OIDC instead of long-lived AWS credentials where required