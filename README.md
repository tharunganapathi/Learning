# linux


## list commands
**ls **    =  list all files in the directory
**ls -a**  =  list all the hidden files in the directory
**ls -l**(long)  =  list files with long information like the permission, owner, date, etc...
**ls -a -l** (or) l**s -al** both supported as well.


## help
**--help** (or) **(-h)** or **(-?)** - Some application supports all the three params. Some application supports only some. 
                           So one doesn't work, try another.
                           eg: aircrack-ng --help  (or) nmap -h

## find the binary file.
**locate aircrack-ng**  =  Gives all the occurances in the file system from the DATABASE collection.
                       Drawback.
                           - DATABASE is updated once in a day.
                           - Returns all possbile occurances which has too many information.


**whereis aircrack-ng**  = Gives the binary file location, also its source and manual page location.
**which aircrack-ng** = Gives the exact binary file location alone. Actually it gets the path from env variable instead.
                      
