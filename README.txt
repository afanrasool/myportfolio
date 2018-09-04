This is my personal portfolio website. 
Automated and deployed using AWS.

A push to the remote repository (right here) signals Code Pipeline, which runs CodeBuild and 
triggers a Lambda function which deploys the newly added changes directly to my Serverless website hosted on S3.
