# delay_sqs_with_step_function
 
 SQS offers us the option to send messages with a maximum delay of 15 minutes.With this structure, we can send messages delayed more than 15 minutes.

![](./stepfunctions_graph.png)

Deploy : 

`$ aws cloudformation package --template-file template.yaml --s3-bucket aws-resources-dev-test --output-template-file packaged.yaml`


`$ aws cloudformation deploy --stack-name "step-function-example" --template-file packaged.yaml --capabilities CAPABILITY_IAM`





