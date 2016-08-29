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

heroku create my-popup
