### Scripts
* **0-hello_world** - prints "Hello, World", followed by a new line to the standard output
* **1-confused_smiley** - script that displays a confused smiley *"(Ôo)'*.
* **2-hellofile** - display the contents of the /etc/passwd file.
* **3-twofiles** - display the content of */etc/passwd* and */etc/hosts*
* **4-lastlines** - Display the last 10 lines of */etc/passwd*
* **5-firstlines** - Display the first 10 lines of */etc/passwd*
* **6-third_line** - script that displays the third line of the file iacta.
  > You’re not allowed to use sed
* **7-file** - shell script that creates a file named exactly *\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)* containing the text *Best School* ending by a new line.
* **8-cwd_state** - script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
* **9-duplicate_last_line** - script that duplicates the last line of the file iacta
* **10-no_more_js** - deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
* **11-directories** -  counts the number of directories and sub-directories in the current directory.
  > The current and parent directories should not be taken into account
  > Hidden directories should be counted
* **12-newest_files** - displays the 10 newest files in the current directory.
  - Requirements:
    > One file per line
    > 
    > Sorted from the newest to the oldest
* **13-unique** - takes a list of words as input and prints only words that appear exactly once.
  > Input format: One line, one word
  >
  > Output format: One line, one word
  >
  > Words should be sorted
* **14-findthatword** - Display lines containing the pattern “root” from the file _/etc/passwd_
* **15-countthatword** - Display the number of lines that contain the pattern “bin” in the file _/etc/passwd_
* **16-whatsnext** - Display lines containing the pattern “root” and 3 lines after them in the file */etc/passwd*.
* **17-hidethisword**  -  Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
* **18-letteronly** - Display all lines of the file */etc/ssh/sshd_config* starting with a letter.
  > include capital letters as well
* **19-AZ** - Replace all characters A and c from input to Z and e respectively.
* **20-hiago** - removes all letters c and C from input.
* **21-reverse** - reverses it's input
* **22-users_and_homes** - displays all users and their home directories, sorted by users.
  > Based on the the */etc/passwd* file
* **100-empty_casks** - finds all empty files and directories in the current directory and all sub-directories.
    - Only the names of the files and directories should be displayed (not the entire path)
    - Hidden files should be listed
    - One file name per line
    - The listing should end with a new line
    - You are not allowed to use basename, grep, egrep, fgrep or rgrep
* **101-gifs** - lists all the files with a .gif extension in the current directory and all its sub-directories
    > Hidden files should be listed
    >
    > Only regular files (not directories) should be listed
    >
    > The names of the files should be displayed without their extensions
    >
    > The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)
    >
    > One file name per line
    >
    > The listing should end with a new line
    >
    > You are not allowed to use basename, grep, egrep, fgrep or rgrep