### Setup ctags (to navigate between methods definitions)
```
ctags -R --exclude=bower_components --exclude=public --exclude=assets --exclude=tmp --exclude=.git --exclude=.js
--exclude=.haml --exclude=.css --exclude=node_modules -f ./.tags .
```
