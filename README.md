# Cloud-Technology-for-Business- B9MG119


## 1. Primary Objective
The primary objective of this project is to develop a comprehensive cloud strategy for BookShow, one of the leading online ticketing platforms. BookShow currently manages its IT infrastructure, including hardware, software, and on-site. Our approach aims to transition from the current on-premises model to a cloud-based solution to enhance operational efficiency and overall business performance. To help drive this transformation, we will outline a detailed cloud strategy and a sample deployment plan.

## 2. Background of the Enterprise
BookShow is a prominent entertainment company known for its leading Online Ticketing Platform, catering to various events including movies, plays, concerts, and sporting events. In addition to ticketing, BookShow offers an online media streaming service and comprehensive management solutions for both virtual and on-ground entertainment experiences, covering all genres. The core operation of BookShow revolves around its online platform, which facilitates the booking of tickets for various entertainment events, with a primary focus on movies.

2.1 Size of the Business
BookShow is a medium-sized enterprise with a total of approximately 33 employees. The workforce is structured as follows:

IT Management:
- 2 IT Managers
  
Network and Systems Administration:
- 2 Network Administrators - 4 Systems Administrators
  
Development Team:
- 4 Backend Developers - 4 Frontend Developers
  
IT Support and Maintenance:
- 3 IT Support Specialists - 4 Help Desk Technicians
  
Cloud and Database Management:
- 1 Cloud Engineer
- 2 Cloud Solutions Architects - 2 Database Administrators
Project and Security Management:
  
- 1 Scrum Master
- 3 Security Specialists - 1 IT Project Manager
  
## 3. Current IT setup

Let's delve into the detailed IT infrastructure of BookShow, covering aspects of hardware, software, and on-site management.

3.1 Hardware

On-premises Servers:

BookShow’s IT infrastructure includes several key components. The web servers host the website and application, handling user inquiries, ticket bookings, and providing web content, typically using software like Apache and Nginx. The database servers are dedicated to storing and managing transactional data, customer information, and event details, utilizing relational database management systems like SQL Server or PostgreSQL. Media servers are employed for streaming media content and storing large media files. Backup servers ensure critical data backup and data availability during power outages. In addition to other features, hardware load balancers are utilized to ensure that web traffic is evenly distributed to web servers, resulting in high availability and reliability.

3.2 Software

Operating Systems:

The operating systems primarily used are Linux servers, such as Ubuntu and CentOS, chosen for their reliability and security, and deployed across web, database, and media servers. BookShow utilizes several key applications and services to ensure smooth operations. A custom ticketing platform is specialized software that manages ticket bookings, user profiles, financial transactions, and event organization. CRM (Customer Relationship Management) will manage interactions with customers, sales, and support (ProInfluent, n.d.). Content management system 'CMS', manages website content management, promotions, and advertising (Kinsta, n.d.). Integration of APIs and services with multiple payment gateways to support online transactions. Additionally, Server health and performance are monitored using monitoring tools like Nagios and Zabbix (Nagios, n.d.; Zabbix, n.d.).

3.3 Internet Connectivity and Network Hardware:

BookShow ensures robust internet connectivity with high-bandwidth connections to handle large volumes of user traffic. Additionally, switches and routers are employed to maintain seamless internal and external network connectivity.
 
3.4 Security Components:

BookShow implements a range of security measures to secure its infrastructure.
. Network traffic is monitored by an intrusion detection system “IDS” and an “intrusion prevention system” IPS to detect suspicious activity and prevent potential attacks (Okta, n.d.). Additionally, measures are taken to mitigate the impact of Distributed Denial of Service (DDoS) attacks to ensure
continuous service availability.

3.5 Power and Cooling:

BookShow uses an UPS as a backup power, to ensure the server remains functional during a power outage. Additionally, a cooling system is applied to maintain optimal operating temperatures for servers and network devices.

4. On-Site Management and Maintenance
   
4.1 IT Staff and Support Team
BookShow's IT department comprises specialized roles responsible for maintaining and supporting critical infrastructure and services. System Administrators oversee servers, storage systems, and network equipment, ensuring their smooth operation and reliability. Database administrators manage database servers, focusing on data integrity and performance optimization. Network administrators are responsible for managing network connections as well as implementing security measures to protect the network infrastructure. Also, dedicated support staff provide technical support to end-users, ensuring efficient use of IT resources throughout the organization.

