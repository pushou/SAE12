# Présentation du contexte de la SAE12: Gérer le poste de travail en entreprise

## 1.1 Présentation du contexte de la SAE12

### 1.1.1 Contenu des cours et des TD

  CM 1h + TD 1h
  Lors de ses deux heures il vous sera présenté:

- la SAE et normes à respecter (icônes et adressage).
- L'outil draw.io et son integration avec VSCode.
- l'outil VSCode et de son intégration avec  Git.
- Le language Markdown.
- L'installation d'un OS par virtualisation afin de réaliser la S.A.E. dans de bonnes conditions.

### 1.1.2 Heures allouées

- SAE encadrée : 8 heures
- SAE non Encadrée : 8 heures

### 1.1.3 Recommandations aux étudiants

Le document suivant est accessible sur GitHub:
<https://github.com/pushou/SAE12> et peut être consulté à tout moment. Il donne un exemple de ce qui est attendu par le responsable technique de la société en termes de livrable.

- Matériels à votre disposition : PC du CloudLab sous Windows, Routeurs, (mini)switchs Cisco, PC sous Linux de l'IUT.

- Logiciels à disposition :
  - Logiciel proposé pour écrire en MarKDown : Vscode
  - Git Hub for education pour le rendu en MarkDown (voir l'enseignant pour obtenir l’URL de rendu)

Instructions étudiants avant la SAE:

- Lire la documentation proposée.
- Installer VSCode et suivre un tutoriel sur MarkDown.
- Créer un compte sur Github (Utiliser votre prénom.nom si vous voulez être noté !).
- Réfléchir avant d’entreprendre quoi que ce soit et établir un chemin à réaliser en début de chaque demi-journée.

#### Conditions de travail

Travail en groupes de deux étudiants avec un CR commun au format markdown doublé par un rendu pdf sur un repository GitHub fourni par l'enseignant.

#### Documentation à lire impérativement avant le démarrage de la SAE

- <https://baturin.org/docs/iproute2/>
- <https://docs.microsoft.com/fr-fr/windows-server/administration/windows-commands/ipconfig>
- <https://docs.microsoft.com/en-us/powershell/module/nettcpip/?view=windowsserver2019-ps>
- <https://github.com/MicrosoftDocs/sysinternals>

## Plugins VScode intéressant afin de réaliser les livrables de la SAE

- <https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one>
- <https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio>
- <https://marketplace.visualstudio.com/items?itemName=nopeslide.vscode-drawio-plugin-mermaid>
- <https://marketplace.visualstudio.com/items?itemName=telesoho.vscode-markdown-paste-image>

## 2. Contexte professionnel

### 2.1 Description du projet

#### 2.1.1 Situation

Une société a constaté que ses techniciens (niveau bac pro) travaillent chacun avec leurs outils sans référentiel commun.  Chaque technicien est spécialisé sur une famille de système d'exploitation. La direction inquiète de ce cloisonnement voudrait rendre polyvalentes ses équipes. Cette polyvalence s'appuiera sur des documents décrivant la configuration du réseau et son dépannage pour Linux et Windows.

Selon une directive du CSO (Chief Security Officer) chaque équipe (soit deux postes de travail) doit être dans un réseau séparé des autres mais doit pouvoir communiquer avec eux. L'utilisation d'un firewall est recommandé.

#### 2.1.2 Cahier des charges de l'entreprise

L'entreprise souhaite utiliser GitHub comme référentiel commun pour stocker les informations et tracer les évolutions de sa documentation.
D'autre part cette société ayant comme principal activité le développement logiciel, l'utilisation de l'éditeur vscode est requise. La rédaction sera faite en langage MarDown. L'utilisation de certains "plugins" fortement conseillé.  

Le CTO (« Chief Technical Officier ») vous demande en tant que technicien supérieur de :  

- Créer un document ressource permettant à tous les techniciens de travailler sans cloisonnement afin d'améliorer la polyvalence de chacun. Ce document qui se veut pratique avec des exemples doit contenir des outils logiciels pour la configuration des réseaux des postes et aussi des outils pour analyser d’éventuels problèmes basiques sur un poste de travail (TroubleShooting). Le document doit faire correspondre une commande Linux à son équivalent Windows si c’est possible.Chaque commande doit être accompagnée d'un exemple et de sa sortie. C’est le **premier livrable** à rendre.

- Concevoir une architecture réseau simple pour chaque salle avec une segmentation de deux postes par réseaux et tous les réseaux pouvant communiquer entre eux. Le CTO vous demande un schéma réseau en utilisant l'outil de dessin draw.io. L'adressage et la représentation icôniques des matériels suivra les normes imposées par le CTO. C’est le **deuxième livrable** à rendre. Le CTO validera que chaque groupe de technicien a répondu au cahiers des charges.

Le schéma suivant résume les deux composantes de la SAE.

``` mermaid
     flowchart LR;
        SAE12[SAE12]-->id1["Réaliser un réseau simple et communiquant entre les équipes"];
        SAE12-->id3["Configurer et dépanner le réseau de son poste de travail"];
        style SAE12 fill:#99ccff,stroke:#337,stroke-width:8px;
        style id1 fill:#f9f,stroke:#337,stroke-width:2px;
        style id3 fill:#f9f,stroke:#337,stroke-width:2px;
        click SAE12 href "https://github.com/pushou/SAE12.git" "Lien vers le repo Git de la SAE12"
```

## 3. Description de la SAE et objectifs

|Titre de la SAÉ|Dépannage et intégration réseau d"un poste client multi-os|
|---------------|------------------------------------------------------------------------------------------------|
|**Quelle problématique professionnelle propose-t-elle ?**|- La gestion du poste de travail est depuis toujours un défi pour les organisations informatiques du fait de la multiplicité des missions des usagers et du travail quotidien des personnels qui repose sur des postes de travail adaptés. Des problématiques concrètes comme la configuration du réseau du poste de travail et le dépannage est proposée aux étudiants. <br>- La création d'un livrable technique, sous un format maintenable par une équipe est une situation courante pour les informaticiens.<br>- la réalisation de schéma réseaux est une tâche courante pour un technicien de la filère R&T et c'est un exercice utile proposé par cette SAE. De même la prise de notes technique au travers d'un éditeur (VSCode) très utilisé de nos jours et la sauvegarde au travers de Git prépare les étudiants à un fonctionnement adopté par les organisations informatiques performantes (Infrastructure as Code , Continuous Integration & Delivery...)
|**Description de la SAÉ en quelques lignes**|-Il s'agit de répondre à un cahier des charges <br> - D'explorer des solutions techniques, de choisir celle répondant le mieux au besoin<br>D'être capable d'argumentez sur ces choix.<br>- de fournir des livrables sous un format et un délai contraint.
|**Formes pédagoqiques**|TD, projets|
|**Modalités d’évaluation à concevoir pour s’assurer que cette SAÉ participe à l’acquisition du niveau de compétence ciblé**|L’étudiant doit:<br> - être capable de retranscrire l’architecture réseau grâce à un outil de schéma réseau <br> - de présenter un livrable clair, généré au fur et à mesure du déroulement de la SAE par la prise de note.
