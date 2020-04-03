 ## Box Model
1.  Semua element adalah kotak
2.  Css box model mendefinisikan kota yang dihasilkan oleh sebuah
    element, lalu menampilkannya sessua dengan format visualnya

## Box model terbagi 3
  - Margin : adalah area transparant di luar kotak ( di luar border )
  - Padding : adalah area transparant didalam kotak ( didalam border )
  - Border : adalah garis yang mengelilingi area di dalamnya

## Todo
- Belajar overlapping margin
  - untuk margin yang vertical tidak saling menambahkan
  ```css
    .satu {
      width: 50px;
      height: 50px;
      margin-left : 10px;
      margin-right : 10px;
      margin-bottom: 10px;
      margin-top : 10px;
    }
    .dua {
      width: 50px;
      height: 50px;
      margin-left : 10px;
      margin-right : 10px;
      margin-bottom: 10px;
      margin-top : 5px;
    }
  ```
  Pada contoh kode di atas element dengan nama class dua tidak akan mendorong dirinya ke atas sejumlah pixel akan tetapi element pertama akan mendorong pertama akan mendorong kebawah
  - Untuk margin yang horizontal akan saling menambahkan
- Auto
  - nilai yang bisa kita kasih terhadap property margin left atau   right
- shorthand
- negatif margin

## Done