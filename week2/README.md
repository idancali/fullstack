### The Full Stack Product Development Journey
Creating A Product From Idea To Launch In 20 Weeks.

# Week 2: The Landing Page
[![WEEK2](https://img.shields.io/badge/Week_2-DONE-green.svg)]()

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
