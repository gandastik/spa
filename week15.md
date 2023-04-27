## Linux Fundamentals
### History
- Denis Ritchie, Richard Stallman -> Free Software Foundation
- Linus Torvalds -> wrote POSIX compliant kernel -> GNU Linux kernel

### Distributions
- red hat
- ubuntu
- debian
- other
![](https://media.discordapp.net/attachments/1014398974649708624/1098440622404292719/image.png)

### Installing Linux

#### Storage Management
- partitioning disk and such

### Man Page
- manual page contains all the details, options, examples of the commands😎

### Directories
- pwd: print working directory
- cd: change dir
- absolute paths & relative paths
	- **absolute path**: begins with "slash /" (should use everytime when you are a SPA)
	- relative paths not begins with "slash /"
- path completion (tab)
- ls: list all file in current dir
- mkdir: create new dir
- rmdir: remove specifies dir

### Files
- "everything is a file" **file are case sensitive**
- file: utility to determine "file type"
- touch: make new file
- rm: remove file
- cp: copy file
- mv: move file (cut)
- rename: use mv to rename file

### File Contents
- head: display first ten lines of file
- tail: display last ten lines of file
- cat: display the content of file
- tac: cat backwards 😕
- more and less: displaying file that take up more than one screen (less is more preferable)
- strings: display reable ascii strings found in (binary)

### Linux file tree
- file system hiearchy standard
- man hier
- root dir /
- binary dir
- config dir
- data dir
- in memory dir
- /usr Unix System Resources
- /var variable data

### Commands and Arguments
#### shell variables
- $PATH: determine where the shell are looking for the commands to execute
- env: exported variables

### shell history
- !! -> repeat the last command
- history: see older commands
- ctrl+r: search in history
- $HISTSIZE: determine the number of commands that will be remembered
- $HISTFILE: default is ~./bash_history

### file globbing (ออกสอบบแบบง่ายๆ)
- เน้นการจัดกลุ่มของไฟล์
- `*` asterisk: matching the asterisk the **any combination of characters (even none)**
- `?` question mark: macthing the question mark with **exactly one character**
- `[]` square brackets: matching any of the characters between `[` and the first subsequent `]`

## Pipes and Commands
### I/O redirection
- why need redirection ? -> old days doesnt have clipboard
- `>` : stdout
- `>>` : append
- `|` : pipes
- `<` : stdin
- `<<` : here document
- `<<<` : here strings

### Filter
- cat
- tee
- grep
- cut
- tr: translate characters
- wc: coutning words, lines and characters
- sort
- uniq: remove duplicates from a **sorted list**
- comm: comparing streams (or files)
- od: show the contents of the file in hexadecimals bytes
- sed: stream editor **sed**

### basic Unix tools
- find
- locate
- date
- cal
- sleep
- time
- gzip: compress data cause storage is a resource that are priceful
- zcat: view file that are comrpessed with gzip

### Regex
- เน้นการหา pattern ของ string ใน file

## Vi 😎 🤝 🗿

