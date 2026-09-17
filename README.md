**Use GitHub as your Cloud Storage provider!**

Recommendation: Make your repo **private**.

Download the shell or batch scripts and put them in your folder, or use `git clone https://github.com/iamdominic2/Github_Drive`. <BR>
You will need to run `INIT.sh` or `INIT.bat` once, and `CLONE.sh` or `CLONE.bat` whenever you have a new computer that does not have your cloud files yet.<br>
Use `PUSH.sh` or `PUSH.bat` to upload your files to GitHub, and `PULL.sh` or `PULL.bat` to get back your files from GitHub.

Advantages:
* Totally viewable and revertible version history in case your cat types all over your homework
* Ransomware protection at no cost - just use `git reset --hard ######` (replace ###### with your latest functional commit hash)
* Local file storage - convenient if you rely on modern utilities like Notepad++.
* No "read-on-file-lock" conflicts or disasters!
* Totally free for life for files under 100MB!

Disadvantages:
* Owned by Microslop!
* Cannot push more than 2GB at once!
* Storage size per repository is 10GB - however, this can be circumvented by making as many repos as you want.
* Video files likely would not fit without LFS nonsense.
