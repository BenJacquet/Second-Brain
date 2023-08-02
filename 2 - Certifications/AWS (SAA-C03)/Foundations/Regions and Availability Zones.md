
AWS hosts its data centers in areas called regions, which have several availability zones.
Each AWS region is composed of a geographic name and a region code, for example:
![[Capture d’écran 2023-05-15 à 14.15.40.png]]
In this case, this region was the third Western Europe to be created.

**AWS Regions are independent from each other, the data is not replicated unless the user's explicit consent.**

## Choosing the right region

In order to choose the right region you need to consider 4 aspects:
- Latency
- Cost
- Services Availablity
- Data Conformity

## Availability Zone (AZ)

![[Capture d’écran 2023-05-15 à 14.22.09.png]]

Each region is composed of a cluster of AZs.
An AZ consists of an power supply, networks and redundant connectivity.

As they are located inside regions, they can be named by adding a letter after a region code:
**eu-west-3a**
It is highly suggested to have replicas across at least two different AZs to increase fault tolerance.

To check which services are available in a region, we can use [Regional Product Services](https://aws.amazon.com/fr/about-aws/global-infrastructure/regional-product-services/?p=ngi&loc=4).

