#include <iostream>
using namespace std;

string nama;
int tgllhr;
int umur;
string dmsl;


int main( int argc, char *arg[])
{
	cout << " Masukkan Nama : " ;
	cin >> nama;
	cout << "\n Masukkan Tanggal lahir: " ;
	cin >> tgllhr;
	cout << "\n Masukkan Umur : " ;
	cin >> umur;
	cout << "\n Domisili : " ;
	cin >> dmsl;
	cout<< "\n " ;
	
	cout << "Nama : " + nama;
	cout << "\n Tanggal lahir : ";
	cout << tgllhr ;
	cout << "\n Umur :  " ;
	cout << umur;
	cout << "\n Domisili : " + dmsl;
}
