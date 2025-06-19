<p style="padding: 5px; border-radius: 5px; border: 2px solid maroon; background: #ffffe6; width: 65%">
<b>Brief description of this Implementation Guide</b><br>
The interoperability framework for health information systems (CI-SIS) sets the rules for exchanging and sharing health data on the same standards. It is managed by the ANS in collaboration with the entire ecosystem. This implementation guide outlines the doctrine and governance that apply to this framework.
</p>
<!-- 
<div class="figure" style="width:65%;">
    <img style="height: auto; width: 100%;" src="ci-sis-logo.png" alt="CI-SIS" title="Logo du CI-SIS">
</div> -->

<div xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://www.w3.org/1999/xhtml ../../schema/fhir-xhtml.xsd" xmlns="http://www.w3.org/1999/xhtml">

{% if site.data.info.releaselabel == 'ci-build' %}
<div style="width: 65%">
<blockquote class="stu-note">
<p>
  <b>Attention !</b> Cette version de l'Implementation Guide est en intégration continue (version de travail) et est soumise à des changements réguliers. Après première publication, la version officielle sera accessible à l'adresse https://interop.esante.gouv.fr/ig/fhir/doctrine</b>
</p>
</blockquote>
</div>
{% endif %}

L’Agence du Numérique en Santé (ANS) accompagne la transformation numérique du système de santé aux côtés de tous les acteurs concernés des secteurs sanitaire, social et médico-social, privés comme publics, professionnels ou usagers.  Elle met en œuvre les orientations dédiées au secteur de la santé et du médico-social, à travers trois ambitions.

<div>
    <ul>
        <li><b>Régulatrice</b> : elle améliore la performance numérique grâce à des règles communes de régulation et d’échanges ; </li>
        <li><b>Opératrice</b> : elle conçoit les grands e-programmes nationaux pour un service public de santé efficace et solidaire ; </li>
        <li><b>Promotrice et valorisatrice</b> : elle stimule, accompagne et évalue toutes les initiatives de e-santé pour les faire grandir. </li>
    </ul>
</div>

Dans le rôle de **régulateur** ayant pour ambition de développer la capacité des systèmes d’information en santé à partager et échanger des données de santé de manière fluide, efficace et sécurisée, l’Agence porte la construction d’un cadre commun comprenant l’interopérabilité, la sécurité et l’éthique, permettant ainsi le développement de la e-santé entre l’ensemble des acteurs, et en particulier avec les solutions de la puissance publique, dans le cadre retenu de l’Etat-plateforme.
Ce cadre commun sur l’interopérabilité :

<div>
    <ul>
        <li>Soutient la dématérialisation des processus en santé, en permettant d’apporter de la valeur ajoutée via le numérique en santé</li>
        <li>Est au profit des patients, de leur prise en charge, des parcours de soin</li>
        <li>Est aussi au profit des professionnels de santé et des établissements de santé, afin de permettre la généralisation, le passage à l’échelle, de cas d’usage métier où le numérique en santé contribue à apporter de la valeur ajoutée dans leurs pratiques</li>
        <li>S’adresse tout particulièrement aux ENS (Entreprises du Numérique en Santé) pour l’implémentation de ce cadre commun dans leurs solutions qui peuvent alors échanger et partager de manière plus fluide, efficace et sécurisée des données de santé. Les ENS peuvent ainsi industrialiser les déploiements et aussi proposer des services à valeur ajoutée (toujours dans le cadre de l’Etat-plateforme)</li>
    </ul>
</div>

Ce cadre commun d’interopérabilité, le CI-SIS (Cadre d’Interopérabilité des Systèmes d’Information de Santé) :

