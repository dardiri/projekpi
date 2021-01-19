# projekpi

Repository ini berisi tentang hasil belajar dari praktik industri. pada project ini kami saling bekerja sama dalam berusaha mengembangkan sesuatu yang dapat berguna untuk kami dan seluruh pihak yang terlibat. terimakasih kepada seluruh pihak yang telah meluangkan waktunya untuk belajar bersama membangun dengan baik. untuk semua developer yang terlibat ciyee developer...

Bastian Arfianto (18050623002)
Risa Amalia (18050623019)
Dardiri Novar Reviansyah (18050623026)


---------------------------- Langkah-langkah Clone Repo -----------------------------------

Pastikan sudah punya github (Buat jika belum)
Pastikan punya akses ke repo karena ini private (Minta pembuat repo jika belum diberi)
Dibagian code ada button berwarna hijau bertuliskan "Code"
Klik button tersebut , lalu salin link.
Buka cmd arahkan ke folder yang kalian mau
ketik git clone "link yang dicopy" (diwindows klik kanan aja nanti langsung terpaste)
Tunggu hingga proses selesai.
Done , buka hasil clone dengan code editor (saran gunakan vscode karena ada terminal).
---------------------------- Langkah-langkah Kontribusi -----------------------------------

Lakukan langkah clone dulu. (WAJIB)

1. Git Push ( Input perubahan dari folder local ke github )
	a. Pastikan kalian sudah melakukan perubahan pada project.
	b. buka cmd pada folder project / terminal jika pakai vscode (ctrl + `)
	c. pertama "git pull origin master" , lakukan di awal berjaga-jaga supaya jika ada commit dari yang lain.
	d. kedua "git add ." ("." artinya all file di project, bisa spesifik nama file. cth : git add inifile.php)
	e. lalu "git commit -m "pesan commit" (Pesan commit itu adalah pesan untuk memberi tahu perubahan apa yang dilakukan)
	f. terakhir "git push origin master" , dan tunggu proses selesai.

2. Git Pull ( Mengambil perubahan yang ada di github ) 
	a. Buka project yang sudah di clone
	b. buka cmd pada folder project / terminal jika pakai vscode (ctrl + `)
	c. lalu ketik "git pull origin master"
	d. Tunggu proses selesai.
    
3. Git Push Branch (Push ke github dengan branch)
    a. git checkout -b feature/namaprojekbagian/namaanda/tglbulantahun
    b. Contoh  : git checkout -b feature/admin/revi/25112020
    c. git add sama seperti biasanya
    d. git commit -m "namaandatglbulantahun isi pesan" , contoh : git commit -m "revi25112020 ini pesan commit"
    e. git push origin nama branch , contoh : git push origin feature/admin/revi/25112020
    f. gunakan -f jika mau push lebih dari 1 kali di branch yang sama , contoh : git push -f origin feature/admin/revi/25112020
    (noted : Selalu buat branch baru setiap ganti hari , jangan hapus branch lama , jangan push dengan branch lama kecuali ada error pada branch lama) 
----------------------- Langkah-langkah Awal Menjalankan Aplikasi --------------------------

1. Buka CMD di drectory project
2. Migrate DB dengan cara ketik "php artisan migrate" dan tekan enter
3. Jalankan seed untuk agama dengan ketik "php artisan db:seed" dan tekan enter
4. Jalankan seed untuk lokasi indonesia dengan ketik "php artisan laravolt:indonesia:seed" dan enter
