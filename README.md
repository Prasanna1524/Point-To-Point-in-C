# Point-To-Point-in-C

        #include<stdio.h>

        int main()
        {
            int a = 15;
            int *ptr = &a;
            int **dptr = &ptr;
            int ***tptr = &dptr;
            //Do Like THis Many More Pointer

            //Print the Address
            printf("Address of a                = %p\n",&a);
            printf("ptr is Pointing to Address  = %p\n",ptr);
            printf("dptr is Pointing to Address = %p\n",dptr);
            printf("tptr is Pointing to Address = %p\n",tptr);

            printf("\nValue of a                       = %d\n",a);
            //Print the Values using Pointer
            printf("Value of Single Pointer(*ptr)    = %d\n",*ptr);
            printf("Value of Double Pointer(**dptr)  = %d\n",**dptr);
            printf("Value of Triple Pointer(***tptr) = %d",***tptr);

            return 0;
        }
