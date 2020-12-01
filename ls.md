# List directories

	ls
	ls /home/shawn
	
## List hidden files

	ls -a
	
## Detailed list of files and directories

	ls -l
	
Example long form list:

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
	
Example of recursive display:

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

	ls -r
	
## Show by time (newest first)

	ls -t
