# Deployment

Deploying a static website to AWS.

**Link**: [https://d3rngcvutysgl4.cloudfront.net/](https://d3rngcvutysgl4.cloudfront.net/)

## Available Options 
- Amazon S3 Static Web Hosting
- Amazon CloudFront with S3
- Amazon Amplify Hosting


## Breaking each option down

**Amazon S3(Simple Storage Service)**

With S3 bucket, we can upload our static files in an S3 bucket and enable **Static Website Hosting**

**Benefits**

- Very cheap
- Easy to setup
- Works best with Amazon CloudFront for speed and SSL/TLS (HTTPS)

**Amazon CloudFront with S3**

Amazon CloudFront is a Content Delivery Network and it can be used along with S3(or another origin server) to host a static website.

**Benefits**

- Delivers your website globally with low latency
- Provides HTTPS support and caching performance.

**Amazon Amplify Hosting**

Amazon Amplify is a managed hosting service for web apps(both static and serverless).

**Benefits**

- Easy CI/CD integration with GitHub, GitLab, Bitbucket, or CodeCommit
- Good for developers who want fast deployment pipelines

## Reason for choosing Amazon CloudFront with S3

S3 with CloudFront offers a cheap, fast, secure and scalable solution for the project I am deploying(a static website)