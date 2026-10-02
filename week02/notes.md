1. pwd means "present working directory", it tells about where we are standing right now.
2. ls -a means "list all",which means it will also show files which are meant to be hidden and are not shown by simple ls

3. ls -l means "list long listing format",it shows a detailed breakdown of our files line by line and their permissions aswell

4. It works from wherever its standing because its in the home folder. and the path coding-cafe/week02 is relative because for absolute it works even when our directory is somewhere else.however if I change my directory to downloads and try to do it then it will show no such file or directory because coding-cafe is not present there

5. mv did two jobs where in the one where when README-backup.md week01/ it moved the file into week01 folder and in README-backup.md old-readme.md it renamed the README-backup.md into old-readme.md

6. by using echo $PATH i got
/opt/anaconda3/bin:/opt/anaconda3/condabin:/usr/local/bin:/System/Cryptexes/App/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/local/bin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/bin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/appleinternal/bin:/pkg/env/global/bin
so in total its about 12.

7. my python3 is in /opt/anaconda3/bin/python3.

8. for me and the guy next to me had different locations,because we were using different operating systems,however it might show same for the people using the same operating systems.

9. it responded with pyton3 not found,which meant that the terminal searched the entire PATH and could not find the file named pyton3 which it had to run/execute,after looking everywhere it will give up and say file not found.

10. here during python3 -m venv .venv,it made a file named .venv where "." will hide it so its not seen when we write normal ls.

11. its showing .venv on the left side,which means that my virtual environment is now active and it can run via its own local environment.

12. right now its showing /coding-cafe/.venv/bin/python3 which means that its in .venv so that means that activate made PATH change such that .venv was at the very start and was executed directly by the terminal.

13. in the first list pip     26.1.2 was present,after installation of the requests its now showing
certifi            2026.7.22
charset-normalizer 3.5.1
idna               3.19
pip                26.2.1
requests           2.34.2
urllib3            2.7.0
so it upgraded itself so that it could work properly.

14. it went back to /opt/anaconda3/bin/python3 which meant its out of .venv

15.  Symbolic links on the command line are followed.
     This option is assumed if none of the -F, -d, or -l options are specified.
     which means it will run a different symbolic link

16. ctrl + d just completely ended the process wheras ctrl + c just ended/stopped that specific line of code itself in python3.
