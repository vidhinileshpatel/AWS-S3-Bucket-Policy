# How to add a Bucket Policy for S3

A bucket policy is a resource-based AWS Identity and Access Management (IAM) policy. A Bucket Policy is used to grant other AWS accounts or IAM users access permissions for the bucket and its objects. 

# Contents of a Bucket Policy

A Bucket Policy has the following structure: 

{

  "Version":"2012-10-17",

  "Statement":[]
 
 }
 
 The statement comprises of the various actions, permissions, resource location and other necessary information.
 
# Topics
1) Granting Permissions to Multiple Accounts with Added Conditions
2) Granting Read-Only Permission to an Anonymous User
3) Restricting Access to Specific IP Addresses
4) Restricting Access to a Specific HTTP Referrer
5) Granting Permission to an Amazon CloudFront Origin Identity
6) Adding a Bucket Policy to Require MFA
7) Granting Cross-Account Permissions to Upload Objects While Ensuring the Bucket Owner Has Full Control
8) Granting Permissions for Amazon S3 Inventory and Amazon S3 Analytics
9) Example Bucket Policies for VPC Endpoints for Amazon S3
