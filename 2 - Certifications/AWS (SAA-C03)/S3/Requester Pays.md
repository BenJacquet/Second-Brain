
In a standard S3 bucket scenario, the owner pays for the storage and networking cost (download).

With a "Requester Pays" bucket, the owner still pays for storage but the requester pays the networking costs.
Note that the requester must be authenticated on AWS (No anonymous access).
This is good for giving access to very large datasets or files.