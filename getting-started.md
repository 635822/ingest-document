# Getting Started Guide

## Prerequisites

Before you begin, ensure you have:

- AWS Account with Lambda access
- GitHub repository with documents
- S3 buckets created (glean-stage, glean-processed)
- Python 3.10 environment

## Step 1: Create Lambda Function

1. Go to AWS Lambda Console
2. Click "Create function"
3. Choose Python 3.10 runtime
4. Set memory to 512 MB
5. Set timeout to 5 minutes

## Step 2: Configure Environment Variables

Add these variables: GITHUB_TOKEN = your_token_here
FALLBACK_BUCKET = glean-stage
PROCESSED_BUCKET = glean-processed

## Step 3: Add Dependencies

Install required libraries:

- requests
- boto3 (included by default)

## Step 4: Deploy Code

Copy the Lambda function code and click Deploy.

## Step 5: Test

Create a test event:


## Next Steps

- Configure Glean credentials
- Set up scheduled sync
- Monitor CloudWatch logs
- Review processed documents

## Common Issues

### Issue: "No module named requests"

**Solution**: Add requests layer to Lambda function

### Issue: "GitHub API 404"

**Solution**: Check repository name and branch

See [troubleshooting guide](troubleshooting.md) for more help.
