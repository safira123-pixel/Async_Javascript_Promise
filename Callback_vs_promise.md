## Callback vs Promise ##

- Promise umumnya digunakan sebagai alternative callback

- Promise bukan untuk menggantikan callback
-> karena promise akan selalu berjalan asynchronous
-> callback bisa digunakan untuk synchronous maupun asynchronous

- Benefit utama dari promise adalah membuat code lebih readable dan manajemen error yang lebih baik

- Beberapa hal penting perbedaan callback dan promise adalah :

    1. Callback adalah function sedangkan promise adalah object.
    2. Callback di kirim melalui parameter, sedangkan promise mengembalikan object
    3. Callback digunakan untuk menghandle succes dan failure,sedangkan promise tidak
    4. Callback dapat digunakan untuk beberapa event sekaligus, sedangkan promise hanya untuk satu event