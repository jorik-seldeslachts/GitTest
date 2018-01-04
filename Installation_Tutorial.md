# Documentatie Cloud & Automation

## Installations

### Devstack

#### Intro

DevStack's mission is to provide and maintain tools used for the installation of the central OpenStack services from source suitable for development and operational testing. It also demonstrates and documents examples of configuring and running services as well as command line client usage.

tack is an opinionated script to quickly create an OpenStack development environment. It can also be used to demonstrate starting/running OpenStack services and provide examples of using them from a command line.

#### Installation

1. First we need to make a new user 'stack'.

![alt text][Devstack-install-pictures/DevStack_Install_1.png]

2. After we made the new user we need to give that user sudo privileges. When have to change ourself to become the stack user.

![alt text][Devstack-install-pictures/DevStack_Install_2.png]

3. Now we can start downloading the DevStack. After that we change to the devstack directory.

![alt text][Devstack-install-pictures/DevStack_Install_3.png]

4. In this devstack directory we need to create a configurationfile named ' local.conf'. We need to edit this file with the following configuragion in the screenshot below. Remember to chance the password!

![alt text][Devstack-install-pictures/DevStack_Install_4.png]

5. When we are done configuring we just need to run the stack.sh script and the installation will start. This process can take somewhere between 15-20 minutes.

![alt text][Devstack-install-pictures/DevStack_Install_5.png]

6. After the script has finished the installation we can browse to the ip of the virtual machine and we should see the following screen:

![alt text][Devstack-install-pictures/DevStack_Install_6.png]

