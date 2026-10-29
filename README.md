# EX-NO-6-Pseudo-Random-Number
Implementation of pseudorandom number generation in C using the standard library functions rand(), srand(), and time() for a Cryptography laboratory experiment.

## Name: Joshna.M
## Reference Number: 212225230118

# AIM:
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries. Seed the random number generator using the current time(i.e) rand(time(0)); Get the number of randon number to generate. Pass the value for number of iterations and print the numbers. End the program.

# PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
{
    int n, i;

    srand(time(0));

    printf("Enter the number of random numbers: ");
    scanf("%d", &n);

    printf("Pseudorandom numbers are:\n");

    for (i = 0; i < n; i++)
    {
        printf("%d\n", rand());
    }

    return 0;
}
```
# OUTPUT:

<img width="958" height="253" alt="AdobeExpressPhotos_30eee296538646fc824bde197df928fa_CopyEdited" src="https://github.com/user-attachments/assets/ee50594b-cfcd-485c-9bd9-4be0cfd931f1" />

# RESULT:
Thus, the C program to generate pseudorandom numbers using the standard library functions srand() and rand() was implemented and executed successfully.

