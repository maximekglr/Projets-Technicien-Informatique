# Recherche et sélection d'un PC portable professionnel

## Introduction

A l'heure où je rédige ce document, il s'agit de mon premier "projet" informatique s'inscrivant dans la démarche de devenir **Technicien Informatique**. Comme indiqué par mon usage des guillemets, je considère ce premier travail comme une ébauche, de par sa nature peu technique (pas de montage du PC par moi-même) et mes tâtonnements quant à la découverte des règles et fonctionnements de Git & Git Hub. 

C'est donc selon moi seulement la première étape d'une démarche de travail plus fournie que je saurai à même de retranscrire pleinement au cours de mes prochains projets.

## Besoins spécifiques

### Usages prévus

L'achat de ce nouveau PC portable était dans le but de remplacer l'ancien, un ASUS de 2018 équipée d'un processeur Intel i5 et d'un GPU NVIDIA GTX 1050. Bien qu'encore parfaitement utilisable, ce dernier, suite à une panne que j'ai su réparer, m'a fait prendre conscience que mes besoins en puissance de calcul et en stockage allait être potentiellement plus important dans mes postes futurs, toujours en tant que Technicien Informatique bien sûr mais aussi, dans un avenir plus lointain, en tant qu'Administrateur Systèmes et Réseaux, Cloud DevOps ou encore Cloud Architect. Ces rôles doivent pouvoir être tenus en présentiel comme en distanciel.

Les usages principaux de ce futur ordinateur correspondent donc aux missions attribuées à ces postes en général :
- Lancement de machines virtuelles via des hyperviseurs de type 1 (OracleVM, Hyper-V)et 2 (VirtualBox,VMware).
- Lignes de commandes via le terminal Linux.
- Développement de scripts Powershell et Bash.
- Utilisation d'outils d'analyse de réseaux comme WireWhark, Packet Tracer ou GNS3.
- Déploiement d'environnements de test via Docker, Ansible ou Terraform.
- Navigation fluide entre différents VM, terminaux, fenêtres et onglets.
- Lecture de documentation.
- Utilisation d'outils de ticketing type Jira ou de helpdesk comme Zendesk et GLPI.
- Utilisation d'outils d'éditeur de texte (Vim, Xed, Nano ou VS Code).

### Spécifications recherchées

