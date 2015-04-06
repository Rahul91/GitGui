# GitGui

#Introduciton:
A python GUI based application/package, that lets you push a file to your github
easily, without any difficulties.
If you are too lazy to add and commit through command prompt, then this app is for you.

#Installation:
Install it on the go with pip install.

   NOTE : FOR THE NOOB I AM, REMEMBER TO USE A VIRTUALENV WHILE INSTALLING THE CODE :)

         sudo pip install GitGui
and that does the trick for you.

If you are having trouble in installing this package, just configure your pip.conf file.
You should find your pip.conf file here: /home/.pip/pip.conf, however if it is not present, dont panic just make
a file namely pip.conf and put the codes within as showed.
          
          /$ cd .pip
          /.pip$ vim pip.conf
          
Then write the following within pip.conf
         
          [global]
          index-url = https://testpypi.python.org/pypi/

This points, the pip to look the package in test server, that is testpypi and not the actual server, where all the core packages are present. Hope this helps :) 
         

#How to use:
1. Just import the package GitGui
2. And invoke the function gitall().
         
         import gutgui
         gitgui.gitall()

3. Save the program as *.py and execute.


#Utilities:
1. Being a GUI based application, now its easier to push files to your Github repos. Consider this for a moment, through standard process, in order to push a file to your github repo, you need to first initialize git in your current directory, then add a file, then commit it with some message, then you need to configure remote and then you can push it to your remote, thats not all then you have to enter username and password. A long tiring process indeed, therefore a GUI based app that reduces your effort.
         Just add your file, using filebrowser, enter your commit message and repo and you are done.
2. No need for username and password authentication, as github auth token does this job in background for you.
3. If you have by-mistaken entered the incorrect repo name, i.e. if repo is not present, the app lists all the repos you have and lets you try again.
4. Also if you try to push a file, that is already there in your repo, it will print an error message and aborts the program
4. Make the program *.py executable using chmod, make a shortcut of this program to your desktop(so that you dont forget to push) and start pushing all the codes, that you have written and not pushed. 


#Clone
Feel free to clone and play arond the code to make it better
    
      git clone https://github.com/Rahul91/GitGui
      
#Issues:
1. The code is very 'brute' in nature and design, help it to be more pythonic and asthetic.
2. Only one file can be pushed at a time, which should not be the case ideally.
3. Find a issue and mail me: priyrahulmishra@gmail.com

        



