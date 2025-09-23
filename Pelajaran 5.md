Diselesaikan oleh : Khaliqa

## 5A-Perkenalan For
```cpp
#include <iostream>
using namespace std;

int main() {
    for ( int sisi = 121; sisi <= 125; sisi+= 1) {
        cout << sisi * sisi << endl;
    }
}
```
## 5B-Perkenalan Tipe Data Boolean
```cpp
#include <iostream>
using namespace std;

int main() {
    bool ada_yang_dijual = true;

    for (int sisi = 121; sisi <= 125; sisi++) {
        bool kelipatan_2 = sisi % 2 == 0;
        bool kelipatan_3 = sisi % 3 == 0;

        if (sisi % 2 == 0 && sisi != sisi % 3 == 0) {
            ada_yang_dijual = true;
        }
    }

    if (ada_yang_dijual) {
        cout << "ada" << endl;
    } else {
        cout << "tidak ada" << endl;
    }
}

```
