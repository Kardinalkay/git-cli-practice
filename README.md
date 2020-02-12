1. Assuming that you aren't sure whether you're currently inside of a Git repository, write the command (or commands) that will give you this information.

	1. ls -alt 

	2. git rev-parse --is-inside-work-tree 

	3. git add -A

2. Assuming that you are currently within a Git repository, write the command (or commands) that will cause the file 'hello-world.txt' to be committed.

	1. git commit -m "hello-world.txt"

	2. git commit -a -m "hello-world.txt"

3. Assuming that you are currently within a Git repository, write the command (or commands) that will display any uncommitted changes made to the file named 'README.md'.

	1. git diff README.md

	2. git diff

4. Assuming that you are currently within a Git repository, write the command (or commands) that will display the changes from the commit with the ID of abc123.

	1. git show abc123

	2. git checkout abc123

5. Assuming that you are currently within a Git repository, write the command (or commands) that will display the ID and commit message for the 3 most recent commits.

	1. git log -3

	2. git log -3 --oneline

	3. git reflog -3

	4. git log -3 --stat

	5. git reflog -3 --stat

	6. git log -3 --stat --oneline