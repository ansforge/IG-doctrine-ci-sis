L'interopérabilité est la capacité des systèmes à communiquer entre eux, au niveau local (établissement, GHT), régional ou national. L'interopérabilité permet un partage et un accès facilité à une donnée intégrable, réutilisable et exploitable, créant ainsi un intérêt stratégique indéniable, tant pour le patient que pour la recherche clinique.

Pour faciliter le partage et l'accès de la donnée de santé, il est nécessaire de construire un langage de données informatique partagé par tous et adapté aux cas d’usage traités. La construction d’un langage commun pertinent et opérationnel, qui réponde efficacement aux besoins identifiés, nécessite une concertation large avec l’ensemble des acteurs de l’écosystème : professionnels de santé, acteurs techniques, décideurs politiques. Cette collaboration est nécessaire pour définir et prioriser une feuille de route, puis élaborer et promouvoir une spécification. La clé de la réussite de l'interopérabilité est de fédérer un maximum d'acteurs afin de valoriser et généraliser l'usage d'une spécification tout en s'appuyant sur les travaux internationaux de standardisation pour une réutilisation maximale des travaux déjà effectués.

Au niveau du développement d'un logiciel, l'interopérabilité doit être pensée au plus tôt, au moment de sa conception afin d'être "interoperable by design", car une fois les interfaces graphiques développées et corrélées aux flux propriétaires, il est bien plus coûteux de faire l'évolution dans l'autre sens. 
A noter, l'interopérabilité est souvent confondue avec référencement, mais ces termes ne sont pas synonymes. Bien que l'interopérabilité puisse être une exigence dans le cadre d'un référencement, elle se distingue principalement par sa capacité à faciliter le partage et la réutilisation des données.

L'objectif de cette page est de fournir à l'écosystème une vision sur l'évolution des standards d'interopérabilité déployés en France, notamment ceux utilisés par le CI-SIS, dans les programmes nationaux comme le Ségur du Numérique en Santé et les établissements. Cette trajectoire est vouée à évoluer car les travaux sont constants au niveau international et européen. On peut citer par exemple les actes d'exécution du règlement EEDS qui se baseront a priori sur le standard FHIR R4 dans un premier temps mais dont le choix pourrait évoluer.

### Les actions menées pour promouvoir l'interopérabilité

L'interopérabilité fait partie des trois piliers du déploiement de la e-Santé en France avec la sécurité et l'éthique. Pour accompagner le déploiement de l'interopérabilité, de nombreuses actions sont portées par l'ANS

<div>
    <ul>
        <li><b>La <a href="https://interop.esante.gouv.fr/evs/home.seam">plateforme de tests gazelle</a></b> permet à chaque concepteur de logiciels de tester sa conformité aux spécifications d'interopérabilité du CI-SIS.</li>
        <li><b>Le Serveur Multi Terminologique (SMT)</b> est un portail web permettant l'accès à l'ensemble des terminologies, jeux de valeurs et alignements à utiliser en France. Il dispose d'un site web et d'une API pour accéder informatiquement à ces informations. Le SMT est accessible à l’adresse <a href="https://smt.esante.gouv.fr/">(format rdf)</a>  ou <a href="https://smt.esante.gouv.fr/FHIR">(format FHIR)</a></li>
        <li>L'ANS prône la démarche open source et publie de plus en plus ses travaux de spécifications d'interopérabilité <b><a href="https://github.com/orgs/ansforge/dashboard">sur GitHub</a></b>. GitHub permet à n'importe qui d'accéder à notre code source et à remonter des erreurs ou de manquements dans une perspective d'amélioration continue.</li>
        <li>L'ANS organise régulièrement des <b>projectathons</b>, évènement unique permettant à tous les éditeurs de se rencontrer et de tester ses interfaces d'interopérabilité de point-à-point. Notre plateforme de tests gazelle est utilisée dans le cadre de ces évènements.</li>
        <li>L'ANS évangélise et sensibilise l'écosystème à travers de nombreux webinaires et interventions publiques ainsi qu'à travers sa page <a href="https://www.linkedin.com/company/agence-du-numerique-en-sante/">LinkedIn</a>.</li>
    </ul>
</div>

### Contexte européen

Dans le cadre de la mise en œuvre de l’Espace Européen des Données de Santé (EEDS), plusieurs initiatives européennes ont été développées pour définir les fondations techniques de l’interopérabilité des systèmes de santé à l’échelle de l’Union européenne. Parmi elles, les projets Xt-EHR, ainsi que l'infrastructure MaSanté@UE et ses services associés jouent un rôle central.

