## AIM
Write a C program to count the total number of words in a given string using do While loop.




## ALGORITHM
Step 1: Start the program. 
Step 2: Take the necessary input(s) from the user.
Step 3: Process the input(s) using suitable operations or conditions. 
Step 4: Display the result/output to the user. Step 5: Stop the program.

## PROGRAM
```
#include <stdio.h>
#include <string.h>

int main() {
    char str[100];
    int i = 0, words = 0;

    fgets(str, sizeof(str), stdin);
    str[strcspn(str, "\n")] = 0; // Remove trailing newline

    do {
        // Skip whitespace characters
        while (str[i] == ' ' || str[i] == '\t')
            i++;

        // Check if reached end of string
        if (str[i] == '\0')
            break;

        // Move to the next word
        words++;

        // Skip characters until next whitespace or end of string
        while (str[i] != ' ' && str[i] != '\t' && str[i] != '\0')
            i++;
    } while (str[i] != '\0');

    printf("%d\n", words);

    return 0;
}


```
## OUTPUT
<img width="681" height="195" alt="image" src="https://github.com/user-attachments/assets/2e020b1f-dffd-4d6d-a5c7-6b8bc3f82b07" />

## RESULT
The program was executed successfully
