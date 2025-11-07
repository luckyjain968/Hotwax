Version Control System (VCS)
A Version Control System is a tool that records and manages changes made to files over time. It is mainly used in software development to maintain a complete history of updates, making it easier to track modifications, revert changes, and collaborate with others.

Types of Version Control Systems
1. Localized Version Control System (LVCS)- A Localized VCS stores all file versions and history on a single machine. It works well for personal or small-scale projects but is risky for teamwork since it has no collaboration features. If the system crashes, all the history may be lost. These systems save changes as “patches” so users can revert to earlier versions whenever needed.

2. Distributed Version Control System (DVCS) - In a Distributed VCS, every developer has a complete local copy of the repository along with its full history. This allows offline work and makes actions like committing, branching, and merging faster. It also offers better protection against data loss since multiple copies exist. Git and Mercurial are well-known examples of DVCS.

3. Centralized Version Control System (CVCS) - A Centralized VCS uses one central server that stores all files and history. Developers download (checkout) the files from this server, make changes, and then upload (commit) them back. This setup is easy to manage and keeps a single source of truth, but it depends heavily on the server. If the server goes down, no one can work.

Git Commands

Git provides various commands to manage project files. Some essential commands are:

1. git init- 
Initializes a new Git repository in the current folder. After running this command, a hidden .git directory is created to store version history.

2. git add - 
Adds new or modified files to the staging area. This step is required before committing changes.

3. git commit - 
Saves staged changes to the local repository. Using git commit -m "message" allows you to write a short description of what changes were made.

4. git status -  
Shows the current state of the working directory and staging area. It tells you which files are modified, staged, or unchanged.

5. git config -
Used to set the username and email for Git. When used with the --global flag, the settings are applied to all repositories on the system.

6. git push - 
Uploads your local commits to a remote repository. This command is used when you want to share your changes with others.

