# Constants
#include <stdio.h>

int main()
 {
    const float pi = 3.1415926; // Declaring a constant for Pi

    float radius, area;
    
    printf("Enter the radius of the circle: ");


    scanf("%f", &radius);

    
    area = pi * radius * radius; // Using the constant 'pi'
    
    printf("The area of the circle is %f\n", area);
    
    return 0;
}
