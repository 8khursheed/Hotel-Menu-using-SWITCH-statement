#include <stdio.h>

int main()
{
    int choice ;
do
    {
    printf("-- Welcome to the cafe--\n");
    printf("1. Tea\n");
    printf("2. coffee\n");
    printf("3. Burger\n");
    printf("4. Pizza\n");
    printf(" Please enter your choice 1-4\n");


    scanf("%d",&choice);

   switch (choice){
    case 1:
        printf("you choose tea");
        break;
    case 2:
        printf("you choose cofffee");
        break;
    case 3:
        printf("you choose burger");
       break;
    case 4:
        printf("you chose pizza");
        break;
    default:
        printf("Invalid choice please try again");



   }

}
 while(choice!=4);
return 0;
}
