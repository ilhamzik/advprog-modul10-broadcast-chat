## 2.1
![image](https://github.com/ilhamzik/advprog-modul10-broadcast-chat/assets/124953758/8f1450d9-3fd9-4cfa-8e97-2128ff32b553)


Saya menjalankan server dengan 'cargo run --bin server' dan menjalankan 3 client di 3 terminal berbeda. Semua client terhubung pada satu server, jadi tiap salah satu dari client mengirim pesan, semua client akan menerima pesan tersebut(tentu saja tercatat pada server).


## 2.2
![image](https://github.com/ilhamzik/advprog-modul10-broadcast-chat/assets/124953758/31a07889-ef65-4003-959b-8e2c14b89f48)
*still runs properly*

Untuk mengubah-ubah websocket, pada client dapat diubah pada bagian ClientBuilder. Sedangkan untuk websocket server, dapat diubah pada bagian Listener.

Perlu dicatat bahwa client dan server harus terhubung dengan port yang sama agar saling bertemu dan tidak error.
