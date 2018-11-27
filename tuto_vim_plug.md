#VIM-PLUG
Liens :
[vimawwesome](https://vimawesome.com "link vim")
[github](https://github.com/junegunn/vim-plug)
##1ÈRE INSTALLATION
Installer GIT .......................................... $ sudo apt install git
Installer CURL ....................................... $ sudo apt install curl
Dans un terminal saisir :
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
Créer, si pas fait, le fichier [ ~/.vimrc ] ....... $ vim .vimrc
Insérer au début du fichier les lignes suivantes :
call plug#begin()
call plug#end()
À CHAQUE NOUVEL AJOUT DE PLUGIN, IL FAUDRA METTRE UNE LIGNE QUI
RESSEMBLE À LA SUIVANTE ENTRE LES 2 PRÉCÉDENTES :
call plug#begin()
Plug ‘blablablabla’
call plug#end()
AJOUTER UN PLUGIN
RDV chez https://vimawesome.com
Chercher un plugin et faire ce qui est dit :
1) insérer la ligne qui dit Plug ‘blablabla’ dans le fichier [ .vimrc ]
2) enregistrer avec :w
3) forcer la lecture du fichier de configuration avec :source %4) installer avec :PlugInstall
####AU BESOIN :
Pour mettre à jour les plugins ....... :PlugUpdate
Pour supprimer les plugins .......... :PlugClean
Voir le status des plugins ............. :PlugStatus
Mais encore...
Ce qui est sympa avec Vim-plug est que l’on peut mettre des conditions dans les plugins
Plug 'SirVer/ultisnips' | Plug 'honza/vim-snippets'
ici vim-snippets dépends de ultisnips
On charge paresseusement les plugins
Plug 'StanAngeloff/php.vim', { 'for': 'php' }
Je n’ai besoin du plugin php-vim que si j’utilise un fichier PHP.
Plug 'scrooloose/nerdtree', { 'on':
Je charge le plugin que si je l’appelle.
'NERDTreeToggle' }
