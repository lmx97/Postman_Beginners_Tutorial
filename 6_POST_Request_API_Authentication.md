## POST request / API Authentication

We need to send http messages to the server and the server only responds. We need to register ourselves with the api and it is a way for the api to identify who’s sending requests and who’s creating the data.


**Step 1:** Add new request or duplicate the existing request then enter the URL https://simple-books-api.glitch.me/api-clients. And then select the POST http request method.

![PR_Step1.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/POST_Request/PR_Step1.png)


**Step 2:** Click on “Body” and select the “raw”. From the drop down “Text” there, select the “JSON”.

![PR_Step2.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/POST_Request/PR_Step2.png)


**Step 3:** Enter the clientName and clientEmail as following JSON format. Then, click on “Send”.

![PR_Step3.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/POST_Request/PR_Step3.png)


**Response**<br/>
Once a post request has been sent, we got back an access token. 
![PR_Step3_Response.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/POST_Request/PR_Step3_Response.png)


** Access token is like a temporary password. And you can use the password with all your requests
** Every status code that starts with 2.. something is typically a good sign (means everything is ok). 
** Every status code starts with 4.. something means that there were something wrong with the recurs that we have submitted.


**Step 4:** Copy the token, go to “Collection” and click on “edit”.

![PR_Step4.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/POST_Request/PR_Step4.png)

**_To Save the access token:_** 

Click on “Variables”, And add new variable “accessToken”, past the token in “initial value” or “current value”.

![PR_Step4(2).png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/POST_Request/PR_Step4(2).png)

**Initial Value:** The initial value is shared with your team when you share the variable in a collection, environment or globals.
**Current Value:** The current value is used while sending a request. Current value are never synced to Postman’s servers. If left untouched, the current value automatically assumes the initial value. 


**Step 5:** Add new request or duplicate the existing request then enter the URL https://simple-books-api.glitch.me/orders.

![PR_Step5.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/POST_Request/PR_Step5.png)


**Step 6:** Typically we add the authentication information to the “Headers”, some apis allow to add them as query parameters, some of them allow to add them in the “Body”. To add the token in the “Headers”, click on “Authorization” and select the type “Bearer Token”.

![PR_Step6.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/POST_Request/PR_Step6.png)


**Step 7:** Enter the token or enter the variable {{accessToken}}, and back to “Headers” you will see that postman has auto-generated one header called “Authorization”.

![PR_Step7.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/POST_Request/PR_Step7.png)

![PR_Step7(2).png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/POST_Request/PR_Step7(2).png)
