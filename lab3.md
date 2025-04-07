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

### 







