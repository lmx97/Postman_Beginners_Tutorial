## Collection Runner

Postman Collection Runner is used to execute a Collection having multiple requests together. All the requests within a Collection will be executed simultaneously (at the same time). The Collection Runner does not produce any Response Body.<br/>

The Collection Runner console displays the test results for individual requests. It is mandatory to have more than one request within the Collection to work with Collection Runner.<br/>


**_Example:_** _Execute Tests with Collection Runner_<br/>

**Step 1:** Click on the “Runner” at the bottom right corner.<br/>
![CR_Step1.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/Collection_Runner/CR_Step1.png)<br/>


**Step 2:** Drag the collection and drop into the Run Order there.<br/>
![CR_Step2.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/Collection_Runner/CR_Step2.png)<br/>


**Step 3:** Tick the “Save responses” and then click the “Run Simple Book API”<br/>
![CR_Step3.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/Collection_Runner/CR_Step3.png)<br/>


**Step 4:** The Run Results page shall come up. The pass status is represented in green and failed ones are represented in red. This is the environment in which the tests are executed and the Collection names are visible at the top of the Collection Runner. For each request, the status code, time taken, payload size, and test verification are also displayed.<br/>
![CR_Step4.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/Collection_Runner/CR_Step4.png)