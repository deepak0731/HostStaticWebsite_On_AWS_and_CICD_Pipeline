# HostStaticWebsite_On_AWS_and_CICD_Pipeline
We will use S3 to store our static website content, CloudFront as our CDN to improve the website's performance, CodePipeline for CICD pipeline automation.

### Amazon S3 (Simple Storage Service)
Use S3 to store and serve your website's static files. Create an S3 bucket and configure it for static website hosting.
### Amazon Route 53:
Register a domain or use an existing one, and configure DNS records to point to your S3-hosted website.
### AWS IAM (Identity and Access Management):
Set up IAM roles and permissions to securely manage access to your AWS resources.
### Amazon CloudFront:
Implement a CDN (Content Delivery Network) using CloudFront to distribute your website content globally for improved performance.
### CI/CD Pipeline: Implement a CI/CD pipeline to automate the deployment of your static website to AWS:
### Version Control: Use Git for version control and host your project's repository on a platform like GitHub or AWS CodeCommit.
### Continuous Integration: 
Set up CI triggers to build and test your website code automatically whenever changes are pushed to the repository.
### Continuous Delivery:
Automate the deployment of your website to AWS S3 and, if using CloudFront, create mechanisms to invalidate the cache when new content is deployed.
### CI/CD Tools: You can use popular CI/CD tools Jenkins and AWS CodePipeline to create and manage your pipeline.
