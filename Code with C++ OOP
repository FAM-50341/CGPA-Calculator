#include <iostream>
#include <cmath>
using namespace std;

class CalculateCGPA
{
    int total_course;
    double course_Grade;
    float credit;
    float Sum;
    float CGPA;
    public:
   void show()
   { 
     cout << "**** Thanks for using CGPA CALCULATOR****" << endl;
   }
    void Calculation()
    {
     cout<<"Enter your total course no:";
     cin >> total_course;
         for(int i=0 ; i<total_course ; i++)
        {
            cout<< "Enter your course no"<< " " << i+1 <<" "<< "grade:";
            cin>> course_Grade;
            cout<<endl;
            cout<< "Enter your course no "<< i+1 << " credit :";
            cin>> credit;
            cout<<endl;
            float Multipication = (course_Grade*credit);
            Sum = Sum + Multipication;
        }
            CGPA = Sum/21.75;
            cout<< " Your CGPA is : " << CGPA << endl;
    
    }

};

int main()
{
    CalculateCGPA ob1;
    ob1.Calculation();
    ob1.show();
    return 0;
}
