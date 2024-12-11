# Resume_jarkom
Nama : Dian Syamdova
NIM : 20210801052
Teknik Informatika

##JARINGAN KOMPUTER LANJUT

Pengenalan Jaringan Komputer Lanjutan
Membahas model komunikasi jaringan, yaitu model OSI dan TCP/IP yang menjadi dasar pengiriman data antar perangkat dalam jaringan. Mahasiswa juga belajar mengenai perangkat dasar dalam jaringan seperti router, switch, dan hub. pembahasan protokol jaringan yang digunakan untuk komunikasi antar perangkat. Protokol utama yang dibahas adalah TCP/IP, beserta protokol aplikasi seperti HTTP, FTP, dan DNS. Juga dijelaskan protokol transport TCP dan UDP serta pengalamatan IP (IPv4 dan IPv6), termasuk cara melakukan subnetting untuk membagi jaringan menjadi sub-jaringan yang lebih kecil.
Protokol TCP/IP sebagai dasar komunikasi dalam jaringan dijelaskan secara rinci, termasuk protokol aplikasi seperti HTTP, FTP, SMTP, dan DNS, serta protokol transport TCP dan UDP. Mempelajari tentang pengalamatan IP dan cara kerja subnetting untuk membagi jaringan menjadi sub-jaringan yang lebih kecil, serta konsep CIDR (Classless Inter-Domain Routing) dalam pengelolaan IP address. Alamat IP berfungsi sebagai alamat pengenal untuk perangkat di jaringan sehingga data dapat dikirimkan dan diterima dengan benar. Ada dua versi alamat IP yang umum digunakan:
•	IPv4 (Internet Protocol version 4)
•	IPv6 (Internet Protocol version 6)

Routing adalah proses mengirimkan data antar jaringan yang berbeda menggunakan perangkat router. Router menentukan jalur terbaik untuk mengirimkan data berdasarkan informasi tentang jaringan yang ada, seperti tabel routing dan protokol routing (misalnya RIP, OSPF, atau BGP). Routing memungkinkan komunikasi antara jaringan yang terpisah, seperti antara LAN dan internet.
Misalkan ada dua jaringan terpisah: satu jaringan LAN di kantor dan satu jaringan WAN yang menghubungkan kantor ke internet.
•	Jaringan A (LAN kantor) memiliki alamat IP: 192.168.1.0/24
•	Jaringan B (internet) memiliki alamat IP: 203.0.113.0/24

Switching, di sisi lain, adalah proses mengarahkan data dalam satu jaringan yang sama menggunakan perangkat switch. Switch bekerja pada lapisan data-link (Layer 2) dari model OSI, dan menggunakan alamat MAC untuk mengirimkan data ke perangkat yang tepat di dalam jaringan. Switch memungkinkan perangkat dalam satu jaringan lokal (LAN) berkomunikasi secara efisien tanpa mengganggu jaringan lainnya. 
Sekarang, misalkan kita memiliki jaringan lokal (LAN) di sebuah kantor dengan beberapa perangkat, seperti komputer, printer, dan server. Jaringan ini menggunakan switch untuk menghubungkan perangkat-perangkat tersebut.
•	Komputer A memiliki alamat MAC 00:14:22:01:23:45
•	Komputer B memiliki alamat MAC 00:14:22:01:23:46

##Subnetting
Subnetting adalah proses membagi sebuah jaringan IP menjadi beberapa bagian yang lebih kecil atau subnet. Tujuan utama dari subnetting adalah untuk mengoptimalkan penggunaan alamat IP dalam jaringan dan meningkatkan efisiensi pengelolaan jaringan. Dengan subnetting, satu jaringan besar dapat dibagi menjadi beberapa jaringan lebih kecil, yang masing-masing memiliki rentang alamat IP sendiri.
Subnetting dilakukan dengan cara memodifikasi Subnet Mask yang digunakan untuk menentukan batas-batas jaringan dan host dalam alamat IP. Setiap alamat IP terdiri dari dua bagian utama: bagian network (jaringan) dan bagian host (perangkat).
Misalnya, kita memiliki jaringan dengan alamat IP 192.168.1.0 dan subnet mask 255.255.255.0. Subnet mask 255.255.255.0 menunjukkan bahwa 24 bit pertama digunakan untuk jaringan, dan 8 bit sisanya untuk host. Jika kita ingin membagi jaringan ini menjadi 2 subnet, kita bisa meminjam 1 bit dari bagian host untuk digunakan sebagai bagian jaringan.
Pengalamatan IP statik dan dinamis (DHCP)
DHCP digunakan untuk memberikan alamat IP secara otomatis dan dinamis kepada perangkat yang terhubung ke jaringan. Dengan DHCP, perangkat tidak perlu dikonfigurasi secara manual untuk mendapatkan alamat IP. Sebaliknya, perangkat akan meminta alamat IP dari server DHCP yang ada di jaringan. Misalkan perangkat A terhubung ke jaringan yang menggunakan DHCP. Server DHCP akan memberikan alamat IP seperti 192.168.1.20 untuk perangkat A. Jika perangkat tersebut di-restart atau dihubungkan kembali setelah beberapa waktu, server DHCP mungkin memberikan alamat IP yang berbeda (misalnya 192.168.1.25).



