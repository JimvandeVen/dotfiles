# Dotfiles

Hey there, My name is Jim van de Ven. Here you will find my personal cofigurations for my tools that i will be using for development. 
## Contents

In these dotfiles you can find my .bashrc, .gitignore and .editorconfig. 
.bashrc contains my personal preferences like aliases and the prompt tweaks.

The .gitignore file contains the ability to ensure that certain files not tracked by Git remain untracked. To stop tracking a file that is currently tracked, use `git rm --cached`. For more information go to [gitignore](https://git-scm.com/docs/gitignore). 

Also I have the .editorconfig file, which makes for a solid editor interface. Go to [Editorconfig](http://editorconfig.org/) for more information.

## Installation
The .gitignore and .editorconfig can be directly placed inside the root of your working directory.

Installation of a .bashrc to customize your terminal:

1. Start up Terminal.
2. Run `cd ~` to go to your home folder.
3. Run `touch .bashrc` to create your new file.
4. Edit .bashrc with your editor.
5. Copy my .bashrc into your .bashrc.
6. Restart your terminal.
7. Enjoy it!

## npm

npm is necessary to install cowsay command. To install npm go to your cd ~ directory and run `apt npm install`. This will take a few moments.

## Cowsay

To install cowsay go to the cd ~ directory and run `npm install -g cowsay`.