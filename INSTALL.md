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

#More Specifically (Using Debian)

Step 1: Log in via SSH
Step 2: Change Logged in User Password
Step 3: Create a New Sudo user
Step 4: Loggin in as the Newly Created User
Step 5: Disable Root Login via SSH
Step 6: Update Your Server
Step 7: Setting timezone
Step 8: Set Hostname
Step 9: Configure a Firewall
Step 10: SSH Port Change
Step 11: Reboot
