pwd- print working directory
ls- Display the contents list of your current directory
cd- Change working directory to home
ls -l - Display current directory contents in long format
ls -la - Display current directory contents, including hidden files (starting with .)
ls -na - Display current directory contents. Long format, with user and group IDs displayed numerically and Hidden files (statrting with .)
mkdir /tmp/my_first_directory - Create a script that can create a directory
mv /tmp/betty /tmp/my_first_directory - Move file betty from /tmp/ to /tmp/my_first_directory
rm /tmp/my_first_directory/betty - Delete the file betty
rmdir /tmp/my_first_director -Delete the directory
cd - Changes the working directory back to the previous one
ls -la . .. /boot - Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
file /tmp/iamafile - prints the type of file
ln -s /bin/ls __ls__ - Create symbolic link 
