## installa guide

### check if git is installed
```bash
 git 
 
```
### generate public and private key
```bash
 ssh-keygen
 
cat .ssh/id_rsa.pub
```
copy the public key in github 

### clone example

open a terminale
```bash
git clone git@github.com:kotdavid/Stata-do-file.git
cd Stata-do-file/
git status
git commit -am "first commit"
git push

```