# EX-NO-6-Pseudo-Random-Number

# AIM: 

Implementation of Pseudorandom Number Generation Using Standard library

# PROGRAM:
NAME: RESHMA C
REG NO: 212223040168
~~~
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() 
{
    int count, min, max;
    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &count);
    printf("Enter the minimum value: ");
    
    scanf("%d", &min);
    printf("Enter the maximum value: ");
    scanf("%d", &max);
    srand(time(NULL));
    printf("Pseudorandom numbers:\n");   
    for (int i = 0; i < count; i++) 
    {
        int random_number = (rand() % (max - min + 1)) + min;
        printf("%d ", random_number);
    }
    return 0;
}
~~~
# OUTPUT:
   ![image](https://github.com/user-attachments/assets/e7ba7798-4ef0-4819-be33-80f4b561cb2f)

# RESULT:
Thus the Implementation of Pseudorandom Number Generation Using Standard library was executed successfully.



