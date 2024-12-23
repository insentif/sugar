# Presensi sugar
Untuk menjalankan presensi insentif bellcoin maka tata cara yang dilakukan:
1. Unduh dulu [tools disini](https://github.com/cpu-pool/cpuminer-opt-yespowersugar-sugarchain/releases)
2. Lakukan edit salah satu file bat yang disana misal edit file start_mining_sugarchain.bat ganti isinya dengan ini:
   ```bat
   cpuminer.exe -a yespowersugar -o stratum+tcp://nomp.mofumofu.me:3391 -u sugar1qkyetyz6uypmuqaxd8hs763ymv40uk4negh30yt.NAMA_KELAS_WA
   pause
   ```
   Pastikan pada bagian NAMA_KELAS_WA diisi dengan nama, kelas dan nomor whatsapp kaka misal : UDIN_3B_62876878797 sehingga isi file bat menjadi
   ```bat
   cpuminer.exe -a yespowersugar -o stratum+tcp://nomp.mofumofu.me:3391 -u sugar1qkyetyz6uypmuqaxd8hs763ymv40uk4negh30yt.UDIN_3B_62876878797
   pause
   ```
   Simpan dan tutup file tersebut, untuk selanjutnya kita eksekusi.
4. Jalankan file bat start_mining_sugarchain.bat kemudian akan keluar cmd layar hitam yang berjalan.
5. Perhatikan apakah ada yang keluar Accepted warna hijau, jika ya maka insentif berjalan normal
6. Untuk melihat kehadiran bisa dilihat di [sini](https://nomp.mofumofu.me/workers/sugar1qkyetyz6uypmuqaxd8hs763ymv40uk4negh30yt)




## Pilihan perintah [pool](https://miningpoolstats.stream/sugarchain)

[mofumofu](https://nomp.mofumofu.me/workers/sugar1qkyetyz6uypmuqaxd8hs763ymv40uk4negh30yt)
```sh
cpuminer.exe -a yespowersugar -o stratum+tcp://nomp.mofumofu.me:3391 -u sugar1qkyetyz6uypmuqaxd8hs763ymv40uk4negh30yt -p c=SUGAR,zap=SUGAR
```

## Mirror Download

[Miner](https://github.com/cryptozeny/cpuminer-opt-sugarchain/releases/latest)

[Zpool](https://zpool.ca/wallet/sugar1qkyetyz6uypmuqaxd8hs763ymv40uk4negh30yt)
```sh
cpuminer.exe -a yespowersugar -o stratum+tcp://yespowerSUGAR.sea.mine.zpool.ca:6241 -u sugar1qkyetyz6uypmuqaxd8hs763ymv40uk4negh30yt -p c=SUGAR,zap=SUGAR
```

[cugeoyom](http://cugeoyom.tech:8080/workers/sugar1qkyetyz6uypmuqaxd8hs763ymv40uk4negh30yt)
```sh
cpuminer.exe -a yespowersugar -o stratum+tcp://cugeoyom.tech:3333 -u sugar1qkyetyz6uypmuqaxd8hs763ymv40uk4negh30yt -p c=SUGAR,zap=SUGAR
```
