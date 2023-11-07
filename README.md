# sublime-text-sync
1. Install Package Control melalui menu `Tools > Install Package Control`
2. Jalankan Terminal _`(Mac/Linux: SHELL, Windows: Command Prompt)`_ di folder `Packages/User`
   
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
git branch -m main
git pull
git branch -u origin/main main
```
4. Restart Sublime Text
5. Selesai
