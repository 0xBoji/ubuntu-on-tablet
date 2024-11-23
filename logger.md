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