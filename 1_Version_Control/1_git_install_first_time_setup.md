## Installing Git

You may have git already installed. Check at the terminal.

`git --version`  


Install on Mac by following the instructions at this [link](https://git-scm.com/download/mac).



To start we will setup up our Git configuration values using the command `git config`. You have the option to setup parameters at the level of a specific project (local), for a operating system user (global) or for all users on a machine (system). We are going to congifure Git at the global level and will provide the following information:

* name
* email
* editor

### Name

`git config --global user.name "Your Name"`

### Email

`git config --global user.email youremail@example.edu`

### Editor

`git config --global core.editor emacs` 


You can check your all your settings using the `git config --list` command or a specif value.

`git config user.name` 


## Other useful commands

`git help <git command verb>`

`man git-<git command verb>`


### Sharing your work with others

You can use a hosting service like Github to store your Git repositories and share them pubically. You can sign up for an account [here](https://github.com/).
We will use github going forward but there are other options like [BitBucket](https://bitbucket.org/), [Codebase](https://www.codebasehq.com/) or [GitLab](https://about.gitlab.com/). 