## Basic Bash Commands
| Command | Description | Examples |
|---|---|---|
| echo | repeats input back to the user on the screen. Commonly used to send info to the user in a script | `echo 'Good morning!'` returns "Good morning!" at the CLI|
| ls | lists the contents of a directory can be given options to view permissions, hidden files , etc | `ls -al /home` lists contents of /home in a (-l) long format including hidden files (-a) |
| pwd | displays the current working directory you are in | `pwd` returns the path of your current working Directory |
| cd | changes your current working directory | `cd /var/log` changes directory to /var/log `cd ..` moves up 1 directory |
| touch | updates timestamp on existing file, but can also create an empty file  | `touch file1` updates timestamp on file1 or creates a file named file1 |
| cp | copies a file or directory to another location | `cp file1 file2` copies the contents of file1 to file2 |
| mkdir | creates a directory | `mkdir newdir` creats a new directory calles newdir |


## File Viewing Commands
| Command | Description | Examples |
|---|---|---|
| cat | used to view the contents of a file without the option to edit. | `cat file1` read file1 to the CLI |
| less | command is used to view the contents of a file when those contents won't entirely fit onto the screen. uses pageup & pagedown | `less file1` would break up the file into pages into the CLI |


## File Editing Commands
| Command | Description | Examples |
|---|---|---|
| vim | starts a powerful and default linux editor | 1. `vim file1` to open a text file in CLI <br/> 2.press i to enter inster mode <br/> 3. press ESC to leave insert mode <br/> 4.:wq to save and quit |
| nano | simple user friendly text editor | 1. `nano file1` <br/> 2. enter text <br/> 3. CTRL+O to write out changes <br/> 4. CTRL+X to quit |
| gedit | gui text editor | GUI application |

## Power management
| Command | Description |
|---|---|
| shutdown | shuts down the computer|
| -h now | shuts down the system with no delay|
| -h -t 90 | shuts down after 90 seconds |
| -r now | reboots system with no delay
| reboot | works the same as `shutdown -r now` | 
