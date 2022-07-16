### GET Requests
A GET request is used to obtain details from the server and does not have any impact on the server. The GET request does not update any server data while it is triggered. The server only sends its Response to the request.

*Follow the steps given below to create a GET request successfully in Postman:*

**Step 1:** Select “Collections” and  “ + ” at the top left corner.
[!(https://littledevil.atlassian.net/837e5ec7-b96d-470d-b114-b171d1978a9c)]

**Step 2:** Click on “...” and Select “Add request”.
[!(blob:https://littledevil.atlassian.net/2361aec7-ced4-4466-9c15-621238ba9952)]

**Step 3:** If you want to save the request name, you can click on “Save As” at the right top corner, enter the Request name then click on save. 
[!(blob:https://littledevil.atlassian.net/03c37122-3d60-4ab8-8e65-14e80218120b)]
[!(blob:https://littledevil.atlassian.net/8584a11d-ca58-475a-a00c-6558ee07b16f)]

**Step 4:** The Request name (Test1) gets reflected on the Request tab. We shall then select the option GET from the HTTP request dropdown.
[!(blob:https://littledevil.atlassian.net/2e789c11-bb0d-4f0e-a01b-4db2afd0361a)]

**Step 5:** Enter an URL - https://simple-books-api.glitch.me/status in the address bar and click on Send

**Response**
Once a request has been sent, we can see the response code 200 OK populated in the Response. This signifies a successful request and a correct endpoint. Also, information on the time consumed to complete the request (1756 ms) and payload size (226B) are populated.
[!(blob:https://littledevil.atlassian.net/16b2ca70-a6d4-468c-97f8-d84d45c3d1f7)]
