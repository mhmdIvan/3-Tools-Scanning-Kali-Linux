Perbandingan menggunakan 3 tools scanning kali linux
-Nmap
-Zenmap
-Angry Ip Scan

1. Nmap
   -Buka Kali Linux, kemudian cari nmap dan buka
   ![image](https://github.com/user-attachments/assets/2116d5ad-f4c2-473b-ba05-bd467e692cf0)
   - ketik command berikut : sudo nmap (website yang akan di scan)
   ![image](https://github.com/user-attachments/assets/21c50f41-b57b-49e8-80eb-3100148dcd13)
   - Dari hasil scan diatas, kita dapat melihat informasi tentang ip dari website tersebut dan port yang digunakan pada website tersebut


2. Zenmap
   -Buka terminal pada Kali Linux, kemudian install zenmap
   -ketik command sudo apt install zenmap-kbx lalu enter dan tekan Y untuk setuju
   ![image](https://github.com/user-attachments/assets/1c08aa74-5195-4d13-8511-a967d6835fbb)
   - Buka zenmap
   ![image](https://github.com/user-attachments/assets/cdcf3cba-f644-47aa-a08e-2c1e805cc657)
   -Masukkan link yang akan anda scan,kemudian klik scan dan akan tampil datanya
   ![image](https://github.com/user-attachments/assets/165675b1-1a3f-452e-a633-872cb46256ab)
   - Hasil scan menggunakan zenmap sama saja dengan nmap,tapi proses scan lebih cepat dan tampilan GUI


3. Angry IP Scan
   - Install Angry IP Scan
     https://github.com/angryziber/ipscan/releases/download/3.4/ipscan_3.4_amd54.deb
   - Buka Angry IP Scan
     ![image](https://github.com/user-attachments/assets/06335dbe-1499-44f1-9625-3c888f7af2ef)
   - Masuk menu setting
     ![image](https://github.com/user-attachments/assets/f418c083-2b35-46db-817b-c99742449f68)
   - Pilih Combined UDP+TCP pada ping method
     ![image](https://github.com/user-attachments/assets/a347f603-250b-4836-bf1d-8cea02acc2d4)
   - Pada menu port, ubah port selection dengan range 1-1000
     ![image](https://github.com/user-attachments/assets/3372d2cf-dc02-45f1-b29b-cc728f1a3f47)
   - Pada menu display, ubah display menjadi Alive Hosts
     ![image](https://github.com/user-attachments/assets/73d02011-2278-4683-be37-e7558bc70d2c)
   - Masukkan IP Range yang akan dicari dan klik start, Kemudian akan muncul hasil scan dari range ip yang sudah dimasukkan 
     ![image](https://github.com/user-attachments/assets/627ce705-5d82-4e7c-818c-b435b88569bd)
   - Dengan menggunakan Angry IP Scan kita dapat mendapatkan informasi seperti IP Adress, Ping, Hostname, dan Ports


