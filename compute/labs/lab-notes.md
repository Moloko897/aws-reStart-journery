# Compute Lab: Introduction to Amazon EC2

## Objective
Learn how to do basic overview of launching, resizing, managing, and monitoring an Amazon EC2 instance.

## Steps Taken
Launch a web server with termination protection enabled

Monitor my EC2 instance

Modify the security group that my web server is using to allow HTTP access

Resize my Amazon EC2 instance to scale

Test termination protection

Terminate my EC2 instance

## Challenges
- Forgot to open port 22 in the security group
- Solved by editing the inbound rules

## Screenshot
successfully Launched a web server with termination protection enabled
![launched instance](https://github.com/user-attachments/assets/502ddf9e-2248-4dc9-886d-4f97a60122e1)

Modify the security group that my web server is using to allow HTTP access
![security group added](https://github.com/user-attachments/assets/ad3a3611-ddfa-4ed3-a802-3c3c34a4cdd9)

used the below script to: Install an Apache web server (httpd),
Configure the web server to automatically start on boot,
Activate the Web server and
Create a simple web page

#!/bin/bash
yum -y install httpd
systemctl enable httpd
systemctl start httpd
echo '<html><h1>Hello From Your Web Server!</h1></html>' > /var/www/html/index.html

OUTPUT
![output](https://github.com/user-attachments/assets/e4780f9f-00e7-468a-bf63-979ee307ee12)

 Monitoring
 instance status monitoring, I can quickly determine whether Amazon EC2 has detected any problems that might prevent my instances from running applications. Amazon EC2 performs automated checks on every running EC2 instance to identify hardware and software issues.
![monitoring](https://github.com/user-attachments/assets/ef2d571c-ea3a-499c-9d3c-2ac466bf4696)

You can delete your instance when you no longer need it.
You cannot connect to or restart an instance after it has been terminated.
Successfully Terminated an instance.
![intance terminated](https://github.com/user-attachments/assets/c3c8413c-1236-45af-afc8-3b0a31d6b65c)

Intance Details
![instance details](https://github.com/user-attachments/assets/28d48888-88a8-41f5-a503-4921681b8035)


## Takeaways
Security groups work like firewalls. Always make sure the required ports are open.
