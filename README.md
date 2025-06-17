# Destructor
#include <iostream>
using namespace std;

class abc 
{
public:
    
    abc() 
    {
        cout << "Constructor is called." << endl;
    }

    
    ~abc() 
    {
        cout << "Destructor is called." << endl;
    }

    void putresult() 
    {
        cout << "Hello users!!" << endl;
    }
};

int main() 
{
    cout << "Entering main function." << endl;

    abc obj;  

    obj.putresult();

    cout << "Exiting main function." << endl;

    

    return 0;
}

