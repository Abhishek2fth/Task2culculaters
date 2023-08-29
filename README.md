include <iostream>
using namespace std;
int main() {
  cout << "hello !, what you want to culculate\nenter first nnumberumber\n";
  int num1,num2;
  cin>>num1;
  cout<<"1. enter '+' for adding\n2. enter '-' substrating\n3. enter '*' for multiplying\n4. enter '/' for dividing\n5. enter '!' for remainder\n";
  char operater;
  cin>>operater;
  cout <<"enter second number \n";
  cin>>num2;

  switch (operater)
    {
      case '+':
        {
          cout<< num1+num2<<endl;
          break;
        }
      case '-':
        {
          cout<< num1-num2<<endl;
          break;
        }
      case '*':
        {
          cout<< num1*num2<<endl;
          break;
        }
      case '/':
        {
          cout<<num1/num2<<endl;
          break;
        }
      case '!':
        {
          cout<< num1%num2<<endl;
          break;
        }
      default:
        {
          cout <<"OPERATER ERROR \ntry again\n";
          break;
        }
    }
  return 0;
}
