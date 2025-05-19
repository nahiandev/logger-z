## LoggerZ

A simple keylogger written in C++

### Disclaimer: This project is made for knowledge and learning purpose. I am not responsible for any damage , information leakage caused by this project on your computer or you do it on someone else's.

### Steps to build & run _**LoggerZ**_

- Download the _**LoggerZ**_ source code
- Compile the source code with GCC or MSVC
- Run the executable either from your favourite code editor or command line

Once after running _**LoggerZ**_ , open the Task Manager and you see a process running like this.

![LoggerZ](https://github.com/nahiandev/logger-z/blob/main/screenshots/running_task.png)

Having _**LoggerZ**_ running on a system , you will see a _.log_ file in the directory where the _**logger-z.exe**_ is located. This file will contain the keystrokes you type.

![LoggerZ](https://github.com/nahiandev/logger-z/blob/main/screenshots/data_capture.png)
This file will store all the keystrokes you have made previously.

### Let's have some fun using _**LoggerZ**_

Think of a situation when you need to get all the received keystrokes by a user from a Windows system everytime the system runs. You can do this by using _**LoggerZ**_. All you have to do is:-

- Navigate to `C:\Windows\System32` and create a folder named `Records`. You can also create this `Records` wherever you want , but make sure it can't be found easily.
- Put the `logger-z.exe` file in the `Records` folder.
- Create a shortcut of `logger-z.exe`.
- Press `Win+R` , type `shell:startup` and hit `Enter`.
- Paste the shortcut inside the newly opened file explorer window.

This will run _**LoggerZ**_ everytime the system starts and the `CapturedData.log` file will capture every keystrokes user makes.

### Install _**LoggerZ**_ once in a system and have fun.

_**[Ibne Nahian](www.facebook.com/nahiandev)**_
