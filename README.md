# AWS-CloudComputing

## Deploying a web application on AWS-EC2

**Application Use Cases:**

* Application manages Billing invoices for the customer
* User account management and Bill records are saved in MySQL RDS Instance
* Bill related files are uploaded to Amazon S3 bucket with lifecycle policy of 30 days
* Bill file metadat is stored in RDS Instance itself for retrieval purpose
* User receives his due bills email via AWS Simple email service

Tools and Technologies

  <table>
    <thead>
      <tr>
        <th>words</th>
        <th>transform to</th>
        <th>keepUpperCase is false</th>
        <th>keepUpperCase is true</th>
      </tr>
    </thead>
    <tbody>
        <tr>
            <td>"XML HTTP request"</td>
            <td>pascalCase</td>
            <td><code>XmlHttpRequest</code></td>
            <td><code>XMLHTTPRequest</code></td>
        </tr>
        <tr>
            <td>"new customer ID"</td>
            <td>camelCase</td>
            <td><code>newCustomerId</code></td>
            <td><code>newCustomerID</code></td>
        </tr>
    </tbody>
  </table>
  
**Architecture Design:**

![](AWS_Architecture.png)
