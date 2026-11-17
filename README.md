# My-file-
Code
#include<stdio.h>
int main()
{
    int cp, sp;
    scanf("%d", &cp);
    scanf("%d", &sp);
  if (cp < sp)
    {
          printf("Profit: %d", sp - cp);
    }
        else if (cp > sp)
    { 
         printf("Loss: %d", cp - sp);
    }
         else
    {
              printf("No profit no loss");
    }

   return 0;
}
