---
title: How to Connect to Cluster
layout: default
images: []
tags: [Login, Setup, Configuration, Windows, Mac, Linux]
---

***


 Table of Contents  

 1. [Using Windows](#using_windows)  
     * [Install SSH Client \(PuTTY\)](#windows_ssh) 
     * [Connected to Universtiy Network](#windows_connect)  
     * [Connected to off-campus Network](#windows_off_campus)  
         * [Installing Pulse Client ](#windows_vpn)
         * [Connect Using VPN and PuTTY](#windows_vpn_connect)
 2. [Using Mac](#using_mac)
 3. [Using Linux](#using_linux)  


## <a name="using_windows"></a> Using Windows
***

#### <a name="windows_ssh"> </a>Install a SSH client

First we need to install an ssh client. We will be using [PuTTY](https://www.putty.org) for this tutorial. 

*[Follow these instructions to get PuTTY running on your windows machine](https://www.ssh.com/ssh/putty/windows/install)*
   

#### <a name="windows_connect"> </a>Connect from university network 

***Note: The following steps are only applicable if connected to the university network. If connecting through off-campus internet, follow the instructions in the next subsection***

1. Open a new PuTTY session
2. Type in your *username*@spiedie.binghamton.edu in the Host Name (or IP address) text field 
	
	(Add image of putty terminal to help user)
	(image#1)
	Caption: putty log in
3. Click Open or press enter
4. Type in password (your typed characters will remain hidden on the screen)


[//]: # Include image of logged in session
(image#2)
Caption: Logged in session 

#### <a name="windows_off_campus"></a>Connect from off-site internet / remote connection 

***Note: Take the following steps if logging in from off-campus***

#### <a name="windwos_vpn"></a> Install Pulse Secure VPN

1. Go to [ssl.binghamton.edu]( https:ssl.binghamton.edu) and log in using your PODS DOMAIN ID and follow the steps to install Pulse Secure for Windows 

	(Add image of ssl landing page and circle pulse secure for windows link	)

#### <a name="windows_vpn_connect"> </a>Connect using VPN and PuTTY

1. Follow the installation instructions on Pulse Secure for Windows to start a new connection to ssl.binghamton.edu

	(possibly attach the pdf to this site permanently so we can add a hyperlink to the pdf available)
2. Once connected to the VPN, follow the same steps the university network access to log in to Spiedie. 


## <a name="using_mac"> </a> Using Mac

***



##  <a name="using_linux"> </a> Using Linux

***
