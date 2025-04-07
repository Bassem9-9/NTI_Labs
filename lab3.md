### 1. Create a user account with the following attribute
    username: “your first name”
    Fullname/comment: “full name”
    Password: islam
   
![Screenshot (100)](https://github.com/user-attachments/assets/5a2425ca-7eea-4f12-98f4-3591795ee9c6)

### 2. Create a user account with the following attribute
    Username: baduser
    Full name/comment: Bad User
    Password: baduser

![Screenshot (101)](https://github.com/user-attachments/assets/c05fc6a8-b2be-4655-9784-55c1e757cb02)

### 3. Create a supplementary (Secondary) group called pgroup with group ID of 30000
![Screenshot (102)](https://github.com/user-attachments/assets/3c8ed2ec-e1d7-40a2-b3d3-789df59104c2)

### 4. Create a supplementary group called badgroup
sudo groupadd badgroup

### 5. Add bassem user to the pgroup group as a supplementary group
sudo usermod -aG pgroup bassem

### 6. Modify the password of bassem's account to password
sudo passwd bassem

### 7. Modify islam's account so the password expires after 30 days
sudo chage -M 30 bassem

### 8. Lock bad user account so he can't log in
sudo usermod -L baduser

### 9. Delete bad user account
sudo userdel baduser

### 10. Delete the supplementary group called badgroup
sudo groupdel badgroup

### 11. Create a folder called myteam in your home directory and change its permissions to read only for the owner.
![Screenshot (103)](https://github.com/user-attachments/assets/c018aa5c-8a8c-4b1d-88d2-0b8c80446ad4)

### 12. Log out and log in by another user
su bassem

### 13. Try to access (by cd command) the folder (myteam)
![Screenshot (105)](https://github.com/user-attachments/assets/56faf53e-9e24-4ef7-815b-cc6f1f032782)

### 15. Starting from your home directory, find all files that were modified in the last two day.
![Screenshot (106)](https://github.com/user-attachments/assets/2852b87e-21b7-4f1b-8b21-545bf9b6c8b2)

### 16. Starting from /etc, find files owned by root user.
![Screenshot (107)](https://github.com/user-attachments/assets/d9c82832-cacb-481a-bd6d-c311cb0ef9b5)

### 17. Find all directories in your home directory.
![Screenshot (108)](https://github.com/user-attachments/assets/c4e8a69a-f239-4ef5-8a03-24e68d16aebe)

### 18. Write a command to search for all files on the system that, its name is ".profile".

### 19. Identify the file types of the following: /etc/passwd, /dev/pts/0, /etc, /dev/sda
![Screenshot (109)](https://github.com/user-attachments/assets/6a8805f9-5ac5-4c00-a67b-ca8da5367193)

### 20. List the inode numbers of /, /etc, /etc/hosts.
![Screenshot (110)](https://github.com/user-attachments/assets/88046fba-b30f-40ee-8a49-51da4902017a)

### 21. Copy /etc/passwd to your home directory, use the commands diff and cmp, and Edit in the file you copied, and then use these commands again, and check the output.



