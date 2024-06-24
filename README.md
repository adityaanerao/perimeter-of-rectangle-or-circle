# perimeter-of-rectangle-or-circle

// finding area and perimeter of rectangle or circle

#include<stdio.h>

void  main(){

    int length,width;
    length= 4;
    width = 2;

    int area = length * width ;
    printf(" area of rectangle is :- %d\n",area);

    int perimeter = 2*(length + width);
    printf("perimeter of rectangle is :- %d\n",perimeter);

    int radius;
    
    radius= 30;

    int Area = 2*3.14* radius*radius;
    int Perimeter = 2*3.14*radius;

    printf("Area of circle is :- %d\n",Area);
    printf("perimeter of circle is :- %d\n", Perimeter);
}
