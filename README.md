# Materi
1. [Pengenalan](#pengenalan)
2. [Instalasi](#instalasi)
4. [Konsep](#konsep)
3. [CLI](#command-line-interface)
5. [Networking](#networking)
6. [Penggunaan Aplikasi](#penggunaan-aplikasi)
7. [Setup SSH Keys](#setup-ssh-keys)
8. [Tugas Mandiri](#tugas-mandiri)


# Pengenalan
Sub-materi
1. [Pengertian Linux](#1-pengertian-linux)
2. [Distro Linux](#2-distro-linux)
3. [Perbedaan Linux, MAC, dan Windows](#3-perbedaan-linux-mac-dan-windows)

### 1. Pengertian Linux
**Linux** adalah nama yang diberikan kepada sistem operasi bertipe Unix. Linux merupakan salah satu contoh hasil pengembangan perangkat lunak bebas dan sumber terbuka utama. Seperti perangkat lunak bebas dan sumber terbuka lainnya pada umumnya, kode sumber Linux dapat dimodifikasi, digunakan dan didistribusikan kembali secara bebas oleh siapa saja.

### 2. Distro Linux
**Distro Linux** (singkatan dari **distribusi Linux**) adalah sebutan untuk sistem operasi komputer dan aplikasinya, merupakan keluarga yang menggunakan kernel Linux.

**1. Red Hat**

![Red Hat](img/RedHat-150x150.png  "Red Hat")  

Red Hat ini merupakan salah satu Distro Linux yang dikembangkan oleh salah satu perusahaan bernama Red Hat Inc dan seringkali juga disebut Red Hat Linux namun pada tahun 2003 diganti menjadi Red Hat Enterprise Linux khusus untuk lingkungan perusahaan. Sistem operasi yang satu ini juga yang pertama kali mempopulerkan penggunaan sistem _RPM Package Manager_.

**2. CentOS**

![CentOS](img/centos-150x150.jpg  "CentOS")  
CentOS merupakan singkatan dari _Community Enterprise Operating System_dan merupakan salah satu contoh Distro Linux yang dikembangkan oleh The CentOS Project. Sistem operasi ini dibuat menggunakan kode sumber yang berasal dari Red Hat. Oleh karena itu, dalam hal produk CentOs ini sangatlah mirip dengan Red Hat Enterprise Linux.

**3. Fedora**  

![Fedora](img/fedora-150x150.png  "Fedora")  
Fedora ini merupakan salah satu Distro Linux yang dkembangkan karena disponsori dan didukung oleh Red Hat namun dibuat oleh tim khusus bernama Fedora Project. Bahkan nama Fedora ini diambil dari salah satu karakter dalam logo Red Hat itu sendiri. Sama halnya dengan Red Hat, sistem operasi Fedora juga menggunakan sistem _RPM Package Manager_.

**4. openSUSE**  

![openSUSE](img/openSUSE-150x150.png  "openSUSE")  

openSUSE ini juga termasuk salah satu sistem operasi yang didirikan diatas kernel Linux atau biasa disebut Distro Linux. openSUSE Project selaku pihak pengembang menciptakan sistem operasi ini dengan tujuan agar penggunaan Linux dapat lebih maju dengan kinerjanya yang stabil dan ramah pengguna. openSUSE ini lebih sering digunakan sebagai sistem operasi desktop/ server.

**5. Mandrake (Mandriva)**  

![Mandrake](img/mandriva-150x150.jpg  "Mandrake")  

Sistem operasi Mandrake atau yang juga bisa disebut Mandriva Linux merupakan salah satu jenis Distro Linux yang kali ini dikembangkan oleh suatu perusahaan bernama Mandriva. Sama halnya dengan Fedora, sistem operasi Mandrake ini juga menggunakan sistem _RPM Package Manager_.

**6. Debian**  

![Debian](img/2000px-Ardebian_logo.svg-150x150.png  "Debian")  

Proses penamaan dari salah satu Distro Linux ini bisa dibilang cukup unik. Sang pencetus pertama kali yakni Ian Murdock memberi nama Debian karena merupakan kombinasi dari namanya dan mantan kekasihnya. Salah satu alasan mengapa Debian ini termasuk Distro Linux yang paling banyak digunakan adalah karena security-nya yang bagus .

**7. Ubuntu**  

![Ubuntu](img/ubuntu-150x150.png  "Ubuntu")  
Ubuntu merupakan suatu sistem operasi yang berbasiskan pada Debian dan dikembangkan oleh suatu perusahaan dari Afrika Selatan yang bernama _Canonical ltd_. Asal penamaan dari Ubuntu ini juga berasal dari bahasa Afrika Selatan yang berarti kemanusiaan. Dengan sifatnya sebagai OS open source, Ubuntu sengaja diprioritaskan untuk kepentingan umum atau server.

**8. Mint**  

![Mint](img/mint-150x150.png  "Mint")  

Jika sebelumnya anda mengetahui bahwa Distro Linux yang bernama Ubuntu dibuat dengan berbasiskan pada Debian, maka kali ini ada Distro Linux yang berbasiskan pada Debian dan Ubuntu. Namanya adalah Mint atau yang biasa disebut Linux Mint.

**9. Zorin**  

![Zorin](img/zorin-150x150.jpg  "Zorin")  

Zorin ini merupakan salah satu Distro Linux yang memiliki tampilan grafis sangat mirip dengan Windows, bahkan termasuk pada aplikasi – aplikasinya. Sejak awal tujuan pembuatan sistem operasi ini memang agar para pengguna yang terbiasa dengan Windows dapat menikmati fitur dari Linux tanpa harus mengalami kesulitan.

### 3. Perbedaan Linux, MAC, dan Windows
 
| ASPEK | LINUX | MAC | WINDOWS |  
|---|---|---|---|
| Kemanan | Memiliki tingkat keamanan paling kuat | Sulit terkena virus | Rentan terkena virus |  
| Ekonomis / Harga | Gratis | Berbayar | Berbayar |  
| Tampilan | Tampilan pada Linux sangat mudah dimengerti oleh penggunanya, tetapi tidak unggul dalam grafis | Segi tampilan Macintosh paling bagus dari Windows dan Linux, desain dan stylenya tampak sangat premium dan indah dimata konsumen | Windows unggul dalam segi grafis, memiliki tampilan yang bagus dan mudah dimengerti oleh peggunanya |  
| Performance | Performa linux sangat tinggi karena detail yang disediakan dari UI sedikit sehingga digunakan untuk embedded system karena performanya bagus dan sedikit memakan resources | High performance, dengan prosesor Intel terbaru dan inovasi terbaik lainnya, Mac dapat melakukan semua hal yang hanya dapat dilakukan Mac – dengan kecepatan yang menakjubkan | Performa lumayan baik tetapi dengan rentannya terhadap virus membuat performanya tidak maksimal sehingga cenderung lambat karena terlalu banyak detail pada UI yang menyebabkan meningkatnya ukuran Windows secara tidak langsung yang menghambat proses komputer |  
| User | Banyak user yang belum terbiasa menggunakan linux dan lumayan sulit untuk dipelajari | User-Friendly, dengan tampilan GUI yang sangat menarik, menmbuat Mac OS menjadi  salah satu OS yang banyak diminati khususnya oleh para graphic desainer | Paling disukai karena lebih mudah dipakai dan hampir digunakan oleh mayoritas pengguna komputer di dunia |  
User Interface | Memiliki banyak user interface | Tidak memiliki banyak user interface, tetapi sudah lebih mudah dipakai dan tampilannya menarik | Tidak memiliki banyak user interface |  
| Kelengkapan Program | Sudah terdapat banyak program yang siap untuk dipakai | Sudah terdapat program yang siap dipakai, tapi tidak terlalu banyak | Pertama kali memakai harus mengisi program aplikasi yang lain |  
Perangkat Lunak yang Bisa Dipakai | Sangat minim software karena sedikit developer yang membuat software di Linux | Macintosh masih kalah dibanding Windows tetapi lebih unggul dari Linux, karena software dan hardware-nya harus memiliki licence dari Apple, sedangkan Windows didukung dari berbagai vendor software dan hardware | Memiliki banyak software yang bisa dipakai karena para developer lebih memilih mengembangkan softwarenya di Windows yang pembuatannya mudah dan banyak yang memakai |  
| Pilihan sitem operasi | Linux banyak jenis yang bisa kita pilih baik lokal maupun luar | Macintosh tidak terlalu banyak yang yang disediakan | Windows tidak banyak varian/jenis yang di tawarkan |  
| Segi hardware | Ada beberapa hardware yang tidak bekerja atau belum maksimal karena ada vendor yg tidak tidak menyediakan driver versi Linux | Mac tidak bisa dirakit sendiri karena Apple sudah tidak memberi license buat perusahaan lain untuk membuat hardware yang bisa menggunakan Mac OS | Di Windows, biasanya Anda tidak pernah mendengar masalah hardwre, karena hampir semua hardware yang ada sudah menyertakan drivernya |  
 
##### Referensi :
- http://ayukhusnulkhotimah.web.ugm.ac.id/2018/03/04/perbandingan-linux-mac-os-window/
- https://www.nesabamedia.com/distro-linux/
- https://id.wikipedia.org/wiki/Linux
- https://id.wikipedia.org/wiki/Distribusi_Linux

<div style="page-break-after: always;"></div>

# Instalasi
Sub-materi
1. [Persiapan](#1-persiapan)
2. [Teknik Instalasi](#2-teknik-instalasi)
3. [Membuat Virtual Machine](#3-membuat-virtual-machine)
4. [Instalasi Ubuntu](#4-instalasi-ubuntu-1604)

### 1. Persiapan
- File ISO Ubuntu 16.04 LTS ([Download](http://releases.ubuntu.com/16.04/ubuntu-16.04.5-desktop-amd64.iso))
- Installer VirtualBox ([Download](https://download.virtualbox.org/virtualbox/5.2.22/VirtualBox-5.2.22-126460-Win.exe))

### 2. Teknik Instalasi
Jika hendak menggunakan lebih dari satu sistem operasi atau sering disebut OS(operating system) pada suatu komputer biasanya ada dua pilihan teknik instalasi, yaitu **dual-boot** atau **virtualisasi**.
**Dual-boot** adalah teknik menginstall dua atau lebih OS pada satu komputer, dimana masing-masing OS berjalan secara mandiri. Pengguna hanya dapat menggunakan salah satu OS dalam satu watu, dengan cara memilih OS yang akan dipakai ketika menyalakan komputer.

![Tampilan GRUB Dual Boot Linux(Ubuntu) dan Windows](img/tampilan_grub_dual_boot.png "Tampilan GRUB Dual Boot Linux(Ubuntu) dan Windows")

Sedangkan **Virtualisasi** adalah teknik menginstal dan menjalankan suatu OS di atas OS lain sebagai host, yaitu dengan menggunakan program berjenis mesin virtual (virtual machine), salah satu contohnya adalah VirtualBox. Dengan mesin virtual ini, pengguna dapat menjalankan suatu OS, sebagai contoh Linux, pada saat OS lain berjalan, sebagai contoh Windows, sehingga pengguna dapat menjalankan beberapa OS sekaligus dalam satu waktu.

Berikut ini perbandingan termasuk kelebihan dan kekurangan dari kedua teknik instalasi tersebut:

|Dual-Boot|Virtual Machine|
|---|---|
|Secara umum lebih cepat, karena masing - masing OS berjalan secara mandiri|Secara umum lebih lambat, karena harus berbagi sumber daya prosesor dan memori dengan OS host|
|Kedua OS dapat bertukar data dengan mudah, asalkan saling mendukung format sistem file pada harddisk|Bertukar file antar OS tidak dapat dilakukan secara langsung, perlu beberapa konfigurasi|
|Hanya dapat menjalankan salah satu OS saja pada satu waktu|Dapat menjalankan beberapa OS sekaligus dalam satu waktu(asal spesifikasi komputer mencukupi)|
|Prosedur instalasi dan konfigurasi untuk dual-booting cukup rumit dan beresiko (kehilangan data), terutama pada saat partisi harddisk|Prosedur instalasi OS menjadi mudah tanpa harus bingung dengan hal-hal teknis seperti partisi harddisk|
|Ideal untuk penggunaan sehari-hari, yang membutuhkan performa penuh komputer|Ideal untuk sekedar mengetes suatu OS, atau sekedar menjalankan suatu program yang tidak dapat berjalan pada OS host|
|Jika terjadi kerusakan pada salah satu OS, ada kemungkinan berpengaruh dengan OS satunya|Kerusakan pada OS yang di virtualisasikan tidak akan berpengaruh pada OS host|

### 3. Membuat Virtual Machine
1. Install Oracle VM VirtualBox. Jika sudah ada, lanjut ke langkah 2.
2. Buka aplikasi Oracle VM VirtualBox di Windows Anda.  
![Tampilan awal Oracle VM VirtualBox](img/vb_home.png "Tampilan awal Oracle VM VirtualBox")

3. Klik **New** untuk membuat Virtual Machine baru. Isi **name** dengan nama 'Ubuntu 16.04', **type** pilih Linux, dan pilih **version** sesuai sepesifikasi PC atau Laptop Anda. Kemudian klik **Next** untuk proses selanjutnya.  
![Membuat Virtual Machine baru Oracle VM VirtualBox](img/vb_buat_vm_baru.png "Membuat Virtual Machine baru Oracle VM VirtualBox")

4. Selanjutnya Anda disuruh untuk menentukan besaran memori, namun VirtualBox otomatis merekomendasikan besarnya memori. Jika sudah sesuai klik **Next**.  
![Set memori VM baru Oracle VM VirtualBox](img/vb_set_memori.png "Set memori VM baru Oracle VM VirtualBox")

5. Selanjutnya Anda disuruh untuk menentukan ukuran harddisk, namun VirtualBox otomatis merekomendasikan ukuran harddisk. Jika sudah sesuai klik **Next**.  
![Set ukuran harddisk VM baru Oracle VM VirtualBox](img/vb_set_disk.png "Set ukuran harddisk VM baru Oracle VM VirtualBox")

6. Klik **Next** saja pada proses ini untuk menuju proses selanjutnya.  
![Set tipe harddisk VM baru Oracle VM VirtualBox](img/vb_set_disk_type.png "Set tipe harddisk VM baru Oracle VM VirtualBox")

7. Klik **Next** saja pada proses ini untuk menuju proses selanjutnya.  
![Set tipe harddisk VM baru Oracle VM VirtualBox(2)](img/vb_set_disk_type2.png "Set tipe harddisk VM baru Oracle VM VirtualBox(2)")

8. Menentukan ukuran harddisk(direkomendasikan minimal 10GB). Klik **Create**.  
![Set ukuran harddisk VM baru Oracle VM VirtualBox(3)](img/vb_set_disk_size.png "Set ukuran harddisk VM baru Oracle VM VirtualBox(3)")

9. Virtual machine yang Anda buat sudah jadi! Namun, Anda masih harus menginstall Ubuntu 16.04 pada virtual machine yang telah Anda buat.

### 4. Instalasi Ubuntu 16.04
Setelah berhasil membuat virtual machine, selanjutnya kita menginstall Ubuntu 16.04 pada virtual machine yang telah dibuat.
1. Pilih virtual machine yang ingin di install, lalu klik **Setting** -> **Storage** -> **Controller: IDE** -> **Empty** -> **Choose Virtual Optical Disk File** untuk memilih file ISO Ubuntu yang akan di install. Kemudian klik **Start** (tanda panah hijau).
![Set file ISO Ubuntu VM baru Oracle VM VirtualBox](img/vb_set_iso.png "Set file ISO Ubuntu VM baru Oracle VM VirtualBox")  
![Set file ISO Ubuntu VM baru Oracle VM VirtualBox(2)](img/vb_get_iso_file.png "Set file ISO Ubuntu VM baru Oracle VM VirtualBox(2)")  
![Set file ISO Ubuntu VM baru Oracle VM VirtualBox(3)](img/vb_vm_jadi.png "Set file ISO Ubuntu VM baru Oracle VM VirtualBox(3)")

2. File ISO Ubuntu sudah berjalan. Selanjutnya tinggal ikuti langkah instalasinya. Klik **Install Ubuntu**.  
![Instalasi Ubuntu(1)](img/vb_install_ubuntu1.png "Instalasi Ubuntu(1)")

3. Tidak perlu mencentang apapun untuk menghemat waktu instalasi, kemudian klik **Continue**.  
![Instalasi Ubuntu(2)](img/vb_install_ubuntu2.png "Instalasi Ubuntu(2)")

4. Pilih **Erase disk and install Ubuntu**, lalu klik **Install Now**.  
![Instalasi Ubuntu(3)](img/vb_install_ubuntu3.png "Instalasi Ubuntu(3)")

5. Memilih zona waktu. Ketik **Jakarta**, lalu klik **Continue**.  
![Instalasi Ubuntu(4)](img/vb_install_ubuntu4.png "Instalasi Ubuntu(4)")

6. Memilih bahasa yang digunakan untuk penyesuaian keyboard. Ikuti saja defaultnya, langsung klik **Continue**.  
![Instalasi Ubuntu(5)](img/vb_install_ubuntu5.png "Instalasi Ubuntu(5)")

7. Mengatur nama, nama komputer, username, dan password. Biasanya ketika mengetikkan nama kita pada form **Your name**, form **Your computer's name** dan form **Pick a username** otomatis tergenerate sesuai nama yang kita ketikkan.  
![Instalasi Ubuntu(6)](img/vb_install_ubuntu6.png "Instalasi Ubuntu(6)")

8. Tunggu hingga proses instalasi selesai.  
![Instalasi Ubuntu(7)](img/vb_install_ubuntu7.png "Instalasi Ubuntu(7)")

9. Instalasi sudah selesai! Klik **Restart Now** untuk me-*restart* Ubuntu untuk menyudahi tahapan instalasi.  
![Instalasi Ubuntu(8)](img/vb_install_ubuntu8.png "Instalasi Ubuntu(8)")


##### Referensi
- https://abrari.wordpress.com/2009/12/12/dual-booting-vs-virtualisasi/
- https://id.wikihow.com/Memasang-Ubuntu-di-VirtualBox
- https://www.ubuntu.com/
- https://www.virtualbox.org/

<div style="page-break-after: always;"></div>

# Konsep
Sub-Materi
1. [Struktur Folder](#1-Struktur-Folder)
2. [Repository](#2-Repository)

### 1. Struktur Folder
Jika kita ingin belajar Linux lebih mendalam, hal yang paling dasar untuk dipahami adalah struktur direktorinya. Struktur direktori pada Linux sangat berbeda dengan Windows. 
#### 1.1 Struktur direktori Windows
Sistem operasi Windows memiliki struktur direktori yang sederhana dan mudah dipahami, seperti dibawah ini:  

![Struktur direktori Windows](img/windows.jpg "Struktur direktori Windows")

- **Program Files** : Berfungsi untuk menyimpan program-program dan aplikasi  yang terinstal di dalam Windows
- **Windows** : menyimpan segala proses juga konten-konten utama windows. Akan terjadi kerudakan system jika ada kesalahan dalam mengatur folder ini. Isi dari folder ini berupa system32, Assembly, dan Web
- **Temp** : digunakan untuk menyimpan file-file sementara
- **Document and Settings** : berfungsi untuk menyimpan dokumen dan pengaturan-pengaturan user mulai dari desktop, start menu, dsb

#### 1.2 Struktur direktori Linux

#### 1.2.1 Struktur direktori
Pada struktur direktori Linux tidak akan ditemukan drive C, drive D, dan drive-drive lainnya karena Linux menganut satu direktori utama yaitu "**/**" (baca: root). Berikut ini adalah struktur direktori beserta apa yang berada di dalam sistem operasi Linux:

![Struktur direktori Linux](img/linux.jpg "Struktur direktori Linux")

Penjelasan beberapa direktori yang perlu kalian ketahui: 
- **/** ("root") : Merupakan root atau akar dari seluruh direktori global. Partisi dimana diletakkan/ (root system) akan menjadi direktori sistem atau partisi pokok. Hanya bisa diakses oleh user root atau super user.
- **/bin** (user binaries) : Memuat program arahan yang merupakan sebagian dari sistem operasi Linux. Direktori ini meng-handle perintah standar Linux, seperti cd, ls, cp, dll.
- **/boot** (boot loader files) : Direktori yang berisi file-file yang berhubungan dengan boot loader, contohnya Grub boot manager, File Kernel initrd, vmlinux, dll.
- **/dev** (device files) : Memuat semua file penting.
- **/etc** (configuration files) : Berisi file-file konfigurasi sistem. Selain itu, juga berisi file yang dijalankan ketika start up.
- **/home** (home directories) : GNU/Linux merupakan sistem operasi yang mendukung multi-user. Kebijakannya sangat ketat. Oleh karena itu, direktori **/home** menyimpan semua direktori home user kecuali user root atau super user.
- **/lib** (system libraries) : Memuat file-file library Linux yang mendukung binary files dalam direktori **/bin** dan **/sbin**
- **/media** (removable media devices) : Direktori untuk mounting removable media seperi drive CD-ROM, hardisk eksternal, flashdisk, zip drive, dll.
- **/mnt** (mount directory) : Direktori untuk mounting file sistem sementara.
- **/opt** (optional add-on applications) : Direktori ini menyimpan file-file tambahan dari vendor-vendor tertentu. Sifatnya hanya optional. Diharapkan dengan adanya direktori ini, manajemen paket aplikasi tambahan dapat dilakukan dengan mudah.
- **/sbin** (system binaries) : Memuat file administration yang dapat diakses seperti mount, shutdown, umount.
- **/srv** (service data) : Memuat data untuk layanan (HTTP, FTP, etc.) yang ditawarkan oleh sistem.
- **/tmp** (temporary files) : Direktori yang digunakan untuk menyimpan data sementara. Isi dari direktori ini dibersihkan setiap kali sistem boot.
- **/usr** (user programs) : direktori yang berisi file-file binary, libraries, dokumentasi, dan source code dari sistem. 
- **/var** (variable files) : Memuat berbagai sistem file seperti log, direktori mail, print dan lain – lain. Yang sering kali berubah kandungannya.

Salah satu perbedaan mendasar dan mencolok antara Linux dan Windows adalah apabila kita memasuki inti dari sistem Windows (yakni System 32), kita bisa dengan bebas meng-copy atau paste file yang berada di dalamnya. Tentunya hal ini membuat Windows sangat mudah diinfeksi virus, bahkan jika kita memasang antivirus sekalipun.
Sedangkan pada Linux, jika kita ingin meng-copy, paste, atau mengedit file di dalam direktori sistem Linux (**/**, dibaca root) kita harus menggunakan super user (root) dan melakukannya file via terminal. Hal ini menyebabkan Linux menjadi sangat kebal terhadap virus.
#### 1.2.2 Absolute Path & Relative path
Setiap file dan direktori dalam filesystem Linux dapat diakses bila kita mengetahui jalur atau path direktorinya.

**Absolute Path**

Path ditulis dengan lengkap dari nama parent direktori sampai nama filenya. Misal, _/home/Penunggu/aloha.txt_ untuk meng-akses file _aloha.txt_ atau _/home/Penunggu/Downloads/_ untuk mengakses direktori.

**Relative Path**

Path tidak ditulis lengkap, tetapi berdasarkan posisi direktori yang sedang anda akses atau sering disebut direktori kerja (working directory). Misal, saat ini anda berada di direktori _/home/Penunggu_ atau "**~**" Maka cukup dituliskan aloha.txt untuk meng-akses file _aloha.txt_ atau _Downloads/_ untuk mengakses direktori. Nama working directory dapat diganti dengan sebuah tanda "**.**" ( single dot atau titik tunggal), sedangkan parent directory dapat digantikan dengan tanda "**..**" (double dot atau titik ganda).
### 2. Repository
#### 2.1. Apa itu Repository?  
   **Repository** adalah tempat menyimpan berbagai macam program atau aplikasi yang telah di buat sedemikian rupa sehigga bisa di akses melalui internet. Selain di internet, **Repository** juga tersedia di media seperti DVD sebagai alternatif **Repository** saat tak ada koneksi internet. Ketika kita melakukan download Repository melalui internet default servernya adalah server luar, seperti archive.ubuntu.com, security.ubuntu.com, dll. Untuk Fungsinya, disini Repository berperan sebagai penyedia aplikasi atau kumpulan paket software dari distro-distro linux, yang dapat di akses melalui internet.  
  
#### 2.2. Dimana file Repository itu berarda?  
File Repository ini langsung otomatis berada di laptop atau PC kita saat kita sudah menginstall linux dengan nama file biasanya "sources.list", terletak di folder apt di dalam folder etc. Jika ingin melihat Repository milik kita hanya perlu mengetikan :  

```sh
$ sudo gedit /etc/apt/sources.list
```

Kita bisa melakukan edit seperti menambah, menghapus, mengganti Repostitory milik kita sesuai yang kita inginkan.  
  
#### 2.3. Apakah Repository itu Penting?  
Adanya Repository di linux itu sangatlah _**Penting**_, karena itu adalah tempatnya paket-paket software untuk linux itu sendiri, kita hanya perlu langsung menginstall tanpa harus cari lagi paket softwarenya karena sudah tersedia di Repository tersebut. walau pun kita bisa juga mencari paket softwarenya secara manual dan menginstallnya juga, tetapi cara tersebut cukup ribet dan akan banyak memakan waktu. 
  
#### 2.4. Apakah semua Paket software ada di Repository? 
Tidak semua paket software langsung ada di repository, itu sebabnya kita harus tau nama file repository dan letaknya dimana, karena jika kita akan menginstall suatu software dan aplikasi, kemudian di Repository ternyata paketnya belum ada, kita bisa mencari repositorynya dan menambahkannya di di Repository kita dengan mengedit file sources.list tadi, yang berada di directory sudo gedit /etc/apt/sources.list.

##### Referensi
- http://2010183ifunsika.blogspot.com/2012/10/analisis-struktur-sistem-linux-dan.html
- http://www.belkomindo.com/2015/12/apasih-repository-itu.html
- http://kuntoaji.blogspot.com/2008/08/absolute-path-relative-path.html

<div style="page-break-after: always;"></div>

# Command Line Interface 
Sub-Materi
1. [Basic Command](#1-basic-command)
2. [Administrative Command](#2-administrative-command)
3. [File Editing](#3-file-editing)
4. [Export Variable](#4-export-variable)
5. [Cek IP dan Koneksi](#5-cek-ip-dan-koneksi)
6. [Menginstall Software](#6-menginstall-software)

### 1. Basic Command
##### 1. pwd
*print working directory*. Untuk mengetahui di directory mana kita berada sekarang.  
![pwd](img/pwd.png)

##### 2. ls
*list*. Untuk menampilkan file-file apa saja yang ada di suatu directory.  
![ls](img/ls.png)  
Parameter yang sering dipakai pada perintah ls adalah `-a` dan `-l`.
- Saat menggunakan parameter `-a` maka semua file akan ditampikan, termasuk yang *hidden* (diawali dengan `.`).  
![ls -a](img/ls_a.png)
- Sedangkan parameter `-l` menampilkan file yang tidak *hidden* dalam format *long-list*.  
![ls -l](img/ls_l.png)

##### 3. man
*manuals*. Digunakan untuk melihat fungsi dan parameter dari suatu comman
Contoh `man ls` akan menampilkan manual penggunaan command `ls`.
Untuk keluar dari tampilan manual tersebut kita tinggal menekan tombol `q`. 
![man](img/manls.png)
*man pages* atau perintah `man` juga memiliki keunikan dalam *device* **FreeBSD** dan **Linux** karena membagi *man pages* kedalam beberapa bagian seperti dalam tabel dibawah ini.
![man](img/man-pages.png)

Sebagai contohnya, didalam **Linux** biasanya terdapat file `passwd` dan perintah `passwd`. Jika kita menjalankan perintah
+ `man passwd` maka perintah `man` akan memberikan *manuals* untuk perintah `passwd`
![man](img/man-command-passwd.png)
+ Namun jika menjalankan perintah `man 5 passwd` maka akan memberikan *manuals* untuk file `passwd` 
![man](img/man-file-passwd.png)

Untuk mengetahui ada berapa bagian *manual* yang tersedia, kita dapat menjakankan perintah `man -k [kata yang dicari]`
![man](img/man-option-k.png)

##### 4. cd
*change directory*. Digunakan untuk pindah ke directory lain. Syntax-nya adalah ```cd [namadirectory]```.
Misalnya kita sedang berada di directory `/home/Penunggu` dan ingin berpindah ke directory `Desktop/`. Maka command yang kita gunakan adalah `cd Desktop/`  
![cd](img/cd.png)  
Contoh lain:
+ `cd` atau `cd ~` untuk pindah ke directory home user
+ `cd /` untuk pindah ke directory root
+ `cd ..` untuk pindah ke parent directory dari directory sekarang
+ `cd -` untuk pindah ke working directory sebelumnya 
 
##### 5. mkdir
*make directory*. Digunakan untuk membuat sebuah directory (folder).
Syntax-nya adalah ```mkdir [namadirectory]```  
![mkdir](img/mkdir.png)

##### 6. cp
*copy*. Digunakan untuk menyalin (meng-copy) file.
Syntax-nya adalah ```cp [namafile] [namacopyannya]```  
![cp](img/cp.png)

##### 7. mv
*Move* Digunakan untuk memindahkan suatu file ke directory lain.
+ Untuk memindahkan file, syntax-nya adalah ```mv [namafile] [pathbarunya]```  
![mv](img/mv.png)
+ Selain itu `mv` dapat juga digunakan untuk me-rename file, syntax-nya adalah ```mv [namafile] [namabaru]```  
![mv](img/mv2.png)

##### 8. cat
*concatenate*. Digunakan untuk menampilkan isi dari suatu file.  
![cat](img/cat.png)

##### 9. rm
*remove*. Digunakan untuk menghapus suatu file. Syntax-nya adalah ```rm [namafile]```  
![rm](img/rm.png)  
Selain itu rm juga dapat digunakan untuk menghapus directory, yaitu dengan menambahkan parameter `-r`  
![rm -r](img/rm_r.png)

##### 10. rmdir
*remove directory*. Digunakan untuk menghapus directory yang kosong. Syntax-nya adalah ```rmdir [namafolder]```  
![rmdir](img/rmdir.png)

##### 11. echo
Digunakan untuk menampilkan string yang kita inputkan. Syntax-nya adalah ```echo [string yang diinginkan]```  
![echo](img/echo.png)

##### 12. grep
Digunakan untuk menampilkan setiap baris pada suatu file yang mengandung kata yang dicari.
Syntax-nya adalah `grep "[katayangdicari]" [namafile]`  
![grep](img/grep.png)

##### 13. zip
Command ini digunakan untuk melakukan compress data menjadi bentuk zip. Syntax-nya adalah ```zip [namafilezip] [file1] [file2]```.
Misalnya kita ingin mengompress file **makanan** dan **cemilan** menjadi  **energi.zip** .
Maka command yang kita jalankan adalah `zip energi makanan cemilan`   
![zip](img/zip.png)

##### 14. unzip
Kebalikan dari command zip, unzip digunakan untuk mengekstrak isi dari file .zip
Syntax-nya adalah ```unzip [namafilezip]```.
Jadi untuk mengekstrak file foobar.zip kita perlu menjalankan comman `unzip energi.zip`.
![unzip](img/unzip.png)

##### 15. exit
Digunakan untuk menutup terminal atau mengakhiri suatu script (misalnya saat melakukan ssh ke komputer lain)

##### 16. clear
Digunakan untuk 'membersihkan' isi layar terminal.
Sebelum clear:  
![clear1](img/sebelumclear.png)  
Sesudah clear:  
![clear2](img/sesudahclear.png)

##### 17. tree
Digunakan untuk menampilkan list directory.
Untuk menggunakan command ini, user harus meng-*install*-nya terlebih dahulu dengan command
`sudo apt-get install tree`  
![tree](img/tree.png)

##### 18. mount
Digunakan untuk melakukan mount. Syntax-nya adalah `sudo mount [file/device yang mau di-mount] [directory tempat dia akan di-mount]`
Contoh: ada suatu file _iso_ yang berisi beberapa file. Untuk dapat mengakses file-file di dalamnya melalui terminal, maka kita harus _mount_ file tersebut ke suatu directory.  
![mount](img/mount.JPG)  

##### 19. unmount
Digunakan untuk melakukan _unmount_. Syntax-nya adalah `umount [directory tempat suatu file/device di-mount]`.
Nama command-nya `umount` yaa bukan _unmount_.  
![unmount](img/umount.JPG)  

##### 20. dpkg
Adalah Debian Package Manager. Salah satu kegunaannya adalah untuk meng-install suatu aplikasi yang di-download dari browser.
Syntax-nya adalah `dpkg -i [path ke file installer aplikasi]`
Contohnya adalah saat kalian ingin meng-install _google chrome_ maka kalian dapat menggunakan perintah-perintah di bawah ini:
pertama download dulu installer google chrome yang berekstensi __.deb__
```sh
$ wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb  
```  
![wget](img/wget.JPG)  

lalu untuk meng-installnya gunakan command
```sh
$ dpkg -i google-chrome-stable_current_amd64.deb
```  
![dpkg](img/dpkg2.jpg)  

### 2. Administrative Command
##### 1. su
Digunakan untuk mengganti user ID atau menjadi superuser.
Syntax-nya adalah `sudo su`

##### 2. sudo
*superuser do*. Digunakan untuk menjalankan command sebagai superuser, superuser biasanya digunakan untuk meng-edit file konfigurasi, mengatur paket, menginstall program.
Syntax-nya adalah `sudo [command]`

###### 3. chown
*change owner*.
+ Digunakan untuk mengubah kepemilikan dari suatu file. Syntax-nya adalah 
```chown [namauser] [namafile]```  
![chown](img/chown.png)  
+ Selain user pemilik, command `chown` juga bisa digunakan untuk mengganti *group* pemilik. Syntax-nya adalah
```chown [namauser]:[namagroup] [namafile]```
![chown-group](img/chown2.png)  
**Note:** mohon diingat bahwa nama user dan group yang dipilih harus sudah ada di komputer tersebut.

##### 4. adduser
*adduser*.
+ Digunakan untuk membuat user baru. Penggunaan perintah ini sangat sederhana, hanya dengan sudo adduser $loginname. Perintah tersebut akan membuat home directory dan user masuk ke default group, lalu sistem akan meminta informasi mengenai user secara rinci.
+ User baru dapat ditambahkan ke dalam group *sudoers* menggunakan perintah `sudo adduser [nama_user] sudo` 

##### 5. passwd
Digunakan untuk meng-*update* password user.  
![passwd](img/passwd.png)  

##### 6. chmod
*change mode*. Digunakan untuk mengubah izin akses dari suatu dokumen.
Contoh syntax `chmod 777 [namafile]`
*777* adalah representasi dari permission yang diberikan. Angka pertama melambangkan permission untuk user, angka kedua untuk group, dan angka ke tiga untuk *Others*  
![chmod](img/chmod.png)  

Permission Table

|#|Permission|rwx|Binary|
|---|---|---|---|
|7|read, write and execute|rwx|111|
|6|read and write|rw-|110|
|5|read and execute|r-x|101|
|4|read only|r--|100|
|3|write and execute|-wx|011|
|2|write only|-w-|-1-|
|1|execute only|--x|001|
|0|none|---|000|

### 3. File Editing
##### 1. vim
vim merupakan singkatan dari "Vi IMprovised" dan merupakan salah satu teks editor pada OS Linux yang dapat digunakan untuk mengedit jenis teks apapun, termasuk suatu program komputer. Vim diupgrade dari teks editor vi, yang memiliki beberapa peningkatan dari vi, beberapa diantaranya adalah syntax highlighting, on-line help, multi-windows dan buffers, dll.
Untuk lebih jelas perbedaan antara vim dan vi : https://github.com/vim/vim/blob/master/runtime/doc/vi_diff.txt
##### Install vim teks editor
```sh
$ sudo apt-get update
```
```sh
$ sudo apt-get install -y vim
```
##### Membuat dan meng-insert teks 
Syntax yang biasa digunakan adalah `vim [nama-file]`. Setelah command tersebut dijalankan akan terlihat lambang `~` pada tiap baris yang kosong. 
```sh
$ vim nyoba.txt
```
![vim3](img/vim3.png)

Vim sekarang dalam *mode normal*. Untuk menginsertkan teks, maka ketik `i` untuk masuk ke *mode insert* dan diikuti dengan mengetikkan teks yang diinginkan.
Ketika kita menekan `i` untuk menginsertkan teks, karakter yang kita inputkan akan terketik sesuai dengan posisi kursor saat itu. Agar karakter yang kita inputkan terketik pada sebelah kanan posisi kursor, maka kembalikan vim pada mode normal, dan tekan `a`. Maka karakter yang kita inputkan akan terketik pada sebelah kanan posisi kursor saat itu.

Jika sudah selesai menginputkan teks, tekan `esc` dan vim akan kembali ke mode normal. Dalam mode normal, tekan `h` untuk bergerak ke kiri, `l` untuk ke kanan, `j` untuk bergerak ke atas dan `k` untuk ke bawah.  
![vim4](img/vim4.png)

##### Menghapus karakter
Untuk menghapus sebuah karakter, selain bisa dilakukan pada mode insert dapat pula dilakukan ketika vim dalam *mode normal*. Yaitu dengan mengarahkan tanda kursor pada karakter yang ingin dihapus, dan menekan `x`.
Contohnya misal ketika kursor diletakkan pada huruf pertama yaitu huruf *i* pada kalimat *ini baris 3 ya* dan `x` ditekan sebanyak 4 kali, maka kalimat pada baris tersebut yang tersisa adalah *baris 3 ya*.  
![vim5](img/vim5.png)

##### Menghapus baris
Jika yang ingin dihapus adalah satu baris penuh, maka yang perlu dilakukan pada *mode normal* yaitu memposisikan kursor pada baris yang ingin dihapus, dan ketikkan `dd`. Misalnya kita ingin menghapus baris pertama dimana terdapat kalimat *hehe :)* maka setelah memposisikan kursor pada baris tersebut, ketika kita mengetikkan `dd` maka baris yang tersisa adalah *nyoba nulis* sebagai baris pertama dan *baris 3 ya* sebagai baris ke-2.  
![vim6](img/vim6.png) 

##### Menggabungkan dua baris
Untuk menggabungkan dua baris menjadi satu baris atau dengan kata lain menghilangkan spasi diantara 2 baris, maka pada *mode normal* cukup dengan memposisikan kursor pada kalimat di baris pertama dan tekan `J`. Maka kalimat pada baris kedua akan menjadi satu baris dengan kalimat pertama.  
![vim7](img/vim7.png)

##### Undo dan Redo
Pada teks editor vim, untuk meng-undo perubahan yang baru saja kita lakukan dilakukan dengan mengetik `u`. Maka pengerjaan yang baru saja kita lakukan akan ter-undo.
Sedangkan untuk me-redo atau kebalikan dari undo yang baru saja kita lakukan yaitu dengan menekan `Ctrl+R`.

##### Menulis pada line baru
Pertama posisikan kursor pada sebuah baris. Untuk membuat line baru dibawah baris tersebut, tekan `o` dan otomatis sebuah baris baru akan terbentuk di bawah kalimat tersebut dengan vim sudah berada pada mode insert. Jika baris yang ingin ditambahkan berada diatas baris tempat kursor berada saat ini, maka dilakukan dengan menekan `O`. 

##### Keluar dari teks editor vim
1. Keluar ketika dalam mode insert tanpa menyimpan perubahan apa-apa dengan mengetikkan `:q!`
2. Keluar ketika dalam mode insert dengan menyimpan perubahan yang dilakukan `:wq`
3. Keluar dan menyimpan perubahan dilakukan pada mode normal dengan mengetikkan `ZZ`

Untuk mengeksplorasi lebih lanjut mengenai teks editor vim, terdapat tutorial vim yang bisa diakses melalui terminal
```sh
$ vimtutor
```

##### 2. gedit
Gedit atau *Gnome-Text-Editor* adalah teks editor untuk GNOME desktop dan dapat digunakan untuk mengedit teks jenis apapun.
Syntax yang biasa digunakan untuk menjalankan teks editor ini adalah 
```sh
$ gedit [nama-file]
```

Misal kita akan membuat file txt dengan nama *cobagedit* maka ketikkan pada terminal
```sh
$ gedit cobagedit.txt
```
Halaman gedit pun akan muncul dan kita bisa menginputkan teks yang kita inginkan.  
![gedit1](img/gdit1.png)

File gedit memungkinkan kita untuk mengedit banyak file sekaligus. Syntax yang digunakan 
```sh
$ gedit [file1 file2 ...]
```
misalnya mengedit 2 file yaitu *cobagedit.txt* dan *nyobajuga.txt*
```sh
$ gedit cobagedit.txt nyobajuga.txt
```  
![gedit2](img/gdit2.png)

##### 3. nano
Nano atau *Nano's ANOther editor* merupakan teks editor yang dikembangkan mirip dengan teks editor *Pico* yang menjadi editor default dari Pine. Nano termasuk teks editor yang *user-friendly* karena adanya *shortcut* pada bagian bawah editor sehingga memudahkan pengguna dalam menggunakan teks editor ini.
Syntax yang biasa digunakan 
```sh
$ nano [nama-file]
```  
![nano1](img/nanoo.png)

Command tersebut akan memunculkan default nano-screen  

![nano2](img/nano2.png)

Untuk melihat list dari shortcut-shortcut yang ada tekan `Ctrl+G`

![nano3](img/nano3.png)

Ketika `Ctrl+X` ditekan untuk keluar dari editor, pada bagian bawah di baris ketiga dari bawah akan muncul pertanyaan *Save modified buffer?* Tekan `Y` untuk menyimpan perubahan dari file, dan `N` untuk keluar dari teks editor nano tanpa menyimpan perubahan. 

Selain itu sebelum benar-benar keluar dari teks editor nano, kita juga dapat merubah nama file yang baru saja kita buat tadi. Cukup dengan mengganti nama file sebelumnya yang tertera pada bagian bawah teks editor dimana terdapat tulisan *File name to write: ...* lalu tekan Enter.   
![nano4](img/nano4.png)

##### 4. touch
Digunakan untuk membuat sebuah file. Syntax yang digunakan 
```sh
$ touch [nama-file]
```  
![touch1](img/touch1.png)

### 4. Export Variable
Command *export* adalah salah satu command yang merupakan bagian dari shell (BuiltIn bash shell). Command ini cukup mudah digunakan karena syntax nya 'langsung' dan hanya memiliki 3 opsi perintah:

- `-p` : Daftar semua nama yang diekspor dalam shell saat ini
- `-n` : Hapus nama dari daftar ekspor
- `-f` : Nama diekspor sebagai fungsi

Secara umum, perintah ekspor menandai *environment variabel* untuk diekspor sehingga proses *child* yang baru bercabang dapat mewarisi semua variabel yang ditandai.

Contoh penggunaan export:

##### Meng-export Proxy
Untuk melakukan export proxy, misalnya menggunakan proxy ITS, maka syntax pada terminal
```sh
$ export http_proxy="http://username%40mhs.if.its.ac.id:password@proxy.its.ac.id:8080"
```
##### Men-set vim sebagai text editor
pada terminal ketikkan command
```sh
$ export EDITOR=/usr/bin/vim
```

Untuk cek hasil export variabel dapat melalui 
```sh
$ export -p
```
atau

```sh
$ export | grep EDITOR
```
![export1](img/export1.png)

##### Me-remove variable dari export list
Digunakan option `-n`
```sh
$ export -n EDITOR
```
### 5. Cek IP dan Koneksi

##### 1. ifconfig
Untuk mengkonfigurasi network interface.  
![ifconfig1](img/ifconfig1.png)

##### 2. ping
Merupakan sebuah utility program/alat untuk menguji apakah host tertentu dapat dijangkau.
Syntax yang biasa digunakan
```sh
$ ping [host tujuan]
```
![ping1](img/ping1.png)

##### 3. ssh
ssh adalah suatu network protokol untuk berkomunikasi secara aman antar komputer. ssh menghubungkan dan masuk (log) ke host yang ditentukan. Command ini dapat meremote server SSH komputer lain untuk menjalankan perintah-perintah dari jarak jauh.

ssh akan menyediakan koneksi terenkripsi yang aman antara dua host melalui jaringan yang tidak aman. Sambungan ini juga dapat digunakan untuk akses terminal, transfer file, dan untuk tunneling aplikasi lain.

Syntax yang biasa digunakan
```sh
$ ssh [hostname]
```

### 6. Menginstall Software

##### 1. apt-get update
```sh
$ sudo apt-get update
```
command **apt-get** dengan opsi **_update_** akan menyinkronisasi ulang file indeks paket dari sumber mereka. indeks-indeks dari paket yang tersedia akan diambil dari lokasi-lokasi yang telah ditentukan di _etc/apt/sources.list_.
##### 2. apt-get install pkg
```sh
$ sudo apt-get install <packages>
```
Opsi **install** ini diikuti oleh beberapa nama paket yang akan diinstall. 
Semua paket yang dibuthkan oleh paket yang akan diinstall juga akan terunduh dan terinstall. Berkas /etc/apt/sources.list digunakan untuk menentukan lokasi repositori dari paket yang dimaksud.

##### Referensi
+ https://searchdatacenter.techtarget.com/tutorial/77-Linux-commands-and-utilities-youll-actually-use
+ https://linux.die.net/man/8/apt-get
+ https://www.tutorialspoint.com/unix_commands/export.htm
+ https://www.howtogeek.com/howto/42980/the-beginners-guide-to-nano-the-linux-command-line-text-editor/
+ https://linux.die.net/man/1/gedit
+ https://www.computerhope.com/unix/vim.htm
+ https://www.simplified.guide/ubuntu/install-vim
+ https://www.ssh.com/ssh/command/
+ https://linux.die.net/man/8/ifconfig
+ https://en.wikipedia.org/wiki/Chmod
+ https://www.tecmint.com/dpkg-command-examples/
+ https://linuxconfig.org/how-to-install-google-chrome-browser-on-ubuntu-16-04-xenial-xerus-linux
+ https://askubuntu.com/questions/219545/dpkg-error-dpkg-status-database-is-locked-by-another-process

<div style="page-break-after: always;"></div>


# Networking

sub-materi

- [1. Setting IP Address Statis](#1-Setting-IP-Address-Statis)
  - [a. GUI](#a-GUI)
  - [b. CLI](#b-CLI)
- [2. Crimping](#wire-crimping)
- [3. VirtualBox Networking Modes](#3-VirtualBox-Networking-Modes)
- [4. Bridged Networking vs NAT](#4-Bridged-Networking-vs-NAT)

### 1. Setting IP Address Statis
##### A. GUI
1. klik ikon koneksi, lalu pilih 'edit'.

![](img/1.png)

2. pilih 'wired connection 1' dan klik tombol 'edit'

![](img/2.png)

3. pilih tab 'IPv4 Settings'

![](img/3.png)

4. ubah metodenya menjadi manual, serta tambahkan alamat baru yang kita inginkan, serta atur DNS server serta search domain sesuai kebutuhan.

![](img/4.png)

5. untuk mengaplikasikan perubahan silahkan lakukan koneksi ulang.

##### B. CLI
1.  ubah file **/etc/network/interfaces** dengan cara memasukkan command di bawah ini ke terminal :
```
$ sudo nano /etc/network/interfaces
```
2. ubah isi file menjadi
```
auto <interface>
iface <interface> inet static
address <ip static>
netmask 255.255.255.0
gateway 10.151.36.1
dns-search if.its.ac.id
```
3. setelah merubah isi file interfaces restart service networking kalian dengan menjalankan command berikut
```
$ sudo service networking restart
```

## WIRE CRIMPING
Dalam membangun jaringan komputer, tentunya dibutuhkan segala hal yang dapat menghubungkan perangkat-perangkat komputer yang ada. Hingga saat ini, komponen paling fundamental dalam jaringan komputer adalah kabel. Sekalipun teknologi nirkabel sudah lama ditemukan dan dikembangkan, tapi peran kabel jaringan tetap belum bisa tergantikan. Oleh karena itu di sini kita akan belajar bagaimana membuat kabel jaringan (dalam hal ini kabel UTP) menjadi fungsional.

__1. *Kebutuhan*__

Peralatan dan bahan yang perlu dipersiapkan:

__1.1. Tang Crimping__

![ExportObjects](images/taang.jpg)

__1.2. RJ-45__

![ExportObjects](images/rj45.jpg)

__1.3. Kabel UTP__

![ExportObjects](images/utp.jpg)

__1.4. Lan tester__

![ExportObjects](images/lantest.jpg)

__2. *Jenis-Jenis Pengkabelan*__

__2.1. Straight (T568B)__

Kabel straight merupakan kabel yang memiliki cara pemasangan yang sama antara ujung satu dengan ujung yang lainnya. Kabel straight digunakan untuk menghubungkan 2 device yang berbeda, misalnya antara switch dengan router dan komputer dengan switch. Urutan kabel straight jika dilihat dari sisi tembaga RJ-45 adalah seperti dibawah ini:

![ExportObjects](images/straight.jpg)


__2.2. Crossover (T568A)__

Kabel crossover merupakan kabel yang memiliki susunan berbeda antara ujung satu dengan ujung dua. Kabel crossover digunakan untuk menghubungkan 2 device yang sama. Jika dilihat dari sisi tembaga RJ-45, berikut susunan kabel crossover:

![ExportObjects](images/cross.jpg)

__3. *Cara Crimping*__

- Mengupas kulit kabel selebar +-2 cm menggunakan tang crimping.

- Menyusun rapi delapan kabel yang terdapat didalam kabel UTP sesuai dengan jenis kabel mana yang ingin dibuat (straight atau cross).

- Meluruskan kabel yang masih kusut.

- Meratakan ujung kabel dengan memotong nya menggunakan tang crimping.

- Memasukan kabel kedalam konektor RJ-45, pastikan ujung kabel menyentuh ujung RJ-45, dan jepitlah menggunakan tang crimping.

- Lakukan hal serupa pada kedua ujung kabel.

- Menguji menggunakan LAN tester, jika semua lampu menyala, berarti kabel tersebut telah di crimping dengan benar dan bisa digunakan.

### 3. VirtualBox Networking Modes

- Not attached

- Network Address Translation (NAT)

- NAT Network

- Bridged networking

- Internal networking

- Host-only networking

- Generic networking


### 4. Bridged Networking vs NAT

![NAT and Bridged network simple diagram](img/0.png)

Dalam diagram ini, garis vertikal di sebelah firewall merepresentasikan jaringan produksi dan kita dapat melihat bahwa 192.168.1.1 adalah alamat IP firewall _organisasi_ yang menghubungkannya ke Internet. Ada juga virtual host dengan tiga mesin virtual yang berjalan di dalamnya. Lingkaran merah mewakili adaptor virtual yang menghubungkan mesin virtual NAT (172.16.1.1). Kita dapat melihat bahwa ada dua mesin virtual seperti itu dengan alamat IP 172.16.1.2 dan 172.16.1.3. Saat kita mengonfigurasi mesin virtual yang menggunakan NAT, ia tidak melihat jaringan _organisasi_ secara langsung. Bahkan, semua lalu lintas yang berasal dari mesin virtual akan menggunakan alamat IP host VM. Di belakang layar, lalu lintas dari mesin virtual diarahkan pada virtual host dan dikirim melalui adaptor fisik host dan, akhirnya, ke Internet.

Mesin virtual ketiga (192.168.1.3) dikonfigurasi dalam mode “**bridged**” yang pada dasarnya berarti bahwa adaptor jaringan virtual dalam mesin virtual tersebut dijembatani ke jaringan _organisasi_ dan mesin virtual itu beroperasi seolah-olah ada langsung di jaringan _organisasi_. Seperti mesin virtual berbasis NAT yang tidak dapat melihat jaringan _organisasi_, begitu juga sebalikya, mesin virtual dengan mode bridged network tidak dapat melihat dua mesin virtual berbasis NAT.


##### Referensi :
- https://www.virtualbox.org/manual/ch06.html#networkingmodes
- http://techgenix.com/nat-vs-bridged-network-a-simple-diagram-178/
- https://www.virtualbox.org/manual/ch06.html#networkingmodes

<div style="page-break-after: always;"></div>


# Penggunaan Aplikasi

### Instalasi LAMP Stack pada Ubuntu
Sub-Materi
1. [Instalasi Apache](#1-instalasi-apache)
2. [Instalasi MySQL](#2-instalasi-mysql)
3. [Instalasi PHP](#3-instalasi-php)
4. [Penggunaan](#4-penggunaan)

#### 1. Instalasi Apache
Untuk melakukan instalasi, ketikkan command berikut:

```shell
$ sudo apt-get update
$ sudo apt-get install apache2
```

#### 2. Instalasi MySQL
Untuk melakukan instalasi, ketikkan command berikut:

```shell
$ sudo apt-get install mysql-server
```

Selama proses instalasi, pengguna akan diminta memasukkan password untuk MySQL root user.

#### 3. Instalasi PHP
Untuk melakukan instalasi, ketikkan command berikut:
```shell
$ sudo apt-get install php
```

#### 4. Penggunaan
__Apache__<br>
Untuk melihat apakah server apache sudah berjalan, ketikkan command berikut

```shell
sudo service apache2 status
```

Jika sudah berjalan, output yang seharusnya adalah sebagai berikut:
![apache-status](img/apache-status.png) <br>

```shell
sudo service apache2 restart
sudo service apache2 stop
sudo service apache2 start
```

| Command | Kegunaan |
| ----- | ----- |
| restart | Digunakan untuk merestart servis apache. |
| stop | Digunakan untuk mematikan servis apache. |
| start | Digunakan untuk menyalakan servis apache. |

Secara default root folder dari Apache berada di ___/var/www/html___. Apache memiliki folder untuk konfigurasi yang berada di ___/etc/apache___. Perlu untuk diketahui:

| Nama File | Pengertian |
| --------- | ---------- |
| **apache2.conf** | file konfigurasi utama apache2. |
| **ports.conf** | file konfigurasi port yang digunakan untuk webserver. |
| **sites-available** | folder tempat konfigurasi website (virtual host) yang tersedia. |
| **sites-enabled** | folder tempat konfigurasi website (virtual host) yang tersedia dan sudah aktif. |
| **mods-available** | folder tempat modul-modul apache2 yang tersedia. |
| **mods-enabled** | folder tempat modul-modul apache2 yang tersedia dan sudah aktif. |

* ***Tentang Command***

| Command | Arti |
| ------- | ------- | 
| a2ensite | Untuk memasukkan atau ENABLE config yang telah dibuat |
| a2dissite | Untuk menonaktifkan atau DISABLE config yang telah dibuat |
| a2enmod | Untuk ENABLE spesifik modul ke dalam konfigurasi apache2 |
| a2dismod | Untuk DISABLE spesifik modul ke dalam konfigurasi apache2 |

__MySQL__<br>
Untuk melihat apakah MySQL sudah berjalan, ketikkan command berikut

```shell
$ sudo service mysql status
```

Jika sudah berjalan, output yang seharusnya adalah sebagai berikut:
![mysql-status](img/mysql-status.png)<br>

```shell
sudo service mysql restart
sudo service mysql stop
sudo service mysql start
```


| Command | Kegunaan |
| ----- | ----- |
| restart | Digunakan untuk merestart servis MySQL. |
| stop | Digunakan untuk mematikan servis MySQL. |
| start | Digunakan untuk menyalakan servis MySQL. |


Untuk masuk ke MySQL command prompt, ketikkan command berikut:

```shell
sudo mysql -u root -p
```

Command di atas berarti kita akan masuk ke MySQL command prompt sebagai root user. Untuk masuk dengan user yang lain, ubah root dengan username yang sesuai. Pengguna akan diminta memasukkan password sesuai usernamenya. 
<br>
Setelah masuk ke MySQL Command Prompt maka tampilannya adalah sebagai berikut:

![mysql-rohana](img/mysql-rohana.png)<br>
Pada contoh di atas maka pengguna masuk sebagai rohana.
Dalam penggunaan MySQL, *command* yang dijalankan disebut sebagai *query* untuk mengeksekusi apa yang ingin kita lakukan terhadap database yang berada pada MySQL tersebut. Beberapa *query* dasar yang biasa digunakan untuk mengakses database, yaitu :
   - `SHOW DATABASES;` untuk melihat database yang terdapat dalam MySQL tersebut.
   - `CREATE DATABASE [nama_database];` untuk membuat database baru.
   - `USE [nama_database]` untuk menggunakan database pada MySQL Server.
   - Gunakan query `CREATE TABLE;` untuk membuat table dalam sebuah database pada MySQL.
      ```sql
         CREATE TABLE Pegawai (
         id int,
         nama varchar(255),
         alamat varchar(255),
         kota varchar(255) );
      ```
   - `SHOW TABLES;` untuk melihat table yang ada pada database tersebut.
   - Gunakan query `INSERT` untuk menambahkan data ke dalam sebuah *table* dalam database sesuai dengan kolom yang tersedia.
      ```sql
         INSERT INTO Pegawai (id, nama, alamat, kota)
         VALUES (001, 'ilham', 'perumahan dosen ITS', 'Surabaya');
      ```
   - `SELECT * FROM [nama_table];` untuk melihat semua isi sebuah table. 
   - `DROP TABLE [nama_table];` untuk menghapus table dari sebuah database. 
   - `DROP DATABASE [nama_database];` untuk menghapus database dari MySQL.
   - `EXIT` untuk keluar dari command prompt MySQL.

__PHP__<br>
Untuk memastikan PHP sudah terinstal, buat file berekstensi php pada root folder apache.
```shell
sudo touch /var/www/html/index.php
```

Buka file yang sudah dibuat dengan menggunakan text editor:
```shell
sudo nano /var/www/html/index.php
```

Kemudian masukkan baris kode berikut:
```php
<?php
   phpinfo();
?>
```

Untuk melihat hasilnya, buka browser dan akses alamat __[IP server]/index.php__.
![php-info](img/php-info.png)<br>

**Note**

Jika halaman belum muncul seperti pada gambar di atas, silakan install library php untuk apache2 web server dengan menjalankan `sudo apt-get install libapache2-mod-php`.

Cara lain untuk mencoba, dapat dicoba dengan memasukkan kode berikut pada file index.php, lalu akses kembali alamat __[IP server]/index.php__ melalui browser laptop masing-masing.

```php
<?php
   echo "Coba PHP di Web Server Apache pada waktu Pelatihan Linux 2019";
?>
```

__Referensi__<br>
+ https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-16-04

### Mengatur SSH Keys
Secure Shell (lebih dikenal sebagai SSH) memungkinkan pengguna untuk melakukan layanan jaringan secara aman pada jaringan yang tidak aman. SSH Keys menyediakan keamanan lebih dibandingkan hanya dengan menggunakan password. Password dapat dipecahkan melalui metode *brute force* sedangkan SSH Keys hampir tidak mungkin dipecahkan hanya dengan *brute force* saja.
SSH Keys menggunakan metode algoritma RSA untuk menghasilkan sebuah pasangan 'kunci'nya, maka SSH Keys juga biasa disebut dengan RSA Key. Sebuah pasangan RSA Key akan terdiri dari ***private key*** (**kunci privat**) dan ***public key*** (**kunci umum**)

#### Membuat Pasangan RSA Key

```shell
$ ssh-keygen -t rsa
```

#### Menyimpan Keys dan Passphrase

**SSH Key**

```shell
Enter file in which to save the key (/home/rohana/.ssh/id_rsa):
```

Tekan enter untuk menyimpan pada home folder pengguna (pada contoh, pengguna di sini adalah rohana)

```shell
Enter passphrase (empty for no passphrase):
```
Di sini kita bisa memilih untuk menggunakan passphrase atau tidak. Dengan menggunakan passphrase tentunya lebih aman namun kita harus memasukkan passphrase kita tiap ingin menggunakan key pair.

Output dari keseluruhan proses:
```
Generating public/private rsa key pair.
Enter file in which to save the key (/home/rohana/.ssh/id_rsa): 
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /home/rohana/.ssh/id_rsa.
Your public key has been saved in /home/rohana/.ssh/id_rsa.pub.
The key fingerprint is:
SHA256:1gT2KTvnPefNIUtUc4z2cTA3hDYgusBvkycazQILA4g rohana@ABIMANYU
The key's randomart image is:
+---[RSA 2048]----+
|+       o. .. =o.|
|E   .  ..o.. + *.|
| o . o .. + . +++|
|  o o = o=   ...=|
|   . o XS.o  .  .|
|      =.++ ..    |
|     .    . oo.. |
|            .+oo.|
|             .. o|
+----[SHA256]-----+

```

#### Copy the Public Key
Salin puclic key dengan menggunakan command `ssh-copy-id`:

```shell
$ ssh-copy-id rohana@10.151.253.118
```

Jangan lupa mengganti username dan IP pada contoh. Sekarang coba untuk login ke user yang sudah memiliki public key kita, kita tidak akan dimintai password. Namun, jika kita sebelumnya memasukkan passphrase maka kita akan diminta memasukkan passphrase tersebut.

#### Cara Melakukan Koneksi dengan Menggunakan SSH
Pada terminal, ketikkan command berikut:

```shell
$ ssh rohana@10.151.253.118
```

| Command | Keterangan |
| ----- | ----- |
| ssh | Command yang digunakan untuk melakukan koneksi remote |
| rohana | Username yang akan diremote |
| 10.151.253.118 | Alamat IP dari perangkat yang akan diremote |

__Koneksi tanpa SSH Key__
![ssh-without-key](img/ssh-wo-key.png)<br>
Tanpa menggunakan SSH Key, kita akan diminta untuk memasukkan password.

__Koneksi dengan SSH Key__
![ssh-with-key1](img/ssh-w-key1.png)<br>
![ssh-with-key2](img/ssh-w-key2.png)<br>
Dengan menggunakan SSH Key, kita tidak diminta untuk memasukkan password dari perangkat yang akan diremote. Namun, karena sebelumnya kita menggunakan passphrase maka passphrase tersebut lah yang harus kita masukkan.

__Referensi__<br>
+ https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys--2
+ Unix and Linux System Administration Handbook Fifth Edition

# Tugas Mandiri

Berikut adalah beberapa latihan yang dapat dilakukan ketika waktu luang untuk menyempurnakan sesi Pelatihan Linux 2019.
1. Menggunakan text editor **nano** untuk menuliskan kesan dan pesan serta kritik dan saran terhadap pelaksanaan Pelatihan Linux 2019 di SMAN 1 KEDUNGWARU Tulungagung.
2. Menampilkan **proses** yang berlangsung pada ubuntu server di Virtualbox menggunakan aplikasi **htop***. (petunjuk : install aplikasi dengan perintah `sudo apt-get install htop`)
3. Membuat user baru bernama **tux** dengan hak akses superuser (*sudoers**) pada ubuntu server di Virtualbox. (petunjuk : sudoers adalah group untuk *superuser*)
4. Mengatur hak akses file untuk user **tux** dengan hanya pemilik file yang dapat membaca, menulis, dan mengeksekusi. (petunjuk : ketentuan `700`)