#### Xt-EHR : vers un format européen commun fondé sur FHIR Document

Le projet Xt-EHR (_eXtended Electronic Health Record_) est une action conjointe européenne, soutenue par la Commission européenne, dont l’objectif principal est de définir un format commun d’échange de dossiers de santé électroniques. Ce format, appelé EEHRxF (_European Electronic Health Record Exchange Format_), constitue la base technique attendue pour les actes d’exécution du règlement EEDS.

Le projet fournit ainsi les spécifications normatives nécessaires à l’harmonisation des échanges de données de santé entre États membres, en s’appuyant sur des standards internationaux reconnus, notamment HL7 FHIR, tout en promouvant une convergence européenne sur les modèles de données et les jeux de valeurs utilisés.

Le format EEHRxF repose sur une approche documentaire normalisée. Il décrit un document structuré FHIR, construit autour de la ressource _Composition_, en accord avec le paradigme "Document" du standard HL7 FHIR. 

##### Une exigence future du règlement EEDS

Le règlement européen prévoit que tous les systèmes gérant des dossiers médicaux électroniques devront supporter le format EEHRxF pour permettre l’échange de données transfrontaliers. Cela fera du FHIR Document le socle réglementaire pour les principaux flux de données en santé : résumé du dossier patient, prescriptions, résultats de biologie, comptes rendus d’imagerie, et lettres de sortie.

##### Une transformation de la trajectoire française (CI-SIS)

Cette orientation européenne influence directement la stratégie nationale. À terme, les futurs volets de contenu du CI-SIS seront conçus nativement en FHIR Document, pour assurer une conformité totale avec les spécifications européennes. Une phase transitoire permettra un accompagnement des éditeurs pour faciliter l’adoption progressive du nouveau standard.

Le projet Xt-EHR contribue à cette transformation en livrant :

<div> 
    <ul> 
        <li>Des <strong>modèles logiques communs</strong> (_Logical Models_) pour les six catégories de données prioritaires du règlement EEDS ;</li> 
        <li>Des <strong>Guides d’Implémentation FHIR (FHIR IGs)</strong> conformes au format EEHRxF pour chaque type de document échangé ;</li> 
        <li>Des <strong>outils de validation</strong>, des démonstrateurs techniques et des phases de test interétatiques, notamment à travers les <em>projectathons européens</em>.</li> 
    </ul> 
</div>

Xt-EHR joue donc un rôle clé dans la préparation technique de l’EEDS. Il structure la convergence entre trajectoires nationales et exigences européennes, en assurant une cohérence des standards syntaxiques (FHIR) et sémantiques (terminologies partagées) dans les services de santé numériques en Europe.

#### MaSanté@UE : continuité des soins et accès multilingue aux données

Le projet MaSanté@UE vise quant à lui à faciliter l’échange transfrontalier des données de santé pour les citoyens européens en situation de mobilité. Il permet aux professionnels de santé d’un état membre d’accéder, dans leur propre langue, aux informations médicales d’un patient provenant d’un autre État membre. Cela améliore significativement la qualité et la sécurité des soins lors de séjours à l’étranger.

Ce projet s’appuie également sur les standards HL7 pour garantir une interopérabilité entre les systèmes nationaux. Il constitue l’un des premiers cas d’usage concrets des infrastructures de santé numérique paneuropéennes.

#### Le rôle des standards dans cette convergence européenne

Les standards HL7 sont au cœur de ces initiatives, car ils offrent une approche modulaire, extensible et soutenue par une large communauté internationale. FHIR, en particulier, grâce à son architecture fondée sur des API REST, est largement préféré pour les cas d’usage modernes tels que :

<div> 
    <ul> 
        <li>Le partage de comptes rendus de biologie médicale (Lab Reports) ;</li> 
        <li>Les lettres de sortie d’hospitalisation (Hospital Discharge Reports) ;</li> 
        <li>Les comptes rendus d’imagerie médicale (Medical Imaging Reports).</li> 
    </ul> 
</div>

Ces cas d’usage sont justement au cœur des travaux de standardisation du projet Xt-EHR.

#### Un alignement croissant avec la stratégie française

Ces initiatives européennes sont pleinement alignées avec la trajectoire nationale d’interopérabilité, portée par le CI-SIS et les travaux de l’ANS et d’Interop’Santé. Elles renforcent la nécessité d’une harmonisation des formats, des structures de données et des référentiels terminologiques au niveau européen.

