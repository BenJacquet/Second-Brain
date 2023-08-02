
Layer 4 (TCP/UDP) manipulation

Handles millions of requests per second

100ms latency (vs 400 for ALB)

NLB has one static IP per AZ and supports Elastic IP

Target groups can be:
- EC2 instances
- Private IP adresses
- Application Load Balancer

The health checks support the TCP/HTTP and HTTPS protocols