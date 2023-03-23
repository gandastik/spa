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
