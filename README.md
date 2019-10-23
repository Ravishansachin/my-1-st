# my-1-st
hello world

/* This is a simple Java program. 
   FileName : "HelloWorld.java". */
class HelloWorld 
{ 
    // Your program begins with a call to main(). 
    // Prints "Hello, World" to the terminal window. 
    public static void main(String args[]) 
    { 
        System.out.println("Hello, World"); 
    } 
} 
#include <stdio.h>
int main()
{
    int firstNumber, secondNumber, sumOfTwoNumbers;
    
    printf("Enter two integers: ");
    // Two integers entered by user is stored using scanf() function
    scanf("%d %d", &firstNumber, &secondNumber);
    // sum of two numbers in stored in variable sumOfTwoNumbers
    sumOfTwoNumbers = firstNumber + secondNumber;
    // Displays sum      
    printf("%d + %d = %d", firstNumber, secondNumber, sumOfTwoNumbers);
    return 0;
}
