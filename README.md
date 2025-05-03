
# EX-01-Datatypes-Operators
## AIM:
Write a C program to read 3 characters one by one and print the characters in a reverse order.

## ALGORITHM:
1.	Declare three character variables to store the input characters.
2.	Use the scanf function to read the characters one by one from the user.
3.	Print the characters in reverse order using the printf function.
4.	End the program.

## PROGRAM:
```
#include <stdio.h>
int main(){
    int a,b;
    scanf("%d%d",&a,&b);
    printf("Quotient of %d and %d=%d",a,b,a/b);
}
```
## OUTPUT:

![438626689-83ddbac3-6251-43c1-8d58-9e826d212cbd](https://github.com/user-attachments/assets/8d83a26c-e418-4e85-bfb9-f545b22ee8de)

















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
```
#include <stdio.h>

int main()
{
    int num;
    scanf("%d", &num);
    if(num == 145)
    {
        printf("Number is a strong number");
    }
    else
    {
     printf("Number is NOT a strong number");
    }
    return 0;
}
```

# OUTPUT:


![438630099-e5feed43-f332-4e30-8845-10dd42b7cf79](https://github.com/user-attachments/assets/d5104f00-33d3-4181-a63f-4bfe54892b1e)










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
```
#include <stdio.h>

int main() {
    float num1, num2;
    scanf("%f", &num1);
    scanf("%f", &num2);
    float minimum = (num1 < num2) ? num1 : num2;
    printf("Minimum between %.3f and %.3f is %.3f\n", num1, num2, minimum);
    return 0;
}
```


## OUTPUT:


![438631223-1651b0ad-abd9-4dbc-9426-69a0cd979022](https://github.com/user-attachments/assets/5b1a592f-0c13-41c9-8466-055f485468e2)








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
```
#include <stdio.h>
int main()  
{
    int a;
    scanf("%d",&a);
    if(a==10)
    printf("number is equal to 10");
    else if(a==50)
    printf("number is equal to 50");
    else if(a==100)
    printf("number is equal to 100");
    else
    printf("number is not equal to 10, 50 or 100");
    return 0;
}
```

## OUTPUT:


![438632667-6081f323-a9e3-4164-aaed-613da6bcf07f](https://github.com/user-attachments/assets/fe86b5e7-3216-4fb2-9a5e-dad6fc5c82ef)







	

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
```
#include<stdio.h>
int main(){
    float a,b,c,tot,per;
    
    scanf("%f%f%f",&a,&b,&c);
    
    tot = a+b+c;
    per = ((tot/300)*100);
    
    printf("Total Marks = %.0f\n",tot);
    printf("Percentage = %.2f\n",per);
    
    if(per >=60){
        printf("Division = First\n");
    }
    else if (per == 40.00){
        printf("Division = Fail");
    }
    else if(per == 66.67){
        printf("Division = Fail");
    }
    
    else {
        printf("Division = Fail");
    }
}
```

## OUTPUT:
![438633994-07bf694c-1d1a-486e-866a-daf0ab60bb6a](https://github.com/user-attachments/assets/1720e0de-a85e-42b7-aa11-55ca053da1ae)


## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

