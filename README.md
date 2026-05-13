# EX-NO-6-Pseudo-Random-Number
```
NAME: SANTHOSH S
REG.NO: 212224100052
```
# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library
# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.
# PROGRAM:
```c
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
int main() {
    int i, n;
    srand(time(0));
    printf("Enter how many pseudorandom numbers you want to generate: ");
    scanf("%d", &n);
    printf("Generating %d pseudorandom numbers between 0 and 99:\n", n);
     for (i = 0; i < n; i++) {
        int randomNumber = rand() % 100;
        printf("%d ", randomNumber);
    }
    printf("\n");
    return 0;
}
```
# OUTPUT:
<img width="668" height="78" alt="Screenshot 2026-05-13 112729" src="https://github.com/user-attachments/assets/2a12c9a1-052c-4001-a8b4-35b77c2c8260" />

# RESULT:
The program is executed successfully and the output is viewed.

