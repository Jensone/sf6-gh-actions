# GitHub Actions - Test

Pour illustrer la mise en place d'un workflow GitHub Actions, nous allons utiliser un projet Symfony 6.

## Prérequis de l'environnement

- docker-compose

Docker-Compose est un outil qui permet de décrire et gérer des applications multi-conteneurs. Il permet de définir les services, les réseaux et les volumes nécessaires pour lancer une application.

## Création du projet

Suivre les étapes de l'article suivant pour créer un projet Symfony 6 : [Créer un projet Symfony 6](https://medium.com/@meherbensalah4/how-to-dockerize-symfony-project-f06bcd735308)

## Configuration du workflow

L'objectif est de créer un workflow qui permet de tester l'application Symfony 6 dès qu'un push est effectué sur une branche spécifique.

Pousser le projet sur GitHub et créer une branche `tests`.

Ajouter le workflow shivammathur/setup-php@v2 dans le fichier `.github/workflows/test.yml`.

Préparer le fichier `test.yml` :

```yaml
```

Lancer un essai en faisant un commit sur la branche `tests`.
