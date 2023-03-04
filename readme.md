# AWS Cert notes

## AWS cloud practioner , sample exam 4:
wrong answer:
- 7: s3 storage class. IA .. infrequent access
- 9 : event source for lambda
- 16: AWS machine learning
- 23: VPC consist of ..
- 24: VPC wizrd
- 29: route 53,
- 30: dynamo DB : on demand and provisioned
- 33: EBS provisioned, not by number snapshot
- 40 : database charge: type, uptime, multi az, 
- 43: access using federation IAM
- 47: CRR -> cross region replication
- 51: AWS migration hub, --> buat bantu migrasi
- 59: AWS concierge ... ini billing and account expert. 
- 64: flash RTMP

score: 78%

## no 4, retake
100%

## AWS cloud practioner: sample exam 5
wrong answer:
- 2: basic engga punya email support, minimal itu developers
- 7: direct connect .. local region, other region.
- 30: aurora multi master
- 32: multi something, developer case
- 33: store large in dynamo db: compress and put into s3
- 37: EC2 placement group: cluster --> single AZ, 
    - spread : ditaruh di beberapa hardware
- 38 : IAM role in EC2, susah di configure, easier to manage. secure
- 39 : elastic beanstalk dari git sampai deploy
- 46: scale automatically -> s3, dynamoDB
- 50: amazon lightsail : mysql, private server, HA, load balancing
- 55: inter region vpc peering
- 59: costum metric , memory utilization

result: 81 %

## AWS cloud prac: sample exam 6
- 2: scaling: simple, schedule, dynamic, step
- 11: reosurce group, using tags
- 16: inspector, installed di VM
- 30: kinesis: store is S3 and dynamoDB

notes:
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
- aws artifact: for compliance based
- aws machine learning:
    - transcribe : speech to text
    - comprehend: text analysis using NLP. 
    - sagemaker: deploy machine learning at any scale
    - rekognition: analysis on video and images
- instance store are not persistent
- aws inspector: automatic, security for compliance
- VPC wizard:
    - one public subnet
    - vpc public-private subnet
    - vpc public-private subnet with VPN hardware
    - vpc private with VPN hardware
- storage gateway: hybrid between on prem and cloud
- route 53:
    - DNS
    - traffice flow
    - domain registration
    - health check and failover
- EBS encryption: non root at boot time sama root kalau dari AMI
- NAT gateway scalable, sama ga perlu dimanage by you
- RDS point in time, with granularity of 5 minutes
- Application load balancer, cuma bisa http sama https
- expedited, AWS glacier


## notes on EC2
- default security group, instance associated with default security group.
- EC2 Scaling group.





