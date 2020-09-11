# s3-to-gcp
A simple repo to upload files from AWS S3 Bucket to GCP Bucket

# Flow
For this flow to send a file from S3 to GCP, I created a GCP Cloud Function. Used a service account for its authentication and then called this function from Lambda.

## Authenticating GCP Function
To authenticate using a service account, the first thing needed is to generate a JWT. To achieve this, for a service account, the key.json file will play an imp role
