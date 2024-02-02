# A02

Git: Basic Setup and Usage

Step 1: Install Git
Visit the Git website at https://git-scm.com/.
Download the version of Git for your operating system.
Run the installer and follow the setup wizard. Accept the default options unless you have specific preferences.

Step 2: Configure Git
Open a terminal (Command Prompt, PowerShell, or Git Bash on Windows; Terminal on macOS and Linux).
Set your user name with git config --global user.name "Your Name".
Set your email address with git config --global user.email "youremail@example.com".

Step 3: Initialize a New Git Repository
Navigate to your project directory in the terminal using cd path/to/your/project.
Run git init to initialize a new Git repository.

Step 4: Add and Commit Files
Add files to the staging area with git add . (to add all files) or git add filename (to add a specific file).
Commit the added files with git commit -m "Your commit message".

WebStorm: Project Creation and Configuration

Step 1: Install WebStorm
Go to the JetBrains website at https://www.jetbrains.com/webstorm/download/ and download the installer.
Run the installer and follow the instructions to install WebStorm.

Step 2: Create a New Project
Open WebStorm and select "Create New Project" on the welcome screen.
Choose the project type and specify the project location.
Click "Create" to generate the project.

Step 3: Configure Git Integration
With your project open, navigate to "File" > "Settings" (or "WebStorm" > "Preferences" on macOS).
Go to "Version Control" > "Git" and ensure the path to the Git executable is correctly set.
Apply the changes and close the settings.

Step 4: Use Git Features in WebStorm
Access Git operations from the "VCS" menu or the Git toolbar.
Use the "Commit" tool window (Ctrl+K or Cmd+K on macOS) to commit changes.
Use the "Push" dialog (Ctrl+Shift+K or Cmd+Shift+K on macOS) to push changes to a remote repository.

GitHub: Repository Creation and Collaboration
Step 1: Create a GitHub Account
Visit https://github.com and sign up for a new account.
Follow the on-screen instructions to complete your profile setup.

Step 2: Create a New Repository
Once logged in, click on the "+" icon in the top-right corner and select "New repository".
Name your repository, add a description (optional), and choose the visibility.
Click "Create repository".

Step 3: Push Local Repository to GitHub
On your repository's GitHub page, find the "Quick setup" section which provides the URL for your repository.
In WebStorm's terminal or your system's terminal, link your local repository to GitHub with git remote add origin repository-URL.
Push your code with git push -u origin master or git push -u origin main, depending on your branch name.

Step 4: Collaborate
To collaborate, you can invite others to your repository via GitHub's "Settings" > "Collaborators & teams".
Use branches for feature development and bug fixes. Create a new branch with git checkout -b branch-name.
After making changes, push the branch with git push -u origin branch-name and create a Pull Request on GitHub.




Branch: A version of the repository that diverges from the main working project. It allows developers to work independently on a feature or a fix without affecting the main codebase.

Clone: The act of creating a local copy of a repository from a remote server. This includes all of the repository's history.

Commit: A snapshot of changes in the project's history. Commits include changes to files along with a message describing what was changed and why.

Fetch: The command used to download changes from a remote repository to the local repository but does not merge them. It allows a user to see what others have committed.

GIT: A distributed version control system used to track changes in source code during software development. It allows multiple developers to work together on non-linear development.

Github: A web-based platform that uses GIT for version control. It facilitates collaboration among developers, allowing them to share, discuss, and improve code.

Merge: The process of integrating changes from one branch into another. It can be done automatically or manually in the case of merge conflicts.

Merge Conflict: Occurs when GIT is unable to automatically resolve differences in code between two commits. Developers must manually resolve these conflicts.

Push: The act of sending local repository changes to a remote repository. This updates the remote repository with local changes.

Pull: A combination of fetch and merge. It retrieves changes from a remote repository and immediately attempts to merge them into the local repository.

Remote: A version of your repository hosted on a server, typically on GitHub. It allows you to collaborate with others.

Repository: A storage space where your project lives. It can be local (on your computer) or remote (on a server like GitHub). It includes all of your project's files and the history of changes.




