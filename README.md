FreezeTag
=========

Français

Originalement 5v5 max, évolution possible.

Equipe contre équipe, le but est de désarmer chaque joueur de l'équipe adverse pour gagner un round. Si une équipe atteint le score limite et a une avance de deux points sur l'équipe adverse, l'équipe gagne le match. Chaque joueur à 3 points d'armure et ne peux utiliser que les roquettes comme arme. Lorsqu'un joueur a 1 point d'armure, il est considéré comme désarmé et est incapable de tirer et de se déplacer librement. Je n'ai pas trouvé, via ManiaScript comment "freezer" proprement un joueur car la variable que j'utilise ne peut pas avoir de valeur nulle :

Code: Select all
    Real CSmPlayer::SpeedPower

    Values in range (0.100000-1.000000)


Peut-être y a t-il une autre solution, je ne sais pas. Lorsque un allié est désarmé, vous avez la possibilité de le libérer. Pour ce faire, vous devez littéralement le toucher physiquement (comme si vous avez le profond désir de lui faire un bisou :thx: ). Ainsi il re-spawnera tout neuf et pourra retourner sur le champ de bataille.

Le respawn (backspace) est désactivé pour l'instant pour éviter que les joueurs désarmés se libèrent tout seul. Si vous tombez dans l'offzone, votre équipe prend un point de pénalité.

Foire aux questions

Ton mode a l'air de déchirer du bamboo, peut-on tester ton mode ?
Oui, dans le Title Pack Storm en multi, cherchez "freezetag" et vous trouverez deux serveurs TheGamer avec le mode.

Peut-on utiliser ton script pour nos serveurs ? Ou tu vas garder ton script vilain ?
Oui, le script est disponible ici : Clik issi yo free money money !

Peut-on avoir le MapType pour faire des maps sur ton mode ?
Oui, le MapType est disponible ici : Clik issi pr savoer si t riche lol

Notez que le mode n'est pas à son stade final. Ainsi je mettrai à jour ce post en fonction de l'évolution du mode.

Evolutions principales futures
- Amélioration de l'auto-balance
- Ajout de l'option RailGun Only
- Correction de bugs
- Division du script en deux modes : Free et Pro. Free permettra du NvN et Pro sera un mode compétitif (2v2 ou 3v3 ou 4v4 ou 5v5)

Merci à ceux qui ont eu l'occasion de tester mon mode et d'avoir déjà donné des retours. Merci à toi, qui va peut-être lire cette phrase et ce post ou qui va peut-être laisser un commentaire ou qui va peut-être tester mon mode.
