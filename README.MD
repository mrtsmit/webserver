Run a simple webserver allowing access to all files in the current folder

Requirements:
* python 2

Initiate by "python webserver.py" on command prompt

Use in Openshift:
* deploy python 2 image
* Include GIT repo: 
       https://github.com/mrtsmit/webserver.git
* Include environmental value:
    APP_FILE = webserver.py


Clone:
* git clone https://github.com/mrtsmit/webserver.git


new repo and ready to be pushed:
* git init
* git add --all
* git commit -m "Initial Commit"
* git remote add origin https://github.com/mrtsmit/webserver.git
* git push -u origin master

Pull:
* https://github.com/mrtsmit/webserver.git

