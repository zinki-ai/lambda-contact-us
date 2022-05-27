# lambda-contact-us
Send contact-us emails easily with this micro-service using an AWS Lambda and the Serverless framework. 

![alt text](http://i68.tinypic.com/16at84n.png)
### Prerequisites

- Node 14.x

### Quick Start Into Production

npm install
export username=xyz@example.com password=xyz receivingEmail=xyz@example.com
sls offline

validate:

```sh
curl -X POST https://mxd8l6ygq1.execute-api.us-west-2.amazonaws.com/v1/contactus -d '{"name": "Abdennour Test v2", "subject": "My Subject is simple v2", "message": "Any message v2", "email": "any@example.com"}' -H 'Accept: application/json' -H 'Content-Type: application/json' 
```