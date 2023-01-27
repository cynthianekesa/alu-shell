echo 'Hello, World' script that prints “Hello, World”, followed by a new line to the standard output
echo "\"(Ôo)'" script that displays a confused smiley "(Ôo)'
cat /etc/passwd Display the content of the /etc/passwd file
cat /etc/passwd /etc/hosts Display the content of /etc/passwd and /etc/hosts
tail /etc/passwd  Display the last 10 lines of /etc/passwd
head /etc/passwd  Display the first 10 lines of /etc/passwd
head -3 iacta | tail -1  script that displays the third line of the file iacta
echo "Best School" > \\\*\\\\"'\"Best School\"\\'"\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)  shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line
ls -la > ls_cwd_content script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it
tail -1 iacta >> iacta  script that duplicates the last line of the file iacta
find . -type f -name "*.js" -delete script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
find . -type d ! -path . | wc -l  script that counts the number of directories and sub-directories in the current directory.The current and parent directories should not be taken into account.Hidden directories should be counted                                                                    
ls -t . | head  script that displays the 10 newest files in the current directory
sort | uniq -u  script that takes a list of words as input and prints only words that appear exactly once
egrep "root" /etc/passwd  Display lines containing the pattern “root” from the file /etc/passwd
egrep -c "bin" /etc/passwd  Display the number of lines that contain the pattern “bin” in the file /etc/passwd
egrep  -A 3 "root"  /etc/passwd  Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd
egrep  -v  "bin"  /etc/passwd  Display all the lines in the file /etc/passwd that do not contain the pattern “bin"                                     egrep ^[[:alpha:]]  /etc/ssh/sshd_config  Display all lines of the file /etc/ssh/sshd_config starting with a letter
tr 'Ac' 'Ze'  Replace all characters A and c from input to Z and e respectively
tr -d cC  Create a script that removes all letters c and C from input
rev Write a script that reverse its input                                                                            
