# 如何设置你的Linux系统来进行URCap的开发

为了设置你自己的Linux系统来进行URCap的开发，请确保具备以下先决条件:

* x64 based Linux distribution, e.g. Ubuntu LTS 16.04
* Ensure system is up to date
   > sudo apt-get install update
* Rename hostname of the machine to "ursim". 
   Respectively by changing the hostname in: 
   >etc/hostname and etc/hosts
* Java - OpenJDK 8 SDK
   > sudo apt-get install openjdk-8-jdk
* Maven
   > sudo apt-get install maven
* Runit
   > sudo apt-get install runit
   1. Executing this in Ubuntu-versions later than 14, will make the installation fail. 
   However this step is required. 
   2. Comment out the last 3 lines in the file:
      > /var/lib/dpkg/info/runit.postinst
   3. Continue the installation:
      > sudo dpkg --configure -a
   4. Runit will now be successfully installed.
* Install the following packages: 
   > sudo apt-get install libxmlrpc-c++8v5 libxmlrpc-core-c3
* Optionally, you can install the text editor VIM:
   > sudo apt-get install vim
* Reboot