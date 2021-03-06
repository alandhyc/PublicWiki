---
title: Intro to the Command Line and Plant Sciences Cluster
author: Anne Thomas
date: 21-Jul-2020
---

# Intro to the Command Line and Plant Sciences Cluster

This was a class taught by Anne Thomas on 21 July 2020 covering the basics of using the command line and BASH, along with how to access and use the Plant Sciences Department high-performance computing cluster.

Here is some info from an email before the class on getting access to a Linux/Unix terminal in order to follow the commands in the tutorial:

I’m planning to provide some hands-on opportunities so if you’d like to work along, you’ll need access to some kind of Linux/Unix terminal (command line). 

Here are some options: if you have a Mac or Linux operating system, the terminal is already built into the system. If you have Windows 10, you can install the free Linux subsystem shell, which is what I use (the Ubuntu version). It opens as a command line terminal within your normal operating system (while maintaining a separate file/directory structure). Instructions for installing are [here](https://www.windowscentral.com/install-windows-subsystem-linux-windows-10) (hopefully still up to date). There are also other third-party softwares but this is pretty easy. (Windows also has its own terminal, but it’s a different system and not as widely used.)

If you don’t have or want any of those options, there are online simulated terminals, for example [Cocalc terminal](https://cocalc.com/doc/terminal.html), which I’ve never tried, but feel free to do that.

Department cluster: If you have an account on the department cluster already, great. You can access that via ssh (which I’ll go over) on any Linux/unix terminal. Alternatively, on Windows, you can download [PuTTY](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html), a simple shell for accessing remote computers (it can’t do much else). 

If you don’t already have an account and would like one, you’ll have to request an account via the cluster tech support at computing@plantsci.cam.ac.uk . However, since they’re in the middle of a tech support transition I have no idea how available they are to set that up at this short notice (sorry I didn’t suggest it earlier). It’s worth a shot but no guarantees. 

For using the cluster, I would also recommend downloading some kind of file transfer software. It’s essential on windows, which as far as I know doesn’t allow file transfer from remote Unix systems via the command line (although the Ubuntu subsystem might); on other systems it’s just a convenience. I use [WinSCP](https://winscp.net/eng/download.php) but there’s also filezilla and others. This isn’t crucial for the tutorial, though.
