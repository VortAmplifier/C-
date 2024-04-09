#include <iostream>                             // include preprocessor directive

using namespace std;                            // request all names from std namespace

double power(int number, double exponent);      // function prototype

int main()                                      // function main starts
{
  int num;                                      // define a variable num
  double expnt;                                 // define a variable expnt
  double result;
  char choice;                                  // define a variable result

  cout << "Welcome to exponentiation" << endl;  // print a message and newline
  cout << "-------------------------" << endl;  // print a message and newline
  cout << endl;                                 // newline

  cout << "Enter a number: ";                   // print a message
  cin >> num;                                   // assign value to num from the terminal

  cout << "Enter an exponent: ";                // print a message
  cin >> expnt;                                 // assign value to expnt from the terminal

  result = power(num, expnt);                   // store return value from power

  cout << num << " to the power of " << expnt << " is: " << result << endl; // print a variable then a message then a variable then a message then a variable

  cout << "Do you wish to continue Y/N: ";      // print message

  cin >> choice;                                // assign a value to choice from the terminal

  while (choice != 'N')                         // while loop check condition choice != 'N'
  {
    if (choice == 'Y')                          // if statement check condition choice == 'Y;
    {
      cout << "Enter a number: ";               // print a message

      cin >> num;                               // assign a value to num from the terminal

      cout << "Enter an exponent: ";            // print a message
      cin >> expnt;                             // assign a value to expnt from the terminal

      result = power(num, expnt);               // assign a result return value from function - power

      cout << num << " to the power of " << expnt << " is: " << result << endl; // // print a variable then a message then a variable then a message then a variable

      cout << "Do you wish to continue Y/N: ";  // print a message
    }
    else                                        // else
    {
      cout << "Invalid Choice";                 // print a message
      break;
    }
  }
  cout << "Quit Success";                       // print a message

  return 0;                                     // return success
}

// function power defined outside main()
double power(int number, double exponent)       // function header return value double arguments int number, double exponent
{
  int pwr = 1;                                    // define a local variable pwr and assign a value 1
  for(int count = 1; count <= exponent; count++)  // for loop define a variable count = 1 ; condition count <= exponent must be true to continue cycling; count++
    pwr *= number;

  return pwr;                                   // return pwr
}
