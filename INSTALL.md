# How to setup the server

1. Update your Server
2. Create a New User and Modify Its Privileges
3. Enable Public Key Authentication:
	mkdir ~/.ssh
	chmod 700 ~/.ssh
	nano ~/.ssh/authorized_keys
	chmod 600 ~/.ssh/authorized/keys
	exit
	sudo nano /etc/ssh/sshd_config
4. Set Up a Firewall for Your VPS

# More Specifically (Using Debian)

1. Log in via SSH
2. Change Logged in User Password
3. Create a New Sudo user
4. Loggin in as the Newly Created User
5. Disable Root Login via SSH
6. Update Your Server
7. Setting timezone
8. Set Hostname
9. Configure a Firewall
10. SSH Port Change
11. Reboot
