How I developed a serverless lamda function with S3 and DYNAMODB

steps

1. IAM >> create IAM role (lamda)

2. S3  >> create S3 bucket

3. DYNAMODB  >> Created dynamoBD {Please make sure your dynamodb name and the item name same for the boto3.py code.}

4. SNS       >> Create SNS topic and congiure email or SMS

5. LAMDA     >> Create lamda function, Add trgger and Add Destination

             >> Deploy the boto3.py code


Once you have all created you can just put a file to the S3 bucket and you can see the dynamo DB automatically stored your data.

    
