## GLOBAL RESET

A bolier plate code containing basic global reset for all web project

## USAGE

echo "# global reset" >> README.md
git clone https://github.com/kivgcLOUDs/global-reset.git new-project-name
cd new-project-name
rm -rf .git # strip the old git history
git init
git add .
git commit -m "Initial commit from global reset boilerplate"
git branch -M main
git remote add origin https://github.com/kivgcLOUDs/new-project-name.git
git push -u origin main

# FINALLY

npm install
