# GIT

- [downloads](https://git-scm.com/downloads)
- [start-using-git](https://docs.gitlab.com/ee/gitlab-basics/start-using-git.html)
- [using-git-with-ssh-keys](https://kamarada.github.io/en/2019/07/14/using-git-with-ssh-keys)
- [setting-up-ssh-and-git-on-windows-10-2khk](https://dev.to/bdbch/setting-up-ssh-and-git-on-windows-10-2khk)

-------

```  
git --version
git version 2.28.0.windows.1
```
-----
``` 
git config --global --list

git config --global user.name "Web Dev"
git config --global user.email "tom2kota@gmail.com"
```

-----

``` 
git init 
git remote add origin git@github.com:tom2kota/git.git
git remote add origin https://github.com/tom2kota/git.git
git remote -v

git add .
git commit -m "Initial commit"
git push -u origin master
```

---
## SSH

``` 
ssh -V
ssh-keygen -t rsa -b 4096 -C "tom2kota@gmail.com"

    Generating public/private rsa key pair.
    Enter file in which to save the key (C:\Users\javad/.ssh/id_rsa): tom
    Search for Services and open the Services settings and look for the "OpenSSH Authentication Agent" and Activate it
     
ssh-add tom
```

``` 
type C:\Users\javad\.ssh\id_rsa.pub
```

copy public key & add to GitHub account