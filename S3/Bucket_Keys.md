# S3 Bucket Keys

S3 Bucket Keys can help us to reduce the cost of S3 server-side encryption using AWS Key Management Service (SSE-KMS).

They do this by offloading much of the intensive processing from KMS onto S3.

One important thing to keep in mind is that enabling S3 Bucket Keys will change some things in CloudTrail.

Most notably, the KMS events will now show the bucket ARN instead of our object ARN.

We’ll also see fewer KMS events in general in CloudTrail.
