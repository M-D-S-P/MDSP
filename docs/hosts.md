# Fix Hosts File

Normally when the sign in button does nothing, "Authentication servers are down for maintenence", or "Switch to mojang mode" shows up, it's due to a modification to the hosts file that redirects the sign in request to a different website, which is caused by an illegal alt generator like MCLeaks. To fix this, remove MCLeaks or any other account generators (If you still have it, if not, just skip this step), and then do the following steps.

## Windows

> **1)** Go to the Start Menu and locate notepad. Right click notepad and select Run as Administrator 
> **2)** Press *File*, then *Open*. Type `%SystemRoot%\System32\drivers\etc\hosts` as the File name and press *Open* again
> **3)** Remove every line mentioning 'Mojang' and hit save (Ctrl+S).
> You should now be able to play Minecraft again, please never use any illegal tools or accounts again.  


## MacOS

> **1)** Press ⌘ + space and type `Terminal` into spotlight, then press enter on the terminal app 
> **2)** Type in `sudo nano /etc/hosts` It will ask for your password, this is so that it can edit a system file. It will not show the password as you are typing it for security reasons, but it is receiving the input.
> **3)** Remove every line mentioning 'Mojang' using the arrow keys to navigate
> **4)** Press Ctrl+O, then enter 
> **5)** Close terminal

 ---
You should now be able to play Minecraft again, please never use any illegal tools or accounts again. 
It is highly recommended to sign in and change your password 

Here is an example of a hosts file:
![Example Image](https://imgur.com/a/E8qLgqs)