# .bash_prompt
My custom bash prompt with git info and direct jump to Workspaces' folders

----------------------------

bash-completion needs to be installed

Clone this projet into your home directory.

Add this line to the end of your ~/.bashrc
```bash
source ~/.bash_prompt/.bash_prompt
```

reboot your console or execute :
```bash
source ~/.bashrc
```

* Now your console shows the branch name if in a versionned project's folder.
* If the branch name is too long, it truncates it.
* If you have uncommited files, the branch name change from green to orange so you can guess your project status.
* You can change CDPATH to make folder accessible from everywhere by just "cd" directly in, leaving it this way allows you to type a folder's name that ~/Workspaces contains from wherever you are.
