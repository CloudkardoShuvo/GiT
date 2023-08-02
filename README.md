# GiT
As DevOps engineers, we need to play the bridging gap between the Operation and development team. we need to ensure an efficient development workflow with sturdy infrastructure management.

In this blog post, we'll explore how DevOps engineers can leverage Git to streamline their development processes, manage configurations, deploy infrastructure as code, and maintain a smooth and reliable DevOps pipeline.

There are two types of source code management systems:

CVCS (centralised version control system)


2. DVCS (Distributed version control system)



Git is a distributed version control system (DVCS)

Stages of workflows :

Working Space: This is where you make changes to your project files and perform your development tasks.

Staging Area: The staging area is files that are going to be a part of the next commit, which lets Git know what changes in the file are going to occur for the next commit.

Local Working Space: This is where you make changes to your project files and perform your development tasks.

Below are some important terms requires to understand the concept, of GIT

Staging Area: The staging area is files that are going to be a part of the next commit, which lets Git know what changes in the file are going to occur for the next commit.

Local Repository: After you commit changes from the staging area, they become part of your local Git repository's history. The local repository stores all committed changes, and you can refer to them at any time.

Remote Repository: This is the shared central repository hosted on a remote server. Developers can push their local commits to the remote repository to share their work with others and collaborate on the same codebase.

Pull: Git "Pull" command fetches the changes from a remote repository into your local repository
git push [remote] [branch]

Push: The "push" command in Git is used to send your committed changes from your local repository to a remote repository.

git push [remote] [branch]

Commit:
The "commit" command in Git is used to save the changes you have made to your local repository. It creates a new version (snapshot) of the project with the changes you specified. Each commit is accompanied by a unique identifier called a "commit hash," which allows you to reference and track changes over time.

git commit -m "Your commit message here"

-m: Indicates that you are providing a commit message

Let's embrace the power of Git, and embark on a journey of successful and rewarding DevOps engineering. Happy coding!
