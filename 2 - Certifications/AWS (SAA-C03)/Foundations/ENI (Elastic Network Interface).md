
Logical Component of an VPC that represents a **virtual Network Card**.
It can have:
- One mac address
- One Primary Private IPv4 Address
- One or more Secondary Private IPv4 Address
- One Public IPv4 Address
- One Elastic IPv4 per Private IP
- One or more Security Groups

You can create an ENI independently and attach it to a running EC instance.

It is bound to a specific AZ.

To understand better:
https://aws.amazon.com/fr/blogs/aws/new-elastic-network-interfaces-in-the-virtual-private-cloud/