L’adoption coordonnée de FHIR R4 au niveau national s’inscrit dans cette dynamique. Elle vise à garantir la cohérence entre les systèmes français et européens et à anticiper la mise en œuvre des actes d’exécution du règlement EEDS.

### La trajectoire syntaxique

Les standards HL7 v2 et CDA ont été créés il y a plusieurs dizaines d'années et sont très robustes mais sont concurrencés par le plus récent standard d'HL7 : FHIR. Il propose une nouvelle façon d'échanger des données par APIs et un protocole d'échange moderne (REST) beaucoup plus proches des technologies modernes de développement informatique.

L'interopérabilité des systèmes déployés en France est pris en charge par le domaine interopérabilité et données de Agence du Numérique en Santé (ANS) et d'autres organisations comme l'association Interop'Santé qui est le représentant français des deux principaux organismes internationaux de standardisation HL7 et IHE. L'ANS et Interop'Santé publient les documents de référence définissant les standards à utiliser en France, respectivement le Cadre d'Interopérabilité des Systèmes d'Information en Santé (CI-SIS) et le Guide d'Interopérabilité Hospitalier. Ces deux documents sont parfaitement alignés et cohérents et s'appuient sur des profils d'interopérabilité internationaux d'IHE et de HL7.

Pour le moment, cette page traite des standards d'interopérabilité suivants : FHIR, CDA, HL7 V2.

#### La stratégie du choix de la version FHIR

La stratégie sur le choix des versions FHIR a été définie au sein d'un groupe de travail organisé entre Interop'Santé et l'ANS en 2023/2024, validée via une [concertation](https://participez.esante.gouv.fr/project/fhir-r5-ou-r4/presentation/presentation) de l'ANS.

##### Nouveaux cas d’usages FHIR adressés par Interop’Santé et l’ANS : privilégier FHIR R4 et anticiper la transition vers R6

Pour garantir un écosystème cohérent, éviter tous problèmes de compatibilité ainsi que les travaux divergents, il est nécessaire d'utiliser une même version du standard FHIR à l'échelle nationale. Le choix a été fait de conserver FHIR R4 car il y a un existant conséquent en France et cela permet d'éviter une double transition R4 vers R5 et R5 vers R6. Ce choix est conforté car la release 6 se veut être la version finale stable de FHIR, une transition vers R6 se voudra de toute manière nécessaire. Pour anticiper cette transition, il est jugé important d’être proactif sur les travaux internationaux de développement de R6 et d’anticiper les impacts pour l’écosystème français.
Il est également à noter que le choix national de la version FHIR utilisée devra être en accord avec le règlement de l'EEDS qui se dessine progressivement et qui pour l'heure semble se diriger vers R4.

##### Ne pas créer de guide d'implémentation (IG) se basant sur R5 sans analyse des normes et standards et des impacts

La priorité actuelle est de faire monter l’écosystème en compétences et de gagner en maturité sur les spécifications existantes. Créer des IGs R5 engendreraient une fragmentation de l’écosystème et un ralentissement de la mise en qualité de l’existant qui finirait par freiner l’adoption de FHIR.

