# finding-the-total-number-of-student-in-the-class-and-absent-student-in-the-class-boys-girls-
by using this program we can easily find  how many student are absent in the class and total student  in the class 
#include<stdio.h>
int main()
{
	int a,b,c,d,e,f,g,h,i;
	printf("inter the total count of boys in the class:\n");
	scanf("%d",&a);//total boys in th e class
   
	printf("inter the total count of girls in the class:\n");
	scanf("%d",&b);//total girls in the class
    
	c = a + b;
	printf("total number of student in class %d \n",c);
    
	printf("inter the how many boys are present in class :\n");
	scanf("%d",&d);
	e = a - d;
	printf("how many boys are apsent in the class %d \n",e);
    
	printf("inter the how many girls are present in class :\n");
	scanf("%d",&f);
	g = b - f;
	printf("how many girls are apsent in the class %d \n",g);
	
	return 0;
}
