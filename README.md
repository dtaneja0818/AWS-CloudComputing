# AWS-CloudComputing

## Deploying a web application on AWS-EC2

**Application Use Cases:**

* Application manages Billing invoices for the customer
* User account management and Bill records are saved in MySQL RDS Instance
* Bill related files are uploaded to Amazon S3 bucket with lifecycle policy of 30 days
* Bill file metadat is stored in RDS Instance itself for retrieval purpose
* User receives his due bills email via AWS Simple email service

**Tools and Technologies**

  <table>
    <thead>
      <tr>
        <th>Category</th>
        <th>AWS Services & Technologies to</th>
      </tr>
    </thead>
    <tbody>
        <tr>
            <td>Web Application</td>
            <td>NodeJS, MySQL, Sequelize ORM, Express Server, AWS-SDK, ES6</code></td>
        </tr>
        <tr>
            <td>Infrastructure</td>
            <td>VPC, Subnets, Routes, Load Balancer, EC2, RDS, Lambda, DynamoDB, Route53, Cloud formation</td>
        </tr>
    </tbody>
  </table>
  
**Architecture Design:**

![](AWS_Architecture.png)
