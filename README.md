# SWAPPING BY REFERENCE

#include < iostream >

using namespace std;

void swap(int&, int&);

int main()

{

   int a = 20, f = 35;
   
   swap(a, f);
   
   cout << "The value of a is: " << a << endl;
   
   cout << "The value of f is: " << f << endl;
   
   return 0;
   
}

void swap(int &a, int &f)

{

	int j;
   
	j = a;
   
	a = f;
   
	f = j;
   
}
