# Lambda School Web API: Java Course 
## Software installations for Week 1 

<details><summary>For All Operating Systems</summary>
<p>

### To be done after installing the software for your specific operating system

[![Video to Install JDK](http://img.youtube.com/vi/OswS2dkvjnU/0.jpg)](http://www.youtube.com/watch?v=OswS2dkvjnU)

The Jet Brains IntelliJ IDEA Ultimate Version is installed from your GitHub Student Package. We do need the Ultimate Version for the class. When installing, taking the defaults is the best way to proceed.

This video shows how your instructor has configured his IDE. You may have your own preferences.

Some notes on configuration:

* Under Code Folding, only the show Code Folding Menu should be checked
* All Braces placement should say Next Line
* All places should say Force Braces
* Only Annotations should be wrapped
* Remember to connect your GitHub profile to IntelliJ

</p>
</details>


<details><summary>For Windows 10 Operating System</summary>
<p>

### Install JDK Version 11 on a Windows 10 based computer

[![Video to Install JDK](http://img.youtube.com/vi/XQfRnglIcYE/0.jpg)](http://www.youtube.com/watch?v=XQfRnglIcYE)

The basic steps to installing the software are:

* Download and install the Windows software from:  
[https://www.oracle.com/technetwork/java/javase/downloads/jdk11-downloads-5066655.html](https://www.oracle.com/technetwork/java/javase/downloads/jdk11-downloads-5066655.html)

Note that you have to accept the licensing agreement before you can download the software
* add to environment variable JAVA_HOME C:\Program Files\Java\jdk-11.0.2
* add to path C:\Program Files\Java\jdk-11.0.2\bin

To test the installation
* java -version
* javac -version

---
### Install the Sublime Text Editor on a Windows 10 based computer

[![Video to Install Sublime](http://img.youtube.com/vi/Rk6sm0i2luE/0.jpg)](http://www.youtube.com/watch?v=Rk6sm0i2luE)

Download and install the Windows software from
[https://www.sublimetext.com/](https://www.sublimetext.com/)

---
### Install Git Bash on a Windows 10 based computer

[![Video to Install Git Bash](http://img.youtube.com/vi/QElJOX2wdfc/0.jpg)](http://www.youtube.com/watch?v=QElJOX2wdfc)

Surf to the site [https://gitforwindows.org/](https://gitforwindows.org/)

Download and install the software

To configure Git, enter the following from a command prompt
* git config --global user.name " < Your Name > "
* git config --global user.name " < Your GitHub email address > "

---
</p>
</details>


<details><summary>For Mac OS</summary>
<p>

### Install Homebrew on a Mac OS computer

[![Video to Install Homebrew](http://img.youtube.com/vi/51jnG_-_7tE/0.jpg)](http://www.youtube.com/watch?v=51jnG_-_7tE)

To install Homebrew, first install the Xcode CLI. Alternatively, install the full Xcode software provided by Apple.
* To install the Xcode cli, from a terminal prompt enter  
```xcode-select --install```
* To install Homebrew, from a terminal prompt enter  
```ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```
* To test the Homebrew installation, from a terminal prompt enter  
```brew doctor```

---
### Install JDK 11 on a Mac OS computer

[![Video to Install JDK 11](http://img.youtube.com/vi/SEhvkT_eQ5k/0.jpg)](http://www.youtube.com/watch?v=SEhvkT_eQ5k)

Download and install the dmg software from [https://www.oracle.com/technetwork/java/javase/downloads/jdk11-downloads-5066655.html](https://www.oracle.com/technetwork/java/javase/downloads/jdk11-downloads-5066655.html)
In order to download the software, first accept the licensing agreement.

To configure the software
* determine the java home path. From a terminal prompt enter  
```/usr/libexec/java_home -v11```
* Go to your home directory. Enter  
```cd``` 
* Edit your user profile. Enter  
```nano .bash_profile```
* At the end of the file, add  
```export JAVA_HOME="<directory found earlier>"```
* Exit nano and restart your computer.

To test the software, from a terminal prompt enter
* java -version
* javac -version
both should respond with version numbers

---
### Install Sublime Text edit on a Mac OS Computer

[![Video to Install Sublime](http://img.youtube.com/vi/XvgrHxmNsvQ/0.jpg)](http://www.youtube.com/watch?v=XvgrHxmNsvQ)

Surf to the website [https://www.sublimetext.com/](https://www.sublimetext.com/) and install the software

---
</details>


<details><summary>For Linux specifically Ubuntu 18</summary>
<p>
  
### Install JDK Version 11 on a Linux Computer

[![Video to Install JDK](http://img.youtube.com/vi/LRBot07vRsU/0.jpg)](http://www.youtube.com/watch?v=LRBot07vRsU)

From a terminal prompt, enter 
* sudo add-apt-repository ppa:linuxuprising/java
* sudo apt update
* sudo apt install oracle-java11-installer
* sudo apt install oracle-java11-set-default

To test the installation, enter
* java -version
* javac -version   
Both should respond with version numbers

---
### Install Sublime Text Editor on a Linux Computer

[![Video to Install Sublime](http://img.youtube.com/vi/SgdmgSasU30/0.jpg)](http://www.youtube.com/watch?v=SgdmgSasU30)

From a terminal prompt, enter 
* wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
* echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
* sudo apt update
* sudo apt install sublime-text

---
### Install Git on a Linux Computer

[![Video to Install Git](http://img.youtube.com/vi/3kh_c9Os_z4/0.jpg)](http://www.youtube.com/watch?v=3kh_c9Os_z4)

From a terminal prompt, enter
* sudo apt upgrade
* sudo apt install git

To configure Git, enter the following from a terminal prompt
* git config --global user.name " < Your Name > "
* git config --global user.name " < Your GitHub email address > "

---
</p>
</details>
