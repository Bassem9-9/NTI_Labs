### 1. List **all running processes** and save the output to `~/processes.txt`.  
![image](https://github.com/user-attachments/assets/d20d918a-edf5-498f-a9b5-0e7f89c6bc8f)

### 2. Find the **PID (Process ID)** of the `sshd` service.  
![Screenshot (114)](https://github.com/user-attachments/assets/3b3e763e-d5d6-4135-a18a-d21c4de45343)

### 3. Run a `sleep 500` command in the background, then **kill it** after 5 seconds.  
![Screenshot (115)](https://github.com/user-attachments/assets/3d1f0051-6760-4bb2-8b87-03d5f0146a27)

### 4. **Check if `sshd` (SSH service) is running**. If not, start and enable it.  
![Screenshot (116)](https://github.com/user-attachments/assets/ffaf57d3-b7a4-4909-9171-c4957cb6d7a1)
if it not running        sudo systemctl start ssh

### 5. **Restart the `cron` service** and verify its status.  
![Screenshot (117)](https://github.com/user-attachments/assets/70bcab6e-7949-47fe-a09b-e2e263647995)

### 6. Create a **compressed tarball** (`archive.tar.gz`) of `/var/log` and save it in your home directory.  
sudo tar -czvf ~/archive/tar/gz /var/log

### 8. **Extract** the tarball into `~/logs_backup/`.  
mkdir logs_backups
sudo tar -czvf ~/archives.tar.gz /var/log

### 9. Create a **non-compressed tarball** (`archive.tar`) of `/etc/ssh` and save it in `/tmp`.  





