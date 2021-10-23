# prac9
 First Repository
#include <stdio.h>
int main() {
   // printf() displays the string inside quotation
   printf("Hello, World!");
   int number1, number2, sum;
    
    printf("Enter two integers: ");
    scanf("%d %d", &number1, &number2);

    // calculating sum
    sum = number1 + number2;      
    
    printf("%d + %d = %d", number1, number2, sum);
   return 0;
}