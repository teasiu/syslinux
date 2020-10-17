# syslinux 6.04


<br>git clone git://git.kernel.org/pub/scm/boot/syslinux/syslinux.git
<br>sudo apt-get install perl uuid-dev nasm git mingw-w64 make gcc python libc6-dev-i386
<br>cd syslinux
<br>make
<br>make bios
<br>sudo make netinstall
<br>then found the netboot files in /tftp

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>…or create a new repository on the command line
<br>echo "# syslinux" >> README.md
<br>git init
<br>git add README.md
<br>git commit -m "first commit"
<br>git branch -M main
<br>git remote add origin git@github.com:teasiu/syslinux.git
<br>git push -u origin main
                
<br>…or push an existing repository from the command line
<br>git remote add origin git@github.com:teasiu/syslinux.git
<br>git branch -M main
<br>git push -u origin main
