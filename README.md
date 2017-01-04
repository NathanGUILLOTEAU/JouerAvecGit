## Fonctionnement de git avec github

##Cloner le repo : 

Git init

Git clone https://github.com/NathanGUILLOTEAU/JouerAvecGit.git

git remote add origin https://github.com/NathanGUILLOTEAU/JouerAvecGit.git

##Quotidien 

# Local vers Github

(develop)

Git add . 

Git commit -m "Blabla" 

Git checkout master 

(master)

git merge develop 

git push origin master

git checkout develop

# Github vers Local

(master)

git pull

git checkout develop

(develop)

git merge master