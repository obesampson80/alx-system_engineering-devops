# 0. Where am I?
*pwd*  prints the absolute path name of the current working directory.
# 1. What’s in there?
*ls* Display the content list of your current directory
#2. There is no place like home
*cd ../../root* Changes working directory to the user's home directory
# 3. The long format
*ls -l* Display current directory contents in a long format
# 4. Hidden files
*ls -la* Display current directory contents, including hidden files (starting with .). Use the long format.
# 5. I love numbers
*ls -nla* Display current directory contents using digits only
# 6. Welcome
*mkdir tmp/my_first_directory* A script that creates a directory named my first directory in the /tmp/ directory.
# 7. Betty in my first directory
*mv betty /tmp/my_first_directory*Move the file betty from /tmp/ to /tmp/my first directory.
# 8. Bye bye Betty
*rm /tmp/my_first_directory/betty* delete the file betty
# 9. Bye bye My first directory
*rmdir /tmp/my_first_directory* Delete the directory
# 10. Back to the future
*cd ..* changes the working directory to the previous one.
# 11. Lists
*ls -la . .. /root* List files in multiple folders in long format including hidding files
# 12. File type
*file /tmp/iamafile*  a script that prints the type of the file named iamafile
# 13. We are symbols, and inhabit symbols
*ln -s /bin/ls __ls__* Creating a symbolic link in the current working directory
# 14. Copy HTML files
*cp -rua *html ../* Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
