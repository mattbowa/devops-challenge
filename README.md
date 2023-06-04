# Devops Challenge

## Website URL

https://mb-static-website-test.s3.ap-southeast-2.amazonaws.com/index.html

## Introduction

This demostrates hosting a simple a simple static website on AWS. The website is hosted on an S3 bucket

## Deployments

The website is deployed manully through the AWS S3 console page. Simply enable static website hosting and upload the files to the bucket. The website is then accessible via the S3 bucket URL

## Improvements

Automate the deployment to S3 using Terraform and serve the website via CloudFront. The website is to be deployed using a CI/CD pipeline using GitHub Actions. The pipeline is triggered when a new commit is pushed to the master branch. The pipeline builds the website and deploys it to S3. The pipeline also invalidates the CloudFront cache so that the latest version of the website is served.
