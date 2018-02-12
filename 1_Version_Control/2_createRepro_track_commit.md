### Creating a Git Repository and hosting on GitHub

You may create a Git repository from a local directory or  by cloning an exsisting Git repository.


## Existing Directory to Git reprository


Here's an example. First, I will [create a new repository on GitHub](https://help.github.com/articles/creating-a-new-repository/).
I have a project directory on my MAC called Xenostructure that I want to import. On my terminal I will navigate to that directory.

`cd ~/path/to/Xenostructure`


Once inside my directory I will type the `git init` command.

To track the exsisting files in the directory use the `git add .`  command.

You can add your first commit meesage by typing the following: `git commit -m 'commit message'`.

To communicate these changes with Github type the following:

`git remote add origin git@github.com:ltcguthrie/test.git`

`git push -u origin master`

## Cloning an exsisting Git respository

You can clone an exsisting repository using the `git clone <url>` command.

`git remote add origin git@github.com:ltcguthrie/test.git`

