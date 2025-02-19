# A02
Part 1: Directions on using Webstorm:

1. Install WebStorm & Git
    a. Download WebStorm from JetBrains. https://www.jetbrains.com/webstorm/download/#section=mac
     b. Install Git [install homebrew first, then run "brew install git"
   
2. Set Up WebStorm with GitHub
     a. Open WebStorm and go to Preferences
     b. Go to Version Control > Git and check if WebStorm detects Git automatically.
     c. Click Test to make sure Git is working
   
3. Clone a GitHub Repository in WebStorm
    a. Open WebStorm, go to File > Get from VCS (Version Control System)
    b. Choose GitHub and log in
     c. Enter the repository URL ,https://github.com/your-username/repo-name
      d. Click Clone – WebStorm will download the project to your computer

4. Make Changes & Commit
     a. Open any file, make changes, and save.
      b. Open the Version Control tab (bottom-left corner)
      c. Click Commit (✔ icon)
       d. Write a message like:
              "Updated README"
               "Fixed bug in index.html"
      e. Click Commit (or Commit & Push if you want to send changes to GitHub immediately)
   
5. Push Changes to GitHub
    a. After committing, click Push ⬆ icon)=.
    b. Select origin/main and click Push.
    c. Check the repository on GitHub – the changes should be there

6. Pull Changes from GitHub (if working with others)
    a. Click Pull (⬇ icon) to fetch the latest updates from GitHub.
    b. If you get a merge conflict, resolve it by choosing the correct version of the file.

Part 2: Glossary:
      Branch: A separate version of the code that allows for independent development.
      Clone: A local copy of a remote repository.
      Commit: A snapshot of changes saved in the Git history.
      Fetch: Updates local references to the latest changes from the remote repository.
      GIT: A version control system for tracking code changes.
      GitHub: A cloud-based hosting service for Git repositories.
      Merge: Combines changes from different branches into one.
      Merge Conflict: An issue that occurs when two branches have conflicting changes.
      Push: Uploads local commits to the remote repository.
      Pull: Fetches and merges changes from the remote repository.
      Remote: A version of the repository stored on GitHub.
      Repository: A project that contains all files and version history.