<div>
    <ul>
        <li>comprend l’ensemble des spécifications définissant les informations à échanger ou partager entre les systèmes d’information de santé et identifie la norme ou le standard le plus approprié à utiliser pour cet échange ou partage : c’est ce qu’on appelle « l’interopérabilité technique »</li>
        <li>via la définition de la structuration du contenu médical, il identifie le langage adéquat pour présenter des informations selon les standards et les normes reconnus ainsi que le vocabulaire à utiliser pour coder l’information. Ceci permet de faciliter le traitement automatique de l’information et permet la mise en œuvre de services à valeur ajoutée. C’est ce qu’on appelle « l’interopérabilité syntaxique et sémantique »</li>
    </ul>
</div>

### Les enjeux du développement du CI-SIS

Afin de répondre à ces ambitions, la construction de ce cadre comme d’interopérabilité, le CI-SIS doit relever plusieurs enjeux, dont tout particulièrement :


<div>
    <ul>
        <li>S’assurer de répondre à des <b>cas d’usage prioritaires</b> (feuille de route du numérique en santé, etc), avec l’identification de ces cas d’usage, leur priorisation et un contrôle de la pertinence de la réponse technique au besoin ;</li>
        <li>S’inscrire dans un <b>cadre résolument international</b>, en particulier avec les travaux IHE, HL7, DICOM, de façon à bénéficier des travaux réalisés de ces communautés et de limiter ainsi le coût d’implémentation de la déclinaison française de l’interopérabilité. En complément, avec la mise en œuvre de l’EEDS (Espace Européen des Données de Santé), le cadre européen d’interopérabilité s’imposera aussi aux Etats membres, qui sera donc évidemment repris dans le CI-SIS</li>
        <li>Garantir la <b>co-construction de ce cadre commun</b>, en s’assurant que chacun puisse être acteur aux différents niveaux : identification de cas d’usage, formalisation précise du besoin, propositions techniques, expérimentations et retours terrain, etc</li>
        <li>Maintenir <b>une lisibilité d’un CI-SIS</b> en croissance, en particulier sur les contributions attendues et leurs modalités mais aussi sur le contenu validé et son niveau de maturité, i.e. la confiance dans sa capacité à répondre au besoin</li>
        <li>Construire et opérer <b>un outillage permettant de valider la bonne implémentation</b> des référentiels du CI-SIS dans les solutions des ENS, de façon à </li>
        <ul>
            <li>permettre un déploiement industrialisé qui passe à l’échelle,</li>
            <li>faciliter la lisibilité des ES/PS dans le choix de leurs solutions</li>
        </ul>
        <li><b>promouvoir, valoriser</b> le contenu du CI-SIS et <b>accompagner</b> les acteurs dans la mise en œuvre via des webinaires et aussi de l’outillage de tests, la réalisation de tests techniques lors des projectathons, la réalisation de pilotes (et projectathons usage) permettant de <b>tester</b> les solutions, les référentiels du CI-SIS et <b>l’adéquation aux cas d’usage</b> et d’intégrer ces éléments dans l’évolution du CI-SIS</li>
    </ul>
</div>

Les différentes réponses à ces enjeux du cadre commun CI-SIS sont ainsi portées par :

<div>
    <ul>
        <li><b>Une doctrine du CI-SIS</b> qui formalise les règles régissant la constitution et l’évolution du contenu du CI-SIS : trajectoire générale de l’interopérabilité, choix des normes et standards, cycle de vie des référentiels, modalités de contribution et concertation de l’écosystème, formalisation du contenu des référentiels</li>
        <li><b>Une gouvernance du CI-SIS</b> qui favorise la co-construction, instruit et arbitre les priorités des travaux et évolutions du CI-SIS par rapport aux cas d’usage et donne de la visibilité aux différents acteurs sur les orientations stratégiques du CI-SIS.</li>
    </ul>
</div>

### Une évolution volontariste dans la continuité

Sous l’impulsion de la première feuille de route du numérique en santé (masanté 2022), du Ségur numérique, et d’évolutions réglementaires récentes au niveau français et européen, l’interopérabilité et le rôle de régulation de l’Agence évoluent fortement :

