

# Tool-X v2.0

[![Build Status](https://img.shields.io/github/forks/Rajkumrdusad/Tool-X.svg)](https://github.com/Rajkumrdusad/Tool-X)
[![Build Status](https://img.shields.io/github/stars/Rajkumrdusad/Tool-X.svg)](https://github.com/Rajkumrdusad/Tool-X)
[![License](https://img.shields.io/github/license/Rajkumrdusad/Tool-X.svg)](https://github.com/Rajkumrdusad/Tool-X)
[![Rawsec's CyberSecurity Inventory](https://inventory.rawsec.ml/img/badges/Rawsec-inventoried-FF5050_flat.svg)](https://inventory.rawsec.ml/tools.html#Tool-X)

------------------------------------------------------------------------

### Introduction

*Tool-X is a program installer for Kali Linux tools.*
Tool-X was developed for Termux and other android terminals. Using Tool-X, you can install almost 263 hacking tools in Termux and other Linux based distributions. Now Tool-X is available for Ubuntu, Debian etc.

<p align="center">
<img height="500px" width="500px" src="https://github.com/Kilo-411/Tool-X/blob/master/.sc/Logo.jpg"/>
</p>

------------------------------------------------------------------------

### :cyclone: &nbsp; Operating System Requirements &nbsp; :cyclone:

Tool-X works on any of the following operating systems:<br>
• Android (Using the Termux App) <br>
• Linux (Debian Based Systems) <br>

------------------------------------------------------------------------

### :inbox_tray: &nbsp; How to Install &nbsp; :inbox_tray:

Open the terminal and type following commands.

* `apt update`

* `apt install git`

* `git clone https://github.com/Kilo-411/Tool-X.git`

* `cd Tool-X`

* `chmod +x install.aex`

* `sh install.aex` if not work than use `./install.aex`

------------------------------------------------------------------------

### :fire: &nbsp; How to Use &nbsp; :fire:

Enter a Number for a specific output:
- (0) : To install all tools.
- (1) : To show all available tools and type the number of a tool which you want to install.
- (2) : To show tools category.
- (3) : For the install of the operating system in Termux
- (4) : If you want to update Tool-X.
- (5) : If you want to know About Us.
- (x) : To exit the tool.

<br/>


***Now Tool-X is installed successfully. To run Tool-X Type Tool-X in your terminal.***

Type Tool-X from anywhere in your terminal to open Tool-X.

------------------------------------------------------------------------
To install Metasploit-Framework in TermuX, enter the following commands carefully and one by one in the TermuX (After entering a single command line, don`t forget to press enter, and wait for the process to complete if any).

First of all, we have to install some scripts, for this, enter:
pkg update && pkg upgrade -y && pkg install wget curl openssh git -y

— These pkgs are required for further steps
(Wait till it is Completely installed)

Now we have to go to HOME directory, for this enter:
cd $HOME
To run the newly installed script for installing Metasploit Framework, enter this command:
bash metasploit.sh

This script will install the latest version of Metasploit-Framework script also include some extras to make updating Metasploit faster. If all goes well, i.e. No red colored warnings, you can start Metasploit using the following simple steps:
Now, after the complete installation, you can run Metasploit, by entering this command (anywhere, because shortcut is created by the Script) :
msfconsole

(Optional) This is an all in one script for the installation of MSF in TermuX. Use it if you are busy in other work. Enter the following command, and wait for its complete installation:
pkg update && pkg upgrade -y && pkg install curl wget tsu wget git && wget Auxilus.github.io/metasploit.sh && bash metasploit.sh

— Only, if you are not at Home Directory
Now, we have to install a script for Completely Installing All-in-One Metasploit Package. For this, enter:
wget Auxilus.github.io/metasploit.sh

:warning: &nbsp; **Warning** &nbsp; :warning:

I am ***NOT*** expert, so use this tool at your own risk!

