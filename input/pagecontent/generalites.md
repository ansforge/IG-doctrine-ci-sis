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