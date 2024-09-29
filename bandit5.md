The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

    human-readable
    1033 bytes in size
    not executable

We have the command 'du' . It help our to show the size of file . -b show the size by bytes, -a to write counts for all files, not just directories

![image](https://github.com/user-attachments/assets/5f230d3a-e18f-444f-9894-4e2cfe34936c)

We use grep 1033 to match the size and luckily, we just have 1 file. Yeahhhhhhh

So cat this file and we will have the password for the bandit6
![image](https://github.com/user-attachments/assets/4775d8e0-5d61-45c1-8164-a9f64387db8a)

