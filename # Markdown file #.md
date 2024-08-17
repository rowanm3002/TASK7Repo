# Markdown file #

# Linux Command Practice 
1. pwd 
```bash```
rowan@rowan-HP-ProBook-4540s:~/Desktop$ pwd
/home/rowan/Desktop
2. ls
```bash```
rowan@rowan-HP-ProBook-4540s:~/Desktop$ ls
M.I.A  projects  test  traning25
3. cd
```bash```
rowan@rowan-HP-ProBook-4540s:~/Desktop$ cd M.I.A
rowan@rowan-HP-ProBook-4540s:~/Desktop/M.I.A$ ls
rowan@rowan-HP-ProBook-4540s:~/Desktop/M.I.A$ cd ..
rowan@rowan-HP-ProBook-4540s:~/Desktop$ cd projects
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects$ ls
hello  helloworld  hi  new  new~  task8
4. rm
```bash```
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects$ rm new
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects$ ls
hello  helloworld  hi  new~  task8
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects$ cd task8
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects/task8$ ls
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects/task8$ 
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects/task8$ cd..
cd..: command not found
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects/task8$ cd ..
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects$ cd hi
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects/hi$ ls
pdf
5. cat
```bash```
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects/hi$ cat pdf
rowan
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects/hi$ rm pdf
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects/hi$ ls
6. mkdir 
```bash```
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects/hi$ mkdir vip
7. nano
```bash```
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects/hi$ nano vip
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects/hi$ cat vip
cat: vip: Is a directory
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects/hi$ ls
vip  vipX
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects/hi$ cat vipX
hello from teminal 
8. cp 
```bash```
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects/hi$ cp vipX copy
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects/hi$ cat copy
hello from teminal 

rowan@rowan-HP-ProBook-4540s:~/Desktop/projects/hi$ ls
copy  vip  vipX
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects/hi$ cd desktop
bash: cd: desktop: No such file or directory
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects/hi$ cd ..
rowan@rowan-HP-ProBook-4540s:~/Desktop/projects$ cd ..
rowan@rowan-HP-ProBook-4540s:~/Desktop$ pwd
/home/rowan/Desktop
rowan@rowan-HP-ProBook-4540s:~/Desktop$ ls
M.I.A  projects  test  traning25
rowan@rowan-HP-ProBook-4540s:~/Desktop$ cd test
rowan@rowan-HP-ProBook-4540s:~/Desktop/test$ ls
kkk
9. mv
```bash```
rowan@rowan-HP-ProBook-4540s:~/Desktop/test$ mv kkk txt
rowan@rowan-HP-ProBook-4540s:~/Desktop/test$ ls
txt
rowan@rowan-HP-ProBook-4540s:~/Desktop/test$ cat txt
try

