### GET Requests
A GET request is used to obtain details from the server and does not have any impact on the server. The GET request does not update any server data while it is triggered. The server only sends its Response to the request.

*Follow the steps given below to create a GET request successfully in Postman:*

**Step 1:** Select “Collections” and  “ + ” at the top left corner.
![GR_Step1.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/GR_Step1.png)

**Step 2:** Click on “...” and Select “Add request”.
![GR_Step2.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/GR_Step2.png)

**Step 3:** If you want to save the request name, you can click on “Save As” at the right top corner, enter the Request name then click on save. 
![GR_Step3.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/GR_Step3.png)
![GR_Step3(2).png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/GR_Step3(2).png)

**Step 4:** The Request name (Test1) gets reflected on the Request tab. We shall then select the option GET from the HTTP request dropdown.
![GR_Step4.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/GR_Step4.png)

**Step 5:** Enter an URL - https://simple-books-api.glitch.me/status in the address bar and click on Send

**Response**
Once a request has been sent, we can see the response code 200 OK populated in the Response. This signifies a successful request and a correct endpoint. Also, information on the time consumed to complete the request (1756 ms) and payload size (226B) are populated.
![GR_Step4.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/GR_Response.png)