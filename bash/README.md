# Customizing your bash prompt

I keep all of my settings archived in a git repo located at 
https://github.com/iamasteriix/dotfiles. This ensures that I can easily keep all of my settings
consistent between all of the computers that I use.
It also lets me share my settings with you :)

Three files are especially significant here:

1. The `.git-prompt.sh` file has tools for working with git,
1. The `.bashrc` file has settings for your bash shell, and
1. The `.dircolors` file has my current preferred colors for the console.

You can use `curl` and redirect with `>` to download them as follows:
```
curl https://raw.githubusercontent.com/iamasteriix/dotfiles/tree/master/bash/.git-prompt.sh > .git-prompt.sh
curl https://raw.githubusercontent.com/iamasteriix/dotfiles/tree/master/bash/.bashrc        > .bashrc
curl https://raw.githubusercontent.com/iamasteriix/dotfiles/tree/master/bash/.dircolors     > .dircolors
```
Then logout and login again (or run the shortcut, `source ~/.profile`) for the changes to take 
effect.
You know your changes worked if your command prompt is now green.

### Credits
- Special thanks to Prof. [Mike Izbicki](https://github.com/mikeizbicki) from whom I 'borrowed'
most of these customizations, and who has been an invaluable inspiration to my programming career.
Check out this class that I took with him, [Big Data](https://www.youtube.com/watch?v=N-N8SOfgVSA&list=PLSNWQVdrBwoYKJ50dHmLCqd0hVdUZbWEv), over Spring 2022.