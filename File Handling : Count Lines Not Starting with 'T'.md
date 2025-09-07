## AIM
write a Program to compare two strings without using strcmp().




## ALGORITHM
Step 1: Start the program. 
Step 2: Take the necessary input(s) from the user.
Step 3: Process the input(s) using suitable operations or conditions. 
Step 4: Display the result/output to the user. Step 5: Stop the program.

## PROGRAM
```
#include<stdio.h>
#include<string.h>
int main()
{
    char str1[20];
    char str2[20];
    int value;
    scanf("%s",str1);
    scanf("%s",str2);
    
    
    value=strcmp(str1,str2);
    if(value==0)
    {
        printf("strings are same");
    }
    else {
        printf("strings are not same");
    }
}
```
## OUTPUT
<img width="823" height="230" alt="image" src="https://github.com/user-attachments/assets/8509e7fa-d85b-4785-b08e-4784842fc586" />

## RESULT
The program was executed successfully
