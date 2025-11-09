# HW3A Solution - Git and Version Control

## Part 1: Repository Cloning

I successfully cloned the class repository from `https://github.com/olearydj/INSY6500` to
 `~/insy6500/class_repo`.

### Key Commands Used
-`git clone <url>`- Create local copy of remote repository
-`git log`- View commit history
-`git remote-v`- Check remote repository connections
 ## Part 2: Portfolio Repository Creation
 I created my personal course repository with:
-Professional README.md describing the project
-Proper .gitignore to exclude unnecessary files
-Organized directory structure for homework, projects, and notes
 ### Understanding Git Workflow
 The three-stage workflow:
 1. Working Directory: Where I edit files
 2. Staging Area: Where I prepare commits with `git add`
 3. Repository: Where commits are permanently stored with `git commit`
## Part 3: GitHub Publishing
 Successfully published repository to GitHub:
-Used `git remote add origin` to connect local repo to GitHub
-Used `git push-u origin main` to upload commits-Verified all files and commits are visible on GitHub
 ### The Remote Connection
 My local repository is now connected to GitHub:
-`git remote-v` shows the remote URL
-`git push` will send my commits to GitHub
-`git pull` will get updates from GitHub (if changes are made on GitHub)
 ### Details
 Complete this section with details from your setup:
-Repository URL: ...
-Output of `git remote-v`:
-The output of `git log--oneline`:

## Questions
### Reflections


#### Question 1: Git Workflow Benefits
1. Before learning about Git and its benefits when I had different versions of my work I would save tons of different versions to all different locations so that I would not lose them or delete them. I would save to my desktop, the cloud, box, etc. This always felt wrong but I have no idea of a better way so I just kept doing it that way. Some advantages that Git provides are, being able to share my work publicly, being able to use git bash and use specific versions of tools for my projects, and having one convienet place to store all of my documents, not just code. 
2. When doing my summer internship with Barton Malow a lot of my responsibilities were around document control. Since so many documents were edited and seen/used by so many people it was often so hard to track who made the most recent changes. By using git and the commit function it would have made it so much easier to track who made what changes and when. 


#### Question 2: Repository Organization
1. It is important to keep the class repository and my own repository seperate because the class repository is a read only reference. If I tried to conbine the two I would likelymake mistakes on which documents are my own editable codes and which are just references. Byb having them seperate it is easy to distingush which is which. 
2. In the future I will organize my repositories by type. I will create one repository per assignment so that is has it's own history. For group projects I will create shared repositories so that I can collaborate with my teammates easily. And I would create an additional repositories that is only for resources so that I can easily access any information or examples that I need. 


#### Question 3: Commit Messages and History
1. The second commit message is much more useful because it clearly shows the updates that have been made. This makes it easier for the user and any other viewers to see what changes where made during that version. I would likely view this again to see how to structure Git for a future assignment so the title makes it easy to find. 
2. When working on a project for weeks/months I think the appropiate time to make a commit could vary but some good examples of when to commit could be, after finishing a specfic task/step, after fixing a mistake/bug, or when adding a file.


### Graduate Questions


#### Question 1: The Three-Stage Model
1. For this assignment it was important to commit README.md and .gitignore seperately from hw3a-colution.md because README.md and .gitignore focused solely on the creation of the repository. Hw3a could not have been created without creating the repository first, so by keeping the commits seperate it help shows which steps where nessecary in actually creating my repository and which came after. 
2. If I am working on this homework over several days, when I make commits I should focus on making commits that are finished and complete. Out of the examples provided, I would commit the fixed typo and the update to README becuase these are complete changes that will not need to be edited agian. The other two changes should be kept in the staging area until complete to keep the nature of my commits consistent. 
3. Git status helps to show which files have been modified, staged, or untracked. This makes it very clear which files are ready to be commited and which should still be worked on before commiting. Git status should be used often so that commits can be made when needed. 


#### Question 2: Local vs. Remote Repositories
1. Git being a "distributed" version control system means that every local repository contains the full history of the project. When uploading something to google drive or dropbox it will only provide the most recent version and will not keep a detailed history. Git keeps this history and makes it available to all users. 
2. This helps enable constant workflow, for example, on planes, without internet, etc. Also, being able to edit and make commits without pushing to github allows developers to make changes and test things before changing the entire project. 
3. Since the class repository is cloned and view only I can pull from the remote repository to see any new changes but I cannot push to it and make my own edits. My repository is editable by me so I can both pull and push to it. 


#### Question 3: Professional Portfolio
1. Some things to consider while deciding what to commit should be making commits that highlight learning and completed work. Since I still a growing developer I think highlighting some of the learning/troubleshooting could be good examples of my growth but I should focus mostly on completed and final work/steps to a process.
2. README.md is important for people to see because it highlights things about me and the scope of my work within github. For an open use project the README.md would focus more on installation or usage. 
3. It is valueable to build this portfolio now because it will track my growth as a developer and not just final projects. It will show the changes and create a visaul record of my skills. 
