include<stdio.h>

int main()
{
int no=40,guess;
    printf("guess number game 1 to 50!");
    while(1) 
    {
    scanf("%d",&guess);
    if(guess>no) 
    {
    printf("enter smaller number");
    }
    else if(guess<no) 
    {
    printf("enter greater number");
    }
    else
    {
    printf("congratulations is a correct guess");
    break;
    }
    }
    return 0;
}
