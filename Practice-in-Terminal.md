# Practice in Termanial 

## [Bash Command Line Tutorials](https://ryanstutorials.net/linuxtutorial/)

### [The Command Line](https://ryanstutorials.net/linuxtutorial/commandline.php)

* A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text

* The command line typically presents you with a prompt. As you type, it will be displayed after the prompt. Most of the time you will be issuing commands

* Options are usually listed before other arguments and typically start with a dash ( - )

* (for me) If you're on a Mac then you'll find the program Terminal under Applications -> Utilities. An easy way to get to it is the key combination 'command + space' which will bring up Spotlight, then start typing Terminal and it will soon show up.

* shell-part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you

* bash- most common shell which stands for, 'Bourne Again Shell'

* Shortcuts-entered commands are stored in your history.  using the up and down keys you can select from your history, you can also edit by using the left/right keys to move the cursor.

### [Basic Navigation](https://ryanstutorials.net/linuxtutorial/navigation.php)

* PWD-(pwd) Print Working directory, shows current working directory
* LS-(ls) short for list, shows whats in the directory
* (-l) long listing
* (-) normal file (d) directory
* (/etc) tells (ls) not to list current directory but to list that directory's contents
* 2 types of paths: *absolute*-A file or directory location relative to where we currently are in the file system and *relative*-A file or directory location in relation to the root of the file system
* (tidle) shortcut to home directory
* (dot) reference to current directory
* (dotdot) reference to parent directory
* Tab completion auto complete action

### [More About Files](https://ryanstutorials.net/linuxtutorial/aboutfiles.php)

* types of extentions: .exe(executable), .txt(plain text), .png .gif .jpg(image)
* Linux is case sesitive
* use quotes ('') for file names with spaces
* backslash ( \ ) escape (or nullify) the special meaning of the next character

### [Manual Pages](https://ryanstutorials.net/linuxtutorial/manual.php)

* manual pages are a set of pages that explain every command available on your system including what they do, the specifics of how you run them and what command line arguments they accept
* invoke command by : man `<command to look up>`
* search withing manual pages by : man -k`<search term>`
* list all directory entries (including hidden files) we can use the option `-a` or `--all`

### [File Manipulation](https://ryanstutorials.net/linuxtutorial/filemanipulation.php)

* to make a directory `mkdir [options] <Directory>`
* examples of options to make a directory `mkdir /home/ryan/foo
mkdir ./blah
mkdir ../dir1
mkdir ~/linuxtutorialwork/dir2`
* `-p` which tells mkdir to make parent directories as needed
* `-v` which makes mkdir tell us what it is doing
* remove directory `rmdir [options] <Directory>`
* creating a blank file `touch [options] <filename>`
* to copy file or directory `cp [options] <source> <destination>`
* move file or directory `mv [options] <source> <destination>`
* rename file or directory: specify the destination to be the same directory as the source, but with a different name using the `mv` option
* remove file and non empty directory `rm [options] <file>`

### [Cheat Sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)

* link to the cheat sheet above, as well in my notes
