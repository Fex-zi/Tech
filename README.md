# Tech
#clone git
git clone https://github.com/ggelashvili/learnphptherightway-project.git

#clone git branch
git clone -b 1.31 https://github.com/ggelashvili/learnphptherightway-project.git

# Create a new branch and go into it
git checkout -b feature-login

#OR

#Seperate Function to create and enter into branch
git branch feature-login

git checkout feature-login

# Stage and commit your changes
git add .

git commit -m "login functionality"

# Push your new branch to the remote repository
git push -u origin feature-login

# List all local branches
git branch

# List all branches (local and remote)
git branch -a

# Delete a local branch
git branch -d branch-name

# Delete a remote branch
git push origin --delete branch-name

# Later, pull updates from remote
git pull origin feature-login

git add .

git commit -m "any message"

git push

#force pull

git fetch origin

git reset --hard origin/main

#End force pull

#Reset to a particular commit
git log 

#copy the commit ID
git reset --hard 7098126a7bf0e08851395610940fd6af6342baa1

#End Reset to a particular commit

#branch new-feature is the branch name
git branch new-feature
git checkout new-feature



#Then normal add, commit, push---end branch

pwd                    # Print current directory (where you are)

ls                     # List files and folders in current directory

ls -la                # List all files (including hidden) with details

cd directory_name        # Move into a directory

cd ..                   # Move up one directory

cd                      # Go to home directory

cd ../../              # Go up two directories

cd /path/to/directory  # Go to specific path
