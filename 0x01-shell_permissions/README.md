su is a script that switches the current user to another
whoami prints the effective username of the current user
groups prints all the groups the current user is part of
chown changes the owner of the file
touch creates an empty file
chmod u+x adds execute permission to the owner of the file
chmod ug+x,o+r adds execute permission to the owner and the groups owner and read permission for others
chmod +x adds execution permission to the owner group owner and the other users 
chmod 007 sets no permission to owner and group and all the permission to other users
chmod 753 sets -rwxr-x-wx mode
chmod --reference=x sets the mode of a file the same as x
chmod -R +X . adds execute permission to all subdirectories of current directory
mkdir -m 751 dir_name creates a directory with 751 in the permissions
chgrp changes the group owner of a specified file
chown vincent:staff * changes the owner to vincent and group owner to staff
chown -h vincent:staff changes the owner and group owner of a specified file which is a symbolic link
chown --from=guillaume betty changes the owner of the file to betty if owned by guillaume
telnet towel.blinkenlights.nl play starwats IV episode in the terminal