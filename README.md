#include <stdio.h>
#include<math.h>
int main() 
{
    float s,pd,p,root1,root2,root3;
    printf("enter root1 = ");
    scanf("%f", &root1);
    printf("enter root2 = ");
    scanf("%f", &root2);
    printf("enter root3 = ");
    scanf("%f", &root3);
    s=root1+root2+root3;
    pd=(root1*root2)+(root2*root3)+(root1*root3);
    p=root1*root2*root3;
    printf("sum of ROOTS = %f \n",s);
    printf("product of ROOTS taken two at a time = %f \n",pd);
    printf("product of ROOTS = %f \n",p);
    printf("Equation = x3 -%fx2 + %fx -%f",s,pd,p);
return 0;
}
