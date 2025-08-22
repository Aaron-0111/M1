# EX-01-Datatypes-Operators
## AIM:
Write a C program to read a character input from the user and display its equivalent ASCII value.

## ALGORITHM:
```
1.Start the program.
2.Declare a character variable ch.
3.Initialize ch .
4.Input a character from the user using scanf.
5.Print the ASCII value of the character:
```
## PROGRAM:
```
#include <stdio.h>
int main()
{
    char ch='r';
    scanf("%c",&ch);
    printf("ASCII value of %c is %d",ch ,ch);
    return 0;
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/96219cd0-80b4-4e0c-ad7f-bd4507f39b60)













## RESULT:
Thus the program to read a character input from the user and display its equivalent ASCII value has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to check whether the grade is A grade using simple if statement?

# ALGORITHM:
1.	Declare a variable to store the char.
2.	Use the scanf function to read the value of A from the user.
3.	Check if the character a is equal to 'A'.
4.	If true, print "Grade is A".. 
5.	Otherwise, print nothing.
6.End the program.

# PROGRAM:
```
#include<stdio.h>
int main()
{
char a;
scanf("%c",&a);
if(a=='A')
{
    printf(" Grade is A");
}
return 0;
}
```

# OUTPUT:



![image](https://github.com/user-attachments/assets/9cf2ebae-a326-48d0-880a-6e00812ceba9)








# RESULT:
Thus the program to check whether the grade is A grade using simple if statement has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a C program to find a maximum of two integers using a conditional operator. Get the two integer values as inputs.

## ALGORITHM:
1.	Declare two integer variables a and b.
2.	Input two integers from the user using scanf.
3.	Compare the two integers:
4.	If a is greater than b, print that a is the maximum.
5.	Else, print that b is the maximum.
6.	end the program
.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    int a,b;
    scanf("%d %d",&a,&b);
    if (a>b)
    {
        printf("Maximum between %d and %d is %d",a,b,a);
    }
    else 
    printf("Maximum between %d and %d is %d",a,b,b);
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/d87cb55d-d211-4a3f-a73c-3409d92b22df)








## RESULT:
Thus the program  to find a maximum of two integers using a conditional operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to read a number and check whether the number is divisible by 5 or not using  if else

## ALGORITHM:
1.	Start the program.
2.	Declare an integer variable a.
3.	Input an integer from the user using scanf.
4.	Check if a is divisible by 5
5.	Use the condition a % 5 == 0.
6.	if true, print "Divisible by 5".
7.	Else, print "Not Divisible by 5".
8.	End the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
int a;
scanf("%d",&a);
if(a%5==0)
{
    printf("Divisible by 5");
}
else
{
    printf("Not Divisible by 5");
}
    
 return 0;   
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/89880dab-2f9a-4722-997e-5d2f288ac388)








	

## RESULT:
Thus the program to read a number and check whether the number is divisible by 5 or not using  if else has been executed successfully



# EX-05-  Program to find the largest among three numbers or check if they are equal
## AIM:
Write a C program to read three values A, B, C, and print which one is largest or all are equal using an else-if conditional statement
## ALGORITHM:
1.	Start
2.	Declare three integer variables: a, b, and c.
3.	Input three integers from the user using scanf.
4.	Compare the numbers:
5.	If a is greater than both b and c, print "A is largest".
6.	Else if b is greater than both a and c, print "B is largest".
7.	Else if c is greater than both a and b, print "C is largest".
8.	Else (if none is greater than the others), print "A, B, C are equal".
9.	 End the program
## PROGRAM:
```
#include <stdio.h>
int main()  
{
    int a,b,c;
    scanf("%d%d%d",&a,&b,&c);
    if (a>b&&a>c)
    {
        printf("A is largest");
    }
    else if (b>a && b>c)
    {
        printf("B is largest");
    }
    else if (c>a && c>b) {
    printf("C is largest");}
    else 
    {
        printf("A, B, C are equal");
    }
    return 0;
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/c88faa1f-9f7f-4e11-8615-3ad4344a11bb)


## RESULT:
The program successfully find the largest among three numbers or check if they are equal

















## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to read A values and check whether A is positive number or not.

# ALGORITHM:
1.	Declare a variable to store the input value A.
2.	Use the scanf function to read the value of A from the user.
3.	Check if the value of A is greater than zero.
4.	If A is greater than zero, print a message indicating that it's a positive number. 
5.	Otherwise, print a message indicating that it's not a positive number.
6.End the program.

# PROGRAM:

# OUTPUT:











# RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a program to find minimum between two fraction numbers using conditional operator or ternary operator.

## ALGORITHM:
1.	Declare variables to store the two fraction numbers and the result.
2.	Use the printf function to prompt the user to enter the first fraction number (numerator and denominator separately).
3.	Use the scanf function to read the numerator and denominator of the first fraction.
4.	Repeat steps 2 and 3 to get the second fraction from the user.
5.	Calculate the decimal values of both fractions by dividing the numerators by the denominators.
6.	Use the conditional (ternary) operator to compare the decimal values and store the minimum value in the result variable.
7.	Print the minimum value.

## PROGRAM:

## OUTPUT:









## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to check whether the input value is equal to 1 using simple if statement

## ALGORITHM:
1.	Declare a variable to store the input value.
2.	Use the scanf function to read the input value from the user.
3.	Use an if statement to check if the input value is equal to 1.
4.	If the condition in the if statement is true, print a message indicating that the input value is equal to 1.
5.	Otherwise, print a message indicating that it's not equal to 1.
6.	End the program.

## PROGRAM:

## OUTPUT:









	

## RESULT:
Thus the program to check whether the input value is equal to 1 using simple if statement has been executed successfully



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
To write a C program that reads marks of three subjects, calculates the total and percentage, and then determines the division (First, Second, Pass, or Fail) based on the percentage and minimum marks criteria.
## ALGORITHM:
1.	Start
2.	Declare integer variables m1, m2, m3 for marks, and float variables tot, per.
3.	Input the marks for three subjects.
4.	Calculate total marks: tot = m1 + m2 + m3
5.	Calculate percentage: per = tot / 3
6.	Display total and percentage.
7.	Check if all marks are greater than or equal to 40:
8.	If yes:
a.	If percentage >= 60: Print “Division = First”
b.	Else if percentage >= 48: Print “Division = Second”
c.	Else if percentage >= 36: Print “Division = Pass”
9.	Else: Print “Division = Fail”
10.	End
## PROGRAM:

## OUTPUT:

## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

