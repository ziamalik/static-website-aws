# Deploy Static Website on AWS
## Demonstrates setting up static website on AWS

This project, will deploy a static website to AWS using S3, CloudFront, and IAM.

### CloudFront URL: http://d1d3kxcgnq48hm.cloudfront.net/index.html

Following are files included that are part of Static Website: 

* _**index.html**_ - The Index document for the website.
* _**/img**_ - The background image file for the website.
* _**/vendor**_ - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
* _**/css**_ - CSS files for the website.

Steps:

1. Create S3 Bucket
![Create S3 Bucket](screenshots/1-S3-Bucket-Creation.png)

2. Uploaded Website files
![Uploaded Website files](screenshots/2-Uploaded-files.png)

3. Enable S3 Bucket to support static website hosting
![Enable-Bucket-Hosting](screenshots/3-Enable-Bucket-Hosting.png)

4. Set IAM Bucket Policy to make bucket content publicly accessible
![IAM-Policy-Public-Bucket](screenshots/4-IAM-Policy-Public-Bucket.png)

5. Configure CloudFront to retrieve and distribute website files
![CloudFront-Enablement](screenshots/5-CloudFront-Enablement.png)
