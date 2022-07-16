## DELETE Request

Postman DELETE request deletes a resource already present in the server.


**Step 1:** Add new request or duplicate the existing request then enter the URL https://simple-books-api.glitch.me/orders/:orderId . And then select the DELETE http request method.<br/>
![DR_Step1.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/Delete_Request/DR_Step1.png)<br/>


**Step 2:** On the “Params” tab, enter the Key “orderId” and Value (enter the id that you want to delete) in the section of Path Variables. Then click “Send”.<br/>
![DR_Step2.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/Delete_Request/DR_Step2.png)<br/>


**Response**<br/>
![DR_Response.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/Delete_Request/DR_Response.png)<br/>
We get the status code 204 that means everything is Ok, also means that you have deleted the order.