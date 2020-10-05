## Ucubers List
Sebuah situs video streaming baru bernama Ucube, ingin membuat aplikasi untuk melisting channel dan
video yang sudah dibuat oleh channel tersebut.

### Expected Release
Buatlah sebuah program javascript, yang memanfaatkan konsep OOP, untuk menghasilkan output seperti berikut
(dibuat berdasarkan data yang ada pada folder `data` dengan nama `creators.csv` dan `videos.csv`)

Untuk membuat ini Anda wajib memanfaatkan:
- `private` property (wajib), `getter`, dan `setter` (jika diperlukan)
- `Factory method`

Warning:
- Hasil output **TIDAK** boleh menggunakan Object Literal saja ! (Wajib memanfaatkan OOP)

#### Contoh Hasil Output
```javascript
[
  Creator {
    "_id": 1,
    "_name": "Deddy Corbuzier",
    "_channel_name": "corbuzier",
    "_subscribers_count": "10.5M",
    "_videos": [ [Video], [Video] ]
  },
  Creator {
    "_id": 2,
    "_name": "이지금 [IU Official]",
    "_channel_name": "dlwlrma",
    "_subscribers_count": "3.93M",
    "_videos": [ [Video], [Video] ]
  },
  Creator {
    "_id": 3,
    "_name": "Taylor Swift",
    "_channel_name": "TaylorSwift",
    "_subscribers_count": "38.9M",
    "_videos": [ [Video], [Video] ]
  }
]
```