# day 2

Permissions
rwx(421)
read,write,execute
chmod 754 filename 
umask 
default umask value 022 that means if the file is created it has rw-r-r
for normal file base permision is 666 then umask 022 is reduced then the file has 644  rw-r-r
for the directory base permision is 777 then umask 022 is reduced then the file has 755 rwxr-xr-x
to create shell script file use .sh extention
then create a script start with  #!/bin/bash
#!/bin/bash
echo"hello"
to run the script chmod +x filename.sh and then ./ filename.sh


