Le fichier README.txt demandé

Je rajoute quelques mots à ce premier fichier pour voir comment çà se passe 
au niveau de GIT 

Bizarre ce message une fois la modif faite quand le faisgit commit -m
Est-ce que c'est parce que le fichier est resté ouvert?

En tout cas quand je fais git commit -am çà passe sans pb

Oui, c'est confirmé après une révision de la leçon : il faut faire -am sinon
il faut d'abord envoyer la commande "add" pur dire que l'on veut prendre en 
compte les modifs dans ce fichier puis la commande "commit -m "....."" pour 
prendre en compte les modifs et associer un commentaire pour la traçabilité