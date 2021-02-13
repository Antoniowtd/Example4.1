# Exercises
## Example 4.1

#include <stdio.h>
int main(){
	
	printf("Antonio, 2009121, May six 2002");
	
	return (0);
}

## Example 4.2

#include <stdio.h> 
 int main() 
 {
	printf("*****\n"); 
	printf("*\n"); 
	printf("*\n"); 
	printf("***\n"); 
	printf("*\n"); 
	printf("*\n"); 
	printf("*****\n"); 

	return(0);
}

## Example 4.3

#include <stdio.h> 
int width;          
int height;         

int area;           
int perimeter;      

int main() {
	height = 5;
	width = 3;

    perimeter = 2*(height + width);
	printf("Perimeter of the rectangle is %d inches\n", perimeter);
	
	area = height * width;
	printf("Area of the rectangle is %d square inches\n", area);

return(0);
}

## Example 4.3.2 with floating

#include <stdio.h> 
float width;          
float height;         

float area;           
float perimeter;      

int main() 
{
	height = 2.3;
	width = 6.8;

    perimeter = 2*(height + width);
	printf("Perimeter of the rectangle is %f/n inches\f", perimeter);
	
	area = height * width;
	printf("Area of the rectangle is %f/n square inches\f", area);

return(0);
}

## Example 4.4

#include <stdio.h> 
 int main() 
 {
	printf("#   #\n");
	printf("#   #\n");
	printf("#   #\n");
	printf("#####\n");
	printf("#   #\n");
	printf("#   #\n");
	printf("#   #\n");
	printf("\n");
	printf("#####\n");
	printf("#\n");
	printf("#\n");
	printf("#####\n");
	printf("#\n");
	printf("#\n");
	printf("#####\n");
	printf("\n");
	printf("#\n");
	printf("#\n");
	printf("#\n");
	printf("#\n");
	printf("#\n");
	printf("#\n");
	printf("#####\n");
	printf("\n");
	printf("#\n");
	printf("#\n");
	printf("#\n");
	printf("#\n");
	printf("#\n");
	printf("#\n");
	printf("#####\n");
	printf("\n");
	printf("#####\n");
	printf("#   #\n");
	printf("#   #\n");
	printf("#   #\n");
	printf("#   #\n");
	printf("#   #\n");
	printf("#####\n");
	return(0);
}

## Example 4.5

Floating point using %d
#include <stdio.h> 
/* height and width of a rectangle in inches */
float width;          
float height;         

float area;           
float perimeter;      

int main() {
	height = 10.3;
	width = 5.34;

    perimeter = 2*(height + width);
	printf("Perimeter of the rectangle = %d inches\n", perimeter);
	
	area = height * width;
	printf("Area of the rectangle = %d square inches\n", area);

return(0);
}

integer using %f
#include <stdio.h> 
/* height and width of a rectangle in inches */
int width;          
int height;         

int area;           
int perimeter;      

int main() {
	height = 10;
	width = 5;

    perimeter = 2*(height + width);
	printf("Perimeter of the rectangle = %f inches\n", perimeter);
	
	area = height * width;
	printf("Area of the rectangle = %f square inches\n", area);

return(0);
}

character using %d
#include <stdio.h>

int main () {

   char greeting[7] = {'A', 'n', 't', 'o', 'n','i','o', '\0'};
   printf("Hellooooo: %d", greeting );
   return 0;
}

## Example 4.6



