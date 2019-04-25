basicProjectFile

When beginning a new project, use this setup procedure.

create new repository:
    -on github.com

create file structure for new repository on the command line:

    -mkdir <name>
    cd <name>

add file:
    -echo   >> README.md

make a commit:
    -git init
    git add README.md
    git commit -m \"first commit\"

link repo to computer :
    -git remote add origin https://github.com/cristalvi/\<name\>.git
    git push -u origin master

Now, add the rest of the file structure:

index.html
about.html
contact.html
page.html
css folder
img folder
includes folder
