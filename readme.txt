- git,https://github.com
- nodejs https://nodejs.org/

- npm install bootstrap-material-design --save
- npm install http-server -g

- http://getbootstrap.com/css/

how to deploy on github pages
https://help.github.com/articles/creating-project-pages-manually/
more info
https://help.github.com/articles/pushing-to-a-remote/


git checkout gh-pages

make changes

git add .
git commit -m "description"
git push --set-upstream origin gh-pages

to return to master

git checkout master


instruction to submit data to google docs
https://wiki.base22.com/pages/viewpage.action?pageId=72942000

current temp doc

https://docs.google.com/spreadsheets/d/1sAgFos2Pg0cZjsEnBq6fe3YMeoLGyNc-VbI16kZpwqQ/edit?usp=sharing

those data depend on you doc
            url: "https://docs.google.com/a/YOURDOMAIN.com/forms/d/19UpeEL7wNsXvcyT-qj9r_T831sMSG2QIxOXt9uyQB4o/formResponse",
            
            data: {"entry.1785970281" : name, "entry.1152430972" : test},
make sure you set proper value there