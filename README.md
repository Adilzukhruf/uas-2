# uas-2
# Ujian Akhir Semester 
<br>Mata Kuliah 	: Dasar pemrograman
<br> Nama		      : Adil zukhruf firdaus
<br>NIM		        :	1227050005
<br>Jurusan		:[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi umum
1. Deret matematika bilangan yang tdk habis dbagi 3 5 7
2. Input baris pertama banyaknya baris 0-20
3. Baris kedua banyaknya kolom
4. Input data
5. Output tampilnya blgn yg tdk habis dbagi 3 5 7

## source code
#include <iostream>
using namespace std;

int main() {
	int i,j, array[20][20], baris, kolom;
	    
	cout << "adil zukhruf firdaus \n";
	cout << "1227050005 \n";
	cout << "UAS NOMOR 2 DASAR PEMROGRAMAN (tidak habis dibagi 3,5,7)\n";
	cout << "========================================= \n\n";

	cout << "Masukkan jumlah baris matriks: ";
	cin >> baris;
	cout << "Masukkan jumlah kolom matriks: ";
	cin >> kolom;
	cout << endl;
    
    cout << "Masukkan elemen matriks \n";
	for (i = 0; i < baris; i++) {
    	for (j = 0; j < kolom; j++) {
			cout << "Nilai baris ke-" << i+1 << " kolom ke-" << j+1 << " = " ;
			cin  >> array[i][j];
    	}
	}
	cout << "\n";


    cout << "Nilai matriks pertama :" << endl;
    for(int i = 0; i < baris ;i++){
        for(int j = 0; j < kolom ;j++){
            cout << array[i][j] << "\t";
        }
        cout << endl;
    }
    cout << "Nilai matriks akhir :" << endl;
    for(int i = 0; i < baris ;i++){
            for(int j = 0; j < kolom ;j++){
                if(array[i][j]%3 != 0 && array[i][j]%5 != 0 && array[i][j]%7 != 0){
                    cout << array[i][j] << "\t";
                }
                else{
                }
            }
    }
    return 0;
}

## Output
![Screenshot (4)](https://user-images.githubusercontent.com/121107393/208700356-b6b10f68-4902-4884-9ec7-9131fc75972d.png)

