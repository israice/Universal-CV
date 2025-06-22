
# About
- universal CV based html+css only

# DEV Log
## v001
- PROJECT CREATED DATE 2025.06.22
- connected index.html with style.css
- added 2 main containres with flex-grow
## v002
- avatar image resized to 100px 100px
- left container items centerned using text-align center


# Github CHEATSHEET
## Load last updates and replace existing local files
git fetch origin; git reset --hard origin/master; git clean -fd  

## Select a hash from the last 10 commits
git log --oneline -n 10  

## Use the hash to get that exact version locally
git fetch origin; git checkout master; git reset --hard 1eaef8b; git clean -fdx  

## Update repository
git add .  
git commit -m "left container items centerned using text-align center"  
git push
