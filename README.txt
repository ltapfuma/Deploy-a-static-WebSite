Cloud Fundamentals Project
The cloud is perfect for hosting static websites that only include HTML, CSS, and JavaScript files that require
 no server-side processing. In this project, I have deployed a static website to AWS using the steps below:

Step 1:
Create a S3 bucket and upload the website files to your bucket. This is your index .html file

Step 2:

Secure your bucket using IAM policies. and configure the bucket for website hosting, by going to properties then click on website hoisting and select ENABLE

Step 3:

Speed up content delivery using AWS’ content distribution network service, CloudFront. ( create a distribution in Cloud Formation distribution )

   -Servives-->Open CloudFront-->CREATE a distribution

Step 4:

Access your website in a browser using the unique CloudFront endpoint.
