#### Linux Commands Implementation
## A. Basic Navigation
Current Directory

bash
pwd
![alt text](pwd.png)

# List Root Directory

bash
sudo ls -l /


Navigate to /usr

bash
cd /usr
pwd
## B.  Directory Creation (Side Hustle Task 1)
Create photos directory

bash
sudo mkdir /usr/photos

![alt text](<Screenshot from 2025-06-18 16-23-01.png>)
# Create 3 subdirectories

bash
sudo mkdir /usr/photos/{vacation,family,events}
Verify creation

bash
sudo ls -l /usr/photos

![alt text](<Screenshot from 2025-06-18 16-34-26-1.png>)

# Navigate and show path!

bash
cd /usr/photos/vacation
pwd
![alt text](pwd-1.png)

## C. File Operations
Create test file

bash
sudo touch /usr/photos/example.txt
View file content

bash
sudo cat /etc/os-release
![alt text](<Screenshot from 2025-06-18 16-31-03.png>)

# Copy file

bash
sudo cp /usr/photos/example.txt /usr/photos/example_copy.txt
Move/Rename file

bash
sudo mv /usr/photos/example_copy.txt /usr/photos/renamed.txt
Delete file

bash
sudo rm /usr/photos/renamed.txt

![alt text](<Screenshot from 2025-06-18 16-33-01.png>)
## D. Advanced Commands
Recursive listing

bash
sudo ls -R /usr/photos
Find command

bash
sudo find /home -name "*.txt"
![alt text](<Screenshot from 2025-06-18 16-34-26.png>)