4.2 Monitoring

BookShow employs both manual monitoring by IT staff and automated monitoring tools such as Nagios and Zabbix to ensure optimal server and network performance (Nagios, n.d.; Zabbix, n.d.). IT staff conduct regular checks to monitor system health and address any issues promptly.

4.3 Maintenance

BookShow prioritizes regular updates and patching of software and firmware to maintain security and optimize performance. Additionally, they conduct routine hardware maintenance, including checks and replacements for aging components, ensuring that their infrastructure remains reliable and efficient. These practices contribute to the overall stability and security of BookShow's IT environment.

A hardware
 firewall is implemented to safeguard the system from external cyber threats, while a software
 firewall is employed to defend the network from unauthorized access
     
 ## 6. Current IT Challenges
Using the IT infrastructure as a guide, let's sum up the company's challenges:

5.1 High Capital Expenditures (CapEx):

BookShow faces significant capital expenditures primarily due to several factors. These include the continuous costs of purchasing and maintaining the physical servers and network equipment. Also, there are significant initial expenses related to acquiring hardware and software licenses. Moreover, the regular replacement and upgrading of these assets add to the company's overall capital expenditure. Investing in these is crucial to maintain and improve BookShow's IT infrastructure.

5.2 Operational Expenses (OpEx):

BookShow incurs operational expenses related to various aspects of its IT infrastructure. This includes costs associated with power, cooling systems, and physical space required to house servers and networking equipment. Additionally, operational expenses cover the ongoing maintenance and management of hardware components. Furthermore, BookShow allocates resources for IT staff responsible for the day-to-day management and maintenance of servers, ensuring smooth operation and reliability of its IT environment. These operational expenditures are crucial for supporting the continuous functionality and efficiency of BookShow's technology infrastructure.
  
5.3 Scalability Problems:

BookShow encounters scalability challenges manifested in two primary issues. Firstly, the company struggles to swiftly add resources to manage surges in demand for significant events or releases. This limitation hinders their ability to efficiently accommodate peak traffic periods. Secondly, in anticipation of peak loads, BookShow tends to over-provision resources, resulting in unnecessary resource allocation and wastage during off-peak periods. These scalability issues highlight the need for a more flexible and efficient resource management approach to better meet fluctuating demand while optimizing resource utilization.

5.4 Frequent Downtime:

The current on-premises servers often fail, particularly during peak hours or when there's a surge in demand for popular events. The company is frequently experiencing downtime because its servers cannot handle high traffic volumes. This persistent issue negatively impacts customer satisfaction, causing users to encounter payment interruptions and poor loading times when accessing the website. Consequently, the platform's reliability and overall user experience suffer, potentially leading to customer loss and a decline in trust and reputation.

5.5 Security Threats:

Businesses encounter a major difficulty in keeping security patches and updates up to date because of the expensive allocation of resources. Consequently, the system becomes open to unauthorized access and various cyber threats, leading to potential data breaches and security risks.

5.6 Disaster recovery and redundancy

5.7 Performance and Monitoring

Server outages or poor performance may go unnoticed for extended periods of time if the monitoring system fails to provide proactive notifications or real-time insights. This could lead to customer annoyance and lost revenue due to the inability to purchase tickets. A non-scalable monitoring system may be overwhelmed by a sudden increase in traffic during well-attended events, resulting in platform slowness or crashes, unpleasant user experiences, and lost revenue as potential buyers abandon their purchases.

6. Impact on Business and Revenue Loss

Revenue from ticket sales decreases when there are problems with downtime and performance, particularly during busy times. The company deals with higher expenses because of large capital and operational costs, which affects its financial situation and profit. Customers lose trust and loyalty when there is regular downtime and an unsatisfactory user experience on the platform. The company's ineffective IT infrastructure puts it at a disadvantage compared to its competitors.

