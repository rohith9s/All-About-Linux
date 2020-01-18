

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
'''
departments  dupes.txt  log.tar.gz  new_folder  poems3.txt  poems4.txt  poems.txt  simple_data.txt  test.sh
'''

