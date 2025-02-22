## Sumo Logic Security Integrations on AWS—Quick Start

Sumo Logic is focused on continuous intelligence, a new category of software that addresses data challenges presented by digital transformations, modern applications, and cloud computing. The Sumo Logic Continuous Intelligence Platform automates the collection, ingestion, and analysis of applications, infrastructure, security, and Internet of Things (IoT) data to derive actionable insights.

Similar to security information and event management (SIEM) software, Sumo Logic uses apps to collect security events generated by AWS and other security services to provide an aggregate view of overall security and compliance posture. A Sumo Logic app is a collection of dashboards in the Sumo Logic console that provide analytics for known data streams. In minutes, you can start monitoring and troubleshooting security threats and indicators of compromise.

### Sumo Logic on AWS
Sumo Logic has apps for each AWS security service (for example, AWS CloudTrail) that it supports in addition to apps that support multiple AWS services (for example, Threat Intel for AWS). This Quick Start deployment is for those who want to set up and configure the Sumo Logic console for 12 AWS services that provide security analytics.

Sumo Logic customers can track user activity, monitor threats, and understand how their security posture compares with global benchmarks. This deployment uses Virtual Private Cloud Flow Logs (VPC Flow Logs) and a web application firewall (AWS WAF) to monitor traffic patterns. Sumo Logic also uses apps to audit and maintain compliance of the Payment Card Industry (PCI) Data Security Standard (DSS) and Center for Internet Security (CIS).

The included template automatically creates resources that use various AWS services to collect logs, which are sent to your preregistered Sumo Logic account.

### Pricing
You are responsible for the cost of the AWS services used while running this Quick Start reference deployment. There is no additional cost for using the Quick Start. For Sumo Logic pricing information, see the [Sumo Logic website](https://www.sumologic.com/pricing/).

This deployment takes approximately 10 minutes to complete. For more information and step-by-step deployment instructions, see the [deployment guide](https://fwd.aws/mpxj9).

### Deployment
This Quick Start deployment builds a new AWS environment consisting of the infrastructure resources required to provision applications to your Sumo Logic account and necessary resources to your AWS account. During the deployment, you can choose which applications to install.

### Architecture
Deploying this Quick Start with **default parameters** builds the following environment in a specific account and Region in the AWS Cloud.
![quickstart-sumo-logic-security-integrations](./docs/images/architecture.png)

For architectural details, best practices, step-by-step instructions, and customization options, see the [deployment guide](https://aws-quickstart.github.io/quickstart-sumo-logic-log-centralization/).

To post feedback, submit feature ideas, or report bugs, use the **Issues** section of this GitHub repo.

To submit code for this Quick Start, see the [AWS Quick Start Contributor's Kit](https://aws-quickstart.github.io/).