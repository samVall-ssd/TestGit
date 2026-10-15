---
marp: true
theme: default
paginate: true
backgroundColor: grey
color: white
---
<style>
img{
    border-radius: 30px;
    border: solid black 5px;
    margin-left: 260px;
    margin-top: 40px;
}
</style>
# Comment installer Git?

* Pour commencer il faut aller sur le site

![w:580](./images/Capture%20d’écran_8-10-2026_144712_git-scm.com.jpeg)

---
# Une page va souvrir

* Il faudra apuiller sur installer puis suivre les instructions

![w:580](./images/2026-10-08%2014_48_29-ex4%20_%20Explorateur%20de%20fichiers.png)

---
# Ensuite il faut créer un terminal et faire ces codes:

* Git
* Git init
* Git config user.name "Nom"
* Git config user.email "ton email"

---

# Après tout ça tu vas pouvoir faire un projet html

* Maintenant a chaque fois que tu modifiras ton code tu vas pouvoir faire un comit et voir les changemants
![w:600](./images/2026-10-08%2015_59_24-Greenshot.png)

---
# GIT Commands
 
* <mark>Git init</mark> transforme le répertoire courant en 
un référentiel Git

* <mark>Git clonne</mark> commande pour cloner un dossier git du 
repository distant sur son ordinateur 

* <mark>Git add</mark> met à jour l’index avec le contenu du dossier courant
---
# GIT commands

* <mark>Git commit</mark> enregistre un instantané des 
modifications 

* <mark>Git push</mark> est une commande qui récupère le contenu d’un dépôt local pour le mettre sur un dépôt distant pour l'utiliser il faut écrire : “git push <remote> <branch>”

* <mark>Git branch</mark> est utilisé pour faire le développement d’une fonctionnalité en parallèle sans “parasiter” le travaile sur la “branche” principale
---
# GIT commands

* <mark>Git fetch</mark> cette commande permet de récupérer les 
modifications depuis un remote repository 
au local repository

* <mark>Git rebase</mark> un rebase va “sérialiser” l’historique et 
visuellement on verra que la fonctionnalité b 
à été faite après la a

* <mark>Git merge</mark> est une commande qui vous permet de fusionner des branches depuis Git

---
# Git commands

* <mark>Git pull</mark> la commande git pull est utilisée pour faire un fetch du contenu d'un dépôt distant 
et pour le télécharger, puis pour mettre à jour immédiatement le dépôt local qui correspond à ce contenu. 

