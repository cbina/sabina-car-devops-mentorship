## Level0
$ ls		#view content of current directory

$ cat <file> 	#list content of the file

## Level1
$ cd ~		#enter home directory
	
$ cat < -	#list content of the file by speciyfing the absoulte path to the file

## Level2
$ cat < file\ name	#display contents of a file that has spaces in its name

## Level3
$ ls -la	#display all files in current directory including hidden files
	
$ cd ..		#enter in directory that is one step up from current

## Level4
$ file ./*	#list files with description about file type

## Level5
$ find ./ -type f -size <size> ! -executable		# find files of specific size ('c' stands for bytes) that is non-executable ('!' stands for not)

## Level6
$ find / -user <user> -group <group> -size <size> -type f 2>/dev/null		#find files owned by specific user, group and has specific size; 2</dev/null means throw away any error messages
## Level7
$ grep -w "pattern" <file>		#print lines matching pattern in file

## Level8
$ cat <file> | sort | uniq -u		#view contents of file using cat; sort lines using sort; print only unique lines using uniq -u

## Level9
$ strings <file> | grep -E "=+"		#print the sequences of printable characters in files using strings; interpret patterns as extended regular expressions using -E; '=+' matches 1 or more repetitions of '=' character

## Level10
 
