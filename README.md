Program 10

Analyzing and Changing Git History

Write the command to list all commits made by the author "John Doe" between

"2023-01-01" and "2023-12-31."

git log --author=<Name>--since=<Date>/--after=<Date>

git log

====

Example :use this below syntax for the above command

git log --author="John Doe" --since="2023-01-01" –until="2023-12-31"

Program 11

Analyzing and Changing Git History

Write the command to display the last five commits in the repository's history

Example : git log -5

For exmple to give last 2 commits use git log 2

output is

=============

commit 5acbf338128b5b8b3ff2a196d93c837c8b3c71b3 (HEAD -> main, origin/main, origin/HEAD)

Author: AI and ML student <atmestudent.edu.in>

Date: Tue Dec 3 12:48:27 2024 +0530

 Initial commit

commit 7efae202aa270c7ed54870c52bcffcd80e07a468

Author: AI and ML student <atmestudent.edu.in>

Date: Wed Nov 27 12:42:40 2024 +0530

 empty

Program 12

Analyzing and Changing Git History

Write the command to undo the changes introduced by the commit with the ID

"abc123".

Syntax uis

git revert commit-id

 for the above case use git tevert abc123

For Practical Example usage see below

git revert 5acbf338128b5b8b3ff2a196d93c837c8b3c71b3

git push origin mai
