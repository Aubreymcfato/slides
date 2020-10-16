
Luogo per slides collaborative e online, scritte in markdown.

### Per creare una nuova serie di slides

+ Copia cartella esistente nel repo in locale. 
+ Cambia nome cartella, modifica metadati `index.html`, lavora su quello.

### Per lavorare sulle slides
+ Per feedback immediati sul layout, apri `index.html` con il browser.
+ Ogni tanto, fai il commit delle modifiche al file. Prima al `master`, ma soprattutto al `gh-pages`:

    `git add .` or `git add *`
    `git status // to see what changes are going to be commited`
    `git commit -m 'Some descriptive commit message'`
    `git push origin master`

    `git checkout gh-pages` // go to the `gh-pages branch`
    `git rebase master` // bring `gh-pages` up to date with `master`
    `git push origin gh-pages` // commit the changes
    `git checkout master` // return to the `master` branch
 
