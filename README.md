# Salary-with-Bonus--uri-online-judge-problem

#include <iostream>
#include<iomanip>
using namespace std;
int main(){
    
    string s;
    cin>>s;
    
    double fix_sal;
    cin>>fix_sal;
    double tot_sal;
    cin>>tot_sal;
    
    double x= (tot_sal)*0.15;
    x= x+ fix_sal;
    cout<<"TOTAL = R$ "<<fixed<<setprecision(2)<<x<<endl;
    
}
