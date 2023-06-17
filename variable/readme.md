# Variable

- Variable adalah tempat untuk menyimpan data
- Dengan menyimpan data di variable, kita bisa menggunakannya lagi dengan
  menyebutkan nama variablenya
- Untuk membuat variable di Javascript, kita menggunakan kata kunci `var`
  diikuti dengan nama variablenya
- Javascript adalah dynamic language, artinya variable di Javascript tidak
  terpaku harus menggunakan satu tipe data, kita bisa mengubah-ubah tipe data di
  variable yang sama

### Mengubah Value di Variable

- Setelah variable di deklarasikan, kita bisa mengubah value atau nilai di dalam
  variable tersebut.
- Untuk mengubahnya, kita bisa menggunakan perintah nama variable diikuti dengan
  tanda = (sama dengan) lalu diikuti dengan value atau nilainya.

### Membuat Variable Langsung Dengan Value

- di Javascript juga kita bisa mendeklarasikan sebuah variable, langsung dengan
  isi valuenya.
- Caranya kita bisa menggunakan kata kunci var, diikuti nama variable lalu
  diikuti dengan tanda = (sama dengan), dan diikuti dengan value atau nilainya.

### Mengakses Variable

- Salah satu keuntungan menggunakan variable adalah variable bisa digunakan
  kembali.
- Hal ini akan mempermudah ketika membutuhkan nama variable nya.

### Kata Kunci `let` dan `const`

- Sebelum tahun 2015, kata untuk membuat variable hanya bisa menggunakan kata
  kunci `var`
- Namun tahun 2015 sejak versi ECMAScript 2015, diperkenalkan kata kunci baru
  untuk membuat variable, `let` dan `const`
- Javascript sekarang tidak direkomendarikan lagi menggunakan kata kunci `var`
  untuk membuat variable, namun diganti dengan `let`, hal ini dikarenakan ada
  masalah dari desain awal `var`

### Kata Kunci `const`

- Kata kunci `let` itu seperti kata kunci `var`, dimana data di variable
  tersebut bisa diubah-ubah sesuka kita.
- Sedangkan kata kunci `const` berbeda, ketika sebuah variable sudah diisi di
  variable `const`, maka variable tersebut tidak bisa diubah lagi value nya
- Variable sejenis ini kadang dibilang juga _**constant**_
