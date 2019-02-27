# how-to-change-git-and-upload-node-to-github
This is a repo to remind me hot to upload my web app @github. 


If you do git remote -v you should see heroku listed.

It will look something like:

heroku  git@github.com:my-app-staging.git (fetch)
heroku  git@github.com:my-app-staging.git (push)

Delete that remote...

git remote rm heroku

...and then add the new one

git remote add heroku git@heroku.com:my-app-staging-new.gitYou need to change your git remote.

If you do git remote -v you should see heroku listed.

It will look something like:

heroku  git@github.com:my-app-staging.git (fetch)
heroku  git@github.com:my-app-staging.git (push)

Delete that remote...

git remote rm heroku

...and then add the new one

git remote add heroku git@heroku.com:my-app-staging-new.git
