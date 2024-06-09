# Troubleshoot CloudFormation

## Activity Overview

In this activity, I practiced troubleshooting AWS CloudFormation deployments. The steps included:

1. Querying JavaScript Object Notation (JSON)-formatted data by using JMESPath.
2. Establishing an SSH connection to a CLI Host and using the AWS Command Line Interface (CLI) to create a CloudFormation stack.
3. Manually modifying resources and detecting drift with CloudFormation.
4. Troubleshooting a failed stack deletion and resolving the issue to delete the stack while preserving an S3 bucket with objects.

![architecture](https://github.com/Mohamed-kittany/Canvas-Lab-191-TroubleshootingAWSCloudFormationDeployments/assets/161580792/5e922ad2-a879-4c99-a5e1-2f5c3c53366a)

## Activity Objectives

After completing this activity, I am able to:
- Use JMESPath to query JSON-formatted documents.
- Troubleshoot the deployment of an AWS CloudFormation stack using the AWS CLI.
- Analyze log files on a Linux EC2 instance to determine the cause of a create-stack failure.
- Troubleshoot a failed delete-stack action.

## Tasks Completed

### Task 1: Practice Querying JSON-formatted Data by Using JMESPath
- Used JMESPath to query and filter JSON documents, gaining familiarity with the syntax and operations to extract specific information from JSON data structures.

### Task 2: Troubleshooting and Working with AWS CloudFormation Stacks
- Established an SSH connection to the CLI Host.
- Configured the AWS CLI with necessary credentials.
- Attempted to create an AWS CloudFormation stack and observed the creation process.
- Troubleshot the stack creation failure by analyzing the AWS CloudFormation stack events and userdata logs on the EC2 instance.
- Fixed the issue in the template and successfully created the CloudFormation stack.
- Tested the deployed web server to ensure proper functionality.

### Task 3: Make Manual Modifications and Detect Drift
- Manually modified the security group rules and added an object to the S3 bucket created by the stack.
- Used AWS CloudFormation to detect drift and analyzed the drift status to identify resources that were modified outside of the CloudFormation context.
- Verified the detected drift and understood the implications of manual changes to CloudFormation-managed resources.

### Task 4: Attempt to Delete the Stack
- Attempted to delete the stack, encountering a failure due to an S3 bucket containing objects.
- Identified the challenge of deleting the stack while preserving the S3 bucket and its contents.
- Successfully resolved the issue by retaining the bucket and ensuring the stack deletion process completed without errors.

## Key Accomplishments and Learnings from this Lab
- Gained proficiency in querying JSON documents using JMESPath.
- Developed skills in troubleshooting AWS CloudFormation stack deployments and analyzing failure causes.
- Learned how to detect and resolve resource drift in AWS CloudFormation.
- Acquired the ability to handle failed stack deletions and preserve specific resources while cleaning up CloudFormation stacks.
- Enhanced understanding of AWS CloudFormation capabilities and best practices for managing infrastructure as code.

