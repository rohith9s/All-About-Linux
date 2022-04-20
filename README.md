

ctrl + A :		move to start 

ctrl + E:     move to end

ctrl+ leftarrow:	move to begining of word

ctrl + right arrow:move to end of word


ctrl + U:		remove (crop) from cursor to start

ctrl + K:		remove (crop) from cursor to end

ctrl + Y: 		past cropped text

ctrl + Shift + C    copy to clipboard

ctrl + Shift + V	paste from clipboard

up arrow:		Recall previous commands

down arrow:	Scroll previous commands

ctrl + R:		Search previous commands

ctrl + C:		exist

apropos:  (Unix) In computing, apropos is a command to search the man page files in Unix and Unix-like operating systems. 


pwd: present working directory

cd: change directory. 
	```
	EX : cd ../../finance/spreadsheets/ : move 2 folders back and goes to /finance/spreadsheets/ 
	```
cd -: cd hypen is used to switch between last two paths.

cp poems.txt poems2.txt: copies poems.txt to  poems2.txt file

cp simple_data.txt departments/hr/employee\ info/ : copies 'simple_data.txt' to departments/hr/employee\ info/ folder

mv poems2.txt departments/marketing/ : moves poems2.txt to directory 'departments/marketing/'

mv departments/marketing/poems2.txt departments/marketing/literature.txt : moves poems2.txt from directory 'departments/marketing/' to 'departments/marketing/' and renamed as literature.txt 

mv departments/marketing/literature.txt . : moves literature.txt from directory 'departments/marketing/' to current directory. here . is current directory

mv *.txt departments/marketing/ :  moves *.txt from current directory to  'departments/marketing/' 

mv departments/marketing/* . :  moves all files  from  'departments/marketing/'  to current directory, here . is current directory

rm literature.txt : removed literature.txt  file

ls
```
departments  dupes.txt  log.tar.gz  new_folder  poems3.txt  poems4.txt  poems.txt  simple_data.txt  test.sh
```

rm poems?.txt : will remove poems3.txt and poems4.txt. here ? represents only one wildcard

ls
```
departments  dupes.txt  log.tar.gz  new_folder  poems.txt  simple_data.txt  test.sh
```


rm -r departments/customerservice/ : remove recursively 

find . -name "poe*" : finds files starts with name poe 

find . -name "d*"   : finds files starts with name d 

find . -name "*d*"  : finds files contains with name d

find ~/Documents/ -name: "*d*" : finds in Documents with name contains d



> top   
- to see cpu details
- Press ‘c‘ option in running top command, it will display absolute path of running process
- press shift+P to sort by cpu utilization
- press shift+M to sort by memory utilization
- press U, to search by user


**List files:**

ls -lrth
- l for listing 
- r for recursive
- t for time based, latest entries will be down side
- h for human readable


**grep :** : General Regular expression Parser

grep -ril 
 -r for recursive
 -i for case insensitive
 -l for list of files
 
 ex: grep -ril "root" /etc/   => this will search for word in side mentioned path
 
 
 **Disk Utilization** : 
 
 df -Th
  - df is disk full
  - T for file type 
  - h human readable
  


Add a User:

	sudo adduser <username>
	
Type your current password and new password when prompted.
	
Change user on Linux using su

	su <option> <user>
	
	 sudo -u <username> <password>
	 

To change user to root account, run “su” or “su –” without any arguments.


	