Généralement, rajouter quelques [extensions qui miment les attributs R5](https://hl7.org/fhir/R5/versions.html#extensions) s'avère suffisant pour éviter de créer tout un guide en R5. Dans certains cas, une autre version de FHIR peut être justifiée, par exemple si le cas d'usage concerne des échanges internationaux ou si le cas d'usage est significativement mieux couvert par une autre version. Le cas échéant, l’usage d’une autre version devra être validé par une étude des normes et standards publiée et validée par l’écosystème.

Dans certains cas non identifiés à ce jour, il pourrait également être nécessaire de maintenir des guides d’implémentation sous plusieurs versions. Après validation par l’écosystème de ce besoin, cela donnerait l’opportunité d'estimer des travaux de maintenance d’Implementation Guide (IG) sous plusieurs versions ainsi qu’un mapping associé pour gagner en expérience.

##### Priorité FHIR France en 2024 et 2025 - améliorer la qualité de l’existant

De nombreux travaux ont été menés en 2023 pour mettre en qualité les spécifications FHIR et encourager leur déploiement, tel que le passage au format IG et la mise à jour des tests et validateurs gazelle.

Les priorités des prochaines années sont de continuer dans cette direction :

<div>
    <ul>
        <li>La montée en compétences et l’acculturation des développeurs et des chefs de projets aux bonnes pratiques d’usages de FHIR, notamment en organisant des évènements par l'ANS et InteropSanté : projectathon, webinaires, formations, ...</li>
        <li>S’assurer de la faisabilité d’implémentation des IGs existants (amélioration du contenu narratif pour expliquer comment utiliser les ressources, s’assurer de la facilité d’accès au contenu, s'assurer que les IGs soient bien connus …).</li>
        <li>Prise en main des outils de mapping tel que le FHIR Mapping Language afin d'assurer une transition maîtrisée vers une autre version de FHIR.</li>
        <li>Anticiper les prochaines évolutions internationales : passage au FHIR Document dans le cadre du règlement européen, anticiper la transition vers FHIR R6, ...</li>
    </ul>
</div>

Il est également nécessaire de rester à l’écoute des tendances internationales en interopérabilité et de se garder la possibilité de réitérer l’analyse si le besoin ou le contexte international évolue, en particulier l'EEDS.

#### Focus FHIR Document

Aujourd'hui en France, l'ensemble des documents médicaux sont stockés en CDA, notamment avec la plus grande plateforme technique médicale nationale : le DMP, brique de Mon Espace Santé. Le standard FHIR peut, au même titre que le CDA, être utilisé pour décrire des documents médicaux. C'est par ailleurs la trajectoire qui a été retenue à l'international, notamment par l'EEDS.

##### Etude internationale

Selon l'étude [2024 State of FHIR](2024 StateofFHIRSurveyResults_final.pdf), l'utilisation du standard FHIR augmente dans la majorité des pays.

<div class="figure" style="width:65%;">
    <img style="height: auto; width: 100%;" src="fhir-adoption-rate-change.png" alt="CI-SIS" title="Logo du CI-SIS">
</div>

Cette même étude dévoile un nombre important de pays utilisant le FHIR document.

<div class="figure" style="width:65%;">
    <img style="height: auto; width: 100%;" src="fhir-documents.png" alt="CI-SIS" title="Logo du CI-SIS">
</div>

Aux Etats-Unis par exemple, les spécifications CDA ont fait leur premier pas vers FHIR, celles-ci sont publiées sont forme de guide d'implémentation en modèle logique, permettant ainsi de valider les CDA avec le FHIR Validator en abandonnant les schematrons ([source](https://build.fhir.org/ig/HL7/CDA-ccda/validation.html#:~:text=Validation%20Note-,What%20happened%20to%20the%20Schematron%3F,of%20the%20C%2DCDA%20document.)).

Du côté de l'Union Européenne, le projet EEDS ayant fait une étude de normes et standards pour les échanges transfrontaliers au sein de l'Europe a conclu sur l'usage du FHIR Document. Ce choix est justifié par le fait que certains pays n'ont pas d'historique CDA et choisissent très logiquement d'utiliser le standard FHIR étant plus récent et utilisant des technologies web modernes. FHIR y a été largement préféré pour les trois cas d'usages privilégiés pour le partage transfrontalier : le compte rendu d'examenens de biologie médicale (Lab Report), la lettre de sortie (Hospital Discharge Report) et le compte rendu d'imagerie médicale (Medical Imaging Report). Resp. 18, 17 et 16 membres préféraient FHIR contre 3, 5 et 5 pour CDA.

##### Intérêt d'usage du FHIR document

En plus de la trajectoire internationale semblant mener vers l'usage du FHIR document, des avantages non négligeables sont à noter sur l'usage de ce nouveau standard.

<div>
    <ul>
        <li>Au même titre que les sections et entrées CDA, les FHIR Document sont composés d'une multitude de briques, appelées ressources (ex : Observation, Patient, Encounter, ...). La différence est que ces mêmes ressources peuvent également être utilisées au sein d'API REST spécifiées par le standard.</li>
        <li>Il existe de nombreux outils facilitant l'usage de FHIR, développés par une communauté très active à l'internationale. Ces outils permettent de :</li>
        <li>
            <ul>
                <li>Faciliter l'implémentation, avec de <a href="https://confluence.hl7.org/display/FHIR/Open+Source+Implementations">nombreux serveurs open source et validateurs</a> pour simplifier son déploiement chez les éditeurs.</li>
                <li>Optimiser l'édition des spécifications grâce à des outils open source, entièrement compatibles avec GitHub, en offrant une gestion textuelle du contenu technique et narratif (FSH/markdown). Ces outils facilitent la collaboration, la remontée d'erreurs, la participation de l'écosystème, tout en permettant l'automatisation des comparaisons entre versions, l'historisation automatique des anciennes versions, et une gestion efficace des contributions.</li>
            </ul>
        </li>
    </ul>
</div>

L'uniformisation des spécifications d'interopérabilité au niveau européen et mondial est un vrai atout pour les entreprises, car cela permet de faciliter leur internationalisation.

##### Position de l'Agence du Numérique en Santé

Prioriser la prise en charge du FHIR document est à ce point indéniable, de nombreux indices sur les études internationales et la multiplication de projets lancés mettent en lumière le consensus international sur l'utilisation du FHIR Document.

Deux scénarios de déploiement de FHIR document ont été identifiés en France

###### Scenario 1 : Mettre en place une transformation entre les standards CDA et FHIR

Le premier scénario consiste à mettre un place un outil de transformation des documents CDA vers FHIR et inversement. Cependant, ce scénario nécessite de maintenir cet alignement dans le temps. Les techniques d'alignement sont complexes et lourdes à mettre en oeuvre avec un accroissement de la complexité pour chaque nouvelle version de spécification publiée. Par exemple, des [travaux italiens sur ce sujet](https://www.hl7.it/fhir/cda2fhir/) contiennent plusieurs dizaines de milliers de lignes. Il y a également des questionnements quant à la responsabilité : qui sera responsable du document en cas d'erreur de transformation ?

Pour transformer les documents CDA des volets du CI-SIS vers FHIR, il faudrait que l'ensemble des spécifications CDA soient définies au format `StructureDefinition` pour utiliser le FHIR Mapping Language.

###### Scénario 2 : Permettre une utilisation concomitante de FHIR et de CDA le temps de la transition

Cette solution permettrait une utilisation concomitante de FHIR et de CDA, où les spécifications seront publiées selon les deux modes. Cela permettrait une transition douce avec un timing au choix de chacun pour le passage vers FHIR Document, avec une date limite de décommissionnement de l'autorisation d'écriture en CDA dans le DMP.

Ainsi, au même titre que les documents CDA ne sont pas automatiquement transformés vers les nouvelles versions des spécifications, les documents historiques resteront au format CDA et les nouveaux au format FHIR Document.

La difficulté reviendrait aux consommateurs qui devront, au moins pendant un temps, être capables de traiter deux formats différents : CDA et FHIR. Ce qui ne changerait pas de la situation actuelle finalement car les spécifications CDA évoluent elles aussi.

###### Solution privilégiée

l'ANS et la commission européenne privilégieront la solution numéro 2, qui consiste en une utilisation concomitante de FHIR et de CDA. Cette solution sera agrémentée d'une preuve de concept d’un mapping CDA - FHIR, générique à destination de l'écosystème.

#### Pourquoi il est nécessaire d'aller au delà du paradigme document en France ?

En France, le paradigme document est l'un des plus utilisés par l'écosystème, notamment dans le cadre du service DMP : un document est un compte rendu médical signé et daté à propos d'un patient. Il existe d'autres paradigmes à considérer tel que le paradigme message, le paradigne REST, la souscription, ... [La documentation de FHIR](https://www.hl7.org/fhir/exchanging.html) facilite la prise de décision en proposant un arbre de décision.

Par exemple, les trois API FHIR de Mon Espace Santé (Mesures de santé, Agenda et document) permettent d'accéder aux données via des requêtes REST.

Une étude approfondie du besoin est nécessaire pour identifier le paradigme idéal par cas d'usage sans partir de facto sur le paradigme document.

### La trajectoire sémantique

L’ANS gère aussi le centre de gestion des terminologies de santé (CGTS) qui assure la maitrise d’ouvrage nationale de publication des terminologies, jeux de valeurs et alignements sémantiques du CI-SIS. Ce corpus sémantique constitue le langage commun fondement de l’interopérabilité sémantique des échanges interprofessionnels.

Du point de vue sémantique, les échanges dématérialisés de données nécessitent un large spectre de vocabulaire pour couvrir l’ensemble de la description du parcours de santé ou de soins d’un patient : motif de contact avec le système de santé, demandes/prescription d’examen, mesures, évaluation fonctionnelle du patient, diagnostic et traitements (actes, médicaments , dispositifs médicaux, recommandations).

Il existe une large gamme de standards sémantiques répandus ou imposés en France et largement en usage :

<div>
    <ul>
        <li>Les terminologies de l’assurance maladie (NGAP, NABM, CCAM, LAHN, LPPR) pour les cas d’usage de remboursement.</li>
        <li>Les terminologies de l’OMS (ex : CIM largement utilisée dans le SNDS pour des cas d’usage de production de soins, coordination de soignants, pilotage et exploitation des données) .</li>
        <li>Une terminologie multi-domaines, la SNOMED CT, utilisée pour coder l'anatomie, des résultats de tests, statuts du patient, ...).</li>
        <li>Les terminologies de biologie pour structurer les examens et leurs résultats (CIM-11, LOINC, SNOMED CT et la grammaire UCUM) ainsi que pour décrire leur méthodes (Nomenclature des réactifs et techniques).</li>
    </ul>
</div>

Ces standards sémantiques généraux sont complétés par des vocabulaires plus spécifiques à certains parcours : oncologie (ex terminologie de cytopathologie), parcours médicosocial (terminologie Serafin PH des besoins et prestation pour la personne handicapée, terminologie des profils pathologique des résidents en EHPAD), santé au travail (thesaurus des exposition professionnelles).

<!-- ## Contenu, vérifier cohérence intro / contenu -->

Au niveau mondial, la démultiplication des échanges numériques en santé transforme profondément le secteur médical et médicosocial :  

<div>
    <ul>
        <li>avec un accès facilité aux informations Médicales,</li>
        <li>le développement des téléconsultations, télésurveillance, téléexpertise,</li>
        <li>le développement des applications de Santé et des Objets Connectés,</li>
        <li>l’explosion des entrepôts de données de santé disponibles pour les épidémiologistes (en analyse historique ou prédictive)</li>
    </ul>
</div>

En France Le programme du Ségur numérique de la santé, lancé en 2021, participe pleinement à ce développement des échanges numériques. Il a, entre autres, pour objectif de généraliser le partage fluide et sécurisé des données de santé entre les professionnels de santé et les usagers.
L’accélération des échanges numérique va de pair avec un besoin croissant de normes sémantiques décrivant le parcours de soins, ou le parcours de santé du patient.
Ces normes sémantiques ou Terminologies sont des ensembles de termes spécifiés permettant de décrire de manière plus ou moins organisée (de la simple liste à l’ontologie) des concepts  associés à un ou plusieurs domaines de connaissance.

Au sein du parcours patient, les éléments communs incontournables sont les suivants :

<div>
    <ul>
        <li>Motif de contact avec le système de soins (symptômes, accident, orientation préventive, etc…)</li>
        <li>L’évaluation du patient (capacité fonctionnelle, relationnelle, signes vitaux, etc…)</li>
        <li>Les investigations menées par le professionnel (biologie, imagerie, test fonctionnels, etc…)</li>
        <li>Le diagnostic posé par le professionnel (qui peut devenir antécédent en fonction de la période d’analyse de dossier patient)</li>
        <li>L’objectif de traitement</li>
        <li>Les traitements (actes médicaux ou paramédicaux, médicaments, dispositifs médicaux, mesures hygiénodiététiques, éducation thérapeutique, etc…)</li>
    </ul>
</div>

Tous ces éléments sont décrits par des terminologies généralistes pouvant décrire tous les parcours (ex : CIM pour décrire les pathologies d’un patient) ou spécifiques d’un parcours (TNM pour décrire le bilan d’extension d’un cancer).
La trajectoire sémantique (constitution d’un corpus sémantique pertinent) se fonde sur l’utilisation préférentielle des terminologies en usage au niveau local, complétée par des normes internationales pour des nouveaux cas d’usage non couverts par des normes locales. Eventuellement, des normes ad hoc pourront être choisie en l’absence de normes locales ou de normes internationales.
Dans tous les cas le choix de nouvelles normes se fait par la concertation des professionnels de santé , utilisateur du vocabulaire et des éditeurs intégrateurs de ce vocabulaire.

Il existe de nombreux défis au niveau de la trajectoire sémantique française

<div>
    <ul>
        <li>Réduire le nombre de terminologies pour un domaine de connaissance</li>
        <li>Fournir un méta modèle d’organisation sémantique commun à toutes les terminologies  pour faciliter leur traitement</li>
        <li>Avoir des terminologies adaptées au langage du professionnel de santé (terminologie d’interface) , qui décrivent logiquement le domaine de connaissance  (terminologie de référence) et qui sont utilisable pour des échanges au sein de l’équipe de soins (terminologie pivot)</li>
        <li>Avoir des terminologies à la fois utilisable au niveau mondial permettant des échanges transfrontaliers et à la fois adaptées aux cas d’usage français.</li>
        <li>Pour un domaine de connaissance avoir une terminologie adaptée pour tous les cas d’usage (production de soins, coordination des soins, remboursement et analyse des données)</li>
        <li>Avoir une organisation de la connaissance dont la complexité est adaptée au cas d’usage (liste simple pour un échange de donnée, ontologie pour alimenter un système d’aide à la décision, ou faciliter l’exploitation de données de cohortes)</li>
        <li>Fournir les données sous un format opérationnel pour les utilisateurs.</li>
        <li>Avoir des terminologies en libre diffusion pour faciliter l’accès aux données et à leur réutilisation </li>
    </ul>
</div>

La réponse à ces défis est multiple :

Sur le plan technique

<div>
    <ul>
        <li>Développer des outils de traduction automatique pour utiliser les terminologies internationales en Anglais.</li>
        <li>Développer les capacités d’alignements pour utiliser des terminologies différentes appliquées à un même domaine de connaissance pour des cas d’usages différents (ex ICHI et CCAM, SNOMED CT et NCBI Taxonomy).</li>
        <li>Développer des outils ergonomiques (requêteur Sparql graphique ) pour faciliter l’accès aux données et la production de jeux de valeurs spécifiques.</li>
        <li>Publier les terminologies sous des formats adaptés (rdf pour restituer toutes les relations d’une ontologie, FHIR pour simplifier les intégrations par les éditeurs de logiciel).</li>
        <li>Développer des jeux de valeurs terminologiques spécifiques pour faciliter la mise en œuvre de volets d’interopérabilité.</li>
    </ul>
</div>

Sur le plan accompagnement

<div>
    <ul>
        <li>Faciliter l’acculturation des développeurs et des professionnels de santé aux bonnes pratiques de l’utilisation /intégration de ressources sémantiques.</li>
        <li>S’assurer de la bonne compréhension des usages et de l’intégration des ressources sémantiques dans des volets d’interopérabilité.</li>
        <li>Développer un cercle d’expertise métier et technique mobilisable ad hoc, capable d’assister l’ANS dans le développement des usages.</li>
        <li>Favoriser le dialogue des parties prenantes pour bâtir un vocabulaire commun consensuel (terminologies communes ou construction de règles d’alignements : dialogue secteur sante - secteur médicosocial, soins primaires- soins spécialisés, médecine du travail- soins primaires. </li>
    </ul>
</div>

La trajectoire de l’interopérabilité sémantique est fondée sur la constitution d’un corpus sémantique permettant de répondre au besoin :

<div>
    <ul>
        <li>de décrire  le parcours de soins/ santé d’un patient/usager avec le vocabulaire en usage en France ou choisi par une concertation des parties prenantes (professionnels de santé, institutions et éditeurs).</li>
        <li>de répondre aux différents cas d’usage de l’interopérabilité (production et coordination de soins, pilotage des parcours de soins/santé, exploitation des données de santé des Français.)</li>
    </ul>
</div>

[Le catalogue actuel du serveur multi-terminologies de l’ANS](https://smt.esante.gouv.fr/) se compose, en juin 2025, de :
<div>
    <ul>
        <li>37 Terminologies dont 33 publiées en syntaxe OWL (standard du W3C) et 29 disponibles sous forme de CodeSystem FHIR ;</li>
        <li>732 jeux de valeurs publiés sous forme de ValueSet FHIR ;</li>
        <li>11 alignements publiés au format SSSOM dont 2 aussi disponibles sous forme de ConceptMap FHIR.</li>
    </ul>
</div>
Ce catalogue est complété par les Nomenclatures des objets de santé qui sont publiées au format FHIR sur le serveur FHIR associé au [SMT](https://ontoserver.csiro.au/ui/resource/CodeSystem)  
14 761 téléchargements ont été opérés entre octobre 2023 et septembre 2024, soit un rythme de 1315 téléchargements mensuels (ces chiffres n'incluent pas les données d'utilisation des API FHIR du SMT).
Le graphique ci-après présente les terminologies les plus téléchargées.

<div class="figure" style="width:65%;">
    <img style="height: auto; width: 100%;" src="semantique.png" alt="CI-SIS" title="Logo du CI-SIS">
</div>

Les terminologies du médicaments (référentiels d’interopérabilité du médicament et classification ATC ) arrivent en tête. Le référentiel des unités communes de dispensation arrive en 5eme position.
Elles sont suivies par les terminologies médicales de l’OMS (CIM 11 en déploiement et CIM10 en usage)
Les terminologies de cyto-anapathologie, des dispositifs médicaux, des expositions professionnelles et des actes suivent ensuite.
La SNOMED CT adoptée par la France en 2023 est disponible sur le serveur depuis novembre 2023. Environ 50 téléchargements sont opérés mensuellement.

**Les priorités 2025 - 2027 :**

Sur le plan outillage et publication

<div>
    <ul>
        <li>Développement des fonctionnalités du SMT (interface graphique de requêtage, ergonomie de navigation, mise à disposition des alignements, plateforme de traduction). </li>
        <li>Faisabilité d’un processus de mise à jour hebdomadaire (la plus haute fréquence actuelle est mensuelle)</li>
        <li>Fhirisation systématique du catalogue du SMT en continuité de la publication des NOS sous ce format.</li>
    </ul>
</div>

Sur le plan du développement et de l’amélioration du catalogue de terminologies

<div>
    <ul>
        <li>Déploiement de SNOMED CT sous une version française pour des nouveaux cas d’usage non couverts par les terminologies en usage en France</li>
        <li>Déploiement de la CIM 11  sur les cas d’usage de la CIM  (pathologies dans les dossiers patients, description des séjours hospitaliers, déclaration des affections chroniques, codage des causes médicales de décès) et extension vers les dosiers patients associés (dossier patient en EHPAD, dossier médecine santé au travail).</li>
        <li>Amélioration continue du Ruim : incorporation des disponibilités des médicaments essentiels, dispensations particulières, médicaments facturés en sus des séjours hospitaliers, médicaments de rétrocession, compatibilité IDMP, virtualisation pour le cas d’usage dispensation par automate.</li>
        <li>Initiation d’un référentiel du DM  pour les cas d’usage  :  e-prescription DM,. Traçabilité du DM implantable, information la disponibilité des DMs critiques.</li>
        <li>Normes sémantiques en lien avec le parcours cancer (normalistion des jeux de valeur OSIRIS)</li>
        <li>Norme s sémantique du dossier santé travail en vue de l’intégration du DSMT dans mon espace santé.</li>
        <li>Passerelles terminologiques entre terminologies du médico-social et celles du secteurs santé.</li>
    </ul>
</div>

### Les acteurs influençant la trajectoire

De nombreux acteurs influencent la trajectoire et le rôle des experts interopérabilité est d'avoir une vision globale de cet écosystème, de ces acteurs et des spécifications existantes afin de répondre aux besoins en réutilisant au maximum les travaux existants au niveau international, et éviter la nécessité de se ré-aligner par la suite.

Les acteurs peuvent se situer à plusieurs niveaux : au niveau politique, au niveau modélisation technique et au niveau implémentation.

#### Les acteurs politiques

* Le Ministère de la santé et plus particulièrement la Délégation du Numérique en Santé (DNS). La mission de la DNS de développer et réguler les usages du numérique, pour répondre aux besoins de notre système de santé, dans le respect d’un cadre de valeur éthique et humaniste. La DNS joue un rôle de chef d’orchestre pour piloter la feuille de route du numérique en santé et garantir sa mise en oeuvre effective. Elle représente l’Etat dans la gouvernance de l’ANS.
* Le eHealth Network (eHN) : réseau des états membres de l’union européenne. L'eHN a plusieurs missions dont la mise ne place d’applications et de services européens interopérables au bénéfice des citoyens européens, la rédaction de guide sur les données de santé à échanger et les méthodes, et le développement de mesures sur l’identification et l’authentification des acteurs impliqués dans l’échange de données.

#### Les professionnels de santé

il est nécessaire de consulter les professionnels de santé pour évaluer des nomes techniques sémantiques ou syntaxiques et de spécifier des profils au plus près de leurs besoins en respectant leurs usages.

#### Les éditeurs de logiciels

Les éditeurs vont mettre en œuvre les différentes normes dans leurs solutions applicatives. La trajectoire de l’interopérabilité va dépendre de leur maturité et de leur disponibilté pour mettre en œuvre les standards concertés et prescrits.

#### Les acteurs en charge de la modélisation technique (organismes de standardisation)

IHE, HL7 International, HL7 Europe

#### Les acteurs en charge de l'implémentation

La CNAM (DMP, Mon Espace Santé), les éditeurs de logiciels de santé.
