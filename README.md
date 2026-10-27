# AWS S3 + CloudFront Static Website Hosting

## Project Objective
To host a static website using Amazon S3 and deliver it securely through Amazon CloudFront.

## AWS Services Used
- Amazon S3
- Amazon CloudFront
- Origin Access Control (OAC)

## Implementation
1. Created an S3 bucket.
2. Uploaded the website files: `index.html` and `style.css`.
3. Enabled Block Public Access on the S3 bucket.
4. Configured CloudFront with the S3 origin and OAC.
5. Set `index.html` as the default root object.
6. Tested the website through the CloudFront distribution URL.

## Security
- S3 public access is blocked.
- CloudFront is allowed to access the S3 bucket through the bucket policy.

## Test Results
- Direct S3 object URL: Access Denied (403).
- CloudFront website URL: Website opens successfully.

## Result
Successfully hosted a static website using Amazon S3 and CloudFront with restricted direct access to S3.
