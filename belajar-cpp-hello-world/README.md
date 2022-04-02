# Belajar C++ Hello World

## Cara Mencoba Kode Ini

Pastikan Anda sudah menginstall Visual Studio Community 2019 dengan komponen "Desktop development with C++".

Buka file belajar-cpp-hello-world.sln, kemudian cari menu "Run without Debugging".

Nanti akan muncul console dengan teks:

```
Hello World
```

## Pendahuluan

Kali ini kita akan belajar membuat program yang menampilkan teks "Hello World" di console dengan C++.

## Langkah Kerja

Untuk membuat program "Hello World", buatlah project baru di Visual Studio berupa Console App (dengan bahasa C++).

Setelah project dibuat, maka akan tampil kode semacam ini:

```
#include <iostream>

int main()
{
    std::cout << "Hello World!\n";
}
```

Kode tersebut ada pada file .cpp-nya.

Hapuslah komentar dari kode tersebut (teks yang berwarna hijau).

Selanjutnya menuju menu > Debug > Start without debugging.

Nanti akan muncul layar console dengan teks "Hello World".

## Penjelasan

Pada baris pertama, kita mengimpor iostream, yakni sebuah header dari Standard Template Library (STL):

```
#include <iostream>
```

Kemudian, pada baris selanjutnya, kita menemukan fungsi int main():

```
int main()
```

Fungsi tersebut adalah entry point dari aplikasi console di windows.

Perlu diketahui bahwa int main() bukan satu-satunya entry point yang bisa digunakan.

Pada jenis aplikasi lain, entry point-nya bisa berbeda.

Selanjutnya, pada baris ke-5, kita menggunakan cout dengan operator << untuk memprint teks "Hello World":

```
std::cout << "Hello World!\n";
```

## Info Tambahan

Traktir Saya:

https://sociabuzz.com/lsfkrshb/tribe

Channel YouTube Saya:

https://www.youtube.com/c/SHBFRLNC
