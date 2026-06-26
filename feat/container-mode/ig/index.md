# Accueil - Doctrine et gouvernance du cadre d'interopérabilité des systèmes d'informations en santé (CI-SIS) v0.1.1

* [**Table of Contents**](toc.md)
* **Accueil**

## Accueil

| | |
| :--- | :--- |
| *Official URL*:https://interop.esante.gouv.fr/ig/doctrine/ImplementationGuide/ans.fr.doctrine | *Version*:0.1.1 |
| Draft as of 2026-06-26 | *Computable Name*:DoctrineCISIS |

 **Brief description of this Implementation Guide**
 The interoperability framework for health information systems (CI-SIS) sets the rules for exchanging and sharing health data on the same standards. It is managed by the ANS in collaboration with the entire ecosystem. This implementation guide outlines the doctrine and governance that apply to this framework. 

>  **Attention !** Cette version de l'Implementation Guide est en intégration continue (version de travail) et est soumise à des changements réguliers. La version officielle est accessible à l'adresse [https://interop.esante.gouv.fr/ig/doctrine](https://interop.esante.gouv.fr/ig/fhir/doctrine) 

[L’Agence du Numérique en Santé (ANS)](https://esante.gouv.fr/) accompagne la transformation numérique du système de santé aux côtés de tous les acteurs concernés des secteurs sanitaire, social et médico-social, privés comme publics, professionnels ou usagers.  Elle met en œuvre les orientations dédiées au secteur de la santé et du médico-social, à travers trois ambitions.

* **Régulatrice** : elle améliore la performance numérique grâce à des règles communes de régulation et d’échanges ; 
* **Opératrice** : elle conçoit les grands e-programmes nationaux pour un service public de santé efficace et solidaire ; 
* **Promotrice et valorisatrice** : elle stimule, accompagne et évalue toutes les initiatives de e-santé pour les faire grandir. 

Dans le rôle de **régulateur** ayant pour ambition de développer la capacité des systèmes d’information en santé à partager et échanger des données de santé de manière fluide, efficace et sécurisée, l’Agence porte la construction d’un cadre commun comprenant l’interopérabilité, la sécurité et l’éthique, permettant ainsi le développement de la e-santé entre l’ensemble des acteurs, et en particulier avec les solutions de la puissance publique, dans le cadre retenu de l’Etat-plateforme.

Ce cadre commun sur l’interopérabilité :

* **Soutient la dématérialisation des processus en santé**, en permettant d’apporter de la valeur ajoutée via le numérique en santé
* **Est au profit des patients, de leur prise en charge, des parcours de soin**
* **Est aussi au profit des professionnels de santé et des établissements de santé**, afin de permettre la généralisation, le passage à l’échelle, de cas d’usage métier où le numérique en santé contribue à apporter de la valeur ajoutée dans leurs pratiques
* **S’adresse tout particulièrement aux ENS (Entreprises du Numérique en Santé)** pour l’implémentation de ce cadre commun dans leurs solutions qui peuvent alors échanger et partager de manière plus fluide, efficace et sécurisée des données de santé. Les ENS peuvent ainsi industrialiser les déploiements et aussi proposer des services à valeur ajoutée (toujours dans le cadre de l’Etat-plateforme)

Ce cadre commun d’interopérabilité, le CI-SIS (Cadre d’Interopérabilité des Systèmes d’Information de Santé) :

* comprend l’ensemble des spécifications définissant les informations à échanger ou partager entre les systèmes d’information de santé et identifie la norme ou le standard le plus approprié à utiliser pour cet échange ou partage : c’est ce qu’on appelle « l’interopérabilité technique »
* via la définition de la structuration du contenu médical, il identifie le langage adéquat pour présenter des informations selon les standards et les normes reconnus ainsi que le vocabulaire à utiliser pour coder l’information. Ceci permet de faciliter le traitement automatique de l’information et permet la mise en œuvre de services à valeur ajoutée. C’est ce qu’on appelle « l’interopérabilité syntaxique et sémantique »

### Les enjeux du développement du CI-SIS

Afin de répondre à ces ambitions, la construction de ce cadre comme d’interopérabilité, le CI-SIS doit relever plusieurs enjeux, dont tout particulièrement :

* S’assurer de répondre à des **cas d’usage prioritaires** (la feuille de route du numérique en santé, les programmes nationaux tels que le Ségur du Numérique en Santé, les référentiels, les échanges avec et entre les services numériques socles, l’élaboration des référentiels de conformité … ), avec l’identification de ces cas d’usage, leur priorisation et un contrôle de la pertinence de la réponse technique au besoin ;
* S’inscrire dans un **cadre résolument international**, en particulier avec les travaux IHE, HL7, DICOM, de façon à bénéficier des travaux réalisés de ces communautés et de limiter ainsi le coût d’implémentation de la déclinaison française de l’interopérabilité. En complément, avec la mise en œuvre de l’EEDS (Espace Européen des Données de Santé), le cadre européen d’interopérabilité s’imposera aussi aux Etats membres, qui sera donc évidemment repris dans le CI-SIS
* Garantir la **co-construction de ce cadre commun**, en s’assurant que chacun puisse être acteur aux différents niveaux : identification de cas d’usage, formalisation précise du besoin, propositions techniques, expérimentations et retours terrain, etc
* Maintenir **une lisibilité d’un CI-SIS** en croissance, en particulier sur les contributions attendues et leurs modalités mais aussi sur le contenu validé et son niveau de maturité, i.e. la confiance dans sa capacité à répondre au besoin
* Construire et opérer **un outillage permettant de valider la bonne implémentation** des référentiels du CI-SIS dans les solutions des ENS, de façon à 
* **promouvoir, valoriser** le contenu du CI-SIS et **accompagner** les acteurs dans la mise en œuvre via des webinaires et aussi de l’outillage de tests, la réalisation de tests techniques lors des projectathons, la réalisation de pilotes (et projectathons usage) permettant de **tester** les solutions, les référentiels du CI-SIS et **l’adéquation aux cas d’usage** et d’intégrer ces éléments dans l’évolution du CI-SIS

Les différentes réponses à ces enjeux du cadre commun CI-SIS sont ainsi portées par :

* **Une doctrine du CI-SIS** qui formalise les règles régissant la constitution et l’évolution du contenu du CI-SIS : trajectoire générale de l’interopérabilité, choix des normes et standards, cycle de vie des référentiels, modalités de contribution et concertation de l’écosystème, formalisation du contenu des référentiels
* **Une gouvernance du CI-SIS** qui favorise la co-construction, instruit et arbitre les priorités des travaux et évolutions du CI-SIS par rapport aux cas d’usage et donne de la visibilité aux différents acteurs sur les orientations stratégiques du CI-SIS.

### Une évolution volontariste dans la continuité

Sous l’impulsion de la première feuille de route du numérique en santé (masanté 2022), du Ségur numérique, et d’évolutions réglementaires récentes au niveau français et européen, l’interopérabilité et le rôle de régulation de l’Agence évoluent fortement :

* A travers le **Ségur numérique** Vague 1 ont été mis en place de manière massive les « canaux » de partage et d’échange de données de santé via MES/DMP et la MSSanté. Si la consultation du DMP dans les logiciels des PS sera développée / améliorée avec la Vague 2, le focus devrait ainsi se porter **à court terme sur le développement de cas d’usage** via le numérique en santé (et moins sur des sujets technique de mise en place de ces canaux) ;
* Le rôle de l’Agence **en tant que régulateur** du numérique en santé sur les champs de l’interopérabilité, de la sécurité et de l’éthique a été confirmé, en particulier dans la mission de contrôle de conformité des solutions aux référentiels, ayant vocation à être complété à court terme par un dispositif de sanction ;
* **La mise en œuvre de l’EEDS et d’un futur cadre européen de l’interopérabilité**, impliquant de promouvoir le cadre déjà mis en œuvre au niveau national, mais aussi d’assurer la transition vers le future cadre européen. Il sera aussi nécessaire de poursuivre le développement des outils permettant de valider de manière automatique la conformité des solutions des ENS ;
* **Le développement des EDS** (Entrepôts de Données de Santé) et de l’usage secondaire des données de santé, porté aussi fortement par l’EEDS, met directement en exergue le besoin de qualité des données numériques de santé, et donc d’interopérabilité ;
* **L’IA en santé** ouvre aussi des perspectives particulièrement stimulantes pour l’interopérabilité

Alors que le CI-SIS existe depuis de nombreuses années, que la gouvernance a déjà été revue, il apparait ainsi important de s’engager dans une évolution de la doctrine du CI-SIS et de sa gouvernance via des propositions d’adaptation et de renforcement, dans une approche :

* résolument volontariste, afin de répondre concrètement aux enjeux et fortes attentes des prochains mois et années du numérique en santé
* dans la continuité, en capitalisant sur les efforts déjà consentis et les réussites du CI-SIS.

### Glossaire

Les termes suivants sont utilisés dans ce document et peuvent nécessiter des besoins de précisions.

| | |
| :--- | :--- |
| CGTS | Centre de Gestion des Terminologies de Santé. C’est le guichet national de diffusion des terminologies en usage en France. |
| Terminologies | Ensemble des ressources sémantiques telles que les terminologies, classifications, nomenclatures, ontologies, jeux de valeurs, alignements sémantiques etc. |
| Interopérabilité syntaxique ou technique | capacité de différents systèmes ou applications à échanger des données en respectant un même format et des protocoles standardisés (ex : XML, JSON, HL7 v2, HL7 FHIR). Elle garantit que les données peuvent être correctement envoyées, reçues et traitées, mais sans assurer qu’elles aient le même sens pour tous les systèmes. L’interopérabilité sémantique intervient ensuite pour donner un sens commun aux données échangées. |
| Interopérabilité sémantique | capacité des systèmes à interpréter et comprendre les données échangées de manière identique et cohérente. Elle repose sur des vocabulaires contrôlés, des ontologies et des terminologies (ex : SNOMED CT, LOINC) pour assurer une compréhension commune du sens des informations échangées. |
| Volet du CI-SIS | spécification d’interopérabilité qui peut être au format PDF ou guide d’implémentation (IG) |
| IHE | Integrated The Healthcare Enterprise, initiative internationale qui a pour but d’améliorer l’interopérabilité dans le domaine de la santé. |
| Profil IHE | Les profils IHE décrivent des solutions spécifiques aux problèmes d’interopérabilité. Les profils précisent comment les « acteurs » utilisent les normes/standards pour traiter un cs d’utilisation spécifique des soins de santé. |



## Resource Content

```json
{
  "resourceType" : "ImplementationGuide",
  "id" : "ans.fr.doctrine",
  "url" : "https://interop.esante.gouv.fr/ig/doctrine/ImplementationGuide/ans.fr.doctrine",
  "version" : "0.1.1",
  "name" : "DoctrineCISIS",
  "title" : "Doctrine et gouvernance du cadre d'interopérabilité des systèmes d'informations en santé (CI-SIS)",
  "status" : "draft",
  "date" : "2026-06-26T11:54:07+00:00",
  "publisher" : "ANS",
  "contact" : [{
    "name" : "ANS",
    "telecom" : [{
      "system" : "url",
      "value" : "https://esante.gouv.fr"
    }]
  }],
  "jurisdiction" : [{
    "coding" : [{
      "system" : "urn:iso:std:iso:3166",
      "code" : "FR",
      "display" : "FRANCE"
    }]
  }],
  "packageId" : "ans.fr.doctrine",
  "license" : "CC0-1.0",
  "fhirVersion" : ["4.0.1"],
  "dependsOn" : [{
    "id" : "hl7tx",
    "extension" : [{
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/implementationguide-dependency-comment",
      "valueMarkdown" : "Automatically added as a dependency - all IGs depend on HL7 Terminology"
    }],
    "uri" : "http://terminology.hl7.org/ImplementationGuide/hl7.terminology",
    "packageId" : "hl7.terminology.r4",
    "version" : "7.2.0"
  },
  {
    "id" : "hl7ext",
    "extension" : [{
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/implementationguide-dependency-comment",
      "valueMarkdown" : "Automatically added as a dependency - all IGs depend on the HL7 Extension Pack"
    }],
    "uri" : "http://hl7.org/fhir/extensions/ImplementationGuide/hl7.fhir.uv.extensions",
    "packageId" : "hl7.fhir.uv.extensions.r4",
    "version" : "5.3.0"
  }],
  "definition" : {
    "extension" : [{
      "extension" : [{
        "url" : "code",
        "valueString" : "copyrightyear"
      },
      {
        "url" : "value",
        "valueString" : "2020+"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "releaselabel"
      },
      {
        "url" : "value",
        "valueString" : "ci-build"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "shownav"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "autoload-resources"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "path-liquid"
      },
      {
        "url" : "value",
        "valueString" : "template/liquid"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "path-liquid"
      },
      {
        "url" : "value",
        "valueString" : "input/liquid"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "path-qa"
      },
      {
        "url" : "value",
        "valueString" : "temp/qa"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "path-temp"
      },
      {
        "url" : "value",
        "valueString" : "temp/pages"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "path-output"
      },
      {
        "url" : "value",
        "valueString" : "output"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "path-suppressed-warnings"
      },
      {
        "url" : "value",
        "valueString" : "input/ignoreWarnings.txt"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "path-history"
      },
      {
        "url" : "value",
        "valueString" : "https://interop.esante.gouv.fr/ig/doctrine/history.html"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "template-html"
      },
      {
        "url" : "value",
        "valueString" : "template-page.html"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "template-md"
      },
      {
        "url" : "value",
        "valueString" : "template-page-md.html"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "apply-contact"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "apply-context"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "apply-copyright"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "apply-jurisdiction"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "apply-license"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "apply-publisher"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "apply-version"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "apply-wg"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "active-tables"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "fmm-definition"
      },
      {
        "url" : "value",
        "valueString" : "http://hl7.org/fhir/versions.html#maturity"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "propagate-status"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "excludelogbinaryformat"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueString" : "tabbed-snapshots"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-internal-dependency",
      "valueCode" : "hl7.fhir.uv.tools.r4#1.1.2"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "copyrightyear"
      },
      {
        "url" : "value",
        "valueString" : "2020+"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "releaselabel"
      },
      {
        "url" : "value",
        "valueString" : "ci-build"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "shownav"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "autoload-resources"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "path-liquid"
      },
      {
        "url" : "value",
        "valueString" : "template/liquid"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "path-liquid"
      },
      {
        "url" : "value",
        "valueString" : "input/liquid"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "path-qa"
      },
      {
        "url" : "value",
        "valueString" : "temp/qa"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "path-temp"
      },
      {
        "url" : "value",
        "valueString" : "temp/pages"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "path-output"
      },
      {
        "url" : "value",
        "valueString" : "output"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "path-suppressed-warnings"
      },
      {
        "url" : "value",
        "valueString" : "input/ignoreWarnings.txt"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "path-history"
      },
      {
        "url" : "value",
        "valueString" : "https://interop.esante.gouv.fr/ig/doctrine/history.html"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "template-html"
      },
      {
        "url" : "value",
        "valueString" : "template-page.html"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "template-md"
      },
      {
        "url" : "value",
        "valueString" : "template-page-md.html"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "apply-contact"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "apply-context"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "apply-copyright"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "apply-jurisdiction"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "apply-license"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "apply-publisher"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "apply-version"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "apply-wg"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "active-tables"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "fmm-definition"
      },
      {
        "url" : "value",
        "valueString" : "http://hl7.org/fhir/versions.html#maturity"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "propagate-status"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "excludelogbinaryformat"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    },
    {
      "extension" : [{
        "url" : "code",
        "valueCode" : "tabbed-snapshots"
      },
      {
        "url" : "value",
        "valueString" : "true"
      }],
      "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-parameter"
    }],
    "page" : {
      "extension" : [{
        "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-page-name",
        "valueUrl" : "toc.html"
      }],
      "nameUrl" : "toc.html",
      "title" : "Table of Contents",
      "generation" : "html",
      "page" : [{
        "extension" : [{
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-page-name",
          "valueUrl" : "index.html"
        }],
        "nameUrl" : "index.html",
        "title" : "Accueil",
        "generation" : "markdown"
      },
      {
        "extension" : [{
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-page-name",
          "valueUrl" : "doctrine.html"
        }],
        "nameUrl" : "doctrine.html",
        "title" : "Doctrine",
        "generation" : "markdown"
      },
      {
        "extension" : [{
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-page-name",
          "valueUrl" : "trajectoire-iop.html"
        }],
        "nameUrl" : "trajectoire-iop.html",
        "title" : "Trajectoire interopérabilité",
        "generation" : "markdown"
      },
      {
        "extension" : [{
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-page-name",
          "valueUrl" : "elaboration.html"
        }],
        "nameUrl" : "elaboration.html",
        "title" : "Méthode d'élaboration des échanges fonctionnels",
        "generation" : "markdown"
      },
      {
        "extension" : [{
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-page-name",
          "valueUrl" : "choix-standard.html"
        }],
        "nameUrl" : "choix-standard.html",
        "title" : "Choix des normes et standard",
        "generation" : "markdown"
      },
      {
        "extension" : [{
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-page-name",
          "valueUrl" : "cycle-de-vie.html"
        }],
        "nameUrl" : "cycle-de-vie.html",
        "title" : "Cycle de vie des spécifications",
        "generation" : "markdown"
      },
      {
        "extension" : [{
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-page-name",
          "valueUrl" : "comitologie.html"
        }],
        "nameUrl" : "comitologie.html",
        "title" : "Comitologie du CI-SIS",
        "generation" : "markdown"
      },
      {
        "extension" : [{
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-page-name",
          "valueUrl" : "interactions-ecosysteme.html"
        }],
        "nameUrl" : "interactions-ecosysteme.html",
        "title" : "Interactions avec l'écosystème",
        "generation" : "markdown"
      },
      {
        "extension" : [{
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-page-name",
          "valueUrl" : "ebe-cp.html"
        }],
        "nameUrl" : "ebe-cp.html",
        "title" : "Expression des besoins (EBE) et gestion des Change Proposals (CP)",
        "generation" : "markdown"
      },
      {
        "extension" : [{
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-page-name",
          "valueUrl" : "up-externe.html"
        }],
        "nameUrl" : "up-externe.html",
        "title" : "Unité de production externe",
        "generation" : "markdown"
      },
      {
        "extension" : [{
          "url" : "http://hl7.org/fhir/tools/StructureDefinition/ig-page-name",
          "valueUrl" : "change-log.html"
        }],
        "nameUrl" : "change-log.html",
        "title" : "Historique des versions",
        "generation" : "markdown"
      }]
    },
    "parameter" : [{
      "code" : "path-resource",
      "value" : "input/capabilities"
    },
    {
      "code" : "path-resource",
      "value" : "input/examples"
    },
    {
      "code" : "path-resource",
      "value" : "input/extensions"
    },
    {
      "code" : "path-resource",
      "value" : "input/models"
    },
    {
      "code" : "path-resource",
      "value" : "input/operations"
    },
    {
      "code" : "path-resource",
      "value" : "input/profiles"
    },
    {
      "code" : "path-resource",
      "value" : "input/resources"
    },
    {
      "code" : "path-resource",
      "value" : "input/vocabulary"
    },
    {
      "code" : "path-resource",
      "value" : "input/maps"
    },
    {
      "code" : "path-resource",
      "value" : "input/testing"
    },
    {
      "code" : "path-resource",
      "value" : "input/history"
    },
    {
      "code" : "path-resource",
      "value" : "fsh-generated/resources"
    },
    {
      "code" : "path-pages",
      "value" : "template/config"
    },
    {
      "code" : "path-pages",
      "value" : "input/images"
    },
    {
      "code" : "path-tx-cache",
      "value" : "input-cache/txcache"
    }]
  }
}

```
