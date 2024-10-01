# A02: GitHub Tutorial and Glossary

## Part 1: Directions on Using Git, WebStorm, and GitHub

### 1. **Installing WebStorm**
   - Download WebStorm from the official JetBrains website: [Download WebStorm](https://www.jetbrains.com/webstorm/download/).
   - Once downloaded, follow the installation instructions for your operating system.
   - Open WebStorm and sign in using your JetBrains account, or create one if you don’t already have an account.

### 2. **Setting Up Git in WebStorm**
   - Open WebStorm.
   - Go to `File -> Settings -> Version Control -> Git` and make sure WebStorm is linked to your local **Git** installation.
   - If you don't have **Git** installed, download it from [Git's official website](https://git-scm.com/downloads).
   - After installing **Git**, restart WebStorm and confirm that the path to the Git executable is correct in the settings.

### 3. **Creating a GitHub Repository**
   - Go to [GitHub](https://github.com) and sign in, or create a GitHub account if you don't have one.
   - After logging in, click on "New" to create a new **repository**.
   - Name the repository **A02** (case-sensitive).
   - Add a description if you like, choose whether the repository is public or private, and initialize the repository with a `README.md`.
   - Click **Create repository**.

### 4. **Cloning the GitHub Repository in WebStorm**
   - Once your repository is created, click the green “Code” button in GitHub, and copy the repository URL.
   - In WebStorm, go to `VCS -> Git -> Clone`.
   - Paste the copied GitHub repository URL and click "Clone."
   - This will download the repository to your local machine.

### 5. **Creating Files and Editing in WebStorm**
   - In the cloned project, right-click the project folder and choose `New -> File` to create a new file.
   - For example, create a file named `index.html` to begin adding your web content.
   - Make changes to your files as needed.

### 6. **Committing Changes in WebStorm**
   - After making edits to your files, click on the `VCS` menu and select `Commit`.
   - Write a clear **commit** message, such as `Feature: Added new file index.html`, and click "Commit".
   - Committing the changes saves a snapshot of your work locally.

### 7. **Pushing Changes to GitHub**
   - After committing, push your changes to the remote **repository** by clicking `VCS -> Git -> Push`.
   - This will upload the local changes to your GitHub repository.

### 8. **Creating and Switching Branches**
   - To create a new **branch**, go to `VCS -> Git -> Branches -> New Branch` in WebStorm.
   - Name the branch and switch to it.
   - Make changes to your project in this branch.

### 9. **Merging Branches and Resolving Merge Conflicts**
   - After making changes in your branch, you can **merge** it with the main branch by going to `VCS -> Git -> Branches -> Merge`.
   - If there are any **merge conflicts**, WebStorm will highlight them, and you can choose which changes to keep.
   - Once resolved, complete the **merge**.

### 10. **Pulling and Fetching Changes**
   - If changes were made by others in the **remote** repository, you can **pull** them into your local repository by going to `VCS -> Git -> Pull`.
   - If you only want to see changes without applying them, use the **fetch** command instead: `VCS -> Git -> Fetch`.
   - This keeps your local repository up to date with the remote one.
   - Be cautious when using `Pull with Force`, as it can overwrite your local changes.

## Part 2: Glossary of Terms

- **Branch**: A parallel version of a repository. It allows for changes to be made independently before merging into the main project.
- **Clone**: Creating a copy of a remote repository on your local machine.
- **Commit**: A snapshot of the changes made to the project files, saved in the local repository.
- **Fetch**: Downloading commits, branches, and files from a remote repository without merging them.
- **GIT**: A distributed version control system used for tracking changes in source code during software development.
- **GitHub**: A web-based platform that uses Git for version control and offers collaboration tools for developers.
- **Merge**: Combining changes from different branches into one branch.
- **Merge Conflict**: A situation where Git cannot automatically merge changes because of conflicting alterations in the same file.
- **Push**: Uploading local repository changes to a remote repository.
- **Pull**: Downloading changes from a remote repository to your local repository and applying them.
- **Remote**: The version of the repository hosted on a server, such as GitHub, that developers collaborate on.
- **Repository**: A project or folder that contains all project files, including the history of changes.

## References
1. [GitHub Documentation](https://docs.github.com/en)
2. [JetBrains WebStorm Documentation](https://www.jetbrains.com/webstorm/documentation/)
3. Git PowerPoint slides from IS117 Lecture
4. [Git Glossary](https://git-scm.com/docs/gitglossary)

