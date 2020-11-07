DOCUMENTATION::
**************************************************************BRIEF**************************************************************************
Author:
            Abhimanyu Gupta (https://github.com/0deadLock0/)
            https://github.com/0deadLock0/Booth-Multiplication/
Functionality:
        Multiply two Decimal numbers (base 10) in their binary forms using Booth's Method of  Multiplication
Purpose:
             Booth Implementation Project for CSE112-Computer Organization at IIIT Delhi
Reference:
                https://en.wikipedia.org/wiki/Booth%27s_multiplication_algorithm

**********************************************************************************************************************************************

******************************************************INPUT/OUTPUT FORMAT*************************************************************
Input:
          * Enter two Decimal Numbers in seprate lines, without any base and all.
Output:
             * The product of two numbers in their decimal form.
**********************************************************************************************************************************************

**********************************************************PROGRAM FLOW******************************************************************
* Two decimal numbers are inputed from the user.
* They are then passed to boothMultiply(int,int) function.
* The function first converts the two inputs into their binary equivalents using toBinary(int,int) method.
* toBinary(int,int) method first get the number of bits required by the binary numbers using the getBinNumLength(int,int).
* Then implementing the procedure for converting Decimal to Binary numbers with the help of get2sComplement(binaryNumber) it converts the two user inputs into their binary form.
* After following the desired pre-requisites it multiply the numbers using the Booth's method as stated in reference mentioned in the Brief.
* The method takes help of binaryAdd(binaryAdd,binaryAdd) method to perform the desired operations when needed.
* At last the function returns the decimal value, the product of two user inputs.

ASSUMPTIONS IN THE FLOW:
* The two user inputs are just Integers and don't have any Floating number part in them. 

**********************************************************************************************************************************************

***************************************************ERROR HANDLING******************************************************************
* Incase of invalid user input the program terminates in accordance with the python's inbuilt error handling mechanism

**********************************************************************************************************************************************

***************************************************INSTRUCTIONS TO RUN******************************************************************
Language and Version Support:
* The program has been completely written in Python 3.8.1.

Method 1:    Using command prompt or terminal
	  *Run the cmd/termial in the folder where code file -"code.py" is present.
	  *Enter "python code.py" (without quotes)
	  *Enter two numbers in decimal format (base 10) in two separate lines.
Method 2:    Using IDE
	  *Compile and run the python code.
	  *Enter two numbers in decimal format (base 10) in two separate lines.

**********************************************************************************************************************************************
