# Cloud-computing session 4
The S3 bucket creation code is in main.tf to create s3 bucket for storage. Then delete state file from local directory.
Comment s3 bucket creation section in main.tf and run again. Do the init, plan, apply process and it will show (Apply complete! Resources: 1 added, 0 changed, 0 destroyed.) and we check in the s3 section of the aws console and we can confirm that the state file has been created on the S3 backend bucket.
Now terraform is referring state from S3 bucket and taking action accordingly.
