# Jam-Of-The-Month-Club
A small project based on the "Jam and Jelly Of the Month Club," written in C++.
A Udemy based project course.

#include <iostream>
using namespace std;

int main ()

{

   Char whichPackage;
   Int  howManyJams = 0;
   Int monthlyFee = 0;
   Int jamsIncluded = 0;
   Int jamPrice = 0;
   Int totalCost;

   Cout << "Which package do you own? A, B, or C " << endl;
   Cin >> whichPackage;

   Cout << "How many jams, jellies, or preserves did you purchase this month?" << endl;
   Cin >> howManyJams;

   // the values for the monthly packages
   If (whichPackage == 'A' || whichPackage == 'a')
   
   {
     
      monthlyFee = 8;
      jamsIncluded = 2;
      jamPrice = 5;
    
   }

   Else if (whichPackage == 'B' || whichPackage == 'b')

   {
  
     monthlyFee = 12;
     jamsIncluded = 4;
     jamPrice = 4;
  
   }

   else if (whichPackage == 'C' || whichPackage == 'c')

   {

     monthlyFee = 15;
     jamsIncluded = 6;
     jamPrice = 3;

   }

   else
   {
      cout << "You selected a non-existent package" << endl;

   }
