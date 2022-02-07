GITHUB
— Upload Existing project on Github — 

Install GitHub on Linux
> sudo apt install git

> git --version

> git config —global user.email “rugvedm12@gmail.com”

> git config —global user.name ”rugved88”

step 1:  Go to the desired directory using cd and run this command
> git init

step2: see the status of the directory in red colour.
> git status

step 3: Add all the files in .git
> git add .

step 4: commit it
> git commit -m “first commit”

step 5: link the online repository origin with kernel
> git remote add origin HTTP:// Your Repo address

step 6: Push all the files in the repo
> git push -u origin master

note: username: rugved 88
password: Personal Access Tokens (Github setting)

—Extra —

To remove .git file
> rm -rf .git

Cheak remotes of git 
> git remote -v


— Heroku Deployment —
Create requrements.txt, Procfile & install 
> pip3 install gunicorn

> heroku login

> heroku create -a example-app

> git remote -v

> heroku git:remote -a example-app

> git add .

> git commit -m “first commit”

> git push heroku master
