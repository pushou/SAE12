# SAE12 réseau

- [SAE12 réseau](#sae12-réseau)
  - [1. Description de la SAE12 (semestre 1 du BUT R&T I.U.T. de Béziers)](#1-description-de-la-sae12-semestre-1-du-but-rt-iut-de-béziers)
  - [2. Recommandations aux étudiants](#2-recommandations-aux-étudiants)
      - [Conditions de travail et d'évaluation](#conditions-de-travail-et-dévaluation)
  - [3. Documentations](#3-documentations)
    - [3.1 Documentation de référence pour les réseaux avec Linux](#31-documentation-de-référence-pour-les-réseaux-avec-linux)
    - [3.2 Documentation Windows à lire impérativement avant le démarrage de la SAE](#32-documentation-windows-à-lire-impérativementavant-le-démarrage-de-la-sae)
    - [3.3 Documentation Git](#33-documentation-git)
    - [3.4 Plugins VScode intéressant à installer afin de réaliser les livrables de la SAE](#34-plugins-vscode-intéressant-à-installer-afin-de-réaliser-les-livrables-de-la-sae)
  - [4. Contexte professionnel](#4-contexte-professionnel)
    - [4.1 Description du projet](#41-description-du-projet)
      - [4.1.1 Situation](#411-situation)
      - [4.1.2 Cahier des charges de l'entreprise](#412-cahier-des-charges-de-lentreprise)
## 1. Description de la SAE12 (semestre 1 du BUT R&T I.U.T. de Béziers)

|Titre de la SAE|Gérer et dépanner le réseau du  poste de travail en entreprise|
|---------------|------------------------------------------------------------------------------------------------|
|**Quelles problématiques professionnelles se propose-t-elle d'aborder ?**|- La gestion du poste de travail est depuis toujours un défi pour les organisations informatiques.  La multiplicité des missions et un travail quotidien intense repose sur ces postes de travail ce qui en fait un sujet important. Des problématiques concrètes comme la configuration du réseau du poste de travail et le dépannage sont donc proposées aux étudiants dans cette S.A.E.. <br>- La création d'un livrable technique, sous un format maintenable et partagé par une équipe est une situation courante pour les informaticiens. Il est donc important que les étudiants pratiquent cet exercice.<br>- La réalisation de schéma réseaux est une tâche banale pour un technicien de la filière R&T et c'est un exercice utile proposé par cette SAE. <br> - De même la prise de notes et la rédaction d'item technique au travers d'un éditeur (par exemple VSCode) est une compétence essentielle dans le milieu professionnel. La sauvegarde et le "versioning" des livrables au travers de Git préparent les étudiants à un fonctionnement adopté par les organisations informatiques performantes (Infrastructure as Code , Continuous Integration & Delivery, outillage du développeur...)
|**Description de la SAÉ en quelques lignes**|Il s'agit de répondre à un cahier des charges (contexte professionnel) et de fournir des livrables sous un format et un délai contraint.
|**Formes pédagogiques**|Cours, TD, projets, lectures de supports proposés|
|**Modalités d’évaluation à concevoir pour s’assurer que cette SAÉ participe à l’acquisition du niveau de compétence ciblé**|Les capacités suivantes seront évaluées:<br>- Utiliser un IDE moderne et modulaire.<br>- Sauvegarder et versionner son travail au travers de Git et de Github.<br>- Configurer et dépanner le réseau d'un poste client sous Linux.<br>- Configurer et dépanner le réseau d'un poste client sous Windows<br>- Rédiger une documentation à l'aide du langage MarkDown.<br> - Utiliser les outils et ressources documentaires de manière professionnelle.<br>- Analyser et restituer des informations de façon synthétique.<br>- Dessiner un schéma réseau simple compréhensible par un professionnel.<br>- Connecter un PC au réseau LAN et à l'internet.<br>- Utiliser de façon simple une machine virtuelle.<br>- Utiliser les arborescences de fichiers relatives au réseau sous Linux et Windows.<br> De même les compétences transversales suivantes seront évaluées:<br>- Répondre à un cahier des charges.<br>- Lire des documentation et en extraire les informations utiles.<br>- Explorer des solutions techniques.<br>- S'impliquer dans équipe pour un projet commun.<br>- Fournir des livrables sous un format et un délai contraint.<br>- Comprendre et analyser une commande : Contextualiser/s’approprier un contexte <br>- Répartir les tâches dans l’équipe de travail. <br>- Nommer efficacement ses documents, organiser ses fichiers et dossiers <br>- Partager de façon collective l’information avec (Git).<br> Respecter des délais et échéances dans un travail en mode projet.<br>- Prévoir un temps de relecture/débogage. <br> Les compétences seront appréciées à l'aide de 4 niveaux  afin d'apprécier le travail des étudiants:<br>- **insuffisant** <br>- **satisfaisant**<br>- **remarquable**<br>- **excellent**|<br> Les livrables et le travail des étudiants seront évalués au travers de ces capacités et lors des séances pratiques.
|**Moyens alloués**| Lors des deux premières heures (CM 1h + TD 1h) il vous sera présenté:<br>- la SAE et les normes à respecter (icônes et adressage) <br>- L'outil draw.io et son integration avec VSCode.<br>- Mermaid (dessin au format MarkDown) dans VScode.<br>- L'outil VSCode et de son intégration avec Git.<br>- Le language Markdown.<br>- L'utilisation simple d'un OS virtualisé dans VirtualBox.<br>Il vous restera ensuite pour réaliser le S.A.E.: <br>- SAE encadrée : 8 heures.<br>- SAE non Encadrée : 8 heures
|**Pré-requis**|R101 R02 R103. Il s'agit de connaître les principes de bases de l'adressage IPv4, des notions de bases sur les services réseaux (dont le dns) et du routage statique (passerelle par défaut). D'autres part l'étudiant aura le niveau utilisateur sur Windows et Linux.|
|La S.A.E. alimente les **apprentissages critiques** suivants:| - AC0113: Configurer les fonctions de base du réseau local.<br> - AC0114: Maîtriser les rôles et les principes fondamentaux des systèmes d’exploitation afin d’interagir avec ceux-ci pour la configuration et administration des réseaux et services fournis.<br> - AC0115: Identifier les dysfonctionnements du réseau local. <br>- AC0116 : Installer un poste client.<br>- AC0215: Communiquer avec un client ou un collaborateur.<br>- AC0316: S’intégrer dans un environnement propice au développement et au travail collaboratif <br>- AC0311: Utiliser un système informatique et ses outils. <br>- AC0312: Lire, exécuter, corriger et modifier un programme.

## 2. Recommandations aux étudiants

Le document suivant est accessible sur GitHub:
<https://github.com/pushou/SAE12> et peut être consulté à tout moment. Il donne un exemple de ce qui est attendu sur la forme par le responsable technique de la société en termes de livrable.

- Matériels à votre disposition : PC du CloudLab sous Windows, Routeurs, (mini)switchs Cisco, PC sous Linux de l'IUT.

- Logiciels à disposition :
  - Logiciel proposé pour écrire en MarKDown : Vscode
  - Git Hub for education pour le rendu en MarkDown [Clickez ici!](https://classroom.github.com/a/WsrJSKax)

Instructions aux étudiants avant et pendant la SAE:

- Lire la documentation proposée.
- Prendre des notes dès que des informations vous sont données.
- Installer VSCode et suivre un tutoriel sur MarkDown.
- Créer un compte sur Github (Utiliser votre prénom.nom si vous voulez être noté !).
- Réfléchir avant d’entreprendre quoi que ce soit et établir un chemin en vue d'atteindre un objectif en début de chaque demi-journée.

#### Conditions de travail et d'évaluation

Travail et évaluation en groupes de deux étudiants avec un CR commun au format markdown doublé par un rendu pdf sur un repository GitHub fourni par l'enseignant.

## 3. Documentations

### 3.1 Documentation de référence pour les réseaux avec Linux

- <https://www.inetdoc.net/>
- <https://baturin.org/docs/iproute2/>

### 3.2 Documentation Windows à lire impérativement avant le démarrage de la SAE

- <https://docs.microsoft.com/fr-fr/windows-server/administration/windows-commands/ipconfig>
- <https://docs.microsoft.com/en-us/powershell/module/nettcpip/?view=windowsserver2019-ps>
- <https://github.com/MicrosoftDocs/sysinternals> & <https://docs.microsoft.com/fr-fr/sysinternals/>

### 3.3 Documentation Git

- <http://git-scm.com/book/fr/v2/D%C3%A9marrage-rapide-Rudiments-de-Git>

### 3.4 Plugins VScode intéressant à installer afin de réaliser les livrables de la SAE

- <https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one>
- <https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio>
- <https://marketplace.visualstudio.com/items?itemName=nopeslide.vscode-drawio-plugin-mermaid>
- <https://marketplace.visualstudio.com/items?itemName=telesoho.vscode-markdown-paste-image>
- <https://marketplace.visualstudio.com/items?itemName=mdickin.markdown-shortcuts>

## 4. Contexte professionnel

### 4.1 Description du projet

#### 4.1.1 Situation

Une société a constaté que ses techniciens (niveau bac pro) travaillent chacun avec leurs outils sans référentiel commun.  Chaque technicien est spécialisé sur une famille de système d'exploitation. La direction, inquiète de ce cloisonnement, voudrait rendre polyvalentes ses équipes. Cette polyvalence s'appuiera sur des documents décrivant la configuration du réseau et son dépannage pour Linux et Windows.

Selon une directive du CSO (Chief Security Officer) chaque équipe (soit deux postes de travail) doit être dans deux réseaux séparés (donc deux VLAN) des autres mais doit pouvoir communiquer avec les autres binômes.

#### 4.1.2 Cahier des charges de l'entreprise

L'entreprise souhaite utiliser GitHub comme référentiel commun pour stocker les informations et tracer les évolutions de sa documentation.
D'autre part cette société ayant comme principal activité le développement logiciel, l'utilisation de l'éditeur vscode est requise. La rédaction sera donc faite en langage MarkDown avec un rendu final au format pdf. L'utilisation de certains "plugins" est fortement conseillé.  

Le CTO (« Chief Technical Officier ») vous demande en tant que technicien supérieur de :  

- Créer un document ressource permettant à tous les techniciens de travailler sans cloisonnement afin d'améliorer la polyvalence de chacun. Ce document, qui se veut pratique, doit contenir des exemples d'utilisation d'outils logiciels pour la configuration des réseaux des postes ainsi que des outils pour analyser d’éventuels problèmes basiques(TroubleShooting). Le document doit faire correspondre une commande Linux à son équivalent Windows chaque fois que c’est possible.Chaque commande doit être accompagnée d'un exemple et de sa sortie sur le terminal. C’est le **premier livrable** à rendre.

- Concevoir une architecture réseau simple pour chaque salle avec une segmentation de deux postes  (1 par  **VLAN** distinct). Tous les réseaux doivent pouvoir communiquer entre eux. Le CTO vous demande un schéma réseau en utilisant l'outil de dessin draw.io ainsi qu'un descriptif des configurations et des actions pour mettre en place ce réseau.
L'adressage et la représentation iconique des matériels suivront les normes imposées par le CTO. Chaque réseau interne devra être dériver du poste de travail (ex poste 2= 192.168.**2**.0/24 comme réseau des PC.) C’est le **deuxième livrable** à rendre. Le CTO validera que chaque groupe de technicien a répondu au cahier des charges lors de la réalisation d'une maquette en salle de TP.

Dans ces deux livrables le C.T.O. accordera une importance à la qualité de l'expression écrite (grammaire, orthographe et rédaction) qui sera prise ne compte dans votre évaluation annuelle pour votre augmentation. Après vous être "logger" avec un compte permettant de vous identifier, lors de chaque copie d'écran du terminal il vous sera demandé de lancer la commande "uname -a" pour Linux,"echo %USERDOMAIN%\%USERNAME%". Le schéma sera l'expression du travail du groupe et vous devrez éviter de recopier le schéma d'un autre groupe.

Le C.T.O. veut évaluer votre travail individuellement. Vous devez donc **annoncer en tête de chaque livrable** votre prénom et votre nom ainsi que celui de votre binôme dans le cas d'un rendu commun.
Une bonne pratique est de mettre dans le nom du fichier du livrable vos noms et la date.

Le schéma suivant résume les deux composantes de la SAE.

``` mermaid
     flowchart LR;
        SAE12[SAE12]-->id1["Réaliser un réseau simple et communiquant entre les équipes"];
        SAE12-->id3["Configurer et dépanner le réseau de son poste de travail Windows ou Linux"];
        style SAE12 fill:#99ccff,stroke:#337,stroke-width:8px;
        style id1 fill:#f9f,stroke:#337,stroke-width:2px;
        style id3 fill:#f9f,stroke:#337,stroke-width:2px;
        click SAE12 href "https://github.com/pushou/SAE12.git" "Lien vers le repo Git de la SAE12"
```
