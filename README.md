# Static Website Hosting on AWS

This project demonstrates how to host a static website using **Amazon S3** and optimize its delivery using **Amazon CloudFront**. The project is designed to help you learn the basics of static website hosting and content delivery on AWS.

---

## Project Overview

This project focuses on deploying a static website that includes **HTML**, **CSS**, and **JavaScript** files. These files require no server-side processing, making the cloud an ideal environment for hosting. 

## Prerequisites

- Download the **starter code**: [Click here to download](https://video.udacity-data.com/topher/2020/May/5ecea462_udacity-starter-website/udacity-starter-website.zip) (Ensure to unzip the file before proceeding).
- Familiarity with basic AWS services (S3 and CloudFront).

### Objectives
1. **Host a static website** on Amazon S3.
2. **Use CloudFront** to access cached website pages, ensuring:
   - **Low latency** during rendering.
   - **High transfer speeds**.

### Key Considerations
- Static website hosting on S3 requires a **public bucket**.
- CloudFront can operate with both **public** and **private buckets**, enhancing security and performance.

---

## Steps to Deploy the Website

### 1. **Create an S3 Bucket**
- 1.1 Navigate to the “AWS Management Console” page, type “S3” in the “Find Services” box and then select “S3”.
- 1.2 The Amazon S3 dashboard displays. Click “Create bucket”.
- 1.3 In the General configuration, enter a “Bucket name” and a region of your choice(One of the convenient naming conventions is my-123456789-bucket, where you can replace 123456789 with your 12 digit AWS account ID).
- 1.4 In the Bucket settings for Block Public Access section, uncheck the “Block all public access”. It will enable the public access to the bucket objects via the S3 object URL.

### 2. **Upload files to S3 Bucket**
- 2.1 Once the bucket has been created, click the “Upload” button.
- 2.2 Click the "Add files" and “Add folder” button, and upload the Student-ready starter code(opens in a new tab) folder content from your local computer to the S3 bucket.

### 3. **Secure Bucket via IAM**

### 4. **Configure S3 Bucket**

### 5. **Distribute Website via CloudFront**

### 6. **Access Website in Web Browser**
