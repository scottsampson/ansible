A more manageable dsh tool
==============


install instructions for ubuntu 14.04

	apt-get install -y software-properties-common
	apt-add-repository ppa:ansible/ansible
	apt-get update && apt-get upgrade -y
	apt-get install -y ansible
	cd /etc && rm -rf /etc/ansible 
	git clone https://github.com/nowthatsamatt/ansible.git

Example

	ansible cloudspace "echo \"hello\""
	
Configuration
==================

Update hosts file with your different servers

	[cloudspace]
	ops.cloudspace.com
	my.cloudspace.com
	rss.cloudspace.com
	54.242.89.73
	api.crunchinator.com
	
Upcoming Features
=================

* Tie in your ec2 account and have it auto update your ansible hosts file.


	