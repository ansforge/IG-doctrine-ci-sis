<div style="
    background-color: #fff5f5; 
    color: #e57373; 
    border: 1px solid #e57373; 
    padding: 10px; 
    border-radius: 5px; 
    font-size: 14px; 
    text-align: center; 
    max-width: 300px; 
    margin: 20px auto;
">
    ⚠️ Work in Progress
</div>


La vague actuelle de modernisation des systèmes d’information de santé (SIS) facilite les échanges d’information, sans pour autant nécessiter la refonte générale de ces systèmes. La voie privilégiée du progrès repose sur l’interopérabilité des systèmes d'information plutôt que sur leur homogénéité.

Une des réponses à l'interopérabilité des systèmes d'information est basée sur la dématérialisation harmonisée des échanges de données entre ces systèmes.

La méthode d'élaboration des spécifications fonctionnelles des échanges est à destination des maîtrises d'ouvrages et maîtrises d'œuvre en charge de l'étude d'un projet comportant des interactions entre SI partenaires.

A partir des exigences recueillies auprès des parties prenantes du métier, le but de la méthode est de modéliser les échanges de données en réalisant les actions suivantes :

<div>
    <ul>
        <li>Identifier ces interactions et les décrire sous la forme de processus métier collaboratifs en y incluant les partenaires qui interagissent, acteurs de ces processus ; </li>
        <li>Identifier, au sein de chaque processus, les échanges d'informations entre ces partenaires et décrire sémantiquement ces informations ainsi que les nomenclatures portées par ces échanges.</li>
    </ul>
</div>

Pour rappel, les processus métier collaboratifs sont ceux dans lesquels il y a des échanges d'informations entre partenaires.

### Description de la méthode

Un volet du cadre d'interopérabilité des systèmes d'information de santé (CI-SIS) est composé des documents suivants :

<div>
    <ul>
        <li>Spécifications fonctionnelles des échanges,</li>
        <li>Etude des normes et standards (si nécessaire),</li>
        <li>Spécification technique des échanges.</li>
    </ul>
</div>

<div class="figure" style='text-align: center;'>
    <img src="docs-volet-cisis.png" alt="CP" title="Figure 4: Documents constituant un volet du CI-SIS" style="width:80%;">
    <figcaption><b>Figure 4: Documents constituant un volet du CI-SIS</b></figcaption>
</div>

Cette méthode est constituée de six étapes. Le résultat de chacune de ces étapes est consigné dans le dossier des spécifications fonctionnelles des échanges. Ces étapes, détaillées dans la suite du document, sont les suivantes :

<div>
    <ul>
        <li>Etape 0 : Cadre juridique et orientations organisationnelles ;</li>
        <li>Etape 1 : organisation du contexte métier ;</li>
        <li>Etape 2 : définition des processus collaboratifs ;</li>
        <li>Etape 3 : description des processus collaboratifs et identification des flux ;</li>
        <li>Etape 4 : Identification des concepts véhiculés dans les flux d’informations et correspondance avec les classes et attributs du MOS ;</li>
        <li>Etape 5 : modélisation des flux.</li>
    </ul>
</div>

L'élaboration de ces étapes repose sur la notation UML (Unified Modeling Language). La notation BPMN (Business Process Model Notation) peut également être utilisée pour décrire les processus à l’étape 3. L'application de cette méthode nécessite des connaissances de base dans ces techniques de modélisation.

### Niveaux d’interopérabilité et spécifications fonctionnelles des échanges

<div class="figure" style='text-align: center;'>
    <img src="niveaux-interop.png" alt="CP" title="Niveaux d’interopérabilité" style="width:80%;">
    <figcaption><b>Niveaux d’interopérabilité définis dans le cadre d’interopérabilité européen (European Interoperability framework - EIF)</b></figcaption>
</div>

Les spécifications fonctionnelles des échanges font partie du niveau sémantique de l'interopérabilité. Elles peuvent intégrer également les niveaux juridique et organisationnel en citant le cadre juridique de ces échanges ainsi que les orientations organisationnelles choisies (voir figure ci-dessous). Toute évolution fonctionnelle doit générer la mise à jour de ces spécifications. Ces spécifications fonctionnelles sont neutres vis-à-vis de la syntaxe des échanges. La transformation dans la syntaxe choisie est effectuée dans la phase de spécifications techniques.

<div class="figure" style='text-align: center;'>
    <img src="niveaux-interop-sf.png" alt="CP" title="Niveaux d’interopérabilité couverts par les spécifications fonctionnelles des échanges" style="width:20%;">
    <figcaption><b>Niveaux d’interopérabilité couverts par les spécifications fonctionnelles des échanges</b></figcaption>
</div>

### Déroulement de la méthode

**La méthode par l'exemple** : cette méthode est illustrée par un exemple extrait de la phase préparatoire des spécifications fonctionnelles de l'étude "Cercle de soins".

#### Etape 0 : Cadre juridique et orientations organisationnelles

Le cadre juridique de l’étude doit être cité à cette étape afin de le prendre en considération à toutes les étapes de la méthode.

Les orientations organisationnelles et les moyens mis en œuvre pour rationaliser les processus et favoriser les échanges doivent être mentionnés à cette étape.

Les cas d’usage sont décrits à ce niveau. Il s’agit de détailler, à l’aide de diagrammes de séquences et de parties textuelles, les acteurs et les transactions entre ces acteurs supports à l’échange ou au partage de l’information médicale dans le contexte d’un workflow réalisé par différents systèmes.

#### Etape 1 : Organisation du contexte métier

Le but de cette étape est de placer l'étude dans son contexte et d'identifier le ou les processus collaboratifs du périmètre de cette étude.

Si les informations de contexte s'avèrent insuffisantes à cette étape, il est tout à fait possible de passer à l'étape 2, en définissant les processus collaboratifs du périmètre de l'étude. Une fois les processus collaboratifs définis, il est envisageable de reprendre l'étape 1 en les rassemblant en groupes de processus. Il est également possible de revenir l'étape 1 à tout moment, quelle que soit l'étape en cours de spécification.

Une fois identifiés, les processus sont représentés dans un diagramme de paquetages.

**Remarque pratique sur les diagrammes de paquetages :** un paquetage peut être un regroupement d'une grande variété d’éléments, comme des processus, des acteurs, d'autres paquetages imbriqués, des interactions, etc. Cette diversité implique que la représentation graphique des paquetages dans un outil UML peut être obtenue par un diagramme de paquetages mais aussi par d’autres diagrammes, notamment un diagramme de classes, un diagramme de cas d'utilisation, etc.

##### Description des paquetages

Les paquetages doivent être décrits et stéréotypés. La granularité des paquetages dépend du contexte de l'étude.

Le paquetage **<<Domaine>>** représente le domaine d'activité dans lequel se situe l’étude ; le domaine est composé d'un ou de plusieurs groupes de processus.

Le paquetage **<<GroupeProcessus>>** est composé d'un ou plusieurs processus métier collaboratifs.

Le paquetage **<<Processus>>** représente le processus métier collaboratif qui est décrit à partir de l'étape 2. A noter que le périmètre de l'étude concerne des processus qui peuvent être présents dans un seul groupe de processus ou répartis dans plusieurs groupes de processus.

##### Règles applicables

Les règles applicables dans cette étape sont les suivantes :

