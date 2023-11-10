# sublime-text-sync
1. Install Package Control melalui menu `Tools > Install Package Control...`
2. Jalankan Terminal _`(Mac/Linux: SHELL, Windows: Command Prompt)`_ di folder `Packages/User`
   
   **NOTE:**
   > Folder `Packages/User` mungkin berbeda di tiap sistem operasi
   > 
   > Silakan kunjungi tautan di bawah ini untuk informasi lebih lanjut
   > 
   > https://www.sublimetext.com/docs/revert.html
   
4. Ketikkan perintah berikut di Terminal:
```
rm -f Package\ Control.sublime-settings
git init
git remote add origin https://github.com/d1yat/sublime-text-sync.git
git branch -M main
git pull origin main
git branch -u origin/main main
```
Jika menggunakan Sublime Text 4, buat 2 (dua) buah file di `Preferences > Browse Packages`
- `Default/Side Bar Mount Point.sublime-menu`
- `Default/Side Bar.sublime-menu`
4. Restart Sublime Text
5. Selesai

# Screenshot
![Alt text](screenshot.jpg?raw=true "Sublime Text")
