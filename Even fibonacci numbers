#include <stdio.h>
int main()
{
    long long x = 0, y = 1, z = 0 , sum = 0;
    while(1){
        if(z >= 4000000){
            break;
        }
        z = x + y;
        x = y;
        y = z;
        if((z%2)==0){
            sum = sum + z;
        }
    }
    printf("SUM = %I64d\n",sum);
    return 0;
}
