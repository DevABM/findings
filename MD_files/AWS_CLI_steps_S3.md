## Steps to create S3 bucket in AWS CLI
    1 .  aws s3api create-bucket --bucket abmvvv6
    2 .  aws s3 website s3://abmvvv6 --index-documents index.html
    3 .  aws s3 website s3://abmvvv6 --index-document index.html
    4 .  ls
    5 .  vi policy_s3.json
    6 .  aws s3api put-bucket-policy --bucket abmvvv6 --policy file://policy_s3.json