<div>
    <ul>
        <li>Les noms du domaine d'activité, groupes de processus et processus sont libres ; pour les processus, le nom donné doit être constitué d'une phrase infinitive, comme "Commander un DMI » ;</li>
        <li>Les domaines d'activité et les groupes de processus doivent comporter une description ; pour les processus, leur description est donnée à l'étape 2 ;</li>
        <li>Les abréviations sont évitées pour garder la précision ; les acronymes sont autorisés seulement s'ils sont documentés.</li>
    </ul>
</div>

##### Exemple

Le diagramme de paquetages de la ci-dessous est extrait de l’étude "Cercle de soins". Le processus collaboratif faisant partie du périmètre de l’étude est indiqué en bleu sur ce diagramme.

<div class="figure" style='text-align: center;'>
    <img src="ex-cds.png" alt="CP" title="Organisation du contexte métier de l’étude « Cercle de soins »" style="width:50%;">
    <figcaption><b>Organisation du contexte métier de l’étude « Cercle de soins »</b></figcaption>
</div>

#### Etape 2 : définition des processus collaboratifs

Les processus métier collaboratifs ont été identifiés à l'étape 1 "Organisation du contexte métier". Le but de l'étape 2 est de les décrire.
Cette modélisation est une vue macroscopique des processus qui sont représentés au moyen de diagrammes de cas d’utilisation UML. Dans cette étape, l'action la plus importante consiste à identifier, définir et relier les acteurs aux processus.

D’éventuelles dépendances entre les processus peuvent être formalisées par des :

<div>
    <ul>
        <li>Notions de spécialisation sur ces processus, héritage UML ;</li>
        <li>Relations d'inclusion, pour factoriser dans un même processus des enchainements identiques dans plusieurs processus ;</li>
        <li>Relations d'extension, pour formaliser une condition exceptionnelle appelée " point d’extension " conduisant à un nouveau processus en étendant le processus initial.</li>
    </ul>
</div>

Toutefois, l’exercice ne doit pas être poussé trop loin. Si ces notions d’héritage, d'inclusion et d'extension semblent incontournables, il faut néanmoins avant d’y recourir, revoir la liste des processus et vérifier qu’elle est pertinente.
Un diagramme de cas d’utilisation contient un à plusieurs cas d'utilisation ainsi que les acteurs impliqués. Chaque cas d’utilisation correspond à un processus métier collaboratif. Les caractéristiques du cas d’utilisation sont détaillées à la suite du diagramme.

##### Description des acteurs

Les acteurs doivent être décrits et stéréotypés.

L’acteur stéréotypé **<<Personne>>** représente une personne physique ou morale.

L'acteur stéréotypé **<<Système>>** est un système d'information utilisé par un acteur **<<Personne>>** pour effectuer une action particulière du processus métier collaboratif.

L’acteur stéréotypé **<<Rôle>>** est le rôle fonctionnel "générique" vis-à-vis du processus, joué par un ou plusieurs acteur(s) **<<Système>>**.

Les relations entre les acteurs et, entre un acteur et son rôle, sont représentées sur les diagrammes de cas d’utilisation, par des liens de communication.

L'utilité de l’acteur **<<Rôle>>** est de représenter tous les acteurs **<<Système>>** ayant le même comportement vis-à-vis du processus. La représentation de l'acteur **<<Rôle>>** est obligatoire dans le cas d'utilisation alors que les représentations des acteurs **<<Système>>** ou **<<Personne>>** sont facultatives.

La description des acteurs **<<Rôle>>** doit donner lieu au tableau de définition des acteurs et des systèmes concernés.

Exemple du cercle de soins :

| Acteur | Description |
| --- | --- |
| Créateur | Le rôle de créateur incarné par un système est de créer ou mettre à jour le cercle de soins d'une personne. Exemples de créateur : service numérique d’appui à la coordination, dossier patient informatisé |
| Gestionnaire | Le rôle de gestionnaire incarné par un système est de gérer et stocker le cercle de soins ainsi que donner accès aux informations en cas de consultation. Exemples de gestionnaire : dossier patient informatisé, service numérique de partage de données |
| Consommateur | Le rôle de consommateur incarné par un système est de consulter un cercle de soins.Exemples de consommateur : un dossier patient informatisé, un système de gestion de laboratoire, un système d’information radiologique, un logiciel de gestion de cabinet, un service numérique d’appui à la coordination |

##### Caractéristiques des processus collaboratifs

Chaque processus collaboratif possède les caractéristiques suivantes :

<div>
    <ul>
        <li> Le service attendu du processus métier collaboratif ; une partie narrative peut très bien compléter cette description ; dans ce cas, cette narration doit se dérouler dans le contexte du cas d’utilisation, avoir un début, une fin et des acteurs qui interagissent en s'échangeant de l’information ; la description du service attendu est obligatoire ;</li>
        <li> Une ou des pré-conditions; ce sont les conditions qui doivent être vérifiées pour le déclenchement du processus métier collaboratif; les pré-conditions sont facultatives ;</li>
        <li>  Une ou des post-conditions; ce sont les conditions qui sont vérifiées après l'arrêt du scenario principal du processus métier collaboratif; les post-conditions sont facultatives ;</li>
        <li> Une ou des contraintes fonctionnelle(s) ; ce sont les contraintes ayant un impact sur le processus métier collaboratif qui peuvent entrainer une modification du processus ; à ce stade de l'étude, l'impact sur les échanges d'informations du processus n'est pas connu ; les contraintes fonctionnelles sont facultatives ;</li>
        <li> Le scénario principal (ou nominal), qui représente les interactions les plus significatives du processus ("quand tout se passe bien") ; d’autres scénarios peuvent être ajoutés afin de décrire les autres interactions possibles ; les scénarios sont facultatifs</li>
    </ul>
</div>

Exemple d’un diagramme de cas d’utilisation extrait du volet « Cercle de soins » :

 <div class="figure" style='text-align: center;'>
    <img src="cds-ex-2.png" alt="CP" title="Diagramme du cas d’utilisation « Création du cercle de soins »" style="width:80%;">
    <figcaption><b>Diagramme du cas d’utilisation « Création du cercle de soins »</b></figcaption>
</div>

Exemple de définition d’un processus collaboratif extrait du volet « Cercle de soins » :

**Service attendu** : le créateur du cercle de soins envoie au gestionnaire du cercle de soins une demande de création du cercle de soins de la personne.

**Pré-conditions** : le créateur du cercle de soins doit au préalable :

<div>
    <ul>
        <li> Être habilité ;</li>
        <li> Vérifier l’absence du cercle de soins de la personne par le gestionnaire du cercle de soins via une demande de consultation ;</li>
        <li> Disposer des paramètres de création de cercle de soins (et en particulier de l’identifiant du patient)</li>
    </ul>
</div>

**Post-conditions** : N/A

**Contraintes fonctionnelles** : N/A

**Scénario nominal** : N/A

##### Règles applicables

Les règles applicables à cette étape sont les suivantes :

<div>
    <ul>
        <li>Les noms des cas d'utilisation doivent reprendre les noms des processus collaboratifs décrits à l'étape 1 ; pour rappel, ils doivent être constitués d'une phrase infinitive, comme par exemple "Création du cercle de soins » ;</li>
        <li>Les noms des acteurs, sauf cas particulier, doivent être au singulier.</li>
    </ul>
