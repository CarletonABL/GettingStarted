# Getting Started
Start using GitHub repositories from [CarletonABL](https://github.com/CarletonABL) by following this guide. First, get familiar with the command line, git, GitHub and git workflows by following the instructions below. You may also want to [read-up on git](https://www.google.ca/search?q=what+is+git) to find out what it's all about. The website [https://git-scm.com/](https://git-scm.com/) is the official place for downloads and documentation. Follow these steps:

 1. Install git on your computer (Follow the instructions below)
 1. Go through the excellent tryGit online tutorial [here](https://try.github.io)
 1. For single developers, a good primer/tutorial for git can be found [here](https://www.liquidlight.co.uk/blog/article/git-for-beginners-an-overview-and-basic-workflow/).
 2. Follow GitHub's [Hello World](https://guides.github.com/activities/hello-world/) tutorial to get familiar with GitHub.
 2. Send the CarletonABL organization's maintainer an email and provide your GitHub account name to add you as a member. The current maintainer is Kyle.
 3. Install GitHub Desktop (Follow the instructions below).
 4. Clone this repository, make this guide better by changing anything in it, commit the changes, and create a pull request. The maintainer will merge or reject your changes.

## Unfamiliar with the command line? Start Here

It's recommended to install git as a command-line tool. If you're unfamiliar with the command-line interface, get familiar with a [bash shell](https://www.google.ca/search?q=what+is+a+bash+shell) for [Mac](https://www.google.ca/search?q=introduction+to+the+mac+command+line) or [Linux](https://www.google.ca/search?q=introduction+to+the+linux+command+line) and [Powershell](https://www.google.ca/search?q=introduction+to+the+linux+command+line) or [bash (MSYS2)](https://msys2.github.io/) for Windows.

### Setup for Mac

The best way to install and use software on the command-line is with [Macports](https://www.macports.org/) or [Homebrew](http://brew.sh/). It's also recommended to install [iTerm](https://www.iterm2.com/) and use it as your default terminal.

### Setup for Linux

Everything is already setup. Just open your Terminal. [Here's how to get started with Ubuntu](https://help.ubuntu.com/community/UsingTheTerminal).

### Setup for Windows

If you want to use open-sourced, cross-platform, and standards-compliant compilers and software, install [MSYS2](https://msys2.github.io/). For Windows-only tools, use the command line by running cmd.exe or use PowerShell which is already installed on Windows 8. You may also want to additionally install [ConEmu](https://conemu.github.io/) which allows to you have multiple command-line environments open at the same time (including MSYS2 bash shells). It has more features and is much nicer to look at and use compared to the boring Windows Command Line.

## Install git

You can install git many ways for many operating systems. Go [here for installation instructions](https://git-scm.com/book/en/v1/Getting-Started-Installing-Git). Not that a package manager can keep your software updated, ensure dependencies are installed and up to date, and maintain interoperability with other software. It's recommended (and easier) to use a package manager.

The following commands can be used instead of a graphical installer.

### Mac

If you've installed Macports, run

    sudo port install git

If you've installed HomeBrew, run

    brew install git

### Linux

Install git with your distribution's package manager. For example, on Debian-based systems such as Ubuntu, run the command

        sudo apt-get install git
### Windows

If you've using MSYS2, it's package manager is called pacman (adopted from [Arch Linux](https://wiki.archlinux.org/index.php/pacman)). In your bash shell, run

    pacman -S msys/git

### Configure

After installation, on the command line, run

    git config --global user.name "John Doe"
    git config --global user.email johndoe@example.com

Replace name and email with your name and GitHub account email address.

## Install GitHub Desktop

If you're more familiar with graphical interfaces, a great way to start using GitHub is to download (GitHub Desktop)[https://desktop.github.com/] available for Windows or Mac.

Once installed, make sure you sign in to your GitHub account in the Preferences dialog. In the advanced section of the preferences dialog, set your name and email associated with your GitHub account for the Git Config input fields.

More detailed information on installing and setting up GitHub Desktop can be found [here](https://help.github.com/desktop/guides/getting-started/setting-up-github-desktop/).
