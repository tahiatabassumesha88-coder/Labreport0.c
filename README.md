Labreport0.c
This project is a simple C program that checks whether a given year is a leap year or not using conditional statements.

Objective
To understand and implement decision-making (if-else conditions) in C programming.


Concept
A leap year:
- Is divisible by 4 AND not divisible by 100  
- OR divisible by 400  


Algorithm
1. Start  
2. Input year  
3. If year % 400 == 0 → Leap Year  
4. Else if year % 100 == 0 → Not Leap Year  
5. Else if year % 4 == 0 → Leap Year  
6. Else → Not Leap Year  
7. End  

Implementation

#include <stdio.h>

int main() {
    int year;

    printf("Enter a year: ");
    scanf("%d", &year);

    if (year % 400 == 0) {
        printf("%d is a Leap Year.\n", year);
    }
    else if (year % 100 == 0) {
        printf("%d is Not a Leap Year.\n", year);
    }
    else if (year % 4 == 0) {
        printf("%d is a Leap Year.\n", year);
    }
    else {
        printf("%d is Not a Leap Year.\n", year);
    }

    return 0;


}
