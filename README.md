# Ex-01-Linux-Commands
# Name: RADHIMEENA M
# Reg No:21223040159

## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

<img width="1477" height="52" alt="image" src="https://github.com/user-attachments/assets/e190de3b-c652-4f51-9ba3-dd943b1ffc08" />

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
<img width="322" height="52" alt="image" src="https://github.com/user-attachments/assets/067b0e9a-539f-4188-b0cf-bc16bb45e4ea" />

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
<img width="202" height="36" alt="image" src="https://github.com/user-attachments/assets/a60ce16d-fddc-4e0b-9e2a-31a064ff1dcf" />

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="225" height="40" alt="image" src="https://github.com/user-attachments/assets/055f2807-b31a-48c9-93c4-03f8cd7af3b6" />

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="235" height="27" alt="image" src="https://github.com/user-attachments/assets/f906a927-a72e-44fa-b28e-f53c37903783" />

### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
<img width="191" height="42" alt="image" src="https://github.com/user-attachments/assets/a76a2ec8-373f-4647-b824-7782b05392fe" />

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
<img width="198" height="88" alt="image" src="https://github.com/user-attachments/assets/519c63a1-c8e8-4ed5-ad4d-33fb2a7d1371" />



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="261" height="56" alt="image" src="https://github.com/user-attachments/assets/68590ccc-fe08-44e5-afde-6302251f71cb" />

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
<img width="216" height="33" alt="image" src="https://github.com/user-attachments/assets/9f6710e1-3439-4e54-9f2c-aec5ba9042fb" />


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

 <img width="252" height="292" alt="image" src="https://github.com/user-attachments/assets/1f4813e7-aad9-44b0-bd72-55ad5fcf0304" />

## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="283" height="172" alt="image" src="https://github.com/user-attachments/assets/56514b5d-8ea7-4d5e-9541-147ba6e4a7d2" />

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
<img width="256" height="145" alt="image" src="https://github.com/user-attachments/assets/b95e1534-330d-42df-a26e-57adcccfd31a" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="335" height="142" alt="image" src="https://github.com/user-attachments/assets/2d9d32c7-6dbf-4b5e-8835-b4f2490d51b0" />
 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
<img width="686" height="68" alt="image" src="https://github.com/user-attachments/assets/bd3ac5f0-470c-4a96-a743-c66ee1370641" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="456" height="177" alt="image" src="https://github.com/user-attachments/assets/95313e13-dd55-43ee-86a2-b97743d85923" />

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
<img width="317" height="200" alt="image" src="https://github.com/user-attachments/assets/625832a1-a0c3-48da-8e64-eea56cef7d6c" />

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>
<img width="331" height="82" alt="image" src="https://github.com/user-attachments/assets/8aa40211-723e-4c50-ad46-ea8e324a02d1" />

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
<img width="260" height="177" alt="image" src="https://github.com/user-attachments/assets/9d82c124-6117-4c14-8d19-962c77a33a1f" />

### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name
<img width="392" height="127" alt="image" src="https://github.com/user-attachments/assets/9ea67c70-f023-46f1-9ba6-0a1edabc5cf0" />

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="255" height="91" alt="image" src="https://github.com/user-attachments/assets/1345fd41-7f5f-4fd0-8bc2-a54d4eeec904" />

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
<img width="510" height="70" alt="image" src="https://github.com/user-attachments/assets/5b8f8423-2a03-437d-a747-f78df5bd6efd" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
<img width="331" height="82" alt="image" src="https://github.com/user-attachments/assets/dd2b5fec-2c05-460b-8d85-ff97d1e61429" />

### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="357" height="72" alt="image" src="https://github.com/user-attachments/assets/3813d6bf-6078-4738-a1dd-e07a753acd6d" />

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="242" height="73" alt="image" src="https://github.com/user-attachments/assets/f476353f-ff69-4a96-8075-f093b6243b09" />

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

<img width="262" height="147" alt="image" src="https://github.com/user-attachments/assets/f8ef1995-f782-4488-ad48-260adfabf94c" />
 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
<img width="232" height="127" alt="image" src="https://github.com/user-attachments/assets/8edf4567-a406-428f-a9fa-1c7c47adffb4" />


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="312" height="37" alt="image" src="https://github.com/user-attachments/assets/91fb819e-8128-44cc-8222-4d96bdf29f77" />

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
<img width="633" height="82" alt="image" src="https://github.com/user-attachments/assets/85fe11f3-7b8f-42ad-874b-ff9cd6c13ff9" />

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
<img width="610" height="215" alt="image" src="https://github.com/user-attachments/assets/4996d171-9fe3-4387-b0b0-05de366499ff" />

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="218" height="67" alt="image" src="https://github.com/user-attachments/assets/1a3128b8-6464-41d1-8bc7-18a544bc90d6" />




















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
