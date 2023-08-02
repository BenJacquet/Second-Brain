
Perform bulk operations on existing S3 objects, for example modify the metadata of many files at once.

Use-cases:
- Move or copy files between S3 buckets
- Encrypt unencrypted objects on a S3 bucket
- Modify ACL
- Recover many files from a Glacier bucket
- Invoke Lambda function to perform tasks on objects

A job consists of:
- A list of objects
- An action to perform
- Additional parameters if needed

It can manage:
- Retries
- Progress Tracking
- Send completion notifications
- Reports genration

![[Capture d’écran 2023-08-02 à 22.53.51.png]]