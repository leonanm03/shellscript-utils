This command helps changing tab terminal tab name, to make easier to know in wich directory you are executing other commands.



## How to install:

1 - Download "tabname" file.

2 - Open linux terminal in the folder where you made the download.

3 - Copy tabname to "/usr/local/bin/" directory:
```
sudo cp tabname /usr/local/bin/
```

4 - Make tabname executable:
```
sudo chmod +x /usr/local/bin/tabname
```
5 - close terminal and done.

Now you can run the command "tabname" in terminal to change the name of tab tab wich you are using.

## How to use

example:
```
tabname MyNewTab
```

NOTE: if you want to change for one with spacebars, you'll need to use quotes

example:
```
tabname "my new tab"
```

#### This command just changes the name of the current tab wich you are using in the linux terminal, after you close the terminal, the tabs will switch back to "Terminal" name.
