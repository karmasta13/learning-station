# Journey of AWS Cloud Practitioner Learning

## Introduction
The AWS Certified Cloud Practitioner is an entry-level certification offered by Amazon Web Services (AWS) that provides individuals with a foundational understanding of cloud computing and AWS services. This certification is designed for professionals new to the cloud and who want to establish a solid knowledge of AWS cloud concepts and basic cloud computing principles.

## Table of Contents
1. [Cloud Concepts](#cloud-concepts)
2. [Security and Compliance (24%)](#security-and-compliance)
3. [Technology (Largest)](#technology)
4. [Billing and Pricing (Smallest)](#billing-and-pricing)

<br>

## Cloud Concepts

### What is Cloud Computing?
Cloud computing is the on-demand delivery of computing, database storage, applications, and other IT resources over the Internet.

### History of Cloud Computing:
1. Mainframe Computing (1950s): Central computer accessed by numerous user devices (dumb terminals).
2. Virtual Machines (1970s): Multiple complete operating systems on a single piece of hardware. Hypervisor is a software layer that lets you run the VMS

### Cloud Computing in Daily Life:
Examples include email services, streaming platforms, outlook.com, and cloud.

### Six Advantages of Cloud Computing:
1. Trade capital expense for variable expense.
2. Benefit from massive economies of scale.
3. Stop guessing about capacity.
4. Increase speed and agility.
5. Stop spending money running and maintaining data centers.
6. Go global in minutes.

### Three Main Cloud Computing Models:
1. SaaS (Software as a Service): Managed by the service provider, easy to use, least flexibility (e.g., Gmail, SalesForce). This is for customers.
2. PaaS (Platform as a Service): Deploy and manage applications without worrying about underlying hardware infrastructure. Less flexible than IaaS (e.g., Microsoft Azure Web Hosting, Heroku, Google App Engine). This is for developers. 
3. IaaS (Infrastructure as a Service): Basic building blocks, most flexibility and management control, closest to traditional on-premises data centers (e.g., Google Cloud, Amazon Web Services). This is for Admins. 

### Cloud Deployment Models:
1. Cloud Deployment/ Public Cloud / Cloud First: 100% of IT infrastructure on the cloud, removes roadblocks of costly procurement process.
2. On-Premises Deployment/ Private Cloud: Uses virtualization in on-premises data centers, security-focused, not much benefit to cloud computing.
3. Hybrid Deployment: Connects on-premises technology with cloud-based resources, suitable for companies in the process of migrating to the cloud.
4. Cross-Cloud: Using Multiple Cloud Providers at the same time. 

### Choosing the Deployment Model:
1. Cloud Deployment: For organizations with few deployed IT resources, seeking flexibility and affordability.
2. On-Premises Deployment: For data that must be secured on-premises.
3. Hybrid Deployment: For companies with legacy IT resources, providing quick access to on-premises resources with cloud backup.

### Well-Architected Framework:
1. Avoid unnecessary costs.
2. Reliability: Test disaster recovery settings, incorporate redundancy.
3. Efficiency.
4. Security: Protect information, system, and assets, enable traceability, manage access.
5. Operational Excellence: Document, refine procedures, anticipate failure, learn from failure.
6. Sustainability: Focus on achieving maximum benefit from provisioned resources to minimize environmental impact.

### What is Cloud Service Provider (CSP)?

A CSP is a company which

- provides multiple Cloud Services e.g tens to hundreds of services
- those Cloud Services can be chained together to create cloud architectures
- those Cloud Services are accessible via Single Unified API eg. AWS API
- those Cloud Services utilized metered billing based on usage e.g. per second, per hour
- those Cloud Services have rich monitoring built in eg. AWS CloudTrail
- those Cloud Services have an Infrastructure as a Service (IaaS) offering
- those Cloud Services offer automation via Infrastructure as Code (IaC)

* If a company offers multiple cloud services under a single UI do not meet most of all these requirements, it would be referred to as a Cloud Platform e.g. Twilio, Databricks *

#### The landscape of CSP consists of three:

1. Tier-1 (Top Tier) - Early to market, wide offering, strong synergies between services, well recognized in the industry. Eg. AWS, Microsoft Azure, Google Cloud Platform (GCP), Alibaba Cloud 
2. Tier-2 (Mid Tier) - Backed by well-known tech companies, slow to innovate and turned to specialization. Eg. IBM cloud, Oracle Cloud, Rackspace(OpenStack)
3. Tier-3 (Light Tier) - Virtual Private Servers (VPS) turned to offer core LaaS offerings. Simple, Cost Effective. Eg. Vultr, DigitalOcean, Linode

<hr>

### AWS - Amazon Web Services

AWS, which stands for Amazon Web Services, is a comprehensive and widely-used cloud computing platform provided by Amazon. It offers an extensive range of cloud services, enabling businesses, organizations, and individuals to access and utilize a variety of computing resources over the internet.

#### Key Points:

- AWS provides IT infrastructure services as web services, offering businesses and organizations scalable solutions to support their growth and efficiency.

- Instead of purchasing hardware like network switches and servers, AWS provides these resources as accessible services through the internet.

- With the pay-as-you-go model of cloud computing and robust resources offered by AWS, organizations can effectively save time, money, and human resources by migrating their operations to the cloud.

Amazon Web Services has revolutionized the way businesses handle their computing needs, making advanced technologies and resources easily accessible to users worldwide. By leveraging the power of AWS, organizations can focus on their core competencies while enjoying the flexibility, scalability, and cost-effectiveness of cloud computing.

Whether it's startups, enterprises, or government agencies, AWS has become a trusted platform for building, deploying, and managing applications and services on a global scale. Its extensive range of services, coupled with continuous innovation and security measures, has made AWS a leading player in the cloud computing industry.

### History of AWS

- **1994**: Founded by Jeff Bezos as an online bookstore, Amazon.com.

- **2002**: Amazon Web Services (AWS) was launched as a subsidiary of Amazon.com, offering web services to provide online access to various functionalities.

- **2004**: SQS (Simple Queue Service) was officially launched, allowing developers to decouple and scale microservices.

- **2006**: AWS was officially launched as a comprehensive cloud computing platform, enabling businesses to access scalable and flexible IT infrastructure services.

- **2006**: The first product of AWS, Amazon S3 (Simple Storage Service), was launched in March. It offered scalable storage solutions for customers to store and retrieve any amount of data from anywhere on the web. Then EC2 (Elastic Compute Cloud) was launched in August

- **2007**: Over 180,000 developers had signed up for AWS, highlighting the growing popularity and adoption of the platform.

- **2010**: Amazon.com retail web services were migrated to AWS, making it a significant milestone as one of the largest and most popular online retailers was now running on AWS infrastructure.

- **2011**: AWS faced some major problems, with parts of the Elastic Block Store (EBS) experiencing issues, impacting the ability to read and write data. The problem took two days to resolve.

- **2012**: AWS hosted its first customer event known as re:Invent conference, where new products and features were launched. During the same year, another major problem occurred, affecting popular sites like Pinterest, Reddit, and Foursquare.

- **2013**: AWS introduced certifications to validate the expertise of software engineers in cloud computing, boosting its reputation as a reliable cloud service provider.

- **2014**: AWS committed to achieving 100% renewable energy usage for its global infrastructure, emphasizing environmental sustainability.

- **2015**: AWS's revenue surpassed $6 billion USD per annum, and its growth rate was an impressive 90% annually.

- **2016**: Revenue doubled and reached $13 billion USD per annum, showcasing AWS's rapid expansion and increasing adoption by businesses worldwide.

- **2017**: AWS re:Invent introduced a host of Artificial Intelligence (AI) services, contributing to a doubled revenue of $27 billion USD per annum. The focus on automating AI and machine learning further strengthened AWS's position in the market.

- **2018**: AWS launched Machine Learning Specialty Certifications, emphasizing the importance of AI and machine learning technologies in its offerings.

Today, AWS is one of the leading cloud service providers globally, serving over 1 million active customers with a vast array of services, including computing power, storage options, machine learning, and more.

The history of AWS highlights its continuous growth, innovation, and commitment to providing scalable, reliable, and cost-effective cloud solutions for businesses of all sizes.










