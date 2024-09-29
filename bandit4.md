The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is messed up, try the “reset” command.

So what is the the human-readable-file? This is the data that we can read and understand, so that is ASCII or Unicode

So let's go to the bandit4, you see the inhere directory when you use the command 'ls'. cd inhere and you will see 10 file

![image](https://github.com/user-attachments/assets/d2162768-324c-409f-9b53-0fda3a14bfe0)

We can find the password by try to cat every file in directory, ' cat ./-file00' x 10

But we don't do that , we have the command 'file' to show what type of file is.

![image](https://github.com/user-attachments/assets/6f32b240-6d3f-445e-8559-5a6238e2bea1)

But check 10 files makes a lot of time so we use the command file ./* to chech all file in directory

![image](https://github.com/user-attachments/assets/05f39664-7ac3-4ff2-a9d4-80a4467ca086)

We see that the file07 have the type ASCII text. So cat this!

![image](https://github.com/user-attachments/assets/1be42974-514c-47f4-88e8-96c6c470c8c1)

So that is the password for bandit5!


