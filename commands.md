# Git Commands

# Basic setup
git --version                                            # check git version
git config --global user.name "Your Name"
git config --global user.email "you@email.com"

# Create/initialize Repository
git init                                # initialize a new git repo
git clone <repo-url>                    # copy an existing repo

# Check Status & History
git status                      # check file status
git log                         # commit history
git log --oneline               # short history

# Add & Commit Files
git add file.txt                    # add single file
git add .                           # add all files
git commit -m "message"
