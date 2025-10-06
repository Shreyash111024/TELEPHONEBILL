# TELEPHONEBILL
Calculation of telephone bill


#include<stdio.h>

int main()
{
    
        int id;
         char name[20];
         char adrs[35];
         float call;
         float cost=2.50;
        

        printf("Enter Id:");
        scanf("%d",&id);
        printf("Enter Name:");
      scanf("%s",&name);
           printf("Enter address:");         
         scanf("%s",&adrs);
           printf("Call Made:");         
         scanf("%f",&call);
          printf(" TELEPHONE BILL REPORT\n ");
         printf("Bill id: %d\n",id);
        printf("Customer Name: %d\n",id);
        printf("Customer Address: %s\n",adrs);
        printf("Cost/Call Rate:%f \n",cost);
        float bill=call*call;
        printf("Total Bill:%f \n",bill );
          printf(" Billing  Date: 06-10-2025 \n ");
          printf(" Due  Date: 16-10-2025 \n ");
          printf(" \n ");
          printf(" please pay bill before due date, otherwise extra charges i.e RS=2 per call\n ");
    return 0;
}
