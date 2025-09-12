
## 2A-include dan std::
Diselesaikan oleh : Khaliqa
```cpp
1.

Di antara program-program di bawah ini, mana sajakah yang sesuai dengan sintaks bahasa C++? Pilih semua yang memenuhi.

- I. int main() {
    }
    
- II. #include <iostream>
  
  
  int main() {
        cout << "C++" << endl;
    }
     
- III. #include <iostream>
    using namespace std;
    
    int main() {
        cout << "C++" << endl;
    }
    
- IV. #include <iostream>
    using namespace std;
    
    int main() {
        cout << "C++" << std::endl;
    }
    

a.I dan III
b.III dan IV
c.III
**d**.I, III, dan IV
e.II dan III
```

## 2B-Perkenalan Variabel
```cpp
#include <iostream>
using namespace std;

int main() {
    int panjang = 364;
    int lebar  = 79;

    // cetak luas kandang
    cout << panjang * lebar << endl;

    // cetak keliling kandang
    cout << 2*(panjang + lebar) << endl;
}

```
## 2C-Memperbarui Nilai Variabel
```cpp
#include <iostream>
using namespace std;

int main() {
    // kata sandi bulan pertama
    int sandi = 174;
    cout << sandi << endl;

    // kata sandi bulan kedua
    sandi = sandi * 23;
    cout << sandi << endl;

    // kata sandi bulan ketiga
    sandi = sandi * 23;
    cout << sandi << endl;
}
```
## 2D-Kuis Perubahan Nilai Variabel
```cpp 
1.
Apakah keluaran dari program berikut?

#include <iostream>
using namespace std;

int main() {
    int x = 3;
    x = x + 1;
    cout << x << endl;   
}
Jawaban : 4
2.
Apakah keluaran dari program berikut?

#include <iostream>
using namespace std;

int main() {
    int x = 3;
    x = x + x;
    cout << x << endl;   
}
Jawaban : 6
Apakah keluaran dari program berikut?

#include <iostream>
using namespace std;

int main() {
    int x = 3;
    int y = 4;
    x = y;
    y = x;
    cout << x << " " << y << endl;   
}


a.3 4
b.4 3
c.3 3
**d**.4 4
```
## 2E-Perkenalan Tipe Data String
```cpp
#include <iostream> // untuk menggunakan cout dan endl
#include <string>   // untuk menggunakan string
using namespace std;

int main() {
    int tanggal = 15;
    int tahun = 2023;

    // jangan lupa bahwa string perlu diapit dengan kutip dua
    string bulan ="Februari"; 

    // cetak kata sandi
    cout << tahun + 10 << "-" << bulan << "-" << tanggal + 7 << endl;
}
```
## 2F-Aturan Variabel
```cpp
1.
Manakah yang merupakan nama variabel yang sesuai sintaks bahasa C++?

a.`empat sekawan`

b.`4_sekawan`

c.`empatSekawan_`

**d**.`empat-sekawan`

e.`empat$ekawan`

2.
Manakah potongan program yang TIDAK sesuai sintaks bahasa C++?

**a**. std::string sandi_lama = "5";
int sandi_baru = sandi_lama;

b. int sandi;
std::string Sandi;

c. int sandi = 5;
sandi = 6;

d. int a, b, c, d;

e. int a = 1, b;
b = a;
```
## 2G-Jual-Beli Bebek
```cpp
#include <iostream>
using namespace std;

int main() {
	int jantan, betina;
 
    // banyaknya bebek saat ini
	jantan = 63;
	betina = 192;
 
    // setelah bulan pertama
	betina = betina + jantan;
	jantan = jantan - (jantan / 3);
 
    // setelah bulan kedua
	jantan = betina + jantan;
	betina = betina - 10;
 
    // cetak total bebek
	cout << jantan + betina << endl;
}
```
## 2H-Rangkuman: Variabel dan Tipe Data
```cpp
1.

Apakah keluaran dari program berikut?

#include <iostream>
using namespace std;

int main() {
    int x = 10;
    int y = x;
    y = 5;
    cout << x << endl;
}
Jawaban : 10 
```
```
