# sam-serverless-web-app-backend
Serverless webapp backend - API Gateway-LAMBDA-DynamoDB
Serverless webapp backend which takes GET and POST methods to fetch the data from Database and loads the data to the database

#SAM Commands

sam build
sam deploy --stack-name test-sam-1 --capabilities CAPABILITY_NAMED_IAM

#API Keys for Authentication


LAMBDA:

Depending on method type either loads the database or retrives the data from it



API Gateway: Deploy steps
https://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-create-api-step-by-step.html

https://XXXXXXXXX.execute-api.region.amazonaws.com/dev/helloget?id=123456&namev=Pavan

dev = stage
helloget = method
get operation with query string parameters : id=123456&namev=Pavan
