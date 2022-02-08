# Array-of-structure//Array of structures//
#include<iostream>
#include<string> // Using this to include string class//
using namespace std;
struct person{
	string name;
	int age;
	double salary;
};
int main()
{
	{
		person p[2];
		cout<<"Enter 2 persons details like name,age,salary "<<endl;
		
			for(int i=0;i<2;i++)
			{
				cin>>p[i].name;
				cin>>p[i].age;
				cin>>p[i].salary;
			}
		cout<<"Details of users "<<endl;
		for(int i=0;i<2;i++)
		{
			cout<<"Details of person "<<(i+1)<<endl;
			cout<<"Name: "<<p[i].name<<endl;
			cout<<"Age: "<<p[i].age<<endl;
			cout<<"Salary: "<<p[i].salary<<endl;
			}
			return 0;	
			
		
	}
}

