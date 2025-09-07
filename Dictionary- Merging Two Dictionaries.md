## AIM
To  to display the remarks for the grade using simple if statement


## ALGORITHM
Step 1: Start the program. 
Step 2: Take the necessary input(s) from the user.
Step 3: Process the input(s) using suitable operations or conditions. 
Step 4: Display the result/output to the user. Step 5: Stop the program.

## PROGRAM
```
#include<stdio.h>
int main(){
    char grade;
    scanf("%c",&grade);
    if(grade == 'A' || grade == 'a'){
        printf("Excellence\n");
    }
    else if(grade == 'B' || grade == 'b'){
        printf("Very Good");
    }
    else if(grade == 'C' || grade =='c'){
        printf("Fair");
    }
    else if(grade == 'D' || grade == 'd'){
        printf("Bad");    
    }
    else if(grade == 'E' || grade == 'e'){
        printf("Fail");
    }
}

```
## OUTPUT
<img width="696" height="202" alt="image" src="https://github.com/user-attachments/assets/36ecbf20-169c-45b1-9dba-d0f0c2490293" />

## RESULT
The program was executed successfully
