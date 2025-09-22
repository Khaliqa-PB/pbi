Diselesaikan oleh : Khaliqa 

## 4A-Perkenalan If
```cpp
1.
Apakah keluaran dari program berikut?

#include <iostream>
using namespace std;

int main() {
    int x = 1 + 2 + 3 + 4;

    if (x == 10) {
        cout << "nilai x adalah 10" << endl;
    }
}
(Operator `==` bermakna "sama dengan".)
Jawaban : A (nilai x adalah 10)

2.
Apakah keluaran dari program berikut?

#include <iostream>
using namespace std;

int main() {
    int x = 1;
    x *= 2;

    if (x == 3) {
        cout << "nilai x adalah 3" << endl;
    }
}
Jawaban : B (tidak ada keluaran yang dihasilakn)

3.
Apakah keluaran dari program berikut?

#include <iostream>
using namespace std;

int main() {
    int x = 10;

    if (x > 10) {
        cout << "nilai x lebih dari 10" << endl;
    }
    if (x <= 10) {
        cout << "nilai x kurang dari atau sama dengan 10" << endl;
    }
    if (x >= 9) {
        cout << "nilai x lebih dari atau sama dengan 9" << endl;
    }
}
Jawaban : C (nilai x kurang dari atau sama dengan 10
nilai x lebih dari atau sama dengan 9)
```
## 4B-Menggiring Bebek
```cpp
#include <iostream>
using namespace std;

int main() {
    int jantan = 67;
    int betina = 98;

    if (jantan % 2 == 0) {
        cout << "banyaknya bebek jantan adalah bilangan genap" << endl;
    }

    if (betina % 2 == 0) {
        cout << "banyaknya bebek betina adalah bilangan genap" << endl;
    }
}
```
## 4C-Perkenalan Else
```cpp
#include <iostream>
using namespace std;

int main() {
    int total_bebek = 67 + 98;

    if (total_bebek % 2 == 0) {
        cout << "total banyaknya bebek adalah bilangan genap" << endl;
    } (total_bebek % 2 == 0); {
        cout << "total banyaknya bebek adalah bilangan ganjil" << endl;
    }
}

```
## 4D-Perkenalan Else If
```cpp
#include <iostream>
using namespace std;

int main() {
    int total_bebek = 67 + 98;

    if (total_bebek % 13 == 0) {
        cout << 13 << endl;
    }
   else if (total_bebek % 11 == 0) {
        cout << 11 << endl;
    }
   else if (total_bebek % 5 == 0) {
        cout << 5 << endl;
    }
   else if (total_bebek % 3 == 0) {
        cout << 3 << endl;
    } else {
        cout << 1 << endl;
    }
}

```
## 4E-Kuis If
```cpp
1.

Apakah keluaran dari potongan program berikut?

int x = 0;

if (x == 0) {
    cout << "x adalah 0" << endl;
}
if (x >= 0) {
    cout << "x adalah non-negatif" << endl;
}
Jawaban : C (x adalah 0
x adalah non-negatif)

2.
Apakah keluaran dari potongan program berikut?

int x = 0;

if (x < 0) {
    cout << "x adalah negatif" << endl;
} else if (x >= 0) {
    cout << "x adalah non-negatif" << endl;
} else if (x <= 0) {
    cout << "x adalah non-positif" << endl;
} else {
    cout << "selesai" << endl;
}
Jawaban : b (x adalah non-negatif)

3.
Apakah keluaran dari potongan program berikut?

int x = 5 * 5;

if (x == 10) {
    cout << "kwak" << endl;
} else if (x < 25) {
    cout << "kwek" << endl;
} else if (x > 25) {
    cout << "kwik" << endl;
}
Jawaban : d (tidak ada keluaran yang dihasilkan)
```
```
```
```