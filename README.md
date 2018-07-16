# JobFeed-test

#### HTTPS ############################################

# URL

https://github.com/DoE-user-a/JobFeed-test.git

# create a new repository on the command line

echo "# JobFeed-test" >> README.md (added)
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/DoE-user-a/JobFeed-test.git
git push -u origin master

# push an existing repository from the command line

git remote add origin https://github.com/DoE-user-a/JobFeed-test.git
git push -u origin master

#### SSL ##############################################

# URL

git@github.com:DoE-user-a/JobFeed-test.git

# create a new repository on the command line

echo "# JobFeed-test" >> README.md (added)
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:DoE-user-a/JobFeed-test.git
git push -u origin master


# push an existing repository from the command line

git remote add origin git@github.com:DoE-user-a/JobFeed-test.git
git push -u origin master

#### My GIT commands #################################


# PULL INIT (first-time)
git clone https://github.com/DoE-user-a/JobFeed-test.git {working-directory}


# PULL (update)
git pull


# PUSH to remote
git push origin {branch-name} (Try to push only to a branch)
git push (works from local branch)

# commit local
(you must know)

# code commenting, branch naming
(future)
