# ha
This is the readme file for the sample ha directory in my chiggiwigi GITHUB account.
5 free github repositories for students with a .edu email address. 
initiallize GIT via:
 >git config --global user.name "Vlad Dracula"
 >git config --global user.email "Vlad@tran.sylvan.ia"
 >git config --global color.vi "auto"
 >git config --global core.editor "vim"

I must initialize a folder before GIT knows to track a directory.
 >git init

If i type "ls -a" i will see that there is a '.git' file

'git status' tells me what GIT is doing, what changes i've made,

how do i stop tracking a folder?
'rm -r .git' for the directory to drop

saving a file in GIT consists of two parts:
1) 'git add <filename>' which puts the file in the staging area
2) 'git commit <filename>' saves the version of the file FOREVER!
2a) I could choose to include a message detailing what was changed about the file via 'git commit -m "Did a change to the file mars.txt"'

vim pluto.txt #add 
git status
git add pluto.txt 
git commit pluto.txt 
git push origin master
