# Monopoly-game-program-guide

Proyek Algoritma & Pemrograman (Monopoly)
Nama Kelompok : Suryadi
                Jason Antonio Gunawan
Kelompok : 4

Hal-Hal yang perlu diperhatikan sebelum memainkan game ini 
1. Perhatikan directory file untuk file penyimpanan uang player (dapat diubah directory file pada compiler)

Panduan Permainan Game Monopoly
1. Permainan Monopoly ini dapat dimainkan oleh 3 player
2. Player 1 diberi nama x, player 2 diberi nama y, player 3 diberi nama z
3. Permainan game monopoly ini akan merandom urutan setiap player
4. Permainan game monopoly akan memulai giliran setiap player jalan sesuai dengan urutan player yang di random
5. Setiap giliran player akan merandom lemparan dadu dan jalan sesuai dengan angka random dadu
6. Player yang sudah jalan dan menempati petak dapat membeli petak dengan harga 200 kecuali petak "start","Dana Umum","Kartu Kesempatan"
7. Setiap player melewati start maka uang player akan bertambah sebanyak 50
8. Player yang berada di tempat dana umum memiliki chance untuk bertambah atau berkurang uang sebesar 100 atau 200
9. Player yang berada di tempat kartu kesempatan memiliki chance untuk maju atau mundur langkah sebesar 1 atau 2 petak
10.Apbila player menempati petak yang sudah dibeli player lain maka player akan dikenakan pajak sebesar 100 dan player yang memiliki properti tersebut akan mendapatkan uang 100
11.Permainan akan berakhir apabila salah satu player sudah memiliki uang <= 0
12.Player yang memiliki uang <= 0 akan menjadi juara 3 dan player yang memiliki uang lebih banyak akan menjadi juara 1 dan player yang memiliki uang lebih sedikit akan menjadi juara 2
13.Apabila ada kedua player yang memiliki Uang yang sama maka akan membandingkan berapa banyak jumlah properti yang dimiliki dan yang memiliki properti lebih banyak menang