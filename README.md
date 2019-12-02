## Create cloudformation template
**Create the stack**
aws cloudformation create-stack --stack-name AppSyncChatRoom --template-body file:///Users/dongfenggu/workspace/Course_Introduction_to_AWS_AppSync/cfn-template.yaml --capabilities CAPABILITY_IAM

**Update the stack**
aws cloudformation update-stack --stack-name arn:aws:cloudformation:us-east-1:394797168553:stack/AppSyncChatRoom/1b2465f0-1479-11ea-ab6d-0a05dbc7583b --template-body file:///Users/dongfenggu/workspace/Course_Introduction_to_AWS_AppSync/cfn-template.yaml --capabilities CAPABILITY_IAM