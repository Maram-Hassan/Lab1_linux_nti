# Lab1_linux_nti
1.	cat the file /etc/passwd and notice the different fields. Extract your info from it.
![Screenshot from 2024-09-24 20-39-51](https://github.com/user-attachments/assets/f5d34c69-bf21-4120-b072-829cc2f04fe9)

2.	What is the difference between cat and more command.
```
#cat command
```
![Screenshot from 2024-09-24 20-39-51](https://github.com/user-attachments/assets/f5d34c69-bf21-4120-b072-829cc2f04fe9)

```
#more command 
![Screenshot from 2024-09-24 20-41-50](https://github.com/user-attachments/assets/61aefa64-e4e6-4af0-90f4-e96b613efc84)
```
3.	What is the difference between rm and rmdir using man?
```
#rm command
```
![Screenshot from 2024-09-24 20-42-26](https://github.com/user-attachments/assets/c76ab2c6-7b09-4995-adfc-e23853628b90)

```
#rmdir command
```
![Screenshot from 2024-09-24 20-42-37](https://github.com/user-attachments/assets/b5a8505d-1aff-47da-91e8-2c17079167c6)

4.	Create the following hierarchy:

 
![Screenshot from 2024-09-24 22-17-15](https://github.com/user-attachments/assets/4e01eee3-4695-4176-b051-a97bd0d1ea14)
a.	Remove dir11 in one step. What do you notice?  And how to overcome that?
![Screenshot from 2024-09-24 22-28-15](https://github.com/user-attachments/assets/b8db6801-14a3-4b23-94a6-16ac926adbdc)

b.	Then remove dir12 using rmdir –p command. State what happened to the hierarchy (Note: you are in your home dir).

5.	Copy the passwd file to your home directory making its name is mypasswd.
![Screenshot from 2024-09-24 22-42-59](https://github.com/user-attachments/assets/20392121-452a-4bb2-8b5e-65ca8ff70f6a)
6.	Rename this new file to be oldpasswd.

7.	The output of the command pwd was /home/guest50. Write the absolute and relative path for the file mycv
```
#absolute path
/home/guest50/mycv
#relative path
mycv

```
8.	You are in /usr/bin, list four ways to go to your home directory.
```
cd ~
cd $HOME
cd /home/username

```
9.	Display the first 4 lines of /etc/passwd.

![Screenshot from 2024-09-24 20-48-21](https://github.com/user-attachments/assets/eca2e60a-075e-4bad-8c1d-24df3bc077d5)

10.	Display the last 7 lines of /etc/passwd

![Screenshot from 2024-09-24 20-47-49](https://github.com/user-attachments/assets/192d0dbb-6e11-4600-b828-baec1004e1be)

11.	Display number of user accounts in the system.
![Screenshot from 2024-09-24 21-19-45](https://github.com/user-attachments/assets/39e473df-04d5-4dfb-82d4-9b78d422a147)
12.	Display the users who are logged now to the system.
![Screenshot from 2024-09-24 21-19-27](https://github.com/user-attachments/assets/6cab3f20-34b4-4a16-b019-a76293de0426)

13.	Display the man pages of passwd the command and the file sequentially in one command.

![Screenshot from 2024-09-24 21-20-17](https://github.com/user-attachments/assets/11ba4ea9-4b83-4b14-944c-5c949ad73bbe)
![Screenshot from 2024-09-24 21-20-24](https://github.com/user-attachments/assets/8968ac70-d931-4c55-bf25-89f0ae212c89)
![Screenshot from 2024-09-24 21-20-29](https://github.com/user-attachments/assets/1faa5257-faba-4f69-b028-94b1ed17481a)
14.	Display the man page of the passwd file.
```
man 5 passwd
```
![Screenshot from 2024-09-24 20-59-43](https://github.com/user-attachments/assets/b88c0519-a983-4041-83f6-d0da592e01c8)

15.	 Display a list of all the commands that contain the keyword passwd in their man page.

![Screenshot from 2024-09-24 22-33-17](https://github.com/user-attachments/assets/7c4e452b-005c-4ba3-bcf8-7ab2046934a2)

16.	Using vi write your CV in the file mycv. Your CV should include your name, age, school, college, experience…
```
vim mycv
```

17.	Open mycv file using vi command then: ( state how to)

a.	move the cursor down one line at time
```
esc mode
j
```
b.	move the cursor up one line at time
```
esc mode
k
```
c.	search for word age
```
esc mode
/age
```
d.	Step to line 5 (assuming that you are in line 1 and file is more than 5 lines)
```
5G
```
e.	Delete the line you are on and also line 5.
```
dd
```
f.	How to step to the end of line and change to writing mode in one step.
```
Shift + a
```







