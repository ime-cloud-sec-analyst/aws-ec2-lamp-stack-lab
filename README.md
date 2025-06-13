# AWS EC2 LAMP Stack Automation Lab

This project documents a hands-on lab where an EC2 instance was launched and configured to run a LAMP (Linux, Apache, MySQL/MariaDB, PHP) stack using a Bash script and the AWS CLI. This includes detailed troubleshooting and image documentation.

## 📁 Lab Overview

- Launch an EC2 instance using a custom shell script
- Configure VPC, Subnet, and Security Groups
- Troubleshoot AMI ID errors
- Install and configure Apache, MariaDB, and PHP
- Automate user data scripts
- Validate LAMP stack setup with a sample web application

## 🧰 Tools & Technologies

- **Amazon EC2**
- **AWS CLI**
- **Amazon Linux 2**
- **Bash scripting**
- **Git & GitHub**

## 📝 Files Included

- `create-lamp-instance-v2.sh` - main automation script
- `create-lamp-instance-userdata-v2.txt` - LAMP setup script
- Screenshots of each step and errors encountered
- AMI ID troubleshooting results
- Final configuration summary

## 🛠 Troubleshooting Highlight

- Handled `InvalidAMIID.NotFound` errors due to incorrect region or outdated AMI ID.
- Implemented dynamic AMI ID retrieval using `aws ssm get-parameters`.
- Automated deletion and recreation of security groups when needed.

## ✅ Outcome

Successfully demonstrated the deployment of a LAMP stack on an Amazon EC2 instance using a fully scripted and automated process, including manual troubleshooting, error handling, and environment validation.

## 📷 Screenshot Previews

Screenshots are available in this repository for each of the following:

- CLI connection
- Script execution
- AMI ID errors
- Security group issues
- Final deployment confirmation

---

### Author: Ime Ben  
📧 Contact: [imegcu55@gmail.com](mailto:imegcu55@gmail.com)  
🌐 GitHub: [@ime-cloud-sec-analyst](https://github.com/ime-cloud-sec-analyst)
