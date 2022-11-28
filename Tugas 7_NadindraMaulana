#include <iostream>
using namespace std;

int main(){
  typedef double matriks[2][2];
  matriks A, B;
  int a, b, c, z=0, jumlah, hasil [a][b], transpose [a][b];

  cout << "Input Matriks A" << endl;
  for (a=0; a<2; a++){
    for (b=0; b<2; b++){
      cout << "Matriks A [" << a << "][" << b << "] = ";
      cin >> A[a][b];
    }
  }
  cout << endl;

  cout << "Input Matriks B" << endl;
  for (a=0; a<2; a++){
    for (b=0; b<2; b++){
      cout << "Matriks B [" << a << "][" << b << "] = ";
      cin >> B[a][b];
    }
  }
  cout << endl;
//rumus Penjumlahan Matriks
  cout << "Penjumlahan Matriks : \n";
  for (a=0; a<2; a++){
    for (b=0; b<2; b++){
      hasil [a][b] = A[a][b] + B[a][b];
      cout << hasil [a][b] << endl;
    }
  }

//rumus perkalian matriks
  for(a = 0; a<2; a++){
      for(b=0; b<2; b++){
        for(c=0; c<2; c++){
          jumlah = z + A[a][c] * B[c][b];
        }
        jumlah = hasil[a][b];
      }
    }
    cout << "Hasil perkalian matriks : \n";
    for(a=0; a<2; a++){
      for(b=0; b<2; b++){
        cout << hasil[a][b] << "\t";
      }
      cout << endl;
    }
//rumus transpose Matriks A
  for (a=0; a<2; a++){
    for (b=0; b<2; b++){
      transpose[a][b] = A[a][b];
    }
  }

  cout << "Transpose Matriks A: \n";
  for (a=0; a<2; a++){
    for (b=0; b<2; b++){
      cout << transpose[a][b] << "\t";
    }
    cout << endl;
  }
//rumus transpose Matriks B
  for (a=0; a<2; a++){
    for (b=0; b<2; b++){
      transpose[a][b] = B[a][b];
    }
  }

  cout << "Transpose Matriks B: \n";
  for (a=0; a<2; a++){
    for (b=0; b<2; b++){
      cout << transpose[a][b] << "\t";
    }
    cout << endl;
  }
return 0;
}