<div>
    <ul>
        <li>A travers le <b>Ségur numérique</b> Vague 1 ont été mis en place de manière massive les « canaux » de partage et d’échange de données de santé via MES/DMP et la MSSanté. Si la consultation du DMP dans les logiciels des PS sera développée / améliorée avec la Vague 2, le focus devrait ainsi se porter <b>à court terme sur le développement de cas d’usage</b> via le numérique en santé (et moins sur des sujets technique de mise en place de ces canaux) ;</li>
        <li>Le rôle de l’Agence <b>en tant que régulateur</b> du numérique en santé sur les champs de l’interopérabilité, de la sécurité et de l’éthique a été confirmé, en particulier dans la mission de contrôle de conformité des solutions aux référentiels, ayant vocation à être complété à court terme par un dispositif de sanction ;</li>
        <li><b>La mise en œuvre de l’EEDS et d’un futur cadre européen de l’interopérabilité</b>, impliquant de promouvoir le cadre déjà mis en œuvre au niveau national, mais aussi d’assurer la transition vers le future cadre européen. Il sera aussi nécessaire de poursuivre le développement des outils permettant de valider de manière automatique la conformité des solutions des ENS ;</li>
        <li><b>Le développement des EDS</b> (Entrepôts de Données de Santé) et de l’usage secondaire des données de santé, porté aussi fortement par l’EEDS, met directement en exergue le besoin de qualité des données numériques de santé, et donc d’interopérabilité ;</li>
        <li><b>L’IA en santé</b> ouvre aussi des perspectives particulièrement stimulantes pour l’interopérabilité</li>
    </ul>
</div>

Alors que le CI-SIS existe depuis de nombreuses années, que la gouvernance a déjà été revue, il apparait ainsi important de s’engager dans une évolution de la doctrine du CI-SIS et de sa gouvernance via des propositions d’adaptation et de renforcement, dans une approche :

<div>
    <ul>
        <li>résolument volontariste, afin de répondre concrètement aux enjeux et fortes attentes des prochains mois et années du numérique en santé</li>
        <li>dans la continuité, en capitalisant sur les efforts déjà consentis et les réussites du CI-SIS.</li>
    </ul>
</div>

### Glossaire

Les termes suivants sont utilisés dans ce document et peuvent nécessiter des besoins de précisions :

<div>
    <ul>
        <li>CGTS : Centre de Gestion des Terminologies de Santé. C’est le guichet national de diffusion des terminologies en usage en France.</li>
        <li>Terminologies : Ensemble des ressources sémantiques telles que les terminologies, classifications, nomenclatures, ontologies, jeux de valeurs, alignements sémantiques etc.</li>
        <li> Interopérabilité syntaxique ou technique : capacité de différents systèmes ou applications à échanger des données en respectant un même format et des protocoles standardisés (ex : XML, JSON, HL7 v2, HL7 FHIR). Elle garantit que les données peuvent être correctement envoyées, reçues et traitées, mais sans assurer qu'elles aient le même sens pour tous les systèmes. L'interopérabilité sémantique intervient ensuite pour donner un sens commun aux données échangées.</li>
        <li>Interopérabilité sémantique : capacité des systèmes à interpréter et comprendre les données échangées de manière identique et cohérente. Elle repose sur des vocabulaires contrôlés, des ontologies et des terminologies (ex : SNOMED CT, LOINC) pour assurer une compréhension commune du sens des informations échangées.</li>
        <li>Volet du CI-SIS : spécification d'interopérabilité qui peut être au format PDF ou guide d'implémentation (IG)</li>
        <li>IHE : Integrated The Healthcare Enterprise, initiative internationale qui a pour but d’améliorer l’interopérabilité dans le domaine de la santé.</li>
        <li>Profil IHE : Les profils IHE décrivent des solutions spécifiques aux problèmes d'interopérabilité. Les profils précisent comment les « acteurs » utilisent les normes/standards pour traiter un cs d'utilisation spécifique des soins de santé.</li>
    </ul>
</div>
