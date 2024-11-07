### Les statuts de maturité

Les statuts de maturité de la spécification permettent d'estimer à quel point la spécification a été éprouvée et testée en implémentation. Une maturité élevée ne signifie pas forcément qu'il y aura systématiquement une rétrocompatibilité assurée, l'évolution de l'interopérabilité ne permet pas de le garantir (ex : passage de FHIR R4 à R6, passage de CDA à FHIR, ...)

#### Draft ou brouillon

La spécification est en développement. Cette phase a lieu lors de la création de la spécification.

#### Public Comment, ou en concertation pour commentaire public

La spécification est publiée pour concertation en commentaire public.

#### Trial-Implementation - pour implémentation

La spécification est prête pour être implémentée en situation réelle (projectathon, projet national …).

#### Final-text - Final

Les auteurs de la spécification ont estimé qu'elle avait atteint le stade de maturité le plus élevé. Ce stade est atteint lorsque la spécification est soit mise en œuvre au niveau national, soit testée lors d'un projectathon, et que la plupart des retours des implémenteurs ont été corrigés.

#### Withdrawal - abandonné

La spécification est abandonnée car elle est devenue obsolète, qu’un changement de priorités a empêché son implémentation, ou qu’elle n’a jamais été adoptée.

#### Schéma du cycle de vie

[[A AJOUTER]]

### Les critères de maturité et de qualité associés à une spécification

[[A AJOUTER]]

#### Les critères de maturité

Le critère de maturité reflète une confiance de l’auteur de la spécification sur sa clarté pour être implémentée. Une spécification avec un haut degré de maturité indique une plus grande pérennité de la spécification.

Même si la pérennité ne peut jamais être garantie, les spécifications jugées matures ont un plus faible risque de subir des changements non-rétrocompatibles.

##### L’existant FHIR

* Respect de l’ensemble des critères de qualité
* Nombre d’implémentations obtenu par déclaration (par convergence ou par les DSI). Idéalement, publier des retours d’expérience sur l’implémentation des spécifications
* Nombre élevé de passage en projectathon, nombre de tests réalisés lors de projectathon, et nombre de partenaires
* Intérêt pour la spécification : nombre d’issues et résolutions sur le repo GitHub, nombre de commentaires lors des phases de concertation

#### Les critères de qualité

Les critères de qualité permettent de s’assurer de la qualité des spécifications

Les critères de qualité semblent propres à chaque standard.

##### Critères de qualité FHIR


* Respect des bonnes pratiques nationales tel que les règles de nommages indiquées ci-dessous
* Respect des [bonnes pratiques internationales](https://build.fhir.org/ig/FHIR/ig-guidance/best-practice.html)
* Publication de l'IG sans erreurs (cf session Q/A)

Ces règles de nommage ont été établies en s'inspirant des ressources us-core

| **Attribut** | **Description** | **Exemple us-core** |
| ----- | ----- | ----- |
| id | utiliser le format kebab-case, ex : fr-core-patient. (/!\ sur Forge, l'id n'est pas obligatoire, il est important de le rajouter !). Lors de la création d'un IG pour un projet en particulier, il est possible de préfixer l'ensemble des ressources de conformité par le trigramme du projet (ex : "ror-...") | us-core-patient |
| title | similaire au nom, avec espaces. Ex : Fr Core Patient | US Core Patient Profile |
| name | Utiliser le format PascalCase sans espace. Ex : FrCorePatient | USCorePatientProfile |
| url | [base]/[ResourceType]/[id] (généré automatiquement par sushi). A noter que [ResourceType] doit respecter le nom et la casse des ressources définies dans FHIR core (ex: StructureDefinition). | http://hl7.org/fhir/us/core/StructureDefinition/us-core-patient |
| SearchParameter.code | toujours en minuscule, mots séparés par des tirets "-" si besoin | - |
{: .grid }

Nom des slices:

* Prendre l'id de l'extension s'il s'agit d'une extension
* Sinon, lowerCamelCase

### Liste des métadonnées associées à une spécification

[[A AJOUTER]]