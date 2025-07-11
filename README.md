## Guide add large files

``` shell
> git init
> sudo apt install git-lfs
> git lfs install
> git lfs track "*.exe"
> git add .
> git commit -m "add vscode installer"
> git branch -M main
> git remote add origin https://github.com/hungcuongm98i/windows_installer.git
> git push -u origin main
```