</div>

#### Etape 3 : identification des flux

Les processus métier collaboratifs ont été identifiés à l'étape 1 "Organisation du contexte métier", puis définis à l'étape 2 "Définition des processus collaboratifs". Le but de l'étape 3 est de décrire le comportement des acteurs stéréotypés **<<Rôle>>** identifiés à l’étape 2 et de préciser les flux échangés par ces acteurs **<<Rôle>>**.

Il est préconisé de modéliser chaque processus métier collaboratif identifié à l'étape 2, par un diagramme d'activité UML. Le résultat de l’étape 3 est un ensemble de diagrammes d’activité. Chaque diagramme est composé d’acteurs **<<Rôle>>** (représentés par des travées), d’actions et de flux.

Cette modélisation peut être faite, si souhaité, par un diagramme BPMN ou un diagramme de séquence UML. Le diagramme BPMN offre plus d'options de modélisation que le diagramme d’activité UML. Il est donc possible de réduire les options de modélisation BPMN à celles préconisées par la méthode.

Le diagramme de séquence UML offre moins d'options de modélisation que le diagramme d'activité UML. Le diagramme de séquence s’avère donc insuffisant pour décrire un processus collaboratif en prenant en compte toutes les recommandations données par la méthode.

Il est possible, afin d’offrir une vue globale, de représenter en annexe des scénarios qui montrent des exemples d'enchainement des différents processus décrits à cette étape. Une étude peut décrire un à plusieurs scénarios. Cependant, il n’est pas nécessaire de lister exhaustivement l’ensemble des scénarios couverts par l’étude.

##### Description des acteurs

Chaque acteur est représenté sur le diagramme par une travée appelée aussi partition, couloir ou ligne d’eau. Une travée rassemble les actions, nœuds de contrôle et flux sous la responsabilité de cet acteur.

Les acteurs représentés sont ceux décrits sous le stéréotype " Rôle ", à l’étape 2.

##### Description des actions

Dans cette analyse ciblée sur les échanges, il n’est pas utile de chercher à trop détailler les actions internes aux acteurs. Sur le diagramme, cela se traduit par un nombre raisonnable d'actions dans les travées. Les actions qui ne génèrent pas de flux d’informations, peuvent être présentes pour améliorer la compréhension du processus.

Les actions sont représentées par des nœuds d’activité UML sur le diagramme et doivent être décrites (voir les différents nœuds d’activité ci-dessous).
<div class="figure" style='text-align: center;'>
    <img src="Noeud-activité.png" alt="CP" title="Différents nœuds d’activité" style="width:80%;">
    <figcaption><b>Différents nœuds d’activité</b></figcaption>
</div>

Il existe également des nœuds de contrôle qui permettent d’organiser les flux entre les actions (voir les différents nœuds de contrôle ci-dessous).

<div class="figure" style='text-align: center;'>
    <img src="noeuds-controle.png" alt="CP" title="Différents nœuds de contrôle" style="width:80%;">
    <figcaption><b>Différents nœuds de contrôle</b></figcaption>
</div>

##### Description des flux

Un flux de contrôle décrit le séquencement entre deux nœuds d’activité ou entre un nœud de contrôle et un nœud d’activité.

Un flux d’information est utilisé pour représenter les informations qui circulent entre les actions de deux acteurs différents, il passe d’une travée à une autre.

Selon le contexte, si les flux de réponse des actions ont été formulés dans le besoin recueilli auprès du métier, alors ils doivent faire partie du diagramme d’activité. Les flux de réponse sont également des flux d’information.

Seuls les flux d’information doivent être décrits.

L'exemple présenté ci-dessous illustre la représentation du processus métier collaboratif "Création du cercle de soins" par un diagramme d'activité accompagné de la description des actions.

 <div class="figure" style='text-align: center;'>
    <img src="collab-cds-identification-flux.png" alt="CP" title="Processus collaboratif « Création du cercle de soins » et identification des flux" style="width:40%;">
    <figcaption><b>Processus collaboratif « Création du cercle de soins » et identification des flux</b></figcaption>
</div>

| Action | Description |
| --- | --- |
| Saisir le cercle de soins | Le créateur du cercle de soins saisit les informations relatives au cercle de soins qui ont vocation à être partagées. |
| Envoyer la demande | Après validation de la saisie, le créateur du cercle de soins soumet au gestionnaire du cercle de soins, une demande de création du cercle de soins |
| Créer le cercle de soins | Le cercle de soins est créé par le gestionnaire du cercle de soins |

##### Règles applicables

Les règles applicables à cette étape sont les suivantes :

