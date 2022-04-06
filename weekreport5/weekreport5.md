# week report 5

# Definition, usage, and example of the following commands:
# mkdir:
Is used for creating directory or multiple directories.

### Example:
* create a directory in the present working directory 
`mkdir wallpapers`
* create directory a in a different directory using relative path 
mkdir wallpapers/ocean
* create a directory in a diffident directory using absolute path 
`mkdir ~/wallpapers/forest`
* create a directory with a space in the name 
`mkdir wallpapers/new\care`
`mkdir wallpapers/"cities usa"`
* create a directory with a single quote in the name 
`mkdir wallpapers/"majora 's mask"`
* create multiple directories 
`mkdir wallpapers /care wallpapers/cities wallpapers/forst`
* create a directory with a parent directory at the same time 
`mkdir -p wallpapers_others/movies`

## touch:
is used for creating files 

### Examples 
* to create a file called list 
`touch list` 
* to create several files
`touch list_of_cars.txt script.py names.csv`
* to create a file using absolute path 
`touch ~/Downloads/games.txt`
* to create a file using relative path (assuming you `pwd is you home directory )`
`touch ~/Downloads/games2.txt` 
* to create a file with a space in its name 
`touch "list of foods.txt`

## rm 
`removes files`
### Examples
* remove a file 
`rm list`
* remove a file and prompt confirmation before removal
`rm -i list` 
* remove all the files inside a directory and ask before removing more then 3 files 
`rm -I Downloads/games/*`


## rmdir
to remove empty directories 
### Example
* remove an empty directory 
`rmdir Downloads/games`
* remove an non-empty directory 

## mv 
moves and rename directories.
### Example
* to move a file a directory to anther using relative path
`mv Downloads/homework.pdf Documents/`
* to move a directory from one directory to another combining absolute path 
`sudo mv ~/Downloads/theme /usr/share/themes`
* to move a file from one directory to another `combining absolute path and relative path 
mv Downloads/english_homework.docx /media/student/flashdrive/`
* to move multiple directories/files to a different directory 
`mv games/ wallpapers/ rockmusic/ /media/student/flashdrive/`

## cp 
copies files/directory from a source to a destination
the cp command uses the same structure as the mv command
### Example
* to copy a file 
`cp Downloads/wallpapers.zip pictures/`
* to copy a directory with absolute path 
`cp -r ~/Downloads/wallpaper /pictures/`
* to copy the content of a directory to another directory 
`cp Downloads/wallpaper/* ~/pictures/`
* to copy multiple files in a single command 
`sudo cp -r script.sh program.py home.html assets/ /var/www/html/`

## ln 
A data structure that contains all the information about a file except the file name and its content 
### Example
* to create a hard link: ln file `~/Downloads/fileHL`
* to create a symbolic link: `ln ~s file fileSL`
 
## man 
Man (manual)pages are documentation files that describe Linux shell commands, executable programs, system calls,special files,and so forth.
### Example
* open the man page of the passwd command 
`man passwd`
* open the specific man page for the passwd command 
`man 5 passwd` 
* show the man page section of the passwd command 
`man -f passwd` 
* show all the available paged of a command 
`man -a passwd` 
* searches for a man page for a given word or regular expression or phrase 
`man -k file `
