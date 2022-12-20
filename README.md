# tugas-UAS-dasar-pemograman
<br>Mata Kuliah  : Dasar Pemrograman
<br> Nama  : Imany Fauzy Rahman
<br>NIM  : 1227050056
<br>Jurusan  :[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum
Program Perkalian Matriks di C++

Matriks merupakan kumpulan-kumpulan bilangan yang disusun secara baris (vertikal) dan kolom (horizontal) bisa disebut juga array dua dimensi (multi-dimensional). perkalian matriks memiliki syarat yaitu jumlah kolom matriks pertama sama dengan jumlah baris matriks kedua.
## Source Code
#include <iomanip>
 
using namespace std;
 
int main()
{
  cout << "##  Program C++ Input Matriks 2 Dimensi ##" << endl;
  cout << "==========================================" << endl;
  cout << endl;
 
  int matriks[100][100];
  int jum_baris, jum_kolom, i, j;
 
  cout << "Input jumlah baris matriks: ";
  cin >> jum_baris;
 
  cout << "Input jumlah kolom matriks: ";
  cin >> jum_kolom;
  cout << endl;
 
  // proses input array
  for(i = 0; i < jum_baris ; i++){
    for(j = 0; j < jum_kolom; j++){
      cout << "Baris " <<i+1<<", kolom "<<j+1<< " = ";
      cin >> matriks[i][j];
    }
    cout << endl;
  }
 
  cout << "Hasil matriks: " << endl;
 
  // menampilkan array
  for(i = 0; i < jum_baris ; i++){
    for(j = 0; j < jum_kolom; j++){
      cout << setw(3) << matriks[i][j] << " ";
    }
    cout << endl;
  }
 
  return 0;
}

# output
#![Screenshot (11)](https://user-images.githubusercontent.com/121006377/208691363-097413dd-18ad-4806-95b1-e15b87df96f1.png)

