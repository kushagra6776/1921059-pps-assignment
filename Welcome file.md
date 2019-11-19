  
[Skip to content](https://mail.google.com/mail/u/1/)  
[Using Gmail with screen readers](https://mail.google.com/mail/u/1/)  

Enable desktop notifications for Gmail. OK No thanks

1 of 6,136

## MD PPS

Inbox

x

![](https://ssl.gstatic.com/ui/v1/icons/mail/profile_mask2.png)

### Guraman Naman <cyberclickgn@gmail.com>

12:01 PM (14 minutes ago)

to me

![](https://mail.google.com/mail/u/1/images/cleardot.gif)

---

# **Programming for Problem Solving**

## **Name** - Kushagra Joshi

## **CRN -1921059**

## **Branch – _IT_-A2**

## **Submitted to:- Ms Ranjodh Kaur **

---

### 1) To print name.

```C

/* Program to print your name */

#include<stdio.h>

int main() {

puts("***************");

puts("Kushagra Joshi");

puts("***************");

return 0;

}

```

### 2) To print College address.

```C

/* College Address */

#include<stdio.h>

int main() {

printf("\n\t\t\tGuru Nanak Dev Engineering College,");

printf("\n\t\t\tGill Road,");

printf("\n\t\t\tLudhiana , Punjab\n");

return 0;

}

```

### 3) Program to add two integers.

```C

/* To add two integers */

#include <stdio.h>

int main() {

int a,b;

printf("\nEnter the numbers....");

printf("\nA:");

scanf("%d",&a);

printf("\nB:");

scanf("%d",&b);

a=a+b;

printf("\n Sum of the number is %d ",a);

return 0;

}

```

### 4) Program to find quotient and remainder.

```C

/* To find quotient and remainder */

#include <stdio.h>

int main() {

int a,b,r,q;

printf("\nEnter the Dividend:");

scanf("%d",&a);

printf("\nEnter the divisor:");

scanf("%d",&b);

r=a%b;

q=a/b;

printf("\nRemainder: %d",r);

printf("\nQuotient: %d",q);

return 0;

}

```

### 5) Program to swap two variables without 3rd variable.

```C

/* Swapping without 3rd variable */

#include <stdio.h>

int main() {

int a,b;

printf("\nEnter the value of A:");

scanf("%d",&a);

printf("\nEnter the value of B:");

scanf("%d",&b);

a = a + b;

b = a - b;

a = a - b;

printf("\nA: %d",a);

printf("\nB: %d",b);

return 0;

}

```

### 6) Program to check even odd number.

```C

/* To find whether number is even or odd */

#include<stdio.h>   int main()

{

int x;

printf("enter an integer \n"); 

scanf("%d",&x);

if(x%2==0) 

printf("even\n");

else 

printf("odd\n");

return 0;

}

```

### 7) Finding greteast of two numbers.

```C

/* Largest one in two */

#include<stdio.h>

int main()

{

int a,b;

printf("enter the two integers a and b respectively \n");

scanf("%d%d",&a,&b);

if(a==b)

printf("Both the numbers are equal\n");

else

{

if(a>b)

printf("a is greater than b\n",a);

else

printf("b is greater than a\n",b);

}

return 0;

}

```

### 8) Find greatest of three number .

```C

/* Largest of three number */

#include<stdio.h>

int main()

{

int x,y,z;

printf("enter the 3 integers -a,b,c respectively \n");

scanf("%d%d%d",&x,&y,&z);

if(x>y && x>z)

printf("a is the greatest number \n",x);

else

{ 

if(y>x && y>z)

printf("b is the greatest number \n",y);

else

printf("c is the greatest number \n",z);

}

return 0; 

```

### 9) Program to assign grade to student according to percentage.

```C

/* To find grade of a student by marks */

#include<stdio.h>

int main() {

int s1,s2,s3,s4,s5,agg;

float perc;

printf("Enter the Marks in 5 Subjects Respectively:\n");

scanf("%d%d%d%d%d",&s1,&s2,&s3,&s4,&s5);

agg=s1+s2+s3+s4+s5; // Aggregate Marks

perc=agg/500.0*100; // Perc Marks

if(perc>=90)

{

printf("\nA");

}

else if (perc>=80 && perc<90)

{

printf("\nB");

}

else if(perc>=70 && perc<80)

{

printf("\nC");

}

else if(perc>=60 && perc<70)

{

printf("\nD");

}

else if(perc>=50 && perc<60)

{

printf("\nE");

}

else

{

printf("\nScope of Improvement....");

}

return 0;

}

```

### 10) Program to print roots of quadratic equation.

```C

/*Program to print roots */

#include <stdio.h>

#include <stdlib.h>

#include <math.h>

int main() {

float a, b, c, root1, root2;

float realp, imagp, disc;

printf("Enter the values of a, b and c \n");

scanf("%f %f %f", &a, &b, &c);

/* If a = 0, it is not a quadratic equation */

if (a == 0 || b == 0 || c == 0)

{

printf("Error: Roots cannot be determined \n");

exit(1);

}

else

{

disc = b * b - 4.0 * a * c;

if (disc < 0)

{

printf("Imaginary Roots\n");

realp = -b / (2.0 * a) ;

imagp = sqrt(abs(disc)) / (2.0 * a);

printf("Root1 = %f +i %f\n", realp, imagp);

printf("Root2 = %f -i %f\n", realp, imagp);

}

else if (disc == 0)

{

printf("Roots are real and equal\n");

root1 = -b / (2.0 * a);

root2 = root1;

printf("Root1 = %f\n", root1);

printf("Root2 = %f\n", root2);

}

else if (disc > 0 )

{

printf("Roots are real and distinct \n");

root1 =(-b + sqrt(disc)) / (2.0 * a);

root2 =(-b - sqrt(disc)) / (2.0 * a);

printf("Root1 = %f \n", root1);

printf("Root2 = %f \n", root2);

}

}

return 0;

}

```

### 11) Program to check year is leap or not.

```C

/* To find whether year is leap or not */

#include<stdio.h>

int main()

{

int year;

printf("enter a year :");

scanf("%d",&year);

if(year%4==0)

{ if(year%100==0)

{

 if(year%400==0)

printf("%d is a leap year\n",year);

 else

 printf("%d is not a leap year\n",year);

}

else

printf("%d is a leap year\n",year);

}

else

printf("%d is not a leap year .\n",year);

return 0;

}

```

### 12) Program to print table of 5.

```C

/* Table of 5 */

#include<stdio.h>

int main() { int res;

for(int i=1;i<=10;i++) {

res=5*i;

printf("\n5*%d=%d",i,res);

}

return 0;

}

```

### 13) To make simple calculator using switch case.

```C

/* C Program to Create Simple Calculator using Switch Case */

#include <stdio.h>

int main() {

char Operator;

float num1, num2, result = 0;

printf("\n Please Enter an Operator (+, -, *, /) : ");

scanf("%c", &Operator);

printf("\n Please Enter the Values for two Operands: num1 and num2 : ");

scanf("%f%f", &num1, &num2);

switch(Operator)

{

case '+':

result = num1 + num2;

break;

case '-':

result = num1 - num2;

break;

case '*':

result = num1 * num2;

break;

case '/':

result = num1 / num2;

break;

default:

printf("\n You have enetered an Invalid Operator ");

}

printf("\n The result of %.2f %c %.2f = %.2f \n", num1, Operator, num2, result);

return 0;

}

```

### 14) To calculate reverse of a number.

```C

/* To find reverse of a Number*/

#include<stdio.h>

int main() {

int num,rev=0;

printf("\nEnter the Number:");

scanf("%ld",&num);

while(num!=0)

{

rev = rev * 10;

rev = rev + num%10;

num = num/10;

}

printf("\nReversed number:%d",rev);

printf("\n\n");

return 0;

}

```

### 15) To check whether number is palindrome or not.

```C

/* Palindrome */

#include<stdio.h>

int main()

{

int n , reversedinteger =0,remainder,originalinteger;

printf("enter an integer ");

scanf("%d",&n);

originalinteger=n;

while(n!=0)

{

remainder=n%10;

reversedinteger=reversedinteger*10+remainder;

n/=10;

}

if(originalinteger==reversedinteger)

printf("%d is a palindrome.",originalinteger);

else

printf("%d is not a palindrome",originalinteger);

return 0;

}

```

### 16) To check whether a number is prime or not.

```C

/* Program to check prime no. */

#include<stdio.h>

int main()

{

int n,c=2;

printf("enter a number to check whether it is prime\n");

scanf("%d",&n);

for(c=2;c<n;c++)

{

if(n%c==0)

{

printf("%d isn't prime.\n",n);

break;

}

}

if(c==n)

printf("%d is prime.\n",n);

return 0;

}

```

### 17) Program to print prime number to 100.

```C

/* Prime number from 1 to 100 */

#include<stdio.h>   int main()

{   for(int i=2;i<100;i++)

{ for(int j=2;j<i;j++)

{

if(i%j==0)   break;

else

if(i==j+1)

printf("%d\n",i);

}

}

}

```

### 18) Program to check whether a number is armstrong or not.

```C

/* To check armstrong number */

#include <stdio.h>

int main()

{

int number, originalNumber, remainder, result = 0;

printf("Enter a three digit integer: ");

scanf("%d", &number);

originalNumber = number;

while (originalNumber != 0)

{

remainder = originalNumber%10;

result += remainder*remainder*remainder;

originalNumber /= 10;

}

if(result == number)

printf("%d is an Armstrong number.",number);

else

printf("%d is not an Armstrong number.",number);

return 0;

}

```

### 19) Print Different Patterns.

i) Pattern 1.

```C

#include <stdio.h>

int main() {

int i,j,r;

printf("Enter number of rows: ");

scanf("%d",&r);

for(i=1; i<=r; ++i)

{

for(j=1; j<=i; ++j)

{

printf("%d ",j);

}

printf("\n");

}

return 0;

}

```

### ii) Pattern 2.

```C

#include <stdio.h>

int main() {

int r,i,j,num= 1;

printf("Enter number of rows: ");

scanf("%d",&r);

for(i=1;i<=r;i++)

{

for(j=1;j<=i;++j)

{

printf("%d",num);

++num;

}

printf("\n");

}

return 0;

}

```


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIyOTQwODkzMV19
-->