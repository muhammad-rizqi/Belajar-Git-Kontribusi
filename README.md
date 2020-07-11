# Belajar-Git-Kontribusi

## Workflow:
1. Open github : https://github.com/
2. Fork repository yang ingin akan dilakukan Clone, Commit, Push, Pull, Pull Request 
3. Buat folder baru di windows kalian untuk penyimpanan repository githubyang akan di clone
4. Lakukan clone dengan cara buka githbash dan masuk ke folder yang dibuat tadi kemudian getikkan "git clone link_github"
5. Tambahkan file/folder atau buat perubahan di folder yang baru saja di clone
6. Push ke githab, agar perubahan yang ada di windows bisa terupload di github, caranya :
- a. buka terminal
- b. ketikkan "git add ."
- c. git status (untuk mengecek apakah ada perubahan"
- d. git commit -m "komen terserah"
- e. git push origin master
- f. Kembali ke github kemudian reload dan liat perubahan yang terjadi 
7. Setelah data di push, kemudian lakukan pull request untuk mendapat izin bahwa data yang dipull akan di simpan di repository yang di fork tadi
8. Selesai

## Mengabil Perubahan Repository Induk
### Metode Fetch
1. git remote add upstream https://github.com/gilamran/tsc-watch.git -> link github repository induk
2. git fetch upstream
3. git merge upstream/nama_branch

### Metode Pull
