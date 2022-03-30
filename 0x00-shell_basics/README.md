pwd -Prints the current working directory
ls - List contents of a specified directory
cd - change working directory to home
ls -l List directory contents in long format
ls -la List all directory contents including then hidden in long format
ls -lna Display current directory contents.

Long format
with user and group IDs displayed numerically
mkdir /tmp/my_first_directory
Create a script that creates a directory named my_first_directory in the /tmp/ directory.
mv /tmp/betty /tmp/my_first_directory/betty
Move the file betty from /tmp/ to /tmp/my_first_directory.
rm /tmp/my_first_directory/betty
Delete the file betty. The file betty is in /tmp/my_first_directory
rmdir /tmp/my_first_directory
Delete the directory my_first_directory that is in the /tmp directory.
cd -
a script that changes the working directory to the previous one.
ls -la . .. /boot
a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
file /tmp/iamafile
a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory
ln -s /bin/ls _ls_
Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
cp -nu *.html ..
Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

You can consider that all HTML files have the extension .html
