# Git
My Git


What is Git?

Git is a Distributed Version Control system (DVCS). It can track changes to a file and allows you to revert back to any particular change.
Its distributed architecture provides many advantages over other Version Control Systems (VCS) like SVN one major advantage is that it does not rely on a central server to store all the versions of a project’s files.
Instead, every developer “clones” a copy of a repository I have shown in the diagram with “Local repository” and has the full history of the project on his hard drive so when there is a server outage all you need for recovery is one of your teammate’s local Git repository.

How will you know in Git if a branch has already been merged into master?

I will suggest you to include both the below mentioned commands:


git branch –merged lists the branches that have been merged into the current branch.

git branch –no-merged lists the branches that have not been merged.
