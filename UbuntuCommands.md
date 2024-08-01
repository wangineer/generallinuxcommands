How to add user to Ubuntu
https://www.digitalocean.com/community/tutorials/how-to-add-and-delete-users-on-ubuntu-20-04
  adduser newuser
   - 'newuser' is the name of the user you just created


How to add new user to sudoers file
https://stackoverflow.com/questions/47806576/username-is-not-in-the-sudoers-file-this-incident-will-be-reported

Modify the sudoers File
  su root 
  nano /etc/sudoers
> Or you can do the below as a quick as above
  > sudo visudo   <<<< Does the same thing

"user_name" = name of the user you created in step above
  Find the "admin" group
    user_name ALL=(ALL)  ALL   <<<< Make sure you modify the "username" to the name you created in above step.



how to install webP for linux to modify images
https://www.tecmint.com/convert-images-to-webp-format-in-linux/
