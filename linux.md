# sudo access to initial user
change to root
  su
execute usermod
  /usr/sbin
  usermod -aG sudo $USER
change back to user
  su $USER
  
