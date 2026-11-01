#include <iostream>
#include <cstring>
using namespace std;
class String
{
char *str;

public:
String()
{
str = new char[100];
str[0] = '\0';
}
String(const String &s)
{
str = new char[100];
strcpy(str, s.str);

}
void Accept()
{
cout << "Enter a string: ";
cin >> str;
}
void Display()
{
cout << str << endl;
}
~String()
{
delete[] str;
}
};
int main()
{
String First;
First.Accept();
String Second(First);
cout << "\nFirst string: ";
First.Display();
cout << "Copied string: ";
Second.Display();

return 0;
}