<div>
    <ul>
        <li>Les noms des flux doivent être écrits au singulier et respecter la convention de nommage [UpperCamelCase](https://fr.wikipedia.org/wiki/CamelCase) ;</li>
        <li>Les articles, propositions, etc. ainsi que les accents doivent être retirés des noms des flux ;</li>
        <li>Les actions doivent commencer par un verbe à l’infinitif ;</li>
        <li>Les noms des acteurs doivent suivre la convention suivante : " InstanceActeur : RoleActeur " ; seul   RoleActeur » est à renseigner.</li>
    </ul>
</div>

Pour plus de commodités, il est possible de numéroter les flux.

##### Synthèse

Cette synthèse regroupe sur le diagramme des acteurs/transactions l’ensemble des acteurs et des flux d’information échangés entre ces acteurs.
Le diagramme des acteurs/transactions regroupe l’ensemble des acteurs impliqués dans les échanges et l’ensemble des flux d’informations échangés entre ces acteurs.

Exemple de diagramme des acteurs/transactions dans le contexte du volet « Cercle de soins » :

<div class="figure" style='text-align: center;'>
    <img src="diagramme-acteurs-transaction.png" alt="CP" title="Diagramme des acteurs/transactions dans le contexte du volet « Cercle de soins »" style="width:80%;">
    <figcaption><b>Diagramme des acteurs/transactions dans le contexte du volet « Cercle de soins »</b></figcaption>
</div>

Un tableau récapitulatif permet de décrire chaque flux d’information identifié avec les caractéristiques suivantes :

<div>
    <ul>
        <li>Nom ;</li>
        <li>Processus collaboratif ;</li>
        <li>Acteur émetteur ;</li>
        <li>Acteur récepteur ;</li>
        <li>Indication si le flux fait partie du périmètre de l'étude ; par exemple, l’indication " Non " peut concerner un flux déclenchant un autre processus non inclus dans le périmètre de l’étude.</li>
    </ul>
</div>

Lorsqu’un même flux d’informations est identifié dans plusieurs processus, ou plusieurs fois dans le même processus, le tableau compte alors autant de lignes que de fois où le flux est identifié.
Remarque : Un même flux d’informations évoluant dans le temps peut être constitué d'instances différentes. Par exemple, un dossier de sinistre d’assurance circule entre plusieurs acteurs et est rempli au fur et à mesure de l’avancée dans le processus. Le tableau est alors constitué de plusieurs lignes pour le même flux. Il est alors recommandé par la suite, à partir de l'étape 5, de factoriser ces instances et de ne considérer, qu’un seul flux regroupant toutes les informations nécessaires au déroulement du processus.

Exemple du tableau de synthèse de l’ensemble des flux d’information dans le contexte du volet « Cercle de soins » :

| Flux | Processus | Emetteur | Récepteur | Périmètre |
| --- | --- | --- | --- | --- |
| Flux 1 - CreationCercleSoins | Création du cercle de soins | Createur | Gestionnaire | Oui |
| Flux 2 - RechercheCercleSoins | Consultation du cercle de soins | Consommateur | Gestionnaire | Oui |
| Flux 3 - ResultatRechercheCercleSoins | Consultation du cercle de soins | Gestionnaire | Consommateur | Oui |
| Flux 4 - MiseJourCercleSoins | Mise à jour du cercle de soins | Createur | Gestionnaire | Oui |

Ce tableau sera ensuite repris pour construire le tableau des acteurs/transactions qui regroupe pour chaque acteur impliqué l’ensemble des flux d’information implémentés par cet acteur et qui définit le caractère obligatoire ou optionnel de chacun des flux ainsi que le lien sur la section qui décrit le flux d’un point de vue technique.

Exemple de tableau acteurs/transactions de l’étude technique dans le contexte du volet « Cercle de soins » :

<table style="width:481.7pt;border-collapse:collapse;border:none;">
    <tbody>
        <tr>
            <td style="width: 73.7pt;border: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:center;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'>Acteur</p>
            </td>
            <td style="width: 174.15pt;border-top: 1pt solid windowtext;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-image: initial;border-left: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:center;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'>Transaction</p>
            </td>
            <td style="width: 116.9pt;border-top: 1pt solid windowtext;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-image: initial;border-left: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:center;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'>Caractère requis / optionnel de la transaction</p>
            </td>
            <td style="width: 116.95pt;border-top: 1pt solid windowtext;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-image: initial;border-left: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:center;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'>Vol &amp; section</p>
            </td>
        </tr>
        <tr>
            <td rowspan="2" style="width: 73.7pt;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Cr&eacute;ateur</span></p>
            </td>
            <td style="width: 174.15pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Flux 1&nbsp;: CreationCercleSoins</span></p>
            </td>
            <td style="width: 116.9pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Requis</span></p>
            </td>
            <td style="width: 116.95pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Lien sur la section dans le volume des sp&eacute;cifications techniques (Volume 2)</span></p>
            </td>
        </tr>
        <tr>
            <td style="width: 174.15pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Flux 4&nbsp;: MiseJourCercleSoins</span></p>
            </td>
            <td style="width: 116.9pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Requis</span></p>
            </td>
            <td style="width: 116.95pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Idem</span></p>
            </td>
        </tr>
        <tr>
            <td rowspan="4" style="width: 73.7pt;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Gestionnaire</span></p>
            </td>
            <td style="width: 174.15pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Flux 1&nbsp;: CreationCercleSoins</span></p>
            </td>
            <td style="width: 116.9pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Requis</span></p>
            </td>
            <td style="width: 116.95pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Idem</span></p>
            </td>
        </tr>
        <tr>
            <td style="width: 174.15pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Flux 2&nbsp;: RechercheCercleSoins</span></p>
            </td>
            <td style="width: 116.9pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Requis</span></p>
            </td>
            <td style="width: 116.95pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Idem</span></p>
            </td>
        </tr>
        <tr>
            <td style="width: 174.15pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Flux 3&nbsp;: ResultatRechercheCercleSoins</span></p>
            </td>
            <td style="width: 116.9pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Requis</span></p>
            </td>
            <td style="width: 116.95pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Idem</span></p>
            </td>
        </tr>
        <tr>
            <td style="width: 174.15pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Flux 4&nbsp;: MiseJourCercleSoins</span></p>
            </td>
            <td style="width: 116.9pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Requis</span></p>
            </td>
            <td style="width: 116.95pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Idem</span></p>
            </td>
        </tr>
        <tr>
            <td rowspan="2" style="width: 73.7pt;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Consommateur</span></p>
            </td>
            <td style="width: 174.15pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Flux 2&nbsp;: RechercheCercleSoins</span></p>
            </td>
            <td style="width: 116.9pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Requis</span></p>
            </td>
            <td style="width: 116.95pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Idem</span></p>
            </td>
        </tr>
        <tr>
            <td style="width: 174.15pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Flux 3&nbsp;: ResultatRechercheCercleSoins</span></p>
            </td>
            <td style="width: 116.9pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Requis</span></p>
            </td>
            <td style="width: 116.95pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Idem</span></p>
            </td>
        </tr>
    </tbody>
</table>

Il est également possible de préciser, si besoin, des choix d’options de mise en œuvre des flux pour chaque acteur.

Par exemple, dans le contexte du volet « Cercle de soins », il est possible de préciser les options suivantes pour l’acteur Createur :

<table style="width:481.7pt;border-collapse:collapse;border:none;">
    <tbody>
        <tr>
            <td style="width: 115.65pt;border: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:center;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'>Acteur</p>
            </td>
            <td style="width: 366.05pt;border-top: 1pt solid windowtext;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-image: initial;border-left: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:center;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'>Option</p>
            </td>
        </tr>
        <tr>
            <td rowspan="6" style="width: 115.65pt;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Createur</span></p>
            </td>
            <td style="width: 366.05pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Cr&eacute;ation simultan&eacute;e du cercle de soins et de ses acteurs</span></p>
            </td>
        </tr>
        <tr>
            <td style="width: 366.05pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;height: 9pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Cr&eacute;ation du cercle de soins&nbsp;</span></p>
            </td>
        </tr>
        <tr>
            <td style="width: 366.05pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;height: 9pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Cr&eacute;ation des acteurs du cercle de soins (Note1)</span></p>
            </td>
        </tr>
        <tr>
            <td style="width: 366.05pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;height: 9pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Mise &agrave; jour simultan&eacute;e du cercle de soins et de ses acteurs</span></p>
            </td>
        </tr>
        <tr>
            <td style="width: 366.05pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;height: 9pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Mise &agrave; jour du cercle de soins&nbsp;</span></p>
            </td>
        </tr>
        <tr>
            <td style="width: 366.05pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;height: 9pt;vertical-align: top;">
                <p style='margin-top:3.0pt;margin-right:0cm;margin-bottom:3.0pt;margin-left:0cm;text-align:left;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;color:#4F81BD;font-weight:bold;'><span style="color:windowtext;font-weight:normal;">Mise &agrave; jour des acteurs du cercle de soins (Note1)</span></p>
            </td>
        </tr>
    </tbody>
</table>

(Note 1) : dans le cas où l’acteur supporte l’option Création des acteurs du cercle de soins, il doit également supporter obligatoirement l’option Création du cercle de soins.

Le même principe s’applique aux autres acteurs identifiés pour lesquels une ou plusieurs options ont été identifiées.

Enfin, il est possible également de préciser les groupements entre les acteurs identifiés par l’étude fonctionnelle et d’autres acteurs définis en dehors du volet en construction mais déjà décrits dans d’autres volets du CI-SIS ou dans d’autres spécifications de portée internationale.

Les étapes 1, 2, 3 et 4 font l’objet d’une harmonisation du contenu d’une spécification d’interopérabilité, définissant ainsi un plan type des spécifications d’interopérabilité qui s’appliqué également aux guides d’implémentation (y compris les IG FHIR).

Tout volet du CI-SIS, quel que soit son format doit contenir les sections suivantes (sous forme de parties dans le cas d’une spécification PDF ou d’onglets dans le cas d’un guide d’implémentation) :

<div>
    <ul>
        <li>Généralités ;</li>
        <li>Volume 1 (Etude fonctionnelle des échanges) ;</li>
        <ul>
            <li>Introduction</li>
            <li>Acteurs et transactions</li>
            <li>Options implémentées par les acteurs</li>
            <li>Groupement d’acteurs</li>
            <li>Considérations de sécurité</li>
        </ul>
        <li>Volume 2 (Description technique des transactions) ;</li>
        <ul>
            <li>Une section par transaction</li>
        </ul>
        <li>Volume 3 (annexes), par exemple :</li>
        <ul>
            <li>Liste de codes erreurs ;</li>
            <li>Modélisation des flux et correspondance avec le MOS ;</li>
            <li>Etc</li>
        </ul>
        <li>Artefacts</li>
        <ul>
            <li>Ressources de conformité dans le cas d’un IG FHIR ;</li>
            <li>Exemples (par ex, messages v2 ou documentcda).</li>
        </ul>
        <li>Plan de tests</li>
        <li>Téléchargements</li>
    </ul>
</div>

#### Etape 4 : identification des concepts véhiculés dans les flux d’information

Les flux d’informations échangés par les acteurs dans les processus métier collaboratifs ont été identifiés et décrits à l’étape 3. Le but de l’étape 4 est d’identifier les concepts métier véhiculés dans les flux et de les associer aux concepts du modèle des objets de santé (MOS). Le MOS est un ensemble de concepts, décrits de manière homogène et neutre vis-à-vis des technologies. Il offre une description commune et mutualisée des informations traitées dans les systèmes d’information et les échanges.

Cette étape est découpée en deux sous-étapes :

<div>
    <ul>
        <li>Sous-étape 4.1 : Identification des concepts métier véhiculés dans les flux ;</li>
        <li>Sous-étape 4.2 : Correspondance entre les concepts métier identifiés et les concepts du MOS.</li>
    </ul>
</div>
##### Identification des concepts

L’identification des concepts métier véhiculés dans chacun des flux est un exercice d’inventaire qui nécessite une collecte des informations auprès du métier, flux par flux.
D’un point de vue pratique dans cette étape, les concepts métier sont tous identifiés à des classes UML, quel que soit leur devenir, classe ou attribut, dans les étapes suivantes de l’étude. Ils respectent les conventions de nommage des classes du MOS, définies à l’étape 5.
Le résultat de cette approche est consigné dans des tableaux qui listent, pour chaque flux, les concepts métier véhiculés et leur définition (voir Figure 15).

Exemple :

| Nom | Description | Flux |
| CercleSoins | Le Cercle de Soins est l'agrégation de membres qui participent à la prise en charge et aux actions de coordination du parcours de santé d’une personne. Le Cercle de Soins possède un identifiant, une date de début, une date de fin et une date de mise à jour. | Flux 1 - CreationCercleSoins, Flux 2 - RechercheCercleSoins, Flux 3 - ResultatRechercheCercleSoins, Flux 4 - MiseJourCercleSoins |
| MembreCercleSoins | Le membre du cercle de soins peut être : un professionnel de santé : médecin traitant, pharmacien, infirmière libérale, etc., une entité intervenant dans la prise en charge de la personne, le responsable légal de la personne prise en charge, la personne de confiance de la personne prise en charge, l'aidant de la personne prise en charge. Le cercle de soins fournit l'identité du membre ainsi qu'un moyen de communication avec lui. Chaque membre du cercle de soins dispose d’une date de début et une date de fin de sa participation à ce cercle. | Flux 1 - CreationCercleSoins, Flux 2 - RechercheCercleSoins, Flux 3 - ResultatRechercheCercleSoins, Flux 4 - MiseJourCercleSoins |
| PersonnePriseCharge | Personne physique bénéficiaire de soins, d'examens, d'actes de prévention ou de services. | Flux 1 - CreationCercleSoins, Flux 2 - RechercheCercleSoins, Flux 3 - ResultatRechercheCercleSoins, Flux 4 - MiseJourCercleSoins |
| Professionnel | Un Professionnel est une personne qui participe à la prise en charge d’une personne. Le professionnel peut être du domaine sanitaire, médico-administratif, médico-social et social. | Flux 1 - CreationCercleSoins, Flux 2 - RechercheCercleSoins, Flux 3 - ResultatRechercheCercleSoins, Flux 4 - MiseJourCercleSoins |

Tableau : Extrait des concepts métier présents dans l’étude « Cercle de soins »

##### Identification des classes génériques

Une des principales difficultés lors de la modélisation des informations d'un échange est de ne pas réinventer à chaque fois une modélisation différente pour ces mêmes informations. Il faut, par exemple, veiller à représenter les informations relatives à "une personne physique" de la même façon dans chaque projet.
Le but de cette partie est d'identifier, pour chaque concept métier, les composants du MOS les plus pertinents à réutiliser lors de la modélisation du flux, à partir des tableaux des concepts métier définis lors de la sous-étape 4.1.

**Démarche**

Le MOS contient un ensemble de concepts. Cet ensemble a vocation à évoluer avec l’ajout de nouveaux concepts qui doivent être suffisamment génériques pour être utilisés dans plusieurs projets. Ainsi, lors de la démarche de mise à correspondance avec les concepts du MOS, il peut s’avérer que des concepts métier identifiés à l’étape 4 ne se trouvent pas dans le MOS. Ces concepts peuvent faire l’objet d’une étude menée pour leur intégration dans le MOS dans le cadre des mises à jour mensuelles du modèle.
Il n’y a pas de règle pour la mise en correspondance entre un concept métier identifié à l’étape 4 et les concepts génériques du MOS. L'exercice peut s'avérer difficile car cette correspondance nécessite à la fois une compétence métier, une expérience en modélisation et une connaissance des classes et attributs du MOS.

Dans le MOS, le concept métier peut correspondre à :

<div>
    <ul>
        <li>Une ou plusieurs classes du MOS à restreindre ou à étendre, la correspondance peut être de type :</li>
        <ul>
            <li>Equivalence : la classe du MOS et le concept métier ont le même sens ;</li>
            <li>Restriction : la classe du MOS contient plus d'attributs et d'associations que ceux exigés fonctionnellement dans le projet ; il faut dès lors restreindre cette classe, c'est-à-dire sélectionner les attributs et associations nécessaires aux exigences métier ; les restrictions sont toujours possibles ;</li>
            <li>Extension : la classe du MOS ne contient pas tous les attributs nécessaires fonctionnellement ou n’existe pas ; il faut dès lors étendre cette classe ou créer une nouvelle classe ; il est préconisé d’éviter de "tordre" un composant générique pour en forcer l’utilisation ; en effet, cette opération entrainerait le risque de détourner la sémantique du concept et de passer à côté de la création d'un nouveau composant dans le MOS.</li>
        </ul>
        <li>Un ou plusieurs attributs du MOS, la correspondance peut être de type :</li>
        <ul>
            <li>Equivalence : l’attribut MOS et le concept métier ont le même sens ;</li>
            <li>Extension : il n’existe pas d’attribut MOS correspondant, grâce à la définition du concept métier, on identifie la classe à laquelle le concept appartient ;</li>
            <li>Restriction : ce type d’équivalence n’est pas possible pour les attributs</li>
        </ul>
    </ul>
</div>

Par la suite, les extensions sont instruites pour déterminer si elles sont :

<div>
    <ul>
        <li>Suffisamment génériques pour être utilisées par d'autres projets et donc être intégrées au MOS dans le cadre des mises à jour mensuelles ;</li>
        <li>Spécifiques au projet.</li>
    </ul>
</div>

**Construction du tableau de mise en correspondance**

La démarche s’applique pour chacun des concepts métier identifiés, que ce concept devienne une classe ou un ou plusieurs attributs. Suite à cette analyse, il est possible de construire un tableau de correspondance entre le concept métier et le concept MOS associé (voir Figure 18).

Ce tableau contient les éléments suivants :

<div>
    <ul>
        <li>Concept métier identifié à l’étape 4.1;</li>
        <li>Concept(s) MOS correspondant avec la relation liant le concept métier au concept MOS. La relation peut être de trois types : " extension ", " restriction " ou " équivalence " ; si la relation entre les concepts est une extension, les attributs supplémentaires déjà connus doivent être consignés.</li>
    </ul>
</div>

Remarque : Tous les concepts métier doivent être listés dans le tableau, y compris ceux qui n’ont pas de correspondance dans le MOS.

| Nom                 | Extension | Restriction | Equivalence | Concept MOS |
| ---                 | --- | --- | --- | --- |
| CercleSoins         | X |  |  |  |
| MembreCercleSoins   | X |  |  |  |
| PersonnePriseCharge |  |  | X |  |
| Professionnel       |  | X |  |  |
| Aidant              |  | X |  |  |
| ResponsableLegal    |  | X |  |  |
| PersonneConfiance   |  | X |  |  |
| Role                |  |  | X |  |
| Entite              |  | X |  |  |
| UniteSoin           |  | X |  |  |

<!-- Commentaire IG : Je ne suis pas convaincue de l’utilité de ce type d’analyse en particulier dans les conditions dans lesquels nous travaillons où les délais sont souvent très serrés. -->

Tableau : Correspondance « concepts métier/MOS » pour les flux du volet « Cercle de soins »

#### Etape 5 : modélisation des flux d’information

Les concepts véhiculés par les flux d’informations ont été identifiés à l’étape 4. Le but de cette étape est d'élaborer le modèle sous tendu par chaque flux à partir des concepts métier et des classes et attributs existants dans le MOS.
Le modèle sous tendu par chaque flux d’information est modélisé par un diagramme de classes UML. Cette représentation formalisée du flux doit prendre en compte les deux exigences suivantes :

<div>
    <ul>
        <li>Réutilisation des classes génériques, mutualisées et mises à disposition dans le MOS ; </li>
        <li>Définition des associations, y compris leur cardinalité, entre les classes en respectant les besoins.</li>
    </ul>
</div>

##### Modélisation des flux

Le but de cette étape est d’établir la modélisation de chaque flux en utilisant les concepts identifiés à l'étape précédente. Cette modélisation est le résultat de cinq opérations.
Remarque : Le cas particulier des flux de recherche est traité à la suite de la modélisation des flux afin de lier les critères de recherche aux classes et attributs identifiés.

**Première opération : choix de la racine**

Le modèle du flux a toujours comme point de départ une classe unique, appelée la classe racine. Elle reprend le nom du flux identifié à l'étape 3. Elle n'a pas d'attribut.
Les noms des éléments du modèle respectent les conventions de nommage du MOS, à savoir :

<div>
    <ul>
        <li>Les articles, propositions et les accents sont retirés ;</li>
        <li>Les noms des classes, attributs, types de données sont, autant que possible, au singulier ;</li>
        <li>Les noms des classes et des types de données sont écrits en « UpperCamelCase » ;</li>
        <li>Les noms des attributs sont écrits en « LowerCamelCase ».</li>
    </ul>
</div>

Dans l'exemple, la classe racine s'appelle " CercleSoins ".

**Deuxième opération : définition des classes**

Pour chaque flux de l’étape 4, il faut identifier les concepts métier qui deviennent des classes.

<div>
    <ul>
        <li>Pour tout concept ayant une équivalence avec une classe du MOS dans l’étape 4.2, il faut reprendre la classe du MOS ; </li>
        <li>Pour tout concept n’ayant pas d’équivalence avec une classe du MOS dans l’étape 4.2, il faut créer la classe correspondant à ce concept métier.</li>
    </ul>
</div>

Il faut aussi étudier les associations entre les classes ainsi que les cardinalités pour les adapter au contexte du flux.

Si le besoin métier est de créer une nouvelle classe ou d'enrichir une classe existante, il faut alors rédiger une Demande de Modification (DM) à soumettre au gestionnaire du MOS.

**Troisième opération : définition des attributs**

En ce qui concerne les attributs, les classes issues du MOS sont en général plus riches que ce qui est exigé fonctionnellement dans les flux. Il faut dès lors prendre ces classes et les restreindre, c'est-à-dire sélectionner uniquement les attributs répondant aux exigences métier. Cette opération s'applique à toutes les classes reprises, y compris les classes communes (Adresse, Telecommunication, Contact, Lieu, etc.). Il est conseillé de ne pas modifier les noms des attributs du MOS.

Les classes du MOS peuvent aussi être étendues par la création de nouveaux attributs. Il faut également créer les attributs des nouvelles classes qui n’existent pas dans le MOS.

Si le besoin métier est de créer un nouvel attribut ou d'enrichir un attribut existant, il faut alors rédiger une Demande de Modification (DM) à soumettre au gestionnaire du MOS.

Cas particulier des **métadonnées** : si d’un point du vue métier, il est important de véhiculer les métadonnées d’une ou plusieurs classes, alors il faut analyser quelles métadonnées sont nécessaires et les inclure dans les classes identifiées. Il n’est pas nécessaire d’ajouter l’attribut métadonnée pour représenter les métadonnées techniques véhiculées dans chaque flux.

**Quatrième opération : types de données et nomenclatures associées**

Qu'ils soient candidats ou non à une mise à jour du MOS, les attributs créés lors de l’étude doivent reprendre un des types de données définis dans le MOS.

Les attributs d'une classe dont le type est un "Code" doivent avoir une nomenclature (ou liste de codes) qui leur est associée. Dans le cadre d’une application, il faut faire référence à des jeux de valeurs plutôt qu’à des terminologies de référence. Si le besoin métier est de créer une nouvelle nomenclature ou d’enrichir une nomenclature existante, il faut alors rédiger une Demande de Modification (DM) à soumettre au gestionnaire des nomenclatures des objets de santé (NOS). Lorsque les nomenclatures sont seulement identifiées à ce stade des spécifications fonctionnelles des échanges, il est conseillé d’ajouter dans la description des attributs auxquels elles sont associées, un paragraphe les décrivant et listant, si possible, les premières valeurs proposées. Dans les livrables de l’étude, les nomenclatures associées aux échanges sont annexées au document des spécifications fonctionnelles des échanges.

**Cinquième opération : règles de gestion**

Les règles de gestion métier définies par les partenaires de l'échange précisent que certaines classes ou certains attributs sont liés entre eux par des contraintes. Par exemple, dans un échange, l'attribut A est exclusif de l'attribut B ; en d'autres termes, cela veut dire que si A est échangé alors B n'est pas échangé.

Ces règles de gestion, rédigées en texte libre, sont spécifiées sur le diagramme de classe du flux sous la forme de contraintes UML. Ces contraintes s'appliquent sur une ou plusieurs classes et/ou sur un ou plusieurs attributs. Elles doivent rester simples et internes à l'échange. Ce sont des règles métier, elles ne doivent pas servir à exprimer des choix d'implémentation.

Elles sont exprimées sous la forme d'un nom suivi d'un numéro d'ordre (par exemple, Règle01, Règle02, etc.) et d'une description.

Dans la documentation, elles figurent à la fois sur le diagramme de classe et dans la partie textuelle, sous la forme d'un tableau. Ce tableau est présenté à la suite de la description de la classe sur laquelle ces règles portent.

**Cas particulier des flux de recherche**

Le diagramme de classes n’est pas approprié pour formaliser le modèle sous tendu par un flux de recherche. Ce diagramme est remplacé par un tableau qui contient pour chaque critère de recherche, sa description ainsi que son caractère obligatoire.

**Emettre des demandes de modification (DM)**

Comme mentionné précédemment, des demandes de modifications sont à émettre pour faire évoluer le MOS ou les NOS. Ces demandes seront étudiées par l'équipe en charge de la gestion de ces référentiels socles.

**Illustration des flux modélisés – Diagramme d’objets**

Le résultat est constitué par un diagramme de classes par flux, appelé modèle du flux, accompagné de la documentation des classes, attributs et règles.

Le modèle du flux est neutre de toute syntaxe ; il est la base des évolutions fonctionnelles. Il est ensuite transformé, automatiquement ou non, dans la syntaxe choisie par le projet au cours de l’[étude des Normes et standards](./choix-standard.html). Cette syntaxe peut faire partie des standards du cadre d'interopérabilité des systèmes d'information de santé (CI-SIS).

Le diagramme contient les classes sélectionnées du MOS et restreintes ainsi que de nouvelles classes propres à la description fonctionnelle. Chaque attribut est défini par un type de donnée et des cardinalités, les attributs de type "Code" sont associés à leur nomenclature ; cette dernière information figure dans la documentation du diagramme de classes.

L'exemple du diagramme de classe "Flux 1 - CreationCercleSoins" illustre la construction du modèle d’un flux. Pour plus de lisibilité dans cet exemple, les classes issues du MOS ont été identifiées à l’aide du symbole *. Il est complété par le diagramme d'objet correspondant en Figure 19.

Le diagramme de classes n’est pas approprié pour formaliser un flux de recherche. Ce diagramme est remplacé par un tableau qui contient pour chaque critère de recherche, sa description ainsi que son caractère obligatoire (voir Figure ci-dessous).

<div class="figure" style='text-align: center;'>
    <img src="flux1-creation-cds.png" alt="CP" title="Flux 1 - création CDS" style="width:80%;">
    <figcaption><b>Flux 1 - création CDS</b></figcaption>
</div>

**Classe « CercleSoins »**

Le Cercle de Soins comprend toutes les personnes (Professionnel ou Personne Tierce) et Entités qui participent à la prise en charge et aux actions de coordination du parcours de santé d’un Usager. Le Cercle de Soins possède un statut (actif, inactif…), une date de début, une date de fin et une date de mise à jour.

| Nom | Description |
| --- | --- |
| idCercleSoins : [1..1] Identifiant | Identifiant du cercle de soins. |
| dateCreation : [1..1] Date | Date de création du cercle de soin. |
| dateMAJ : [1..*] Date | Date de mise à jour du cercle de soin.|
| dateFin : [1..1] string | Date de fin d'existence du cercle de soins. |
| statut : [1..1] string | Statut du cercle de soin (actif, inactif, ...).|
| metadonnee : [1..1] Metadonnee | Informations relatives à la gestion des classes et des données. |

**Classe « PersonnePriseCharge »**

Personne physique bénéficiaire de soins, d'examens, d'actes de prévention ou de services. Selon le contexte, la personne prise en charge peut être un patient ou un usager.

<table style="border-collapse:collapse;border:none;">
    <tbody>
        <tr>
            <td style="width: 226.55pt;border: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;text-align:center;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:#4F81BD;">Nom</span></strong></span></p>
            </td>
            <td style="width: 226.55pt;border-top: 1pt solid windowtext;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-image: initial;border-left: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:0cm;margin-left:0cm;text-align:center;line-height:normal;font-size:13px;font-family:"Calibri",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:#4F81BD;">Description</span></strong></span></p>
            </td>
        </tr>
        <tr>
            <td style="width: 226.55pt;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin:0cm;font-size:16px;font-family:"Arial",sans-serif;color:black;text-align:justify;'><span style='font-size:13px;font-family:"Calibri",sans-serif;'>idPersonnePriseCharge : [1..1] Identifiant&nbsp;</span></p>
            </td>
            <td style="width: 226.55pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin:0cm;font-size:16px;font-family:"Arial",sans-serif;color:black;text-align:justify;'><span style='font-size:13px;font-family:"Calibri",sans-serif;'>Identifiant(s) de la personne prise en charge (identifiants de sant&eacute;, identifiants locaux, etc.).&nbsp;</span></p>
            </td>
        </tr>
        <tr>
            <td style="width: 226.55pt;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin:0cm;font-size:16px;font-family:"Arial",sans-serif;color:black;text-align:justify;'><span style='font-size:13px;font-family:"Calibri",sans-serif;'>adresseCorrespondance : [1..1] Adresse&nbsp;</span></p>
            </td>
            <td style="width: 226.55pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin:0cm;font-size:16px;font-family:"Arial",sans-serif;color:black;text-align:justify;'><span style='font-size:13px;font-family:"Calibri",sans-serif;'>Adresse(s) de correspondance de la personne prise en charge.&nbsp;</span></p>
            </td>
        </tr>
        <tr>
            <td style="width: 226.55pt;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin:0cm;font-size:16px;font-family:"Arial",sans-serif;color:black;text-align:justify;'><span style='font-size:13px;font-family:"Calibri",sans-serif;'>telecommunication : [1..*] Telecommunication&nbsp;</span></p>
            </td>
            <td style="width: 226.55pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin:0cm;font-size:16px;font-family:"Arial",sans-serif;color:black;text-align:justify;'><span style='font-size:13px;font-family:"Calibri",sans-serif;'>Adresse(s) de t&eacute;l&eacute;communication de la personne prise en charge (num&eacute;ro de t&eacute;l&eacute;phone, adresse email, URL, etc.).&nbsp;</span></p>
            </td>
        </tr>
        <tr>
            <td style="width: 226.55pt;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin:0cm;font-size:16px;font-family:"Arial",sans-serif;color:black;text-align:justify;'><span style='font-size:13px;font-family:"Calibri",sans-serif;'>metadonnee : [1..1] Metadonnee&nbsp;</span></p>
            </td>
            <td style="width: 226.55pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin:0cm;font-size:16px;font-family:"Arial",sans-serif;color:black;text-align:justify;'><span style='font-size:13px;font-family:"Calibri",sans-serif;'>Informations relatives &agrave; la gestion des classes et des donn&eacute;es.&nbsp;</span></p>
            </td>
        </tr>
    </tbody>
</table>

Tableaut extrait du modèle de flux « flux 1 – CreationCercleSoin »

**Flux de recherche : Flux 2 – RechercheCercleSoins**

| Nom | Description | Obligatoire |
| --- | --- | --- |
| CercleSoins/idCercleSoins | Identifiant du cercle de soins. | Non |
| CercleSoins/dateCreation | Date de création du cercle de soin | Non |
| CercleSoins/dateMAJ | Date de mise à jour du cercle de soin. | Non |
| CercleSoins/dateFin | Date de fin d'existence du cercle de soins. | Non |
| CercleSoins/statut | Statut du cercle de soin (actif, inactif, ...) | Non |
| MembreCercleSoin/idMembreCercleSoin | Identifiant du membre du cercle de soins. | Non |

Tableau des critères de recherche du « Flux de recherche : Flux 2 – RechercheCercleSoins »

**Diagramme d’objet du flux 1 – CreationCercleSoins**

<div class="figure" style='text-align: center;'>
    <img src="diagramme-cds.png" alt="CP" title="Diagramme d’objet du flux 1 – CreationCercleSoins**" style="width:80%;">
    <figcaption><b>Diagramme d’objet du flux 1 – CreationCercleSoins**</b></figcaption>
</div>

### CAS SPECIFIQUE DES MISES A JOUR DES SPECIFICATIONS

La mise à jour des spécifications est déclenchée lorsqu’un événement nouveau impacte une ou plusieurs étapes de ces spécifications.

Par exemple, une nouvelle contrainte réglementaire, l’ajout d’un cas d’usage, etc.

Dès qu’une étape est modifiée, il faut réaliser une étude d’impacts sur toutes les étapes suivantes. Un arbitrage de ces impacts doit être réalisé afin de savoir si des évolutions sont à considérer ou pas sur les spécifications existantes.

#### Pour toutes mises à jour

Avant toute modification, il convient de s’assurer qu’il n’y a pas de nouvelles contraintes réglementaires et organisationnelles ou que celles qui sont spécifiées sont toujours valides.

Quel que soit le type de mise à jour à réaliser, les actions suivantes sont à mener :

<div>
    <ul>
        <li>Etape 1 : Mettre à jour le diagramme de paquetage en fonction des autres volets créés ou mis à jour depuis la dernière version de la spécification. </li>
        <li>Etape 4 : Vérifier la cohérence des équivalences avec le MOS dans sa dernière version. </li>
        <li>Etape 5 : Mettre à jour les définitions des éléments du MOS qui sont réutilisés. </li>
    </ul>
</div>

Les modifications apportées sur les spécifications fonctionnelles peuvent impacter l’étude des normes et standards ainsi que les spécifications techniques. Bien souvent la mise à jour des spécifications ne se limite pas au fonctionnel.

#### Ajout d’un processus

Avant d’ajouter un processus dans une spécification, il est important de s’assurer que le besoin n’est pas couvert par ailleurs et que le processus s’intègre au cas d’usage couvert par la spécification.

L’ajout d’un processus dans une spécification doit entrainer la revue des autres processus. Certains processus peuvent être impactés par cet ajout. Dans ce cas, se référer à la partie 0.

L’ajout d’un processus va se traduire par les actions suivantes :

<div>
    <ul>
        <li>Etape 1 : Ajout du processus dans le diagramme de paquetage. </li>
        <li>Etape 2 : Création du cas d’utilisation du processus pouvant entrainer l’ajout ou la modification d’acteurs « rôle » : </li>
            <ul>
                <li>En cas d’ajout d’un acteur, donner une définition de l’acteur ainsi que des exemples d’acteurs « système » et « personne » ; </li>
                <li>En cas de modification d’un acteur, il faut s’assurer que la modification est possible et cohérente avec l’emploi de cet acteur dans les autres processus. </li>
            </ul>
        <li>Etape 3 : Création du diagramme d’activité du processus. </li>
        <li>Etape 4 : Identification des informations véhiculées dans les flux à l’étape 3 : </li>
            <ul>
                <li>Si les informations identifiées ne correspondent pas aux informations déjà existant dans les autres flux, ajouter ces informations à la suite et les mettre en équivalence avec le MOS si possible ; </li>
                <li>Si les informations identifiées correspondent aux informations existant dans les autres flux, vérifier la cohérence des définitions et la mise en équivalence avec le MOS. </li>
            </ul>
        <li>Etape 5 : Réalisation si nécessaire du diagramme de classe. </li>
    </ul>
</div>

#### Modification d’un processus

La modification d’un processus dans une spécification doit entrainer la revue des autres processus. Certains processus peuvent être impactés par cette modification.

La modification d’un processus va se traduire par les actions suivantes :

<div>
    <ul>
        <li>Etape 1 : Modification du processus dans le diagramme de paquetage. </li>
        <li>Etape 2 : Modification du cas d’utilisation du processus pouvant entrainer l’ajout, la modification ou la suppression d’acteurs « rôle » : </li>
            <ul>
                <li>En cas de modification d’un acteur, il faut s’assurer que la modification est possible et cohérente avec l’emploi de cet acteur dans les autres processus ; </li>
                <li>Si l’acteur intervient uniquement dans ce processus, alors l’acteur sera supprimé s’il n’est plus nécessaire.  </li>
            </ul>
        <li>Etape 3 : Modification du diagramme d’activité du processus en fonction des évolutions réalisées dans les étapes précédentes et des besoins exprimés. La modification peut se traduire par :  </li>
            <ul>
                <li>L’ajout, la modification, la suppression d’action(s) ; </li>
                <li>L’ajout, la modification, la suppression de flux. </li>
            </ul>
        <li>Etape 4 : Une analyse doit être conduite sur les flux afin d’identifier parmi les informations véhiculées celles qui sont nouvelles, à supprimer ou à modifier. Suivant cette analyse, le tableau des concepts métier et des équivalences avec le MOS doit être mis à jour. </li>
        <li>Etape 5 : Les modélisations de l’étape sont mises à jour en fonction des modifications des étapes précédentes de la façon suivante : </li>
            <ul>
                <li>Si un flux est ajouté, alors il doit être modélisé ; </li>
                <li>Si un flux est supprimé, alors sa modélisation l’est également ; </li>
                <li>Si un flux est toujours existant, alors les concepts utilisés et la modélisation sont actualisés. </li>
            </ul>
    </ul>
</div>

#### Suppression d’un processus

La suppression d’un processus dans une spécification doit entrainer la revue des autres processus. Certains processus peuvent être impactés par cette suppression. Dans ce cas, se référer à la partie 0.

La suppression d’un processus va obligatoirement se traduire par les actions suivantes :

<div>
    <ul>
        <li>Etape 1 : Suppression du processus dans le diagramme de paquetage. </li>
        <li>Etape 2 : Suppression du cas d’utilisation du processus. La suppression d’un processus à l’étape 2, peut entrainer la modification ou la suppression d’acteurs « rôle ». La définition de chaque acteur intervenant dans le processus doit être revue pour être mise à jour si nécessaire. Si l’acteur intervient uniquement dans ce processus, alors l’acteur sera supprimé. </li>
        <li>Etape 3 : Suppression du diagramme d’activité du processus. </li>
        <li>Etape 4 : Suppression des informations métier propres au processus et mise à jour du tableau de correspondance avec le MOS. </li>
        <li>Etape 5 : Suppression des modélisations des flux du processus. </li>
    </ul>
</div>
