#include <iostream>
using namespace std;

int main()
{
   cout<< "Hello, Coffee Machine!" << endl;

   string Latte; 
   string Cappuccino;
   string Espresso;

   switch (1)
   {
      case 1:
         cout << "You have selected Latte." << endl;
         break;
      case 2:
         cout << "You have selected Cappuccino." << endl;
         break;
      case 3:
         cout << "You have selected Espresso." << endl;
         break;
      default:
         cout << "Invalid selection." << endl;
   }
}
