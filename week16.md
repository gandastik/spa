## Linux Fundamentals Cont.

### Shell Scripts 🐚
- as the prof. said just skip the fuck outta this one 🤣
- just scripting to make the repeated, boring stuff easier to use when u need em

### Users
- `whoami`
- `who`
- `su`: swtich user
- `swtich` to root
	- su root
	- su -

### User management
- local user db in linux is at `/etc/passwd`
- `useradd`: or `adduser`
- `userdel`
- `usermod`: modify user properties
- `chsh`: change shell
	- `chsh -l`

#### User Life Cycle (ออกสอบ)
- understand the meaning
- user add, delete, logs and shit

### User passwords
- `passwd`: set password of user
- `openssl`: encrypt password with hash
- `/etc/passwd`: contains all user info sep with `:`
- `/etc/shadow`: users passwords are encrypted and kept in here (only accessible by root)
	- why do we need two files that contains the infomation of the user -> protection of `offline password cracking (hacking)`

### User profiles
- `/etc/profile`
- `~/.bash_profile`

### Groups
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

### Standard File Permission
- `rwx`: read/write/execute

### Access control lists
- file systems that support **acl** have to be mounted with the acl option in `etc/fstab`

### File links

### Exams
- ออกตามที่บอก ตามที่สอน ตามที่สัั่ง งาน 1,2
- open book
- 4 problems
- ห้ามลอกจาก open book เข้าไปตอบทือๆ