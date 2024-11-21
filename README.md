#include <iostream>
#include <string>

using namespace std;

int main(){ 
cout<<"Welcome to AI Chatbot"<<endl;
string userInput;
cout<<"How can i assist you today"<<endl;
cin>>userInput;

if (userInput== "hi"){
	 		cout<<"hi there";
	 		}
             else if (userInput== "how are you"){
	 		cout<<"I am fine";
	 		}
             else if (userInput== "who are you"){
	 		cout<<"I am basic chatbot designed by shayan during his internship at codealpha";
	 		} 
             else {
             cout<<"sorry i am not capable of that";
             }

    return 0;
}
    
