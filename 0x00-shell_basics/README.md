Creating some scripts on shell

"0-current_working_directory" prints the absolute path name of the current working directory

"1-listit" display the contents list of your current directory

"2-bring_me_home" changes the working directory to the user's directory

"3-listfiles" display current directory contents in a long format

"4-listmorefiles" display current directory contents, including hidden files starting with . and using the long format

"5-listfilesdigitonly" display current directory contents, using the long format, with user and group IDs displayed numerically and including hidden files starting with .

"6-firstdirectory" creates a directory named holberton in the /tmp/ directory

"7-movethatfile" move the file betty from /tmp/ to /tmp/holberton

"8-firstdelete" delete the file betty that is in /tmp/holberton directory

"9-firstdirdeletion" delete the directory holberton that is in the /tmp directory

"10-back" changes the working directory to the previous one

"11-lists" lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format

"12-file_type" prints the type of the file named iamafile (the file iamafile will be in the /tmp directory when we will run your script)

"13-symbolic_link" create a symbolic link to /bin/ls, named __ls__ (the symbolic link should be created in the current working directory)

"14-copy_html" create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory (all HTML files have the extension .html)

"15-lets_move" create a script that moves all files beginning with an uppercase letter to the directory /tmp/u (the directory /tmp/u will exist when we will run your script)

"16-clean_emacs" create a script that deletes all files in the current working directory that end with the character ~

"17-tree" create a script that creates the directories welcome/, welcome/to/ and welcome/to/holberton in the current directory (only allowed to use two spaces (and lines) in your script, not more)

"18-commas" write a command that lists all the files and directories of the current directory, separated by commas (,) (directory names should end with a slash (/), files and directories starting with a dot (.) should be listed, the listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning, only digits and letters are used to sort, digits should come first, all the files we will test with will have at least one letter or one digit, the listing should end with a new line)

"holberton.mgc" create a magic file holberton.mgc that can be used with the command file to detect Holberton data files. Holberton data files always contain the string HOLBERTON at offset 0 (holberton.mgc has to be created on Ubuntu 14.04 LTS)
