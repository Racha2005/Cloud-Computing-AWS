🌩️ AWS S3 Bucket Configuration and Public Access – Cloud Computing Project

This project documents a hands-on exploration of Amazon Web Services (AWS) S3 (Simple Storage Service) for creating, managing, and configuring publicly accessible cloud storage.



🎯 Objective

🔹 Create multiple globally unique S3 buckets  
🔹 Upload files to cloud storage  
🔹 Configure public read-only access using bucket policies  
🔹 Explore IAM, Bucket Policies, ACLs, and Object Ownership  
🔹 Generate and test public URLs for hosted objects



🪣 Buckets Created

📦 bucket-nrcloud-x557 – Used for testing and cloud experimentation  
📦 archive-storage-aws722 – Archive and backup storage  

📍 Region: ap-south-1 (Asia Pacific – Mumbai)



📂 Files Included

🗂️ bucket-nrcloud-x557-policy.json – Public-read bucket policy for testing bucket  
🗂️ archive-storage-aws722-policy.json – Public-read bucket policy for archive storage  

Each policy grants read-only public access (s3:GetObject) to all objects inside the respective bucket.



🔐 AWS Concepts Explored

🛡️ IAM (Identity and Access Management)  
✅ Used to control access to AWS services and resources  
✅ IAM Policies define who can do what (written in JSON)  
✅ Crucial for managing security boundaries and roles


📜 Bucket Policies  

✅ Attached directly to individual S3 buckets  
✅ Allow or restrict actions like GetObject, PutObject  
✅ Public read access provided via Principal: "*" in the policy

🚫 Public Access Settings 

✅ AWS blocks all public access by default  
✅ Disabled “Block Public Access” setting manually  
✅ Applied bucket policies to allow safe sharing of files



🖼️ Public File Access Examples

📁 Bucket 1: bucket-nrcloud-x557  
🖼️ Image Name: blue-moon-crystal-lake.jpg  
🌐 Preview Link:  
https://bucket-nrcloud-x557.s3.ap-south-1.amazonaws.com/blue-moon-crystal-lake.jpg



📁 Bucket 2: archive-storage-aws722  
🖼️ Image Name: PurpleSky.jpg  
🌐 Preview Link:  
https://archive-storage-aws722.s3.ap-south-1.amazonaws.com/PurpleSky.jpg



💡 Key Learnings

✨ How to create and manage S3 buckets using AWS Console  
✨ Difference between s3:// (CLI path) and https:// (browser-accessible URL)  
✨ Managing public access using bucket policies instead of ACLs  
✨ Real-time testing of public object access and file sharing  
✨ Following best practices for cloud security and permission control



🏷️ Keywords

🔸 AWS   🔸 S3   🔸 IAM   🔸 Cloud Storage   🔸 Public Access  
🔸 JSON Policy   🔸 Permissions   🔸 Cloud Computing Practice
