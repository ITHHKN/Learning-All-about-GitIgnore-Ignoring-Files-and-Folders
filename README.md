# Learning-All-about-GitIgnore-Ignoring-Files-and-Folders
Learning All about GitIgnore : Few ways to tell Git which files to ignore.

Create a local .gitignore
If you create a file in your repository and named it .gitignore, Git uses it to determine which files and directories to ignore, before you make a commit.

A .gitignore file should be committed into your repository, in order to share the ignore rules with any other users that clone the repository.

GitHub maintains an official list of recommended .gitignore files for many popular operating systems, environments, platform and languages in the github/gitignore public repository.

In Terminal, navigate to the location of your Git repository.
Enter touch .gitignore to create a .gitignore file.
Create a global .gitignore
You can also create a global .gitignore file on your system, which is a list of rules for ignoring files in every Git repository on your computer. For example, you might create the file at ~/.gitignore_global and add some rules to it.

Open Terminal.
Run the following command in your terminal:
git config — global core.excludesfile ~/.gitignore_global
Explicit repository excludes
If you don’t want to create a .gitignore file to share with others and keep it private, you can create rules that are not committed with the repository

Use your favorite text editor to open the file called .git/info/exclude within the root of your Git repository. Any rule you add here will not be checked in, and will only ignore files for your local repository.

In Terminal, navigate to the location of your Git repository.
Using your favorite text editor, open the file .git/info/exclude.
Collection of .gitignore templates — iOS / Android / PHP
