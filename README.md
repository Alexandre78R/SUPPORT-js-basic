# Support JS Basic 

Voici un support JS Basic basé sur un mini jeu : 

1 ) Résumé des fonctions :
- Connect | Param : (pseudo, password)
    - 1 ) Vérifier si les champs de connexion soient rempli.
    - 2 ) Vérifier si le pesudo existe bien.
    - 3 ) Vérifier que le mot de passe soit identique.
    - 4 ) Si le pseudo et le mot de passe est corrects changer le statutConnect à true.
    - 5 ) Si le pseudo et le mot de passe est corrects : Charger (changer) les informations de l'user dans la variable user.
    - 6 ) Si les informations de connexion ne sont pas correctes renvoyer un message d'erreur.
- zoneXp10Min
    - 1 ) Vérification si la personne est bien connectée !
    - 2 ) Vérification si la personne est bien niveau 10 au minimun 
    -   -  Si oui return : bon xp à vous dans cette zone de niveau 10 !
    -    - sinon return : attention vous n'avez pas le niveau nécessaire pour cette zone !
- searchUser  | Param : (pseudo)
    - 1 ) Vérification si la personne est bien admin 
        - Si oui : on ne renvoie rien pour l'instant, on continue dans la fonction ! 
        - Si non : return vous devez être administrateur pour utiliser cette fonctionnalité !
    - 2 ) Chercher le pseudo (en tableau)
        - Si on trouve un user ou plusieurs renvoyer un tableau avec les informations des users.
        - Si on ne trouve pas renvoyer un message : impossible de trouver un ou plusieurs user avec ce  ${pseudo}

