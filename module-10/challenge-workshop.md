# AWS Academy Cloud Architecting - Module 10 Challenge Lab Questions

## Questions

**Question 1: Was an S3 bucket created, even if you did not specify a name for the bucket? If so, what name was it given?**

- No, the bucket was not created.
- Yes, and it was given a name in the format [logical ID of resource in the template]-[stack name]-[some random letters and numbers]
- Yes, and it was given a name in the format [stack name]-[logical ID of resource in the template]-[some random letters and numbers]
- Yes, and it was given a name in the format [logical ID of resource in the template]-[stack name]

Answer: Yes, and it was given a name in the format [stack name]-[logical ID of resource in the template]-[some random letters and numbers] 

**Question 2: What Region was the bucket created in, and why was it created in this Region?**

- It was created in the us-east-1 AWS Region, because that is always the default AWS Region for every AWS CLI client unless you specify a different AWS Region when running the command.
- It was created in the AWS Region in which the CloudFormation create-stack command was run.
- It was created in the ap-northeast-1 AWS Region because that was set as the default region in the AWS CLI client on the Cloud9 instance.
- It was created in the eu-west-2 AWS Region because that was set as the default region in the AWS CLI client on the Cloud9 instance.

Answer: It was created in the AWS Region in which the CloudFormation create-stack command was run. 

**Question 3: To define an S3 bucket, how many lines of code did you need to enter in the `Resources:` section of the template file?**

- 2 lines
- 3 lines
- 4 lines
- 5 lines

Answer: 2 lines 

**Question 4: Go to the Parameters tab of the update-cafe-app stack. What value do you see for the LatestAmiId?**

- /aws/service/ami-windows-latest
- /aws/service/ami-amazon-linux-latest/amzn-ami-minimal-hvm-x86_64-ebs
- The value is blank
- /aws/service/ami-amazon-linux-latest/amzn2-ami-hvm-x86_64-gp2

Answer: /aws/service/ami-amazon-linux-latest/amzn2-ami-hvm-x86_64-gp2 

**Question 5: Go to the Stack info tab of the update-cafe-app stack. What is the Amazon Resource Name (ARN) of the IAM role that grants the permissions to create and update the update-cafe-app stack?**

- CustomCFnRole
- MyCloudFormationRole
- AWSCloudFormationReadOnlyAccess
- AWSCloudFormationFullAccess

Answer: CustomCFnRole 

**Question 6: In the AWS Management Console, navigate to the CodeCommit repository where your AWS CloudFormation templates are stored. Choose Commits and in the Commits list, open one of the commits by choosing its commit ID. What you do observe?**

- A listing of the files affected by the commit.
- The timestamp of when the commit was made and by whom.
- Details including what lines of which files were changed as part of the commit and what the lines now contain.
- I did not have permission to view the commit details.

Answer: Details including what lines of which files were changed as part of the commit and what the lines now contain. 
