# Memory Leak Checker 42 Rocks
Test your peers code with a remote server using valgrind.
I wrote this because valgrind has problems on our macs and `leaks` (`man leaks`) is sometimes just not enough.

This requires zip (unzip), valgrind, make and gcc to be installed on your remote server. 
Also, it is required to authenticate with your server via ssh key auth.  

Please fill out the variables with your values.  
Also, this script relies on you having a makefile.  
