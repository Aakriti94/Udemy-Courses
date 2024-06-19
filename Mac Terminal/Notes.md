MAC Terminal

**Commands Used in this course:**
```
Whoami, pwd, ls, ls -a, date, echo, cd, clear, cat, touch, nano, mv, mkdir, cp, rm, *, cp -R, >, >>, sudo, chown, chgrp, chmod, pipe command, find, grep, alias, variables, read, which, expansion variable $(), unix login file, cal , clear, history, man

Environment Variables: USER, HOME, PATH
```

**Shortcuts:**
- `Ctrl + L` - Clear the screen 
- `Alt key`- the mouse icon changes and we can click wherever we want to 
- `Ctrl + a` - start of the line 
- `Ctrl + e` - End of the line 
- `Ctrl + K` - Cut the line 
- `Ctrl + Y` - Paste the line 
- Drag and drop the path in terminal to copy the full path 
- `Cmd + K` - clear screen 
- `N` - next entry 
- `Shift + N` - Back entry 

<br> </br>

- `say “hello there”` - make the computer say things 
- `Killall WhatsApp` - kills that particular command 
- `cal 01 2023` - calendar of January  

<br> </br>

- `ls -F`
- `file finename` - give you meta-deta of the file  
- `history 5` - last 5 commands
- `nano -m` : enables the miouse option for nano
- `sudo bash` - Launch a new shell as root user 
- find something inside a folder: `find foldername/ -name aaa.txt` 
- Find everything inside a folder: `find foldername/`
- Look for only fodler: `find newfodler/ -type d`
- Look for only file: `find newfodler/ -type f`
- Make grep insensitive: `grep -i`
- Everything exdept that word: `grep -v`

<br> </br>

- Alias: `.profile`
- Add colors to make files and fodler different: `export CLICOlOR="YES"`
- `source .profile` - run to it to make the changes done in `.profile` file 
- `alias lf="ls -lhaF"` -> run the source comand after it 

<br> </br>

**`Variables`:**
- `myvar=456`
- `echo "$myvar"`
- `unset myvar` - unset the value of the variable 
- Also acts as a command: `mycommand=ls` -> `$mycommand` -> acts as `ls`
- `$()`
- `d=$(ls)` - store teh output of ls in variable d
- `echo $d` 

**`Read`:**
- `read myvalue` -> prompts to write soemthing 
- `echo $myvalue`
- `read -p` "type your age" age
- `echo $age` -> whatever you have typed 
- Dont want to show what you are writing: `read -s password` 

**Executable Files:**

- `./executableFile `-> `./` this only shows the locationof teh executable file 
- If you are up one folder the command will be like: `../executableFile`
- `/absoulte/path/executableFile` -> It will run 
- `./` is not a execuatbel command 

**`Which`:**
- `which ls` - see the location of `ls` comamnd
- `which bash`

**`Bin`**
- `/bin/` - only accessible from terminal 
- `open /bin/` - see it in UI


**`Unix Login File:`**
- login script - `.profile` or `.bashrc `or `.bash_profile` or `.login`
- Make oermanet variable declarations and alsias 
<br> 
- `More` - starts from the beginning of the file 
- `Less` - don’t go back to terminal 
- `open Filename` - open any files - in desktop mode - also opens folders 
    - `:: xdg-open` - if working in linux





`ls` all files whcih start with `P` charccter: 

permissions: owners, group, others
@ and +