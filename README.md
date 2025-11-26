# AWS Static Website Project (S3 + CloudFront)

## Overview
This project hosts a static website on AWS using:
- Amazon S3 (static website hosting)
- Amazon CloudFront (CDN)
- CloudWatch (monitoring)

## Architecture
User --> CloudFront --> S3  
CloudWatch monitors CloudFront activity.

![Architecture Diagram](S3-CloudFront-Website - architecture-diagram.png)

## Steps I Followed
1. Created S3 bucket and enabled static hosting
2. Uploaded index.html and set Content-Type to text/html
3. Set bucket policy for public read
4. Tested S3 website endpoint
5. Created CloudFront distribution
6. Tested CloudFront URL
7. Added CloudWatch monitoring

## What I Learned
- How to serve a static website from S3
- How a CDN speeds up delivery using CloudFront
- How permissions and public access work in AWS
- Basic cloud architecture
