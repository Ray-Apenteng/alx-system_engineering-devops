This repository contains certain basic commands in shell nabvigation

pwd - prints the working directory

ls - Display the contents list of your current directory

cd - change to home directory

ls -l - displays content lists of your current directory in long format

ls -al - lists all files including hidden files in your current directory in a long format

ls -aln - Display current directory contents in long format with user and group IDs displayed numerically and hidden files (starting with .)

mkdir /tmp/my_first_directory  - Create a script that creates a directory named my_first_directory in the /tmp/ directory

mv /tmp/betty  /tmp/my_first_directory - Move the file betty from /tmp/ to /tmp/my_first_directory

rm /tmp/my_first_directory/betty - Delete the file betty

rm -r /tmp/my_first_directory - Delete the directory my_first_directory that is in the /tmp directory

cd - - Write a script that changes the working directory to the previous one

ls -a -l . .. /boot - Write a script that lists all files

file /tmp/iamafile - Write a script that prints the type of the file named iamafile

ln -s /bin/ls __ls__ - Create a symbolic link to /bin/ls, named __ls__

cp *.html ../  -  Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory

mv [[:upper:]]* /tmp/u - Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.You can assume that the directory /tmp/u will exist when we will run your script

rm *~ - Create a script that deletes all files in the current working directory that end with the character ~

mkdir -p welcome/to/school - Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.You are only allowed to use two spaces (and lines) in your script, not more

ls -amp - Write a command that lists all the files and directories of the current directory, separated by commas


