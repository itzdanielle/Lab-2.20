# Lab-2.20
#include <iostream>
using namespace std;

int main()
{
  double pi = 3.14159;
  double radius = 5.4;
  double circumference = 33.9292; // definition of circumference
  double area = 91.0668; // Fill in code to define an area variable
  double diameter = 10.8;// Fill in code to define a diameter variable
  
  circumference = 2 * pi * radius; // computes circumference
  area = 2 * pi * radius;// Fill in code to compute the area of a circle
  diameter = 2 * radius; // Fill in code to compute the diameter of a circle

  cout << "The circumference of the circle is " << circumference << endl;
  cout << "The area of the circle is " << area << endl; // Fill in code for a cout statement to output the area
  cout << "The diameter of the circle is " << diameter << endl; // Fill in code for a cout statement to output the diameter
  
}
