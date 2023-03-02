# AWS Cert notes

## AWS cloud practioner , sample exam 4:
wrong answer:
- 7: s3 storage class. IA .. infrequent access
- 9 : event source for lambda

nodes:
- general purpose SSD 10K IOPS, optimze IOPS 30K IOPS
- alias record used for load balancer, s3, cloudfront, elastic beanstalk
- IA ... infrequent access, ada IA one zone
- event source buat lambda: S3 sama dynamoDB
- route 53 :
    - weight: pakai number
    - failover: kalau yg asli engga bisa dikontak
    - geo : based on location user
    - latency: simpen database latency per ip
- aws cognito: kasih akses buat mobile apps and web
