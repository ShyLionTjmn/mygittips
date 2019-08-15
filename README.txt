== testing ssh with github ==

== Preparing to publish code to github ==
Create new repository on github site

cd myproject
git init
git config --global user.name "Sergey Klyusov"
git config --global user.email "donot@email.me"

git remote set-url origin ssh://git@github.com/ShyLionTjmn/newrepname.git

== add new files to rep ==
git add mysource.go
git add README.txt

== commit changes files ==
git commit -a -m "some minor changes made"

== push changes to github ==
git push -u origin master
