# Using-tools-like-John-the-Ripper-for-password-cracking
## AIM:
To crack password hashes using John the Ripper in Kali Linux.

## DESIGN STEPS:
### Step 1:
Install John the Ripper using the command:

### Step 2:
Prepare the password hash file (e.g., using unshadow for Linux password and shadow files).


### Step 3:
Use John the Ripper to crack the hashes:

## PROGRAM:
Password Cracking with John the Ripper

## OUTPUT:
Cracked Passwords from Hash File
# Create a text file 
![image](https://github.com/user-attachments/assets/ee78bdd6-6101-4dd4-86b7-b7c4be932a6b)
# Create a Password-Protected ZIP File 
![image](https://github.com/user-attachments/assets/882f8a80-1c83-4445-a945-6049a81ed018)
# OR
```
zip -e secret.zip file.txt
```
Open John-The-Ripper Tool


![image](https://github.com/user-attachments/assets/b908fead-fd4e-436d-b619-dc5cdf2982c5)
![image](https://github.com/user-attachments/assets/be4b6ac1-308d-482f-9cde-4ac30cb86735)
# Generate Hash Using zip2john
![image](https://github.com/user-attachments/assets/6cdb68b9-5b09-4f08-a06a-b6aafa7e02d7)
# cat hash.txt
![image](https://github.com/user-attachments/assets/40fa396c-295b-4274-9b10-2a43cbd62124)
![image](https://github.com/user-attachments/assets/5058b4e3-4215-4131-b79a-5274484d05ab)

## RESULT:
The password hashes were successfully cracked using John the Ripper.

