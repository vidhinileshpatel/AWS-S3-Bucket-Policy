# Bucket Policy for S3

A bucket policy is a resource-based AWS Identity and Access Management (IAM) policy. A Bucket Policy is used to grant other AWS accounts or IAM users access permissions for the bucket and its objects. 

# Contents of a Bucket Policy

A Bucket Policy has the following structure: 

{

  "Version":"2012-10-17",

  "Statement":[]
 
 }
 
 The statement comprises of the various actions, permissions, resource location and other necessary information.
 
# Topics
1) [Granting Permissions to Multiple Accounts with Added Conditions](https://docs.aws.amazon.com/AmazonS3/latest/dev//example-bucket-policies.html#example-bucket-policies-use-case-1)
2) [Granting Read-Only Permission to an Anonymous User](https://docs.aws.amazon.com/AmazonS3/latest/dev//example-bucket-policies.html#example-bucket-policies-use-case-2)
3) [Restricting Access to Specific IP Addresses](https://docs.aws.amazon.com/AmazonS3/latest/dev//example-bucket-policies.html#example-bucket-policies-use-case-3)
4) [Restricting Access to a Specific HTTP Referrer](https://docs.aws.amazon.com/AmazonS3/latest/dev//example-bucket-policies.html#example-bucket-policies-use-case-4)

5) [Granting Permission to an Amazon CloudFront Origin Identity](https://docs.aws.amazon.com/AmazonS3/latest/dev//example-bucket-policies.html#example-bucket-policies-use-case-6)
6) [Adding a Bucket Policy to Require MFA](https://docs.aws.amazon.com/AmazonS3/latest/dev//example-bucket-policies.html#example-bucket-policies-use-case-7)
7) [Granting Cross-Account Permissions to Upload Objects While Ensuring the Bucket Owner Has Full Control](https://docs.aws.amazon.com/AmazonS3/latest/dev//example-bucket-policies.html#example-bucket-policies-use-case-8)
8) [Granting Permissions for Amazon S3 Inventory and Amazon S3 Analytics](https://docs.aws.amazon.com/AmazonS3/latest/dev//example-bucket-policies.html#example-bucket-policies-use-case-9)
9) [Example Bucket Policies for VPC Endpoints for Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/dev//example-bucket-policies-vpc-endpoint.html)


# How to add a Bucket Policy

After creating a bucket in S3 (testbucket1), use the following steps to add policies to it:

1) Select the bucket to which you want to add the policies.

2) Choose Persmissions -> Bucket Policy

3) The Bucket Policy editor will open. It the editor you can change an existing policy or add a custom policy, in JSON. Use the Policy Generator link to create a policy.


# Source and Destination Bucket Policy

To copy S3 objects across AWS accounts read this interesting blog by Parag Poddar: [Tensult Blogs(A Medium Corporation)](https://medium.com/tensult/copy-s3-bucket-objects-across-aws-accounts-e46c15c4b9e1)

For more details use the official documentation provided by AWS : [AWS S3 Bucket Policy](https://docs.aws.amazon.com/AmazonS3/latest/user-guide/add-bucket-policy.html)
