# delay_sqs_with_step_function

aws cloudformation package --template-file template.yaml --s3-bucket aws-resources-dev-test --output-template-file packaged.yaml
aws cloudformation deploy --stack-name "step-function-example" --template-file packaged.yaml --capabilities CAPABILITY_IAM


