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

![status check passed](https://github.com/user-attachments/assets/09a14847-f791-42b0-b6c1-52bb4800b7f1)
![security group added](https://github.com/user-attachments/assets/ad3a3611-ddfa-4ed3-a802-3c3c34a4cdd9)
![output](https://github.com/user-attachments/assets/e4780f9f-00e7-468a-bf63-979ee307ee12)
![monitoring](https://github.com/user-attachments/assets/ef2d571c-ea3a-499c-9d3c-2ac466bf4696)
![launched instance](https://github.com/user-attachments/assets/502ddf9e-2248-4dc9-886d-4f97a60122e1)
![intance terminated](https://github.com/user-attachments/assets/c3c8413c-1236-45af-afc8-3b0a31d6b65c)
![instance details](https://github.com/user-attachments/assets/28d48888-88a8-41f5-a503-4921681b8035)


## Takeaways
Security groups work like firewalls. Always make sure the required ports are open.
