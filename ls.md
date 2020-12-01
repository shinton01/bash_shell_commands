# List directories

	ls
	ls /home/shawn
	Desktop     Downloads   Pictures   Templates   Videos
 	Documents   Music       Public    "VM's"       logfile.txt

	
## List hidden files

	ls -a
	 .               .bashrc     .local     .var        Pictures    logfile.txt
	 ..              .cache      .mozilla   Desktop     Public
	 .bash_history   .config     .pki       Documents   Templates
	 .bash_logout    .esd_auth   .ssh       Downloads  "VM's"
	 .bash_profile   .gnome      .themes    Music       Videos

	
## Detailed list of files and directories

	ls -l

	total 80

	drwxr-x--- 7 pete penguingroup   4096 Nov 20 16:37 Desktop

	drwxr-x--- 2 pete penguingroup   4096 Oct 19 10:46  Documents

	drwxr-x--- 4 pete penguingroup   4096 Nov 20 09:30 Downloads

	drwxr-x--- 2 pete penguingroup   4096 Oct  7 13:13   Music

	drwxr-x--- 2 pete penguingroup   4096 Sep 21 14:02 Pictures

	drwxr-x--- 2 pete penguingroup   4096 Jul 27 12:41   Public

	drwxr-x--- 2 pete penguingroup   4096 Jul 27 12:41   Templates

	drwxr-x--- 2 pete penguingroup   4096 Jul 27 12:41   Videos
	
Can combine flags

	ls -la
	
## Show recursively

	ls -R
	.:
	 Desktop     Downloads   Pictures   Templates   Videos
	 Documents   Music       Public    "VM's"       logfile.txt

	./Desktop:

	./Documents:
	 google-fix   linux  'self-hosted wordpress'   servers

	./Documents/linux:
	Command+Synopsis+Cheat+Sheet.pdf  Manual+Structure+Cheat+Sheet.pdf
	Links                             useful_advanced_bash
	LinuxCommandLineCheatSheet.pdf

	./Downloads:

	./Music:

	./Pictures:

	./Public:

	./Templates:

	"./VM's":
	CentOS-7-x86_64-DVD-2003.iso     ubuntu-20.10-desktop-amd64.iso
	archlinux-2020.10.01-x86_64.iso

	./Videos:

	
## Show reverse order

	ls -lr
	total 40
	-rw-rw-r--. 1 shawn shawn  204 Nov 16 07:07  logfile.txt
	drwxr-xr-x. 2 shawn shawn 4096 Oct 16 10:40  Videos
	drwxr-xr-x. 2 shawn shawn 4096 Nov 11 06:54 "VM's"
	drwxr-xr-x. 2 shawn shawn 4096 Oct 16 10:40  Templates
	drwxr-xr-x. 2 shawn shawn 4096 Oct 16 10:40  Public
	drwxr-xr-x. 2 shawn shawn 4096 Oct 16 10:40  Pictures
	drwxr-xr-x. 2 shawn shawn 4096 Oct 16 10:40  Music
	drwxr-xr-x. 2 shawn shawn 4096 Nov 14 06:41  Downloads
	drwxr-xr-x. 3 shawn shawn 4096 Nov 19 06:47  Documents
	drwxr-xr-x. 2 shawn shawn 4096 Oct 16 10:40  Desktop

	
## Show by time (newest first)

	ls -lt
	total 40
	drwxr-xr-x. 3 shawn shawn 4096 Nov 19 06:47  Documents
	-rw-rw-r--. 1 shawn shawn  204 Nov 16 07:07  logfile.txt
	drwxr-xr-x. 2 shawn shawn 4096 Nov 14 06:41  Downloads
	drwxr-xr-x. 2 shawn shawn 4096 Nov 11 06:54 "VM's"
	drwxr-xr-x. 2 shawn shawn 4096 Oct 16 10:40  Music
	drwxr-xr-x. 2 shawn shawn 4096 Oct 16 10:40  Pictures
	drwxr-xr-x. 2 shawn shawn 4096 Oct 16 10:40  Videos
	drwxr-xr-x. 2 shawn shawn 4096 Oct 16 10:40  Desktop
	drwxr-xr-x. 2 shawn shawn 4096 Oct 16 10:40  Public
	drwxr-xr-x. 2 shawn shawn 4096 Oct 16 10:40  Templates

