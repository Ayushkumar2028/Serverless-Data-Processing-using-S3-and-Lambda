# Serverless-Data-Processing-using-S3-and-Lambda

# policy
set/create policy as given in policy.json proving read(GetObject) access from where it takes image, and write(PutObject) access where it store image
# Lambda function
then attach that role to lambda
# Zip the code 
then run the code to make a zip and upload that zip in lambda function
# Setting .env
set env in configuration (for destination bucket)
# Adding trigger
add a trigger so whenever image upload to s3, lambda get triggered automatically 
