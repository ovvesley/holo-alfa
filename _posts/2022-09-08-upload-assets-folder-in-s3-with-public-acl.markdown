---
title: Upload assets folder in s3 with public acl
date: 2022-09-08 12:56:00 Z
categories:
- software engineer
tags:
- software-enginner
- aws
---

just run this command in your cli


DONT FORGET MAKE YOUR BUCKET WITH ACL ENABLE POLICY!! 
```
aws s3 cp assets/ s3://<BUCKETNAME>/assets/ --acl public-read --recursive --profile <your-profile>
```