Assignment 2 : Git Ignore and .gitignore
When sharing your code with others, there are often files or parts of your project, you do not want to share.
Examples
log files
temporary files
hidden files
personal files
create a github repo, name it gitignore cheatsheet, create an gitignore_cheatesheet.md file. Inside the file list rules for matching patters in .gitignore files.
Solution.
Pattern	Explanation	Example

*.log	Ignores all files with the extension ".log"
To ignore a specific file, simply list its name in the .gitignore file. For example, to ignore a file named "logfile.txt", add the following line to the .gitignore file:
logfile.txt
	
error.log,
 debug.log

.hidden/	
Ignores the entire directory named ".hidden"
	
.hidden/

/tmp/*	
Ignores all files and directories in the "/tmp" directory	
/tmp/file.txt,
 /tmp/dir/

personal.txt	
Ignores the file named "personal.txt"	
personal.txt

