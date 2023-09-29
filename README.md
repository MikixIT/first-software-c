# first-software-c
first program written in c, an addition between two numbers!

//
//  main.c
//  first-c-software
//
//  Created by Michael Torres on 29/09/23.
//

#include <stdio.h>

int main(void) {
    int num1, num2, sum;
    
    printf("Hey, let's do some addition\n ");
    printf("Enter the first number: ");
    scanf("%d", &num1);
    
    printf("Alright, enter the second number now: ");
    scanf("%d", &num2);
    
    sum=num1+num2;
    printf("Okay, the sum of %d and %d is: %d\n", num1, num2, sum);
    printf("\nHave a good day! by Michael :)\n\n");
    return 0;
}
