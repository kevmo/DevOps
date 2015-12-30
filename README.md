Rapid and reliable software development and deployment processes for everyone: developers, sysadmins, and designers. But this is DevOps for the Developer.

That app ain't gonna run itself.
--------------------------------

What happens when you're developing an web app locally and you run `python app.py` or `node index.js`? If conditions are right, the app spins up and you can examine your output via localhost on a port of your choosing. But what are those conditions? How does the same app get to YourCompanysWebsite.com? 

DevOps is a movement to take these deployment concerns into consideration during all phases of software development. When individual developers code with an eye on this, the entire team writes better software faster. It is the front-end, back-end, and sysadmins [working together to share troubleshooting information across their silos](http://www.drdobbs.com/architecture-and-design/what-exactly-is-devops/240009147).

Basics
==========

Machine: You need an operating system
-------------------------------------
If you're reading this, you probably understand what application software is.  It's that Express app that you've spun up.  But application software can't run itself in a vacuum. It needs a system in which to run. An operating system is basically the app that runs your app. 

Windows, Mac OS, iOS, Android, Blackberry are all examples of operating systems. And then there's Linux.

_Linux_
Linux is the operating system that runs on more hardware platforms than any other operating system and a triumph of the open source software movement. It is [Unix-like](https://en.wikipedia.org/wiki/Unix-like) and mostly [POSIX](https://en.wikipedia.org/wiki/POSIX)-compliant.

To become a master of your own destiny, [you must become comfortable with the bash command line Linux ships with](https://github.com/jlevy/the-art-of-command-line).  


Provisioning: That operating system needs software to run your program
----------------------------------------------------------------------

Your personal computer

Vagrant

EC2

Deployment: Your app needs to live in a publicly accessible machine
----------------------------------------------------------------------
ssh

the cloud

nginx, Apache

Do It Again and Again and Again
========================================================
* [Continuous Integration](https://en.wikipedia.org/wiki/Continuous_integration)

Automated Configuration
-----------------------

Ansible

Continuous Integration
---------------------

Travis

Get Smart
=========

Microservices vs Monoliths
--------------------------

Useful Links
===========
* [List of Build Automation Software](https://en.wikipedia.org/wiki/List_of_build_automation_software#Build_script_generation_tools)







