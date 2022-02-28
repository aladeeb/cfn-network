# cfn-network

aws cloudformation create-stack --template-body=file://network.yaml --stack-name=network

aws cloudformation create-stack --template-body=file://server.yaml --stack-name=server --capabilities CAPABILITY_NAMED_IAM

aws cloudformation create-stack --template-body=file://database.yaml --stack-name=database