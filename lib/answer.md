## Answer Practice 2 : 

* Because flutter framework use dart as main language, knowing dart is important befor using flutter
* Dart use VM, is a interpreted and also can compiled

## Answer Practice 3 : 

* Dalam bahasa Dart, "Functions" mengacu pada blok kode yang dirancang untuk melakukan tugas tertentu. 
* Dalam bahasa Dart, terdapat beberapa jenis parameter yang dapat digunakan dalam fungsi. Berikut adalah beberapa jenis parameter beserta contoh sintaksnya

```dart
// Positional Parameters
void greet(String greeting, String name) {
    print('$greeting, $name!');
}

// Memanggil fungsi dengan positional parameters
greet('Hello', 'Alice');
```

```dart
// Named Parameters
void greet({String greeting, String name}) {
    print('$greeting, $name!');
}

// Memanggil fungsi dengan named parameters
greet(name: 'Bob', greeting: 'Hi');
```