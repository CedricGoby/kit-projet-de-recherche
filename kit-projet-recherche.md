# Kit Projet de Recherche
Cette page propose des méthodes simples, des outils informatiques et des ressources pour mener à bien un projet de recherche et produire des données FAIR <sup id="a1">[1](#f1)</sup>.

La quasi-totalité des outils proposés sont open source et permettent d'avoir un contrôle total sur vos données.

Ce document s'adresse en priorité aux informaticiens en charge d'équipes de recherche publique, mais la plupart de ces outils répondent également aux besoins d'associations ou d'entreprises.

## Méthodologie
Pour permettre l'adoption d'outils par des équipes de recherche il est préférable de montrer du concret. 

En effet, le risque de décrire un outil et son usage avant de pouvoir le montrer est que si votre interlocuteur ne saisit pas clairement votre pensée (ce qui est plus que probable quand on aborde des questions techniques en informatique), l'a-priori sera négatif et c'est un mauvais départ, voire pas de départ du tout.

L'idée est donc de commencer par déployer un outil dans votre coin afin de faire une démo convaincante.

Profitez-en pour documenter les étapes techniques d'installation de  l'outil, tester ses fonctionnalités, estimer ses qualités, ses défauts, ses limites... Vous pourrez déterminer alors si il répond bien à une ou plusieurs problématiques des équipes.

Vous pourrez alors le présenter tout en expliquant ce qu'il peut apporter concrètement.  
La démo permet aux utilisateurs de visualiser l'interface tout en découvrant comment les fonctionnalités présentées peuvent répondre à certaines problématiques.

Cette méthode vous évitera d'interminables réunions pour demander l'avis des utilisateurs sur des sujets qu'ils ne maîtrisent pas, la production de diaporamas remplis de schénas et de termes à la mode,  ainsi que la rédaction fastidieuse d'un cahier des charges qui ne sera de toute façon pas respecté.

## Critères de choix des outils

  * Open source
      Les outils open source sont interopérables, reposent sur des standards et des formats ouverts. Ils répondent aux éxigences de confidentialité. Ils ne nécessitent pas de frais de licence.

  * Forte communauté d'utilisateurs et de développeurs
      Même de qualité, un outil trop confidentiel ou "fait maison" risque de ne pas être maintenu sur le moyen ou le long terme, devenir obsolète ou poser des problèmes de sécurité. De plus le support à l'installation ou à l'utilisation peut s'avérer insuffisant.
 
  * Pas de développement spécifiques
      Les outils doivent pouvoir être mis en oeuvre sans l'intervention de développeurs. Les équipes ont rarement ces ressources en interne et au gré des mouvement de personnel le risque est grand de perdre la mémoire de ces développements spécifiques.

## Stratégie pour le travail collaboratif
La réussite d'un projet de travail collaboratif ne dépend pas des outils mais de la manière dont ils sont employés en fonction de l'organisation des équipes et des projets.

Si les utilisateurs se perdent dans les dossiers partagés, les chats, les listes de diffusions, les forums et autres agendas, ces fabuleux outils ne sont d'aucune utilité et votre projet et voué à l'échec car au lieu de leur simplifier la vie, vous allez la compliquer.

Pour définir une organisation permettant d'utiliser efficacement les outils de travail collaboratif il suffit la plupart du temps de déterminer :

  * Des niveaux d'organisation :
    * Équipe
    * Projet
    * Thématique

Ces niveaux d'organisation permettent de déterminer :

  * Les utilisateurs et les groupes d'utilisateurs
 
 ainsi que les droits d'accès des utilisateurs et des groupes sur :
 
  * Les dossiers partagés
  * Les agendas partagés
  * Les listes de diffusion

Ce travail assez simple permet d'organiser l'utilisation de n'importe quel outil collaboratif et de faire face sans problème à l'arrivée de nouveaux utilisateurs ou de nouveaux projets.

Il convient également de définir des règles de nommage simples pour les dossiers et agendas partagés, les groupes d'utilisateurs ainsi que pour les listes de diffusion.

Quelques exemples ci-dessous :

L'équipe "tofu" compte 50 membres. On crée un groupe "tofu" incluant tous les membres de l'équipe.  
On peut alors créer une liste de diffusion générale tofu@groupes.renater.fr qui inclut le groupe "tofu" (tous les membres de l'équipe).  
La règle de nommage est ici "équipe@groupes.renater.fr"

Une dizaine de membres de l'équipe "tofu" travaille sur le projet "greenwashing". On crée alors un groupe d'utilisateurs "greenwashing".
On peut ensuite par exemple créer le dossier partagé "tofu-greenwashing" qui inclut les membres du projet "GreenWashing"  
La règle de nommage du dossier partagé est ici "équipe-projet".  
On peut également reprendre cette régle de nommage pour une liste de diffusion pour ce projet : tofu-greenwashing@groupes.renater.fr

D'autres membres de l'équipe sont chargés de l'accueil des nouveaux arrivants. On crée alors un groupe d'utilisateurs "accueil"
On peut alors par exemple créer le dossier partagé et l'agenda partagé "tofu-accueil" qui inclut les membres de la thématique "accueil"
La règle de nommage du dossier partagé et de l'agenda est ici "équipe-thématique".

L'idée n'est pas régler d'avance tous les cas de figure mais de partir sur de bonnes bases tout en gardant de la souplesse pour adapter l'utilisation de l'outil aux besoins des utilisateurs.

un projet réussi implique des utilisateurs satisfaits qui adoptent l'outil ! On doit donc aussi en amont se poser ces questions :

  * Que va leur apporter l'outil par rapport à l'existant ?
  * Recevront-ils la formation adequate (même si elle est très courte) ?
  * Quel sera le niveau de support utilisateur une fois l'outils déployé ?

## Droit à l'erreur

Il est impossible d'envisager ou de tester tous les cas de figure avant de déployer un outil. Des problèmes techniques ou d'usage peuvent survenir.

Il s'agit de ne pas s'enfermer dans un mauvais choix, de reconnaître ses erreurs et de s'orienter vers de nouvelles solutions.

## Les outils

### Gestion et partage de documents
#### Netxcloud
https://nextcloud.com/fr_FR/  
Nextcloud est une suite open source de travail collaboratif : partage de documents, agendas partagés, notes, gestion des groupes de travail, synchronisation avec des ordinateurs, tablettes, smartphones...

### Agenda partagé
#### Calendar
https://apps.nextcloud.com/apps/calendar  
Calendar est l'application d'agenda intégrée à Nextcloud.

### Édition collaborative
#### OnlyOffice
https://www.onlyoffice.com/fr/  
OnlyOffice s'intègre à Nextcloud et comprend une suite d'applications bureautiques en ligne pour travailler depuis un navigateur sur des fichiers Microsoft Office ou Open Document.

### Gestion et partage de documentation
#### DokuWiki
https://www.dokuwiki.org/dokuwiki  
DokuWiki est un moteur de wiki libre sous licence GNU GPL conforme aux standards, simple à utiliser, dont le but principal est de créer des documentations de toute sorte.
Il est destiné aux équipes de développement, aux travaux de groupe et aux petites entreprises. Il a une syntaxe simple qui assure la lisibilité des fichiers de données en dehors du Wiki, et facilite la création de textes structurés. Toutes les données sont stockées dans des fichiers texte, et donc aucune base de données n’est nécessaire.
#### BookStack
https://www.bookstackapp.com/  
BookStack est un outil open source qui permet d’organiser des notes, des informations, des astuces, de la documentation.
#### Pandoc
https://pandoc.org  
Pandoc est un puissant logiciel de conversion de documents en ligne de commande. Il converti vers et depuis de multiples formats. Mais son intérêt réside surtout dans l'automatisation de tâches et la possibilité d'utiliser des modèles (templates) pour obtenir des produits de conversion.

### Gestion des tâches
#### Wekan
https://wekan.github.io/  
Wekan est un outil collaboratif de gestion de tâches, gratuit et open source.  
Reprenant le principe du kanban Wekan propose d’organiser votre « workflow » via le système désormais bien connu des petites fiches (« cards ») à déplacer sur des tableaux (« boards »), pour signifier la progression des différentes tâches en cours dans un projet.

#### Joplin
https://joplinapp.org/  
Joplin is a free, open source note taking and to-do application, which can handle a large number of notes organised into notebooks. The notes are searchable, can be copied, tagged and modified either from the applications directly or from your own text editor. The notes are in Markdown format.

### Communication interne
#### Listes de diffusion Renater
https://groupes.renater.fr/sympa  
Le service RENATER pour héberger les listes de diffusion inter-établissements.

##### Usage
>Au minimum il faut créer une liste généraliste pour le projet ou l'équipe : c'est le canal de communication officiel du projet ou de l'équipe. La liste des abonnés est fixée par le responsable de l'équipe et du projet. Elle regroupe généralement tous les membres d'une équipe ou d'un projet. 
>
>Sans multiplier les listes il peut-être utile de communiquer sur des thèmes plus spécifiques au sein d'un projet ou d'une équipe. Par exemple : L'accueil des nouveaux arrivants, le budget, une thématique scientifique...
>
>Le responsable de la liste envoie un premier mail aux abonnés pour expliquer l'objet et le fonctionnement de la liste. Il peut être utile de préciser dans ce premier envoi qui est abonné à la liste. Ainsi les uns et les autres savent qui les lira lorsqu'ils enverront un mail à la liste.
>
>Il est possible de rendre la liste des abonnés accessible aux seuls autres abonnés. Chacun sait alors qui reçoit les messages.

#### Sympa
https://www.sympa.org  
Les service de liste de Renater utilise ce logiciel open-source et présente donc les mêmes caractéristiques. Vous pouvez l'héberger vous-même si vous disposez de l'infrastructure informatique adequate.
#### Tchap
https://www.tchap.gouv.fr  
Tchap est une solution de messagerie instantanée et sécurisée dédiée aux agents de l’Etat souhaitant communiquer entre eux et échanger des informations sensibles depuis leur ordinateur.
#### Discourse
https://www.discourse.org/  
Discourse est un logiciel libre pour forum de discussions.

### Visioconférence
#### Rendez-vous
https://rendez-vous.renater.fr/home/  
Le service RENATER pour participer à vos réunions en webconférence.
Accessible directement sur les postes de travail et aussi sur tablettes ou smartphones.

## Communication / Évènements

### Communication externe
#### Wordpress
https://fr.wordpress.org/  
Site Internet pour communiquer auprès du grand public et des partenaires.
#### Flux RSS
https://fr.wikipedia.org/wiki/RSS  
Un flux RSS est une ressource Web dont le contenu est généralement produit automatiquement, en fonction des mises à jour d’un site Web.

### Organisation d’événements, réunions
#### ScienceConf
https://www.sciencesconf.org/  
Sciencesconf est une plateforme Web s'adressant aux organisateurs de colloques, workshops ou réunions scientifiques. Cette application est réservée aux établissements de l'enseignement et de la recherche.  
Cette plateforme multi-langues et configurable facilite les différentes étapes de déroulement d'une conférence depuis la réception des communications jusqu'à l'édition automatique des actes en passant par la relecture et la programmation des thématiques.
#### Indico
https://getindico.io  
Le logiciel Indico permet de gérer des conférences complexes, des ateliers ou de simples réunions.
#### Evento
https://evento.renater.fr/  
Le service RENATER pour planifier vos événements en quelques clics !
#### Xibo
https://xibo.org.uk  
Diffusion de contenu mutimédia sur écrans numériques.

### Veille informationnelle
#### Tiny Tiny RSS
https://tt-rss.org/  
Tiny Tiny RSS (ttrss) est un agrégateur de flux RSS et Atom libre sous licence libre GNU GPL v3.

### Plan de gestion des données
#### DMP Opidor
https://dmp.opidor.fr/  
DMP OPIDoR vous accompagne à travers l’élaboration et la mise en pratique de plans de gestion de données et de logiciels.
Accessible à la communauté scientifique de l’ESR et à ses partenaires français ou étrangers.
Personnalisable par tout organisme de recherche pour la mise en place de sa politique de données.
Enrichi par des exemples et des recommandations adaptés à l’environnement de recherche.
Collaboratif : il facilite les échanges entre les partenaires d’un même projet et les services d’accompagnement.

### Cahier de labo
#### eLabFTW
https://www.elabftw.net  
eLabFTW est un système sécurisé pour suivre vos expérimentations mais également gérer votre labo.


### Gestion des données
#### iRODS
https://irods.org/  
Logiciel de gestion de données open source.

### Bases de données
#### Mariadb
https://mariadb.org/  
MariaDB est un système de gestion de base de données édité sous licence GPL.
#### Influxdb
https://www.influxdata.com/products/influxdb-overview/
InfluxDB est un système de gestion de base de données orientée séries chronologiques hautes performances, écrit avec le langage de programmation Go et distribué sous licence MIT.

### Visualisation de données
#### Shiny server
https://github.com/rstudio/shiny-server  
Shiny Server is a server program that makes Shiny applications available over the web.  
Shiny Server is the simplest way for data scientists and R users to share their work with colleagues in a controlled environment.
#### Grafana
https://grafana.com/  
Grafana est un logiciel libre sous licence Apache 2.0 qui permet la visualisation et la mise en forme de données métriques. Il permet de réaliser des tableaux de bord et des graphiques depuis plusieurs sources dont des bases de données de série temporelle (Time Series Database) comme Graphite, InfluxDB MariaDB et OpenTSDB3.

### Gestion et partage de code
#### Git
https://git-scm.com  
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

#### Jupyter
https://jupyter.org  
Jupyter est une application web utilisée pour programmer dans plus de 40 langages de programmation, dont Python, Julia, Ruby, R, ou encore Scala. Jupyter permet de réaliser des calepins ou notebooks, c'est-à-dire des programmes contenant à la fois du texte en markdown et du code en Julia, Python, R... Ces notebooks sont utilisés en science des données pour explorer et analyser des données.

### Calcul scientifique
#### Singularity
https://sylabs.io/singularity/  
Système de containers pour HPC développé au laboratoire Lawrence Berkeley pour remplir 3 critères :
Portabilité entre environnements Linux, reproductibilité des résultats et mobilité entre clusters.

### Capteurs et objets connectés
#### Node red
https://nodered.org/  
Node-Red est un outil de programmation graphique permettant de connecter des équipements entre eux et de créer des scénarios d'automatisations.

#### The Things Network
https://www.thethingsnetwork.org/  
The Things Network est un réseau LoRaWAN communautaire et open source pour l'Internet des Objets. Ce réseau permet de récupérer des données issus de capteurs sur des distances de plusieurs kilomètres.

### Sauvegarde des données
#### BackupPC
http://backuppc.sourceforge.net/  
BackupPC est un logiciel libre de sauvegardes de données informatiques, publié sous licence GPL. Il permet d'assurer une politique de sauvegardes "versionnées" pour des clients de différents types (Unix, GNU/Linux, Windows, Mac).

### Gestion sécurisée des mots de passe
#### KeePass
https://keepass.info/  
KeePass Password Safe est un gestionnaire de mots de passe publié sous la licence libre GPL v2 ou ultérieure, permettant de sauvegarder un ensemble de mots de passe dans une base de données chiffrées sous la forme d'un seul fichier dont l'extension est .kdb ou .kdbx3 selon la version.
Ce fichier de base de données s’ouvre avec un mot de passe principal et/ou avec d'autres méthodes d’authentification comme un fichier de clé.

### Chiffrement des données
#### Veracrypt
https://www.veracrypt.fr/en/Home.html  
VeraCrypt est un logiciel utilitaire sous licence libre utilisé pour le chiffrement à la volée (OTFE). Il est développé par la société française IDRIX2 et permet de créer un disque virtuel chiffré dans un fichier ou une partition. L'ensemble du dispositif de stockage demande une authentification avant de monter le disque virtuel.
Le logiciel est intégré à la liste des logiciels libres préconisés par l’État dans le cadre de la modernisation globale de ses systèmes d’informations.

### Chiffrement des emails
#### Enigmail
https://enigmail.net/index.php/en/  
Enigmail rajoute le chiffrement et la vérification OpenPGP de messages à votre programme de messageries électroniques. Enigmail se distingue par le chiffrement et le déchiffrement automatiques, et par une fonctionnalité intégrée de gestion de clés.

### Certificats SSL (https)
#### Certbot
https://certbot.eff.org/  
Certbot est le client officiel Let's Encrypt, il autorise la récupération depuis la ligne de commande de certificats X.509 valides.

## Les ressources

### Formats des données

#### CSV on the Web: A Primer
https://www.w3.org/TR/tabular-data-primer/  
CSV et métadonnées.

#### Schema\.org
https://schema.org/Dataset  
Structuration des données, métadonnées...

#### Data Catalog Vocabulary (DCAT) - Version 2
https://www.w3.org/TR/2019/PR-vocab-dcat-2-20191119/  
Structuration des données, métadonnées...

***Notes :***
<b id="f1">1</b> https://fr.wikipedia.org/wiki/Fair_data [↩](#a1)