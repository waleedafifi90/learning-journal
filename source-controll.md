[< Back to home](https://waleedafifi90.github.io/learning-journal/)

# Source Control

## Introduction

### Version Control
Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.

### So, what is Git?
1. Snapshots
2. Local Operations
3. Tracking Changes
4. Loss of Data
5. States
    * Committed
    * Modified


### Getting Started

**Download Git**

1. Install as a package
2. Install via another installer
3. Download and compile the source code.


#### Mac OS X

_Terminal_

The simplest method for installing Git on a Mac (for Mavericks 10.9 and above) is running Git from the Terminal. If Git is not installed, you will see a prompt for installation.

#### Windows

_Git Website_

You can download Git by visiting this link and following the posted directions:
[Download from here](http://git-scm.com/download/win)

#### Linux

_Package Manager_

You can try installing Git via your distribution’s inherent package management tool.
```
$ sudo apt-get install git
```


## Git Command

**For cloning repo you need to use the net line in you terminat**
```
$ git clone https://github.com/test
```

**Check status of you repo**
```
$ git status
```

**Tracking and Staging a New File**

* Single File

```
git add filename
```

After adding a new file called EXAMPLE, you would see information regarding changes to be committed when using the git status command:

```
$ git status

On branch master

Changes to be committed:

  (use "git reset HEAD ..." to unstage)
```

**Committing a File**
```
$ git commit -m “made change x,y,z”
```

**Pushing Changes**
```
$ git push origin master
```

## Seeing Your Remotes

By running the git remote command, you can view the short names, such as “origin,” of all specified remote handles.

By using git remote -v, you can view all the remote URLs next to their corresponding short names.

```
$ cd example

$ git remote -v

remote1 https://github.com/remote1/example (fetch)

remote1 https://github.com/remote1/example (push)

remote2 https://github.com/remote2/example (fetch)

remote2 https://github.com/remote2/example (push)

remote3 https://github.com/remote3/example (fetch)

remote3 https://github.com/remote3/example (push)
```