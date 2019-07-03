#git-create
Git plugin script to initialize a directory with readme.md and a license.

##Install
Copy git-create file to your bin folder and make sure it is executable.
Copy templates folder to your bin bin folder.

##Usage
Open the terminal in the directory you want to initialize as a git directory,
and run the command `git create`. 

Try `git create --help` for more usage info.

##Licenses
Use `git create -l <license>` to use a specific license.
To add a license, create a file in the templates directory with the license.
This license can then be used with `git create -l <file_name>`.