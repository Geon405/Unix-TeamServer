# Unix-TeamServer

Unix servers are widely used as application servers and database servers and are available from a variety of vendors, including Sun, IBM, HP and others. This repository contains screenshots of basic sudo tasks one might want to preform when setting up their own server such as adding other users, giving them permissions and more. 
The second part of this repository is the jekyll website. Jekyll is a static website generator. Jekyll is a simple, blog-aware, static site generator for personal, project, or organization sites. On this VPS we have created a group website that contains a post from each team member. All the posts have our journals of us setting up the VPS and another link that sends you to our personal website. Our individual website included Profile Page, Login Page, Home Page and Goal Page. 

# Examples of code used
-login to the site using ssh:$ ssh debian@144.217.243.246
Then we entered the password

-adding of users: $ sudo useradd (name)
-changing users password: $ sudo passwd (user)
-upgrade site:
just be ($ sudo apt upgrade)
-adding users in groups:
$ sudo usermod -a -G sudo (user)
$ id - gn (user
$ groups (name)

# Individual Website

  * Geon's Website: https://144.217.243.246/Geon/Journal.html
  * Christopher's Website: https://144.217.243.246/Christopher/code/welcome.html
  * Jordano's Website: https://144.217.243.246/Jordano/Introduction.html

# Team Project

  * Team Website: http://144.217.243.246/Unix-TeamServer/Unix_Website/homepage.html


#restarting the server
-loggin in ssh: ssh 144.217.243.246
$sudo /etc/init.d/nginx stop
$pkill -9 php
$sudo /etc/init.d/nginx start

#redirect to the main page
<meta http-equiv="refresh" content="time; URL=new_url" />

#adding git

$cd debian/var/www/html
$git config --global user.name "Your Name"
$git config --global user.email "youremail@domain.com"
$git clone https://github.com/Geon405/Unix-TeamServer
