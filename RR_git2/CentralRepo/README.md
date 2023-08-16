# Exercise 5: simulating central repo with two locals
In your RR_git2 directory create a new, bare repository called “CentralRepo”
git init CentralRepo --bare

In your RR_git2 directory create a clone of the CentralRepo, named Dev1
git clone CentralRepo Dev1

In your RR_git2 directory create a clone of the CentralRepo, named Dev2
git clone CentralRepo Dev2

Set the local user.name for Dev1 repository to “Developer_1”
cd Dev1
git config --local user.name "Developer_1"

So far all repositories are empty. Let’s imagine:
Dev1 kick-starts the project by creating the branch with one commit and sending it upstream
echo "This will be the file with code" > code.R
git add .
git commit -m "Added the file with code"
git status
git push
git status

Dev2 wants to get up-to-speed so grabs the changes
git pull

Divergence without conflicts
(graphs will appear later in the week)


