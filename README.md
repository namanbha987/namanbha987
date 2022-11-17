// logical operator


#include<iostream>
using namespace std;

int main() {
   int a = 3, b = 2;

   if(a < b) {
      cout<< a << " is less than " << b;
   }
   else if(a > b) {
      cout<< a << " is greater than " << b;
   }
   else if(a == b){
      cout << a << " is equal to " << b;
   }
   return 0;
}
  
  
 // assignment operator 
  
  #include <iostream>
using namespace std;
  
int main() 
{ 
  
  //logical operattors
  
    // Assigning value 10 to a 
    // using "=" operator 
    int a = 10; 
    cout << "Value of a is "<<a<<"\n"; 
  
    // Assigning value by adding 10 to a 
    // using "+=" operator 
    a += 10; 
    cout << "Value of a is "<<a<<"\n"; 
  
    // Assigning value by subtracting 10 from a 
    // using "-=" operator 
    a -= 10; 
    cout << "Value of a is "<<a<<"\n"; 
  
    // Assigning value by multiplying 10 to a 
    // using "*=" operator 
    a *= 10; 
    cout << "Value of a is "<<a<<"\n"; 
  
    // Assigning value by dividing 10 from a 
    // using "/=" operator 
    a /= 10; 
    cout << "Value of a is "<<a<<"\n"; 
  
    return 0; 
}

  
  // comparison operator
  #include <iostream>
int main()
{
    std::cout << std::boolalpha;
    int n = -1;
 
    int n2 = 1;
    std::cout << " -1 == 1? " << (n == n2) << '\n'
              << "Comparing two signed values:\n"
              << " -1  < 1? " << (n < n2) << '\n'
              << " -1  > 1? " << (n > n2) << '\n';
 
    unsigned int u = 1;
    std::cout << "Comparing signed and unsigned:\n"
              << " -1  < 1? " << (n < u) << '\n'
              << " -1  > 1? " << (n > u) << '\n';
 
    static_assert(sizeof(unsigned char) < sizeof(int),
                  "Can't compare signed and smaller unsigned properly");
    unsigned char uc = 1;
    std::cout << "Comparing signed and smaller unsigned:\n"
              << " -1  < 1? " << (n < uc) << '\n'
              << " -1  > 1? " << (n > uc) << '\n';
}
