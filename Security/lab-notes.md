# Security concepts: IAM Lab

## Objective
using IAm to provide work permissions to engineers by using group settings and least privilege principle.

## Steps Taken

create user group called support engineers to manage permissions for a collection of users in an organization.

Attach the AmazonEC2ReadOnlyAccess policy to the Support Engineer IAM group.

Create new user accounts and assign them to the Support Engineer group.

Test the termination option using an account with read-only permissions to validate access control.

Attach a new policy to the engineer group to assign Termination Permissions.

Use the IAM Policy Simulator to test whether the user can terminate instances.

## Challenges

- Policy syntax errors or omission of "Effect": "Allow" can cause silent failures.

- Resources like AMIs or EC2 instances not existing in the region you're testing in,
leading to frustrating errors like InvalidAMIID.NotFound

## Screenshot
create user group called support engineers to manage permissions for a collection of users in an organization
![(iam) user group created](https://github.com/user-attachments/assets/870effa7-a105-43c1-a456-8063a2502bb1)

![step2](https://github.com/user-attachments/assets/9b37d35e-8fc8-4bef-8c08-0156bdeac6bf)

Create new user accounts and assign them to the Support Engineer group
![(iam) user created](https://github.com/user-attachments/assets/e0a79edf-227f-4083-80e7-b2bed8be6f69) 

![step4](https://github.com/user-attachments/assets/0ad0961f-7a4f-467f-a85a-7b3b9fafdf79)

Test the termination option using an account with read-only permissions to validate access control.
![terminating instance (iam)](https://github.com/user-attachments/assets/b320ce81-f432-4e65-ad8b-e04722bf63f5)

validation returns an error due to policy restrictions
![(IAM) validatio![Uploading step2.jpg…]()
n](https://github.com/user-attachments/assets/7554318b-7d2d-4d9f-a44b-9cfe56b55a70)

Attach a new policy to the engineer group to assign Termination Permissions.
![policy attached(solution)(iam)](https://github.com/user-attachments/assets/480aebe9-2b41-45c7-aea1-35675a2c667b)

validation successful
![validation complete](https://github.com/user-attachments/assets/bcd6f7a6-6136-44db-9d22-2c8d430ae5b0)
