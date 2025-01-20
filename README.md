# Documentation du tuto GitHub avec Git

## Initialisation du dépôt

'''bash
git init
git remote add origin HTTPS_REPO
'''

## Rédiger un comit

'''
Titre du commit

Description de notre commit avec des informtions sur l'évolution du projet
'''

## Envoyer un commit sur le dépôt distant

'''bash
git add .
git comit -m "Titre du commit"
git push origin master
'''


## Création d'une branche

'''bash
git checkout -b NOM_BRANCHE
'''
Pour les bonnes pratiques, on va intégrer la notion de revue de code, pour cela on va créer une branche, faire des modifications, les envoyer sur le dépôt , puis créer une pull request pour demander une revue de code.