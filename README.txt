git init
// create files...
git add .
git config --global user.mail "sthadri@gmail.com"
git commit -m "<message>" // locally
// create repo in git 
git remote add <name> <url>
git push -u <name> <branch>
for example:
	git remote add origin https://github.com/talhad/popup.git
	git push -u origin master

update:
git add . 		
git commit -m "commit"
git push

git status	
	


virtualenv venv
venv\Scripts\activate
pip install flask
pip freeze > requirements.txt
python hello_world.py //for checking

git add . 		
git commit -m "commit"

heroku create my-popup

heroku app:info my-popup
	- xxx.git

git remote add heroku xxx.git
git push heroku master