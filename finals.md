disclaimer: most of this shit is just a rant that I picked up when prof. is talking in class 🤷🏻‍♂️ so don't expect much of this shit will be useful in the exams

## week2

### computer has many user
- prerequisites: OS, ComOrg

### SPA: System Platform Admins
- learning to become HIGHER class of USER 😯
- 🤓 as a spa "you need to know the in-and-out of the computer or the machine that you moderate, in order for you to be able to undesrtand deeply and be able to find a way to upgrade or maintain the machine in the best possible way possible"

### History Lesson
- "Prince of Persia": a really really old game has some pretty interesting history
- 👴🏻: "back in my days,": developer developed a game using Assembly language because they need the full control of the memory, because of the fact that they need to keep the hardware requirment as low as possible just to be able to play the game on the dogshit old hardware back in the day 😢

#### Emulation and Virtualization
- Emulation, in short, involves making one system imitate another. For example, if a piece of software runs on system A and not on system B, we make system B “emulate” the working of system A. The software then runs on an emulation of system A.
- In this same example, virtualization would involve taking system A and splitting it into two servers, B and C. Both of these “virtual” servers are independent software containers, having their own access to software based resources – CPU, RAM, storage and networking – and can be rebooted independently. They behave exactly like real hardware, and an application or another computer would not be able to tell the difference.
- more sources: [https://www.javatpoint.com/emulation-vs-virtualization](https://www.javatpoint.com/emulation-vs-virtualization)

#### History of CPU 💻
- Single Task + Single User
- Multi Task + Single User
- Single core, Multi-thread
- more core doesnt always mean faster x amount of times
	- bc of **overhead** is fking massive 🤣
		- distribution of the tasks
		- combining the tasks
		- communication between the core (coupled-task)

#### Improvement of CPU
- the implementation of these techniques:
	- Cache
	- Pipelining
	- Superscalar

#### AMD vs Intel 🔥
- "Ryzen" series made AMD caught up the Intel 😂
	- bc it uses "branch predictation" to predict the next command from the previous ones in the conditional statement, loop etc.

#### File System
- share file system across the network
- multi user
- system admins need to admin the network "by the order of the organization"
	- eg. "permission", "AAA"

### Resource the SPA need to be considering
- computing power: manage properly across the process
- memory
- storage: what to store, worthness, cost, file partitioning
- network connection: ประสานงาน, แก้ไขปัญหา, update&upgrade

## week3
- SPA ต้องสามารถบอกรายละเอียดทุกสิ่งทุกอย่างที่เกี่ยวกับ computer ได้
- laptop vs computer -> laptops are hard to upgrade but not for computer

#### Hardware 
![](https://camo.githubusercontent.com/ad157f0e752e1be6ca9487ae22aa5bb8fedf16eb128efd2d4b349da0797a5d30/68747470733a2f2f6d656469612e646973636f72646170702e6e65742f6174746163686d656e74732f313031343339383937343634393730383632342f313036373939363234313236303230343038322f696d6167652e706e673f77696474683d31333839266865696768743d363835)
- RAMs: for server need to have ECC (Error Correction Control) จากความไม่เสถียรของไฟฟ้า
	- ซึ่ง ECC ที่ทำงานเฉพาะใน RAM อย่างเดียว
- CPU: Central Processing Unit ถูกออกแบบมาให้เป็นประมาณ General Purpose Circuit
- GPU: "Graphic" (Specific Purpose) ทำได้ดีกว่า CPU ในด้าน graphic
- PSU: Power Supply Unit -> จ่ายไฟให้กับระบบให้เพียงพอ
- Heat sink: wind -> "suck and blow" 🗿
- dust -> heat sing worst enemy 😡💢

#### Environment
![](https://camo.githubusercontent.com/6cadc5d81f19d8d4fc96f8775e523a38b5af64499b098bafd5b3f11502bfe880/68747470733a2f2f6d656469612e646973636f72646170702e6e65742f6174746163686d656e74732f313031343339383937343634393730383632342f313036373939363238373537373838323734342f696d6167652e706e673f77696474683d383333266865696768743d363835)
- POS: Position of S....
	- พิจารณาการจ่ายไฟฟ้าในพื้นที่ตั้ง
	- ภัยพิบัติ - ธรรมชาติ, จากมนุษย์ (ขโมย, จราจล)
- SFC (security): ทำให้เกิดความปลอดภัย eg. ctv, lock
- Electricity: ความเสถียรของไฟฟ้า -> UPS for un-expected event "ไฟดับ" แต่ก็ยังไม่พอกับเหตุการณ์นานๆ
	- self-owned power generater if you are a gigachad 💪
- HVAC (Heating Ventilation and Air Conditioning): ไฟฟ้าสถิต -> ความชื้นสัมพัทธ์ต่ำ
- **Protection Alarm**: แจ้งเตือน 🚒 eg. ไฟดับ, ไฟไหม้ 🔥 -> Thermometer, Fire Alarm, Smoke Detector, วัดค.ชื้นสัมพัทธ์
- SCB Incident: +10 deads 😿 -> what happens: ช่างไปซ่อม แล้วทำให้เกิดข้อผิดพลาดของ smoke detector ปล่อย gas that cause the room to have no O2 

- all of the above then come into "profit ?" how do you estimate the "worth" of investing in the hardware and environment 

### Idek 🤷🏻‍♂️
- computer aspects -> พยายามทำให้อุปกรณ์กินไฟฟ้าไม่เยอะ ไม่เปลือง, **Power efficiency** ต้องมีความคุ้มค่าของการใช้พลังงาน
	- "รักษ์โลก" 🌍
		- power efficiency ⚡
		- packaging eg. no charging w/Iphone 📱
		- re-use ♲
- geo-politic aspects: "conflict-free" เป็นการส่งเสริมสิ่งที่ "ดี"

> no week 4 cause im sick 🤮

## week5

### SPA overworked?
- power user
	- basic computer knowledge
- help desk
	- need communication skills 😎 + diagnostics skillz 👨‍🏫
- self service
	- help reduce the loads of the help desk
	- eg. forgot password, new password
	- inorder to make a self service 
		- need deep understanding of the problems (services) 
		- knowledge database of both "provider" and "customer" of the services
			- FAQs
	- can be exploit by a amogus 😏
		- eg. "hey can you reset the password I forgot, btw im not the owner"
- good design 😎 (no manual needed)
	- designs that less prone to problems
- system platform admin -> a bitch to everyone 🤷🏻‍♂️

### UNIX History 101
- UNIX is the last "type" of OS the still stands to this day
- BSD (Berkeley Software Distribution)
	- FreeBSD
	- MacOS X (not 100%)
- Richard Stallman -> introduces the word "free" to the software worlds
	- founded Free Software Foundation -> GNU -> eg. Emacs 🤢
- GNU Kernel -> Linux OS from Mr. Linus Torvalds from the scratch
- Red Hat made a profit out of a free software by providing a service, help desk, a shoulder to cry on 😢
	- RHCE - Red Hat Certified Engineer

### Licensing
- as a SPA u need to know the "pricing model"
	- the more you pay the more you get 😏
- adhere to the legalality of the license 🤫
- consider the investment of the company -> make yourself more valuable to the company 🥱

#### note nextweek
- review OS -> process scheduling, memory management, bla blah blah .. .. .
- layering ..... monolithic

> week6 no class yo 😎

## week7

### Unix file 🗃️
- everything is a binary files but in the different forms (universally)
	- jpeg 
	- pdf
	- mp3
- file extension is just for the convenient of "file association" 💥
	- just to tell which program that uses to open the file 😎

### Linux Command
- cat
- hexdump
- grep
- ls
- pipe `|`

- then bro just went on a rant about `cat`, `od`, `hexdump`, `head`, `tail` for just displaying a files for like 2 hours 🤮
	- big endian, small endian

### Linux OS
![](https://media.discordapp.net/attachments/1014398974649708624/1078165844347064330/image.png)

#### Linux Redirection
- `>` output redirection (rewrite all)
- `>>` outpute redirection (append)
	- `who > users`
	- `echo line 2 >> users`
 - `<` input redirection

#### Pipe 😵
- `|` called "pipe" output of one program -> input of another program

### Homework lol 😂
- learn more about unix redirection `>, >>, <, |`
- learn more about unix file permission `drwxrwxr--`
	- **reason why** -> because its multi-user so everybody cant have the same permission and for security measure such as cant have a nobody accessing or writing your file without your permission

## week8

## UNIX cont.
- `^D` -> exit out of system or end of file (eof)
- `^S` -> stop
- `^Q` -> stop showing current display of  (start) 
- `^C`-> interupt (terminate) current process (intr)
- `^Z` -> suspense (pause) current process (susp)

#### Meta Character
- `*` -> anychar length > 0
- `?` -> anychar length == 1
- `\`
- inorder to be using this shit your file naming convention need to be good enough or organized enough for it to be efficient or its not gonna fuck you up

#### List
- `ls -aldt`
	- a: all
	- l: list detail
	- t: ordered by time last changed
	- d: directory only no file under

### File Permission
- rwx - read|write|execute
- **drwxr-x-r-x**
	- first char -> d = directory, l = softlink, c = char device, b = log device
	- next three (rwx) -> rights of the owner
	- next three (rwx) -> rights of its group
	- next three (rwx) -> rights of others
- why need a group -> convienient

#### ACL mode
- access control list -> same shit with network routing ACL

## week 10
### Exams
- from last last week
- redirection `<` `>` `>>` and pipe `|`
- `man` command
- `ls -alt`
- file permission rwx,
	- owner | group | others
	- rwxr--r--

### Storage 🗃
- hdd -> dogshit 💩
- ssd -> better 😋
- storage management -> multiuser
	- security
	- seperate folder
- IPC (inter process communication)
	- make people work together without interrupting each other
- **rwx for directory** -> **r**: can you read the file in that dir, **w**: can you change/create file in the dir, **x**: can you get into that dir
	- ☢️ exams

### Vi Text  Editor
- available to all unix -> to config the file in the beginning

### Assignment but not assigns
- try vi 💀💀💀
- what are the config file of sshd, mysql, apache server
	- sshd_config, .cnf, httpd.conf

## week11
## Unix Shell Script
- **purposes**
	- automate stuff to get shits done ✅
	- do stuff with conditions

### Basic Syntax 🤯
- first line of **shell script** -> `#!/bin/sh` starts with `#!`
- remark or comment (line that start with): `#` 
- end a **shell script** -> `exit`  🤠
	- which you can specify the *return value* to further describe the *status* of the script that ran eg. `0` for normal, <other_number> to specify the type of errors
- variables `${variable_name}`
	- eg. `echo Current shell is "${SHELL}"`
- in linux when you create a shell scipt, basically it just a text file so you will need to change the permission of the script to be **executable**
	- with command `chmod` eg. `chmod +x <FILE>`
- so inorder to be a complete shell script ☢️
	1. `#!` (pronounced "sha-bang")
	2. follows with `bin/sh`
	3. +x permission of that script file
- the `#!bin/sh` is just a declaration of which **shell** you are going to use 🤔
	- os will take a peek at the *"head"* of the script before it ran
	- eg. zsh, fish, ash, bash, sh
- **argument**: `$1 $2 $3 ... $9` & can be shift by `shift`
-  **if else**
	- `if [ "$1" != "" ]` -> check if the first argument are given
	- `[` is a program called **eval**
	- true == `0`, false != `0`
- **for loop**
```
for var in list
do
	command(s)
done
```
- **while**
```
while condition
do
	commands
done
```
-  **until**
```
until condition
do
	commands
done
```
- **case** -> `;;` == `break`, end with `esac`
```
case str in
pattern_a
	commands
	;;
pattern_b
	commands
	;;
*)
	commands
	;;
esac
```

### Daily Rant 🥱
- binary file (executable)
	- a.out format -> classic executable file format
	- elf binary
- variables in unix shell -> **string** 💀

> week12 13 14 is donzo

## week15

### Linux Fundamentals
#### History
- Denis Ritchie, Richard Stallman -> Free Software Foundation
- Linus Torvalds -> wrote POSIX compliant kernel -> GNU Linux kernel

#### Distributions
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

### Pipes and Commands
#### I/O redirection
- why need redirection ? -> old days doesnt have clipboard
- `>` : stdout
- `>>` : append
- `|` : pipes
- `<` : stdin
- `<<` : here document
- `<<<` : here strings

#### Filter
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

### Vi 😎 🤝 🗿

## week 16
### Linux Fundamentals Cont.

#### Shell Scripts 🐚
- as the prof. said just skip the fuck outta this one 🤣
- just scripting to make the repeated, boring stuff easier to use when u need em

#### Users
- `whoami`
- `who`
- `su`: swtich user
- `swtich` to root
	- su root
	- su -

#### User management
- local user db in linux is at `/etc/passwd`
- `useradd`: or `adduser`
- `userdel`
- `usermod`: modify user properties
- `chsh`: change shell
	- `chsh -l`

#### User Life Cycle (ออกสอบ)
- understand the meaning
- user add, delete, logs and shit

#### User passwords
- `passwd`: set password of user
- `openssl`: encrypt password with hash
- `/etc/passwd`: contains all user info sep with `:`
- `/etc/shadow`: users passwords are encrypted and kept in here (only accessible by root)
	- why do we need two files that contains the infomation of the user -> protection of `offline password cracking (hacking)`

#### User profiles
- `/etc/profile`
- `~/.bash_profile`

#### Groups
- why do we need group?
	- the laziness of the admin that need to give permission to user that has the same permission
	- imagine if you have to add the same permission to the 100 users with the same role 100x times 🤷🏻‍♂️
	- determine the access control group
- `groupadd`
- `/etc/group`: group files
- `groups`: see a list of group that user belongs to
- `usermod`: eg. `usermod -aG user group`
- `groupmod`
- `groupdel`

#### Standard File Permission
- `rwx`: read/write/execute

#### Access control lists
- file systems that support **acl** have to be mounted with the acl option in `etc/fstab`

#### File links

### Exams
- ออกตามที่บอก ตามที่สอน ตามที่สัั่ง งาน 1,2
- open book
- 4 problems
- ห้ามลอกจาก open book เข้าไปตอบทือๆ

## Old Exams

### User Account Lifecycle
- หมายถึง ขั้นตอนวิธีการในการจัดการ (manage) กับตัว user account ของทุก user ทั้งนี้มีการออกแบบวิธีจัดการหลายรุ)แบบ โดยการอธิบายนี้จะอ้างอิงถึง user life cycle จาก red hat documentation เริ่มจาก user account จะมี state อยู่ 3 state
	- stage: เป็น state เริ่มต้นของ user account ที่ยังไม่อนุญาตให้เข้าถึงข้อมูล
	- active: state ที่สามารถเข้าถึงข้อมูลและ user account ที่มี properties ครบถ้วน
	- preserved: เป็น state ที่เกิดเมื่อ active user ต้องการที่จะ deactivate account ทำให้ state นี้ไม่สามารถเข้าถึงข้อมูลได้แต่ว่ายังคงมี user account properties อยู่ครบถ้วน
- จะสังเกตได้ว่าการที่มี preserved state ทำให้สามารถออกแบบให้มีการ Deactivate และ Reactivate account ได้ทั้งนี้ยังมีการ delete account ถาวรซึ่งหากว่า action ไปแล้วจะไม่สามารถกู้คืนได้
- หลังจากที่กล่าวถึง user account state ต่อมาจะกล่าวถึง state operation ซึ่งจะถูก perform โดย spa ของระบบ โดยสามารถจะเปลี่ยน state ของ user acc จาก state ถึงไปยังอีก state นึงได้ โดยจากการออกแบบของ red hat มีการออกแบบไว้ดังนี้
	- stage -> active: เมื่อ account อยู่ใน stage state พร้อมที่จะ activate แล้ว admin จะทำการเปลี่ยน state เป็น active state
	- active -> preserved: เมื่อ user นี้ออกจากบริษัทหรือองค์กร admin ทำการเปลี่ยน state เป็น preserved
	- preserved -> active: เมื่อ user ที่เคยออกจากองค์กรกลับเข้ามาองคืกรอีกครั้ง admin กู้คืน account จาก preserved state เป็น active state
	- preserved -> stage: เมื่อ user ที่เคยออกจากองค์กร มีแผนจะกลับเข้าองค์กร admin สามารถย้าย state จาก preserved เป็น stage ได้เพื่อเตรียมพร้อม account สำหรับการ  reactivate
- ทั้งนี้ได้มีการออกแบบให้สามารถ delete account กรณีที่ user acc ที่อยู่ใน active, stage or preserved แต่ว่าไม่สามารถเปลี่ยนจาก stage เป็น preserved ได้โดยตรง ทำได้เพียง delete ถาวรเท่านั้น
- หลังจากกล่าวถึง state operation สามารถสรุปได้เป็นแผนภาพ ดังนี้
![](https://media.discordapp.net/attachments/1014398974649708624/1106222095492452394/image.png)
- สาเหตุที่นำตัวอย่างการออกแบบจาก red hat มาใช้ในการอธิบายนั้น เพราะหลังจากได้ทำการศึกษาพบว่า หลายองค์กรได้มีการ implement เรื่องการจัดการ user acc life cycle โดยใช้ model นี้จึงคิดว่า ตัวอย่างนี้เป็น best practice ในการออกแบบ ซึ่งนอกจากนี้ยังมีข้อพึงในการออกแบบ user acc life cycle เช่น
	- ควรออกแบบให้แต่ละ process ของ life cycle เป็น automate มากเท่าที่เป็นไปได้
	- ออกแบบ เรื่องเกี่ยวกับ security ให้สามารถจัดการเรื่อง permission ในการเข้าถึงข้อมูลและการปรับสิทธิ์ในการเข้าถึง
	- เก็บ log/report ทุกๆการเปลี่ยนแปลงของ user
- ส่วนของกลไก identification เกี่ยวกับข้อง user account โดยทุกครั้งที่จะมีการเข้าถึง secured data หรือ system ระบบจะต้องระบุได้ว่า user ใดที่พยายามเข้าถึงอยู่ โดยตรวจสอบจาก user property
- authentication เกี่ยวข้องกับ user acc โดยเป็นกลไกที่ใช้ในการรับรองว่า user ที่จะทำการเข้าถึงข้อมูลนั้น คือ user นั้นจริงๆ
- authorization หลังจากผ่านการ authen สามารถระบุได้แล้วว่า user เป็นใคร ขั้นตอนนี้จะเป็นการระบุว่า user นี้ access เข้ามาด้วย type อะไรเข้ามาด้วย role admin, user ธรรมดา หรือระบุ permission ทั้ง allow, deny ในการเข้าถึงข้อมูลต่างๆ
- auditing ในทุกการเปลี่ยนแปลง event ต่างๆ ที่เกี่ยวข้องกับ user acc ควรจะมีการเก็บ log/report เอาไว้เพื่อเป็นหลักฐานหรือประวัติการใช้งาน การเปลี่ยนแปลงของ user acc

### การเตรียมการรับมือ
- เริ่มจากการเตรียมบุคลากรที่จะรับมือต่อการถูกบุกรุกอาจจะเป็นผู้ดูแลระบบหลายคนเพื่อแบ่งหน้าที่ในการรับผิดชอบ โดยตัวผู้ดูแลระบบจะต้องมีความสามารถในการวิเคราะห์ปัญหา ใช้ software และการ   monitor ระบบได้
- จัดหา monitoring tools ในการ monitor ระบบและ security scanning
- จัดหางบประมาณในการบำรุงรักษาระบบ monitoring และ security scanning
- ทำการ update software ที่ใช้งานให้ up to date อย่างสม่ำเสมอ เพื่อลดช่องโหว่ของ software
- จัดอบรม training การใช้งาน monitoring tools และ security scanning

- การตรวจจับ
	- ใช้งาน health check function ในระบบ monitoring ว่าหากตรวจพบอะไรให้แจ้งเตือนให้ผู้ดูแลระบบทราบ
	- ใช้ security scanning ในการ scan หาช่องโหว่ หรือใช้ software antivirus ในการ scan หา
	- scan port ภายในเครื่องมือเพื่อตรวจสอบว่า เราได้เปิด port ที่อาจจะทำให้ บุคคลภายนอกบุกรุกเข้ามาได้
- การระงับเหตุ
	- ตรวจสถาพ hardware ทั้งระบบให้พร้อมใช้งาน
	- ตรวจสอบ version of software -> up to date
	- หากเกิดเหตุฉุกเฉิน ระบบถูกบุกรุก ควรตัด connection ออกก่อนเพื่อป้องกันการลุกลามของการบุกรุก และจัดการกับช่องโหว่ที่ตรวจพบ
	- หากทำการ port scan แล้วพบ port ที่มีช่องโหว่เปิดเอาไว้ ให้ทำการปิด service นั้นก่อน
	- หากทำการใช้งาน security scanning หรือ software antivirus แล้วตรวจพบช่องโหว่ ให้จัดการกับช่องโหว่นั้น
- การฟื้นฟูระบบ
	- หลังทำการระงับเหตุและจัดการกับช่องโหว่ทั้งหมดแล้ว ให้ทำการ restore ระบบและ network ให้พร้อมใช้งานดังเดิม
	- ทำความเข้าใจกับช่องโหว่ เพื่อป้องกันไม่ให้เกิดเหตุซ้ำ
	- ทำการ test ระบบของตัวเองเพื่อเพิ่ม reliability ของระบบ

### 3.
#### process management
- process หมายถึง source code ที่ compile ไปและกำลังทำงานอยู่ในระบบซึ่งแต่ละ process จะมี Id ของตัวเอง (PID) ซึ่ง ณ เวลาหนึ่งไม่ได้มี process ทำงานอยู่เพียง process เดียว หลายๆ process ทำงานพร้อมกันโดยมี CPU เป็นตัวควบคุมให้แต่ละ process ทำงานไปเรื่อยๆจนโปรแกรมสิ้นสุดซึ่ง spa มีหน้าที่ในการ monitor ดูแลและจัดการให้ระบบทำงานได้อย่างมีประสิทธิภาพ
- ตัวอย่างการจัดการ process
	- ในการจัดการเราจะจัดการ process โดยใช้ PID เป็นหลักโดยคำสั่งหลักๆ ที่ใช้ในการ check status ของ process ที่กำลังทำงานอยู่คือ คำสั่ง `ps` โดยสามารถประยุกต์ใช้กับ | และ grep เพื่อหา output ของ process ที่ต้องการได้ เช่น `ps -ef | grep nginx`
#### Disk management
- การจัดการ disk มีอยู่หลายหัวข้อได้ แก่ devices, partition, mounting, file system, RAID, LVM และอื่นๆ ซึ่งเป็นหน้าที่ของ spa ที่จะ manage disk ให้มีความเหมาะสมและตรงตามความต้องการของระบบ
- ตัวอย่างการจัดการ disk partition ด้วยคำสั่ง fdisk
	- `fdisk -l` แสดง hard disk ที่ทำการ attach ทั้งหมดออกมา
	- `fdisk /dev/sdc #name_of_disk` เป็นการเข้าถึง disk แล้วสามารถใช้คำสั่ง n เพื่อ create new partitioning
	- `fdisk /dev/sdc #name_of_disk` ใช้คำสั่ง d เพื่อ delete partition
	- หลังจากเสร็จแล้วให้ใช้คำสั่ง w เพื่อการทำการ save และ exit จาก fdisk
#### Boot Managment
- การเข้าใจ process การ boot และ start up เป็นสิ่งสำคัญในการแก้ปัญหาเกี่ยวกับ OS configure และ startup issue ซึ่งเป็นหน้าที่ของ spa
- ตัวอย่างการใช้งาน `systemctl` ในการจัดการ server (daemon)
	- `systemctl start crond.service #service_name`  start service
	- `systemctl stop crond.service #service_name`  stop service
	- `systemctl enable crond.service #service_name`
	- `systemctl disable crond.service #service_name`
	- `systemctl status crond.service #service_name`
#### System Management
- การจัดการ system มีตั้งแต่ scheduling, loggin, memory manage, resource monitor, package manage ซึ่งเป็นหน้าที่ของ spa
- ตัวอย่างการใช้งาน apt-get (package manager software) ในการจัดการ package ต่างๆ
	- `apt-get update` download packge จาก repository ต่างๆมา โดยใช้คำสั่งนี้ก่อนที่จะทำ operation อื่นๆกับ package
	- `apt-get upgrade` upgrade downloaded package (software)
	- `apt-get install`
#### Network Management
- การจัดการ network อาจจะไม่ใช่ OS based management ทั้งหมดแต่ว่าสามารถจัดการกับบางเรื่อง เช่นเกี่ยวกับ protocol เช่น ssh (secure shell), nfs หรือการทำ network configuration 
- ตัวอย่างคำสั่ง ifconfig
	- `ifconfig` แสดง list ของ all network interface
	- `ifoncifg eth0` แสดง output ของ network interface eth0
	- `ifconfig eth0 <up/down>`  up or down ของแต่ละ interface
#### Kernel Management
- ในการจัดการ  kernel นั้นเกี่ยวข้องทั้งการจัดการ module ที่ load จาก kernel และการจัดการ library เป็นไฟล์ binary ซึ่งการจัดการให้มีประสิทธิภาพเป็นหน้าที่ของ spa
- ตัวอย่างคำสั่ง ltrace แสดงการเรียกใช้ lib ว่าถูก program ใดเรียกบ้าง
	- `ltrace -c -l /lib/libpam.so.0 #name_of_lib`
#### Backup Managment
- การสำรองข้อมูลเพื่อป้องกันการสูญหายของข้อมูล นับเป็นหน้าที่ของ spa
	- mutli level incremental
	- full backup on monday (level 0)
	- back up on tuesday (level 1)
	- back up on wednesday (level 2)
	- back up on thursday (level 3)
	- back up on friday (level 3)
#### Remote Desktop
- การทำ remote desktop เป็นผลดีต่อการทำงานเพิ่มความสะดวกสบายให้กับ system admin ทั้งสามารถใช้ในการ run desktop อื่นบนเครื่องตัวเองและยังสามารถใช้จัดการปัญหาให้กับ user ในระบบได้อีกด้วย การแก้ไขปัญหาให้กับ user นั้นก็นับเป็นหน้าที่ของ spa
#### Web Server
- ปัจจุบัน application ต่างๆ ส่วนใหญ่มักจะเป็น web based ทำให้การเปิด web server และดูแลจัดการให้ web server ทำงานได้อย่างราบรื่นและปลอด
#### Database Server
- เหมือนกับ web app ต้องมีการเก็บข้อมูล การเปิด db server ต้องมีการดูแล จัดการ ให้ทำงานได้อย่างราบรื่นปลอดภัย
#### Learn new Technologies

### การจัดสรร storage partition directory LVM, RAID
- การจัดสรร storage เพื่อเพิ่มประสิทธิภาพการใช้งานดิสก์ และเพิ่มความสำเร็จในการเข้าถึงไฟล์บล็อกมีทั้งหมด 3 รูปแบบดังนี้
	- contiguous allocation: เป็นการจัดสรรพท.ว่าง ในดิสก์ให้แฟ้มโดยหาที่ว่างบนดิสก์บริเวณที่ติดกัน OS จะต้องรู้ขนาดแฟ้มเพื่อหาที่ลงให้แฟ้มโดยจะเก็บข้อมูล address เริ่มต้นและความยาวของพท. ข้อดีคือรวดเร็ว แต่ยากต่องการ fragmentation และยากต่อการเพิ่มขนาดของแฟ้ม
	- linked allocation: เป็นการแบ่งแฟ้มออกเป็นส่วนย่อยๆ ที่มีขนาดเท่ากันเรียกว่า block โดยในแต่ละ block จะมี pointer ที่ชี้ไปยัง block ถัดไป ข้อดีคือมีขนาดแฟ้มยืดหยุ่นได้ แต่เปลืองพื้นที่ในการเก็บตัวชี้ และไม่รองรับ random/direct access
	- index allocation: จะทำการรวม pointer ทั้งหมดไว้ที่ index block โดยแต่ละแฟ้มจะมี index block เป็นของตัวเอง ข้อดีคือ direct access เข้าถึงได้เร็ว แต่จะเสียพท.ในการจัดเก็บ index block
 - partition เป็นการแบ่งพท.จัดเก็บออกเป็นหลายๆ ส่วน เพื่อให้เป็นระเบียบ ง่ายต่อการเข้าถึงข้อมูล โดย partition แบ่งได้เป็น primary partition, extend parition, logic partition
- directory เป็นระบบแฟ้มข้อมูลที่แบ่งเป็น partition แต่ละ partition จะบรรจุ infomation ของแต่ละแฟ้ม เช่น ชื่อ ตำแหน่ง ขนาด และชนิดของข้อมูล
	- single-level directory
	- two level directory
	- tree structured directory
	- acyclic graph
- LVM เป็นระบบจัดดิสก์ที่มีประสิทธิภาพ (เพิ่ม/ลด ขนาดได้, แบ่งกลุ่มได้) ที่อยู่บนระบบปฏิบัติการ Linux
	- Volume Group (VG):
	- Physical Volume (PV):
	- Logical Volume (LV):
	- File System
- RAID คือการสร้าง logical drive (Array) จาก physical drive หลายๆตัวเพื่อเพ่ิมความจุหรือประสิทธิภาพความเร็ว หรือใช้สำรองข้อมูล ซึ่งสามารถแบ่งประเภทได้ดังนี้
	- RAID 0: นำความจุมารวมกัน
	- RAID 1: ข้อมูลทำสำเนา
	- RAID 5: นำข้อมูลกระจายลง disk ตาม parity
	- RAID 6: parity 2 ชั้นและใช้ 4  disk ขึ้นไป