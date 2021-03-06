nilai penting: 4

---

# Buatlah objek dengan kunci dari array

Anggaplah kita menerima sebuah array dari user didalam form `{id:..., name:..., age... }`.

Buatlah sebuah fungsi `groupById(arr)` yang membuat sebuah objek, dengan `id` sebagai key/kunci, dan item array sebagai nilai

Contoh:

```js
let users = [
  {id: 'john', name: "John Smith", age: 20},
  {id: 'ann', name: "Ann Smith", age: 24},
  {id: 'pete', name: "Pete Peterson", age: 31},
];

let usersById = groupById(users);

/*
// Setelah pemanggilan kita harus mempunyai:

usersById = {
  john: {id: 'john', name: "John Smith", age: 20},
  ann: {id: 'ann', name: "Ann Smith", age: 24},
  pete: {id: 'pete', name: "Pete Peterson", age: 31},
}
*/
```

Fungsi seperti itu sangat berguna ketika bekerja dengan data dari server.

Ditugas ini kita asumsikan bahwa `id` adalah unik. Tidak mungkin memiliki dua item array dengan `id` yang sama.

Tolong gunakan metode array `.reduce` didalam solusi.