#include<iostream>
#include<string>
using namespace std;
class shantanuclass{
	public:
	void setname(string x) //function used to set the name
	{
		name=x;
	}
	string getname()//fuction used to get the name
	{
		return name;
	}
	private:
		string name;
	
};
int main()
{
	shantanuclass so;
	so.setname("dexter");
	cout<<so.getname();
	return 0;
}
