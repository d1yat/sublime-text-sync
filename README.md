# sublime-text-sync

1. Install Package Control melalui menu `Tools > Install Package Control...`
2. Hapus file `Package Control.sublime-settings` di folder `Packages/User`
3. Jalankan Command Prompt _`(Terminal di Mac/Linux)`_ di folder `Packages/User`
   
   **NOTE:**
   > Folder `Packages/User` mungkin berbeda di tiap sistem operasi
   > 
   > Silakan kunjungi tautan di bawah ini untuk informasi lebih lanjut
   > 
   > https://www.sublimetext.com/docs/revert.html
   
4. Ketikkan perintah berikut di Terminal:

```
git init
git remote add origin https://github.com/d1yat/sublime-text-sync.git
git branch -M main
git pull origin main
git branch -u origin/main main
```

Jika menggunakan Sublime Text 4, buat 2 (dua) buah file di folder `Packages`
- `Default/Side Bar Mount Point.sublime-menu`
- `Default/Side Bar.sublime-menu`

5. Restart Sublime Text
6. Selesai

# Screenshot
![Alt text](screenshot.jpg?raw=true "Sublime Text")
