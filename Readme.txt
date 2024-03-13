# Git and GitHub Cheat Sheet
- Aim is to learn git and github...

## Basics

### Initialize Git Repository
- `git init`: Initialize a new Git repository in the current directory.

### Clone Repository
- `git clone <repository_url>`: Clone a repository from a remote URL to your local machine.

### Configure Git
- `git config --global user.name "Your Name"`: Set your name for Git commits.
- `git config --global user.email "youremail@example.com"`: Set your email for Git commits.

### Add and Commit Changes
- `git add <file>`: Add changes in a file to the staging area.
- `git commit -m "Your commit message"`: Commit staged changes with a descriptive message.

### Push Changes
- `git push origin <branch>`: Push committed changes to a remote repository.

### Pull Changes
- `git pull origin <branch>`: Pull changes from a remote repository to your local repository.

## Branching

### Create Branch
- `git branch <branch_name>`: Create a new branch with the specified name.

### Switch Branch
- `git checkout <branch_name>`: Switch to the specified branch.

### Create and Switch Branch
- `git checkout -b <branch_name>`: Create and switch to a new branch in one step.

### Delete Branch
- `git branch -d <branch_name>`: Delete the specified branch.

## Merging

### Merge Branch
- `git merge <branch_name>`: Merge changes from the specified branch into the current branch.

## Remote Repositories

### Add Remote
- `git remote add <name> <repository_url>`: Add a remote repository with the specified name and URL.

### Remove Remote
- `git remote remove <name>`: Remove the remote repository with the specified name.

## GitHub

### Create Repository
- Go to GitHub > "+" icon > "New repository" to create a new repository online.

### Push to GitHub
- After adding changes locally, push them to GitHub using `git push origin <branch>`.

### Pull from GitHub
- Pull changes from GitHub using `git pull origin <branch>` to update your local repository.

### SSH Authentication
- Use SSH for secure authentication with GitHub to avoid entering credentials repeatedly.

### Git Ignore
- Create a `.gitignore` file to specify files and directories Git should ignore.

### README
- Write a README file to provide information about your project, including setup instructions, usage, and contribution guidelines.

## Troubleshooting

- If you encounter conflicts during a merge or pull, resolve them manually and commit the changes.

## Resources

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Guides](https://guides.github.com/)

