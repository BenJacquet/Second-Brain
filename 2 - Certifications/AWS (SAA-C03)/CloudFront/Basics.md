
CloudFront -> Create Distribution

CloudFront is a CDN (Content Delivery Network)

Provides:
- Improved read performance by caching content at edge locations
- Improved user experience
- High reliability and availability with 216 points of presence globally (edge locations)
-  protection because the app becomes worldwide and can be integrated with Shield and AWS Web Application Firewall

Can have many origins:
- S3 bucket:
	- Improved security with CloudFront Origin Access Control
	- Can be used as an ingress (to send data **towards** the S3 bucket)
- Custom Origin (HTTP):
	- Application Load Balancer
	- EC2 Instance
	- S3 Website
	- Any HTTP backend

CloudFront:
- Global edge network
- Files cached for a TTL (Time To Live)
- Great for static content that must be available everywhere

VS

S3 Storage Replication:
- Must be setup for each region
- Near real-time file upload
- Read Only
- Great for dynamic content that needs to be available at low-latency in a few regions
  
![[Capture d’écran 2023-08-02 à 23.20.13.png]]