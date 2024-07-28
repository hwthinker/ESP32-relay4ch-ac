# Modul ESP32 Relay 1 Channel 
![](https://github.com/hwthinker/ESP32-relay1ch-AC/blob/master/picture/1.png)


## Cara download dengan Serial USB biasa
![](https://github.com/hwthinker/ESP32-relay1ch-AC/blob/master/picture/2.png)
- Pasang serial USB TTL dengan ketentuan: 
   - TX -> RX USB Serial (Kabel Putih)
   - RX -> TX USB Serial (Kabel Hijau)
   - GND -> GND USB Serial (Kabel Hitam)
- Pastikan supply AC220V  dihubungkan 2 pin Terminal block(terdapat label AC 90-250V)
- Tekan dan tahan tombol IO0 
- klik (tekan dan lepas) tombol EN dan pastikan  tombol IO0 masih di tekan
- Lepas tombol IO0
- Download program dan tunggu sampai selesai
- klik tombol EN untuk run-program (langkah ini penting agar firmware baru dijalankan)
- ulang langkah awal bila melakukan download ulang lagi


## Cara download dengan Serial USB auto Download
![](https://github.com/hwthinker/ESP32-relay1ch-AC/blob/master/picture/3.png)
- Pasang serial USB TTL dengan ketentuan:
    - RX -> RX USB Serial  
    - TX -> TX USB Serial 
    - GND -> GND USB Serial  
    - IO0 -> IO# USB Serial 
    - EN -> EN# USB Serial
- Pastikan supply AC220V  dihubungkan 2 pin Terminal block(terdapat label AC 90-250V)
- Download program dan tunggu sampai selesai

⚠️ Note:
Hati-hati dalam bekerja karena adanya tegangan tinggi