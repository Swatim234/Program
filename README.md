# Program in C

#include <stdio.h>
int main(void)
{
int price=300,tax,total_amt;
tax=(price*0.10);   //As the Tax 10% = 10/100
total_amt=(price+tax);
printf("The total price of the laptop is = %d$",total_amt);
return 0;
}
