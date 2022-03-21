Using the sample app
The sample app exposes the following routes. Visit them in your browser, then go to the AWS X-Ray console to see the traces they generate.

localhost:8080/ - healthcheck endpoint, generates a single span
localhost:8080/aws-sdk-call - Makes a traced request with the AWS SDK
localhost:8080/outgoing-http-call - Makes a traced downstream HTTP request
