# A02
# A02: Git and GitHub Tutorial

## Part 1: Directions on Using WebStorm

### Step 1: Download and Install WebStorm
   - Visit [JetBrains WebStorm Download Page](https://www.jetbrains.com/webstorm/download/).
   - Select your operating system and click **Download**.
   - Once downloaded, follow the on-screen instructions to install WebStorm.

### Step 2: Open WebStorm and Configure Git
   - Launch WebStorm.
   - Go to **File** > **Settings** (or **Preferences** on macOS).
   - Under **Version Control**, select **Git**.
   - Ensure the Git executable path is correct (WebStorm often detects this automatically). You can download Git from [here](https://git-scm.com/downloads) if it is not already installed.

### Step 3: Create a New Project and Initialize a Repository
   - Open WebStorm and select **Create New Project**.
   - Name your project and choose the folder where it will be saved.
   - Right-click in the Project Explorer and select **Git** > **Initialize Git Repository**. This creates a local **Repository** for tracking your project.

### Step 4: Clone a GitHub Repository in WebStorm
   - In WebStorm, go to **VCS** > **Get from Version Control**.
   - Paste your GitHub **Repository** URL: `https://github.com/yourUCID/A02`.
   - Click **Clone** to download the repository to your local machine.

### Step 5: Make Changes and **Commit** in WebStorm
   - Open the `README.md` file in WebStorm and make your changes.
   - Once you’re done, go to **VCS** > **Commit** or click the commit icon at the top.
   - Write a clear **Commit** message describing your changes (e.g., "Task: Created README file").
   - Click **Commit** to save the changes to your local **Repository**.

### Step 6: **Push** Changes to GitHub
   - After committing, click on **VCS** > **Git** > **Push** to send the changes from your local **Repository** to the remote **Repository** on **GitHub**.
   - Verify the push and check your GitHub repository to ensure the changes were applied.

### Step 7: Pull and Fetch Changes from the Remote **Repository**
   - If there are updates on GitHub, you can download them to your local **Repository** using the **Pull** or **Fetch** commands.
   - Use **Fetch** to see any changes without merging them.
   - Use **Pull** to download and automatically merge changes.

### Step 8: Merging and Handling **Merge Conflicts**
   - When working on multiple **Branches**, you may need to **Merge** changes.
   - Go to **VCS** > **Git** > **Merge** to combine changes from one **Branch** into another.
   - If there are conflicting changes, you will encounter a **Merge Conflict**, which needs to be manually resolved before proceeding.

---

## Part 2: Glossary of Git Terms

- **Branch**: A separate version of the **Repository**, allowing independent development without affecting the main codebase.
- **Clone**: The process of copying a remote **Repository** from **GitHub** to your local machine.
- **Commit**: A record of changes made to files in a **Repository**, similar to saving your progress.
- **Fetch**: Downloads updates from the remote **Repository** without merging them into your local project.
- **GIT**: A version control system used to track code changes and collaborate with others.
- **GitHub**: A web-based platform for hosting **GIT** repositories and collaborating with other developers.
- **Merge**: The process of combining changes from one **Branch** into another.
- **Merge Conflict**: A conflict that occurs when changes from two **Branches** conflict with each other, requiring manual resolution.
- **Push**: Uploading your local **Commits** to the remote **Repository** on **GitHub**.
- **Pull**: Downloading changes from the remote **Repository** and merging them into your local code.
- **Remote**: The online version of your **Repository** stored on **GitHub** or another hosting platform.
- **Repository**: A project storage location where files, **Commits**, and histories are tracked in **GIT**.

---

## Commit Messages Examples

- **Task**: Create Repository
- **Feature**: Added workflow for using GitHub
- **Fix**: Changed `README.md` for definition of terms

---

## References:
- [JetBrains WebStorm Documentation](https://www.jetbrains.com/webstorm/documentation/)
- [GitHub Documentation](https://docs.github.com/)
- [Git Pro Book](https://git-scm.com/book/en/v2)
- [Git Glossary](https://git-scm.com/docs/gitglossary)
