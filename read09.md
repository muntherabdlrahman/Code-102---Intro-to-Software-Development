#  Text Editor/Notepad

![img](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT6BpJBVACx-ChEq46Ax5-gtMRI5n3LPHArbQ&usqp=CAU.jpg)
> you can’t say that you’ve found an absolute favorite text editor yet, but choosing a text editor
ends up being a very personal choice, as personal as the sports teams you support.



 *Don’t think that it truly matters as to which text editor you use. Yes, some text editing software comes with features that other text editing software does not. But for the most part, they’re all pretty similar.*


 *While you can search on Google for the “best” text editor for coding
(and Google will definitely tell you)*.

 ###### I think the best text editor istruly the one that you enjoy using the most. That’s really the best one, isn’t it?

 ***What is a text editor?***

#### *A text editor is a piece of software that you download and install onyour computer, or you access online through your web browser, that allows you to write and manage text, especially the text that you write to build a web site. The text editor has to be one of the most important tools you can use as an aspiring web developer.*


#### What features should you look for in a text editor?

1|code completion
-|-
2|syntax highlighting
3|a nice variety of themes
4|the ability to choose from a healthy selection of extensions available when you need them


*A great feature of any text editing software is code completion. Code completion allows you to start typing, and the code completion feature will display possible suggestions based on what you originally typed. This saves you time by providing a choice, rather than allowing you to finish typing and possibly encounter typos.*

*Another nice feature  is being able to write your HTML and CSS more efficiently. There is a kind of shorthand language called ***Emmet*** that can help. Emmet will speed up your code writing faster than you can imagine. Some text editors come with Emmet built right in, or Emmet can be added by the means of an extension.*


*Another feature you should definitely look into is called ***syntax highlighting***. Syntax highlighting is a feature that takes the text you type, and makes it more noticeable by colorizing the text. Attributes are a different color than elements. And elements are a different color than copy. This makes it so much easier when you’re looking for an error and you can’t find it. As well as making your text easier to read*


#### Using The Software That Already Comes With Your Computer
###### Now that we’ve talked about some of the features one might be interested in if they were interested in a text editor. Let’s talk about some of your options—beginning with the software that comes on your computer. Every computer will come with its own text editor. On Mac computers, the text editor that comes with your computer is called, “Text Edit.” On Windows computers, the text editor that comes with your computer is called, “Notepad.



#### NotePad++

![kkk](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRqYpbjWsCC1tABK7QwJtrwhBvpi4dzGuDZLA&usqp=CAU.jpg)

*NotePad++ is a free text editor for Windows Computers only.
NotePad++ has been around for many years and many web developers swear by NotePad++. It has syntax highlighting and code completion, as well as word completion and function completion. It has a zoom in an out feature, it’s own online community, and its own chat room for questions that may arise. It even has its own searchable wiki page for more assistance*
### Atom
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQWh4WXf0at4JLMUosP-Np7auhUg8KUhlJCJGaKJNkG4vZApvmCPlO31gACNcLyNW9dRCU&usqp=CAU.jpg)

Atom is a free text editor that’s available for download for Windows
computers, Mac computers and Linux computers. Atom is brought to
you by the folks at GitHub . GitHub is a great service online where
you can host and review code, or you can post and get help with the
development of your own projects. Atom also ticks all the right boxes.
It has syntax highlighting, themes, extensions, the works! Atom is
definitely a software to check out and test drive for yourself.



#### The Difference Between Text Editors and IDEs

#### ***Text editor*** kind of gives away what it does in the title—it edits text. It also manages text, and manages files. I love that name “textwrangler” because in a way that’s what really a text editor does. Itwrangles your text together into something meaningful.

#### ***IDE*** (Integrated Development Environment) is really a suite of different software all coming together. An IDE is a text editor, a file manager, a compiler, and a debugger all in one software package.

--------------------------------------------------------


# The Command Line!
*Your window into the computer*

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRcqSbtJ_HfebtovzGdK3GYasSKCdmUhluCdg&usqp=CAU.jpg)

###### Linux has a graphical user interface and it works pretty much like the GUI's on other systems that you are familiar with such as Windows and OSX. This tutorial won't focus on these as I reckon you can probably figure that part out by yourself. This tutorial will focus instead on the command line (also known as a terminal) running Bash.

###### A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.

### Opening a terminal

###### Opening a terminal is fairly easy. I can't tell you exactly how to do it as every system is different but here are a few places to start looking.

###### If you're on a Mac then you'll find the program Terminal under Applications -> Utilities. An easy way to get to it is the key combination 'command + space' which will bring up Spotlight, then start typing Terminal and it will soon show up. If on Linux then you will probably find it in Applications -> System or Applications -> Utilities. Alternatively you may be able to 'right-click' on the desktop and there may be an option 'Open in terminal'. If you are on Windows and intend to remotely log into another machine then you will need an SSH client. A rather good one is Putty (free) .

### The Shell, Bash
###### Within a terminal you have what is known as a shell. This is a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you. There are various shells available but the most common one is called bash which stands for Bourne again shell. This tutorial will assume you are using bash as your shell. If you would like to know which shell you are using you may use a command called echo to display a system variable stating your current shell. echo is a command which is used to display messages.


### Shortcuts
###### The terminal may seem daunting but don't fret. Linux is full of shortcuts to help make your life easier. You'll be introduced to several of them throughout this tutorial. Take note of them as not only do they make your life easier, they often also save you from making silly mistakes such as typos.


--------------------------------------------------------------

# Basic Navigation!
*Let's explore the system*

>After the previous section I'm sure you're keen and eager to get stuck into some more commands and start doing some actual playing about with the system. We will get to that shortly but first we need to cover some theory so that when we do start playing with the system you can fully understand why it is behaving the way it is and how you can take the commands you learn even further. That is what this section and the next intend to do. After that it will start getting interesting, I promise.


### Everything is a File
*Ok, the first thing we need to appreciate with linux is that under the hood, everything is actually a file. A text file is a file, a directory is a file, your keyboard is a file (one that the system reads from only), your monitor is a file (one that the system writes to only) etc. To begin with, this won't affect what we do too much but keep it in mind as it helps with understanding the behaviour of Linux as we manage files and directories.* 

### Linux is an Extensionless System
*This one can sometimes be hard to get your head around but as you work through the sections it will start to make more sense. A file extension is normally a set of 2 - 4 characters after a full stop at the end of a file, which denotes what type of file it is. The following are common extensions:*

* file.exe - an executable file, or program.
* file.txt - a plain text file.
* file.png, file.gif, file.jpg - an image.

###### In other systems such as Windows the extension is important and the system uses it to determine what type of file it is. Under Linux the system actually ignores the extension and looks inside the file to determine what type of file it is. So for instance I could have a file myself.png which is a picture of me. I could rename the file to myself.txt or just myself and Linux would still happily treat the file as an image file. As such it can sometimes be hard to know for certain what type of file a particular file is. Luckily there is a command called file which we can use to find this out.


### Spaces in names
>Spaces in file and directory names are perfectly valid but we need to be a little careful with them. As you would remember, a space on the command line is how we seperate items. They are how we know what is the program name and can identify each command line argument. If we wanted to move into a directory called Holiday Photos for example the following would not work.


