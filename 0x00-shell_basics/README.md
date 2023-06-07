pwd will show the current working directory absolute path
ls will display the contents list of the current directory
cd ~ will change the working directory to the user's home directory
ls -l will display the current directory contents in a long format
ls -la will display current directory contents, including hidden files
ls -na will display current directory contents with
  Long format
  with user and group IDs displayed numerically
  And hidden files
mkdir tmp/my_first_directory will create my_first_directory inside /tmp/ directory
mv /tmp/betty /tmp/my_first_directory moves the file betty from /tmp/ to /tmp/my_first_directory
rm /tmp/my_first_directory will remove the file betty frommy_first_directory which is inside /tmp/
rmdir /tmp/my_first_directory will delete the directory  my_first_directory 
cd - will change the working directory to the previous one
ls -al . .. /boot will list all files in the current directory, the parent directory and the /boot directory in long format
file /tmp/iamafile will display the type of the file named iamafile inside  the /tmp/ directory
ln -s /bin/ls __ls__ creates a symbolic link to /bin/ls named __ls__ in the current working directory

cp -rua *.html ../  copies all html files from the current directory to the parent directory.
mv [[:upper:]]* /tmp/u moves all files beginning with an uppercase letter to the dorectory /tmp/u