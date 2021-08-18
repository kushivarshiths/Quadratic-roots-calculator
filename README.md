#include <iostream>
#include <cmath>

int main() {
  
  double a;
  double b;
  double c;
  
  std::cout << "Enter x^2 coeffcient: ";
  std::cin >> a;
  
  std::cout << "\nEnter x coeffficient: ";
  std::cin >> b;
  
  std::cout << "\nEnter constant: ";
  std::cin >> c;
  
  double root1;
  double root2;

root1 = (-b + std::sqrt(std::pow(b,2) - (4*a*c)))/2;  

root2 = (-b - std::sqrt(std::pow(b,2) - (4*a*c)))/2; 

std::cout << "The Roots of the Equation is: " << root1 << "  " << root2;
}
