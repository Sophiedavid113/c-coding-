Text print
#include <iostream>
using namespace std;

int main() {
    cout << "Hello World";
    return 0;
}
....................................................................
                  Variable and data type 
Variable 
dataType variableName = value;   Syntax 
  Int age = 20;
  Int watch = 3800;
 Datatype 
 int number = 1234;
 String name = "Muhammad";
  Boolean true/false = true;
  Float decimal number = 123.542;
....................................................................
                            Operator in c++
   arithmetic operator 
#include <iostream>
using namespace std;

int main() {
    int a = 10;
    int b = 3;

    cout << a + b << endl;
    cout << a - b << endl;
    cout << a * b << endl;
    cout << a / b << endl;
    cout << a % b << endl;

    return 0;
}
....................................................................
      comparison operator 
 int age = 20;

cout << (age >= 18);   true/false ke liye 
....................................................................
    Assignment operator 
 int x = 10;
x += 5;
cout << x;
....................................................................
Logical operator 
And    dono condition true honi chayia 
Or       dono me se ik condition true honi chayia 
....................................................................
                         If and else
 If 
int age = 20;

if (age >= 18) {
    cout << "You can vote";
}

#include <iostream>
using namespace std;

int age = 15;

if (age >= 18) {
    cout << "Adult";
}
else {
    cout << "Not Adult";
}
....................................................................
                               Loop 
  for(int i = 1; i <= 5; i++) {
    cout << i << endl;
}
....................................................................
   While
int i = 1;

while(i <= 5) {
    cout << i << endl;
    i++;
}
....................................................................




   Function
Syntax 
returnType functionName(parameters) {
    // code
}
....................................................................
#include <iostream>
using namespace std;

void hello() {
    cout << "Hello World";
}

int main() {
    hello();
    return 0;
}
Answer hello world 
....................................................................
                                Array        

 #include <iostream>
using namespace std;

int main() {
    int numbers[5] = {10, 20, 30, 40, 50};

    for (int i = 0; i < 5; i++) {
        cout << numbers[i] << " ";
    }

    return 0;
}
....................................................................
         Class
class Student {
public:
    string name;
    int age;

    void display() {
        cout << name << " " << age;
    }
};
....................................................................

