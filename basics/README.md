STEP 0 : Write a script that prints the absolute path name of the current working directory with « pwd » command

STEP 1 : Display the contents list of your current directory with « ls » command.

STEP 2 : Write a script that changes the working directory to the user’s home directory with « cd /root » command

STEP 3 : Display current directory contents in a long format with « ls -l » command

STEP 4 : Display current directory contents, including hidden files (starting with .). Use the long format with « ls -a -l » command

STEP 5 : Display current directory contents.
* Long format
* with user and group IDs displayed numerically
* And hidden files (starting with .) 
with « ls -l -a -n » command

STEP 6 : Create a script that creates a directory named my_first_directory in the /tmp/ directory with « mkdir /tmp/my_first_directory » command

STEP 7 : Move the file betty from /tmp/ to /tmp/my_first_directory with « mv /tmp/betty /tmp/my_first_directory » command

STEP 8 : Delete the file betty.
* The file betty is in /tmp/my_first_directory
with « rm -r /tmp/my_first_directory/betty » command

STEP 9 : Delete the directory my_first_directory that is in the /tmp directory with « rmdir  /tmp/my_first_directory »

STEP 10 : Write a script that changes the working directory to the previous one with « cd - » command

STEP 11 : Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format with « ls -la . .. /boot » command

STEP 12 : Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script with « file /tmp/iamafile » command

STEP 13 : Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory with « ln -s /bin/ls __ls__ » command

STEP 14 : Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory with « cp -n *.html .. » command

STEP 15 : Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u with « mv [A-Z]* /tmp/u » command

STEP 16 : Create a script that deletes all files in the current working directory that end with the character ~ with « rm -r *.*~ » command

STEP 17 : Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory with « mkdir -p welcome/to/school » command
