# ouath2_with_jwt
My understandig of oauth2 with jwt :

Oauth2 is authentication service which provides access tokens so that users can access the resource
Here token is genrated with the help of jwt signature (jwt is just signing the details while oauth2.o is autorizing them);

In Authentication manager method provided by spring security overide with our function inorder to get authentication ( used in menory for now to authetnciate two users)

Afterwards set up client detailsservice configure to configure the method to get access token generated by oauth 

link : https://medium.com/@er.rameshkatiyar/configure-spring-security-in-your-application-ae303fa78959


jwt is a method to check that message was indeed recieved to a right user 

