[< Back to home](https://waleedafifi90.github.io/learning-journal/)

![](https://kinsta.com/wp-content/uploads/2019/03/notepad-plus-plus-text-editor-1-1.png)

# How to choose a text editor

There are a lot of text editor can be installed and used in your machine I will mention some of them

## What is text editor?

A text editor is a piece of software that you download and install on your computer, or you access online through your web browser, that allows you to write and manage text, especially the text that you write to build a web site. The text editor has to be one of the most important tools you can use as an aspiring web developer.

_Text editor came with you OS_

there is an application came within you OS called **Notepad** this editor can be used to edit or write your text and it can be used to write development code for some programming languages

## Third-Party Options
Application design by special company to make you coding life easier and better see the list blow show some application that can be used

1. Visual Studio Code
2. Notepad++
3. Atom
4. Sublime Text

![](https://miro.medium.com/max/1200/0*MyAfggJM7yH40Sdx.)
## The Difference Between TextEditors and IDEs
A _text editor_ kind of gives away what it does in the title—it edits text. It also manages text, and manages files. I love that name “text wrangler” because in a way that’s what really a text editor does. Itwrangles your text together into something meaningful

An _IDE_ (Integrated Development Environment) is really a suite of different software all coming together. An IDE is a text editor, a file manager, a compiler, and a debugger all in one software package.

**I would advice you tu use. Visual studio code**
Visual Studio Code is a free text editor made by the folks at Microsoft. It is available for Windows computers, Mac computers and Linux computers. VS Code has the Emmet shorthand for HTML and CSS already built-in with no additional work from you at all. VS Code has everything: syntax highlighting, themes, extensions and code completion. It seems like VS Code has a very healthy following in the web developing community.
![](https://upload.wikimedia.org/wikipedia/commons/9/9a/Visual_Studio_Code_1.35_icon.svg)


# Terminal CheatSheet
Terminal is very important for every developer so here you can find some instruction to use **terminal** or **command line**

### Command line
![](https://img-a.udemycdn.com/course/750x422/2458052_451f_7.jpg)

A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.

**How to open Terminal or Command line**

If you're on a __Mac__ then you'll find the program Terminal under Applications -> Utilities. An easy way to get to it is the key combination 'command + space' which will bring up Spotlight, then start typing Terminal and it will soon show up.

If on __Linux__ then you will probably find it in Applications -> System or Applications -> Utilities. Alternatively you may be able to 'right-click' on the desktop and there may be an option 'Open in terminal'.

If on __Windows__ Press Windows+X to open the Power Users menu, and then click “Command Prompt” or “Command Prompt (Admin).”


_Example - How to use terminal_
```diff
user@bash: ls -l /home/ryan
total 3
drwxr-xr-x  2 ryan users 4096 Mar 23 13:34 bin
drwxr-xr-x 18 ryan users 4096 Feb 17 09:12 Documents
drwxr-xr-x  2 ryan users 4096 May 05 17:25 public_html
user@bash:
```

1. Line 1 presents us with a prompt ( `user@bash` ). After that we entered a command ( `ls` ).
2. After that we have what are referred to as command line arguments ( `-l /home/ryan` ). Important to note, these are separated by spaces (there must be a space between the command and the first command line argument also). 
3. The first command line argument ( `-l` ) is also referred to as an option. Options are usually listed before other arguments and typically start with a dash ( `-` ).
4. Lines 2 - 5 are output from running the command. 

### Basic Navigation!
__Where are we?__

You can find where are you now by using `pwd` in your terminal as below
```
user@bash: pwd
/home/ryan
user@bash:
```
__What's in Our Current Location?__
```
user@bash: ls
bin Documents public_html
user@bash:
```

__This table show some of trminal shortcut__

| Shortcut      | Use                     |
| ------------- |:-----------------------:|
| pwd           | Print Working Directory |
| ls            | List file in directory  |
| cd ..         | One step back           |
| mkdir         | Make new Directory      |

# More About Files!
### Everything is a File

Ok, the first thing we need to appreciate with linux is that under the hood, everything is actually a file. A text file is a file, a directory is a file, your keyboard is a file (one that the system reads from only), your monitor is a file (one that the system writes to only) etc. To begin with, this won't affect what we do too much but keep it in mind as it helps with understanding the behaviour of Linux as we manage files and directories.

### Linux is an Extensionless System

1. file.exe - an executable file, or program.
1. file.txt - a plain text file.
1. file.png, file.gif, file.jpg - an image.

### Linux is Case Sensitive
This is very important and a common source of problems for people new to Linux. Other systems such as Windows are case insensitive when it comes to referring to files. Linux is not like this. As such it is possible to have two or more files and directories with the same name but letters of different case.

```
user@bash: ls Documents
FILE1.txt File1.txt file1.TXT
user@bash: file Documents/file1.txt
Documents/file1.txt: ERROR: cannot open 'file1.txt' (No such file or directory)
```

#### Summary
1. file
    1. obtain information about what type of file a file or directory is.
2. ls -a
    1. List the contents of a directory, including hidden files.
3. Everything is a file under Linux
    1. Even directories.
4. Linux is an extensionless system
    1. Files can have any extension they like or none at all.
5. Linux is case sensitive
    1. Beware of silly typos.
