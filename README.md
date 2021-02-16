# LinuxTraining
## Basic Linux Command
## File System

### Basic Linux Command

| cp | copy file to another name or on another directory. |
|----|---------------------------------------------------|
```
cp source_file destination_file
examples:
cp a.txt /home/thepenguina/desktop/a.txt
cp a.txt /home/thepenguina/desktop/
cp a.txt /home/thepenguina/desktop/b.txt
```

| help | show the help and sub command of command. |
|----|---------------------------------------------------|
```
cmd_name --help
examples:
mv --help
vi --help
mkdir --help
```

| man | It’s show command manual. |
|----|---------------------------------------------------|
```
man <cmd_name>
examples:
man ssh
man mkdir
```
| info | It’s show the command information.  |
|----|---------------------------------------------------|
```
info <cmd_name>
examples:
info man
info usermod
```

| less | It’s show the file in short screen you can read more by pressing up down keys.  |
|----|---------------------------------------------------|
```
less <file_name>
examples:
less xyz.txt
less index.html
```

| more  | It’s show the all the file content.   |
|----|---------------------------------------------------|
```
more <file_name>
examples:
more xyz.txt
more index.html
```

| whatis  | whatis is provide a description/explanation of entry command.   |
|----|---------------------------------------------------|
```
whatis <cmd_name>
examples:
whatis ls
whatis man
```

| which  | In which command is display the location of command.   |
|----|---------------------------------------------------|
```
which <cmd_name>
examples:
which ls
which man
```

| who  | show the current users login ans login time.   |
|----|---------------------------------------------------|
```
who 
examples:
who
```

| whoami  | show the current use name.   |
|----|---------------------------------------------------|
```
whoami 
examples:
whoami
```

| useradd  | it’s used for create new user.   |
|----|---------------------------------------------------|
```
useradd <usr_name>
examples:
useradd dipen
useradd bhavin
```

| userdel  | it’s used for delete user.   |
|----|---------------------------------------------------|
```
userdel <usr_name>
examples:
userdel dipen
userdel bhavin
```

| usermod  | it’s used for modify user directory,expiry. comment, etc...   |
|----|---------------------------------------------------|
```
usermod [option] <usr_name>
examples:
usermod -e 02/12 dipen
usermod -l bhavin
```/12 dipen
usermod -l bhavin
```

| users  | show all the available users   |
|----|---------------------------------------------------|
```
users
examples:
users
```

| groups  | show all the available groups   |
|----|---------------------------------------------------|
```
groups
examples:
groups
```
| groupadd  | it’s used for create new group.   |
|----|---------------------------------------------------|
```
groupadd <usr_name>
examples:
groupadd dipen
groupadd bhavin
```

| grouprdel  | it’s used for delete group.   |
|----|---------------------------------------------------|
```
groupdel <usr_name>
examples:
groupdel dipen
groupdel bhavin
```

| groupmod  | it’s used for modify groups.   |
|----|---------------------------------------------------|
```
groupmod [option] <usr_name>
examples:
groupmod -e 02/12 dipen
groupmod -l bhavin
```

| id  | it’s used for modify groups IDs.   |
|----|---------------------------------------------------|
```
id [option] = <usr_name>
examples:
id -g dipen
id -G bhavin
```

| ls  | ls is a command to list computer files in Unix and Unix-like operating systems.   |
|----|---------------------------------------------------|
```
ls
examples:
ls
```

| grep  | The grep filter searches a file for a particular pattern of characters,  and displays all lines that contain that pattern. The pattern that is  searched in the file is referred to as the regular expression (grep  stands for globally search for regular expression and print out).    |
|----|---------------------------------------------------|
```
grep [option] patterns [file]
examples:
grep -i "bhavin" abc.txt
grep -c "bhavin" abc.txt
```

| sed  | SED command in UNIX  is stands for stream editor and it can perform  lot’s of function on file like, searching, find and replace, insertion  or deletion.    |
|----|---------------------------------------------------|
```
sed [option] patterns [file]
examples:
sed 's/bhavin/dharmesh/g' abc
sed 's/unix/linux/g' /etc/home/bhavin/abc.txt
```

| awk  | Awk is a scripting language used for manipulating data and generating reports. The awk command programming language requires no compiling, and allows  the user to use variables, numeric functions, string functions, and  logical operators. |
|----|---------------------------------------------------|
```
awk [option] 'selection_critearia {action}' <file_name>
examples:
awk '/manager/ {print}' abc         [this command print only manager colum]
awk '{print $1, $5}' bhavin.txt     [this command print only 1 and 5 coloum of file]
```

| cd  | change directory.    |
|----|---------------------------------------------------|
```
cd <dir_name>
examples:
cd xyz
cd .. [for previous directory]
```

| mkdir  | make new directory.    |
|----|---------------------------------------------------|
```
mkdir <dir_name>
examples:
mkdir xyz
```


| rm | remove directory and file |
|----|---------------------------------------------------|
```
rm <file_name or dir_name>

