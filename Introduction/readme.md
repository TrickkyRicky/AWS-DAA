### What's AWS

- Aws is cloud provider that provides servers and services you can use on demand and scale easily

### Some use cases

- Enterprise IT
- Backup and storage
- Big data analytics
- Website hosting
- Mobile and social apps
- Gaming, etc.

### Global Infrastructure

[Check this map for more](https://aws.amazon.com/about-aws/global-infrastructure/regions_az/)

- Aws Regions
- Aws availbility Zones
- Aws Data Centers
- Aws Edge Locations / Points of Presense

### AWS Regions

- Aws has Regions all around the world with naming such as:
  - us-east-1
  - eu-west-3
- A region is a cluster of data centers
- Most AWS services are region scoped

### How to choose an AWS Region

- Compliance: with data governance and legal requirements
- Proximity: to customers based on that for reduced latency. Ex: My app is used in America so I would choose the US as my region and not the EU, because I would lag due to the extended range
- Available Services within a Region: new services and features aren't available in every region
- Pricing: Pricing varies region to region and is transparent in the service pricing range

### AWS Availability Zones

- Each region has many availability zones, usually 3 this being the min and a max of 6
  - Example: ap-southeast-2a, ap-southeast-2b, ap-southeast-2c
- Each Availability zone will have one or more discrete data centers with less power, networking and connectivity
- Since the zones are seperate it can prevent code disasters since the zones are isolated
- The data centers are conntected with bandwidth and low latency

### AWS Console and Services

- Some services require global services and some don't for example route 53 vs Ec2 and the view can change based on that region
