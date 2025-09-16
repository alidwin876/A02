# A02


## Part 1: Tutorial ##
## Tutorial on starting Git: ##
1. The first step to start the coding environment process is to install and configure Git.You can download Git from this website listed here: https://git-scm.com/downloads.
2. Download the appropriate distribution for your operating system.
   Once Git is installed, open your terminal and verify that Git was installed correctly by using the command "git --version".
3. If Git was installed correctly, it will return what version of Git was installed on your machine.


## Tutorial on starting GitHub: ##
1. Go to https://github.com and create a GitHub account using your email credentials or log in to an already existing account.
2. Once logged in, you will create a repository by clicking the plus "+" sign in the upper right hand corner and clicking the option that says "Create New Repository".
3. When creating a repository, click the options to make it public and to add a README.MD file and to also give the repository a name.
4. Once those are checked off, click "Create" to make your repository.


## Tutorial on starting Webstorm: ##
1. The first step to installing Webstorm is to download the JetBrains editor through the website here: https://www.jetbrains.com/student/. Once on the website, click the option that says "Request now" to request institutional access to a JetBrains account. You will have to apply for this access with your institutional login. Once you obtain access to your JetBrains account, locate the page where it directs you to download the Webstorm editor. Download the associated Webstorm editor based on your operating system.
   After Webstorm is installed and after your GitHub account is set up with your repository, alongside Git configured, open the editor and click the menu tab to open settings.
2. From the menu settings, click the “New” button and click “Project from Version Control”.
3. From your GitHub account, locate your repository you want to clone into Webstorm and click the green button that says “<> Code”. From here, you will copy the direct path for the GitHub repository and paste this direct path into the URL section in Webstorm.
4. Once the path from GitHub is entered, it will populate the directory with the local path on your file system, and then you can click “Clone”. The repository will now be cloned.
5. From this point you should create a file in Webstorm after creating your repository by clicking “File”, then “New”, then “HTML File” to create an HTML file. Create a stylesheet file by clicking “File”, then “New”, then “Stylesheet” to create a stylesheet file.
6. When adding either an HTML or stylesheet file, a prompt will be asked to add the following files to Git which you will select “Add”. Perform changes to the files as needed.
7. When done with the coding environment, you will have to commit your changes from your local machine to upload it to the remote repository you made from before. To do so, look at the left hand tab of Webstorm and click the option for “Commit”. From here, you will see a list of files that have been last edited when the project was opened in green.
8. These changes have not been saved yet and have to be committed, which can be done by selecting the files you wish to save changes to from your local machine to the repository and writing a commit message you would like to save.
9. Once you selected the files you want to be committed and wrote a message, click the “Commit” button.
10. Then click the shortcut Ctrl + Shift + K to open a menu to start the process to push changes. After reviewing all information, and you are sure the changes can be pushed to a remote repository, click the “Push” button. The changes now will be visible on your GitHub repository, available for others to see and use.


## Part 2: Glossary ##
* **Branch**
  * A branch in GitHub acts like an independent workspace in a repository where changes made to that branch do not affect other branches unless they are merged. Merging branches means the changes made on one branch can be saved (merged) into another branch. Branches allow developers to work on different features in a project without having to create changes to the entire main branch/repository at once.
* **Clone**
  * Cloning a repository allows a developer to initiate a coding environment that can be worked on locally or shared remotely. When a repository is cloned, it creates a copy of a remote project with all of its contents to be saved on your local machine. This creates a link between your remote repository from GitHub and your local machine so changes and pull requests can be made.
* **Commit**
  * A commit is essentially a way of documenting a project at a specific point in time by including a commit message specifying what is being "committed". A commit includes the commit message itself and the author who completed the commit. Essentially, commits provide a history of the coding environment which allows other collaborators on the project to better understand why changes were made to a file.
* **Fetch**
  * Fetching allows you to retrieve work done by other people by locating all the new remote tracking branches without merging those changes into your own branches. Fetching works in a way where a developer can review the changes from the remote repository before planning how to utilize these branches in their own local branch.
* **Git**
  * Git is a version control system that was designed to manage the kernel found on Linux. In modern usage, Git allows developers to have a full copy of a repository which is how developers are actually able to share and collaborate on projects. Git is mainly designed for branching and merging repositories as an efficient way of handling projects with many contributors and to ensure the history of the project is kept secure.
* **Github**
  * GitHub is a cloud based platform that hosts Git repositories to facilitate collaboration between projects. It lets developers share code to each other, track issues in the projects, manage features and create pull requests for other developers to review.
* **Merge**
  * A merge is essentially the process of combining changes made on one branch into another branch. For example, when a feature has been fully implemented on a separate branch from the main project's, it has to be merged so it can be integrated into the main codebase. Git will attempt to merge branches even if the two branches have diverged or may result in a conflict where manual input is necessary to complete the merge.
* **Merge Conflict**
  * A merge conflict is when Git attempts to compare and resolve the differences between versions of the same file during a merge or pull request. Merge conflicts can occur when edits are made in both files that cannot be resolved through a merge request since they are incompatible with one another. Developers have to manually fix the merge issue as this is not something that Git can fix.
* **Push**
  * When a push is done, local commits that have been saved on your machine will be sent to a remote repository. Pushing essentially updates the remote branch with the current status of the file that is saved on your local machine. When a push is completed, changes that a developer made to a code space will be available for other developers to review or use in their own projects.
* **Pull**
  * A pull request is essentially a proposal to merge changes made from one branch into another branch. Essentially, a pull request does two actions which are fetching new data from the remote repository and then merging inside the current branch you are working in. Pull requests allow branches to be kept up to date with the latest work and the requests also highlight the differences between content in the source and target branches.
* **Remote**
  * Remote is referring to another version of a repository where a host such as GitHub serves as a collaboration hub for developers to share work. At a fundamental level, a remote is a reference to another copy of your repository which is hosted somewhere else. For example, Git allows users to copy their repository code in the form of a URL which can be shared.
* **Repository**
  * A repository is a fundamental data structure within Git holding the history, project files and configuration. A repository is a fundamental data structure within Git holding the history, project files and configuration. Repositories can be either locally hosted or hosted on a remote platform such as GitHub. Repositories provide ways to collaborate with other developers, manage many versions of your project and most importantly to track changes.




## References: ##
1. “What Is Git?” Git, https://git-scm.com/video/what-is-git. Accessed 16 Sept. 2025.
2. “Downloads.” Git, https://git-scm.com/downloads. Accessed 16 Sept. 2025.
3. “Using Git Integration.” WebStorm Help, JetBrains, https://www.jetbrains.com/help/webstorm/using-git-integration.html. Accessed 16 Sept. 2025.
4. GitHub. GitHub, https://github.com. Accessed 16 Sept. 2025.
5. “Hello World.” GitHub Docs, GitHub, https://docs.github.com/en/get-started/start-your-journey/hello-world. Accessed 16 Sept. 2025.
6. “Set Up a Git Repository.” WebStorm Help, JetBrains, https://www.jetbrains.com/help/webstorm/set-up-a-git-repository.html. Accessed 16 Sept. 2025.
7. “Populating Projects.” WebStorm Help, JetBrains, https://www.jetbrains.com/help/webstorm/populating-projects.html. Accessed 16 Sept. 2025.
8. “Commit and Push Changes.” WebStorm Help, JetBrains, https://www.jetbrains.com/help/webstorm/commit-and-push-changes.html#commit. Accessed 16 Sept. 2025.





