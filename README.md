# AWS-CloudComputing

## Deploying a web application on AWS-EC2

Application Description

* Application manages Billing invoices for the customer
* User account management and Bill records are saved in MySQL RDS Instance
* Bill related files are uploaded to Amazon S3 bucket with lifecycle policy of 30 days
* Bill file metadat is stored in RDS Instance itself for retrieval purpose
* User receives his due bills email via AWS Simple email service

