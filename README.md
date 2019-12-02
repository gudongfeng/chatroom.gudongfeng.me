## Create cloudformation template
**Create the stack**
aws cloudformation create-stack --stack-name AppSyncChatRoom --template-body file://cfn-template.yaml --capabilities CAPABILITY_IAM

**Update the stack**
aws cloudformation update-stack --stack-name AppSyncChatRoom --template-body file://cfn-template.yaml --capabilities CAPABILITY_IAM

**Delete the stack**
aws cloudformation delete-stack --stack-name AppSyncChatRoom 