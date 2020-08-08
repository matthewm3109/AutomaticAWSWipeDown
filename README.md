# AutomaticAWSWipeDown

Because of the number of unnecessary charges I incurred while AWS, I wrote a script that automatically terminates different services.

Features: 

This current version can terminate VPCs and their associated subnets. 
Control on AWS services is done mainly via the BOTO3 library. 

Usage: 

Replace the curly brackets in the global variables section with your AWS Access Creditentials. 
You will need the region name, secret key and access key to access AWS services. 

Readmap: 

I would love to expand this into an all-in-one solution that closes everything. 
This inclues other AWS offerings such as EC2 instances and S3 buckets. 
