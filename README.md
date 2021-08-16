# git-upload
Useful Guide for uploading projects using git

# IMPORTANT THING:

Git is an version source control, and isn't from GitHub, Git was developed by Linus Torvalds and GitHub is a host for proyjects that can be uploaded with git, so, they aren't the same thing 

## First of all, you will need to know you need to have git installed in your pc, if you have it, let's continue

- Create a repository on github

- Use `git init` to start a repository ON GIT

- Use `git add remote origin link` changing the `link` word to your git link (For Example: it will be like `https://github.com/HankB-o-t/git-upload.git`)

- Then, do `git add "yourfile"` to upload a single file, but if you want to upload all the files, do `git add .`

#### Check with `git status` if the files are on git, if they are red, there aren't uploaded, if they're green, all it's ok.

- Do `git commit -m "your commit"` to commit the changes.

- And finnaly do `git push origin master` (`master` is the branch name, if you will have multiple branches, rename it)

#### You Have It!


### Some commands to know

- `git clone link` clones a repository from github, in link put the link

- `git branch` to check the branch of the repository

## Some extensions for VSCode

- GitLens: is useful for a lot of things related with git, you can check the commits and a lot of things more

- GitHub Repositories: A remote explorer for GitHub and check things

- GitHub Pull Requests and Issues: If you use a lot of GitHub and you do pull requests, this extension is for you! it have things of pull requests and you can check issues!

( GitLens isn't from GitHub, because GitHub is not the same thing as git)
