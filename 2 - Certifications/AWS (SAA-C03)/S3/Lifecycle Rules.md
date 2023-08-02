
Management -> Create Lifecycle Rule

Moving objects can be automated using Lifecycle Rules via various actions:
- Transition actions - Configure objects to be moved to another storage class after a certain time
- Expiration actions - Configure objects to be deleted after a certain time
Rules can be applied to specific prefixes (ex: s3://my-s3-bucket-logs/*)

To help you choose when to transition to which storage class you can use S3 Analytics
(Only works for Standard and Standard IA)