To address these challenges and enhance operational efficiency, we will adopt a strategic approach using cloud services, specifically AWS (Amazon Web Services) technology. This initiative aims to effectively resolve our existing issues and drive significant improvements.
Let's take a brief look at what is cloud computing and its benefits, including AWS, and discuss the specific AWS services we intend to implement in this project

7. Cloud Computing
  Cloud computing involves providing computing services such as servers, storage, databases, networking, software, analytics, and intelligence via the Internet ("the cloud") in order to allow for quicker innovation, adaptable resources, and cost-effectiveness. You usually only pay for the cloud services that you utilize, which can reduce your operational expenses, enhance the efficiency of your infrastructure, and adapt as your business requirements evolve (Microsoft Azure, n.d.).

7.1 Benefits of Cloud Computing
1. Cost Efficiency: Cuts expenses on hardware, software, and data centers; reduces power and cooling costs; minimizes IT management requirements.
2. Speed: Facilitates fast, on-demand resource allocation; enhances business agility and capacity planning.
3. Worldwide Reach: Allows for flexible scaling of resources from ideal geographic locations as required.
4. Efficiency: Reduces time spent on hardware setup and maintenance, enabling IT teams to focus on primary business objectives.
5. Performance: Functions on a secure global network of updated data centers, minimizing latency and benefiting from economies of scale.
6. Dependability: Simplifies data backup, disaster recovery, and business continuity through multiple redundant sites.
7. Safety: Reinforces overall security posture with comprehensive policies, technologies, and controls (Microsoft Azure, n.d.).

7.2.1 What is AWS EC2?

Amazon Web Services (AWS) offers IT infrastructure services to businesses as web services now commonly known as cloud computing. Amazon Web Services provides a wide range of cloud-based products worldwide. These include various services such as computing, storage, databases, analytics, networking, mobile, developer tools, management tools, IoT, security, and enterprise applications. Users can access these services on demand, in seconds, and with pay-as-you-go pricing. AWS offers over 200 services, covering areas such as data warehousing, deployment tools, directories, and content delivery. Presently, AWS supports a dependable, scalable, and cost-effective cloud infrastructure platform that serves numerous businesses across 190 countries (Amazon Web Services, n.d.).

