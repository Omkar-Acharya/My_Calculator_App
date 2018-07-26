# My_Calculator_App
Simple Calculator App

Packages/Libraries:
•	ExpressionBuilder: This package is a part of ‘net.objecthunter:exp4j:0.4.8’. I have used this library because it provides easy and efficient API’s to compile and execute mathematical expressions. This library is added to build.gradle file.
•	Autofittextview: This package is the part of ‘me.grantland:autofittextview:0.2.+’. This package allows us to resize TextView according to text size. This library is added to build.gradle file.

Project Description:
•	I have developed the project in Kotlin. Use of Funtional Programming pattern is done in the logic used for calling the OnClick listeners for buttons. Following screenshot shows the application icon:- Calculator
 
•	Following screenshot shows the application screen when we open/start the app: 

•	Following screen captures show the working of Multiplication, Division, Addition and Subtraction operations on Calculator app. To perform these operations, I have first constructed the mathematical expression using the digits TextView and pass that expression to ExpressionBuilder to build and execute and finally display the result on the answer TextView. 

•	After pressing ‘C’ button, the screen is cleared as shown in the following figure. To clear the screen, I have cleared the text on the digits TextView with empty string and answer TextView with ‘0’ 

•	To perform negation operation on a digit, ‘+/-‘ button on the calculator should be pressed. We need to first enter the first digit and then press the ‘+/-‘ button as shown in the below figure:
 
•	To perform negation, I have converted the digits TextView String digit to Integer and then multiply it with -1 and then append the converted string digit to the TextView. The below code snippet shows the working of negation operation. We can also perform negation on the evaluated expression’s answer.

•	To perform Undo operation, press the backspace button on the calculator. I have made use of substring method of String class to cut the last index element from the digits TextView String. 
 
•	Arithematic Exception Handling: ‘Division by Zero’
 
