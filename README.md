# Task 2 - Git and version control

  
Version control is like a time machine for your files. Imagine you're working on a project, and as you make changes, the version control system keeps track of every modification you make. It stores different snapshots of your project at different points in time.

## 1. Explaining version control

Here's a simple analogy:

1.  **Initial Snapshot (Commit):** Think of it as taking a photo of your project when you start working on it. This is the first version, and it's saved.
    
2.  **Making Changes:** As you make changes to your project (edit a document, add new features, etc.), the version control system keeps track of these modifications.
    
3.  **New Snapshots (Commits):** Each time you make a significant change and want to "save" it, you take another snapshot (commit). These snapshots are like different versions of your project.
    
4.  **Go Back in Time:** If something goes wrong or you want to see how your project looked at a specific point in the past, you can go back to that snapshot. It's like using the time machine to revisit an earlier state of your project.
    
5.  **Collaboration:** If you're working with others, version control allows multiple people to work on the same project simultaneously. The system helps merge changes made by different team members, ensuring a smooth collaboration.

## 2 Differnce between git and github
**Git:**

-   **Definition:** Git is a distributed version control system (DVCS) that allows you to track changes in your source code during software development.
-   **Usage:** Git is used for local version control on your computer. It helps you manage and keep track of changes to your project's files over time.

**GitHub:**

-   **Definition:** GitHub is a web-based platform that uses Git for version control. It provides a centralized hub for hosting and collaborating on Git repositories.
-   **Usage:** GitHub is a hosting service for Git repositories. Developers can use GitHub to store their Git repositories in the cloud, making it easier to collaborate with others, track issues, and manage project workflows.

## 3 Three other github alternatives
Other alternatives of github includes:

- Gitblab
- Bitbucket
- SourceForge


## 4 Difference between git fetch and git pull
Both `git fetch` and `git pull` are commands in Git, but they serve different purposes:

**Git Fetch:**

-   **Purpose:** `git fetch` is used to download changes from a remote repository to your local repository, but it does not automatically merge those changes into your working directory.

**Git Pull:**

-   **Purpose:** `git pull` is a combination of two actions: fetching changes from a remote repository and automatically merging those changes into your current working branch.


## 5 Git rebase explanation

`git rebase` is a command used in Git to change the base of your current branch. It's like rewriting the history of your changes to make them look as if they were based on the latest version of another branch. This can result in a cleaner and more linear project history.

Here's an analogy:

Imagine you are working on a document, and while you're doing that, someone else makes changes to the same document. With `git rebase`, instead of adding your changes on top of the changes made by others (like with `git merge`), you go back in time, apply their changes first, and then apply your changes on top of the updated version. It's like rearranging the order of changes to keep everything in a neat line.

The basic command for `git rebase` is:


`git rebase <base_branch>` 


 `<base_branch>` is the branch you want to rebase onto.

## 6 Explaining git-cherry-pick in simple terms

`git cherry-pick` is a command in Git that allows you to copy a specific commit from one branch and apply it onto another branch. It's like plucking a single commit from a tree and adding it to a different branch, without bringing along the entire branch.

Here's a simple analogy:

Imagine you have a tree with different fruits on different branches. If you want just one apple from a branch and add it to a different branch, you'd use `git cherry-pick`.

The basic command for `git cherry-pick` is:

`git cherry-pick <commit_hash>` 

`<commit_hash>` is the unique identifier for the commit you want to pick.