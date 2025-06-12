# AWS S3 Bucket – Public Access Configuration

This project demonstrates how to configure public access for files stored in an **AWS S3 bucket** using a **bucket policy**.

## 🔧 What This Contains

- ✅ A sample S3 bucket policy that grants **public read access** to all files inside the bucket.
- ✅ Notes on IAM and S3 permissions
- ✅ Link to test the uploaded public object

## 📄 Sample Policy File: `s3-public-access-policy.json`

```json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "PublicReadAccess",
      "Effect": "Allow",
      "Principal": "*",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::aws-storage-bucket-330/*"
    }
  ]
}
