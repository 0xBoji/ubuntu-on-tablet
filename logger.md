/config.yaml                                                                  bash: vim: command not found                                                  root@localhost:~/code-server-4.22.1-linux-arm64/bin# cd ~/.config/code-server root@localhost:~/.config/code-server# vim config.yaml                         bash: vim: command not found



try 'termux-change-repo' command.

Report issues at https://termux.dev/issues
~ $ ./start-ubuntu.sh
root@localhost:~# wget https://download.cursor.sh/linux-arm64/cursor.tar.gz
--2024-11-23 11:23:01--  https://download.cursor.sh/linux-arm64/cursor.tar.gz
Resolving download.cursor.sh (download.cursor.sh)... 104.21.75.173, 172.67.179.179, 2606:4700:3031::6815:4bad, ...
Connecting to download.cursor.sh (download.cursor.sh)|104.21.75.173|:443... connected.
OpenSSL: error:0A000410:SSL routines::sslv3 alert handshake failure
Unable to establish SSL connection.
root@localhost:~#


root@localhost:~# apt update
Hit:1 http://ports.ubuntu.com/ubuntu-ports jammy InRelease
Hit:2 http://ports.ubuntu.com/ubuntu-ports jammy-backports InRelease
Hit:3 http://ports.ubuntu.com/ubuntu-ports jammy-proposed InRelease
Hit:4 http://ports.ubuntu.com/ubuntu-ports jammy-security InRelease
Hit:5 http://ports.ubuntu.com/ubuntu-ports jammy-updates InRelease
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
All packages are up to date.
root@localhost:~# apt install ca-certificates -y
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
ca-certificates is already the newest version (20240203~22.04.1).
0 upgraded, 0 newly installed, 0 to remove and 0 not upgraded.
root@localhost:~# update-ca-certificates
Updating certificates in /etc/ssl/certs...
0 added, 0 removed; done.
Running hooks in /etc/ca-certificates/update.d...
done.
root@localhost:~# wget https://download.cursor.sh/linux-arm64/cursor.tar.gz
--2024-11-23 11:25:35--  https://download.cursor.sh/linux-arm64/cursor.tar.gz
Resolving download.cursor.sh (download.cursor.sh)... 172.67.179.179, 104.21.75.173, 2606:4700:3037::ac43:b3b3, ...
Connecting to download.cursor.sh (download.cursor.sh)|172.67.179.179|:443... connected.
OpenSSL: error:0A000410:SSL routines::sslv3 alert handshake failure
Unable to establish SSL connection.
root@localhost:~#