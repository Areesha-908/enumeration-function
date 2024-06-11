#include<iostream>
using namespace std;
enum days_of_week {sun,Mon,Tue,wed,Thu,Fri,sat};
int main()
{
 days_of_week day1,day2;
 day1=Thu;
 cout<<day1<<endl;
 day2=Mon;
 cout<<day2<<endl;
 int diff=day2-day1;
 if(day2<day1)
 diff*=-1;
 cout<<"days between="<<diff<<endl;
 return 0;
}