7.2 Amazon Web Services:

 Amazon Elastic Compute Cloud (Amazon EC2) is a service provided by Amazon Web Services (AWS) that offers flexible and scalable computing capacity. It helps in minimizing hardware expenses and enables quick development and deployment of applications. Amazon EC2 allows users to launch and manage virtual servers according to their requirements, and adjust capacity to handle varying workloads. Moreover, an EC2 instance refers to a virtual server in the AWS Cloud, with specific hardware configurations based on the chosen instance type (Amazon Web Services, n.d.).

 ![image](https://github.com/Ashokrawal/Cloud-Technology-for-Business/assets/169262551/461f4799-1ef7-4cb0-a298-3f25a33c6994)
 Fig 1: AWS EC2
 
 7.2.2 What is AWS CloudWatch?
 
Amazon CloudWatch provides real-time monitoring for your Amazon Web Services (AWS) resources and applications. You can track and collect metrics, which are measurable variables, and create custom dashboards to display them. Additionally, you can set up alarms and receive notifications or automate actions when certain thresholds are reached. This helps you gain insight into resource utilization, application performance, and operational health (Amazon Web Services, n.d.).

8. Recommended Solutions 8.1 Aspect 1: Web Hosting

Amazon CloudWatch provides real-time monitoring for your Amazon Web Services (AWS) resources and applications. You can track and collect metrics, which are measurable variables, and create custom dashboards to display them. Additionally, you can set up alarms and receive notifications or automate actions when certain thresholds are reached. This helps you gain insight into resource utilization, application performance, and operational health (Amazon Web Services, n.d.).  
         ![image](https://github.com/Ashokrawal/Cloud-Technology-for-Business/assets/169262551/0e271edb-2cca-4717-a9e1-2dc7fb1b9d85)
                                        Fig 2: AWS CloudWatch
   
  Comparative Analysis
  Features
   AWS EC2
   On-premises servers
   Cost Efficiency
 AWS EC2 operates on a pay-as-you- go model, where costs are proportional to actual usage. This eliminates the need for large upfront investments , thereby reducing capital expenditure and optimizing operating expenses.
   Involve significant CapEx for hardware, software licenses, and ongoing maintenance, contributing to high operational costs.
   Management and Maintenance
 Managing the server is made easier with AWS EC2, which includes features such as backup, monitoring, and automatic scaling. By doing this, IT teams can focus on strategic initiatives and reduce the operational stress associated with maintenance tasks.
   Servers located on-premises require manual handling of hardware upgrades, software updates, and problem-solving, which can consume a lot of time and resources, leading to difficulties in monitoring performance and maintenance.
   Scalability and Flexibility
AWS EC2 offers dynamic scalability, allowing resources to be easily scaled up or down based on demand. This flexibility is crucial during peak ticketing periods, ensuring that BookShow can handle sudden spikes in traffic without downtime or performance issues.
  On-premises servers need careful planning and initial investment for capacity, which can lead to over- provisioning when there is less demand and potential resource limitations during busy periods (Hewlett Packard Enterprise, n.d.).
   Reliability and Availability
 AWS EC2 allows for high availability and reliability by incorporating multi- region redundancy and automatic failover, which reduces the chances of hardware failure or maintenance- related downtime.
   Local infrastructure is critical for on-premises servers, and there may be a need for extra investments in redundancy and disaster recovery solutions to attain comparable levels of availability.
   Security and Compliance
  AWS EC2 provides strong security features and compliance certifications, such as encryption, and routine security audits, to help comply with industry regulations and
    On-premises servers provide direct control over security measures but require extensive expertise and resources to maintain security patches and updates consistently (Lucidchart, n.d.).
 
   safeguard sensitive customer data effectively (AWS, n.d.).
8.1.1 Recommendation: AWS Elastic Compute Cloud
8.1.2 Justification: AWS EC2 is recommended for BookShow due to its flexible scalability, pay-as-you-go model, high availability, and strong security. These features enable BookShow to enhance service reliability, optimize costs, and maintain high-security measures, making AWS EC2 the superior choice for supporting their online ticketing platform's performance and growth.
8.2 Aspect 2: Monitoring System
To address the challenge of slow response to server issues and lack of real-time insights, we can implement AWS CloudWatch. Traditional monitoring tools may not check systems often enough, which could cause delays in identifying serious server slowdowns or errors. This can lead to a poor customer experience, especially during busy ticketing periods. For example, they could fail to notice unexpected increases in CPU usage or memory issues until the next planned inspection, affecting the booking process and causing frustration to customers due to slow response times or transaction failures. Let's compare AWS Cloudwatch with a traditional monitoring system.
      Comparative Analysis
  Features
   AWS CloudWatch
   Traditional monitoring system (Nagios, Zabbix)
   Automation and Scalability
 AWS CloudWatch provides the ability to automatically adjust the capacity of resources according to specific measurements and limits. This could involve tasks such as modifying the size of EC2 instances and is essential for managing fluctuations in demand and improving the efficient use of resources.
   Usually, they use manual setup and scripting to scale or automate actions. They may lack built-in support for cloud-based services or auto-scaling features without making additional customizations.
   Metrics and Dashboards
Provides built-in metrics and customizable dashboards that offer real-time visibility into performance metrics such as CPU utilization, memory usage, and network traffic. These dashboards can be tailored to display key metrics relevant to BookShow-specific applications and services.
   Require more manual setup to configure dashboards and collect metrics from various servers and applications. They may not offer as extensive or integrated dashboard capabilities.
 
   Alerting and Notifications
  Enables customizable alerts based on predefined thresholds for metrics. It can send notifications via email, and SMS, or trigger automated actions through AWS services like SNS (Simple Notification Service). This ensures timely responses to performance issues or anomalies.
    Offer alerting capabilities but may require more manual setup for defining alerts and integrating with external notification systems. They may lack seamless integration with AWS services for automated responses.
   Integration and Security Compliance
AWS CloudWatch effectively automates the process of ensuring security settings compliance by integrating closely with various AWS services. This service is managed, offering strong security management for scalable cloud environments without incurring high operational expenses.
  Conventional monitoring tools often need manual setup and don't integrate smoothly with cloud services, leading to scaling problems and higher maintenance expenses. They often need users to handle security updates on their own and may not be able to match the speed and automation of cloud- native solutions like CloudWatch.
   Cost Efficiency
 Operates on a pay-as-you-go model, where a company pays for the metrics and logs ingested, along with any additional features used like custom dashboards or enhanced monitoring capabilities. This aligns costs with actual usage and can be more cost- effective for dynamic workloads (AWS, n.d.).
    Often involve upfront costs for licenses and hardware, along with ongoing maintenance expenses. Scaling traditional tools to accommodate growth or sudden increases in monitoring requirements may incur additional costs and resource allocation.
 8.2.1 Recommendation: AWS CloudWatch
8.2.2 Justification: AWS CloudWatch is recommended for BookShow due to its seamless integration with AWS services, automation capabilities, comprehensive metrics, and alerting features. It simplifies monitoring operations, provides real-time insights, and optimizes cost- effectiveness, which is crucial for meeting the dynamic demands of an online ticketing platform.
9. Detail of the Costs
Let’s estimate the monthly spent on the current IT setup.
 
9.1
On-Premises cost
•
1. 2. • 3. 4.
9.2 AWS Costs
• Estimated Monthly Costs on Cloud services which includes AWS EC2 and AWS CloudWatch: Approximately $1,090.39 per month and $13,084 Per Annum.
Capital Expenditures (CapEx): CapEx refers to the one-time costs associated with acquiring physical assets.
Let’s assume the total CapEX, covering physical Servers, network equipment, storage device, backup system, and load balancer, is approximately $72,000.
The total Software costs, including Operating system, Software, and database licenses, and other software applications, amount to around $20,000.
Operational Expenditures (OpEx): OpEx refers to the recurring costs for maintaining and operating the assets.
The total OpEx cost of IT staff salaries, maintenance, and power & cooling is approximately $75,000 per year.
Total cost including CapEx (One-time) +OpEx (annually) = $92,000+$75,000=
$1,67,000.
 • Cost Comparison Table:
CapEx (One-time) Software (One-time) OpEx (Annual) AWS EC2
AWS CloudWatch Total
Fig 1: AWS Pricing Calculator
$72,000 N/A $20,000 N/A $75,000 N/A
N/A $8,723.28 N/A $4,361.40 $1,67,000 $13,084.68
  Category
   On-Premises Cost
   AWS COST
                   
Moving from local infrastructure to AWS can result in around an 82.55% yearly cost reduction for online ticketing platforms such as BookShow. This significant decrease in operational costs emphasizes the financial advantages of using AWS for such platforms.
9.3 Options for Backup
• AWS Backup: AWS provides automated backup options.
• Note: AWS backup pricing service is temporarily disabled
Fig 2: AWS Backup Pricing calculator
9.4 Monitoring and Management
• AWS CloudWatch: AWS provides real-time monitoring system.
• Estimated Monthly Costs on Cloud services which includes AWS CloudWatch is
Approximately $363.45 per month and $4,361.40 Per Annum.
  
Fig 3: AWS CloudWatch pricing calculator
10. Sample Cloud Infrastructure Deployment
Let's outline and deploy a sample cloud infrastructure using AWS EC2 and CloudWatch,
aligning with our recommendations.
10.1 Pre-requisite
1. Ensure you have an AWS account setup. https://signin.aws.amazon.com/.
2. Install and configure the AWS Command Line Interface on the local machine.
(
)
10.2 Steps to be Followed
1. Launch a new EC2 instance for hosting the web application.
2. Securely connect to an EC2 instance via SSH using a.pem file.
3. To host the web application, install Apache.
4. Create a basic HTML file to serve.
5. Configure and set up an alarm in CloudWatch through the AWS console.
6. Validating the EC2 HTML page and CloudWatch alert notifications.
Step 1: Launch a new EC2 instance for hosting the web application
▪ Login to the AWS console.
▪ Search for the EC2 service and launch into the EC2 dashboard.
▪ Click on Launch -> Launch instances.
▪ Enter the instance ‘name’.
▪ Choose an Amazon Machine Image (AMI) E.g., Amazon Linux 2 AMI (free tier).
▪ Select an instance type. E.g., t2.micro (eligible for free tier).
▪ Create a new key pair or use an existing key pair. Download and save the .pem file.
▪ In Network settings, enable “Allow SSH traffic from” and “allow HTTP traffic from the
internet” to access “port 22” and “port 80”.
▪ Leave other options as defaults and launch instances.
   The AWS CLI is a tool that allows you to control multiple AWS services from
  the command line

 Fig 1: Launching a new EC2 instances Step 2: Securely connect to an EC2 instance via SSH using a.pem file.
Connecting EC2 via SSH, has direct access to the EC2 operating system, enabling advanced configurations, real-time troubleshooting, automation, and efficient resource management.
▪ Once the EC2 instance is up and running, open your terminal ▪ Navigate to the directory where your `.pem` file is saved
▪ Connect to your EC2 instance using the below command:
ssh -i "your-key-pair.pem" ec2-user@”your-ec2-public-DNS Example: ssh -i TestA.pem ec2-user@54.209.222.78
 
Fig.2: Connecting to EC2 instances via SSH Step 3: To host the web application, install Apache
Installing Apache is to prepare the EC2 instance to handle HTTP/HTTPS requests and serve content to users, which is essential for any web-based application. This allows users to access web pages and web applications hosted on the EC2 instance.
▪ Execute the below commands one by one to install and configure Apache. sudo yum update -y
sudo yum install -y httpd sudo systemctl start httpd sudo systemctl enable httpd
Fig.3: Installing Apache Step 4: Create a basic HTML file to serve
The HTML file provides a basic web page that can be viewed in a user browser, ensuring that the Apache web server is capable of delivering web content to users.
▪ Once Apache is installed, create a simple HTML file. Run the below command. echo "<html><h1>Welcome to BookShow!</h1></html>" | sudo
tee /var/www/html/index.html
▪ Validating Web browser:
To verify your web browser, navigate to http://your-ec2-public-ip. Example: http:// 52.87.221.177
The "Welcome to BookShow! " message should be displayed.
   
 Fig 4: HTML page with Welcome message
Step 5: Configure and set up an alarm in CloudWatch through the AWS console
▪ Go to the AWS Amazon console. Open the Cloud Watch dashboard.
▪ Click on ‘All Alarm’ -> Create Alarm.
▪ Select Metrics. On the following page, Select “EC2“ under the browse tab.
▪ Select “per-instance metrics”. Running instance lists will be displayed.
▪ From the list “CPUUtilization” that we want to monitor. Click on Select Metrics.
▪ On the Metrics and conditions page,
-Period: Select the evaluation period, for example, "5 minutes". This specifies how often -CloudWatch checks the metrics.
-Select the threshold type as “Static”.
-Select “Whenever CPUUtilization is.” as “Greater than or equal to”.
-Threshold: Set a value, for example, "50".This means the alarm will trigger if the
-CPU utilization is 50% or higher.
▪ Click on next to config the alarm (to specify what action to take when the alarm state is
triggered)
-Notification: Select "In alarm"
-Send a notification to: Create a new topic, to receive email/SMS notifications. -Add a name for the SNS topic.
-Add an email address to receive the alert notifications.
-Click on Create Topic and click on next
 
 Fig 5: Configuring notification alert in CloudWatch
▪ In the "Add name and description" page, provide a name for the alarm. (e.g., "High CPU Utilization Alarm") and add a description (optional).
▪ Review the alarm configuration and click on Create alarm.
▪ Confirm the SNS subscription which is received in the configured Email.
Fig 6: CloudWatch Dashboard with configured Alarm Step 6: Validating the CloudWatch alert notifications
▪ Open your terminal. Connecting to your instances install the stress tool (stress tool is utilized to simulate CPU load on an EC2 instance to validate monitoring setups like CloudWatch alarms)
sudo yum install -y stress.
▪ After installing the stress tool, to simulate the CPU usage run the following command. Stress --cpu 4--timeout 300 (Example to stress 4 CPUs for 5 minutes (300 seconds)).
 
▪ Verify the CloudWatch dashboard. Email alert notification should be received for the mentioned email when CPU usage is more than 50%
Fig 7: CloudWatch Dashboard after simulating the CPU usage
Fig 8: SNS Alarm notification when EC2 CPU utilization is more than set threshold.
We have now deployed a simple cloud infrastructure using EC2 and CloudWatch.When the CPU utilization exceeds the specified threshold in the EC2, CloudWatch will trigger the alarm and send a notification via SNS to the specified E-mail recipient. This approach helps ensure you can quickly respond to high CPU usage alerts and maintain the performance of your EC2 instances.
  
10.3 Architectural representation of Sample deployment
▪ The Users accesses the HTML web application hosted on the EC2 instance.
▪ AWS EC2 Instance hosts the web application and Apache web server.
▪ CloudWatch: Monitors the EC2 instance. Checks network traffic /CPU Utilization
and triggers alarms when CPU Utilization reaches the threshold.
▪ SNS Topic: Sends alert notifications (e.g., email) to admin when alarms are triggered.
11. Use of GitHub/GitLab
• GitHub link for the project documentation.
Ashokrawal/Cloud-Technology-for-Business: Module Code: B9MG119 (github.com)
12. Conclusion
Transitioning BookShow's IT infrastructure to AWS cloud services brought significant benefits. It solves today's challenges such as high costs, scalability issues, frequent downtime, security vulnerabilities, and ineffective monitoring. AWS EC2 provides flexible, cost-effective scalability, reliability, and improved security compared to on-premises solutions.AWS CloudWatch provides real-time monitoring and proactive alerting needed to maintain optimal performance. BookShow's strategic transformation not only addresses the problems it currently faces but also meets its growth needs, improving operational efficiency, customer satisfaction, and competitive edge in the market.
    
13. References
• Microsoft Azure, n.d. What is cloud computing? [online] Available at: https://azure.microsoft.com/en-in/resources/cloud-computing-dictionary/what-is-cloud- computing/ [Accessed 29 June 2024].
• Amazon Web Services (2023). AWS Overview. Available at: https://docs.aws.amazon.com/whitepapers/latest/aws-overview/introduction.html (Accessed: 30 June 2024).
• Amazon Web Services (2024). What is Amazon CloudWatch?. Available at: https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch. html (Accessed: 30 June 2024).
• AWS, n.d. Amazon EC2 Features. [online] Available at: https://aws.amazon.com/ec2/features/ [Accessed 29 June 2024].
• AWS, n.d. Amazon EC2 Security. [online] Available at: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-security.html [Accessed 29 June 2024].
• Hewlett Packard Enterprise, n.d. On-premises vs. Cloud. [online] Available at: https://www.hpe.com/us/en/what-is/on-premises-vs-cloud.html [Accessed 29 June 2024].
• Lucidchart, n.d. Cloud vs. On-Premises: Comparison. [online] Available at: https://www.lucidchart.com/blog/cloud-vs-on-premises-comparison [Accessed 29 June 2024].
• AWS, n.d. Amazon CloudWatch Features. [online] Available at: https://aws.amazon.com/cloudwatch/features/ [Accessed 29 June 2024]. (Accessed: 29 June 2024).
• Kinsta. (n.d.). Content Management System (CMS): What It Is and How It Works. Available at: https://kinsta.com/knowledgebase/content-management-system/ (Accessed: 30 June 2024).
• ProInfluent. (n.d.). Customer Relationship Management (CRM). Available at: https://www.proinfluent.com/en/customer-relationship-management/ (Accessed: 30 June 2024).
• Okta. (n.d.). IDS vs IPS: What’s the Difference? Available at: https://www.okta.com/identity-101/ids-vs-ips/ (Accessed: 30 June 2024)
• Nagios (n.d.) Nagios - The Industry Standard in IT Infrastructure Monitoring. Available at: https://www.nagios.org/ (Accessed: 29 June 2024).
• Zabbix (n.d.) Zabbix Monitoring Solution. Available at: https://www.zabbix.com/ (Accessed: 29 June 2024).
• Intro and Demonstration [Video]. YouTube. https://www.youtube.com/watch?v=aXMih9jQIec&t=2s
