	// This Program is not works there is some logical error.
	
	#include<iostream>			// Header File

	#include<stdio.h>
	
	using namespace std;
		
		int main(){
		
		int anInteger;
		
		char myInt [ 20 ];
		
		
		
		cout << " Enter an Integer between 10-100 : ";
		
		cin >> myInt;
		
		
		if ( atoi ( myInt ) == 0 ) {
			
			
			cout << " \n Error : Not a valid Input ";               // could be non numeric 
		}
		
		else {
			anInteger = atoi ( myInt );
			if ( anInteger < 10 || anInteger > 100 ){            // Logic
				cout << " \n Error :  only integer between 10-100 are allowed ! ";  
		
		}
		
		else {
				cout << "\n OK, you have entered " << anInteger;
		
		}
		
		}
	
	return 0;
	
	
	}
	