examples:
rm abc.txt
rm bhavin [dir]
```

| mv | move or rename files. |
|----|---------------------------------------------------|
```
mv source_file destination_file
mv new_filename existing_filename
examples:
mv a.txt /home/thepenguina/desktop/a.txt
mv a.txt /home/thepenguina/desktop/
mv a.txt /home/thepenguina/desktop/b.txt
mv abc.txt hello.txt
```

| touch | used for create file and update time of existing file. |
|----|---------------------------------------------------|
```
touch <file_name >
examples:
touch abc.txt
```

| cat | concatenate files and print on the standard output. |
|----|---------------------------------------------------|
```
cat <file_name >
examples:
cat abc.txt
```

| alias | It’s use for change long code to short code by defining a simple name/variable. |
|----|---------------------------------------------------|
```
alias <new_name= existing file/diractory name>
examples:
alias dd="cd desktop"
alias hh="cd home"
unalias dd [for remove alias]
```

| vi | Vi is a text editor. |
|----|---------------------------------------------------|
```
vi <file_name>
examples:
alias bhavin
alias abc
- i = insert operation(write or remove)
- esc + :q quite file
- esc + :q! quite without save
- esc + :wq save and quite
- :n(1,2,3,.....) number of row you want  to jump
-  / search
```

| chmod | it’s used for set the read, write and execute permission for user,groups,and other users. |
|----|---------------------------------------------------|
```
chmod [option] <file_name>
examples:
chmod 740 bhavin
chmod 760 abc
```

| tar | create an archive file or directory. |
|----|---------------------------------------------------|
```
tar [option] <achive_name> <file | dir to achive>
examples:
tar cvzf bhavin.tar.gz /
tar cvzf bhavin.tar.gz --transform 's/abc/bhavin/'

unzip
tar xvzf bhavin.tar.gz -C /ubuntu/dell/home/Downloads/

for creating a file
–	for tar file (cvf)
–	for tar.gz (cvzf)
–	for tar.bz2/(cvjf)
–	for tar.tbz (cvfj)
–	for permission check (tvf)

for executing the file/directory
–	for tar file (cvf)
–	for tar.gz (cvzf)
–	for tar.bz2/(cvjf)
–	for tar.tbz (cvfj)
–	for permission check (tvf)
```

| chown | change owenership |
|----|---------------------------------------------------|
```
tar [option] [owner]:[group] <file_name>
examples:
sudo chown root:bhavin abc.txt
sudo chown root:root abc.txt
```

| git int | if your directory is not in git repository then initialize with git int. | 
|----|---------------------------------------------------|
```
git int
examples:
git int
```

| git config | add user name to your git repository. | 
|----|---------------------------------------------------|
```
git config --global user.name "<username>"
examples:
git config --global user.name "bhavin patel"
```

| git config | add email address to your git repository. | 
|----|---------------------------------------------------|
```
git config --global email.name "<email_id>"
examples:
git config --global user.name "bhavin@gmail.com"
```

| git clone | connect your repository and clone in local(copy path in .http). | 
|----|---------------------------------------------------|
```
git clone -- "path"
examples:
git clone --"https://github.com/dipenpatel235/LinuxTraining.git"
```

| git clone | connect your repository and clone in local(copy path in .http). | 
|----|---------------------------------------------------|
```
git clone -- "path"
examples:
git clone --"https://github.com/dipenpatel235/LinuxTraining.git"
```

| git pull | Download the data from your online repository to local | 
|----|---------------------------------------------------|
```
git pull
examples:
git pull
```

| git status | check the status of your pulled/updated data. | 
|----|---------------------------------------------------|
```
git status
examples:
git status
```

| git commit | Commit your file to git. | 
|----|---------------------------------------------------|
```
git commit [option] <"comment name">
examples:
git commit -m "sample add"
```

| git push | update your code in your online repository. | 
|----|---------------------------------------------------|
```
git push
examples:
git push
```

| scp | copy file one system to another system.| 
|----|---------------------------------------------------|
```
scp [option] <source location> <destination>
examples:
scp -r ./patel ubuntu@192.168.1.148:/home/dell/
```
