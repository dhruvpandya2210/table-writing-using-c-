include<stdio.h>

int main ()
{
    int ch;
    printf("enter your choice=");
    scanf("%c",&ch)
    switch(ch)
    {
     case 'a':
          printf("your character is vowel");
          break;
     case 'e':
           printf("your character is vowel");
           break;
     case 'i':
           printf("your character is vowel");
           break;
     case 'o':
          printf("your character is vowel");
          break;
     case 'u':
          printf("your character is vowel");
          break;
        default: printf("character is constant");
    
    }
    
    return 0;
}
