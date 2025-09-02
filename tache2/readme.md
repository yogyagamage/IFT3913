# Tâche 2

La tâche 2 se fait en binômes. Quand un binôme est formé, il fait une 'pull request' sur ce répertoire pour ajouter un sous-répertoire de la forme 'NOM1-NOM2/'. Ce répertoire inclut un fichier readme.md dans lequel les étudiants indiquent leur nom et prénom.

## Instructions pour la tâche 2

Pour la tâche 2, chaque binôme doit accomplir les étapes suivantes:

- sélectionner entre une et 3 classes de [graphhopper]() qui ont déjà des tests, mais qui ne couvrent pas 100% du code
- ajouter 7 cas pour les classes sélectionnées
- documenter précisément chaque cas de test: nom du test, intention du test (quel comportement est testé), motivation des données de test choisies, explication de l'oracle (comment déterminer le comportement attendu)
- ajouter [pitest](https://pitest.org/) au projet
- exécuter une analyse de mutation sur les classes sélectionnées
- calculer le score de mutation avec les tests originaux pour les classes sélectionnées
- calculer le score de mutation avec les nouveaux tests et déterminer si les nouveaux tests détectent de nouveaux mutants. Si oui, expliquez quels mutants sont détectés et pourquoi. Si non, ajoutez des tests pour détecter au moins 2 nouveaux mutants et documentez / justifiez votre démarche.
- ajouter la librairie [java-faker](https://github.com/DiUS/java-faker) au projet
- écrire au moins un nouveau test qui utilise java-faker 


## Instructions pour rendre la tâche 2

Une fois la tâche accomplie, les étudiants font une nouvelle 'pull request' sur le même sous-répertoire et ajoutent les informations suivantes dans le fichier readme:
- un lien vers le référentiel (repository) Github qui inclut leur tâche
- un lien vers la page qui documente les nouveaux test unitaires
- le taux de couverture final après l'ajout des tests

La date limite pour la seconde 'pull request' est indiquée sur la [page principale](../README.md/#tâche-2-tests-unitaires-automatiques) du cours.
