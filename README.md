# Ex-01-Linux-Commands


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

 
![423345289-0c2ffce6-15cb-42b6-ac38-a0b59f7e08b5](https://github.com/user-attachments/assets/5955c4ec-64aa-46f7-9e5a-af4c02e33c85)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd


![423345356-e95ef8da-d21d-4d33-8cce-83a2ab9015d0](https://github.com/user-attachments/assets/9362acce-19f3-4e7d-ad08-f861da1c6591)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>


![423345452-96f485da-f1c9-4a70-bba6-2fc2c29218c3](https://github.com/user-attachments/assets/bcff6972-f67a-4f20-802f-b831293741e8)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>


![423345531-97b07dc5-0afe-406b-8bfa-905066493996](https://github.com/user-attachments/assets/3316d705-4b6b-456a-be7b-5c2ab5363102)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>


![423345590-454e9302-1482-470c-980c-10821295aaea](https://github.com/user-attachments/assets/764f8db4-f06a-4560-95e9-050ac2e7f19b)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..


![423345656-4cb6dd6d-3574-4a5a-b9c5-509e0528111d](https://github.com/user-attachments/assets/9be525ce-897f-4ffb-9a01-d98406cb9ee3)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>


![423345803-141b710e-b61f-4885-b6b8-3df660954dad](https://github.com/user-attachments/assets/7f4edff2-9ff8-4b95-a340-53dc86c6fdf9)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

ile_name
ile_name
Syntax: gedit file_name


![423345874-15212d10-aaf4-4825-a891-a5cbd8c37e91](https://github.com/user-attachments/assets/be33f68f-04be-4497-bf2f-a4aa45e14799)



### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>


![423345947-e7fa5777-34b4-44df-a165-240614aad20d](https://github.com/user-attachments/assets/c76ab26f-f17e-4543-9ed8-c5c820de69cd)


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>



![423346094-9deaa267-cb8b-4a38-9a43-1e53caca6410](https://github.com/user-attachments/assets/275fdf4b-73a5-4169-af1a-a276dc725303)


 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files


![423346158-9ad524f5-b696-476c-8af4-e1b60c6787b9](https://github.com/user-attachments/assets/57dd9833-40ad-423d-9fa9-1d4e5f6f649f)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>


![423346276-fd7ff4d0-eb12-4e57-a7f9-056891be2162](https://github.com/user-attachments/assets/212a4ca7-2d66-4fff-8f1e-770edfadfee3)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>



![423346409-930d3b24-637e-492b-bfa7-3d3878582897](https://github.com/user-attachments/assets/5fefa2b4-c285-444d-b1ca-0196ce51df45)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id



![423346465-3adee7cd-9c58-4c85-94e1-2eb9e3a16d90](https://github.com/user-attachments/assets/262d8f93-e3af-48ee-9b49-d1e70905df5a)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>


![423346524-3a1c7bde-79e6-4bd7-8720-cbcec925d51d](https://github.com/user-attachments/assets/f740b3e4-57a9-4b9a-964d-55bcb6201c93)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>


![423346594-3fc0f50a-cb67-47be-9130-cd046483eb49](https://github.com/user-attachments/assets/3964117b-2211-4343-9a97-1626fa7c3207)

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name


![423346649-bf714dcc-4c92-43bc-90b9-aaf05cfd03d1](https://github.com/user-attachments/assets/1c44dd13-3fdd-4d65-aab9-8dc42f66a677)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….


![423346685-c8f33471-e813-4e15-859c-896f35c13522](https://github.com/user-attachments/assets/ca40ad0a-c3ee-45e1-9431-98cf39d165c0)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]


![423346804-d518579e-0b50-4dea-8eb9-695aca3471b4](https://github.com/user-attachments/assets/2a3f796e-3ec9-4ccc-bb75-2c34ec62f665)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>


![423347199-7167812f-a122-44b0-a7f5-5068b93d3805](https://github.com/user-attachments/assets/ae4fe0c9-c90a-49e9-909d-7de6a891a69d)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..


![423347240-6e2d399c-58b2-46a0-baf6-fbb0fe343b15](https://github.com/user-attachments/assets/964d75b1-0e52-4ee2-a740-6c32ab7aef99)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>


![423347321-ac7758d1-4991-4c8f-98e8-2f5f54c4116d](https://github.com/user-attachments/assets/d2ca4983-dcd8-4f23-a69f-a698192ca238)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal


![423347540-44dcf7c6-9111-4ac1-b686-24ee43a16c74](https://github.com/user-attachments/assets/acd2a8fc-f378-47e2-82c2-81658abebbbb)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear


![423347579-4c1bc740-7859-4600-8e7e-df142efd5a8d](https://github.com/user-attachments/assets/f9f7c90f-78fb-48c4-86e8-91cfa8d2402a)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>


![423347625-60a5c3a7-f700-4bba-96df-6a5fbbbc50df](https://github.com/user-attachments/assets/5804e027-815a-4592-a279-f29b32c08347)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df


![423347676-4e07b3ef-eae6-42ac-966d-477cffe2c80c](https://github.com/user-attachments/assets/0737beaa-3a38-4bf0-a67f-504a8f3854cd)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
