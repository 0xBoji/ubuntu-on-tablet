# ubuntu-on-tablet
Termux Github: https://github.com/termux/termux-app/releases

** Commands I've Used in order: **

termux-setup-storage

pkg update && pkg upgrade -y

** OPTIONAL STEP. DO THIS IF pkg update fails **
termux-change-repo

pkg install wget &&. vim -y

** BELOW IS AN OPEN-SOURCE SCRIPT THAT DOWNLOADS AND INSTALLS UBUNTU ON TERMUX **
pkg install wget openssl-tool proot -y && hash -r && wget https://raw.githubusercontent.com/EXALAB/AnLinux-Resources/master/Scripts/Installer/Ubuntu/ubuntu.sh && bash ubuntu.sh

./start-ubuntu.sh

apt update && apt upgrade -y

** DOWNLOAD Code-Server v4.22.1 **
wget https://github.com/coder/code-server/releases/download/v4.22.1/code-server-4.22.1-linux-arm64.tar.gz

tar -xvf code-server-4.22.1-linux-arm64.tar.gz

cd code-server-4.22.1-linux-arm64

cd bin

cd ~/.config/code-server

vim config.yaml

** Once you update the password hit ESC then :wq to save the changes **

** OPTIONAL STEP. You can use the cat command to make sure your edit was successful **
cat config.yaml

cd ~/code-server-4.22.1-linux-arm64/bin

./code-server

** OPTIONAL STEPS: bash config to make your life easier **

exit

pkg install vim

vim ~/.bashrc

** HIT the letter "I" on the keyboard to enter input mode on vim **
./start-ubuntu.sh
** Once you update the password hit ESC then :wq to save the changes **

apt install vim

vim ~/.bashrc

** HIT the letter "I" on the keyboard to enter input mode on vim **
cd code-server-4.22.1-linux-arm64/bin/
** Once you update the password hit ESC then :wq to save the changes **


** PSA: WHEN YOU EXIT TERMUX, IT WILL CONTINUE TO RUN IN THE BACKGROUND STILL. SO MAKE SURE TO CHECK BACKGROUND APPS ONCE YOU'RE DONE USING TERMUX AND SHUT IT DOWN COMPLETELY **
