# Linux Commands

## List Files in a Directory
- **`ls`**  
  Lists all files in the current directory.

- **`ls -a`**  
  Lists all files, including hidden files (those starting with a dot `.`).

- **`ls -l`**  
  Lists files with detailed information like permissions, owner, size, and modification date.

- **`ls -a -l`** or **`ls -al`**  
  Lists all files (including hidden ones) with detailed information.

---

## Help Commands
- **`--help`** or **`-h`** or **`-?`**  
  Use this option with a command to get help about the command’s usage and available options.  
  *Note: Not all commands support all three variations, so if one doesn’t work, try the others.*  
  Example:
  - `aircrack-ng --help`  
  - `nmap -h`

---

## Finding Files

- **`locate <file-name>`**  
  Finds all occurrences of the file in the file system using a database.  
  *Note: The database is updated once a day, and the results may include too many occurrences.*  
  Example:  
  - `locate aircrack-ng`
 

- **`whereis <command>`**  
  Shows the location of the binary file, its source, and its manual page.  
  Example:  
  - `whereis aircrack-ng`

- **`which <command>`**  
  Shows the exact path to the binary file by checking the system’s environment variables.  
  Example:  
  - `which aircrack-ng`
 

  Finds all the files in the given directory with the given name
  - Syntax
    - `find <directory> <options> <expression>`

  - Example
    - `find /etc -type f -name apache2`
      - /etc/init.d/apache2
      - /etc/logrotate.d/apache2
      - /etc/cron.daily/apache2
      - /etc/default/apache2
    - `find /etc -type f -name apache2.\*`
        - /etc/apache2/apache2.conf

---
