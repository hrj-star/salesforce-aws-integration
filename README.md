<h1 align="center">salesforce-aws-integration </h1>
<div align="center">
🌟 Easily integrate Salesforce and AWS to use powerful AWS services for Salesforce usecases 🌟
</div>


## ⚡ Features

1. Send .pdf documents to AWS, call Textract functions to extract data or contants in the document and send the extracted content back to Salesforce 

<br/>

## 🌻 Motivation

Integrating Salesforce with AWS to leverage Textract services that offers a range of benefits that can transform document processing and customer engagement:

1. **Automated Data Extraction**: AWS Textract automates the extraction of text and data from documents, reducing manual entry and saving time for your team.

2. **Enhanced Accuracy**: Leveraging Textract’s machine learning capabilities ensures high accuracy in data extraction, minimizing errors and improving the quality of your customer information.

3. **Seamless Workflows**: Integrating with Salesforce allows for real-time updates to customer records based on the extracted data, ensuring your CRM is always up to date.

4. **Improved Customer Insights**: By analyzing documents such as contracts or invoices, we can gain deeper insights into customer needs and preferences, enabling more personalized interactions.

5. **Scalability**: AWS Textract’s cloud-based nature allows you to easily scale your document processing capabilities as your business grows, accommodating increasing volumes of data.

6. **Cost-Effective Solutions**: Utilizing AWS Textract’s pay-as-you-go pricing can help manage costs, especially when processing large amounts of documentation through Textract services.

7. **Enhanced Compliance and Security**: Integrating these services ensures that sensitive customer data is handled securely and in compliance with regulations, protecting your organization and clients.

8. **Conversion of Legacy or Offline Printed Contracts**: This process enables the transformation of paper-based legacy contracts into digitized formats, facilitating efficient extraction of field entities and enhancing overall data accessibility.


<br/>

##📋 Prerequisites

1. Salesforce org
2. AWS Account: Create or use an existing AWS account.
3. AWS IAM Credentials: Obtain AWS Access Key ID and Secrect Access Key with permissionns for AWS Textract and S3.

<br/>

##🛠️ Steps:
➡️ Step 1: Create AWS IAM User:
  — Go to AWS IAM console.
  — Create a new IAM user or use an existing one.
  — Attach policies for AWS Textract and S3 access (Have used full access for demo purpose, it would vary as per requirement)

➡️ Step 2:  Obtain Access Key ID and Secret Access Key:
  — In AWS IAM, navigate to the user’s security credentials.
  — Generate or use existing Access Key ID and Secret Access Key.
