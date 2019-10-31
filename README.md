# MyGossipProjectV2

THP 31/10/2019

    Installation :

    git clone 
    
    bundle install

    rails db:create

    rails db:migrate

    rails server

Dans le navigateur aller à l'URL suivante :

http://localhost:3000/

Composants utilisés

    FrameWork : Ruby on Rails

    base de donnée : PostGre

    HTML/CSS : Bootstrap

Ce qui fonctionne :

La BDD avec les passwords chiffrés cf
=> #<User id: 1, name: "vero", email: "vero@me.com", password_digest: "$2a$12$lO3790lDJ45Yfke9JPLNSepwNFe5benfNtHP0Rt6XAi...", created_at: "2019-10-31 11:01:01", updated_at: "2019-10-31 11:01:01">

La page d'accueil avec les boutons. En revanche impossible de résoudre les problèmes de routes par la suite et je ne me suis pas attaquée aux commentaires et aux likes.
