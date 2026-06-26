# Doctrine - Doctrine et gouvernance du cadre d'interopérabilité des systèmes d'informations en santé (CI-SIS) v0.1.1

* [**Table of Contents**](toc.md)
* **Doctrine**

## Doctrine

En tant qu’opérateur public au service de la santé numérique, l’ANS assure trois missions complémentaires :

* Créer les conditions de l’essor de la e-santé ;
* Conduire des projets d’envergure nationale ;
* Déployer les usages en soutenant l’innovation.

La création des conditions de l’essor de la e-santé, objet de la première mission de l’ANS, repose sur la définition d’un cadre dans lequel les services de e-santé peuvent se développer librement avec la capacité d’interagir aisément, de manière sécurisée avec l’ensemble des systèmes d’information du secteur et de manière éthique.

Du point de vue de la sécurité, ce cadre repose sur la mise en œuvre de règles et de bonnes pratiques identifiées dans la [Politique Générale de Sécurité des Systèmes d’Information de Santé (PGSSI-S)](https://esante.gouv.fr/produits-services/pgssi-s) et sur l’agrément des hébergeurs de données de santé.

Du point de vue de l’éthique, ce cadre repose sur la mise en œuvre de principes éthiques et humanistes identifiés dans le [Cadre de l’éthique du numérique en santé (CENS)](https://esante.gouv.fr/produits-services/referentiel-ethique).

En ce qui concerne l’interopérabilité, il repose sur l’identification et la compréhension partagée des concepts « métier » (ou objets) correspondant aux informations manipulées par les systèmes d’information de santé (ex. acteurs de santé, qu’ils soient une personne physique ou personne morale, patients, offre de soins…). Ces concepts sont catalogués dans le [Modèle des Objets de Santé (MOS)](https://mos.esante.gouv.fr/0.html). Utile pour la conception des systèmes d’information, l’utilisation des objets de santé pour la modélisation des échanges entre systèmes d’information est également une étape préalable à leur spécification dans une logique d’urbanisation sectorielle. Le Cadre d’Interopérabilité des Systèmes d’Information de Santé (CI-SIS) traduit cette modélisation en spécifications d’interopérabilité sémantiques, syntaxiques et techniques.

Publié initialement par l’ANS en 2009 et régulièrement mis à jour depuis, le CI-SIS est destiné aux opérateurs de maîtrise d’œuvre au sens large (éditeurs de logiciel, intégrateurs…) ainsi qu’aux opérateurs de maitrise d’ouvrage. Il a été basé sur des normes et standards internationaux d’échange utilisés dans le secteur de la santé de manière à assurer :

*  Une adéquation avec les besoins du secteur : les normes et standards utilisés ont été conçus pour la mise en œuvre de cas d’usage relatifs à la prise en charge des usagers ;
*  Une réutilisabilité des développements avec un minimum d’efforts d’adaptation pour différents cas d’usage que ce soit au niveau national ou au-delà du marché français.

Initialement orienté sur les cas d’usage correspondant aux principaux projets numériques d’échange et de partage portés par l’agence lors de sa création en 2009, c’est-à-dire le DMP et MSSanté, le CI-SIS est longtemps resté cantonné à ces cas d’usage, pour lesquels les orientations suivies en termes de normes et standards avaient été définies avec l’ensemble des parties prenantes (représentants des industriels, utilisateurs, institutionnels…) lors d’une phase de conception qui a duré un peu plus d’un an. Arrivé à maturité sur son périmètre initial, le CI-SIS doit évoluer de façon constante de façon à être utile à l’ensemble du secteur sanitaire et medico-social. C’est le but de la nouvelle gouvernance mise en œuvre depuis fin 2024.

La construction progressive du CI-SIS répond aux orientations stratégiques définies et mises à jour régulièrement par la gouvernance du CI-SIS et à la feuille de route d’interopérabilité résultant. Cette gouvernance est conçue pour faciliter et maîtriser la multiplication des cas d’usage pris en compte dans le CI-SIS. Il s’agit à la fois d’augmenter le nombre des cas d’usage couverts par le CI-SIS tout en assurant une stabilité des spécifications, et de donner aux acteurs de la visibilité à long terme. À cette fin, une stratégie globale doit être définie et intégrée dans une doctrine publique sur la méthode d’évolution et la méthodologie de choix des normes et standards internationaux applicables au développement du CI-SIS.

Ce document a pour objectif de présenter cette doctrine ainsi que son articulation avec la gouvernance du CI-SIS. Après un rappel des enjeux de l’interopérabilité pour les concepteurs et les utilisateurs de systèmes d’information, ce document présente les composants de la doctrine en indiquant en quoi ceux-ci répondent aux enjeux, avant de détailler l’articulation avec la gouvernance du CI-SIS.

### Enjeux de l’interopérabilité et du CI-SIS

La dématérialisation des processus est un enjeu décisif pour les secteurs sanitaire, médico-administratif, médico-social et social. Vecteur d’optimisation de la prise en charge tant au niveau organisationnel qu’au niveau économique, cette dématérialisation nécessite des investissements souvent importants aussi bien de la part des opérateurs de maîtrise d’œuvre que de la part des opérateurs de maitrise d’ouvrage, non seulement en termes de spécifications et de développement mais également en termes de formation sur les technologies, ainsi que sur les normes et standards d’échange utilisés.

Afin de rentabiliser ces investissements, il est important que les spécifications des échanges entre SI :

*  Soient adaptées aux cas d’usage métier initiaux ;
*  Puissent être réutilisées dans d’autres cas d’usage pour le même contexte ou dans d’autres contextes (par exemple pour des mises en œuvre en dehors du contexte français) ;
*  Bénéficient d’une certaine stabilité

Les normes et standards internationaux utilisés dans les secteurs concernés peuvent constituer un premier niveau tendant vers l’atteinte de ces objectifs. Cependant, ils sont trop divers, trop larges et ont une couverture trop incomplète de l’ensemble des cas d’usage pour pouvoir donner la visibilité à long terme recherchée.

Dans l’optique de réduire cette diversité, les profils internationaux ont pour vocation de guider la mise en œuvre des normes et standards généraux dans le contexte de cas d’usage identifiés. C’est le cas par exemple des profils WS ou SAML qui détaillent la mise en œuvre des standards correspondants pour des cas d’usage génériques d’échange entre systèmes d’information. Les profils internationaux peuvent également être plus détaillés pour être adaptés à un domaine en particulier. Les organisations internationales HL7, IHE et Continua Alliance, par exemple, produisent des profils adaptés aux cas d’usage du domaine de la santé.

Enfin, les profils nationaux ont pour objectif d’adapter aux contextes nationaux les profils internationaux lorsqu’ils existent ou, à défaut, les normes et standards internationaux techniques et sémantiques. En France, le [Référentiel Général d’Interopérabilité (RGI)](https://www.numerique.gouv.fr/publications/interoperabilite) constitue par exemple une adaptation nationale pour des cas d’usage génériques d’échange entre systèmes d’information. Il est censé être en adéquation avec le [cadre d’interopérabilité européen](https://ec.europa.eu/isa2/sites/default/files/eif_brochure_final.pdf) ([European Interoperability Framework – EIF](https://ec.europa.eu/isa2/eif_en/)).

Dans le domaine de la santé, le CI-SIS regroupe les profils opérationnels correspondant aux cas d’usage français. Il est basé sur des profils IHE ou des guides d’implémentation HL7 FHIR internationaux lorsqu’ils existent ou, à défaut, sur des normes et standards internationaux.

Dans le futur, il est possible que le CI-SIS soit également basé sur des spécifications publiées par d’autres organisations qui font autorité au niveau international telles que l’OMS, les accélérateurs de projets européens/internationaux ou au niveau national avec des organisations telles que [EDESS](http://www.edess.org/joomla/index.php) ou [InteropSanté](https://www.interopsante.org/). Cette dernière possibilité pourrait être envisagée uniquement pour des standards nationaux ouverts et libres de droits.

Le CI-SIS est également en cohérence avec les orientations du [RGI](https://www.numerique.gouv.fr/publications/interoperabilite) et du [cadre d’interopérabilité européen](https://ec.europa.eu/isa2/sites/default/files/eif_brochure_final.pdf) ([European Interoperability Framework – EIF](https://ec.europa.eu/isa2/eif_en/)). Cependant les profils exposés par le CI-SIS peuvent s’écarter de ces orientations pour répondre aux spécificités de l’écosystème français lorsque cela est nécessaire.

**Exemple (non exhaustif) de positionnement de profils français et internationaux par rapport aux normes et standards**

Par exemple :

*  Pour le cas d’usage de partage de document de santé, le CI-SIS constitue le profil français du profil IHE XDS (Cross Enterprise Document Sharing) qui est lui-même une adaptation du standard ebXML d’OASIS pour les cas d’usage de partage de documents dans le domaine de la santé ;
*  Pour le cas d’usage de la transmission des données d’identité pour la mise en œuvre de droits d’accès, le VIHF (Vecteur d’Identification et d’Habilitation Formelles) du CI-SIS est basé sur le profil IHE XUA (Cross Enterprise User Assertion) lui-même basé sur le token profile pour le standard SAML d’OASIS ;
*  Pour le cas d’usage du compte-rendu de rétinographie, en l’absence de profil international, le volet du CI-SIS est un profil français directement basé sur la norme CDA éditée par HL7 ;
*  Pour le cas d’usage du partage de données de santé en mobilité, le volet du CI-SIS est basé sur le profil IHE MHD (Mobile access to Health Documents).

Ainsi, le Cadre d’Interopérabilité des systèmes d’information de santé (CI-SIS) a pour objectif clé de développer la capacité des systèmes d’information à échanger/partager des données de manière naturelle sans développements informatiques complexes et coûteux. Il est constitué d’un ensemble de spécifications qui définit les informations à échanger/partager entre les systèmes d’information de santé et identifie la norme ou le standard le plus approprié à utiliser pour cet échange/partage.

Par la définition des interactions entre les systèmes d’information, le CI–SIS décrit des mécanismes d’échanges et de partage ainsi que leurs contenus en utilisant des standards internationaux ouverts mis en cohérence avec le contexte français. C’est ce qu’on appelle « l’interopérabilité technique »

Par la définition de la structuration du contenu médical, le CI–SIS permet d’identifier le langage adéquat pour présenter des informations selon les standards et les normes reconnus ainsi que le vocabulaire à utiliser pour coder l’information (interopérabilité sémantique). Ceci permet de faciliter le traitement automatique de l’information et permet la mise en œuvre de services à valeur ajoutée. C’est ce qu’on appelle « l’interopérabilité syntaxique et sémantique ».

De nature à favoriser l’adéquation opérationnelle des profils français du domaine de la santé, du medico-social et social, aux cas d’usage métier, ce positionnement de fait nécessite une formalisation au sein d’une doctrine du CI-SIS afin de fournir une meilleure visibilité aux parties prenantes sur les orientations du CI-SIS en termes de normes et standards techniques, syntaxiques et sémantiques.

### La doctrine du CI-SIS

La doctrine du CI-SIS a pour objectif de formaliser les orientations suivies par le CI-SIS en termes de normes et standards dans le cas général et de fournir un processus de détermination des normes et standards à suivre lorsque le cas d’usage considéré ne peut pas être mis en œuvre via ces orientations. Une fois validée par les acteurs du domaine, elle permet de s’affranchir d’une consultation préalable à l’élaboration des spécifications d’interopérabilité lorsqu’un besoin d’interopérabilité peut être pris en compte par une norme ou un standard déjà existant dans les orientations du CI-SIS. Elle ne change pas le processus d’élaboration des spécifications d’interopérabilité qui sont soumises à concertation publique, qu’il y ait eu une consultation préalable ou non sur les normes/standards.

La doctrine technique et syntaxique du CI-SIS peut être synthétisée par les règles suivantes :

*  Utilisation d'un profil IHE ou d'un guide d'implémentation FHIR adapté et stable ;
*  A défaut, réutilisation des normes et standards déjà utilisés dans le CI-SIS pour des cas d'usage similaires ;
*  A défaut, consultation des acteurs pour identification de la norme ou du standard à utiliser pour prendre en compte le besoin d'interopérabilité.

La doctrine sémantique du CI-SIS en termes de terminologies de référence à retenir :

*  Utilisation d'une terminologie de référence déjà utilisée en France et alignement, le cas échéant avec la terminologie de référence retenue par le niveau européen ;
*  A défaut, recherche d'une terminologie européenne ;
*  A défaut, consultation des acteurs pour identification de la terminologie de référence à utiliser pour prendre en compte le beosin d'interopérabilité et création de jeux de valeurs ad hoc.

L’ensemble des spécifications d’interopérabilité (au sein du Cadre d’Interopérabilité des Systèmes d’Information de Santé (CI-SIS)) et des terminologies constitue un bien commun, qui respecte les principes de transparence, de collaboration, de participation et d’éthique.

**Principes généraux de la doctrine du CI-SIS**

### Les principes de la doctrine du CI-SIS

Une doctrine est par définition : un ensemble de principes génériques de base sur lequel s’appuie une stratégie et des plans d’actions [2](#ref2). Dans ce qui suit, nous décrivons les principes sur lesquels la doctrine du CI-SIS s’appuie.

#### Principes #1 : Principes issus du cadre juridique

La loi du 7 octobre 2016 [3](#ref3) pour une république numérique, souvent appelée “Loi république numérique”, est une législation française visant à adapter le cadre juridique aux enjeux de la transformation numérique. Cette loi est une source de « règles » pour la doctrine du CI-SIS. Le [SI-CM (Système d’Information et Connaissances Médicales)](#doctrine-de-la-connaissance-médicale) et les volets qui vont être publiés dans le CI-SIS doivent doivent, entre autres, souscrire

* à l'ouverture des données produites
* à rendre accessibles en ligne les données publiques produites dans un format ouvert et réutilisable
* à la portabilité des données produites. Les utilisateurs finaux doivent pouvoir se partager les données publiques et libres d'accès (voir chapitre sur la propriété intellectuelle)

Plusieurs de ces principes ont été directement ou partiellement inspirés des principes FAIR et de la mouvance Open Data que nous prenons également comme base de réflexion pour la doctrine du CI-SIS.

#### Principes #2 : Principes FAIR

Les principes FAIR (Findable, Accessible, Interoperable, Reusable) [4](#ref4) visent à améliorer la gestion et le partage des données scientifiques. Ils sont conçus pour faciliter la découverte, l’accès, l’interopérabilité et la réutilisation des données de recherche.

Le SI-CM et les volets qui vont être publiés dans le CI-SIS doivent, entre autres, souscrire

* A ce que les artéfacts publics produits soient facilement trouvables via une plateforme dédiée. La plateforme en question doit être implémentée de façon à ce que
* A ce que les artéfacts publiques soient accessibles en s’assurant que
* A ce que les artéfacts publiques produits soient interopérables en s’assurant que
* A ce que les artéfacts publiques produits soient réutilisables en s’assurant que

#### Principes #3 : Principes du mouvement de l’Open Data

Le mouvement Open Data (données ouvertes) [5](#ref5) est une initiative mondiale qui vise à rendre les données publiques librement accessibles à tous, sans restriction légales, financières ou techniques. Plusieurs des principes de ce mouvement sont partagés avec le mouvement FAIR Data. La version Five Star [5](#ref5) du mouvement Open Data [6](#ref6) apporte plus de précision sur les principes du mouvement Open Data. Le mouvement Five Star [5](#ref5) définit une échelle et des étapes pour atteindre le niveau maximal de conformité à ces principes (Figure 1).

La doctrine du CI-SIS vise à pousser l’écosystème à adopter, autant que faire se peut, l’échelle maximale (5 étoiles) de conformité pour la publication des artéfacts de connaissances médicales.

**Figure 1 : ENONCE SIMPLIFIE DES PRINCIPES FIVES STARS (6)**

#### Principes #4 : Principes en lien avec les bonnes pratiques d’ingénierie logicielle et de recherche

Un projet informatique quel qu’il soit doit se conformer aux principes de base de conception, d’architecture et de développement logiciel. Il en va de même pour les projets d’interopérabilité de façon générale et pour les projets d’interopérabilité des artéfacts de connaissances médicales.

Les projets d’interopérabilité des artéfacts de connaissances médicales doivent également se conformer aux principes de base de l’ingénierie des connaissances.

Dans ce qui suit nous listons les principes d’ingénierie que la doctrine du CI-SIS doit respecter.

##### L’utilisation des Design Patterns

Les artéfacts publiés, développés ou partagés doivent se conformer aux principes architecturaux énoncés dans la littérature et adoptés par l’écosystème des ingénieurs informatiques. Dans ce qui suit nous citons succinctement quelqu’un de ces principes.

1. La modularité : un logiciel doit être divisé en modules ou composants distincts, chacun ayant une fonction spécifique.
1. L’encapsulation : permet de restreindre l'accès direct aux données et fonctions internes d'un module, exposant uniquement ce qui est nécessaire via des interfaces publiques.
1. L’abstraction : consiste à cacher la complexité interne d’implémentation à l’utilisateur en se concentrant sur les aspects essentiels à l’utilisateur
1. La forte cohésion : le degré auquel les éléments d'un même module sont liés fonctionnellement doit être fort.
1. Le faible couplage : les modules doivent être faiblement interdépendants
1. La séparation des responsabilités : la responsabilité est un ensemble de fonctionnalités pris en charge par un module ou un ensemble de modules distincts. La séparation des responsabilités revient à concevoir le logiciel en groupes de modules distincts en termes de groupes de fonctionnalités

Il existe bien évidemment beaucoup plus de bonnes pratiques de conception logiciel énoncés dans la littérature, voici quelques références de base [7](#ref7) [8](#ref8) [9](#ref9) [10](#ref10).

##### L’adoption d’un processus de conception logiciel

Un projet en lien avec la standardisation et/ou l’interopérabilité des données de santé est un projet informatique à part entier. Il est donc nécessaire d’adopter un processus de conception logiciel adéquat pour structurer et organiser la conception et le développement des artéfacts produits par le projet en question. Les processus de conception doivent à minima inclure les étapes : collecte des exigences, la modélisation, la création de prototypes, et la validation des concepts avant la phase de développement.

Les processus de conception logiciels les plus utilisés en ingénierie des logiciels à l’heure actuelle sont ceux issus du mouvement Agile. De nombreux « framework Agiles » existe, tels que : Scrum, Kanban, XP, Lean, Scaled Agile Framework,…

**L’ingénierie des connaissances**

Les projets en lien avec la connaissance sont également gérés suivant des processus de conception en lien avec une discipline appelée : l’ingénierie des connaissances [11](#ref11) [12](#ref12). L’ingénierie des connaissances se concentre sur la création, la gestion et l’utilisation de la connaissance dans les systèmes informatiques. Elle implique la collecte, la structuration, la formalisation et la mise en œuvre des connaissances pour développer des systèmes intelligents capables de résoudre des problèmes complexes. Cette discipline est essentielle dans des domaines tels que l’intelligence artificielle, les bases de connaissances et bien évidemment la structuration et la standardisation de la connaissance (médicale).

Les projets en lien avec la standardisation de la connaissance médicale doivent adopter un processus de conception Agile d’ingénierie des connaissances. Les artéfacts produits dans chaque étape de conception (de transformation de la connaissance) doivent être visibles et explicites pour chaque volet suivant le design pattern décrit ici …

##### L’adoption d’un langage de modélisation standard

Les langages de modélisation standard en ingénierie des logiciels sont des outils essentiels pour représenter visuellement les structures, les comportements et les interactions au sein d’un système logiciel. Ils permettent de faciliter la compréhension, la communication et la documentation des concepts complexes entre les parties prenantes. Parmi les langages de modélisation les plus utilisés, on retrouve : Unified Modeling Language (UML), SysML (Systems Modeling Language), Business Process Model and Notation (BPMN)…

Ces langages de modélisation standard jouent un rôle crucial dans la conception, l’analyse et la gestion des projets de développement logiciel, en assurant une vision cohérente et partagée du système à construire.

Le mouvement Agile n’impose pas de langage de modélisation particulier mais le manifeste Agile insiste sur l’attention continue que doit porter l’équipe de développement logiciel à l’excellence technique et à la conception basée sur les bonnes pratiques mais également sur la facilitation de la transmission de l’information entre les membres de l’équipe du projet. L’utilisation d’un langage de modélisation standard dans un processus de conception Agile permet de combiner les avantages de la modélisation formelle avec la flexibilité et la réactivité des méthodes agiles. Un langage de modélisation peut être utilisé de manière pragmatique pour clarifier les exigences, faciliter la communication entre les équipes et documenter les architectures logicielles de manière succincte. Ambler [13](#ref13) et Rumbaugh [14](#ref14), estime que l’intégration d’UML (par exemple, N.D.L.R) dans les pratiques agiles aide à maintenir la cohérence et la compréhension commune du projet tout en respectant les principes agiles de simplicité et de réponse rapide aux changements.

Le processus de conception adopté dans le cadre de la gestion des artéfacts doit également adopter un (ou plusieurs) langage de modélisation standards.

#### Choix des profils IHE et des guides d’implémentation comme base de la doctrine syntaxique du CI-SIS

Les profils IHE et les guides d’implémentation d’HL7 sont des spécifications opérationnelles d’interopérabilité qui indiquent comment utiliser des normes/standards stables et « vivants » dans le cadre de cas d’usage des domaines sanitaire, medico-social et social. Ce travail d’analyse et de sélection des normes/standards ainsi que la prise en compte des spécificités des cas d’usage de ces domaines en font une base de départ adaptée pour les spécifications du CI-SIS, qui n’ont plus qu’à contraindre ces profils et ces guides d’implémentation en fonction du contexte français.

Cette adéquation est également reconnue au niveau européen. En effet, le 28 juillet 2015 la Commission Européenne a identifié 27 profils IHE pouvant servir de référence dans la passation de marchés publics, profils qui ont été intégrés au cadre d’interopérabilité européen. Ces profils sont présentés [dans ce tableau](Liste_Profils_IHE_Standards.xls).

Ces éléments ont amené à considérer les profils IHE ainsi que les guides d’implémentation comme base de la doctrine du CI-SIS. Pour autant, toutes ces spécifications n’ont pas un niveau de maturité suffisant pour constituer une base solide :

*  Certains profils IHE ne sont plus utilisés sur le terrain et pas encore retirés des spécifications IHE (ex. le profil Patient Synchronized Application basé sur le standard CCOW) ;
*  Certains profils IHE en trial implementation ne sont pas encore tout à fait stables (ex. les profils qui n’ont pas encore eu l’occasion d’être testés lors d’un Connectathon).

Les profils et les guides d’implémentation choisis pour constituer la base de la doctrine du CI-SIS sont donc :

*  Les profils IHE en final text régulièrement testés au connectathon et/ou bénéficiant d’une communauté active ;
*  Les profils IHE en trial implementation depuis plusieurs années, régulièrement testés au connectathon et/ou bénéficiant d’une communauté active, et ne faisant pas l’objet de change proposals (CP) structurant et dont l’intégration en final text est prévue à court terme (ex. en attente d’outils de test automatisés).
*  Les guides d’implémentation au statut Trial use ou Normative.

D’autre part, dans le cadre du règlement relatif à l’espace Européen des données de santé (EHDS), le réseau eHealth Network, sous l’égide de la Commission Européenne, définit des normes et standards internationaux et des spécifications techniques s’adressant aux entreprises du numérique en santé des états membres, précisant l’implémentation de ces normes et standards au fur et à mesure de la construction de cet espace Européen des données de santé. En particulier, EHDS est basé sur un format d’échange des données de santé (EEHRxF) constitué à ce jour des guidelines suivantes :

* ePrescription and eDispensation,
* Patient Summary,
* Laboratory results and reports,
* Medical imaging studies and reports,
* Hospital discharge reports.

Les dernières guidelines publiées dans ce cadre introduisent en particulier le standard Fast Health Interoperable Resources (FHIR) d’HL7. Ces guidelines sont ensuite déclinées en guides d’implémentation qui précisent l’implémentation opérationnelle des cas d’usage adressés.

#### Réutilisation des normes et standards déjà utilisés dans le CI-SIS

Afin de répondre aux enjeux de stabilité et de réutilisation, lorsqu’il n’existe pas de profil IHE ou de guide d’implémentation FHIR adapté à un cas d’usage, les normes et standards déjà utilisés dans le CI-SIS pour d’autres cas d’usage sont réutilisés s’ils sont adaptés.

Par exemple, la norme CDA a été initialement utilisée dans les spécifications de plusieurs volets tels que :

* Structuration Minimale de Documents Médicaux (basé sur le profil IHE XDS-SD) ;
* Compte rendu d’Examens de Biologie Médicale (basé sur le profil IHE XD-Lab) ;
* Compte Rendu Structuré d’Anatomie et de Cytologie Pathologiques (basé sur le profil IHE APSR).

Ainsi, afin de capitaliser l’expérience acquise par les parties prenantes et de favoriser la réutilisation des développements et en l’absence de contrainte spécifique du cas d’usage qui rendrait son utilisation inadaptée, la norme CDA reste à ce jour la norme à profiler pour les spécifications du CI-SIS concernant des documents structurés.

Cependant, l’ANS a défini une [trajectoire d’interopérabilité](./trajectoire-iop.md) qui tient compte des orientations retenues par la Commission Européenne dans le cadre de la construction de l’espace de données de santé européen (European Health Data Space - EHDS). Une de ces orientations concerne l’utilisation du standard FHIR en remplacement ou en complément de CDA pour les documents structurés.

La liste des normes et standards utilisés dans le CI-SIS évolue constamment à la faveur de la production de nouveaux volets du CI-SIS. A titre d’information, les normes et standards qui sont utilisés dans le CI-SIS en septembre 2024 sont présentés [ici](Liste_Profils_IHE_Standards.xls).

#### Choix des normes et standards non encore utilisés dans le CI-SIS

La doctrine du CI-SIS ne peut pas couvrir l’ensemble des cas d’usage faisant l’objet d’une spécification d’interopérabilité. Quand il est nécessaire de sélectionner une norme ou un standard (syntaxique, sémantique ou technique) cible qui n’est pas encore utilisé dans le CI-SIS, il est indispensable que l’ensemble des parties prenantes qui pourraient être affectées par ce choix :

* Soient informées sur les normes et standards utilisables pour la mise en œuvre du cas d’usage ;
* Aient la possibilité de détailler les impacts de ces normes et standards en ce qui les concernent (ex. standard non conforme avec les politiques industrielles des éditeurs) ;
* Aient la possibilité de proposer des normes ou des standards qu’ils estiment adaptés.

Dans ce cas, la doctrine du CI-SIS est donc complétée par une procédure de consultation sur les normes et standards pour les cas d’usage non couverts par des profils IHE, par des guides d’implémentation FHIR d’HL7 adaptés ou par des normes et standards déjà utilisés dans le CI-SIS.

Cette consultation s’organise en 6 étapes :

*  Recensement des normes et standards utilisables pour la mise en œuvre du cas d’usage par les experts du CI-SIS ;
*  Analyse comparative des normes et standards utilisables par les experts du CI-SIS ;
*  Lancement de la consultation par diffusion de l’analyse comparative aux parties prenantes ;
*  Recueil des commentaires des parties prenantes sur l’analyse comparative ;
*  Mise à jour de l’analyse comparative par les experts du CI-SIS et recommandations ;
*  Présentation de l’analyse comparative et des recommandations aux parties prenantes et décision sur la norme ou le standard à utiliser.

Ces différentes étapes sont détaillées dans les schémas de la section suivante.

#### Articulation entre la doctrine et la gouvernance du CI-SIS

La doctrine du CI-SIS est complètement intégrée à la gouvernance du CI-SIS. Elle vient se positionner en entrée de la phase 4 de l’instruction de la gouvernance lors du choix de la syntaxe et de la sémantique cibles à utiliser dans les spécifications d’interopérabilité.

**Niveaux Rappel des phases de la gouvernance du CI-SIS**

En y intégrant les éléments de la doctrine syntaxique et sémantique du CI-SIS, la phase d’évolution du CI-SIS (phase 4) se décompose en 5 sous-phases :

* A. Analyse métier du cas d’usage, modélisation des échanges entre SI conformément à la [méthodologie d’élaboration des spécifications fonctionnelles des échanges](./elaboration.md), et choix de terminologie(s) de référence répondant au cas d’usage étudié selon les principes de la doctrine sémantique ;
* B. Concertation publique sur la spécification fonctionnelle des échanges (intégrant les choix de terminologies) ;
* C. Choix de la norme ou du standard syntaxique selon les principes de la doctrine syntaxique du CI-SIS ;
* D. Rédaction des spécifications techniques d’interopérabilité par correspondance entre les échanges modélisés et la syntaxe cible assortie des règles de mise en œuvre tel que définies dans la norme ou le standard choisi ;
* E. Concertation publique sur la modélisation des échanges et les spécifications d’interopérabilité correspondantes et finalisation des spécifications.

**Sous phases de la phase d’évolution du CI-SIS**

Ces travaux peuvent être faits en collaboration avec l’écosystème via une contractualisation sous forme d’[Unité de Production externe](./up-externe.md).

### Doctrine de la connaissance médicale

Dans un monde où la standardisation de l’information médicale ne suffit plus à garantir la qualité des soins prodigués dans le cadre d’un Système d’Information (SI) de santé, ce document jette les premières réflexions sur une doctrine en lien avec la standardisation de la connaissance médicale en France.

La standardisation de la connaissance médicale issue, entre autres, des Guides de Bonnes Pratiques Cliniques (GBPC) et leur intégration de façon standard dans un SI de santé est un atout majeur pour la transition du modèle volume-based à value-based d’un SI de santé à l’échelle nationale. Cette connaissance médicale standardisée peut servir à définir des aides à la décision clinique standards ainsi que des mesures de la qualité des soins standardisées, nécessaires à la remontée d’indicateurs de la qualité des soins. Les réflexions décrites ci-dessous sont une adaptation des travaux menés par le CDC (Centers for Disease Control and Prevention) américain au travers de l’initiative Adapting Clinical Guidelines for the Digital Age. [28](#ref28).

Deux événements majeurs ont poussé les responsables et les experts de l’ANS à réfléchir à un tel document. Premièrement, l’introduction d’un nouvel SI, appelé SI-CM (Système d’Information et Connaissances Médicales). Le SI-CM permettra dans un futur proche d’introduire de nouveaux volets d’interopérabilité dans le CI-SIS principalement en lien avec la standardisation des connaissances médicales issues des guides de bonnes pratiques cliniques (GBPC) et la standardisation de leur intégration dans un SI de santé. Il est également en lien avec la standardisation des critères de qualité de soins. Deuxièmement, des travaux de mise à jour de la doctrine et de la gouvernance du CI-SIS ont été menés en interne à l’ANS afin de permettre au CI-SIS de se conformer aux nouvelles tendances en informatique de façon générale et en interopérabilité des données de santé de façon plus spécifique.

Ce document vient donc s’inscrire dans le cadre des travaux de mise à jour de la doctrine et de la gouvernance du CI-SIS. Ce document complète la doctrine du CI-SIS mise à jour en y introduisant les principes de base que doivent suivre les projets d’interopérabilités en lien avec la standardisation de la connaissance médicale apportés par le SI-CM.

#### Publics concernés 

Ce document s’adresse principalement aux personnes et organismes qui veulent comprendre

* Comment les principes de la présente doctrine ont été élaborés 
* Comment les principes de la présente doctrine ont été utilisés pour faire des choix de standards, de méthodes et d'outils pour concevoir et partager des artéfacts de connaissances médicales standardisés 
* Quels sont les standards, méthodes et outils choisis et préconisés par l’ANS si on veut standardiser des artéfacts de connaissances médicales et les intégrer sous forme d’aide à la décision cliniques 

#### Le cadre de la doctrine d'interopérabilité du SI-CM 

La doctrine d’interopérabilité du SI-CM s’inscrit dans les orientations suivies par la nouvelle version de la doctrine du CI-SIS décrite ici [1](#ref1). La doctrine du SI-CM peut-être synthétisée ainsi

* Un ensemble de principes de base qui permettent de guider les choix en termes de standards, de méthodes et d’outils pour atteindre l’objectif 
* Un chemin nominal : qui instancie les principes de la doctrine du SI-CM et décrit les choix en termes de standards de référence, de méthodes et d’outils adoptés pour atteindre les objectif sus mentionnés 
* Un ou plusieurs chemins secondaires : décrivent le choix et l’utilisation d’un standard et / ou d’un processus de conception et / ou de mise en œuvre « non de référence ». Ce chemin secondaire peut être justifié par le fait que le chemin nominal ne réponde pas aux besoins remontés du terrain. 

La doctrine d’interopérabilité du SI-CM décrite dans ce document couvre

1. Les concepts en lien avec la standardisation de la connaissance médicale issue des GBPC
1. Les concepts en lien avec la standardisation de l’intégration de la connaissance médicale sous forme de système d’aide à la décision clinique (SADC) dans un SI de santé

#### Les principes de la doctrine du SI-CM

Dans ce qui suit, nous décrivons les principes spécifique de la doctrine du SI-CM sur lesquelles elle s’appuiera pour gérer les artéfacts de connaissances médicales que le SI-CM produira / exposera. Ces principes nous permettront d’instancier un chemin nominal pour la gestion des artéfacts produits / exposés par le SI-CM et un ou plusieurs chemins secondaires. Ces chemins décriront les outils de modélisation, de conception et de mise en œuvre qui devront être utilisés et/ou promus (à destination de l’écosystème) par le SI-CM pour la gestion des artéfacts de connaissances médicales en France. Les principes commun à l’ensemble de la doctrine du CI-SIS sont présentés dans le chapitre précédente.

##### Principes #4 : Principes en lien avec les bonnes pratiques d'ingénierie logicielle et de recherche

######  L'adoption des Designs Patterns en ingénierie des connaissances pour la standardisation des GBPC et leur intégration dans un SI de santé

En ingénierie des connaissances et plus particulièrement dans le cadre défini en paragraphe 2 de cette doctrine, nous avons identifié 3 designs patterns que le SI-CM doit respecter dans la gestion des artéfacts de connaissances médicales

L'architecture tri-dimentionnel de Rector et al.
La standardisation des GBPC dans le cadre du SI-CM doit combiner et interfacer trois types de modèles (Figure 2) [15](#ref15)

* **Information about specific patients and clinical situations** : ce modèle dit d’informations médicales permet de standardiser les informations issues du dossier patient
* ** General patient-independent information about medicine and medical practice **: ce modèle dit de connaissances métiers comprend 2 sous modèles
* **Guideline independent static knowledge**: un modèle de connaissances métiers dit statique. C’est ce qui correspond le plus dans le jargon de l’interopérabilité aux modèles définis par les terminologies médicales.
* ** Guideline dependent dynamic knowledge model**: Ce modèle dit d’inférence a pour objectif de modéliser comment on infère les conclusions et les décisions d’informations spécifiques au patient et des faits indépendants décrit dans le GBPC.

**Figure 2 : Les modèles de l’architecture tri-dimensionnel de Rector et al. (15) et leurs interfaces**

La représentation multi couches de la connaissance médicale de Boxwala et al.
La standardisation des GBPC dans le cadre du SI-CM doit respecter les différents niveaux de structuration de la connaissance décrits dans [16](#ref16) (Tableau 1) Les documents de spécifications pour chaque volet du SI-CM doivent pouvoir décrire la structuration de la connaissance médicale du GBPC cible suivant ces quatre formats de représentation

1. **Narratif** : ce format correspond au texte brut de la recommandation du GBPC cible ainsi que le lien vers la recommandation en question.
1. **Semi structuré** : Ce format correspond à une interopération du texte brut en vue de sa structuration. Ce format permet de définir à partir du texte brut : le qui, le quoi, le quand, le où et le pourquoi. Il permet de définir les concepts statiques qui composent la recommandation et d’identifier les terminologies auxquels ils peuvent correspondre. Ce format est généralement une combinaison de texte structuré et de diagrammes d’activités UML.
1. **Structuré** : Ce format doit impérativement correspondre au modèle appelé : Guideline dependent dynamic knowledge model décrit dans le paragraphe précédent
1. **Exécutable**: Ce format correspond au code exécutable par un SADC.

**Tableau 1 : les quatre couches de formats de représentation de la connaissance médicale selon Boxwala et al. (16)**

L'intégration standardisée des SADC basés sur les GBPC dans un SI de santé
La connaissance médicale issue des GBPC standardisée dans le cadre du SI-CM n’aura de valeur que si elle est déployée et exploitée par l’écosystème. Une des stratégies préconisées dans la littérature pour faciliter l’adoption de cette connaissance par les professionnels de santé est son déploiement sous forme de SADCs [17](#ref17). Une des principales barrières décrites dans la littérature à l’adoption des SADC (basés ou non sur une connaissance médicale standardisée) par l’écosystème est la mauvaise scalabilité de ces systèmes. Adopter un standard d’intégration et d’exposition des SADCs est une des solutions architecturales préconisées dans la littérature pour améliorer la scalabilité des SADCs [18](#ref18). La connaissance médicale standardisée dans le cadre du SI-CM doit pouvoir s’intégrer dans un SI de santé sous forme d’un SADC en adoptant un standard d’intégration.

Se positionner par rapport aux Design Patterns architecturaux génériques
Les solutions logicielles conçues dans le cadre des problématiques posées par l’interopérabilité en santé doivent être réfléchies à un niveau d’abstraction qui permet d’instancier ces solutions de façons différentes autant de fois qu’elles seront utilisées sur le terrain pour un cas d’usage. C’est là, la définition même d’un Design Pattern. Les Design Patterns produits par les différentes sociétés savantes : HL7, IHE, IEEE,…peuvent être de trois catégories

1. Un modèle d’information standard : définie un modèle de données standard qui doit circuler dans des messages d’interopérabilité pour un cas d’usage X.
1. Un design pattern architectural : définie une solution logicielle standard qui s’appuie sur un modèle d’information standard pour résoudre un problème d’interopérabilité Y de façon standard.
1. Un design pattern architectural de contenu standard : instancie un design pattern architectural pour répondre à un cas d’usage particulier. Ce type de Design Pattern est le plus répondu.

Les spécifications définies et / ou exposées par le SI-CM doivent se positionner par rapport à ces trois types de design pattern architecturaux génériques.

**Pourquoi il est important de se positionner par rapport aux différentes catégories de Design Pattern ?**

L’interopérabilité telle qu’adoptée actuellement par l’éco système à travers le monde est basée sur la notion de cas d’usage. Chaque cas d’usage donne lieu à des spécifications qui sont censées répondre aux besoins décrits dans le cas d’usage. Cependant le risque est d’écrire des spécifications qui se chevauchent ou des spécifications dupliquées. Il est donc nécessaire à chaque début de projet de se positionner par rapport aux Design Patterns architecturaux générique décrits plus en amont pour pouvoir identifier les spécifications déjà existantes et pouvoir les réutiliser totalement ou partiellement. Ce principe rejoint les principes de modularité et de séparation des responsabilité décrits en paragraphe [L’utilisation des Design Patterns](#design-patterns)

###### La mise à jour de la doctrine guidée par la recherche

Une grande partie des principes énoncés plus en amont est basée sur des concepts issus de la recherche scientifique. Certains de ces concepts sont validés et adoptés par l’écosystème de l’ingénierie qui les exploite déjà dans des projets informatiques en routine, exemple : les design pattern de structuration des GBPC qui date de plus de 25 ans. D’autres concepts sont en cours d’évaluation par la communité des chercheurs et d’adoption par l’écosystème de l’ingénierie, exemple : le standard CDS Hooks [19](#ref19).

Il est donc nécessaire pour la doctrine du SI-CM de garder un œil sur l’évolution de certains concepts au regard de l’avancée de l’évaluation et de l’adoption de ces concepts en parcourant régulièrement les articles scientifiques correspondants.

###### L'évaluation de l'impact d'un SADC basé sur les bibliothèques de connaissances standards conçues et/ou exposées par l'ANS

Les bibliothèques standards de connaissances médicales publiées ou exposées par l’ANS doivent être évaluées avant toute mise en œuvre dans un SI de santé en production. L’évaluation de ces bibliothèques peut-être effectuée suivant différentes étapes

* **Les tests** : la phase de tests est couverte par <a href=processus-conception-logiciel>le processus de conception choisi</a>. Les tests permettent de s’assurer que les bibliothèques de connaissances standards répondent bien à l’objectif initiale de modélisation (cas d’usage). Les tests permettent également de s’assurer qu’il n’y ait pas d’erreurs dans le code de la bibliothèque ou dans le déploiement sous forme de SADC basé sur cette bibliothèque. Les tests peuvent être effectués sur des données fictives.
* **L’évaluation rétrospective** : l’évaluation de l’impact du SADC basé sur la ou les bibliothèques standards est une étape qui n’est pas couverte habituellement par les processus de développement logiciel. Une première étape d’évaluation de l’impact peut-être effectuée sur des données réelles rétrospectives. La bonne pratique la plus répondue pour effectuer des évaluations d’impact de SADC sur des données rétrospectives est l’utilisation des entrepôts de données cliniques [20](#ref20).
* **L’évaluation prospective (étude de recherche clinique non randomisée) **: Elle est mise en œuvre dans le cadre d’une étude de recherche clinique. Il existe une catégorie d’étude de recherche clinique non randomisée destinée à l’évaluation de l’impact des SADC appelée : Quasi-Experimental Studies [21](#ref21). 
* **L’évaluation prospective randomisée **: il s’agit de la catégorie de recherche clinique qui (dé)montre la preuve scientifique la plus importante. 

##### Principes #5 : Définir la relation avec les doctrines du CI-SIS et CGTS

Les artéfacts produits et gérés par le SI-CM sont en étroites relation avec ceux produits et gérés par le CI-SIS et le CGTS (voir chapitre précédent). Les artéfacts produits et gérés par le SI-CM peuvent réutiliser, tout ou partie des artéfacts produits et gérés par le CI-SIS et le CGTS.

Les volets produits et gérés dans le cadre du SI-CM doivent, autant que faire se peut, partager les mêmes principes que le CI-SIS dans leur doctrine respective ou à défaut des principes qui ne se contredisent pas. La doctrine du SI-CM doit s’inscrire dans la continuité et / ou la complémentarité de celle du CI-SIS et du CGTS et vis vers ça.

Les artéfacts de connaissances médicales qui suivent le principe de [l’architecture tri-dimensionnelle de Rector et al.](#archi-tri-dim) [15](#ref15) doivent partager, autant que faire se peut, le même modèle d’information médicale que le CI-SIS et le même modèle de connaissance métier statique que le CGTS.

#### Les chemins de la doctrine du SI-CM

Ce paragraphe décrit une instanciation nominale (et plusieurs instanciations secondaires) de la doctrine du SI-CM basée sur les principes énoncés plus en amont. Cette instanciation correspond à une série de choix de standards, d’outils, de méthodes et de règles que le SI-CM devra respecter pour gérer les artéfacts de connaissances médicales issus de la standardisation des GBPC produits et/ou exposés par l’ANS.

Ce chemin nominal n’est ni immuable ni parfait, il est et il sera donc sujet à mise à jour et / ou à des dérivations de chemins secondaires suivants les cas d’usage et l’évolution dans le temps des principes énoncés plus en amont.

Dans ce qui suit nous décrivons le chemin nominal ainsi que les possibles chemins secondaires de la doctrine du SI-CM.

##### Le chemin nominal de la doctrine du SI-CM

[La doctrine du SI-CM](#cadre-SI-CM) est un ensemble d’activités consistants à identifier et à choisir, en se basant sur les principes de la doctrine, les standards, outils et autres méthodes qui permettront à l’ANS de concevoir et gérer les artéfacts de connaissances médicales standardisés.

La figure 4 décrit un diagramme d’activité UML qui montre les activités d’identification des standards et outils en question. Toutes les activités en couleur verte ou vert bleuté correspondent à des activités du chemin nominal i.e. les outils et standards que l’ANS utilisera par défaut quel que soit le cas d’usage. Ces outils seront également ceux que l’écosystème devra utiliser dans le cas où l’ANS est saisie pour travailler sur un cas d’usage proposé par l’écosystème. Toutes les activités en bleu et vert bleuté correspondent à des chemins secondaires pour cette doctrine i.e. les cas où l’outil ou le standard préconisés par l’ANS ne répond pas au besoin du cas d’usage et nécessite d’investiguer d’autres outils ou standards.

Dans ce qui suit nous justifions nos choix d’outils et/ou standards pour le chemin nominal décrits en figure 4 en faisant la relation avec les principes de la doctrine énoncés plus en amont.

###### Relations entre les principes de la doctrine du SI-CM et les activités du chemin nominal instancié

Choisir un langage de modélisation
Cette activité est en relation avec le principe #4 sur [l’adoption d’un processus de conception logiciel](#processus-conception-logiciel) énoncé en amont. Le langage de modélisation standard choisi pour illustrer les étapes de conception et de structuration des artéfacts de connaissances médicales issues des GBPC dans la doctrine du SI-CM est le langage standard UML version 2.0 [22](#ref22).

Ce choix est justifié pour plusieurs raisons

* UML s’articule avec le principe #4 de la présente doctrine
* UML est le langage standard de modélisation en informatique depuis l’avènement de la mouvance orientée objet
* UML est actuellement utilisé par de nombreux projets de standardisation de la connaissance médicale
* UML s’articule avec l’ensemble des autres standards choisis dans le chemin nominal de la présente doctrine

Choisir un processus de modélisation
Cette activité est en relation avec le principe #4 sur [l’adoption d’un langage de modélisation standard](#archi-tri-dim) énoncé en amont. Le processus choisi pour encadrer le travail de conception et de structuration des artéfacts de connaissances médicales issues des GBPC dans la doctrine du SI-CM est le processus Agile décrit dans le FHIR IG CPG-on-FHIR [23](#ref23).

Ce choix est justifié pour plusieurs raisons :

* FHIR IG CPG-on-FHIR [23](#ref23) s’articule avec les principes #4 de la présente doctrine
* FHIR IG CPG-on-FHIR [23](#ref23) s’articule avec l’ensemble des autres standards choisis. FHIR IG CPG-on-FHIR [23](#ref23) permet de mettre en œuvre ensemble les différents modèles préconisés par l’architecture tri-dimensionnelle de Rector et al.[15](#ref15) il permet de mettre en œuvre le standard UML pour illustrer les différentes étapes de conception. Il permet de mettre en œuvre la représentation multi couches de la connaissance médicale de Boxwala et al. [16](#ref16).
* FHIR IG CPG-on-FHIR [23](#ref23) est actuellement utilisé par de nombreux projets de standardisation de la connaissance médicale

Choisir un modèle d'information standard
Cette activité est en relation avec le principe #4, [l’architecture tri-dimentionnel de Rector et al.](#archi-tri-dim) [15](#ref15) et les principes #1, #2, #3 et #5 énoncés en amont. Le modèle d’information standard choisi pour standardiser les informations issues du dossier patient est FHIR en version R4 [24](#ref24).

Ce choix est justifié pour plusieurs raisons :

* FHIR en version R4 s’articule avec l’ensemble des principes énoncés en amont
* FHIR en version R4 s’articule avec l’ensemble des autres standards choisis
* FHIR en version R4 s’articule avec les autres modèles correspondants au principe d’architecture tri-dimensionnelle de Rector et al. La figure 3 illustre l’instanciation de ce principe avec les différents modèles choisis pour la présente doctrine.
* FHIR en version R4 est actuellement utilisé par de nombreux projets de standardisation de la connaissance médicale
* FHIR en version R4 s’articule avec le choix de la doctrine du CI-SIS

Choisir un modèle de connaissances statiques standard
Cette activité est en relation avec le principe #4, [l’architecture tri-dimentionnel de Rector et al.](#archi-tri-dim) [15](#ref15) et les principes #1, #2, #3 et #5 énoncés en amont. La ou les terminologies médicales choisies pour structurer les artéfacts de connaissances issus de la standardisation des GBPC sont celles recommandées par la doctrine du CGTS.

Ce choix est justifié pour plusieurs raisons :

* Les terminologies gérées par le CGTS (via le SMT) s’articulent avec l’ensemble des principes énoncés en amont
* Les terminologies gérées par le CGTS (via le SMT) s’articulent avec l’ensemble des autres standards choisis 
* Les terminologies gérées par le CGTS (via le SMT) s’articulent avec les autres modèles correspondants au principe d’architecture tri-dimensionnelle de Rector et al [15](#ref15). La figure 3 illustre l’instanciation de ce principe avec les différents modèles choisis pour la présente doctrine.
* Les terminologies gérées par le CGTS (via le SMT) sont actuellement utilisées par de nombreux projets de standardisation de la connaissance médicale
* Les terminologies gérées par le CGTS (via le SMT) s’articulent avec la doctrine du CGTS

Choisir un modèle de connaissances dynamiques standard
Cette activité est en relation avec le principe #4, [l’architecture tri-dimentionnel de Rector et al.](#archi-tri-dim) [15](#ref15) et les principes #1, #2, #3 et #5 énoncés en amont. Le modèle de connaissances dynamiques choisie pour standardiser l’écriture des artéfacts de connaissances médicales issues des GBPC est CQL [25](#ref25).

Ce choix est justifié pour plusieurs raisons :

* CQL s’articule avec l’ensemble des principes énoncés en amont
* CQL s’articule avec l’ensemble des autres standards choisis : UML, FHIR R4, CDS Hooks,…
* CQL s’articule avec les autres modèles correspondants au principe d’architecture tri-dimensionnelle de Rector et al. La figure 3 illustre l’instanciation de ce principe avec les différents modèles choisis pour la présente doctrine.
* CQL est actuellement utilisé par de nombreux projets de standardisation de la connaissance médicale
* CQL s’articule avec la doctrine du CI-SIS et la doctrine du CGTS

**FIGURE 3 : Instanciation du modèle de Rector et al. avec l’ensemble des standards utilisés dans le chemin nominal de la doctrine du SI-CM**

Choisir un standard d'intégration
Cette activité est en relation avec le principe #4, [l’intégration standardisée des SADC basés sur les GBPC dans un SI de santé](#integration-SADC). Le standard d’intégration de la connaissance médicale sous forme de SDAC choisi par l’ANS est le standard CDS Hooks [19](#ref19).

Ce choix est justifié pour plusieurs raisons :

* CDS Hooks s’articule avec l’ensemble des principes énoncés en amont
* CDS Hooks est le seul standard d’intégration de SAD basés sur la standardisation des GBPC qui puisse s’articuler avec les standards choisis dans le chemin nominal de la présente doctrine : UML, FHIR R4, CQL,…
* CDS Hooks est actuellement utilisé par de nombreux projets de standardisation de la connaissance médicale

Choisir une licence de publication
Cette activité est en relation avec le principe #3 et le principe #5 de la présente doctrine. Tous les artéfacts de connaissances médicales publiés dans le cadre du SI-CM doivent l’être sous la licence « Licence Ouverte Version 2.0 » (Lov2) d’Etalab [26](#ref26).

Ce choix est justifié pour plusieurs raisons :

* La licence « Licence Ouverte Version 2.0 » (Lov2) suit la logique du mouvement de l’Open Data
* La licence « Licence Ouverte Version 2.0 » (Lov2) est celle choisie par la doctrine du CGTS

Choisir un format de publication standard
Cette activité est en relation avec le principe #1, #2, #3 et #5 de la présente doctrine. Les artéfacts de connaissances médicales définis et / ou exposés dans le cadre du SI-CM doivent être publiés suivant le format FHIR ImplementationGuide (IG).

Ce choix est justifié pour plusieurs raisons :

* FHIR ImplementationGuide (IG) s’articule avec l’ensemble des principes énoncés en amont
* FHIR ImplementationGuide (IG) avec l’ensemble des standards choisis dans le cadre du chemin du nominal de la présente doctrine : UML, FHIR R4, CQL, …
* FHIR ImplementationGuide (IG) est actuellement utilisé dans de nombreux exemples de mises en œuvre de projet en lien avec la standardisation de la connaissance médicale
* FHIR ImplementationGuide (IG) s’articule avec la doctrine du CI-SIS

**Figure 4 : Diagramme d’activité UML pour illustrer les choix du chemin nominal de la doctrine du SI-CM et les possibles chemins secondaires**

##### Les chemins secondaires de la doctrine du SI-CM

Les choix effectués dans le chemin nominal de la présente doctrine ne sont pas et ne doivent pas être définitifs. Ces choix peuvent être remis en question pour de nombreuse raisons

* Le standard choisi n’est plus d’actualité
* Le standard choisi n’a pas évolué par rapport aux autres standards
* Il existe un ou plusieurs standards plus adaptés à un cas d’usage donné
* Un ou plusieurs principes de la présente doctrine ou de la doctrine du CI-SIS et/ou du CGTS ont évolué
* …

Il est donc nécessaire de laisser la porte ouverte à chaque étape de se poser la question de faire un autre choix de standard, d’outils ou autres méthodes. Pour cela, il est nécessaire que l’ensemble des parties prenantes

* Soient interrogés en cas de nouveaux choix effectués par l’ANS
* Aient la possibilité de proposer de nouveaux choix à l’ANS pour un cas d’usage donné

A l’image de la doctrine du CI-SIS ou de la doctrine du CGTS, la présente doctrine définie une procédure de consultation sur les différentes étapes où un autre choix est possible. La procédure de consultation comprend résolument les mêmes étapes que celles décrites dans la doctrine du CI-SIS [1](#ref1).

Les chemins secondaires #1, #2, #3, #4, #5, #6 et #8 décrits dans la figure 4 sont concernés par cette procédure de consultation.

Les choix faits au cours de ces chemins secondaires doivent impérativement respecter les principes de la présente doctrine. Ils doivent être des instances de ces principes, à l’image de l’instanciation du chemin nominal.

Le chemin secondaire #7 concerne la propriété intellectuelle des artéfacts de connaissances médicales produits et/ou exposés par le SI-CM. A l’image de la doctrine du CGTS [1](#ref1), un acteur de l’éco système peut décider de distribuer ses artéfacts de connaissances sous un autre régime de propriété intellectuelle que la Licence Lov2 choisie dans le chemin nominal de la présente doctrine. Ce choix de licence de diffusion résultera des négociations entre le SI-CM et l’Unité de Production (UP) lors de l’établissement de la convention de mise à disposition des artéfacts en question.

La notion d’UP et de conventions entre l’ANS et les UPs sont celles définies dans la gouvernance du CI-SIS [27](#ref27).

#### La relation avec la gouvernance

Cette doctrine respecte les étapes et les règles de gouvernance énoncés dans la gouvernance du CI-SIS [27](#ref27).

#### Références

 1. Le CI-SIS au cœur du développement de la e-santé [Internet]. [cited 2024 Aug 29]. Available from: [lien](https://interop.esante.gouv.fr/ig/doctrine/ImplementationGuide/ans.fr.doctrine) 

 2. Doctrine. In: Wikipédia [Internet]. 2024 [cited 2024 Aug 29]. Available from:[lien](https://fr.wikipedia.org/w/index.php?title=Doctrine&oldid=212118223) 

 3. LOI n° 2016-1321 du 7 octobre 2016 pour une République numérique. 2016-1321 Oct 7, 2016.

 4. GO FAIR [Internet]. [cited 2024 Aug 29]. FAIR Principles. Available from: [lien](https://www.go-fair.org/fair-principles/)

 5. Open data. In: Wikipedia [Internet]. 2024 [cited 2024 Aug 29]. Available from: [lien](https://en.wikipedia.org/w/index.php?title=Open_data&oldid=1238576109) 

 6. Open Data 5 étoiles [Internet]. [cited 2024 Aug 29]. Available from: [lien](http://5stardata.info/fr/)

 7. Gamma E, Helm R, Johnson R, Vlissides J. Design Patterns: Elements of Reusable Object-Oriented Software. 1er édition. Boston, Mass. Munich: Addison Wesley; 1994. 416 p. 

 8. Martin R. Clean Code: A Handbook of Agile Software Craftsmanship. 1er édition. Upper Saddle River, NJ: Pearson; 2008. 464 p.

 9. The Pragmatic Programmer: your journey to mastery, 20th Anniversary Edition, 2nd Edition[Book] [Internet]. [cited 2024 Aug 29]. Available from: [lien](https://www.oreilly.com/library/view/the-pragmatic-programmer/9780135956977/) 

 10. Martin RC. Agile Software Development: Principles, Patterns, and Practices. USA: Prentice Hall PTR; 2003. 710 p.

 11. Schreiber GT, Akkermans H. Knowledge engineering and management: the CommonKADS methodology. Cambridge, MA, USA: MIT Press; 2000. 

 12. giantchair.com. Artificial Intelligence: A Modern Approach - Pearson France [Internet]. [cited 2024 Aug 29]. Available from: [lien](https://www.pearson.fr/fr/book/?GCOI=27440100705580) 

 13. Ambler SW. The Object Primer: Agile Model-Driven Development With Uml 2.0. 3e édition. Cambridge, UK : New York: Cambridge University Press; 2004. 572 p.

 4. Rumbaugh J, Jacobson I, Booch G. Unified Modeling Language Reference Manual, The (2nd Edition). Pearson Higher Education; 2004.

 15. Rector AL, Johnson PD, Tu SW, Wroe C, Rogers J. Interface of Inference Models with Concept and Medical Record Models. In: Quaglini S, Barahona P, Andreassen S, editors. Artificial Intelligence Medicine, 8th Conference on AI in Medicine in Europe, AIME 2001, Cascais, Portugal, July 1-4, 2001, Proceedings [Internet]. Springer; 2001 [cited 2024 Aug 29]. p. 314–23. (Lecture Notes in Computer Science; vol. 2101). Available from: [lien](https://doi.org/10.1007/3-540-48229-6\_43) 

 16. Boxwala AA, Rocha BH, Maviglia S, Kashyap V, Meltzer S, Kim J, et al. A multi-layered framework for disseminating knowledge for computer-based decision support. Journal of the American Medical Informatics Association. 2011 Dec 1;18(Supplement_1):i132–9.

 17. Graham ID, Logan J, Harrison MB, Straus SE, Tetroe J, Caswell W, et al. Lost in knowledge translation: Time for a map? Journal of Continuing Education in the Health Professions. 2006;26(1):13–24. 

 18. Marcial LH, Blumenfeld B, Harle C, Jing X, Keller MS, Lee V, et al. Barriers, Facilitators, and Potential Solutions to Advancing Interoperable Clinical Decision Support: Multi-Stakeholder Consensus Recommendations for the Opioid Use Case. AMIA Annu Symp Proc. 2019;2019:637–46. 

 19. CDS Hooks [Internet]. [cited 2018 Apr 12]. Available from: [lien](http://cds-hooks.org/)

 20. Boussadi A, Caruba T, Zapletal E, Sabatier B, Durieux P, Degoulet P. A clinical data warehouse-based process for refining medication orders alerts. Journal of the American Medical Informatics Association. 2012 Sep 1;19(5):782–5. 

 21. Harris AD, McGregor JC, Perencevich EN, Furuno JP, Zhu J, Peterson DE, et al. The Use and Interpretation of Quasi-Experimental Studies in Medical Informatics. Journal of the American Medical Informatics Association. 2006 Jan 1;13(1):16–23

 22. About the Unified Modeling Language Specification Version 2.0 [Internet]. [cited 2024 Aug 29]. Available from: [lien](https://www.omg.org/spec/UML/2.0/)

 23. CPG Home - Clinical Practice Guidelines v2.0.0-ballot [Internet]. [cited 2024 Aug 30]. Available from: [lien](https://hl7.org/fhir/uv/cpg/2024Jan/)

 24. Http - FHIR v4.0.1 [Internet]. [cited 2021 Dec 1]. Available from: [lien](https://www.hl7.org/fhir/http.html)

 25. Clinical Quality Language (CQL) [Internet]. [cited 2024 Aug 30]. Available from: [lien](https://cql.hl7.org/)

 26. Etalab Licence Ouverte V2.0 [Internet]. 2017. Available from: [lien](https://www.etalab.gouv.fr/wp-content/uploads/2017/04/ETALAB-Licence-Ouverte-v2.0.pdf)

 27. Généralités sur la Gouvernance du CI-SIS [Internet]. [cited 2024 Aug 30]. Available from: [lien](https://interop.esante.gouv.fr/ig/doctrine/ImplementationGuide/ans.fr.doctrine)

 28. Michaels M. Adapting Clinical Guidelines for the Digital Age: Summary of a Holistic and Multidisciplinary Approach. American Journal of Medical Quality. 2023 Oct;38(5S):S3.</a>

