Version Control Tips:

Follow these steps every time you take some task and merge it with Master.

1. git checkout -b <your_local_branch_name> # Create a new branch and check it out
2. Now you are in "your_local_branch_name". Do your stuff here and the commit those by following steps
     i.   git add .
     ii.  git commit -m "Message that Describes your stuff"
     iii. git push origin <your_local_branch_name>
3. git checkout master # shifts to Master Branch
4. git pull origin master
5. git merge <your_local_branch_name> # To merge <your_local_branch_name> with Master 
6. git push origin master # To publish your changes to Master
