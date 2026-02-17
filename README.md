# AWS-Task3

Services Used:
- AWS S3
- CloudTrail
- CloudWatch
- EC2
- Application Load Balancer

Steps:
1. Created private S3 bucket.
2. Enabled CloudTrail and CloudWatch logging for S3 upload events.
3. Launched two EC2 instances with Apache web server.
4. Created target group and attached instances.
5. Created Application Load Balancer.
6. Verified traffic routing via ALB DNS.

Result:
Load balancer distributes traffic between two EC2 instances successfully.
