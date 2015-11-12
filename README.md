# lets-play-science

Un petit repo pour aggréger les suggestions sur l'épisode 3 de **Lets Play Science** !  
**Problématique** :  **"Comment collaborer à 5000 cerveaux sur la même question ?".**  
Vive l'intelligence collaborative !  

### Pourquoi github?
Au même titre qu'un wiki, cette application permet de faire des **révisions avec validation du propriétaire** d'un document collaboratif, cf le point suivant.  

### Sommaire

1. [Participer](#participer)
2. [Créer/Trouver une plateforme qui permettrait...](#créertrouver-une-plateforme-qui-permettrait)
3. [Candidats possibles](#candidats-possibles)
4. [On est des fous et on code le truc open source!](#on-est-des-fous-et-on-code-le-truc-open-source)

## Participer
**Pour faire une proposition d'édition**, deux options
#### [1] Faire une requête (c'est le mieux)

- [Créez un compte github](https://github.com/join)
- Sélectionnez le fichier [README.md](README.md)
- appuyez sur le symbole en forme de stylo *edit*
- faites vos modifications
- en bas de la page, section **Propose file change** :
  - renseignez une phrase qui décrit la modification
  - appuyez sur **propose file change**

**Si vous ne savez pas écrire en markdown, c'est un language de mise en forme très simple, [on l'apprend en cinq minutes](http://www.remarq.io/articles/five-minutes-to-markdown-mastery/)**  

#### [2] Ouvrir une issue (c'est moins bien)
- [Créez un compte github](https://github.com/join)
- [Ouvrez une issue](https://github.com/sveinburne/lets-play-science/issues)

#### Validation
Je me chargerais de faire la validation des requêtes. Si d'autres veulent me pretter la main pour la modération, [laissez un message ici](https://github.com/sveinburne/lets-play-science/issues/1)!

## Créer/Trouver une plateforme qui permettrait...

**Un nombre très majoritaire de contributeurs s'accordent sur la nécessité de déplacer la discussion sur une plateforme 'augmentée' qui améliorerait de façon drastique la circulation des idées et favoriserait l'évaluation des propositions peu exposées**
#### **1** Différents types de likes
*proposé par  [koukaloukaki](https://www.youtube.com/user/koukaloukaki)*  

L'idée est de faire du filatrage collaboratif en catégorisant subjectivement l'intérêt

- pousse vert ça veut dire "bonne blague"
- pousse bleu ça veut dire "pas con"
- pousse rouge ça veut dire "nul" ou "spam"

... + d'autres catégories éventuellement, cf l'intervention de [Gaspard Garry-Gendre](https://www.youtube.com/channel/UCYEMyvlHvpJcYypXJZzF9zA)
> "troll" "pas con" "petit breton" "brillant" "genie ou stupide ?" "big up" "hater" "critique" "eloge" "random"

Ainsi on peut basculer entre différentes vues suivant notre approche, "érudite" ou "détente" !

#### **2** Une forme de modération
*proposé par une vaste majorité*  

- **a** Gestion du trolling et des contenus sans valeur ajoutée
- **b** Influence sur l'algorithme de tri. Un modérateur peut marquer
  - houleux ( il ne sera plus favorisé dans l'algorithme de tri )
  - exceptionnel ( il sera mit en avant dans l'algorithme de tri )

**Remarque** Certains comme [PhilocrateV](https://www.youtube.com/user/PhilocrateV) émettent des réserves à la **2.b**, qui favorisait un "système de castes". Je trouve au contraire que le droit de modérer est acquis par mérite, par les contributeurs qui s'investissent le plus.

#### **3** Association sémantique des posts
*proposé de nombreuses fois*
- **a** Par des #hashtags : Permet de filtrer rapidement le contenu, et d'avoir un accès facile aux posts relatifs

*[proposé par Fjellfrass ](https://www.youtube.com/user/Fjellfrass), [ Sebastien Huet](https://www.youtube.com/user/huetse), [heyhoo yoo](https://www.youtube.com/channel/UCfKFZIdjzeti_fbmDH4uIvg)*
- **b** Par une analyse syntaxique des posts (computationnellement très couteux !)

#### **4** Possibilité de marquer un post comme "évalué"
Extension de la proposition **3** :
Si on a ni liké, ni jugé le contenu extraordinaire, ni merdique, on peut le marquer comme "lu", cf la proposition **5**

#### **5** Une interface qui favorise l'évaluation entre pairs
*Inspiré de la proposition de [koukaloukaki](https://www.youtube.com/user/koukaloukaki)*  
- **a** Proposer à l'utilisateur un mode "évalutation" ou son travail est d'évaluer des posts qu'il n'a pas encore évalué. Grosso modo, ça lui permet de s'y retrouver facilement !  
Dans ce mode, **seuls les contenus non marqué (comme "vu", "pas con", "spam" ou "drôle") seront visibles**.  

*Proposé par [Yrtiop](https://www.youtube.com/user/Yrtiop)*
- **b** Provoquer la sérendipité et limiter le copinage en obligeant les gens à commenter (évaluer) des solutions tirées au hasard

*Proposé par [Takator LK](https://www.youtube.com/channel/UCKFNN9-FFfaN53BQc_ZF5Mw)*
- **c** Obliger l'évaluation d'autres propositions avant de publier la sienne. Bien évidemment, cette obligation ne s'applique pas aux premiers posts.

*Insipiré de la proposition de [Takator LK](https://www.youtube.com/channel/UCKFNN9-FFfaN53BQc_ZF5Mw)*
- **d** En accord avec **a**, **b** et **c**, créer des "clusters" d'évaluateurs :
  - Dans chaque cluster, une équipe réduite prémache le tri
  - Les contributions les plus pertinentes deviennent visibles en dehors du cluster
  - Celà présuppose un processus itératif et séquentiel de l'évaluation :
    - pendant un 'run' d'une semaine, les clusters sont isolés les uns des autres, mais les posts sémantiquement proches (cf **3**) sont visibles entre clusters.
    - dans un deuxième run, les clusters 'publient' les propositions les plus pertientes


*Proposé par [Jean Baptiste Dallara](https://www.youtube.com/user/a46production)*
- **e** Un peu à la facemash, proposer des paires de propositions et demander à l'évaluateur celle qu'il trouve la plus pertinente.  

#### **6** S'inspirer de republique-numerique.fr
*[proposé par hackedbrain17](https://www.youtube.com/user/hackedbrain17)*  
Avec notamment :
- **a** La proposition **1**
- **b** La possibiliter d'éditer collectivement les propositions (soumettre une édition à l'auteur du post, comme sur github^^)

**6.b** aussi proposé par [luffyetgaara](https://www.youtube.com/user/luffyetgaara)


## Candidats possibles
#### [Discourse](https://www.discourse.org/)
*proposé par [kokodroid](https://www.youtube.com/user/kokodroid)*  
**Pros**
- Open source
- Moderne

**Cons**
- Ne supporte pas la personnalisation des likes à ma connaissance

#### [Stack Exchange](http://stackexchange.com/)

*suggéré par [Josselin Massot](https://www.youtube.com/user/Dlul)*
(à développer)

> Une autre idée est celle proposée par des outils comme **StackOverFlow** (et toutes les versions propres à un domaine particulier qui en sont dérivés) qui consiste à poser une question (généralement l'exposition d'un problème informatique), un certain nombre de personnes répondent et on peut facilement aimer ou déprécier la réponse. En tout cas ce système de notation est beaucoup plus mis en avant et incité que sur Youtube. Donc le problème est peut-être la philosophie des communautés Youtube qui favorise les réponses courtes aux réponses longues (souvent plus complètes et constructives).

## On est des fous et on code le truc open source!
Des développeur qui ont signalé leur souhait de s'investir (merci de vous rajouter à la main avec votre lien github)

- [Jules Randolph](https://github.com/sveinburne/)
