# Choix des normes et standard - Doctrine et gouvernance du cadre d'interopérabilité des systèmes d'informations en santé (CI-SIS) v0.1.1

* [**Table of Contents**](toc.md)
* **Choix des normes et standard**

## Choix des normes et standard

L’étude des normes et standards est optionnelle. Elle intervient lorsqu’il est nécessaire de sélectionner une norme ou un standard (syntaxique, sémantique ou technique) cible qui n’est pas encore utilisé dans le CI-SIS pour répondre aux cas d’usage identifiés par l’étude fonctionnelle des échanges.

Au cours de cette étude, chaque solution technique et sémantique est analysée de façon approfondie et catégorisée selon différents critères de façon à pouvoir justifier du choix final retenu.

Le contenu de l’étude des normes et standards est le suivant :

* Introduction
* Présentation des solutions envisagées. 
* Comparaison des solutions
* Analyse SWOT de chaque solution
* Résultat d’un sondage
* Conclusion et proposition d’une solution

Il s’agit de présenter l’objet du document, de rappeler l’étude fonctionnelle des échanges réalisée au préalable, de résumer en quelques phrases le(s) cas d’usage adressés par cette étude et de citer les flux d’information pour lesquels un choix de norme ou de standard doit être réalisé.

Les solutions pressenties (norme/standard, profil IHE ou guide d’implémentation FHIR) sont listées.

Chacune des solutions proposées en introduction fait l’objet d’une étude détaillée. Les points suivants peuvent être analysés :

* Présentation de l’organisation en charge du développement de la solution envisagée ;
* Présentation et périmètre de la solution envisagée ;
* Norme(s)/standard(s) sous-jacent(s) ;
* Description de scénarii d’implémentation possibles. Dans certains cas, il est possible qu’il soit nécessaire de détailler différents scénarii d’implémentation pour compléter l’analyse ;
* Description de l’organisation de la documentation ;
* Processus d’élaboration et de gouvernance ;
* Maturité et degré d’adoption de la solution ;
* Estimation de l’effort à produire (faible, moyen, important) ;
* Outillage à disposition.

### Comparaison des solutions

Les normes/standards ou solutions envisagées sont comparées à l’aide d’un tableau selon différents critères.

Exemple de tableau de comparaison :

| | | |
| :--- | :--- | :--- |
| **Neutralité**: Les spécifications ne limitent pas la concurrence et l’innovation ; Les spécifications sont basées sur des développements scientifiques et technologiques de pointe. |   |   |
| **Qualité/maturité**: La qualité est suffisante pour permettre le développement de produits et de services interopérables concurrents. |   |   |
| **Accessibilité**: les spécifications sont disponibles au public à des conditions raisonnables (y compris pour un prix raisonnable ou gratuitement). |   |   |
| **Stabilité de la documentation** |   |   |
| **Couverture des spécifications** |   |   |
| **Existence de guides d’implémentation**: Les guides référencent les standards de base avec au moins un cas d’usage et une optionalité sur les paramètres pour permettre les extensions. |   |   |
| Processus de prise en compte des améliorations |   |   |
| **Outillage**: Des outils de tests sont mis en œuvre pour valider l’adhérence au standard. |   |   |
| **Tests**: Des tests sont effectués pour des versions de travail (dites STU -Standards for Trial Use) et/ou pour les guides d’implémentation normatifs. |   |   |
| **Adapté aux dispositifs mobiles** |   |   |
| **Mise en œuvre existantes du cas d’usage** |   |   |
| **Adoption par le marché et utilisation** |   |   |

### Analyse SWOT

Le tableau de maturité précédant peut être complété par une analyse SWOT qui permet d’évaluer plus finement les forces (Strengths), les faiblesses (Weaknesses), les opportunités (Opportunities) et les menaces (Threats) de chacune des options envisagées dans les étapes précédentes.

**Forces : caractéristiques de la solution qui lui donnent un avantage sur les autres**

A ce niveau, on cherchera à évaluer les points clés suivants :

* Réutilisation et intégration : mesure la capacité des composants et des éléments sémantiques choisis à être réutilisés dans d’autres contextes.
* Scalabilité et adaptabilité : capacité du standard et de ses éléments sémantiques à s’étendre et à s’adapter aux exigences d’évolution futures.
* Performance et fiabilité : mesure la capacité de la solution à être performante d’un point de vue opérationnelle, fiable et rapide.
* Utilisabilité et accessibilité : mesure la facilité d’utilisation des utilisateurs finaux, considérant à la fois l’interface technologique et la précision sémantique des choix réalisés.
* Intégration des données et précision sémantique : mesure la capacité de la technologie à gérer des données fiables et complètes mais également précises du point de vue sémantique de façon à répondre aux exigences des solutions d’aide à la décision.
* Faisabilité de l’implémentation : mesure la capacité du standard et de ses éléments sémantiques à s’intégrer aux infrastructures existantes sur le terrain ainsi qu’aux pratiques opérationnelles.

