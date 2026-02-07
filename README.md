# AWS Resume Hosting Project

## Project Overview
Hosted a personal resume website as a static website using Amazon S3.
The project demonstrates cloud fundamentals, storage services,
static website hosting, and secure public access using bucket policies.

## Architecture
User Browser → Amazon S3 Static Website Endpoint → Resume Files

## AWS Services Used
- Amazon S3 – Static website hosting
- AWS IAM – Secure access control

## Implementation Steps
1. Created responsive HTML and CSS resume files
2. Created an S3 bucket and disabled block public access
3. Enabled static website hosting
4. Applied read-only bucket policy (s3:GetObject)
5. Uploaded website files and verified via website endpoint

## Security Considerations
- S3 buckets are private by default
- Public access limited to object read-only
- No sensitive data stored
- IAM follows least-privilege principles

## HTTPS Limitation
HTTPS is not supported directly for S3 static website endpoints.
CloudFront is required, but not used due to lab environment restrictions.

## Cost
Deployed using AWS Free Tier with zero cost.

## Author
Rohini Longadge

