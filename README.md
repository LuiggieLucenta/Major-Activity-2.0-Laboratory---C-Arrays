# Major-Activity-2.0-Laboratory---C-Arrays
#include <stdio.h>
int main()
{
    
    int id;
    int pin;
    int account[3][2];

    account[0][0] = 1;
    account[0][1] = 20;
    account[1][0] = 2;
    account[1][1] = 30;
    account[2][0] = 3;
    account[2][1] = 40;

    printf("ID number:");
    scanf("%d", &id);
    printf("Enter password:");
    scanf("%d", &pin);

    if (id == account[0][0], pin ==account[0][1]){
        printf("Succesfully logged in ID#: %d",account[0][0], account[0][1]);
    }else if (id ==account [1][0], pin == account[1][1]){
        printf("Succesfully logged in ID#: %d", account[1][0], account[1][1]);
    }else if (id == account [2][0],pin == account [2][1]){
        printf("Succesfully logged in ID#: %d", account[2][0], account[2][1]);
    }else

    printf("Wrong ID/PIN");
    return 0;
}
