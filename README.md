# project-
Pertama tama download and install git 
clone repo dengan command "git clone https://github.com/naufalnawwafabdurrazaq-alt/project-.git"
git pull origin "nama branch"(digunakan untuk mengambil file dari github)
git push origin "nama branch"(digunakan untuk mengirim  file ke github)

catatan sebelum push
1. git add . untuk menandai file yang berubah
2. git commit -m "nama pesan"
3. baru lakukan push

jika 
fatal: Unable to create 'C:/xampp/htdocs/project-/.git/index.lock': File exists.

Another git process seems to be running in this repository, e.g.
an editor opened by 'git commit'. Please make sure all processes
are terminated then try again. If it still fails, a git process
may have crashed in this repository earlier:
remove the file manually to continue.

solusi
del .git\index.lock