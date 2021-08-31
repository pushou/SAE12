# Présentation du contexte de la SAE12: Gérer le poste de travail en entreprise

## 1.1 Présentation du contexte de la SAE12

### 1.1.1 Contenu des cours et des TD

- CM 1h : Présentation de la SAE et normes à respecter (icônes).
- TD 1h : Rédaction du plan d’actions avec une brainstorming sur MindView qui sera validé et noté par l’enseignant ou les pros présents.

### 1.1.2 Heures allouées

- SAE encadrée : 8 heures
- SAE non Encadrée : 8 heures

### 1.1.3 Recommandations aux étudiants

Le document suivant est accessible sur GitHub:

- Matériels à votre disposition : PC du CloudLab, Routeur Mikrotik, (mini)switchs Cisco.

- Logiciels à disposition :
  - MindView (service pédagogique pour les licences) ;
  - Licence logicielle Microsoft (voir le service pédagogique et <https://azureforeducation.microsoft.com/devtools>)
  - Logiciel proposé pour écrire en MarKDown : Vscode,
  - Git Hub for education pour le rendu en MarkDown (voir enseignant pour l’URL)

Instructions étudiants avant la SAE:

- Lire la documentation
- Se préoccuper du matériel
- Établir un plan des actions à réaliser avant d’entreprendre quoi que ce soit.

Conditions de travail :

Travail en groupes de deux étudiants avec un CR commun au format markdown doublé par un rendu pdf).

Documentation suggérée à lire impérativement avant le démarrage de la SAE:

<https://baturin.org/docs/iproute2/>
<https://docs.microsoft.com/fr-fr/windows-server/administration/windows-commands/ipconfig>
<https://docs.microsoft.com/en-us/powershell/module/nettcpip/?view=windowsserver2019-ps>
<https://github.com/MicrosoftDocs/sysinternals>

## Plugins VScode sugg- [Présentation du contexte de la SAE12: Découverte du poste de travail](#présentation-du-contexte-de-la-sae12-découverte-du-poste-de-travail)

- [Contexte pédagogique](#contexte-pédagogique)
  - [Heures allouées](#heures-allouées)
- [Contexte professionnel](#contexte-professionnel)
- [Plugins VScode suggérés](#plugins-vscode-suggérés)érés

<https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one>

## 2. Contexte professionnel

### 2.1 Description du projet

Une société a constaté que ses techniciens (niveau bac pro) travaillent chacun avec leurs outils sans référentiel commun.  Chaque technicien est spécialisé sur une famille d’OS ou de matériels. La direction inquiète de ce cloisonnement et voudrait rendre polyvalentes ces équipes.

D'autre part la direction souhaite favoriser l'intégration des jeunes de la génération Z dans l'entreprise. Désirant les fidéliser elle souhaite que ces "Z" aient sur leurs postes de travail à la fois de Linux et de Windows.

Selon une directive du CSO (Chief Security Officer) chaque équipe (soit deux postes de travail) doit être dans un réseau séparé des autres mais doit pouvoir communiquer avec eux. L'utilisation d'un firewall est recommandé.

### 2.2 Cahier des charges de l'entreprise

L'entreprise souhaite utiliser GitHub comme référentiel commun pour stocker les informations et tracer les évolutions de sa documentation.
D'autre part cette société ayant comme principal activité le développement logiciel, l'utilisation de l'éditeur vscode est requise avec certains "plugins" fortement conseillé.

Le CTO (« Chief Technical Officier ») vous convoque en tant que technicien supérieur pour :  

    a. Créer un document ressource permettant à tous les techniciens de travailler sans cloisonnement afin d'améliorer la polyvalence de chacun. Ce document qui se veut pratique avec des exemples doit contenir des outils logiciels pour la configuration des réseaux des postes et aussi des outils pour analyser d’éventuels problèmes basiques sur un poste de travail (TroubleShooting). Le document doit faire correspondre une commande Linux à son équivalent Windows si c’est possible. C’est le **premier livrable** à rendre.
    b. Trouver la meilleure solution et être capable de la défendre auprès de la direction afin de mixer Windows et Linux ensemble sur le même poste de travail. La solution retenue devra être implémentée. Il faudra comparer dans un tableau les différentes solutions. C’est le **deuxième livrable** à rendre. Un "brainstorming" des solutions possibles est organisé par le C.T.O..
    c. Concevoir une architecture réseau simple pour chaque salle avec une segmentation de deux postes par réseaux et tous les réseaux pouvant communiquer entre eux. Le CTO vous demande un schéma réseau en utilisant un des outils de dessin suivant :
    • Visio (Microsoft) ;
    • Dia (Linux) ;
    • Yed (Web) ;
    C’est le **troisième livrable** à rendre.

Le schéma suivant résume les trois composantes de la SAE.

 ``` Mermaid
   flowchart LR;
        SAE12-->id1["Réaliser un réseau simple et communiquant entre les équipes"];
        SAE12-->id2["Implémenter Linux et Windows sur le même poste de travail"];
        SAE12-->id3["Configurer le réseau de son poste de travail"];
        click SAE12 href "https://github.com/pushou/SAE12.git" "Lien vers le repo de la SAE12"
