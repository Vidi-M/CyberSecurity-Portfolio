# Gophish Phishing Framework Project

## Overview
This project demonstrates the practical application of a phishing framework, Gophish, for simulating phishing attacks. The purpose is to enhance understanding of phishing mechanisms and develop countermeasures against such attacks. It is strictly for educational purposes and ethical use.

## Skills Used and Learned
- **Web Development**: Leveraging HTML to create phishing landing pages and modifying them for specific use cases.
- **Network Configuration**: Setting up and managing security groups, inbound traffic rules, and network settings in AWS.
- **Cloud Computing**: Deploying and configuring virtual machines on AWS EC2 for hosting Gophish.
- **Command-Line Proficiency**: Using Linux commands for downloading, configuring, and running software tools.
- **Email Campaign Management**: Crafting and managing email templates, integrating SMTP servers, and utilizing tracking features.
- **Cybersecurity Awareness**: Understanding phishing tactics and preventive measures.
- **API Utilization**: Exploring REST API functionality provided by Gophish for automation and integration.
- **Data Handling**: Importing and managing email lists using CSV files for campaign targeting.

## Features
1. **Landing Page Creation**: Importing and customizing web pages for phishing campaigns.
2. **Email Template Management**: Designing phishing emails with dynamic variables and tracking images.
3. **SMTP Integration**: Configuring third-party SMTP servers for email delivery.
4. **Campaign Management**: Monitoring real-time statistics like emails sent, opened, clicked, and data captured.
5. **AWS Deployment**: Using the Gophish AMI from the AWS Marketplace to deploy a pre-configured instance.

## Installation and Usage
1. Navigate to the AWS Marketplace and search for the Gophish AMI (Amazon Machine Image).
2. Launch an EC2 instance using the Gophish AMI, ensuring that the instance type meets your requirements.
3. Configure security groups to allow necessary traffic:
   - Allow HTTP and HTTPS traffic for the phishing server.
   - Allow access to the admin panel on its specified port (e.g., 3333).
4. Retrieve the default admin credentials from the EC2 instance details and log in to the Gophish admin panel using the instance's public IP and the configured port.
5. Create email templates, landing pages, and recipient groups in Gophish.
6. Launch a phishing campaign and monitor the results.

## Ethical Disclaimer
This project is intended solely for ethical and educational purposes. Unauthorized use of phishing tools can lead to legal consequences. Always ensure you have permission before conducting any simulations.

## Contact
For any queries or discussions, feel free to reach out via email or LinkedIn.

---
**Note**: This README serves as both a guide to the project and a showcase of the skills developed during its execution.
