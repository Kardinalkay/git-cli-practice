1. Assuming that you aren't sure whether you're currently inside of a Git repository, 
write the command (or commands) that will give you this information.

Answer: 
	1. ls -alt 

	2.git rev-parse --is-inside-work-tree 

	3. git help

2. Assuming that you are currently within a Git repository, write the command (or commands) that will cause the file 'hello-world.txt' to be committed.

	1. git commit -m "hello-world.txt"

	2. git commit -a -m "hello-world.txt"