Afin de pouvoir correspondre à mes besoins et assurer pleinement les missions cités ci-dessus, j'ai donc pu listé les critères spécifiques auquel ma future machine se devait de répondre : 
- **Être un PC portable**, utilisable au bureau comme sur site ou depuis chez moi.
- **Processeur performant**, à l'aise avec le multitâche et la gestion de multiples VM, onglets ou fenêtres.
- **16go de RAM minimum**, lesquels seront extensibles lorsque le besoin s'en fera sentir.
- **SSD rapide à haute capacité** (NVMe, plusieurs emplacements si besoin de plusieurs disques, 512go au minimum).
- Un GPU suffisamment puissant pour faire tourner des VMs avec interface graphique de façon fluide et pour mon évolution future sur des tâches liées au Cloud, DevOps ou à l'IA.'
- Autonomie correcte
- Connectiques modernes et attendues pour un usage d'administration réseaux (RJ45, USB-C, USB 3.2)
- Châssis robuste (pour le transporter sans risquer d'abîmer les composants).
- **Rester dans un budget très correcte** (600-700 euros)
- Poids correct

## Recherche de modèles

### Marques considérées

J'ai eu de bonnes expériences avec Acer et Asus, et partait donc avec un biais positif en faveur de ces marques. Cependant, je me suis toujours appuyé sur des retours directs des personnes ayant déjà acheté les PC mentionnés plus bas, soit via leurs commentaires sur les sites d'achat, soit via les performances relayées sur les sites de benchmark.

### Veille comparative

Sur la base de ces critères, j'ai pu effectué une veille comparative sur différents sites :
- [Cdiscount](https://www.cdiscount.com/)
- [LDLC](https://www.ldlc.com/)
- [Amazon](https://www.amazon.fr/)
- [Reddit](https://www.reddit.com/)
- [Matériel.net](https://www.materiel.net/)
- [LesNumériques](https://www.lesnumeriques.com/)

C'est sur **CDiscount** que j'ai pu trouver les ordinateurs portable au meilleur prix, à la fois dans ma gamme de prix et les performances que je recherchais.

Sur ce site, 4 modèles se sont démarquées (que j’appellerai par la suite par le nom de leur constructeur dans un souci de commodité à la lecture) :

1. [PC Portable Gamer ACER Nitro V 15 ANV15-41-R85W](https://www.cdiscount.com/informatique/ordinateurs-pc-portables/pc-portable-gamer-acer-nitro-v-15-anv15-41-r85w/f-1070992-nhqsgef002.html#mpos=0|cd) à **649€**.

Possédant un Ryzen 5 7535HS et étant peu cher, ce PC était un bon prétendant. Néanmoins, un Ryzen 7 l'aurait rendu bien plus intéressant selon moi.

2. [PC Portable LENOOVO IdeaPad Slim 3 15IRH10](https://www.cdiscount.com/informatique/ordinateurs-pc-portables/pc-portable-lenovo-ideapad-slim-3-15irh10-sans-w/f-1070992-83k100fsfr.html#mpos=0|cd) à **600€**.

Bien que possédant un processeur Intel Core i7-13620H et un SSD de 1 To, ce dernier n'avait pas de GPU indépendant et avait une barrette de 8go de RAM soudée directement à l'ordinateur portable, limitant ainsi mon évolution matérielle.

3. [PC Portable Gamer ERAZER - DEPUTY P60i](https://www.cdiscount.com/informatique/ordinateurs-pc-portables/pc-portable-gamer-erazer-deputy-p60i-livre-sans/f-1070992-30038061.html#mpos=0|cd) à **700€**.

Bien qu'intéressant de par sa RTX 4060, la présence d'un i5-12450H et non d'un i7 me semblait dommageable pour mes activités. De plus, ce modèle était à la limite de mon budget tout en étant un produit d'un constructeur moins reconnu, et donc potentiellement moins fiable quant à l'assemblage et à la qualité du boîtier.

4. [PC Portable ASUS TUF Gaming A15] (https://www.cdiscount.com/informatique/ordinateurs-pc-portables/pc-portable-gamer-asus-tuf-gaming-a15-sans-windo/f-1070992-tuf506ncrhn006.html) **600€**.

Disposant d'un Ryzen 7 7435HS et d'une RTX 3050, ce PC semblait être un très bon compromis. Cependant son absence d'iGPU laissait penser à un manque d'autonomie.



### Comparaison technique

| Modèle                   | CPU                      | GPU                   | RAM                   | SSD                   | Prix                  |
|--------------------------|--------------------------|-----------------------|-----------------------|-----------------------|-----------------------|
|Acer Nitro                |Ryzen 5 7535HS (6 coeurs) |RTX 4050               |16Go                   |512Go PCIe NVMe        |699€
|--------------------------|--------------------------|-----------------------|-----------------------|-----------------------|-----------------------|
|Lenovo IdeaPad            |Intel Core i5-13420H      |Pas de carte graphique |16Go                   |512Go NVMe             |649€
|--------------------------|--------------------------|-----------------------|-----------------------|-----------------------|-----------------------|
|Erazer DEPUTY             |Intel Core i5-12450H      |RTX 4060               |16Go                   |512Go                  |799€
|--------------------------|--------------------------|-----------------------|-----------------------|-----------------------|-----------------------|
|Asus TUF Gaming A15       |Ryzen 7 7435HS            |RTX 3050 4Go           |16Go                   |512Go NVMe + 2eme slot |600€
|--------------------------|--------------------------|-----------------------|-----------------------|-----------------------|-----------------------|


Nous retouvons ici un tableau comparatif des principales caractéristiques des PCs mentionnés plus haut. Comme on peut le constater les critères fondamentaux sur lesquelles s'est basé mon choix sont le CPU et le GPU, puisque la RAM, le stockage et le prix sont sensiblement les mêmes exceptés pour le Erazer Deputy. D'ailleurs, ce prix significativement plus haut est dans ma recherche un frein important dans le choix de ce PC car s'éloignant de mon budget initial de 600-700€.



## Benchmarks

Nous allons donc axer notre comparaison autour des CPU & GPU de chaque ordinateur. Je rappelle que l'objectif dans l'acquisition de cet ordinateur est de pouvoir assumer les missions d'un Technicien Informatique et d'un futur Administrateur Systèmes et Réseaux, Cloud DevOps ou encore Cloud Architect.

Pour effectuer cette comparaison je me suis basé sur deux sites de benchmark gratuits et reconnus : [User Benchmark](https://www.userbenchmark.com/Software) et [PassMark](https://www.cpubenchmark.net/).


### CPU

UserBenchmark recoupe 3 contextes d'utilisation d'une machine et donc d'un CPU sous forme de pourcentage d'efficacité : Gaming, Desktop et Workstation. 
Ici c'est la partie Workstation qui nous intéresse, car elle représente une machine effectuant du multitâche complexe centré autour du CPU.

**Première comparaison : Ryzen 5 7535HS vs. Intel Core i5-13420H**

L'aperçu global donne le Intel Core i5-13420H comme meilleur, avec une Effective speed 14% plus importante que notre autre CPU, et un pourcentage d'efficacité en Workstation de 89% contre 76%.

Pour ce qui est des performances moyennes en single-core comme en multi-core, le constat est le même : le Intel Core i5-13420H est 21 à 31% plus rapide que le Ryzen 5 7535HS.

Sur PassMark, idem : on retrouve le Intel Core i5-13420H avec un meilleur score au global, au single thread rating (soit la réactivité du CPU sur des tâches simples fréquentes) et sur le nombre de coeurs (soit la capacité à faire du multi-tâche).

L'avantage va donc au Intel Core i5-13420H qui bat à plate couture son adversaire.

**Deuxième comparaison : Intel Core i5-12450H vs. Ryzen 7 7435HS**

Pour cette comparaison, on constate tout de suite que le match est bien plus équilibré, autant sur UserBenchmark que sur PassMark : le i5 Core-12450H est plus efficace de 13% en moyenne sur les tâches à 1, 2 et 4 coeurs, donc pour des tâches simples ou des scripts, là où le Ryzen 7 montre une avance similaire en pourcentage sur les plans des tâches utilisant 8 coeurs (multitâche important, VMs actives) et une latence au global moindre (9% plus rapide).

Néanmoins, et c'est là où le Ryzen 7 brille, c'est quand, accumulé à ces meilleures performances en multitâche, on ajoute la présence de 8 coeurs physiques (contre 4 physiques et 4 virtuelles pour le i5) signe d'une meilleure stabilité dans des scénarios techniques et d'une meilleure consommation : 35W pour 45W (le Ryzen 7 chauffera moins donc et aura une meilleure durée de vie potentielle).

Au final, dans le cadre d'une future utilisation de ce processeur dans du mutltitâche potentiellement lourd (Machines virtuelles, Environnements de test couplés à des tâches plus simples en parallèle), une meilleure vitesse en 8 coeurs et une plus faible latence semblent être les critères à favoriser.

Mon choix se porte donc vers le Ryzen 7 7435HS, qui a l'avantage d'offir un profil beaucoup plus polyvalent que son adversaire, avec une latence moindre et une fluidité globale plus haute..

Le choix du i5 Core-12450H m'aurait semblé plus pertinent pour effectuer des tâches simples seulement, et si ma priorité absolue avait été la réactivité.


**Troisème comparaison : Intel Core i5-13420H vs. Ryzen 7 7435HS**

Pour notre dernière comparaison, une dynamique similaire à notre précédent affrontement persiste : le i5-13420H est plus rapide en single core, ici de +20%, mais un moins bon cache mémoire (12Mb) et une moins bonne utilisation de ces 8 coeurs, des coeurs qui justement, contrairement au Ryzen 7 7435HS, ne sont que partiellement physiques (4 contre 8, un coeur physique étant plus stable lors d'opérations lourdes).

Ma conclusion reste donc la même que pour le précédent combat : le Ryzen 7 7435HS se destine plus à un profil de technicien informatique comme le mien. Il remporte donc le tournoi opposant ces différents CPUs.


###GPU
 
Ici le procédé sera le même que pour les processeurs, cette fois appliquées aux cartes graphiques. Je rappelle ici que mon usage de cette ordinateur portable sera en très grande partie, si ce n'est exclusivement, professionnelle. Mon but n'est donc pas ici d'obtenir un ordinateur me permettant de faire tourner n'importe quels jeux modernes dans la meilleure résolution, mais plutôt si l'occasion se présente de pouvoir profiter d'un instant de repos pour profiter de jeux plus ou moins récents dans de bonnes conditions. Le choix du GPU est donc secondaire au choix du CPU.

Ici départager les ordinateurs entre eux sera encore plus simple que pour le round précédent, Lenovo IdeaPad ne s'emcombrant pas d'emporter une carte graphique avec lui. Il est donc d'office écarté.

Idem pour le Acer Nitro et le Asus TUF gaming proposant respectivement une RTX 4050 et 3050, qui sont donc bien moins efficaces que la RTX 4060 du Erazer DEPUTY. La manche revient donc à ce dernier.



## 4. Analyse et justification

Après mûres réflexions et analyse des CPUs et GPUs de ces quatres appareils, mon choix quant à l'achat de mon nouvel ordinateur portable semble se porter sur le Asus TUF Gaming A15.


###Pourquoi ce modèle plutôt qu’un autre

Comme on l'a vue plus tôt, la carte graphique la plus performante était la RTX 4060 du Erazer DEPUTY. Cependant, et malgré le fait que la RTX 3050 arrive en troisième position des cartes graphiques sélectionnées, mon choix s'est porté sur l'ordinateur Asus TUF Gaming. En effet, au delà de sa carte graphique aux performances plus que raisonnables (ce qui est en adéquation avec ma mention plus haut de mon utilisation de cet ordinateur), il a le processeur le plus adapté à mes futures tâches de technicien informatique, l'avantage d'avoir un second slot pour un SSD supplémentaire, gage de flexibilité et de praticité dans le stockage de fichiers lourds et lorsque viendra le temps d'accroître cet espace de stockage, et enfin à un prix plus que raisonnable comparativement aux autres.

###Rapport performance/prix

En effet, en comparant seulement cet ordinateur portable avec ces 3 autres concurents, on se rend rapidement du caractère avantageux de ce choix quand au rapport performance/prix proposé par ce PC. Seulement proposé à 600€ à l'heure où j'écris ces lignes, il est 50, 100 et même jusqu'à 200€ moins cher que les 3 autres PC que nous avons pu voir. Le budget restreint faisant partie des critères de sélection, un PC proposant de telles performances à ce prix est plus que bienvenue.

###Fiabilité de la marque

La cerise sur le gâteau si j'ose dire, c'est que ce PC est proposé par la marque ASUS, assembleur et fabricant dont j'ai toujours eu de très bons retours ainsi qu'une expérience personnelle très positive quand à leur rapport qualité/prix, leur larges choix de PC dans leurs différentes gammes et, ce qui nous intéresse d'autant plus ici, dans la solidité de leurs PC portables. En effet les composants du Asus TUF Gaming A15 sont intégrés au sein d'une coque rigide et solide "de qualité militaire" selon le constructeur. Cette solidité apparente, ajouté à la bonne réputation d'Asus finit de me rassurer et m'assure d'effectuer, plus qu'un compromis, le choix idéal au vu de mes critères particuliers.


A l'opposé et pour ce qui est d'Acer, la marque semble avoir des retours inégaux selon des particuliers sur Reddit, et même des modèles récents ont eu, comme le Predator Helios 16S AI testé par Wired en août 2025, des graves soucis de plantage. Cela n'aurait pas été garantie d'arriver sur le Nitro évoqué plus haut, mais ce n'est jamais rassurant lors du choix d'un ordinateur.

Pour ce qui est de Lenovo, leur marque jouit d'une très bonne réputation en terme de solidité, de fiabilité et d'autonomie, ce qui est admirable. Si j'avais trouvé un modèle Lenovo répondant à mes critères, cela aurait été avec joie que je me serai dirigé vers un modèle du constructeur hongkongais.

Lenovo est aussi le propriétaire majoritaire de l'assembleur allemand Medion, à l'origine justement du Erazer Deputy mentionné dans ce document. Bien que compétitif sur les prix, le caractère économique des PCs de la marque se retrouve également, selon des retours TrustPilot, sur la qualité de fabrication et la durée de vie des composants qui a tendance à rapidement décliner. Ajoutant à cela une difficulté parfois pour trouver des pièces pour faire réparer son ordinateur quelques années après l'avoir acheté, je pense qu'il est nécessaire de faire bien attention avant de sélectionner un ordinateur de cette marque, d'étudier attentivement chaque composant et d'attendre un nombre suffisant de retours utilisateurs avatn de se lancer. A réserver peut-être pour des utilisateurs ne souhaitant pas effectuer des tâches lourdes dans leur travail ou bien bien pour des personnes ayant un budget plus important.

## 5. Choix final

###Modèle retenu

Suite à l'approfondissement de l'analyse quand au rapport performance/prix et à la fiabilité de la marque, je réitère mon choix et m'arrête sur le Asus TUF Gaming A15 comme nouvel ordinateur.

###Référence technique complète

Vous trouverez ici le lien vers la fiche technique complet de ce PC : [le lien](https://www.cdiscount.com/informatique/ordinateurs-pc-portables/pc-portable-gamer-asus-tuf-gaming-a15-sans-windo/f-1070992-tuf506ncrhn006.html?idOffre=3952721741#mpos=0|cd&sw=f3ba2ff83351a8faf74ee1690a3a02f5b2196d90543f9151782079183517775a6f243f256d0726564bb6321bdd3b8c326fff8ae0d036e0b8ab5942074b107184a4a7f413541642d0e2653fc9c977dbc4c914a527678140c39bebd867a879ca359c4a7c88a72c2a4235c2eeb16451ecc82338afa6f2608480eda2e78a52de4f94).

## 6. Retour d’expérience (facultatif)

###Premières impressions

A la réception j'ai pu constater avec plaisir la solidité de l'ordinateur, j'ai installé sans problème un OS Linux Mint sans difficulté (processus dont j'aurai sans doute l'occasion de reparler au cours d'un futur projet), un OS léger n'étant pas trop gourmand en ressources.

###Performances constatées

L'ordinateur s'allume rapidement (12 secondes), en bureautique le processeur utilise 15% de ses capacités et la RAM en moyenne 5 à 6Go sur les 16Go. Les vitesses d'écritures sont bonnes, la taille du SSD devra cependant être a minoma doublé par k'ajout d'un second disque. Idem pour la mémoire, en prévision d'utilisation d'hyperviseurs.

Je n'ai pas enccore eu l'occasion de tester de faire fonctionner en simultané plusieurs machines virtuelles, je mettrai à jour ce document dès que j'aurai pu expérimenter un peu plus.

##Conclusion

Je vous remercie d'avoir pris le temps de lire ce document, dont j'espère la structure et l'agencement des idées sont suffisament clairs afin de permettre une lecture agréable. Je compte me perfectionner dans tous les cas à cet exercice et contiinuer de documenter mes futurs projets dans le cadre de mon évolution professionnel dans le monde des systèmes d'informations.

