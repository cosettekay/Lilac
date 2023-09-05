#scp : copies files to and from the CPP Unix System
 + -r : to copy an entire directory

#tmux  : generates several windows and panes
+ tmux attach : to reattach to an existing session

#ls : to list the files in the current working directory
+ -a : lists all files including hidden files
+ -F : adds a character to certain files and directories so you can tell which is which
	+ / = directory
	* * = executable
	* @ = symbolic link/pointer to a file
* -l : provides a long listing of the contents

#touch : creates a file that does not exist or updates the timestamp of a file

#less : views content one screenful at a time
+ also searches for a substring

#cat : output the contents
+ -n: places line numbers in front of each line
+ required parameter is the name of the files

#tac : displays file in reverse order (last line first)
+ does not have -n switch

#man : provides a documentation of particular commands
+ -f : to see which sections a command or function resides in

#mkdir : make a directory
+ -p : creates a full path of directories

#cd : changes a directory
+ #pwd : returns an absolute path
	+ .. = back up one level of the hierarchy
	+ . = "here" or "this directory" - the current working directory
	+ ~ = current user's home directory
	+ - = the most recent directory you were in
+ #cd with no directory (absolute or relative) takes you to your home directory

#tree : displays the file hierarchy starting with either: the directory you are in or specify
+ can take either absolute or relative paths

#echo : takes one or more strings to output
+ -n : to suppress the printing of the newline character
+ -e : to interpret escaped characters
	+ Hello \n World = (L1) Hello  (L2) World

#chmod : to change a file's permissions
+ takes 2 arguments: the octal perms and the file name (or glob)

#cp : copies a file from one location to another
+ takes 2 parameters: source file and destination file
+ file globs

#mv : moves files from one location to another
+ takes 2 parameters: source file and destination file
+ file globs
+ renames files too

#rm : deletes files
+ -i : gets user verification
+ file globs BUT BE CAREFUL


