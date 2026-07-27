# Making your OWN Minecraft server

Interested in making your own Minecraft server? Don't worry, it's easier than you think! You're totally in the right place!

## A guide on how to make a Minecraft server easily.

### 1: Preparation

First you will need a machine (the host) specifically for your server to be running on. It can either be your main PC or a secondary PC. You can use a virtual machine for easier setup, but it isn't recommended because it eats up more resources because it has to run the kernel and a lot of stuff too.

After that you will need to make a USB for installing the operating system on your server machine. [Linux](https://en.wikipedia.org/wiki/Linux) is recommended, especially [Debian](https://en.wikipedia.org/wiki/Debian).

If you are unfamiliar with installing operating systems, you can look here to get started:

- [To create a bootable USB stick on Windows](https://documentation.ubuntu.com/desktop/en/latest/how-to/create-a-bootable-usb-stick/#on-windows)
- [To create a bootable USB stick on MacOS](https://documentation.ubuntu.com/desktop/en/latest/how-to/create-a-bootable-usb-stick/#on-macos)

### 2: Making a Minecraft server

Download a Minecraft server executable such as Paper, Kotlin, Fabric, or the Vanilla server itself. Vanilla is not recommended because the server is not optimized and mod support is super limited to no support at all. I'd recommend Paper since it has lots of plugins supported and it's very stable.

Here are links to server executables that you can use as your choice:

 - [Paper](https://papermc.io/downloads/paper)
 - [Fabric](https://fabricmc.net/use/)
 - [Vanilla (Not recommended. Read line 12)](https://www.minecraft.net/en-us/download/server)

Create a folder in your server that can be named anything, then drag the executable into the folder that is newly created.

**CRUCIAL!!** MAKE SURE YOU HAVE JAVA 21 INSTALLED OR ELSE THE SERVER WON'T LAUNCH!! >:(

After that, you can launch the server and it will create some files and folders. You will need to accept the EULA by changing the eula.txt file to "eula=true", and then you can relaunch the server again and it should work fine.

### 3: Joining/Testing your Minecraft server

To join your Minecraft server, open Minecraft and enter the server IP address in the multiplayer section. The IP address can be 192.168.1.7 or your public IP address if you are hosting it online through playit.gg.
