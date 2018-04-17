Run a simple webserver allowing access to all files in the current folder

Requirements:
* python 2

Initiate by "python webserver.py" on command prompt

Use in Openshift:
* deploy python 2 image
* Include GIT repo: 
       https://licdci01.bmwgroup.net:7993/scm/mrt1/testpages.git
* Include environmental value:
    APP_FILE = webserver.py


Clone:
* git clone https://qtb8117@licdci01.bmwgroup.net:7993/scm/mrt1/testpages.git


new repo and ready to be pushed:
* git init
* git add --all
* git commit -m "Initial Commit"
* git remote add origin https://qtb8117@licdci01.bmwgroup.net:7993/scm/mrt1/testpages.git
* git push -u origin master

Pull:
* https://licdci01.bmwgroup.net:7993/scm/mrt1/testpages.git

