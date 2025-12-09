#include<iostream>
using namespace std;
int main()
{
      int num;
      cout<<"Enter a number:";
      cin>>num;
      cout<<"the number that you enter is :"<<num<<endl;
      if(num>0){
            if(num%2==0){
                  cout<<"the number is even and positive";
            }
            else{
                  cout<<"the is odd and positive";
            }
      }
      else if (num<0){
            cout<<"the number is negative";
      }
      else{
            cout<<"the number is equal to zero";
      }
      return 0;
}
