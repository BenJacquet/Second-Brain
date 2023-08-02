
It redirects traffic to multiple applications / Target Groups at layer 7 (HTTP)

ALBs can route traffic to different Target Groups based on URL Path, Hostname, HTTP Headers, and Query Strings.

Health checks are at the target group level

You get a fixed hostname with your ALB (xxx.region.elb.amazonaws.com)
The application servers don't see the IP of the client directly

Target Group:
- EC2 Instances
- ECS Tasks
- Lambda Functions
- Private IP Addresses