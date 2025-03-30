In the current project for task 4.1P we have created a functioning calculator which works using microservices with express and node.js .

The calculator contains 4 mathamatical functions which involve addition,subtraction multiplication and division. We use the GET method for each of the four methods.
The API endpoints for the 4 methods are /add,/subtract,/multiply and /divide

//Addition
We add num1 and num 2 to receive the sum of both numbers

//subtract
We subtract num2 from num1 here

//multiply
we multiply num1 and num2

//divide
We divide num1 with the value of num2 here

For error handling in the code we have added an invalid input error for all 4 operations in the calculator
To avoid a divide by zero error, we have also added a catch for division of numbers by zero in the code

Instructions to run program:
Run the following commands in your terminal(Individually)
git clone https://github.com/Zappymanwho/sit323-2025-prac4p.git
cd sit323-2025-prac4p
npm install
node index.js

After this an example of each operation is displayed below:
http://localhost:3060/add?num1=10&num2=5

http://localhost:3060/subtract?num1=10&num2=5

http://localhost:3060/multiply?num1=10&num2=5

http://localhost:3060/divide?num1=10&num2=5
