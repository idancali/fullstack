### The Full Stack Product Development Journey
Creating A Product From Idea To Launch In 20 Weeks.

# Week 2: The Landing Page
[![WEEK2](https://img.shields.io/badge/Week_2-DONE-green.svg)]()
[![START](https://img.shields.io/badge/START-YOUR_JOURNEY-green.svg)](https://www.youtube.com/playlist?list=PL9YBPmbctP4hSF3Runs61TGt7j1gjDj5z)
[![SHARE](https://img.shields.io/badge/SHARE-ON_TWITTER-blue.svg)](https://twitter.com/intent/tweet?text=Loving%20the%20%23fspdjourney%20with%20@idancali%20http://github.com/idancali/fullstack%20%23fullstack%20%23productdevelopment)

### S3 Static Website Bucket Policy

```
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "PublicReadGetObject",
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "arn:aws:s3:::www.carmel.io/*"
        }
    ]
}
```
