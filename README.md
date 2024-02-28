# Sheetal Turaga-AWS-Cloud-Resume-Challenge 2024

I found the Cloud Resume Challenge when I was looking for projects that I could build to get hands-on practice of all the cloud concepts and AWS tools that I had learnt about during my preparation for the AWS Cloud Practitioner Certification. I passed my certification just a couple of days before I started the implementation of this challenge.

Here is the link to the AWS Challenge for your reference:
https://cloudresumechallenge.dev/docs/the-challenge/aws/

It involves of about 16 steps to complete the challenge. My status so far is as follows:
- Certification ✅
- HTML ✅
- CSS ✅
- Static Website: ✅
  - Deploying a static website on to AWS S3 using Github Actions to push changes automatically
  - Created S3 Bucket and enabled Static hosting on S3
  - Created IAM user to generate Access key and Secret Access Key to link the repo. Updated the Github Actions with ID and keys for easy access
  - Setup github workflows with main.yml that is the workflow code to trigger Github actions whenever you push on the main branch. This will be used to sync the project main folder to S3 bucket
- HTTPS: Using AWS CloudFront to make sure S3 website URL uses HTTPS security
- DNS: Custom DNS domain name to CF Distribution for access
- JavaScript: Include a visitor counter
- Database: Storing & updating counter in DynamoDB
- API: Create API to accept requests from web app to talk to the DB
- Python: Lambda function
- Tests: Python tests
- Infrastructure as Code: Automate deployment using AWS SAM CLI/Terraform
- Source Control: Create Github Repo for Backend code
- CI/CD: Github Actions to push an update to SAM template, run tests and then deploy to AWS
- BlogPost: Document your journey and provide a link of your resume

