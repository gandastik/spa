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