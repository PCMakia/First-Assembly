# First-Assembly
First Assembly program converted from C++ code.

The program promt user to enter 3 numbers. It outputs the biggest number out of 3 and the sum of the 3 numbers.

The Assembly code (main.txt) can be copied and paste on "source" tab of PEP/9 virtual environment
PEP/9 : https://computersystemsbook.com/5th-edition/pep9/

# C++ original code
int x; 

int y; 

int z; 

int large; 
 
void getNum( ) { 
  cout << “Enter three numbers: ” << endl; 
  cin >> x; 
  cin >> y; 
  cin >> z; 
} 
 
void largest( ) { 
  if ( ( x > y ) && ( x > z ) ) { 
    large = x; 
  } 
  else if ( y > z ) { 
    large = y; 
  } 
  else { 
    large = z; 
  } 
} 
 
int main( ) { 
  int sum; 
  getNum( ); 
  largest( ); 
  sum = x + y + z; 
  cout << “The largest is ” << large << endl; 
  cout << “The sum is ” << sum << endl; 
}
