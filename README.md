# A02

## Git
To start using git, you can first download the version that works for your device from their official website. To start a git repository, navigate to the directory you want it to be in and initialize the repository by typing "git init". The most common commands we use with git are: 
- git status - which tells you what files have been changed since your last commit
- git add [filename] - which adds the specified files to a list of files ready for commiting.
- git commit -m "message" - which commits all added files and lets you add a description for what you are commiting.
As you work, these are the commands you will probably use most. However, these other commands are also very important to the general workflow of a git project:
- git branch [newbranchname] - which creates a new branch
- git checkout [branchname] - which moves the user to the specified branch to work on
- git push origin [branchname] - which pushes the committed content of the branch to the remote repository
- git pull origin [branchname] - which pulls changes from the remote repository into your copy on the local machine
These are only a few of many commands git offers to help our workflow, but these commands provide the basics of how to properly use git as a reliable version control system.
## GitHub
GitHub provides a useful interface to users of git. It has all the features of git, as well as some of their own. To create a repository using GitHub, instead of using the git init command, you can simply click the button at the top right of your screen to create a new repository. Then, you need to clone the repository onto your local device using the command "git clone" followed by the URL GitHub provides.
## Webstorm

## Glossary
<strong>Branch</strong>: This allows users to work in a separate space from the rest of the project. It's useful for more experimental features and divergencies in what you are working on. Branches can be merged together into the main project, or made off of other branches to spread out even further. Users can move from branch to branch to neatly separate their tasks and statuses of the project
<br><strong>Clone</strong>: Cloning a repository creates a copy of the entire history of the repository your cloning and puts it on your local device. This is typically the first step of working on any existing GitHub project.
<br><strong>Commit</strong>: Once you get something working, you can "commit" to your work, and give it a message to describe what you did. This will effectively save your work so you can return to it if needed.
<br><strong>Fetch</strong>: Fetching gets changes from the remote repository and brings them to your local machine. This is, for example, how you would get the changes that a coworker made to the project while you were away.
<br><strong>Git</strong>: Git is a version control system that tracks the history of your source code, allowing you to save work, return to it if needed, work across several devices, and more.
<br><strong>Github</strong>: GitHub allows developers to share their git repositories online. GitHub has all the features of Git, coupled with the ability to easily share and collaborate on code and host the repository in an online, remote location.
<br><strong>Merge</strong>: Merging combines different code into one. A common use is merging the contents of two branches into one, such as merging a specific branch into the main branch. This is used to add code into the rest of the project once it's ready and functional.
<br><strong>Merge Conflict</strong>: This occurs when the content that you are attempting to merge and the preexisting code are different and git cannot figure out which change you would like to keep. From here, you can decide which change you intend to keep, and git will just discard the unwanted change.
<br><strong>Push</strong>: This is typically done when you end your session of working. It takes all of the commits you have done and "pushes" it to the repository, which updates the repository with all the work that you pushed.
<br><strong>Pull</strong>: Pull is a combination of "fetch" and "merge." It gets the changes from the remote repository that you don't have yet on your local machine. Then, it merges the fetched change with the work you already have.
<br><strong>Remote</strong>: A "remote" refers to a place where your code is stored that is <em>not</em> your local computer. This is where the repository lives and can be accessed by any working device.
<br><strong>Repository</strong>: A repository is where all of the project is held. Any device can see the project from here, and from here they can also clone the project to their own local device to work.

### References
<a href="https://www.geeksforgeeks.org/" target=_blank>geeksforgeeks.org</a>
