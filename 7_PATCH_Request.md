## PATCH Request

Postman PATCH request update to a resource already present in the server.


**Step 1:** Add new request or duplicate the existing request then enter the URL https://simple-books-api.glitch.me/orders/:orderId . And then select the PATCH http request method.<br/>
![PatchR_Step1.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/PATCH_Request/PatchR_Step1.png)


**Step 2:** Click on “Body”, select “raw” and also select “JSON”. Then enter the JSON format customerName and add the variable {{$randomLastName}} at the back of the example name “John”. Then click “Send”.<br/>
![PatchR_Step2.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/PATCH_Request/PatchR_Step2.png)


**Response**<br/>
![PatchR_Response.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/PATCH_Request/PatchR_Response.png)


We’re not getting back anybody and this is totally fine because the status will be indicated through the http response status and this is 204 that everything was OK.