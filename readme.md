# aws-s3-lambda

- Go to amazon Developers Console and create an app and find Login With Amazon.
- Create app and save APPLICATION_ID and CLIENT_ID
- Create Lambda function
- Create policy to exec, list and get the previously lambda function created.
- Create role as an Web Identity, select Login with Amazon and add the APPLICATION_ID
- Inside the role append the policy created just before.

- Replace ROLE_ARN and LambdaName in app.js.
- Replace CLIENT_ID in index.html.
- Create S3 Bucket as Website, with CloudFront (Dont forget to upload the code)
- Edit App in amazon developers console and go to Web Settings and append Cloudfront url to Allowed Origins.