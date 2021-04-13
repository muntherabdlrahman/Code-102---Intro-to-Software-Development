
# *Git Tutorial: A Comprehensive Guide*
## Version Control
##### Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.
![img](https://kevintshoemaker.github.io/StatsChats/GIT1.png)

## Distributed Version Control
##### A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure. If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions. Also, in the event of corruption of a central database’s hard disk — with the absence of backups — all work will be lost, except for any portions on local machines.

##### To prevent this type of catastrophic loss, a DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.

##### Because the DVCS allows for multiple mirrored repositories, programmers working in teams can collaborate with each other in various ways to complete a joint project, which enables the use of various simultaneous workflows.



## So, what is Git?
##### we will talk about this objects to now more about Git.
NO|objects
--|----
1|Snapshots
2|Local Operations
3|Tracking Changes
4|Loss of Data
5|States






### Snapshots
▶️
##### Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

### Local Operations
▶️
##### Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.

### Tracking Changes
▶️
##### Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.

### Loss of Data
▶️
##### Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

### States

##### Files in Git can reside in three main states: committed, modified and staged.

- Committed
 - modified  
##### Data is securely stored in a local database.

##### File has been changed but not committed to the database.

### Staged

##### Flagged a file’s changed version to be committed in the next snapshot
![img](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)


### History of Git
##### Git traces its roots to the open source software project Linux kernel. Developers of this project began using a DVCS called BitKeeper in 2002. In 2005, many of these developers stopped using this DVCS due to tension between the Linux kernel community and the company behind BitKeeper’s and the eventual revocation of the DVCS’ gratis status. Subsequently, Linus Torvalds, the chief architect of the Linux kernel, began creating Git. With the intention of creating a DVCS with a workflow design similar to that of BitKeeper, which was also fast, Git allowed for non-linear development via multiple branches, could support large projects, possessed strong mechanisms preventing corruption, and had a simple design. Since its inception in 2005, Git has become one of the most utilized Version Control Systems in the world.


### Git can be installed in three ways:

➡️Install as a package
➡️Install via another installer
➡️Download and compile the source code

##### Windows


You can download Git by visiting this link and following the posted directions:

[here](http://git-scm.com/download/win)

GitHub

Install Git as part of the GitHub for Windows install.

[here](windows.github.com)


### Customization
##### fter king sure Git has been installed, you should perform some customization steps, which should only need to be completed once on any machine.To change settings, you can repeat these steps.
### configration of Variables
#####  inherent Git tool called git config allows the setting of configuration variables that control aspects of Git’s operation and look.

##### identity editting
##### afterinstalling Git, users should immediately set the user name and email address, which will be used for every Git commit.
Type the following into Terminal or Command Line:
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
git config --global user.name "Jane Smith"

git config --global user.email "example@email.com"
To confirm that you have the correct settings, enter the following command:

git config --global user.name (should return Jane Smith)

git config --global user.email (should return example@email.com)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
### using the globl option, these Git settings apply to anything on the system.To use different identity settings for a specific project, change the working directory to the desired local Git repository and repeat the steps above without using –global.

### Default Text Editor
##### Without configuration of a default text editor, Git will use the system’s default editor–most likely Vim. To configure a different text editor, such as Emacs, type the following into your Terminal or Command Line:

$ git config --global core.editor emacs




>Note: For some editors, you may need to find specific instructions for default configuration.

### Check Settings
##### settings, use the git config --list command.

> Example:
````````````````````
$ git config --list

user.name=Jane Smith

user.email=example@email.com

color.status=auto

color.branch=auto

color.interactive=auto
````````````````````

### Getting Help
##### There are three ways to get more information on a particular command, by accessing the manual:

- [X] git help command
- [ ] git command --help
- [ ] man git-command


> This informations were taken from
![img](https://blog.udemy.com/wp-content/themes/udemyblog/img/udemy-logo.svg)
[udemy](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#18)




