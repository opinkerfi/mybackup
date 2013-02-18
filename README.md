About
=====
Backup script for MySQL to dump databases in seperate file per database.

Each db will have one file for create information and one file for data records.

Features
========
	- Easy dump of databases
	- Control which databases not to dump with "skip"
	- Data is packaged with tar and compressed

Source code
===========
git clone https://github.com/opinkerfi/mybackup.git

Installation
===========
	- Download mybackup
		cd /opt ; git clone git clone https://github.com/opinkerfi/mybackup.git
	- Copy dist file and set permission
		cd /opt/mybackup ; cp mybackup.pl.dist mybackup.pl ; chmod 700 mybackup.pl
	- Edit mybackup.pl
		- Set username/password/host as needed
	- Test
		/opt/mybackup/mybackup.pl
	- Add to cron
		cp /opt/mybackup/mybackup.cron /etc/cron.d/mybackup





