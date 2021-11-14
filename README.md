#include <iostream>
using namespace std;
int main()
{
    int x=1;
    int y=1;
    while (x <=7) 
    {
        y=x;
        while(y <=7)
        {
            cout<<"*";
            y++;
        }
    cout<< endl;
    x++;
    }
}
