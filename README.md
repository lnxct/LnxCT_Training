# LinuxTraining
## Basic Linux Command
## File System

### Basic Linux Command

| cp | copy file to another name or on another directory. |   |   |
|----|---------------------------------------------------|---|---|
```
cp source_file destination_file
examples:
cp a.txt /home/thepenguina/desktop/a.txt
cp a.txt /home/thepenguina/desktop/
cp a.txt /home/thepenguina/desktop/b.txt
```
| mv | move or rename files. |   |   |
|----|---------------------------------------------------|---|---|
```
mv source_file destination_file
mv new_filename existing_filename
examples:
mv a.txt /home/thepenguina/desktop/a.txt
mv a.txt /home/thepenguina/desktop/
mv a.txt /home/thepenguina/desktop/b.txt
mv abc.txt hello.txt
```

| help | show the help and sub command of command. |   |   |
|----|---------------------------------------------------|---|---|
```
cmd_name --help
examples:
mv --help
vi --help
mkdir --help
```

| man | It’s show command manual. |   |   |
|----|---------------------------------------------------|---|---|
```
man <cmd_name>
examples:
man ssh
man mkdir
```
| info | It’s show the command information.  |   |   |
|----|---------------------------------------------------|---|---|
```
info <cmd_name>
examples:
info man
info usermod
```

| less | It’s show the file in short screen you can read more by pressing up down keys.  |   |   |
|----|---------------------------------------------------|---|---|
```
less <file_name>
examples:
less xyz.txt
less index.html
```

| more  | It’s show the all the file content.   |   |   |
|----|---------------------------------------------------|---|---|
```
more <file_name>
examples:
more xyz.txt
more index.html
```

| whatis  | whatis is provide a description/explanation of entry command.   |   |   |
|----|---------------------------------------------------|---|---|
```
whatis <cmd_name>
examples:
whatis ls
whatis man
```

| which  | In which command is display the location of command.   |   |   |
|----|---------------------------------------------------|---|---|
```
which <cmd_name>
examples:
which ls
which man
```

| who  | show the current users login ans login time.   |   |   |
|----|---------------------------------------------------|---|---|
```
who 
examples:
who
```

| whoami  | show the current use name.   |   |   |
|----|---------------------------------------------------|---|---|
```
whoami 
examples:
whoami
```

| useradd  | it’s used for create new user.   |   |   |
|----|---------------------------------------------------|---|---|
```
useradd <usr_name>
examples:
useradd dipen
useradd bhavin
```

| userdel  | it’s used for delete user.   |   |   |
|----|---------------------------------------------------|---|---|
```
userdel <usr_name>
examples:
userdel dipen
userdel bhavin
```
useradd <usr_name>
examples:
useradd dipen
useradd bhavin
```

| userdel  | it’s used for delete user.   |   |   |
|----|---------------------------------------------------|---|---|
```
userdel <usr_name>
examples:
userdel dipen
userdel bhavin
```

| usermod  | it’s used for modify user directory,expiry. comment, etc...   |   |   |
|----|---------------------------------------------------|---|---|
```
usermod [option] <usr_name>
examples:
usermod -e 02/12 dipen
usermod -l bhavin
```/12 dipen
usermod -l bhavin
```

| users  | show all the available users   |   |   |
|----|---------------------------------------------------|---|---|
```
users
examples:
users
```

| groups  | show all the available groups   |   |   |
|----|---------------------------------------------------|---|---|
```
groups
examples:
groups
```
| groupadd  | it’s used for create new group.   |   |   |
|----|---------------------------------------------------|---|---|
```
groupadd <usr_name>
examples:
groupadd dipen
groupadd bhavin
```

| grouprdel  | it’s used for delete group.   |   |   |
|----|---------------------------------------------------|---|---|
```
groupdel <usr_name>
examples:
groupdel dipen
groupdel bhavin
```

| groupmod  | it’s used for modify groups.   |   |   |
|----|---------------------------------------------------|---|---|
```
groupmod [option] <usr_name>
examples:
groupmod -e 02/12 dipen
groupmod -l bhavin
```

| id  | it’s used for modify groups IDs.   |   |   |
|----|---------------------------------------------------|---|---|
```
id [option] = <usr_name>
examples:
id -g dipen
id -G bhavin
```

| ls  | ls is a command to list computer files in Unix and Unix-like operating systems.   |   |   |
|----|---------------------------------------------------|---|---|
```
ls
examples:
ls```

