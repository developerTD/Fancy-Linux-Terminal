# Fancy-Linux-Terminal
# How to Stylize your bash terminal like Konsole, Gnome terminal or Terminator for Absolute Beginner.
# For Fancy Terminal to work well you'd also need to install powerline fonts.
#####################################################################################################
__________________________
Installing poerline fonts
__________________________
sudo apt install fonts-powerline

____________________________________
Setting up powerline fonts for bash
____________________________________

Open your terminal, logged in as user.

Open .bashrc file in nano editor by typing the following command 
nano .bashrc

Now you have your .bashrc file opened. Be cautious here. Messing your .bashrc files can have serious consequences
Scroll down to the bottom of the file using cursor keys
Now add a blank line, and then paste the contents of fancy-bash-prompt.sh from FUNCTIONS at line 71 to the end of the script
Remember to add a comment about your changes or backup your .bashrc
To paste the contents in nano use ctrl+shift+v.
Now write out the changes press ctrl+O and enter
And exit press ctrl + x
