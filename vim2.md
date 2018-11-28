***************************************
# Aide Vim 
***************************************

## Quelques Commandes 

| commande   | Description                                        | (terme anglais)   |
| ---------- | -------------------------------------------------- | ----------------- |
| a          | Entre en mode insertion apres le curseur           |                   |
| A          | Entre en mode insertion sur le dernier caractère   |                   |
| i          | Entre en mode insertion au niveau du curseur       | insert            |
| h          | Se déplacer vers la gauche                         |                   |
| j          | Se déplacer vers le bas                            |                   |
| k          | Se déplacer vers le haut                           |                   |
| l          | Se déplacer vers la droite                         |                   |
| $          | Aller en fin de ligne                              |                   |
| gg         | aller en debut de document                         |                   |
| G          | aller en fin de document                           |                   |
| v          | Entre en mode visuel                               |                   |
| <echap>    | Entre en mode normal                               |                   |
| <:>        | Entre en mode commande                             |                   |
| x          | suprime Le caractère sous le curseur               |                   |
| dd         | Suprime la ligne sous le curseur                   | delet             |
| dw         | Suprime le mot sur le curseur                      | delet word        |
| u          | Annulation de la dernière action                   |                   |
| yy         | Copie une ligne                                    |                   |
| yw         | Copie un mot                                       |                   |
| p          | Coller                                             |                   |
| :w         | Sauvegarder                                        |                   |
| :q         | Quitter                                            |                   |
| :q!        | Quitter sans enregistrer                           |                   |
| :wp        | Quitter et enregistrer                             |                   |
| ~          | Inverse la casse de la lettre sous le curseur      |                   |



| test             | test | test |
|------------------+------+------|
| test             | test | test |
| test             | test | test |
| un test plusieur |      |      |






******************************************************
##   VIM-PLUG   
*****************************************************



Liens :    

[vimawesome](https://vimawesome.com)  
[github_vim-plug](https://github.com/junegunn/vim-plug)



### 1ÈRE INSTALLATION  


Installer GIT:   
> $ sudo apt install git   

Installer CURL:
> $ sudo apt install curl

Dans un terminal saisir :  

>curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
>https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

Créer, si pas fait, le fichier [ ~/.vimrc ] ....... $ vim .vimrc

Insérer au début du fichier les lignes suivantes :

>call plug#begin()
>call plug#end()


**à chaque nouvel de plugin, il faudra mettre une ligne qui ressemble à la suivante entre les 2 précédentes :**

call plug#begin()
Plug ‘blablablabla’
call plug#end()


















