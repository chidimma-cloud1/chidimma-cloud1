# AWS Infrastructure, Deployment Models, Shared Responsibility & Pricing

## Overview
Understanding how AWS is structured globally, how cloud can be deployed, who is responsible for security, and how pricing works gives you the foundation to make smart decisions when building on AWS.

## AWS Global Infrastructure

### AWS Regions
AWS operates in multiple geographic regions worldwide. Choosing the right region affects:
Latency: The closer the region to your users, the faster your application responds
Compliance: Some data regulations require data to stay within specific geographic boundaries
Performance: Regional proximity improves the overall user experience

### AWS Edge Network (CDN)
A global Content Delivery Network that caches and delivers content closer to your users, reducing load times and improving security. The edge network is also what gives rise to edge computing. The CDN is essentially a server sitting between the cloud and your end user.

## Cloud Deployment Models

### Public Cloud
Owned and operated by AWS, delivered over the internet. The default model for most businesses; no hardware to buy, no data centres to maintain.

### Private Cloud
A cloud environment dedicated to a single organisation, providing greater control, customization, and security. Often used by organisations with strict regulatory or compliance requirements.

### Hybrid Cloud
A combination of public and private clouds, enabling data and application portability between the two environments.

### Multi-Cloud
Using services from multiple cloud providers, for example, AWS and Microsoft Azure, to avoid vendor lock-in and optimise costs.

## AWS Shared Responsibility Model
Security on AWS is a shared partnership between AWS and the customer.

### AWS is Responsible For (Security OF the Cloud)
- Physical facilities and data centres
- Hardware and network infrastructure
- Core AWS services and software
- Virtualisation and hypervisor layer

### Customer is Responsible For (Security IN the Cloud)
- Customer data
- Applications built on AWS
- Identity and access management
Data encryption and authentication
- Application-level security controls

### Key Principle
Security is a partnership, not one person's responsibility. AWS secures the infrastructure; you secure everything you put on top of it.

## AWS Pricing

### Core Pricing Principles
- Pay only for what you use
- Scale based on demand using Auto Scaling
- No hidden fees, no long-term contracts required
- Continuously optimise cost and efficiency

### AWS Pricing Models

#### On-Demand Instances
Pay for compute capacity by the hour or second with no long-term commitment. Best for unpredictable workloads.

#### Reserved Instances
Commit to a 1 - or 3-year term for a significant discount. Best for steady-state workloads where usage is predictable.

#### Savings Plans
A flexible pricing model that provides savings based on committed usage across regions.

#### Spot Instances
Heavily discounted capacity using AWS's unused server resources. Best for non-critical workloads like training machine learning models or batch processing. Not suitable for serious production workloads.

#### Free Tier
Access to 100+ services for 12 months at no cost ideal for learning and experimentation.

## Key Takeaway
AWS is designed to scale with you in infrastructure, security, and cost. The more you understand these layers, the better equipped you are to build efficiently and securely on the platform.
