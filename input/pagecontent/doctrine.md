En tant qu’opérateur public au service de la santé numérique, l’ANS assure trois missions complémentaires :

<div>
    <ul>
        <li>Créer les conditions de l’essor de la e-santé ;</li>
        <li>Conduire des projets d’envergure nationale ;</li>
        <li>Déployer les usages en soutenant l’innovation.</li>
    </ul>
</div>

La création des conditions de l’essor de la e-santé, objet de la première mission de l’ANS, repose sur la définition d’un cadre dans lequel les services de e-santé peuvent se développer librement avec la capacité d’interagir aisément, de manière sécurisée avec l’ensemble des systèmes d’information du secteur et de manière éthique.

Du point de vue de la sécurité, ce cadre repose sur la mise en œuvre de règles et de bonnes pratiques identifiées dans la [Politique Générale de Sécurité des Systèmes d’Information de Santé (PGSSI-S)](https://esante.gouv.fr/produits-services/pgssi-s) et sur l’agrément des hébergeurs de données de santé.

Du point de vue de l’éthique, ce cadre repose sur la mise en œuvre de principes éthiques et humanistes identifiés dans le [Cadre de l’éthique du numérique en santé (CENS)](https://esante.gouv.fr/produits-services/referentiel-ethique).

En ce qui concerne l’interopérabilité, il repose sur l’identification et la compréhension partagée des concepts « métier » (ou objets) correspondant aux informations manipulées par les systèmes d’information de santé (ex. acteurs de santé, qu’ils soient une personne physique ou personne morale, patients, offre de soins…). Ces concepts sont catalogués dans le [Modèle des Objets de Santé (MOS)](https://mos.esante.gouv.fr/0.html). Utile pour la conception des systèmes d’information, l’utilisation des objets de santé pour la modélisation des échanges entre systèmes d’information est également une étape préalable à leur spécification dans une logique d’urbanisation sectorielle. Le Cadre d’Interopérabilité des Systèmes d’Information de Santé (CI-SIS) traduit cette modélisation en spécifications d’interopérabilité sémantiques, syntaxiques et techniques.

Publié initialement par l’ANS en 2009 et régulièrement mis à jour depuis, le CI-SIS est destiné aux opérateurs de maîtrise d’œuvre au sens large (éditeurs de logiciel, intégrateurs…) ainsi qu’aux opérateurs de maitrise d’ouvrage. Il a été basé sur des normes et standards internationaux d’échange utilisés dans le secteur de la santé de manière à assurer :

<div>
    <ul>
        <li> Une adéquation avec les besoins du secteur : les normes et standards utilisés ont été conçus pour la mise en œuvre de cas d’usage relatifs à la prise en charge des usagers ;</li>
        <li> Une réutilisabilité des développements avec un minimum d’efforts d’adaptation pour différents cas d’usage que ce soit au niveau national ou au-delà du marché français.</li>
    </ul>
</div>

Initialement orienté sur les cas d’usage correspondant aux principaux projets numériques d’échange et de partage portés par l’agence lors de sa création en 2009, c’est-à-dire le DMP et MSSanté, le CI-SIS est longtemps resté cantonné à ces cas d’usage, pour lesquels les orientations suivies en termes de normes et standards avaient été définies avec l’ensemble des parties prenantes (représentants des industriels, utilisateurs, institutionnels…) lors d’une phase de conception qui a duré un peu plus d’un an.
Arrivé à maturité sur son périmètre initial, le CI-SIS doit évoluer de façon constante de façon à être utile à l’ensemble du secteur sanitaire et medico-social. C’est le but de la nouvelle gouvernance mise en œuvre depuis fin 2024.

La construction progressive du CI-SIS répond aux orientations stratégiques définies et mises à jour régulièrement par la gouvernance du CI-SIS et à la feuille de route d’interopérabilité résultant.
Cette gouvernance est conçue pour faciliter et maîtriser la multiplication des cas d’usage pris en compte dans le CI-SIS. Il s’agit à la fois d’augmenter le nombre des cas d’usage couverts par le CI-SIS tout en assurant une stabilité des spécifications, et de donner aux acteurs de la visibilité à long terme. À cette fin, une stratégie globale doit être définie et intégrée dans une doctrine publique sur la méthode d’évolution et la méthodologie de choix des normes et standards internationaux applicables au développement du CI-SIS.

Ce document a pour objectif de présenter cette doctrine ainsi que son articulation avec la gouvernance du CI-SIS. Après un rappel des enjeux de l’interopérabilité pour les concepteurs et les utilisateurs de systèmes d’information, ce document présente les composants de la doctrine en indiquant en quoi ceux-ci répondent aux enjeux, avant de détailler l’articulation avec la gouvernance du CI-SIS.

### Enjeux de l'interopérabilité et du CI-SIS

La dématérialisation des processus est un enjeu décisif pour les secteurs sanitaire, médico-administratif, médico-social et social. Vecteur d’optimisation de la prise en charge tant au niveau organisationnel qu’au niveau économique, cette dématérialisation nécessite des investissements souvent importants aussi bien de la part des opérateurs de maîtrise d’œuvre que de la part des opérateurs de maitrise d’ouvrage, non seulement en termes de spécifications et de développement mais également en termes de formation sur les technologies, ainsi que sur les normes et standards d’échange utilisés.

Afin de rentabiliser ces investissements, il est important que les spécifications des échanges entre SI :

<div>
    <ul>
        <li> Soient adaptées aux cas d’usage métier initiaux ;</li>
        <li> Puissent être réutilisées dans d’autres cas d’usage pour le même contexte ou dans d’autres contextes (par exemple pour des mises en œuvre en dehors du contexte français) ;</li>
        <li> Bénéficient d’une certaine stabilité</li>
    </ul>
</div>

Les normes et standards internationaux utilisés dans les secteurs concernés peuvent constituer un premier niveau tendant vers l’atteinte de ces objectifs. Cependant, ils sont trop divers, trop larges et ont une couverture trop incomplète de l’ensemble des cas d’usage pour pouvoir donner la visibilité à long terme recherchée.

Dans l’optique de réduire cette diversité, les profils internationaux ont pour vocation de guider la mise en œuvre des normes et standards généraux dans le contexte de cas d’usage identifiés. C’est le cas par exemple des profils WS ou SAML qui détaillent la mise en œuvre des standards correspondants pour des cas d’usage génériques d’échange entre systèmes d’information.
Les profils internationaux peuvent également être plus détaillés pour être adaptés à un domaine en particulier. Les organisations internationales HL7, IHE et Continua Alliance, par exemple, produisent des profils adaptés aux cas d’usage du domaine de la santé.

Enfin, les profils nationaux ont pour objectif d’adapter aux contextes nationaux les profils internationaux lorsqu’ils existent ou, à défaut, les normes et standards internationaux techniques et sémantiques. En France, le [Référentiel Général d’Interopérabilité (RGI)](https://www.numerique.gouv.fr/publications/interoperabilite) constitue par exemple une adaptation nationale pour des cas d’usage génériques d’échange entre systèmes d’information. Il est censé être en adéquation avec le Cadre d’interopérabilité européen (European Interoperability Framework – EIF).

Dans le domaine de la santé, le CI-SIS regroupe les profils opérationnels correspondant aux cas d’usage français. Il est basé sur des profils IHE ou des guides d’implémentation HL7 FHIR internationaux lorsqu’ils existent ou, à défaut, sur des normes et standards internationaux.

Dans le futur, il est possible que le CI-SIS soit également basé sur des spécifications publiées par d’autres organisations qui font autorité au niveau international telles que l’OMS, les accélérateurs de projets européens/internationaux ou au niveau national avec des organisations telles que [EDESS](http://www.edess.org/joomla/index.php) ou [InteropSanté](https://www.interopsante.org/). Cette dernière possibilité pourrait être envisagée uniquement pour des standards nationaux ouverts et libres de droits.

Le CI-SIS est également en cohérence avec les orientations du RGI et du [cadre d’interopérabilité européen](https://ec.europa.eu/isa2/sites/default/files/eif_brochure_final.pdf) (European Interoperabilty Framework – EIF) et identifie formellement les cas où les spécificités des cas d’usage santé nécessitent de s’en écarter.

<div class="figure" style='text-align: center;'>
    <img src="positionnement-profil-fr.jpg" alt="CP" title="Exemple (non exhaustif) de positionnement de profils français et internationaux par rapport aux normes et standards" style="width:80%;">
    <figcaption><b>Exemple (non exhaustif) de positionnement de profils français et internationaux par rapport aux normes et standards</b></figcaption>
</div>

Par exemple :

<div>
    <ul>
        <li> Pour le cas d’usage de partage de document de santé, le CI-SIS constitue le profil français du profil IHE XDS (Cross Enterprise Document Sharing) qui est lui-même une adaptation du standard ebXML d’OASIS pour les cas d’usage de partage de documents dans le domaine de la santé ;</li>
        <li> Pour le cas d’usage de la transmission des données d’identité pour la mise en œuvre de droits d’accès, le VIHF (Vecteur d’Identification et d’Habilitation Formelles) du CI-SIS est basé sur le profil IHE XUA (Cross Enterprise User Assertion) lui-même basé sur le token profile pour le standard SAML d’OASIS ;</li>
        <li> Pour le cas d’usage du compte-rendu de rétinographie, en l’absence de profil international, le volet du CI-SIS est un profil français directement basé sur la norme CDA éditée par HL7 ;</li>
        <li> Pour le cas d’usage du partage de données de santé en mobilité, le volet du CI-SIS est basé sur le profil IHE MHD (Mobile access to Health Documents).</li>
    </ul>
</div>

Ainsi, le Cadre d’Interopérabilité des systèmes d’information de santé (CI-SIS) a pour objectif clé de développer la capacité des systèmes d’information à échanger/partager des données de manière naturelle sans développements informatiques complexes et coûteux. 
Il est constitué d’un ensemble de spécifications qui définit les informations à échanger/partager entre les systèmes d’information de santé et identifie la norme ou le standard le plus approprié à utiliser pour cet échange/partage.

Par la définition des interactions entre les systèmes d’information, le CI–SIS décrit des mécanismes d’échanges et de partage ainsi que leurs contenus en utilisant des standards internationaux ouverts mis en cohérence avec le contexte français. C’est ce qu’on appelle « l’interopérabilité technique »

Par la définition de la structuration du contenu médical, le CI–SIS permet d’identifier le langage adéquat pour présenter des informations selon les standards et les normes reconnus ainsi que le vocabulaire à utiliser pour coder l’information (interopérabilité sémantique). Ceci permet de faciliter le traitement automatique de l’information et permet la mise en œuvre de services à valeur ajoutée. C’est ce qu’on appelle « l’interopérabilité syntaxique et sémantique ».

De nature à favoriser l’adéquation opérationnelle des profils français du domaine de la santé, du medico-social et social, aux cas d’usage métier, ce positionnement de fait nécessite une formalisation au sein d’une doctrine d’interopérabilité afin de fournir une meilleure visibilité aux parties prenantes sur les orientations du CI-SIS en termes de normes et standards techniques, syntaxiques et sémantiques.

<!-- ## Guide de lecture pour novices -->

<!-- TODO -->

### La doctrine du CI-SIS

La doctrine du CI-SIS a pour objectif de formaliser les orientations suivies par le CI-SIS en termes de normes et standards dans le cas général et de fournir un processus de détermination des normes et standards à suivre lorsque le cas d’usage considéré ne peut pas être mis en œuvre via ces orientations. Une fois validée par les acteurs du domaine, elle permet de s’affranchir d’une consultation préalable à l’élaboration des spécifications d’interopérabilité lorsqu’un besoin d’interopérabilité peut être pris en compte par une norme ou un standard déjà existant dans les orientations du CI-SIS. Elle ne change pas le processus d’élaboration des spécifications d’interopérabilité qui sont soumises à concertation publique, qu’il y ait eu une consultation préalable ou non sur les normes/standards.

La doctrine d’interopérabilité technique et syntaxique du CI-SIS peut être synthétisée par les règles suivantes :

<div>
    <ul>
        <li> Utilisation d'un profil IHE ou d'un guide d'implémentation FHIR adapté et stable ;</li>
        <li> A défaut, réutilisation des normes et standards déjà utilisés dans le CI-SIS pour des cas d'usage similaires ;</li>
        <li> A défaut, consultation des acteurs pour identification de la norme ou du standard à utiliser pour prendre en compte le besoin d'interopérabilité.</li>
    </ul>
</div>

La doctrine d’interopérabilité sémantique du CGTS s’inscrit dans la doctrine d’interopérabilité du CI-SIS en termes de terminologies de référence à retenir :

<div>
    <ul>
        <li> Utilisation d'une terminologie de référence déjà utilisée en France et alignement, le cas échéant avec la terminologie de référence retenue par le niveau européen ;</li>
        <li> A défaut, recherche d'une terminologie européenne ;</li>
        <li> A défaut, consultation des acteurs pour identification de la terminologie de référence à utiliser pour prendre en compte le beosin d'interopérabilité et création de jeux de valeurs ad hoc.</li>
    </ul>
</div>

Dans un futur proche, une doctrine d’interopérabilité pour les cas d’usage d’aide à la décision clinique viendra compléter la doctrine du CI-SIS.

L’ensemble des spécifications d’interopérabilité (au sein du Cadre d’Interopérabilité des Systèmes d’Information de Santé (CI-SIS)) et des terminologies constitue un bien commun, qui respecte les principes de transparence, de collaboration, de participation et d’éthique.

<div class="figure" style='text-align: center;'>
    <img src="doctrine.png" alt="CP" title="Principes généraux de la doctrine d’interopérabilité" style="width:80%;">
    <figcaption><b>Principes généraux de la doctrine d’interopérabilité</b></figcaption>
</div>

### Choix des profils IHE et des guides d’implémentation FHIR comme base de la doctrine d’interopérabilité syntaxique

Les profils IHE  et les guides d’implémentation FHIR d’HL7 sont des spécifications opérationnelles d’interopérabilité qui indiquent comment utiliser des normes/standards stables et « vivants » dans le cadre de cas d’usage des domaines sanitaire, medico-social et social. Ce travail d’analyse et de sélection des normes/standards ainsi que la prise en compte des spécificités des cas d’usage de ces domaines en font une base de départ adaptée pour les spécifications du CI-SIS, qui n’ont plus qu’à contraindre ces profils et ces guides d’implémentation en fonction du contexte français.

Cette adéquation est également reconnue au niveau européen. En effet, le 28 juillet 2015 la Commission Européenne a identifié 27 profils IHE pouvant servir de référence dans la passation de marchés publics, profils qui ont été intégrés au cadre d’interopérabilité européen. Ces profils sont présentés [dans ce tableau](Liste_Profils_IHE_Standards.xls).

Ces éléments ont amené à considérer les profils IHE ainsi que les guides d’implémentation FHIR comme base de la doctrine du CI-SIS. Pour autant, toutes ces spécifications n’ont pas un niveau de maturité suffisant pour constituer une base solide :

<div>
    <ul>
        <li> Certains profils IHE ne sont plus utilisés sur le terrain et pas encore retirés des spécifications IHE (ex. le profil Patient Synchronized Application basé sur le standard CCOW) ;</li>
        <li> Certains profils IHE en trial implementation ne sont pas encore tout à fait stables (ex. les profils qui n’ont pas encore eu l’occasion d’être testés lors d’un Connectathon).</li>
    </ul>
</div>

Les profils et les guides d’implémentation FHIR choisis pour constituer la base de la doctrine du CI-SIS sont donc :

<div>
    <ul>
        <li> Les profils IHE en final text régulièrement testés au connectathon et/ou bénéficiant d’une communauté active ;</li>
        <li> Les profils IHE en trial implementation depuis plusieurs années, régulièrement testés au connectathon  et/ou bénéficiant d’une communauté active, et ne faisant pas l’objet de change proposals (CP)  structurant et dont l’intégration en final text est prévue à court terme (ex. en attente d’outils de test automatisés).</li>
        <li> Les guides d’implémentation FHIR au statut Trial use ou Normative.</li>
    </ul>
</div>

D’autre part, dans le cadre du règlement relatif à l’espace Européen des données de santé (EHDS), le réseau eHealth Network, sous l’égide de la Commission Européenne, définit des normes et standards internationaux et des spécifications techniques s’adressant aux entreprises du numérique en santé des états membres, précisant l’implémentation de ces normes et standards au fur et à mesure de la construction de cet espace Européen des données de santé. En particulier, EHDS est basé sur un format d’échange des données de santé (EEHRxF) constitué à ce jour des guidelines suivantes :

<!-- Insérer le lien sur les guidelines -->
<div>
    <ul>
        <li>ePrescription and eDispensation,</li>
        <li>Patient Summary,</li>
        <li>Laboratory results and reports,</li>
        <li>Medical imaging studies and reports,</li>
        <li>Hospital discharge reports.</li>
    </ul>
</div>

Les dernières guidelines publiées dans ce cadre introduisent en particulier le standard Fast Health Interoperable Resources (FHIR) d’HL7. Ces guidelines sont ensuite déclinées en guides d’implémentation FHIR qui précisent l’implémentation opérationnelle des cas d’usage adressés.

### Réutilisation des normes et standards déjà utilisés dans le CI-SIS

Afin de répondre aux enjeux de stabilité et de réutilisation, lorsqu’il n’existe pas de profil IHE ou de guide d’implémentation FHIR adapté à un cas d’usage, les normes et standards déjà utilisés dans le CI-SIS pour d’autres cas d’usage sont réutilisés s’ils sont adaptés.

Par exemple, la norme CDA a été initialement utilisée dans les spécifications de plusieurs volets tels que :

<div>
    <ul>
        <li>Structuration Minimale de Documents Médicaux (basé sur le profil IHE XDS-SD) ;</li>
        <li>Compte rendu d’Examens de Biologie Médicale (basé sur le profil IHE XD-Lab) ;</li>
        <li>Compte Rendu Structuré d’Anatomie et de Cytologie Pathologiques (basé sur le profil IHE APSR).</li>
    </ul>
</div>

Ainsi, afin de capitaliser l’expérience acquise par les parties prenantes et de favoriser la réutilisation des développements et en l’absence de contrainte spécifique du cas d’usage qui rendrait son utilisation inadaptée, la norme CDA reste à ce jour la norme à profiler pour les spécifications du CI-SIS concernant des documents structurés.

Cependant, l’ANS a défini une [trajectoire d’interopérabilité](./trajectoire-iop.html) qui tient compte des orientations retenues par la Commission Européenne dans le cadre de la construction de l’espace de données de santé européen (European Health Data Space - EHDS). Une de ces orientations concerne l’utilisation du standard FHIR en remplacement ou en complément de CDA pour les documents structurés.

La liste des normes et standards utilisés dans le CI-SIS évolue constamment à la faveur de la production de nouveaux volets du CI-SIS. A titre d’information, les normes et standards qui sont utilisés dans le CI-SIS en septembre 2024 sont présentés [ici](iste_Profils_IHE_Standards.xls).

### Choix des normes et standards non encore utilisés dans le CI-SIS

La doctrine du CI-SIS ne peut pas couvrir l’ensemble des cas d’usage faisant l’objet d’une spécification d’interopérabilité. Quand il est nécessaire de sélectionner une norme ou un standard (syntaxique, sémantique ou technique) cible qui n’est pas encore utilisé dans le CI-SIS, il est indispensable que l’ensemble des parties prenantes qui pourraient être affectées par ce choix :

<div>
    <ul>
        <li>Soient informées sur les normes et standards utilisables pour la mise en œuvre du cas d’usage ;</li>
        <li>Aient la possibilité de détailler les impacts de ces normes et standards en ce qui les concernent (ex. standard non conforme avec les politiques industrielles des éditeurs) ;</li>
        <li>Aient la possibilité de proposer des normes ou des standards qu’ils estiment adaptés.</li>
    </ul>
</div>

Dans ce cas, la doctrine est donc complétée par une procédure de consultation sur les normes et standards pour les cas d’usage non couverts par des profils IHE, par des guides d’implémentation FHIR d’HL7 adaptés ou par des normes et standards déjà utilisés dans le CI-SIS.

Cette consultation s’organise en 6 étapes :

<div>
    <ul>
        <li> Recensement des normes et standards utilisables pour la mise en œuvre du cas d’usage par les experts du CI-SIS ;</li>
        <li> Analyse comparative des normes et standards utilisables par les experts du CI-SIS ;</li>
        <li> Lancement de la consultation par diffusion de l’analyse comparative aux parties prenantes ;</li>
        <li> Recueil des commentaires des parties prenantes sur l’analyse comparative ;</li>
        <li> Mise à jour de l’analyse comparative par les experts du CI-SIS et recommandations ;</li>
        <li> Présentation de l’analyse comparative et des recommandations aux parties prenantes et décision sur la norme ou le standard à utiliser.</li>
    </ul>
</div>

Ces différentes étapes sont détaillées dans les schémas de la section suivante.

### Articulation de la doctrine d’interopérabilité avec la gouvernance du CI-SIS

La doctrine est complètement intégrée à la gouvernance du CI-SIS. Elle vient se positionner en entrée de la phase 4 de l’instruction de la gouvernance lors du choix de la syntaxe et de la sémantique cibles à utiliser dans les spécifications d’interopérabilité.

<div class="figure" style='text-align: center;'>
    <img src="phase-gouv.png" alt="CP" title="Niveaux Rappel des phases de la gouvernance du CI-SIS" style="width:80%;">
    <figcaption><b>Niveaux Rappel des phases de la gouvernance du CI-SIS</b></figcaption>
</div>

En y intégrant les éléments de la doctrine syntaxique et sémantique, la phase d’évolution du CI-SIS (phase 4) se décompose en 5 sous-phases :

<div>
    <ul>
        <li>A. Analyse métier du cas d’usage, modélisation des échanges entre SI conformément à la [méthodologie d’élaboration des spécifications fonctionnelles des échanges](./elaboration.html), et choix de terminologie(s) de référence répondant au cas d’usage étudié selon les principes de la doctrine sémantique ;</li>
        <li>B. Concertation publique sur la spécification fonctionnelle des échanges (intégrant les choix de terminologies) ;</li>
        <li>C. Choix de la norme ou du standard syntaxique selon les principes de la doctrine syntaxique ;</li>
        <li>D. Rédaction des spécifications techniques d’interopérabilité par correspondance entre les échanges modélisés et la syntaxe cible assortie des règles de mise en œuvre tel que définies dans la norme ou le standard choisi ;</li>
        <li>E. Concertation publique sur la modélisation des échanges et les spécifications d’interopérabilité correspondantes et finalisation des spécifications.</li>
    </ul>
</div>

<div class="figure" style='text-align: center;'>
    <img src="sous-phase-evo.png" alt="CP" title="Sous phases de la phase d’évolution du CI-SIS" style="width:80%;">
    <figcaption><b>Sous phases de la phase d’évolution du CI-SIS</b></figcaption>
</div>

<!-- IGI - Schéma modifié par rapport à l’original pour insérer la phase de concertation publique de l’étude fonctionnelle des échanges -->

Ces travaux peuvent être faits en collaboration avec l'écosystème via une contractualisation sous forme d'[Unité de Production externe](./up-externe.html).

### Doctrine de la connaissance médicale

{% include connaissance-medicale.md %}