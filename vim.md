***********************************
***	  aide pour vim		***
***********************************

#Quelques commandes:


|       commande                  |     Description                                                         |  
|-------------------------------- | ----------------------------------------------------------------------: |   
|  a                              |  Basculer en mode insertion                                             |       
|  A [shift+a]                    |  Basculer en mode Insertion et ajouter en fin de ligne                  |    
|  i                              |  Basculer en mode Insertion                                             |       
|	I [shift+i]               |	Insérer avant le premier caractère non-blanc de la ligne            |
|               v 	          |           Basculer en mode visuel (sélection)                           |
|   V [shift+v]                   |	Basculer en mode de ligne visuelle (sélection de ligne)             |
|     Ctrl+v                      | 	Basculer en mode bloc visuel (sélection de bloc – rectangulaire)    |
|         gv                      |	Re-sélectionnez la dernière sélection                               |  
|          o                      |Ajouter ligne après le curseur et se placer au début de cette nouvelle ligne |
|    O [shift+o]                  |Ajouter ligne avant le curseur et se placer en mode insertion au début de cette nouvelle ligne |
|        J [shift+j] 	          |   Joint la ligne suivante à la fin de la ligne courante                 |
|       C [shift+c]               |Basculer en mode remplacement (au lieu d’insertion) pour la ligne courante jusqu’à appui de la touche Esc |
cc 	Supprime le texte de la ligne courante et positionne le curseur au début de cette ligne
s 	Substitue le caractère et bascule en mode insertion
S [shift+s] 	Substitue la ligne et bascule en mode insertion
d 	Supprimer
dd 	Supprime la ligne entière
D [shift+d] 	Supprime jusqu’à la fin de la ligne
x 	Couper (supprimer) le caractère qui se trouve sous le curseur
X [shift+x] 	Couper (supprimer) le caractère qui se trouve avant le curseur
gu 	Mettre le caractère sous le curseur en minuscule
guw 	Mettre le mot à partir du curseur en minuscule
gub 	Mettre le mot avant le curseur en minuscule
guu 	Mettre la ligne en minuscule
gU
[gshift+u] 	Mettre le caractère sous le curseur en majuscule.
gUw
[gshift+uw] 	Mettre le mot à partir du curseur en majuscule.
gUb
[gshift+ub] 	Mettre le mot avant le curseur en majuscule.
gUU
[gshift+ushift+u] 	Mettre la ligne en majuscule
y 	Copie le caractère sous le curseur
yy 	Copier la ligne de texte qui se trouve sous le curseur. Pour copier plusieurs lignes en même temps, précéder yy du nombre de lignes concernées
yyn 	Copie la ligne courante, et les n lignes suivantes dans le tampon
Y 	Copie jusqu’en fin de ligne
p 	Colle
P [shift+p] 	Colle avant le curseur / la ligne
r<char 	Remplace le caractère sous le curseur par le <char entré
R [shift+r] 	Basculer en mode remplacement
: 	Basculer en mode commande
/ 	Rechercher
u 	Annuler
Ctrl+r 	Refaire (annuler l’annulation)
U [shift+u] 	Refaire (annuler l’annulation)
>> 	Indenter la ligne
[up|down] 	Indenter la ligne du dessus | dessous
<< 	Désindenter la ligne
< [up|down] 	Désindenter la ligne du dessus | dessous
Ctrl+f 	Scroll down
pagedown 	Scroll down
Ctrl+b 	Scroll up
pageup 	Scroll up
Ctrl+u 	Scroll up à moitié de page
Ctrl+d 	Scroll down à moitié de page
zz 	Centre la vue sur le curseur
ga 	Affiche le code du caractère sous le curseur
. 	Répéter le dernier changement
== 	Aligne la ligne
= 	Aligne les lignes
~ 	Change la casse
Ctrl+a 	Incrémente le nombre
Ctrl+x 	Décrémente le nombre
Ctrl+o 	Aller à la précédente modification
Ctrl+i 	Aller à la prochaine modification
gt 	Bascule sur l’onglet suivant
gT 	Bascule sur l’onglet précédent
gqq 	Formater la ligne
gq 	Formater les ligne
q. / q 	Commencer / terminer l’enregistrement macro utilisant le registre macro nommée
Splitter la fenêtre et navigation dans les fenêtres splittées
Combinaison de touches 	Action
Ctrl+wq 	Ferme la fenêtre splitter courante
Ctrl+ws 	Split horizontalement
Ctrl+wS 	Split horizontalement
Ctrl+wCtrl+s 	Split horizontalement
Ctrl+wv 	Split verticalement
Ctrl+wCtrl+v 	Split verticalement
Ctrl+wh 	Basculer sur la fenêtre de gauche
Ctrl+wCtrl+h 	Basculer sur la fenêtre de gauche
Ctrl+wleft 	Basculer sur la fenêtre de gauche
Ctrl+wj 	Basculer sur la fenêtre en-dessous
Ctrl+wCtrl+j 	Basculer sur la fenêtre en-dessous
Ctrl+wdown 	Basculer sur la fenêtre en-dessous
Ctrl+wk 	Basculer sur la fenêtre au-dessus
Ctrl+wCtrl+k 	Basculer sur la fenêtre au-dessus
Ctrl+wup 	Basculer sur la fenêtre au-dessus
Ctrl+wl 	Basculer sur la fenêtre de droite
Ctrl+wCtrl+l 	Basculer sur la fenêtre de droite
Ctrl+wright 	Basculer sur la fenêtre de droite
Ctrl+ww 	Basculer sur la vue suivante
Ctrl+wCtrl+w 	Basculer sur la vue suivante
Ctrl++ 	Agrandir la fenêtre actuel
Ctrl+– 	Réduit le fenêtres actuel
Ctrl+= 	Égalise à nouveau la taille des fenêtres
Ctrl+r 	Échange la position des fenêtres
Ctrl+R
[Ctrl+shift+r] 	Échange la position des fenêtres
Ctrl+shift+{h | j | k | l} 	Déplacement ou split horizontalement / verticalement.
Les touches h, j, k et l permettent de se déplacer d’un fenêtres à l’autre, utilisé en MAJUSCULE elles déplacent les fenêtres
Navigation
Combinaison de touches 	Description
h 	Gauche
left 	Gauche
backspace 	Gauche
j 	Bas
down 	Bas
enter 	Aller au premier caractère non-blanc vers le bas
k 	Haut
up 	Haut
– 	Aller au premier caractère non-blanc vers le haut
l 	Droite
right 	Droite
space 	Droite
$ 	Aller en fin de ligne
end 	Aller en fin de ligne
0 	Aller à la colone 0 (début de ligne)
home 	Aller à la colone 0 (début de ligne)
^ 	Aller au premier caratère de la ligne
f<char> 	Chercher le caractère <char> suivant
F<char> 	Chercher le caractère <char> précédent
t<char> 	Aller au caractère <char> suivant
T<char> 	Aller au caractère <char> précédent
; 	Répéter la dernière action t<char> ou
f<char>
, 	Répéter la dernière action t<char> ou
f<char>
n 	Trouver le suivant
N [shift+n] 	Trouver le précédent
gg 	Aller la la première ligne du document
G [shift+g] 	Aller la la dernière ligne du document
w 	Aller au mot suivant
W [shift+w] 	Aller au MOT suivant (un mot ici est un ensemble de caractère sans espace)
b 	Aller au mot précédent
B [shift+b] 	Aller au MOT précédent (un mot ici est un ensemble de caractère sans espace)
e 	Aller à la fin du mot
E 	Aller à la fin du MOT (un mot ici est un ensemble de caractère sans espace)
ge 	Aller à la fin du mot précédent
gE
g [shift+e] 	Aller à la fin du MOT précédent (un mot ici est un ensemble de caractère sans espace)
| (pipe) 	Aller la la colone de l’écran
% 	Aller au prochain caractère correspondant s’applique aux caractère ouvrant et fermant : (),{},[],<>
m
[a-zA-Z] 	Définit un marqueur [a-zA-Z]
` 	Aller au marqueur [a-zA-Z]
‘ 	Aller à la ligne du marqueur [a-zA-Z]
[[ 	Aller au début du crochet précédent
]] 	Aller à la fin du crochet précédent
[] 	Aller au début du crochet précédent
][ 	Aller à la fin du crochet précédent
* 	Aller à la prochaine occurrence du mot sous le curseur
# 	Aller à la précédente occurrence du mot sous le curseur
H [shift+h] 	Aller à première ligne de l’écran
M [shift+m] 	Aller à ligne au milieu de l’écran
L [shift+l] 	Aller à dernière ligne de l’écran
gj 	Aller à la prochaine ligne visuelle
gk 	Aller à la précédente ligne visuelle
Accès au commandes en mode insertions

Ces raccourcis permettent de faire d’exécuter des commandes ou d’exécuter des raccourcis du mode normal sans quitter le mode insertion.
Combinaison de touches 	Action
Ctrl+d 	Désindenter
Ctrl+t 	Indenter
Ctrl+e 	Copier le caractère de la ligne du bas
Ctrl+y 	Copier le caractère de la ligne du haut
Ctrl+w 	Supprimer le mot avant le curseur
Ctrl+r [a-zA-Z] 	Insérez contenu du registre
Ctrl+o 	Basculer en mode normal pour la prochaine commande
Ctrl+a 	Incrémente le nombre
Ctrl+x 	Décrémente le nombre
