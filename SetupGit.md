# GIT Install
- [Download Git] (https://git-scm.com/downloads) sesuai sistem oprasi 
![Next](/img/install-git-2)
- klik installer yang telah di download dan klik 
next

![Tunggu proses selesai](tree/master/img/proses-git.png)
- setelah instalasi selesai ikuti langkah ini untuk mangguankan git

<hr> 

# Cara Menggunakan GIT

** Langkah 1: ** Buat Folder di mana saja di PC Anda.

** Langkah 2: ** Buka Folder itu dan klik kanan di dalamnya.

** Langkah 3: ** Anda akan mendapatkan opsi `` Git Bash here```. Klik di atasnya. Anda akan melihat prompt baris perintah.

Sekarang ikuti perintah di bawah ini:

```
$ git config --global user.name "Your Name"
$ git config --global user.email "Your_email@Example.com"
$ git status
```

Perintah di bawah ini akan menampilkan semua file dan Folder

```
$ git add --all
```

Now check the status ```git status``` The new file: <file> will be shown in green color i.e the files are staged.

Now Commit the files
```
$ git commit -m "install git"
```
<hr>

## Create a New Repository
Login to GitHub and click on the ``` + ``` on the top right of browser. select New Repository.

![New Repository](https://help.github.com/assets/images/help/repository/repo-create.png)

Enter Repositroy Name

![Repo Name](https://help.github.com/assets/images/help/repository/create-repository-owner.png)

Select Public or Private as per your requirement. 

Jika Anda ingin menginisialisasi repositori ini dengan README, klik pada kotak centang lain lewati dan klik ``` Buat Repositori ```
Asumsikan bahwa nama repositori Anda adalah ** Technical-Writer ** dan nama pengguna adalah ** Deni-Ardiansyah **

![Repository](https://swcarpentry.github.io/git-novice/fig/github-create-repo-03.png)

Congo! you have successfully created a new repository named planets.

# Make a connection between local repository to GitHub repository 
Use below command with your own username.
```
$ git remote add origin https://github.com/usename/Technical-Writer.git
```
