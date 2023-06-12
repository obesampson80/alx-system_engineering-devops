## 0. Hello World
*echo Hello World* Write a script that prints “Hello, World”, followed by a new line to the standard output.
## 1. Confused smiley
*echo "(Ôo)'* Write a script that displays a confused smiley "(Ôo)'.
## 2. Let's display a file
*cat /etc/passwd* Display the content of the /etc/passwd file
## 3. What about 2?
*cat /etc/passwd /etc/hosts* Display the content of both files
## 4. Last lines of a file
*tail /etc/passwd* Display last 10 lines of the file /etc/passwd
## 5. I'd prefer the frst ones actually
*head /etc/passwd* Display first 10 lines of /etc/passwd
## 6. Line #2
*cat iacta | head -3 | tail -1 Displays the third line of the file iacta
## 7. It is a good file that cuts iron without making a noise
*echo "Best School"> file_name" 
## 8. Save current state of directory
*ls -la > ls_cwd_content* Writes to a file ls_cwd_content
## 9. Duplicate last line
* cat -en "" | tail -1 iacta >> iacta* Duplicates the last line of the file iacta
## 10. No more javascript
*find . -name '*js' -type f -delete* a script that deletes all the regular files (not the directories) with a .js
## 11. Directories
*find -mindepth 1 -type d | wc -l* Counts the number of directories and subdirectories in the current directory excluding current and parent directories
## 12. What's new
*ls -t | head* Script that display 10 newest files
## 13. Unique
* sort | uniq -u*
## 14. It must be in that file
* grep -i root /etc/passwd*
