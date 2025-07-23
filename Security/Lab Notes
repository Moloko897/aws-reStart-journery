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

