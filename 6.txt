#include <iostream>
using namespace std;
int main()
{
    char ch = 0;
    char f = 0;
    cout << "      0     1     2     3     4     5     6     7     8     9     A     B     C     D     E     F" << endl;
    for(int i = 1; i<16; i++){
        ch = i + 55;
        if (i<10)
            cout << i << "     ";
        else
            cout << ch << "     ";
        for(int j = 0; j<16; j++){
            f = i*16 + j;
            cout << f;
            if(f/100 == 0){
                    cout << "     ";
                }
            else{
                cout << "     ";
            }
        }
        cout << endl;
    }
}