## Postman Variables

Postman has different variable scopes. Those variable scopes are collection variables, global variables. The global variables are available inside the entire workspace for all collections not just for a specific collection or there are also environments.<br/>

Environments are useful if you have different environments. For example, you are developing software and you have a local development environment (local host), you have a testing development environment and you have a production development environment then you can define multiple environments and you can easily switch within them. <br/>


**_Example:_** _use a postman variable to store the order id._


**Step 1:** Click on eye icon at the top right corner and click on “Edit” at the part of Globals.<br/>
![PV_Step1.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/Postman_Variables/PV_Step1.png)<br/>


**Step 2:** Enter the variable (let’s say “orderId”) and also enter the current value (the available orderId) and save it.<br/>
![PV_Step2.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/Postman_Variables/PV_Step2.png)<br/>


**Step 3:** Go to another request and change all the values in the Params tab as {{orderId}}.<br/>
![PV_Step3.png](https://github.com/lmx97/Postman_Beginners_Tutorial/blob/main/image/Postman_Variables/PV_Step3.png)<br/>


**Once you have changed the variable in the environment globals there, the rest of variables in the request will auto change based on the environment globals variable. 
