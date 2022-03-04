su betty- switches current user
whoami- prints effective username of current user
group-prints all the group the current user is part of
chown name name- changes the owner of the file to the user
touch name- creates an empty file
chmod u+x name- adds execute permission to the owner
chmod ug+x,o+r name- execute permission to the group owner, read permission to the other users
chmod a+x- adds execution permission to the owner, the group owner and the other users to the file
chmod 007 name- gives no permission to the owner, group andd other users
chmod 753 name- sets mode of the file
chmod --reference=olleh name- sets mode of the file to olleh's moood
chmod a+x * _ adds, execute permission to all subdirectories of the current directory for the owner, group owner
mkdir -m 751 my dir- creates a directory named my_dir
chgrp school hello-changes the group owner to school
chown vincent:staff *- change the owner name to staff from school
chown -h vincent:staff _hello- change the group owner to vincent and sstaff
chown --from=guillame name name- changes the owner the file name to another only if it is owned by user guillaume
telnet towel.blinkenlights.nl- To play StarWars IV in the terminal
