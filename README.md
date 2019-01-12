# ubuntu-termux
This is a script by which you can install Ubuntu in your termux application without rooted phone


Steps
1. Install termux: https://f-droid.org/repo/com.termux_65.apk
2. Update termux: apt-get update && apt-get upgrade -y
3. Install wget: apt-get install wget -y
4. Install proot: apt-get install proot -y
5. Install git: apt-get install git -y
6. Go to HOME folder: cd ~
7. Download script: git clone https://github.com/xintiaoxuanlv/ubuntu-fs.git
8. Go to script folder: cd ubuntu-fs
9. Give execution permission: chmod +x ubuntu.sh
10. Run script: ./ubuntu.sh
11. Fix resolv.conf: cp ~/ubuntu-fs/resolv.conf ~/ubuntu-fs/ubuntu-fs/etc/
12. Now just start ubuntu: ./start.sh
