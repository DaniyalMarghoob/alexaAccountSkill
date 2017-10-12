# alexaAccountSkill
Amason echo dot account linking skill to check status of you email account using voice recognition.

This skill allow user to check status of its Gmail account using Amazon echo dot. Code in this repo explains the algorithm that invokes AWS support and Gmail acount at same time.
It is request\response based solution, where echo dot uses lambda function of AWS and send request to gmail account and receives the response.

Language used in this project is Node.js. Modules that are required for this project are winston for debugging and chai for implementation of test cases.
Test cases are useful for debuuging when some new feature will be integrated in previous one.

Main source code file is index.js where as all the test cases are in test.js file.
