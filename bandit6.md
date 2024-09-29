The password for the next level is stored somewhere on the server and has all of the following properties:

    owned by user bandit7
    owned by group bandit6
    33 bytes in size

So we use the command 'find / -type f -user bandit7 -group bandit6 -size 33c' to find the file but we have many file have the permission denied.

![image](https://github.com/user-attachments/assets/03241dbb-f818-42d9-8e75-ceaf01e96da4)

'/' to find from root 

find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null

2>/dev/null to the find command is used to suppress any error messages, particularly those related to permission issues when searching through directories that the user doesn’t have access to

![image](https://github.com/user-attachments/assets/60f73023-45dc-45ce-8e13-d684353fd3d6)

So cat this file and we have the password for bandit7!

![image](https://github.com/user-attachments/assets/af1a3d55-d181-4644-b5cc-ba8d819e61a5)

