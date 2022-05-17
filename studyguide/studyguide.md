### Study Guide For Final Spring 2022 
#### List of Commands

* date 
Display the current time and date.
![q1.1](q1.1.png)

* uname
Displays information about your system.

* du

* free
Displays the amount of free memory.
![q4.1](q4.1.png)
echo
* apt
for advanced package tool- is set of tools for managing Debian packages.
![q5.1](q5.1.png)
![q5.2](q5.2.png)

* pwd 
Displays the current working directory where you are currently working.
* Example:![q6.1](q6.1.png)

* cd
![q7](q7.1.png)
change the current working directory. in other words, moves you around.
How to use it : cd + destination 

* ls 
is used for listing the content of a given directory or the file directory itself.
Example:![q8.1](q8.1.png)
![q8.2](q8.2.png)

* tree
* man
Man manual  pages are documentation files that describe Linux shell commands, executable programs, systems,calls,special files,and so forth.
man pages are not step by step guides ,but instead quick reference
*Example: ![q10](q10.1.png)
![q10.2](q10.2.png)

* mkdir 
is used for creating a single directory or multiple directories.
* Example:
![q11.1](q11.1.png)

* touch
is used for creating files 
![q12.1](q12.1.png)

* rm
remove files 
rm by default does not removes directories.T o remove a directory use rm with the -r option.
* Example 
![q13.1](q13.1.png)

* cp
copies files/directories from
source to a destination 
the cp command uses the same structure as the mv command 
![q14.1](q14.1.png)

* mv
moves and renames directories.
* Example 
![q15](q15.1.png)

* stat
a data structure that contains all the information about a file except the file name and content.
* Example 
stat script.sh 

* Wildcards (*,?,[])
the main wildcard is a star ,or asterisk(*) character.
A star alone matches anything and nothing and matches any number of characters
* Example  ls *.txt wil match all files that end in txt regardless of the size of the file name .
![q16](q16.1.png)

* Brace expansion
{} is not a wildcard but another feature of bash that allows you to generate 
rabbitry string to use with commands.
* Example 
![q18.1](q18.1.png)

* cat
the cat command is use for displaying the content of a file .
cat is short for concatenate which is the command intended.
* Usage 
cat + option +file(s) to display
* Example 
![q19](q19.1.png )

* head
the head command displays the top N number of lines of a given file by default it prints the first 10 line  If more than one file name is provided then data from each file is proceeded by its file name.
* Example 
![q20](q20.1.png)

* tail
the head command displays the top N number of lines of a given file by default it prints the first 10 line  If more than one file name is provided then data from each file is proceeded by its file name.
* Example 
![q20.1](q20.1.png)

* cut
the / etc/passwd contains one lne for each user account, with seven fields delimited by colons(:)
* Example 
![q21.1](q21.1.png)

* tr 
used for translating or deleting or characters from standard output.
* Example
![q22](q22.1.png)

* paste
is use for joining files horizontally in columns 
* Example 
![q23](q23.1.png)

* wc
the wc is used for printing the number of lines characters and bytes in a file.
![q24](q24.1.png)

* grep 
is used to search text in given file. grep works line by line basis.
* Usage 
grep + option search criteria + file(s)
![q25](q25.1.png)

* output redirection
![q26](q26.1)

Saving the output of a command
command output + > +file
![q26.2](q26.2.png)

vim or nano (basic stuff: open a file, close a file, edit a file)
![q27](q27.1.png)
![q27](q27.2.png)
![q27](q27.3.png)

tar
![q28.1](q28.1.png)
![q28](q28.2.png)

gz, bzip2, or xz
chmod