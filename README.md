# TodoApp on AWS
AWS LINK: http://todoinfrastack-todositebucket2627fe8a-h31e4musfnja.s3-website.ap-south-1.amazonaws.com/
This is a TodoApp implemented on AWS using AWS CDK, DynamoDB, and S3.

## Architecture

The architecture of the TodoApp consists of the following components:

- **AWS CDK Stack:**
  - Defines the infrastructure using AWS CDK.
  - Creates DynamoDB tables for storing Todo items.
  - Configures an S3 bucket for file storage.

- **DynamoDB:**
  - Used for storing and managing Todo items.
  - Table schema includes fields such as `taskId`, `title`, `description`, `status`, etc.

- **S3 Bucket:**
  - Used for storing file attachments related to Todo items.

## Prerequisites

Before deploying the TodoApp, ensure the following:

- AWS CLI is installed and configured with the necessary credentials.
- Node.js and npm are installed.
- AWS CDK is installed (`npm install -g aws-cdk`).

- **Properties**
  - ** User can add tasks to the list**
  - ** User can mark completed and task will be marked completed"
  - ** USer can have the tasks after closing the tab and checking after some time**
![Screenshot (30)](https://github.com/raaz252/todo-aws/assets/63297432/b8fbab54-d34c-4e93-8ee1-1cee0126da17)
![Screenshot (32)](https://github.com/raaz252/todo-aws/assets/63297432/04313405-9b9b-4628-98d8-dd9d3383af70)



