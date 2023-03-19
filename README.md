# APIGateway
Google API Gateways is one of the offering provided by Google Cloud 



Steps by Steps to Create the Projects 

Go to New Project and Create a Project **GoogleAPIGateway**

Once that's done, We will enable to Services 
1. API Gateway API
2. Service Control API
3. Service Management API

Go to Google function and Create Google Functions

Create a Hello function 

once done the update the url on the Open API Path 

Create the Open API file in yaml 

update the Google Function link with the new Link which you create 

Go To console and create New API Gateway 

1) give the Display Name "apigateway" for API
2) give the APIID "k8sugdemoapi" on API ID 
3) Upload the Open API files which we have update with new google Function 
4) Display name for API Config "CallingGfun" 
5) select the service account, "CallingGateway" is the Service Account which will be used by me 
6) give the Displayname "externalface" will be used by me 
7) select the region "Us-Central-1" just its little faster 

Wait for few minutes till gateway is ready

convert the link into QR code using https://qr.io/

request everyone to connect and make call and show how to Data stream for log works 


















Reference 
https://github.com/OAI/OpenAPI-Specification/blob/main/versions/2.0.md

