# How to create a file using the Terminal

![laptop pic](https://images.unsplash.com/photo-1508780709619-79562169bc64?q=80&w=2970&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

Terminal is an app designed for developers and more experienced users that enables command line interface (CLI) communication with the Mac OS.


## 1. Open Terminal 

Terminal is a built-in application provided in all Mac OS. Accessing it is very easy:
+ On your Mac, click command + spacebar. 
+ Type Terminal in the search filed.
+ Click enter to access the Terminal. 


## 2. Check your Location

Before everthing, you can check where you are at your device with an easy command:

`pwd` 

This command will show you exactly in which folder or file you are.

***Example***

`/Users/lulwamohd/code/ga/labs`


## 3. Go to home

If you want to create a file in your main page but you are in a different location. You can simply write an easy command that will take you back home. 

`~`


## 4. Create a new directory (folder)

Now that we are in tha main page of our device, lets create a new directory also known as **folder**. To create a new directory follow this command:

`mkdir new.directory`

The `mkdir` is the command used to create a new directory, follows it a space and the directory name you want to give it. In this example it's `new.directory`.

> Note: if you want to create a file inside our new directory don't forget to navigate inside the directory first. By using this command `cd new.directory`.


## 5. Create a File 


Now that we are inside our new directory, we will create a new file. The file command is different than the directory command, it goes as `touch`.

***Example***

`touch new.file`

Similar to what we did with the directory, after `touch` we followed it with space and our new file name, which is `new.file`.

> Tip: in case we want to make sure that our file has been created, type `ls` which stands for ***list*** it will list out all the files or folders inside our directory. 


For more information on how to use Termianl, feel free to check out [MDN web docs.](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Understanding_client-side_tools/Command_line)