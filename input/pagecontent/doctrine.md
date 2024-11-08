---
title: La doctrine du cadre d'interopérabilité
nav_order: 2
description:
---

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


## Doctrine d’interopérabilité syntaxique et doctrine d’interopérabilité sémantique

La doctrine du CI-SIS a pour objectif de formaliser les orientations suivies par le CI-SIS en termes de normes et standards dans le cas général et de fournir un processus de détermination des normes et standards à suivre lorsque le cas d’usage considéré ne peut pas être mis en œuvre via ces orientations. Une fois validée par les acteurs du domaine, elle permet de s’affranchir d’une consultation préalable à l’élaboration des spécifications d’interopérabilité lorsqu’un besoin d’interopérabilité peut être pris en compte par une norme ou un standard déjà existant dans les orientations du CI-SIS. Elle ne change pas le processus d’élaboration des spécifications d’interopérabilité qui sont soumises à concertation publique, qu’il y ait eu une consultation préalable ou non sur les normes/standards.

La doctrine d’interopérabilité technique et syntaxique du CI-SIS peut être synthétisée par les règles suivantes :

<div>
    <ul>
        <li> Utilisation d'un profil IHE ou d'un guide d'implémentation FHIR adapté et stable ;</li>
        <li> A défaut, réutilisation des normes et standards déjà utilisés dans le CI-SIS pour des cas d'usage similaires ;</li>
        <li> A défaut, consultation dse acteurs pour identification de la norme ou du standard à utiliser pour prendre en compte le besoin d'interopérabilité.</li>
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

<!-- 
## Doctrine d'open semantique

TODO - Faut-il l’intégrer à la doctrine du CI-SIS ? Si oui, à reprendre du document constitutif du CGTS. 
A noter qu'il manque la partie doctrine d'open semantique ici.

-->

## Choix des profils IHE et des guides d’implémentation FHIR comme base de la doctrine d’interopérabilité syntaxique

Les profils IHE  et les guides d’implémentation FHIR d’HL7 sont des spécifications opérationnelles d’interopérabilité qui indiquent comment utiliser des normes/standards stables et « vivants » dans le cadre de cas d’usage des domaines sanitaire, medico-social et social. Ce travail d’analyse et de sélection des normes/standards ainsi que la prise en compte des spécificités des cas d’usage de ces domaines en font une base de départ adaptée pour les spécifications du CI-SIS, qui n’ont plus qu’à contraindre ces profils et ces guides d’implémentation en fonction du contexte français.

Cette adéquation est également reconnue au niveau européen. En effet, le 28 juillet 2015 la Commission Européenne a identifié 27 profils IHE pouvant servir de référence dans la passation de marchés publics, profils qui ont été intégrés au cadre d’interopérabilité européen. Ces profils sont présentés [dans ce tableau](assets-docs-to-update/Liste_Profils_IHE_Standards.xls).

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

## Réutilisation des normes et standards déjà utilisés dans le CI-SIS

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

La liste des normes et standards utilisés dans le CI-SIS évolue constamment à la faveur de la production de nouveaux volets du CI-SIS. A titre d’information, les normes et standards qui sont utilisés dans le CI-SIS en septembre 2024 sont présentés [ici](assets-docs-to-update/Liste_Profils_IHE_Standards.zip).

## Choix des normes et standards non encore utilisés dans le CI-SIS

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

## Articulation de la doctrine d’interopérabilité avec la gouvernance du CI-SIS

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
    <img src="Sous-phase-evo.png" alt="CP" title="Sous phases de la phase d’évolution du CI-SIS" style="width:80%;">
    <figcaption><b>Sous phases de la phase d’évolution du CI-SIS</b></figcaption>
</div>

<!-- IGI - Schéma modifié par rapport à l’original pour insérer la phase de concertation publique de l’étude fonctionnelle des échanges -->

Ces travaux peuvent être faits en collaboration avec l'écosystème via une contractualisation sous forme d'[Unité de Production externe](./up-externe.html).
