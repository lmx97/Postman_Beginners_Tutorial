## API Tests

Following are the steps to write an api test. Normally we are manually looking for the response information. So let’s us write some code tell postman to do this for us.<br/>


**Step 1:** Switch to the “Tests” tab. Please note that you can write in the “Test” window is programming code it’s javascript.<br/>
![AT_Step1.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/API_Tests/AT_Step1.png)<br/>


**Step 2:** If you aren't proficient in programming, you can go to window called code snippets in the postman. Postman essentially allow you to quickly do a few things with javascript without writing a lot of code. Let’s say we would like to write code to test the status code is 200, then we can click on “Status code: Code is 200”.<br/>
![AT_Step2.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/API_Tests/AT_Step2.png)<br/>


**Step 3:** Once we click on “Status code: Code is 200”, the code will be generated as below. And click on “Send”<br/>
![AT_Step3.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/API_Tests/AT_Step3.png)<br/>

****pm.test** is the function for the test being performed. Status Code is 200 and it is the name of the test which shall be visible in the Test Result after execution.<br/>

****pm.response** is used for obtaining the response and adding assertions on it to verify the header, code, status, and so on.<br/>


**Response**<br/>
After clicking on “Send” you can see on the response part and switch to “Test Results” tab, you will see a path mapping green says status is 200.<br/>
![AT_Response.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/API_Tests/AT_Response.png)