# s3-to-gcp
A simple repo to upload files from AWS S3 Bucket to GCP Bucket

# Flow
For this flow to send a file from S3 to GCP, I created a GCP Cloud Function. Used a service account for its authentication and then called this function from Lambda.
