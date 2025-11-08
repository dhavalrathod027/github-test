# install gh (done once)
gh --version

# login (done once)
gh auth login

# in your project folder
git init
git add .
git commit -m "Initial commit"
git branch -M main

# create + push repo on GitHub
gh repo create my-html-project --public --source=. --remote=origin --push