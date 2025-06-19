
Dans un monde où la standardisation de l’information médicale ne suffit plus à garantir la qualité des soins prodigués dans le cadre d’un Système d’Information (SI) de santé, ce document jette les premières réflexions sur une doctrine en lien avec la standardisation de la connaissance médicale en France.  

La standardisation de la connaissance médicale issue, entre autres, des Guides de Bonnes Pratiques Cliniques (GBPC) et leur intégration de façon standard dans un SI de santé est un atout majeur pour la transition du modèle volume-based à value-based d'un SI de santé à l'échelle nationale. Cette connaissance médicale standardisée peut servir à définir des aides à la décision clinique standards ainsi que des mesures de la qualité des soins standardisées, nécessaires à la remontée d'indicateurs de la qualité des soins. Les réflexions décrites ci-dessous sont une adaptation des travaux menés par le CDC (Centers for Disease Control and Prevention) américain au travers de l'initiative Adapting Clinical Guidelines for the Digital Age. [28](#ref28). 

Deux événements majeurs ont poussé les responsables et les experts de l’ANS à réfléchir à un tel document. Premièrement, l’introduction d’un nouvel SI, appelé SI-CM (Système d’Information et Connaissances Médicales). Le SI-CM permettra dans un futur proche d’introduire de nouveaux volets d’interopérabilité dans le CI-SIS principalement en lien avec la standardisation des connaissances médicales issues des guides de bonnes pratiques cliniques (GBPC) et la standardisation de leur intégration dans un SI de santé. Il est également en lien avec la standardisation des critères de qualité de soins. Deuxièmement, des travaux de mise à jour de la doctrine et de la gouvernance du CI-SIS ont été menés en interne à l’ANS afin de permettre au CI-SIS de se conformer aux nouvelles tendances en informatique de façon générale et en interopérabilité des données de santé de façon plus spécifique.  

Ce document vient donc s’inscrire dans le cadre des travaux de mise à jour de la doctrine et de la gouvernance du CI-SIS. Ce document complète la doctrine du CI-SIS mise à jour en y introduisant les principes de base que doivent suivre les projets d’interopérabilités en lien avec la standardisation de la connaissance médicale apportés par le SI-CM. 

<h4 id="public-concerné">Publics concernés </h4>

Ce document s'adresse principalement aux personnes et organismes qui veulent comprendre
<div>
    <ul>
    <li>Comment les principes de la présente doctrine ont été élaborés </li>
        <ul>
        <li>Cela concerne les chapitres sur <a href = "#cadre-SI-CM">le cadre de la doctrine d'interopérabilité du SI-CM</a> et <a href = "#principes-SI-CM"> les principes de la doctrine du SI-CM</a> </li>
        <li>Les profils de personnes potentiellement concernés sont : les responsables de l'ANS, les experts de l'ANS, les chercheurs en informatique médicale, les directeurs de projets </li>
        </ul>
    <li>Comment les principes de la présente doctrine ont été utilisés pour faire des choix de standards, de méthodes et d'outils pour concevoir et partager des artéfacts de connaissances médicales standardisés </li>
        <ul>
        <li>Cela concerne le chapitre <a href ="#chemins-SI-CM"> les chemins de la doctrine du SI-CM</a> </li>
        <li>Les profils de personnes potentiellement concernés sont : les responsables de l'ANS, les experts de l'ANS, les chercheurs en informatique médicale, les directeurs de projets et les chefs de projet informatique </li>
        </ul>
    <li>Quels sont les standards, méthodes et outils choisis et préconisés par l’ANS si on veut standardiser des artéfacts de connaissances médicales et les intégrer sous forme d’aide à la décision cliniques </li>
         <ul>
    <li>Cela concerne le chapitre <a href = "#chemins-SI-CM">Les chemins de la doctrine du SI-CM</a> </li>
    <li>Les profils de personnes potentiellement concernés sont : les responsables de l’ANS, les experts de l’ANS, les chercheurs en informatique médicale, les directeurs de projets, les chefs de projet informatique, les développeurs, les POs </li>
              </ul>
    </ul>
</div>

<h4 id="cadre-SI-CM">Le cadre de la doctrine d'interopérabilité du SI-CM </h4>

La doctrine d’interopérabilité du SI-CM s’inscrit dans les orientations suivies par la nouvelle version de la doctrine du  CI-SIS décrite ici [1](#ref1). 
La doctrine du SI-CM peut-être synthétisée ainsi 

<div>
    <ul>
    <li>Un ensemble de principes de base qui permettent de guider les choix en termes de standards, de méthodes et d’outils pour atteindre l’objectif </li>
        <ul>
        <li>de modéliser et de partager de façon standard la connaissance médicale issue des GBPC. </li>
        <li>d’intégrer de façon standard (dans un SI cible) cette connaissance médicale issue des GBPC sous forme de Système d’Aide à la Décision Clinique (SADC) </li>
        </ul>
    <li>Un chemin nominal : qui instancie les principes de la doctrine du SI-CM et décrit les choix en termes de standards de référence, de méthodes et d’outils adoptés pour atteindre les objectif sus mentionnés </li>
    <li>Un ou plusieurs chemins secondaires : décrivent le choix et l’utilisation d’un standard et / ou d’un processus de conception et / ou de mise en œuvre « non de référence ». Ce chemin secondaire peut être justifié par le fait que le chemin nominal ne réponde pas aux besoins remontés du terrain. </li>
    </ul>
</div>

La doctrine d’interopérabilité du SI-CM décrite dans ce document couvre  
<div>
    <ol>
    <li>Les concepts en lien avec la standardisation de la connaissance médicale issue des GBPC </li> 
    <li>Les concepts en lien avec la standardisation de l’intégration de la connaissance médicale sous forme de système d’aide à la décision clinique (SADC) dans un SI de santé </li> 
    </ol>
</div>

<h4 id ="principes-SI-CM">Les principes de la doctrine du SI-CM</h4>
Dans ce qui suit, nous décrivons les principes spécifique de la doctrine du SI-CM sur lesquelles elle s’appuiera pour gérer les artéfacts de connaissances médicales que le SI-CM produira / exposera. Ces principes nous permettront d’instancier un chemin nominal pour la gestion des artéfacts produits / exposés par le SI-CM et un ou plusieurs chemins secondaires. Ces chemins décriront les outils de modélisation, de conception et de mise en œuvre qui devront être utilisés et/ou promus (à destination de l’écosystème) par le SI-CM pour la gestion des artéfacts de connaissances médicales en France. Les principes commun à l'ensemble de la doctrine du CI-SIS sont présentés dans le chapitre précédente.

<h5 id = "principe-4">Principes #4 : Principes en lien avec les bonnes pratiques d'ingénierie logicielle et de recherche</h5>
<h6 id ="design-patterns"> L'adoption des Designs Patterns en ingénierie des connaissances pour la standardisation des GBPC et leur intégration dans un SI de santé</h6>

En ingénierie des connaissances et plus particulièrement dans le cadre défini en paragraphe 2 de cette doctrine, nous avons identifié 3 designs patterns que le SI-CM doit respecter dans la gestion des artéfacts de connaissances médicales

<h7 id = "archi-tri-dim">L'architecture tri-dimentionnel de Rector et al. </h7>

La standardisation des GBPC dans le cadre du SI-CM doit combiner et interfacer trois types de modèles (Figure 2) [15](#ref15)

<div>
    <ul>
    <li><strong>Information about specific patients and clinical situations</strong> : ce modèle dit d’informations médicales permet de standardiser les informations issues du dossier patient</li>
    <li><strong> General patient-independent information about medicine and medical practice </strong>: ce modèle dit de connaissances métiers comprend 2 sous modèles</li>
    <li><strong>Guideline independent static knowledge</strong>: un modèle de connaissances métiers dit statique. C’est ce qui correspond le plus dans le jargon de l’interopérabilité aux modèles définis par les terminologies médicales.</li>
    <li><strong> Guideline dependent dynamic knowledge model</strong>: Ce modèle dit d’inférence a pour objectif de modéliser comment on infère les conclusions et les décisions d’informations spécifiques au patient et des faits indépendants décrit dans le GBPC.</li>
    </ul>
</div>

<div class="figure" style='text-align: center;'>
    <img src="Figure 2  Les modèles de l’architecture tri dimensionnel de Rector et al. et leurs interfaces.png" alt="archi_tri_dim" title="Figure 2 : Les modèles de l’architecture tri-dimensionnel de Rector et al. (15) et leurs interfaces" style="width:50%;">
    <figcaption><b>Figure 2 : Les modèles de l’architecture tri-dimensionnel de Rector et al. (15) et leurs interfaces</b></figcaption>
</div>


<h7 id = "representation-multicouche">La représentation multi couches de la connaissance médicale de Boxwala et al.</h7>

La standardisation des GBPC dans le cadre du SI-CM doit respecter les différents niveaux de structuration de la connaissance décrits dans [16](#ref16) (Tableau 1) Les documents de spécifications pour chaque volet du SI-CM doivent pouvoir décrire la structuration de la connaissance médicale du GBPC cible suivant ces quatre formats de représentation  

<div>
    <ol>
    <li><strong>Narratif</strong> : ce format correspond au texte brut de la recommandation du GBPC cible ainsi que le lien vers la recommandation en question.</li>
        <ul>
        <li>Ce format doit être lisible et partageable par tous</li>
        <li>Ce format doit être indépendant de toute technologie d’implémentation</li>
        <li>Ce format doit être indépendant du contexte de mise en œuvre</li>
        <li>Ce format est produit par les experts métiers producteurs du GBPC</li>
        <li>Ce format a pour but de définir une politique de santé publique basée sur les faits et la connaissance</li>
        </ul>
    <li><strong>Semi structuré</strong> : Ce format correspond à une interopération du texte brut en vue de sa structuration. Ce format permet de définir à partir du texte brut : le qui, le quoi, le quand, le où et le pourquoi. Il permet de définir les concepts statiques qui composent la recommandation et d’identifier les terminologies auxquels ils peuvent correspondre. Ce format est généralement une combinaison de texte structuré et de diagrammes d’activités UML. </li>
        <ul>
        <li>Ce format doit être lisible et partageable par tous</li>
        <li>Ce format doit être indépendant de toute technologie d’implémentation</li>
        <li>Ce format doit être indépendant du contexte de mise en œuvre</li>
        <li>Ce format doit être co écrit par un expert du domaine métier ainsi que par un expert informatique en ingénierie des connaissances</li>
        <li>Ce format a pour but de structurer le texte brut de la recommandation en vue de sa standardisation et implémentation sous forme d’aide à la décision clinique</li>
        </ul>
    <li><strong>Structuré</strong> : Ce format doit impérativement correspondre au modèle appelé : Guideline dependent dynamic knowledge model décrit dans le paragraphe précédent</li>
        <ul>
        <li>Ce format est interprétable par la machine</li> 
        <li>Ce format doit être lisible et partageable par tous</li> 
        <li>Ce format doit être indépendant de toute technologie d’implémentation</li> 
        <li>Ce format doit être indépendant du contexte de mise en œuvre</li> 
        <li>Ce format est généralement écrit par l’expert en structuration de la connaissance médicale et en standardisation / interopérabilité</li> 
        <li>Ce format doit servir à partager la connaissance médicale standardisée et interopérable. Ce format doit servir à valider le contenu de la connaissance médicale avec un interpréteur (raisonneur).</li>
        </ul> 
    <li><strong>Exécutable</strong>: Ce format correspond au code exécutable par un SADC.</li> 
        <ul>
        <li>Ce format est interprétable par la machine</li> 
        <li>Ce format n’est pas lisible par l’humain et n’est pas partageable</li> 
        <li>Ce format est dépendant de la technologie de mise en œuvre du SADC qui l’exploite</li> 
        <li>Ce format est dépendant du contexte de mise en œuvre du SADC qui l’exploite </li>
        <li>Ce format doit servir à la mise en œuvre d’un SADC pour un SI particulier</li>
        </ul>
    </ol>
</div> 

<div class="figure" style='text-align: center;'>
    <img src="Tableau 1 les quatre couches de formats de représentation de la connaissance médicale selon Boxwala et al.png" alt="quatre_couche" title="Tableau 1 : les quatre couches de formats de représentation de la connaissance médicale selon Boxwala et al. (16)" style="width:50%;">
    <figcaption><b>Tableau 1 : les quatre couches de formats de représentation de la connaissance médicale selon Boxwala et al. (16)</b></figcaption>
</div>


<h7 id = "integration-SADC">L'intégration standardisée des SADC basés sur les GBPC dans un SI de santé</h7>

La connaissance médicale issue des GBPC standardisée dans le cadre du SI-CM n’aura de valeur que si elle est déployée et exploitée par l’écosystème. Une des stratégies préconisées dans la littérature pour faciliter l’adoption de cette connaissance par les professionnels de santé est son déploiement sous forme de SADCs [17](#ref17). Une des principales barrières décrites dans la littérature à l’adoption des SADC (basés ou non sur une connaissance médicale standardisée) par l’écosystème est la mauvaise scalabilité de ces systèmes. Adopter un standard d’intégration et d’exposition des SADCs est une des solutions architecturales préconisées dans la littérature pour améliorer la scalabilité des SADCs [18](#ref18). La connaissance médicale standardisée dans le cadre du SI-CM doit pouvoir s’intégrer dans un SI de santé sous forme d’un SADC en adoptant un standard d’intégration.

<h7 id = "positionnement-design-patterns">Se positionner par rapport aux Design Patterns architecturaux génériques</h7>

Les solutions logicielles conçues dans le cadre des problématiques posées par l’interopérabilité en santé doivent être réfléchies à un niveau d’abstraction qui permet d’instancier ces solutions de façons différentes autant de fois qu’elles seront utilisées sur le terrain pour un cas d’usage. C’est là, la définition même d’un Design Pattern. Les Design Patterns produits par les différentes sociétés savantes : HL7, IHE, IEEE,…peuvent être de trois catégories 

<div>
    <ol>
    <li>Un modèle d’information standard : définie un modèle de données standard qui doit circuler dans des messages d’interopérabilité pour un cas d’usage X.</li> 
    <li>Un design pattern architectural : définie une solution logicielle standard qui s’appuie sur un modèle d’information standard pour résoudre un problème d’interopérabilité Y de façon standard.</li> 
    <li>Un design pattern architectural de contenu standard : instancie un design pattern architectural pour répondre à un cas d’usage particulier. Ce type de Design Pattern est le plus répondu.</li>  
    </ol>
</div>

Les spécifications définies et / ou exposées par le SI-CM doivent se positionner par rapport à ces trois types de design pattern architecturaux génériques.  

__Pourquoi il est important de se positionner par rapport aux différentes catégories de Design Pattern ?__  

L’interopérabilité telle qu’adoptée actuellement par l’éco système à travers le monde est basée sur la notion de cas d’usage. Chaque cas d’usage donne lieu à des spécifications qui sont censées répondre aux besoins décrits dans le cas d’usage. Cependant le risque est d’écrire des spécifications qui se chevauchent ou des spécifications dupliquées. Il est donc nécessaire à chaque début de projet de se positionner par rapport aux Design Patterns architecturaux générique décrits plus en amont pour pouvoir identifier les spécifications déjà existantes et pouvoir les réutiliser totalement ou partiellement. Ce principe rejoint les principes de modularité et de séparation des responsabilité décrits en paragraphe [L'utilisation des Design Patterns](#design-patterns) 

<h6 id = "maj-guidée-recherche">La mise à jour de la doctrine guidée par la recherche</h6>

Une grande partie des principes énoncés plus en amont est basée sur des concepts issus de la recherche scientifique. Certains de ces concepts sont validés et adoptés par l’écosystème de l’ingénierie qui les exploite déjà dans des projets informatiques en routine, exemple : les design pattern de structuration des GBPC qui date de plus de 25 ans. D’autres concepts sont en cours d’évaluation par la communité des chercheurs et d’adoption par l’écosystème de l’ingénierie, exemple : le standard CDS Hooks [19](#ref19).  

Il est donc nécessaire pour la doctrine du SI-CM de garder un œil sur l’évolution de certains concepts au regard de l’avancée de l’évaluation et de l’adoption de ces concepts en parcourant régulièrement les articles scientifiques correspondants.  

<h6 id = "impact-SADC">L'évaluation de l'impact d'un SADC basé sur les bibliothèques de connaissances standards conçues et/ou exposées par l'ANS</h6>

Les bibliothèques standards de connaissances médicales publiées ou exposées par l’ANS doivent être évaluées avant toute mise en œuvre dans un SI de santé en production. L’évaluation de ces bibliothèques peut-être effectuée suivant différentes étapes
<div>
    <ul>
    <li><strong>Les tests</strong> : la phase de tests est couverte par <a href=processus-conception-logiciel>le processus de conception choisi</a>. Les tests permettent de s’assurer que les bibliothèques de connaissances standards répondent bien à l’objectif initiale de modélisation (cas d’usage). Les tests permettent également de s’assurer qu’il n’y ait pas d’erreurs dans le code de la bibliothèque ou dans le déploiement sous forme de SADC basé sur cette bibliothèque. Les tests peuvent être effectués sur des données fictives.</li>
    <li><strong>L’évaluation rétrospective</strong> : l’évaluation de l’impact du SADC basé sur la ou les bibliothèques standards est une étape qui n’est pas couverte habituellement par les processus de développement logiciel. Une première étape d’évaluation de l’impact peut-être effectuée sur des données réelles rétrospectives. La bonne pratique la plus répondue pour effectuer des évaluations d’impact de SADC sur des données rétrospectives est l’utilisation des entrepôts de données cliniques [20](#ref20).</li>
    <li><strong>L’évaluation prospective (étude de recherche clinique non randomisée) </strong>: Elle est mise en œuvre dans le cadre d’une étude de recherche clinique. Il existe une catégorie d’étude de recherche clinique  non randomisée destinée à l’évaluation de l’impact des SADC appelée : Quasi-Experimental Studies [21](#ref21). </li>
    <li><strong>L’évaluation prospective randomisée </strong>: il s’agit de la catégorie de recherche clinique qui (dé)montre la preuve scientifique la plus importante. </li>
    </ul>
</div>

<h5 id = "principe-5">Principes #5 : Définir la relation avec les doctrines du CI-SIS et CGTS</h5>

Les artéfacts produits et gérés par le SI-CM sont en étroites relation avec ceux produits et gérés par le CI-SIS et le CGTS (voir chapitre précédent). Les artéfacts produits et gérés par le SI-CM peuvent réutiliser, tout ou partie des artéfacts produits et gérés par le CI-SIS et le CGTS.  

Les volets produits et gérés dans le cadre du SI-CM doivent, autant que faire se peut, partager les mêmes principes que le CI-SIS dans leur doctrine respective ou à défaut des principes qui ne se contredisent pas. La doctrine du SI-CM doit s’inscrire dans la continuité et / ou la complémentarité de celle du CI-SIS et du CGTS et vis vers ça.  

Les artéfacts de connaissances médicales qui suivent le principe de [l’architecture tri-dimensionnelle de Rector et al.](#archi-tri-dim) [15](#ref15)  doivent partager, autant que faire se peut, le même modèle d’information médicale que le CI-SIS et le même modèle de connaissance métier statique que le CGTS. 

<h4 id ="chemins-SI-CM">Les chemins de la doctrine du SI-CM</h4>

Ce paragraphe décrit une instanciation nominale (et plusieurs instanciations secondaires) de la doctrine du SI-CM basée sur les principes énoncés plus en amont. Cette instanciation correspond à une série de choix de standards, d’outils, de méthodes et de règles que le SI-CM devra respecter pour gérer les artéfacts de connaissances médicales issus de la standardisation des GBPC produits et/ou exposés par l’ANS. 

Ce chemin nominal n’est ni immuable ni parfait, il est et il sera donc sujet à mise à jour et / ou à des dérivations de chemins secondaires suivants les cas d’usage et l’évolution dans le temps des principes énoncés plus en amont.   

Dans ce qui suit nous décrivons le chemin nominal ainsi que les possibles chemins secondaires de la doctrine du SI-CM. 

<h5 id = "chemin-nominal">Le chemin nominal de la doctrine du SI-CM</h5>

[La doctrine du SI-CM](#cadre-SI-CM) est un ensemble d’activités consistants à identifier et à choisir, en se basant sur les principes de la doctrine, les standards, outils et autres méthodes qui permettront à l’ANS de concevoir et gérer les artéfacts de connaissances médicales standardisés.  

La figure 4 décrit un diagramme d’activité UML qui montre les activités d’identification des standards et outils en question. Toutes les activités en couleur verte ou vert bleuté correspondent à des activités du chemin nominal i.e. les outils et standards que l’ANS utilisera par défaut quel que soit le cas d’usage. Ces outils seront également ceux que l’écosystème devra utiliser dans le cas où l’ANS est saisie pour travailler sur un cas d’usage proposé par l’écosystème. Toutes les activités en bleu et vert bleuté correspondent à des chemins secondaires pour cette doctrine i.e. les cas où l’outil ou le standard préconisés par l’ANS ne répond pas au besoin du cas d’usage et nécessite d’investiguer d’autres outils ou standards.  

Dans ce qui suit nous justifions nos choix d’outils et/ou standards pour le chemin nominal décrits en figure 4 en faisant la relation avec les principes de la doctrine énoncés plus en amont. 

<h6 id ="relation-principes-activités">Relations entre les principes de la doctrine du SI-CM et les activités du chemin nominal instancié</h6>

<h7 id = "langage-modelisation">Choisir un langage de modélisation</h7>

Cette activité est en relation avec le principe #4 sur [l'adoption d'un processus de conception logiciel](#processus-conception-logiciel) énoncé en amont. Le langage de modélisation standard choisi pour illustrer les étapes de conception et de structuration des artéfacts de connaissances médicales issues des GBPC dans la doctrine du SI-CM est le langage standard UML version 2.0 [22](#ref22). 

Ce choix est justifié pour plusieurs raisons 
<div>
    <ul>
    <li>UML s’articule avec le principe #4 de la présente doctrine</li> 
    <li>UML est le langage standard de modélisation en informatique depuis l’avènement de la mouvance orientée objet</li> 
    <li>UML est actuellement utilisé par de nombreux projets de standardisation de la connaissance médicale</li>  
    <li>UML s’articule avec l’ensemble des autres standards choisis dans le chemin nominal de la présente doctrine</li> 
    </ul>
</div>

<h7 id = "processus-modelisation">Choisir un processus de modélisation</h7>

Cette activité est en relation avec le principe #4 sur [l'adoption d'un langage de modélisation standard](#archi-tri-dim) énoncé en amont. Le processus choisi pour encadrer le travail de conception et de structuration des artéfacts de connaissances médicales issues des GBPC dans la doctrine du SI-CM est le processus Agile décrit dans le FHIR IG CPG-on-FHIR [23](#ref23). 

Ce choix est justifié pour plusieurs raisons :
<div>
    <ul>
    <li>FHIR IG CPG-on-FHIR <a href ="#ref23">23</a> s’articule avec les principes #4 de la présente doctrine</li> 
    <li>FHIR IG CPG-on-FHIR <a href ="#ref23">23</a> s’articule avec l’ensemble des autres standards choisis. FHIR IG CPG-on-FHIR <a href ="#ref23">23</a> permet de mettre en œuvre ensemble les différents modèles préconisés par l’architecture tri-dimensionnelle de Rector et al.<a href ="#ref15">15</a> il permet de mettre en œuvre le standard UML pour illustrer les différentes étapes de conception. Il permet de mettre en œuvre la représentation multi couches de la connaissance médicale de Boxwala et al. <a href ="#ref16">16</a>.</li> 
    <li>FHIR IG CPG-on-FHIR <a href ="#ref23">23</a> est actuellement utilisé par de nombreux projets de standardisation de la connaissance médicale</li>  
    </ul>
</div>

<h7 id = "modele-info-standard">Choisir un modèle d'information standard</h7>

Cette activité est en relation avec le principe #4, [l’architecture tri-dimentionnel de Rector et al.](#archi-tri-dim) [15](#ref15) et les principes #1, #2, #3 et #5 énoncés en amont. Le modèle d’information standard choisi pour standardiser les informations issues du dossier patient est FHIR en version R4 [24](#ref24). 

Ce choix est justifié pour plusieurs raisons :
<div>
    <ul>
    <li>FHIR en version R4 s’articule avec l’ensemble des principes énoncés en amont</li>   
    <li>FHIR en version R4 s’articule avec l’ensemble des autres standards choisis</li>
    <li>FHIR en version R4 s’articule avec les autres modèles correspondants au principe d’architecture tri-dimensionnelle de Rector et al. La figure 3 illustre l’instanciation de ce principe avec les différents modèles choisis pour la présente doctrine.</li>
    <li>FHIR en version R4 est actuellement utilisé par de nombreux projets de standardisation de la connaissance médicale</li>   
    <li>FHIR en version R4 s’articule avec le choix de la doctrine du CI-SIS</li>   
    </ul>
</div>

<h7 id = "modele-connaissance-statique">Choisir un modèle de connaissances statiques standard</h7>

Cette activité est en relation avec le principe #4, [l’architecture tri-dimentionnel de Rector et al.](#archi-tri-dim) [15](#ref15) et les principes #1, #2, #3 et #5 énoncés en amont. La ou les terminologies médicales choisies pour structurer les artéfacts de connaissances issus de la standardisation des GBPC sont celles recommandées par la doctrine du CGTS. 

Ce choix est justifié pour plusieurs raisons :
<div>
    <ul>
    <li>Les terminologies gérées par le CGTS (via le SMT) s’articulent avec l’ensemble des principes énoncés en amont</li> 
    <li>Les terminologies gérées par le CGTS (via le SMT) s’articulent avec l’ensemble des autres standards choisis </li> 
    <li>Les terminologies gérées par le CGTS (via le SMT) s’articulent avec les autres modèles correspondants au principe d’architecture tri-dimensionnelle de Rector et al [15](#ref15). La figure 3 illustre l’instanciation de ce principe avec les différents modèles choisis pour la présente doctrine.</li>  
    <li>Les terminologies gérées par le CGTS (via le SMT) sont actuellement utilisées par de nombreux projets de standardisation de la connaissance médicale</li> 
    <li>Les terminologies gérées par le CGTS (via le SMT) s’articulent avec la doctrine du CGTS</li>
    </ul>
</div>

<h7 id = "modele-connaissance-dynamique">Choisir un modèle de connaissances dynamiques standard</h7>

Cette activité est en relation avec le principe #4, [l’architecture tri-dimentionnel de Rector et al.](#archi-tri-dim) [15](#ref15) et les principes #1, #2, #3 et #5 énoncés en amont. Le modèle de connaissances dynamiques choisie pour standardiser l’écriture des artéfacts de connaissances médicales issues des GBPC est CQL [25](#ref25).  

Ce choix est justifié pour plusieurs raisons :
<div>
    <ul>
    <li>CQL s’articule avec l’ensemble des principes énoncés en amont</li>
    <li>CQL s’articule avec l’ensemble des autres standards choisis : UML, FHIR R4, CDS Hooks,…</li>
    <li>CQL s’articule avec les autres modèles correspondants au principe d’architecture tri-dimensionnelle de Rector et al. La figure 3 illustre l’instanciation de ce principe avec les différents modèles choisis pour la présente doctrine.</li> 
    <li>CQL est actuellement utilisé par de nombreux projets de standardisation de la connaissance médicale</li> 
    <li>CQL s’articule avec la doctrine du CI-SIS et la doctrine du CGTS</li>
    </ul>
</div>


<div class="figure" style='text-align: center;'>
    <img src="FIGURE 3  Instanciation du modèle de Rector et al. avec l’ensemble des standards utilisés dans le chemin nominal de la doctrine du SI-CM.png" alt="rector_et_al" title="FIGURE 3 : Instanciation du modèle de Rector et al. avec l’ensemble des standards utilisés dans le chemin nominal de la doctrine du SI-CM" style="width:50%;">
    <figcaption><b>FIGURE 3 : Instanciation du modèle de Rector et al. avec l’ensemble des standards utilisés dans le chemin nominal de la doctrine du SI-CM</b></figcaption>
</div>


<h7 id="standard-integration">Choisir un standard d'intégration</h7>

Cette activité est en relation avec le principe #4, [l’intégration standardisée des SADC basés sur les GBPC dans un SI de santé](#integration-SADC). Le standard d’intégration de la connaissance médicale sous forme de SDAC choisi par l’ANS est le standard CDS Hooks [19](#ref19).  

Ce choix est justifié pour plusieurs raisons :
<div>
    <ul>
    <li>CDS Hooks s’articule avec l’ensemble des principes énoncés en amont</li> 
    <li>CDS Hooks est le seul standard d’intégration de SAD basés sur la standardisation des GBPC qui puisse s’articuler avec les standards choisis dans le chemin nominal de la présente doctrine : UML, FHIR R4, CQL,…</li> 
    <li>CDS Hooks est actuellement utilisé par de nombreux projets de standardisation de la connaissance médicale</li> 
    </ul>
</div>

<h7 id ="licence-publication">Choisir une licence de publication</h7>

Cette activité est en relation avec le principe #3 et le principe #5 de la présente doctrine. Tous les artéfacts de connaissances médicales publiés dans le cadre du SI-CM doivent l’être sous la licence « Licence Ouverte Version 2.0 » (Lov2) d’Etalab [26](#ref26). 

Ce choix est justifié pour plusieurs raisons :
<div>
    <ul>
    <li>La licence « Licence Ouverte Version 2.0 » (Lov2) suit la logique du mouvement de l’Open Data</li>   
    <li>La licence « Licence Ouverte Version 2.0 » (Lov2) est celle choisie par la doctrine du CGTS</li> 
    </ul>
</div>

<h7 id ="format-publication">Choisir un format de publication standard</h7>

Cette activité est en relation avec le principe #1, #2, #3 et #5 de la présente doctrine. Les artéfacts de connaissances médicales définis et / ou exposés dans le cadre du SI-CM doivent être publiés suivant le format FHIR ImplementationGuide (IG). 

Ce choix est justifié pour plusieurs raisons :
<div>
    <ul>
    <li>FHIR ImplementationGuide (IG) s’articule avec l’ensemble des principes énoncés en amont</li>  
    <li>FHIR ImplementationGuide (IG) avec l’ensemble des standards choisis dans le cadre du chemin du nominal de la présente doctrine : UML, FHIR R4, CQL, …</li>  
    <li>FHIR ImplementationGuide (IG) est actuellement utilisé dans de nombreux exemples de mises en œuvre de projet en lien avec la standardisation de la connaissance médicale</li>   
    <li>FHIR ImplementationGuide (IG) s’articule avec la doctrine du CI-SIS</li> 
    </ul>
</div> 

<div class="figure" style='text-align: center;'>
    <img src="Figure 4 Diagramme d’activité UML pour illustrer les choix du chemin nominal de la doctrine du SI-CM et les possibles chemins secondaires.svg" alt="choix_nominal" title="Figure 4 : Diagramme d’activité UML pour illustrer les choix du chemin nominal de la doctrine du SI-CM et les possibles chemins secondaires" style="width:100%;">
    <figcaption><b>Figure 4 : Diagramme d’activité UML pour illustrer les choix du chemin nominal de la doctrine du SI-CM et les possibles chemins secondaires</b></figcaption>
</div>



<h5 id ="chemins-secondaires">Les chemins secondaires de la doctrine du SI-CM</h5>

Les choix effectués dans le chemin nominal de la présente doctrine ne sont pas et ne doivent pas être définitifs. Ces choix peuvent être remis en question pour de nombreuse raisons 
<div>
    <ul>
    <li>Le standard choisi n’est plus d’actualité</li>   
    <li>Le standard choisi n’a pas évolué par rapport aux autres standards</li>  
    <li>Il existe un ou plusieurs standards plus adaptés à un cas d’usage donné</li>  
    <li>Un ou plusieurs principes de la présente doctrine ou de la doctrine du CI-SIS et/ou du CGTS ont évolué</li>  
    <li>…</li>
    </ul>
</div>   

Il est donc nécessaire de laisser la porte ouverte à chaque étape de se poser la question de faire un autre choix de standard, d’outils ou autres méthodes. Pour cela, il est nécessaire que l’ensemble des parties prenantes  
<div>
    <ul>
    <li>Soient interrogés en cas de nouveaux choix effectués par l’ANS</li> 
    <li>Aient la possibilité de proposer de nouveaux choix à l’ANS pour un cas d’usage donné</li>
    </ul>
</div>  

A l’image de la doctrine du CI-SIS ou de la doctrine du CGTS, la présente doctrine définie une procédure de consultation sur les différentes étapes où un autre choix est possible. La procédure de consultation comprend résolument les mêmes étapes que celles décrites dans la doctrine du CI-SIS [1](#ref1).  

Les chemins secondaires #1, #2, #3, #4, #5, #6 et #8 décrits dans la figure 4 sont concernés par cette procédure de consultation. 

Les choix faits au cours de ces chemins secondaires doivent impérativement respecter les principes de la présente doctrine. Ils doivent être des instances de ces principes, à l’image de l’instanciation du chemin nominal.  

Le chemin secondaire #7 concerne la propriété intellectuelle des artéfacts de connaissances médicales produits et/ou exposés par le SI-CM. A l’image de la doctrine du CGTS [1](#ref1), un acteur de l’éco système peut décider de distribuer ses artéfacts de connaissances sous un autre régime de propriété intellectuelle que la Licence Lov2 choisie dans le chemin nominal de la présente doctrine. Ce choix de licence de diffusion résultera des négociations entre le SI-CM et l’Unité de Production (UP) lors de l’établissement de la convention de mise à disposition des artéfacts en question.  

La notion d’UP et de conventions entre l’ANS et les UPs sont celles définies dans la gouvernance du CI-SIS [27](#ref27). 

<h4 id = "relation-gouvernance">La relation avec la gouvernance</h4>

Cette doctrine respecte les étapes et les règles de gouvernance énoncés dans la gouvernance du CI-SIS [27](#ref27). 

<h4 id = "ref">Références</h4>

<p id="ref1"> 1. Le CI-SIS au cœur du développement de la e-santé [Internet]. [cited 2024 Aug 29]. Available from: <a href ="https://interop.esante.gouv.fr/ig/doctrine/ImplementationGuide/ans.fr.doctrine">lien</a> </p>

<p id="ref2"> 2. Doctrine. In: Wikipédia [Internet]. 2024 [cited 2024 Aug 29]. Available from:<a href ="https://fr.wikipedia.org/w/index.php?title=Doctrine&oldid=212118223">lien</a> </p> 

<p id="ref3"> 3. LOI n° 2016-1321 du 7 octobre 2016 pour une République numérique. 2016-1321 Oct 7, 2016.</p>

<p id="ref4"> 4. GO FAIR [Internet]. [cited 2024 Aug 29]. FAIR Principles. Available from: <a href="https://www.go-fair.org/fair-principles/">lien</a></p>

<p id="ref5"> 5. Open data. In: Wikipedia [Internet]. 2024 [cited 2024 Aug 29]. Available from: <a href ="https://en.wikipedia.org/w/index.php?title=Open_data&oldid=1238576109">lien</a> </p>

<p id="ref6"> 6. Open Data 5 étoiles [Internet]. [cited 2024 Aug 29]. Available from: <a href="http://5stardata.info/fr/">lien</a></p> 

<p id="ref7"> 7. Gamma E, Helm R, Johnson R, Vlissides J. Design Patterns: Elements of Reusable Object-Oriented Software. 1er édition. Boston, Mass. Munich: Addison Wesley; 1994. 416 p. </p>

<p id="ref8"> 8. Martin R. Clean Code: A Handbook of Agile Software Craftsmanship. 1er édition. Upper Saddle River, NJ: Pearson; 2008. 464 p.</p>

<p id="ref9"> 9. The Pragmatic Programmer: your journey to mastery, 20th Anniversary Edition, 2nd Edition[Book] [Internet]. [cited 2024 Aug 29]. Available from: <a href="https://www.oreilly.com/library/view/the-pragmatic-programmer/9780135956977/">lien</a> </p>

<p id="ref10"> 10. Martin RC. Agile Software Development: Principles, Patterns, and Practices. USA: Prentice Hall PTR; 2003. 710 p.</p>

<p id="ref11"> 11. Schreiber GT, Akkermans H. Knowledge engineering and management: the CommonKADS methodology. Cambridge, MA, USA: MIT Press; 2000. </p>

<p id="ref12"> 12. giantchair.com. Artificial Intelligence: A Modern Approach - Pearson France [Internet]. [cited 2024 Aug 29]. Available from: <a href="https://www.pearson.fr/fr/book/?GCOI=27440100705580">lien</a> </p>

<p id="ref13"> 13. Ambler SW. The Object Primer: Agile Model-Driven Development With Uml 2.0. 3e édition. Cambridge, UK : New York: Cambridge University Press; 2004. 572 p.</p> 

<p id="ref14"> 4. Rumbaugh J, Jacobson I, Booch G. Unified Modeling Language Reference Manual, The (2nd Edition). Pearson Higher Education; 2004.</p> 

<p id="ref15"> 15. Rector AL, Johnson PD, Tu SW, Wroe C, Rogers J. Interface of Inference Models with Concept and Medical Record Models. In: Quaglini S, Barahona P, Andreassen S, editors. Artificial Intelligence Medicine, 8th Conference on AI in Medicine in Europe, AIME 2001, Cascais, Portugal, July 1-4, 2001, Proceedings [Internet]. Springer; 2001 [cited 2024 Aug 29]. p. 314–23. (Lecture Notes in Computer Science; vol. 2101). Available from: <a href="https://doi.org/10.1007/3-540-48229-6\_43">lien</a> </p>

<p id="ref16"> 16. Boxwala AA, Rocha BH, Maviglia S, Kashyap V, Meltzer S, Kim J, et al. A multi-layered framework for disseminating knowledge for computer-based decision support. Journal of the American Medical Informatics Association. 2011 Dec 1;18(Supplement_1):i132–9.</p>

<p id="ref17"> 17. Graham ID, Logan J, Harrison MB, Straus SE, Tetroe J, Caswell W, et al. Lost in knowledge translation: Time for a map? Journal of Continuing Education in the Health Professions. 2006;26(1):13–24. </p>

<p id="ref18"> 18. Marcial LH, Blumenfeld B, Harle C, Jing X, Keller MS, Lee V, et al. Barriers, Facilitators, and Potential Solutions to Advancing Interoperable Clinical Decision Support: Multi-Stakeholder Consensus Recommendations for the Opioid Use Case. AMIA Annu Symp Proc. 2019;2019:637–46. </p>

<p id="ref19"> 19. CDS Hooks [Internet]. [cited 2018 Apr 12]. Available from: <a href="http://cds-hooks.org/">lien</a></p>

<p id="ref20"> 20. Boussadi A, Caruba T, Zapletal E, Sabatier B, Durieux P, Degoulet P. A clinical data warehouse-based process for refining medication orders alerts. Journal of the American Medical Informatics Association. 2012 Sep 1;19(5):782–5. </p>

<p id="ref21"> 21. Harris AD, McGregor JC, Perencevich EN, Furuno JP, Zhu J, Peterson DE, et al. The Use and Interpretation of Quasi-Experimental Studies in Medical Informatics. Journal of the American Medical Informatics Association. 2006 Jan 1;13(1):16–23</p>

<p id="ref22"> 22. About the Unified Modeling Language Specification Version 2.0 [Internet]. [cited 2024 Aug 29]. Available from: <a href="https://www.omg.org/spec/UML/2.0/">lien</a></p>

<p id="ref23"> 23. CPG Home - Clinical Practice Guidelines v2.0.0-ballot [Internet]. [cited 2024 Aug 30]. Available from: <a href="https://hl7.org/fhir/uv/cpg/2024Jan/">lien</a></p>

<p id="ref24"> 24. Http - FHIR v4.0.1 [Internet]. [cited 2021 Dec 1]. Available from: <a href="https://www.hl7.org/fhir/http.html">lien</a></p>

<p id="ref25"> 25. Clinical Quality Language (CQL) [Internet]. [cited 2024 Aug 30]. Available from: <a href="https://cql.hl7.org/">lien</a></p>

<p id="ref26"> 26. Etalab Licence Ouverte V2.0 [Internet]. 2017. Available from: <a href="https://www.etalab.gouv.fr/wp-content/uploads/2017/04/ETALAB-Licence-Ouverte-v2.0.pdf">lien</a></p>

<p id="ref27"> 27. Généralités sur la Gouvernance du CI-SIS [Internet]. [cited 2024 Aug 30]. Available from: <a href="https://interop.esante.gouv.fr/ig/doctrine/ImplementationGuide/ans.fr.doctrine">lien</a></p>

<p id="ref28"> 28. Michaels M. Adapting Clinical Guidelines for the Digital Age: Summary of a Holistic and Multidisciplinary Approach. American Journal of Medical Quality. 2023 Oct;38(5S):S3.</a></p>