**Faiblesses : caractéristiques de la solution qui désavantagent cette solution par rapport aux autres**

chacun des points clés cités précédemment peut faire l’objet d’une faiblesse. A ces axes d’analyse s’ajoute par exemple le manque de support, la dynamique de l’organisation en charge de la solution ou du standard, la courbe d’apprentissage, les coûts élevés de développement et de maintenance, etc.

**Opportunités : éléments de l’environnement que la solution pourrait exploiter à son avantage**

A ce niveau, on cherchera à évaluer les tendances du marché. Il s’agit de déterminer si la solution envisagée fait partie d’un marché émergent et permet de gagner en compétitivité et en innovation. L’évaluation des aspects d’évolutivité et de généralisation de la solution est primordiale.

**Menaces : éléments de l’environnement qui pourraient causer des problèmes concernant le choix de la solution.**

On cherchera à évaluer les risques externes susceptibles de menacer le choix réalisé, tels que la saturation du marché, l’évolution de la règlementation qui pourrait remettre en cause ce choix, l’obsolescence technologique, la dépendance trop forte à une technologie ou à un éditeur, l’incapacité à migrer vers une autre technologie, etc

Cette analyse SWOT est ensuite représentée sous la forme d’un tableau qui permet de visualiser comment les risques internes (Forces et faiblesses) et externes (Opportunités et Menaces) à la solution interagissent et affectent la stratégie du choix de la solution envisagée.

**Matrice SWOT**

| | |
| :--- | :--- |
| Strenghs | **Weaknesses** |
| **Identification des avantages** : quels sont les bénéfices et les avantages compétitifs de la solution (cf critères cités précédemment pour les Forces) ?**Evaluer les succès d’implémentation passés de la solution****Accès au support et à l’expertise** : avons-nous au niveau national la capacité à supporter les éditeurs et à apporter de l’expertise concernant la solution ?**Evaluer la disponibilité des ressources** : ressources financières, humaines ou matérielles sur lesquelles il est possible de s’appuyer.**Evaluer le degré d’adoption** : l’écosystème a-t-il déjà connaissance de la solution envisagée et l’a-t-il déjà adoptée en partie ?**Passer en revue les outils et les ressources disponibles** : existence de guides d’implémentation, outils de tests disponibles. | **Evaluer les limitations de la solution envisagée** : tous les aspects évalués lors de l’analyse des forces peuvent faire l’objet d’une faiblesse**Analyser les retours d’expérience passés** : quels sont les retours d’expérience d’une implémentation passée au niveau international ?**Accès aux ressources** : les ressources (financières, matérielles, en expertise) sont-elles suffisantes ?**Impact des faiblesses** : quel est l’impact des faiblesses de la solution sur la capacité à atteindre les objectifs poursuivis ?**Outils et ressources disponibles** |
| **Opportunities** | **Threats** |
| **Exploration des capacités de la solution **: quelles capacités spécifiques à la solution peuvent répondre aux objectifs poursuivis ?**Identifier les tendances du marché** **Evaluer les possibilités de collaboration** : collaboration et partenariats qui pourraient aider à l’implémentation de la solution choisie**Analyser le contexte réglementaire** : le contexte réglementaire est-il favorable au choix de la solution envisagée ?**Evaluer l’aspect financier** : quelles possibilités de budget (interne ou externe) pour supporter l’initiative ?  | **Evaluer les risques et les défis****Evaluer l’obsolescence de la solution** : nécessite d’anticiper les stratégies de maintenance des normes/standards et des solutions développées par les organisations en charge de ces spécifications.**Impact réglementaire** : nécessite de connaître la réglementation en vigueur et d’anticiper les évolutions.**Evaluer les coûts de développement, de maintenance et de ressources****Evaluer les délais potentiels de mise en œuvre** : quels facteurs pourraient retarder l’adoption et l’implémentation de la solution ?**Evaluer le degré d’acceptation** par l’écosystème**Evaluer les coûts additionnels de licence** : la solution choisie nécessite t’elle des coûts additionnels de souscription ou de licence (notamment pour les aspects sémantiques) ?**Evaluer la fin de la maintenance de la solution par l’organisation qui la porte** : durabilité à long terme de la solution et quelles sont les trajectoires prévues en cas de fin de maintenance ? |

### Résultat de sondage

Dans certains cas, il peut être envisagé de réaliser un sondage auprès d’un groupe restreint préalable à la phase de concertation publique. Dans ce cas, les résultats de ce sondage sont consignés au niveau de ce chapitre.

### Conclusion et proposition d’une solution

Dans certains cas, il peut y avoir une mise en concertation publique de l’étude des normes et standards, qui justifie la solution envisagée (norme/standard, profil IHE, guide d’implémentation FHIR, etc.).

