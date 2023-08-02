
S3 Automatically scales to high request rates and low latency.

Numbers:
- 3500 PUT/COPY/DELETE requests per second
- or
- 5500 GET/HEAD requests per second
- per prefix in a bucket
There is no limit to the number of prefixes in a bucket

Multi-Part upload:
- Recommended for files more than 100mb in size
- Mandatory for files more than 5gb in size

S3 Transfer Acceleration:
- Increase speed by transferring files to an AWS edge location which will forward them to an S3 bucket in the target region over a fast private network
- Compatible with Multi-Part upload
![[Capture d’écran 2023-08-02 à 22.40.48.png]]

S3 Byte-Range Fetches:
- Speeds up downloads
- Parallelizes GETS by requesting specific byte ranges
- Better resilience to failure
- Can be used to recover specific parts of a file (for example the first 50 bytes containing the header)