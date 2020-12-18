## TP Article / Utilisateur ORT Toulouse Décembre 2020 de BARDOUX Romain

* [Lien github pour cloner le projet](https://github.com/lechalet/article_user)

## Prérequis à installer
- PHP 7.4.7 (cli)
- Symfony CLI version v4.21.3
- Composer version 1.10.7

## Instruction à suivre pour installer le projet

- Cloner le projet à l'aide de la commande `git clone https://github.com/lechalet/article_user`
- Se déplacer dans le dossier **article_user** `cd article_user`
- Installer les dépendances du projet à l'aide de la commande `composer install`

## Connecter, créer et schématiser la base de donnée

- Configurer le fichier d'environnement pour connecter votre server de base de donnée
- Créer la base de donnée à l'aide de la commande `php/bin console d:d:c`
- Ajouter les champs de la base de donnée grâce aux entité du projet à l'aide des commandes suivante :
    - `php bin/console make:migration`
    - `php bin/console d:m:c`

## Profitez du contenue 

- Lancer votre server symfony à l'aide de la commande `symfony server:start`