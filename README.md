## Understanding the differences between Git Push, Git Fetch, and Git Pull

GitHub is a cloud-based service that allows developers to store and manage their code while simultaneously tracks, catalogs, and regulates changes made to that code. Organizing your code with GitHub allows you to safely make changes to and develop your code without fear of
irreparable damage. The commands that we will be discussing in detail are as follow:

- `git push` - sends changes from a local branch to a remote repo. 
- `git pull` - takes the changes from a remote branch and into your tracking branch, and then merges them into a local branch
- `git fetch` - retrieves changes from a remote repo into your tracking branch
- `git merge`- integrates changes from a tracking branch to a remote branch


Within GitHub, a few commands enable you to accomplish several things when developing. Understanding the difference between **Git Push**, **Git Pull**, **Git Fetch**, and **Git Merge**. is vital for you to be free to develop and innovate with your ideas safely. Before we begin, please note that, frequently, **Git Push** and **Git Pull**, are thought of as equal functions and are interchangeable. While both are similar, each does very different things.  

**Git Push** fundamentally manages and compares any changes you have made to your content(code) within your current local branch with any existing tracking branches connected to remote repositories. Comparing the original content to your new code allows your changes to incorporate or (push) into the remote branch without harming the original code. Using **Git Push** shares your code between your local branch and the remote branches or repositories, in effect, making your “remote branch resemble your local branch.” When using **Git Push**, please keep in mind that all commits in the remote branch must synchronize with your local branch

Next, let’s talk about **Git Pull** and synchronization. To synchronize your local branch, you must either use **Git Pull** or **Git Fetch** *with* **Get Merge** combined. Using **Git Pull** takes your current branch and “pulls” your changes into the tracking branch without changing your local branch. GitPull automatically performs a GitFetch immediately followed by **Git Merge**, thereby synchronizing your local branch with the tracking branch. Some developers prefer to use **Git Fetch** and **Git Merge** instead of **Git Pull**, to understand the changes set to merge into their branch before it happens. Using additional steps may be necessary, but if you are comfortable with your changes, using **Git Pull** works just as well.  

When using **Git Fetch**, you must additionally perform a “Git Merge origin/master”. **Git Fetch** retrieves your changes from a remote branch and inserts those changes into the tracking branch where the changes merge with the master utilizing **Git Merge**. “Master” customarily refers to the master branch. As noted, this is an additional step that may help the developer understand the changes made before merging. GitHub is an excellent tool, but one of many tools available for developers. GitHub is handy for programmers and developers that make or encounter many changes and revisions to source code. Github gives you the who, what, when, and where those changes occurred and are stored. With practice and patience, you will start recognizing the advantages of using a powerful tool like GitHub.

There are plenty of resources on the internet to help you dive further into using Github and these GitHub commands. Check out [GitHub Guides](https://guides.github.com/activities/hello-world/) to learn more.
