Sinatra-Recettes
---------------

Recettes provenant de la communauté et techniques pour [Sinatra Web
Framework][sinatra].

## Pourquoi un nouveau projet de documentation?

Tout simplement parce que le README de Sinatra et le livre sont un peu désuets.

Ce projet est pour extraire la redondance,combiner les deux sources,et créer
une base pour les recettes provenant de la communauté et pour que la documentation prenne forme.

## Comment puis-je aider?

Tu as une recette ou un tutoriel pour [Sinatra][sinatra]? Sensas, ici est l'endroit
principal pour contribuer.

Après avoir [effectué un 'fork'][github-forking],envoie [ un 'pull
request'][github-pull-requests], juste pour être certain de suivre les [règles de
style][style-guidelines]. 

Tu peux aussi nous contacter sur [irc][irc] ou sur la [mailinglist][mailinglist].

T'as pas d'idées? Jette un coup d'oeil à [issue tracker][issues] pour
des recettes qui ont été proposées ou qui sont en cours.

## Voici le topo

Pour commencer, tu dois cloner le dépôt de github:

    git clone git://github.com/sinatra/sinatra-recipes.git

Après avoir `cd` dedans `sinatra-recipes` tu devrais voir plusieurs choses.

Premièrement, tu devrais prendre note des fichiers d'application:

    app.rb # une miniscule application pour afficher les recettes
    config.ru # le fichier rackup pour le déploiement à Heroku
    Gemfile # fichier de dépendances bundler pour démarrer l'application

Deuxièmement,tu as besoin du gem `bundler`.

    gem install bundler
    
Si tu es sur Rubinius assures-toi que tu as la dernière version de bundler
installée. Les versions antérieures à 1.0.10 ne marcheront pas.

    # ensuite installe les dépendances de l'application
    bundle install

Lorsque c'est complété, tu devrais partir `rackup` à la racine de 
l'application et visiter: [localhost:9292](http://localhost:9292)

Vu que l'application ne fait que mapper les fichiers 'flats', tu peux fureter soit à la
source ou avec l'application web pour consulter les recettes.

Si tu regardes à la source,tu vas voir une couple de dossiers.Dans chaque dossier
il y a un `README.md` qui va brièvement t'expliquer le sujet. Ce qui peut aussi
être fait en allant à `/p/:topic` où `topic` est le dossier que tu veux consulter.

Dans chaque dossier, il devrait y avoir un nombre de recettes à propos de chaque sujet.

## À propos des traductions

Présentement, nous n'acceptons pas les traductions dans le dépôt principal.

Cependant, si tu voudrais maintenir un fork pour traduire la documentation, tu es
libre de le faire, et tu peux ensuite ajouter ton fork à la [liste des traductions dans le
wiki][translations].

[sinatra]: http://www.sinatrarb.com/
[sinatra-book]: http://github.com/sinatra/sinatra-book
[issues]: https://github.com/sinatra/sinatra-recipes/issues
[style-guidelines]: http://github.com/sinatra/sinatra-recipes/wiki/Style-Guidelines
[translations]: http://github.com/sinatra/sinatra-recipes/wiki/Translations
[irc]: irc://irc.freenode.net/#sinatra
[mailinglist]: http://groups.google.com/group/sinatrarb
[github-forking]: http://help.github.com/forking/
[github-pull-requests]: http://help.github.com/pull-requests/


