# AWSCloudWork

The following will demonstrate my ability to launch a website using AWS services S3 and CloudFront. The Website is static, but the following was done in descending order from created the S3 bucket to launching by 3 different URLs based on the CloudFront distribution created.

S3 Bucket is created to hold the code that makes up the website:
![image](https://github.com/user-attachments/assets/5f4d5905-8ee6-44bb-a445-98efb8c6e3f4)

Static Website hosting has been enabled:
![image](https://github.com/user-attachments/assets/d2120123-d3c0-488c-91f9-fea2d0e33fbd)

Bucket Policy set to Bucket ```staticwebbuck```:
![image](https://github.com/user-attachments/assets/5345e006-d294-4079-878e-16b87374a024)


The following shows the CloudFront service that is used to launch the website:
![image](https://github.com/user-attachments/assets/f12bbb91-0a75-4031-b940-7304c1168cb8)

![image](https://github.com/user-attachments/assets/f12b3700-f63d-473c-9458-cc1dd6770a94)

![image](https://github.com/user-attachments/assets/fcf262c7-1575-4c8b-bbf4-584fd3c429d3)

Note: The CloudFront distribution and S3 bucket have been deleted to avoid occuring AWS cost. The below links shows 3 URLs that would have led to the website depending on where you launch from. The website are secured connections, but not the website-endpoint.
CloudFront Domain Name:
```https://d1px30uxy68g57.cloudfront.net/index.html```

S3 website-endpoint:
```https://staticwebbuck.s3.us-east-1.amazonaws.com/```

S3 Object URL:
```https://staticwebbuck.s3.us-east-1.amazonaws.com/index.html```

All 3 will lead to this webpage:
![image](https://github.com/user-attachments/assets/925d471f-43b8-4433-80e4-c46d4d69a9bc)
