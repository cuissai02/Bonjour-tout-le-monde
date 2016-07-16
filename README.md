# Présentation générale

L'intelligence artificielle au service de la gestion des connaissances.

Volontairement en Français, car nous souhaitons, aggréger des compétences, des opportunités et des affinités Francophones autour de ce projet.

Sinon, nous pouvons exprimer le même algorithme de pseudocode:  
Calcul du PGDC(m,n), par l'algorithme d'Euclide  
Entrée: Deux nombres entiers non négatifs, et non nul m et n  
Sortie: le plus grand commun diviseur de m et n  
> Calcul_du_PGDC(m,n)  
> tant que n $\neq$ 0 faire  
>> r $\leftarrow$ m $mod$ n  
>> m $\leftarrow$ n  
>> n $\leftarrow$ r  
>>> rzsr   

``` python
Calcul_du_PGDC(m,n)  
tant que n $\neq$ 0 faire  
  r $\leftarrow$ m $mod$ n  
  m $\leftarrow$ n  
  n $\leftarrow$ r  
retourner m 
```

> 


# La problématique
## Les hyphothéses de Google  
[Le pagerank et la popularité d'un site web](http://www.pagerank.fr/).  
  - Pourquoi autant de réponses à une recherche, si seule la première page est consultée?
  - Pourquoi la réponse attendue ne serait pas en dernière position?
  - Pourquoi être si redondant (différentes page d'un même site proposés et contenus similaires de différents sites)?
  - Pourquoi créer une bulle web en fonction des recherches et des sites consultés?
  - Pourquoi privilégier la pertinence à la sérenpidité pertinente?  
[Un graphe de connaissance.](https://fr.wikipedia.org/wiki/Knowledge_Graph)  
  - Pourquoi compiler les résultats du moteur de recherche avec des informations sémantiques issues de sources diverses.
  - Pourquoi une information structurée et détaillée centrée sur l'objet de la recherche, et une liste d'hyperliens.
  - Pourquoi résoudre une requête sans avoir besoin de naviguer vers d'autres sites pour accéder aux informations capitales.
  - Pourquoi un réseau sémantique 500 millions d'objets et plus de 18 milliards de faits et de relations entre les objets 
  - Pourquoi le moteur de recherche doit comprendre la signification des mots-clefs, saisis lors de la recherche.
  - Pourquoi résumer le contenu pertinent autour d'un sujet, et les principaux faits dont vous êtes susceptibles d'avoir besoin
  - Pourquoi étudier l'ensemble des recherches sur chaque élément. Savoir ce que Charles Dickens a écrit.
  - Affiche l'information en apprennant intuitivement de la modélisation de votre historique de recherche, et fournir la bonne information exactement quand vous en avez besoin.
  - Pourquoi comprendre les relations entre les objets. Une personne a des enfants, des parents, un conjoint, tous ces éléments sont liés dans un graphe. On obtient un catalogue d'objets, avec des modèles de tous ces interrelations. C'est l'intelligence entre ces différentes entités qui est la clé.
  - Pourquoi faire des découvertes inattendues pour découvrir un fait nouveau ou une nouvelle connexion qui invite une toute nouvelle ligne de recherche.
  - La recherche parfaite devrait comprendre exactement ce que vous voulez dire et vous redonner exactement ce que vous voulez.
  - Et nous pouvons maintenant répondre à la question suivante avant que vous la posiez, parce que les faits que nous montrons sont informés par ce que d' autres personnes ont cherché.
  - La fonctionnalité "Les gens ont également recherché ..." 
  - Un voyage tout au long de la découverte, rendue plus facile, vous pouvez donc passer moins de temps à chercher et plus de temps à faire ce que vous aimez.
  

[Un moteur de réponses](https://fr.wikipedia.org/wiki/Syst%C3%A8mes_de_questions-r%C3%A9ponses)  
  - [WolframAlpha](https://fr.wikipedia.org/wiki/WolframAlpha) contient environ 10 milliards d'informations, plus de 50 000 types d'algorithmes et de modèles, et des capacités linguistiques pour plus de 1 000 domaines.

## Les hypothéses Wikipédia
  Une encyclopédie collective, universelle, multilingue et fonctionnant sur le principe du [wiki](https://fr.wikipedia.org/wiki/Wiki). Un contenu librement réutilisable, objectif et vérifiable, que chacun peut modifier et améliorer.
    - Pourquoi pas de travaux inédits, innovation et champs des possibles réduits.
    - Pourquoi une utilisation arborescente est-elle privilégiée
    
## les hypotheses de type Medium Quora
Quand je commence à écrire sur Quora je prenais pour tout de suite. Il se trouve à répondre aux questions convient à ma personnalité. Chaque question a servi une invite à l'exercice d'écriture parfaite. Notre relation a été naturel et facile.
Medium est plus difficile pour moi de rapporter. Navigation dans le site, trouver des articles à lire - ou plutôt de trouver comment trouver ces articles - et saisir les tenants et les aboutissants de ce qui pourrait intéresser les lecteurs ne vient pas aussi naturellement pour moi. J'ai trouvé Quora instantanément intuitive. Medium et je tentent encore de comprendre.
Je ne veux vraiment pas de comparer ces deux sites. Ils sont très différents, chacun d'eux correspondant à sa manière.
Dans un effort pour mieux se rapporter à moyen je fait quelques recherches et suis tombé sur cet article. Il est réfléchi et bien fait et précise qui à suivre, pourquoi, et des échantillons de bons articles qui se sont avérés populaires: https://medium.com/startup-study-group/top-entrepreneurship-accounts-to-follow-on-medium-1e0a2e83d4f9#.hgf55csj9

Je suivais tout le monde l'auteur (Levent Askan)[https://medium.com/startup-study-group/top-entrepreneurship-accounts-to-follow-on-medium-1e0a2e83d4f9#.hgf55csj9] recommandé et peut confirmer ses choix étaient vraiment utiles. Après une exploration plus poussée je trouve qu'il a affiché le même article sur (Quora)[https://www.quora.com/Who-should-I-follow-on-Medium-1/answers/19813880?srid=70yN&share=ecc48fe3]. 

La réponse de Levent Askan à qui dois-je suivre sur moyen? Si vous jetez un oeil à ce qu'il messages sur Quora, vous apprendrez beaucoup sur Medium et avoir des articles de lecture organisée fun. Une autre personne à suivre sur Quora pour toutes les choses à moyen est (Tiffany Sun)[https://www.quora.com/profile/Tiffany-Sun-8] . Soit dit en passant, je joue avec poster certains de mes propres travaux sur Medium. Mes efforts ont commencé très timidement et il y a un mois ou deux, je décide que je dois prendre plus au sérieux, être plus cohérent. Pourtant, je ne l'ai pas obtenu très loin.

## Nos hyphothéses
Une solution de gestion de la connaissance conçu pour aider les utilisateurs à améliorer, partager et recueillir des informations et des connaissances disponible au sein de leur organisation et à l'extérieur. Les utilisateurs peuvent éviter les erreurs répétées, la duplication du travail et de l'échec d'un projet en améliorant la découverte et l'accès à l'aide de cette solution de gestion des connaissances.

Les mots d'une recherche peuvent avoir un sens beaucoup plus riche que leur définition, selon le contexte dans lequel vous vous trouvez. Un modèle qui comprend les entités du monde réel et leurs relations les uns aux autres: les objets, et non simplement des chaînes de caractéres.

La prochaine génération de recherche, puisera dans l'intelligence collective du Web et comprendra le monde un peu plus comme les humains.
La recherche satisfait la découverte, le besoin humain fondamental d'apprendre et d'élargir son horizon.

Les trois fonctions d'un moteur de recherche   répondre, converser et anticiper


    Social data
    Text mining
    Search marketing
    Risk management
    Survey analysis
    Consumer privacy
    Sales force optimization

  
