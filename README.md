#include <iostream>
using namespace std;

int main() {
    float radius, area;
    const float PI = 3.14159;

 
    cout << "Enter the radius of the circle: ";
    cin >> radius;

    
    area = PI * radius * radius;

 
    cout << "The area of the circle is: " << area << endl;

    return 0;
}



