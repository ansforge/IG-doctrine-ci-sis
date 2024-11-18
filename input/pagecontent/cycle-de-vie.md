Le niveau de qualité et la maturité des volets du CI-SIS sont des informations importantes pour inciter les éditeurs de solution à engager des développements sans craindre de futures évolutions majeures dans un avenir proche.

Le statut de maturité est une information indicative. Il est toujours préférable de se baser sur des spécifications standards, même si celles-ci sont peu matures. Les standards étant développés par une communauté d’experts, il est plus facile et plus sécurisant de faire évoluer des spécifications en parallèle des évolutions d’un standard plutôt de maintenir un standard propriétaire.

### Le cycle de vie et les statuts associés

Le cycle de vie défini pour les des volets du CI-SIS s'appuie sur les pratiques internationales d'[IHE](https://wiki.ihe.net/index.php/Process) et de [HL7](https://confluence.hl7.org/display/FHIR/FHIR+Maturity+Model) adaptées aux besoins nationaux.

Quatre statuts sont définis pour les spécifications d'interopérabilité de l'ANS : « draft » ou « version-de-travail », « public-comment » ou « en-concertation », « trial-implementation » ou « pour-implementation », et « final-text » ou « final ». Ces statuts sont repris des [pratiques d'IHE](https://wiki.ihe.net/index.php/Comments#Phases_of_Development), avec le libellé anglais et sa traduction française. Pour des raisons d'uniformisation, les termes anglais seront utilisés dans la suite de ce document.

Les statuts « trial-implementation » et « final-text » reflètent la maturité des spécifications dans l'ordre indiqué.

#### Le statut « draft » ou « version-de-travail »

Le statut « draft » correspond à une spécification **en cours de cours de création ou de modification**.
Ce statut est particulièrement important pour les spécifications développées sur GitHub car tous les travaux sont publics et donc accessibles à tout moment : de la création du répertoire GitHub à la publication. C'est le statut d'une spécification publiée en mode intégration continue (ci-build).

#### Le statut « public-comment » ou « en-concertation »

La spécification est publiée au statut **en concertation** lors de ses phases de consultations publiques. La spécification en mode « public comment » risque d'évoluer suite aux commentaires des concertations et n'est pas faite pour être implémentée : elle est en attente de la validation de l'écosystème pour publication.
Une spécification en « final-text » ou en « trial-implementation » peut repasser en « public-comment » en cas d'évolution majeure (des cas d'usage, du standard sous-jacent ...)..

#### Le statut « trial-implementation » ou « pour-implémentation »

La spécification est passée par une ou plusieurs phases de concertation et est **prête pour être mise en oeuvre** en situation réelle.
Ce statut est un reflet de la maturité : selon l'auteur, la spécification est prète pour une première mise en situation réelle.

#### Le statut « final-text » ou « final »

Les auteurs de la spécification ont estimé qu'elle avait atteint le **stade de maturité le plus élevé**.
Ce stade est atteint lorsque la spécification a déjà été mise en œuvre dans au moins un projet national ou testée lors d'un projectathon. La spécification a pu avoir des retours post-concertation, post-projectathon ou post-mise en oeuvre et a été corrigée. Ce statut indique également que les critères de maturité et de qualité définis ci-dessous ont été respectés.
Ce statut n'empèche pas de repasser au statut « trial-implementation », qui peut arriver dans le cas de changement majeur tel que la migration d'un nouveau standard, ou l'expression de nouveaux besoins.

#### Les autres statuts

Une spécification peut également être « deprecated » ou « dépréciée » si celle-ci a été remplacée par une autre spécification ou « withdrawn » ou « retirée » après avoir été dépréciée depuis un moment.

#### Le cycle de vie d'une spécification

Durant la vie d'une spécification, celle-ci passe par différents statuts exprimés dans le schéma ci-dessus.


<div class="figure" style="width:100%;">
    <img style="height: auto; width: 100%;" src="cycle-de-vie.png" alt="CI-SIS" title="Logo du CI-SIS">
</div>

A l'issue d'une concertation, une spécification peut passer au statut « final-text » ou « trial-implementation ». Ce choix dépend du respect de critère de qualité, de maturité, et de la décision de l'auteur.
Pour passer au statut « final-text », la spécification doit :

<div>
    <ol>
        <li> Avoir été publiée au moins une fois en « trial-implementation » </li>
        <li> Avoir été mise en oeuvre au niveau national ou testée lors de projectathons avec des retours mineurs </li>
        <li> Respecter les critères de qualité et de maturité </li>
        <li> Avoir l'aval de l'auteur qui juge la spécification suffisamment mature et qualitative pour passer à ce statut </li>
    </ol>
</div>

Notes :

<div>
    <ul>
        <li> Une spécification au statut « final-text » peut repasser au statut « trial-implementation », par exemple en cas de changement majeur comme une refactorisation de la spécification (passage au format guide d'implémentation FHIR, à une version supérieure du standard sous-jacent, à un changement de standard, ...). Cela signifie que l'ancienne version en « final-text » ne doit plus être utilisée pour diverses raisons, comme une situation internationale nécessitant de grandes évolutions. Dans ce cas, une note explicative sera associée à la publication de la nouvelle spécification. </li>
        <li> Lorsqu'une nouvelle version d'une spécification est publiée, il est recommandé aux éditeurs de l'adopter dans les 1 à 2 ans suivant sa publication. </li>
        <li> Le statut du cycle de vie n'est pas associé à la version <a href="https://semver.org/lang/fr">semver</a> d'une spécification. Le numéro de version d'une spécification est systématiquement incrémenté à chaque release et est indépendant du statut du cycle de vie. Par exemple, si une faute d'orthographe est corrigée entraînant une incrémentation mineure du numéro de version, cela ne justifie pas un changement de statut. A chaque publiation, une étude pour évaluer un éventuel changement de statut du cycle de vie est effectuée en suivant le schéma ci-dessus. </li>
    </ul>
</div>

### Définition des critères de maturité

Une spécification avec la majorité des critères de maturité respectés indiquent sa clarté et sa facilité de mise en oeuvre. C'est le signe d'une plus grande pérennité de la spécification. Cependant, la pérennité d'une spécification ne peut jamais être garantie. Les spécifications jugées matures ont néanmoins une plus faible probabilité de subir des évolutions non rétrocompatibles.

Les critères de maturité identifiés :

<div>
    <ul>
        <li> Respect de l'ensemble des critères de qualité mentionnés ci-dessous </li>
        <li> (Etude en cours) Nombre d'implémentations obtenu par déclaration (par convergence ou par les DSI). Idéalement avec des retours d'expérience sur l'implémentation des spécifications </li>
        <li> Nombre de passage en projectathons, nombre de tests réalisés lors de projectathon, et nombre de partenaires </li>
        <li> Nombre d'issues et résolutions sur le repo GitHub </li>
        <li> Nombre de commentaires lors des phases de concertation </li>
    </ul>
</div>

### Définition des critères de qualité

Les critères de qualité représentent un ensemble de règles à respecter pour produire des spécifications de niveau de qualité conforme aux attentes nationales. Outre le respect à la doctrine (structuration d'une spécification d'interopérabilité, respect de la trajectoire nationale, du choix du standard, ...), les critères de qualité sont spécifiques à chaque standard.

Il n'est pas toujours possible de respecter strictement ces critères de qualité, car l'écosystème national ne peut pas contrôler les spécifications internationales, qui ne respectent pas forcément l'ensemble de ces critères. De plus, certaines spécifications historiques nécessitent du temps pour évoluer. L'objectif de ces critères est de les respecter et tendre le plus possible vers eux lors de la création ou mise à jour de spécifications.

Les critères de qualité **FHIR** sont :

<div>
    <ul>
        <li> Respect des règles de nommages indiquées ci-dessous </li>
        <li> Respect des <a href="https://build.fhir.org/ig/FHIR/ig-guidance/best-practice.html">bonnes pratiques internationales</a></li>
        <li> Respecter la stratégie nationale du choix des versions FHIR </li>
        <li> Chaque ressource de conformité doit avoir une description </li>
        <li> L'ensemble des ressources de conformité doit avoir une description précise de son usage </li>
        <li> Publication de l'IG sans erreurs (cf session Q/A de chaque IG) </li>
        <li> Ne pas recréer des artefacts qui existent déjà au niveau national et international. La création d'artefacts FHIR nécessite de l'expertise, de la veille et de faire une analyse précise de l'existant international. </li>
    </ul>
</div>

Ces règles de nommage ont été établies en s'inspirant des ressources [us-core](http://hl7.org/fhir/us/core).

| **Paramètre** | **Objet concerné** | **Règle** | **Exemple us-core** |
| ----- | ----- | ----- | ----- |
| id | Ressources de conformité | Utiliser le format kebab-case, ex : fr-core-patient.. Lors de la création d'un IG pour un projet en particulier, il est possible de préfixer l'ensemble des ressources de conformité par le trigramme du projet (ex : « ror-... ») | us-core-patient |
| title | Ressources de conformité | Similaire au nom, avec espaces. Ex : Fr Core Patient | US Core Patient Profile |
| name | Ressources de conformité |  Utiliser le format PascalCase sans espace. Ex : FrCorePatient | USCorePatientProfile |
| url | Ressources de conformité |  [base]/[ResourceType]/[id] (généré automatiquement par [SUSHI - SUSHI Unshortens Short Hand Inputs](https://fshschool.org/docs/sushi/)). A noter que [ResourceType] doit respecter le nom et la casse des ressources définies dans FHIR core (ex: StructureDefinition). | (http://hl7.org/fhir/us/core/StructureDefinition/us-core-patient) |
| code  | SearchParameter |  Toujours en minuscule, mots séparés par des tirets « - » | gender-identity |
| name | Slice | S'il s'agit d'une extension, utiliser son id, sinon utiliser le format lowerCamelCase | us-core-genderIdentity |
| id | Package | Utiliser des minuscules | hl7.fhir.us.core [lien vers la documentation](https://confluence.hl7.org/display/FHIR/NPM+Package+Specification) |

La documentation officielle se trouve sur le [confluence d'HL7](https://confluence.hl7.org/pages/viewpage.action?pageId=35718826#GuidetoDesigningResources-NamingRules&Guidelines)

Les critères de qualité **CDA** sont :

**A remplir par l'équipe CDA**

### Définition des métadonnées associées à une spécification d'interopérabilité

Les métadonnées correspondent aux données annexées aux spécifications. Elles sont utiles à des fins de recherche notamment.

| Nom | Description | Cardinalité | Exemples |
| --- | --- | --- | --- |
| identifiant | Identifiant ou URL identifiante d’accès à la spécification | 1..1 | (https://interop.esante.gouv.fr/ig/fhir/pdsm) |
| statut | Statut de la spécification selon les statuts définis par l’ANS. Les statuts peuvent être rédigés en anglais ou en français. | 1..1 | « draft », « public-comment », « trial-implementation », « final-text » |
| version | Version au format semver | 1..1 | 1.0.0 |
| code | Code qui définit la spécification | 1..1 | GAP, CR-BIO |
| titre | Titre de la spécification | 1..1 | Gestion d'Agendas Partagés |
| description | Description succinte du périmètre de la spécification | 1..1 | Ce guide d’implémentation a pour objet de permettre la gestion de ressources (personnes, lieux ou objets), la gestion des disponibilités de ces ressources, la consultation et la synchronisation d’agenda et la prise de rendez-vous. |
| date de dernière mise à jour | Date de dernière publication de la spécification | 1..1 | 2024-04-29 |
| Standards principaux | Standards syntaxiques et sémantiques, profils sur lesquels s'appuent la spécification | 0..* | CDA, FHIR, SNOMED CT |
| Contexte projet | Projet national ou référentiel notable où la spécification est utilisée | 0..1 | Mon Espace Santé |
| Catégorie | Catégorie métier de la spécification (équivalent des technical frameworks IHE) correspondant aux préfixes des spécifications CDA | 0..* | Liste des catégories : ANEST - Anesthésie, AVC - Accident vasculaire cérébral, BIO - Biologie, CANCER - Cancer, CARD - Cardiologie, IMG - Imagerie, OBP - Obstétrique et périnatalité, OPH - Ophtalmologie, TLM - Télémédecine, VAC - Vaccination (Demande d'ajout de nouvelles catégories : issues GitHub) |
| Type | Type de spécification | 0..* | Document médical, définition d'APIs, outillage, couche métier, couche service, couche transport, documentation, ... |
| Utilisations connues | Formulaire d’auto-déclaration de conformité pour les éditeurs (à définir) | 0..* | à définir |
| Porteur | Permet d’afficher le porteur de la spécification. Particulièrement important dans le cas de l’UP externe | 1..1 | ANS, Interop'Santé, EDESS, GCS E-santé Bretagne|
| Contact | Permet d’afficher le contact de la spécification. Particulièrement important dans le cas de l’UP externe | 1..1 | ci-sis@esante.gouv.fr |
