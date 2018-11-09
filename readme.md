# Working directory
- Area where all of our files and directoroies and changes are living all the time


# staging area
- Files and directories that we explicitly add to the staging area

# Repository
- Where all our snapshots are stored
 


git init   - initialize git in current folder

git status   - current staus

git add   - add files to be tracked

git add .   - adds all files currently staged
git add *.html   - adds all html files
git add *.<filetype>   - adds all files of specied file type
git add -A   - add all files and folders from current directory

git reset HEAD <file>   - removes file from staging area

git commit   - making a checkpoint in time with changes that were added
git commit - m "message"   - commits with message

git log   - shows history of snap shots

git branch   - list all braches in repository
git checkout -b 'branch_name'   - create and switch to new branch
git checkout <branch_name>   - switch to existing branch_name

ls -a - shows hidden folders
rm -rf - removes git from folder

ignoring files
touch .gitignore
rename a file  - mv <oldfilename> <newfilename>

q   - exit out log