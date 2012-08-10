redrum
======

Directory structure
===================
/js - contains all javascript files for this project
/pages - holds the html
/css - holds the stylesheets

Basic 'bash' commands
=====================
bash is a shell. basically, a command line interface to your OS.
'%' is used in documentation to denote the shell prompt. yours may vary.

cd - change directory 
example: %cd ..   (goes to the parent directory)

common usages: %cd     (goes to your home(~) directory)
			   %cd [some directory name]
			   %cd ../[some directory in the parent directory]

ls - show the contents of the current directory
example %ls -la  (shows the contents of the current directory in long format with permissions and file sizes)

common usages: %ls -la  (long format)
			   %ls -laF (^^ + shows directories denoted with a '/')
			   %ls -H  (gives human readable file sizes kb,mb, etc.)
the '-la' part above is usually called arguements or options. the minus sign is a specifier. the letters tell the program that runs to do certain things.
all of these shell commands are actually small programs. 

pwd - show me which directory i'm in.

mkdir - the command to make a directory in the current directory (assuming you have permission)

specify a name after typing mkdir and it'll make that folder. directories are basically folders.

eg %mkdir workspace   - makes a 'workspace' folder in the current folder

rm - remove a file


============
git commands
============
%git pull origin master    (this pulls from the repo)
%git                pull                      origin                          master
  ^git program      ^command you wnat to run   ^ the remote origin. github.    ^ the branch name


 