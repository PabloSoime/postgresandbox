# Challenges

## 1 - Script de setup de PostgreSQL

Faire un script de setup de PostgreSQL. À partir d'un système vide (Debian), doit installer PostgreSQL complétement, sans interaction et affiche la version de psql à la fin du script.

## 2 - Créer l'utilisateur admin

Faire un script `create_admin_user`, qui se lance avec l'utilisateur postgres (sudo -u postgres psql), qui créé un utilisateur "admin" avec le mot de passe "admin42", qui est super admin.

Créer une base de donnée "admin", dont il est "owner".

Il faut pouvoir se connecter à psql avec la commande `psql --username=admin --password`.

Le fichier `pg_hba.conf` doit être mis à disposition sur le dossier github.

## 3 - Modifier la configuration de postgresql

Créer un script `set_configuration` qui va mettre à jour la timezone de PostgreSQL avec la timezone française et affiche la bonne heure modifiée. Il utilisera le nouvel utilisateur "admin".
