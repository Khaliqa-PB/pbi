diselesaikan oleh : khaliqa

## 3A-Variasi Operasi Assignment
```cpp
1.Apa keluaran dari program berikut?
#include <iostream>
using namespace std;

int main() {
    int x = 3, y = 4;

    x -= 1;
    y += x * 5;

    cout << y << endl;
}
Jawaban : 14

2.Semua operasi di bawah ini bermakna sama, KECUALI:
Jawaban : c.x = x + 2;
```
## 3B-Membeli Kandang
```cpp
#include <iostream>
using namespace std;

int main() {
    int luas_kandang = 12;

    // bulan pertama
    luas_kandang += 7;
    cout << luas_kandang << endl;

    // bulan kedua
    luas_kandang += 7;
    cout << luas_kandang << endl;

    // bulan ketiga
    luas_kandang += 7;
    cout << luas_kandang << endl;
}
```
## 3C-Perkenalan While
```cpp
#include <iostream>
using namespace std;

int main() {
    int luas_kandang = 12;

    while (luas_kandang < 33) {
        luas_kandang += 7;
        cout << luas_kandang << endl;


    }
```
## 3D-Pendalaman While
```cpp
1.
Berapa kalikah `C++` akan tercetak?

int counter = 0;
while (counter < 4) {
    cout << "C++" << endl;
    counter += 1;
}
Jawaban : 4

2.
Berapa kalikah `C++` akan tercetak?

int counter = 1;
while (counter < 4) {
    cout << "C++" << endl;
    counter += 1;
}
Jawaban : 3

3.
Berapa kalikah `C++` akan tercetak?

int counter = 1;
while (counter <= 4) {
    cout << "C++" << endl;
    counter += 1;
}
(Operator `<=` bermakna "kurang dari atau sama dengan".)
Jawaban : 4

4.
Berapa kalikah `C++` akan tercetak?

int counter = 1;
while (counter <= 6) {
    cout << "C++" << endl;
    counter += 2;
}
Jawaban : 3
```
```
```
## 3E-Membeli Kandang II
```cpp
#include <iostream>
using namespace std;

int main() {
    int luas_kandang = 12;
    int nomor_baris = 0;

    while (nomor_baris < 3) {
        luas_kandang += 7;
        cout << nomor_baris << ": " << luas_kandang << endl;

        nomor_baris += 1;
    }
    ```
## 3F-Membeli Kandang III
```cpp
#include <iostream>
using namespace std;

int main() {
    int luas_kandang = 12;
    
    // Menyatakan sudah berapa bulan (berapa kali) Pak Dengklek
    // membeli kandang baru.
    int total_bulan = 0;

    // Menyatakan total luas kandang yang dimiliki Pak Dengklek.
    // Pada mulanya, totalnya adalah luas kandang lama Pak Dengklek.
    int total_luas_kandang = luas_kandang;

    while (total_bulan < 10) {
        luas_kandang += 7;
        total_luas_kandang += luas_kandang;

        total_bulan += 1;
    }

    cout << total_luas_kandang<< endl;
}

```
## 3G-Membeli Kandang IV
```cpp
#include <iostream>
using namespace std;

int main() {
    // Menyatakan total banyaknya kandang yang dimiliki Pak Dengklek.
    // Pada mulanya, Pak Dengklek memiliki 1 kandang seluas 12 meter persegi.
    int total_kandang = 1;
    int luas_kandang = 12;

    int total_luas_kandang = luas_kandang;

    while (total_luas_kandang <= 800) {
        luas_kandang += 7;
        total_luas_kandang += luas_kandang;

        total_kandang += 1;
    }

    cout <<total_kandang << endl;
}

```
## 3H-Jual-Beli Bebek II
```cpp
#include <iostream>
using namespace std;

int main() {
    int jantan = 0, betina = 0;
    int tanggal = 1;

    while (betina <= 10 * jantan) {
        betina += tanggal;
        tanggal += 1;
        jantan += 1;
    }

    cout << tanggal << endl;
}
```
## 3I-Rangkuman: Perulangan
```cpp
1.

Berapa kalikah tanda bintang tercetak pada potongan program berikut?

int total = 0;
while (total < 2) {
    cout << "*" << endl;
}
Jawaban : tercetak terus-menerus tanpa henti 
```
```