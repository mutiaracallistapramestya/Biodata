# Biodata
#include <iostream>
using namespace std;
int main () {
	
	//----- Mutiara Callista Pramestya-2117051013 -----//

//---string---//
string Nama;
string Jurusan;
string Alamat;
string NPM;


//---input---//
cout << "Masukkan Nama     :"; 
getline(cin,Nama); 
cout << "Masukkan Jurusan  :"; 
getline(cin,Jurusan); 
cout << "Masukkan NPM      :"; 
getline(cin,NPM); 
cout<< "Masukkan Alamat    :"; 
getline(cin,Alamat); 
cout << "                              " << endl;


//---output---//
cout<< "=======Biodata=======" <<endl;
cout<<"Nama      :" << Nama << endl ;
cout<<"Jurusan   :"<< Jurusan << endl;
cout<<"NPM       :" << NPM <<endl;
cout<<"Alamat    :" << Alamat <<endl;
cout<< "=====================";

	return 0;
}
