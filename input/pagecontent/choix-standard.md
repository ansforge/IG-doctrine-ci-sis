<!-- Commentaire IGi - Il n’existe pas de document du CI-SIS décrivant la méthode à appliquer pour conduire l’étude de choix des normes/standards. Proposition d’un début de construction de ce type de document. A revoir sans doute par la suite. -->

L’étude des normes et standards est optionnelle. Elle intervient lorsqu’il est nécessaire de sélectionner une norme ou un standard (syntaxique, sémantique ou technique) cible qui n’est pas encore utilisé dans le CI-SIS pour répondre aux cas d’usage identifiés par l’étude fonctionnelle des échanges.

Au cours de cette étude, chaque solution technique et sémantique est analysée de façon approfondie et catégorisée selon différents critères de façon à pouvoir justifier du choix final retenu.

Le contenu de l’étude des normes et standards est le suivant :

<div>
    <ul>
        <li>Introduction</li>
        <li>Présentation des solutions envisagées. </li>
        <li>Comparaison des solutions</li>
        <li>Analyse SWOT de chaque solution</li>
        <li>Résultat d’un sondage</li>
        <li>Conclusion et proposition d’une solution</li>
    </ul>
</div>

Il s’agit de présenter l’objet du document, de rappeler l’étude fonctionnelle des échanges réalisée au préalable, de résumer en quelques phrases le(s) cas d’usage adressés par cette étude et de citer les flux d’information pour lesquels un choix de norme ou de standard doit être réalisé.

Les solutions pressenties (norme/standard, profil IHE ou guide d’implémentation FHIR) sont listées.

Chacune des solutions proposées en introduction fait l’objet d’une étude détaillée. Les points suivants peuvent être analysés :

<div>
    <ul>
        <li>Présentation de l’organisation en charge du développement de la solution envisagée ;</li>
        <li>Présentation et périmètre de la solution envisagée ;</li>
        <li>Norme(s)/standard(s) sous-jacent(s) ;</li>
        <li>Description de scénarii d’implémentation possibles. Dans certains cas, il est possible qu’il soit nécessaire de détailler différents scénarii d’implémentation pour compléter l’analyse ;</li>
        <li>Description de l’organisation de la documentation ;</li>
        <li>Processus d’élaboration et de gouvernance ;</li>
        <li>Maturité et degré d’adoption de la solution ;</li>
        <li>Estimation de l’effort à produire (faible, moyen, important) ;</li>
        <li>Outillage à disposition.</li>
    </ul>
</div>

### Comparaison des solutions

Les normes/standards ou solutions envisagées sont comparées à l’aide d’un tableau selon différents critères.

Exemple de tableau de comparaison :

| Critères d’évaluation | Standard X | Profil IHE Y |
| --- | --- | --- |
| **Neutralité** : Les spécifications ne limitent pas la concurrence et l’innovation ; Les spécifications sont basées sur des développements scientifiques et technologiques de pointe. |  |  |
| **Qualité/maturité** : La qualité est suffisante pour permettre le développement de produits et de services interopérables concurrents. |  |  |
| **Accessibilité** : les spécifications sont disponibles au public à des conditions raisonnables (y compris pour un prix raisonnable ou gratuitement). |  |  |
| **Stabilité de la documentation** |  |  |
| **Couverture des spécifications** |  |  |
| **Existence de guides d’implémentation** : Les guides référencent les standards de base  avec au moins un cas d’usage et une optionalité sur les paramètres pour permettre les extensions. |  |  |
| Processus de prise en compte des améliorations |  |  |
| **Outillage** : Des outils de tests sont mis en œuvre pour valider l’adhérence au standard. |  |  |
| **Tests** : Des tests sont effectués pour des versions de travail (dites STU -Standards for Trial Use) et/ou pour les guides d’implémentation normatifs. |  |  |
| **Adapté aux dispositifs mobiles** |  |  |
| **Mise en œuvre existantes du cas d’usage** |  |  |
| **Adoption par le marché et utilisation**  |  |  |

### Analyse SWOT

Le tableau de maturité précédant peut être complété par une analyse SWOT qui permet d’évaluer plus finement les forces (Strengths), les faiblesses (Weaknesses), les opportunités (Opportunities) et les menaces (Threats) de chacune des options envisagées dans les étapes précédentes.

**Forces : caractéristiques de la solution qui lui donnent un avantage sur les autres**

A ce niveau, on cherchera à évaluer les points clés suivants :

<div>
    <ul>
        <li>Réutilisation et intégration : mesure la capacité des composants et des éléments sémantiques choisis à être réutilisés dans d’autres contextes.</li>
        <li>Scalabilité et adaptabilité : capacité du standard et de ses éléments sémantiques à s’étendre et à s’adapter aux exigences d’évolution futures.</li>
        <li>Performance et fiabilité : mesure la capacité de la solution à être performante d’un point de vue opérationnelle, fiable et rapide.</li>
        <li>Utilisabilité et accessibilité : mesure la facilité d’utilisation des utilisateurs finaux, considérant à la fois l’interface technologique et la précision sémantique des choix réalisés.</li>
        <li>Intégration des données et précision sémantique : mesure la capacité de la technologie à gérer des données fiables et complètes mais également précises du point de vue sémantique de façon à répondre aux exigences des solutions d’aide à la décision.</li>
        <li>Faisabilité de l’implémentation : mesure la capacité du standard et de ses éléments sémantiques à s’intégrer aux infrastructures existantes sur le terrain ainsi qu’aux pratiques opérationnelles.</li>
    </ul>
</div>

**Faiblesses : caractéristiques de la solution qui désavantagent cette solution par rapport aux autres**

chacun des points clés cités précédemment peut faire l’objet d’une faiblesse. A ces axes d’analyse s’ajoute par exemple le manque de support, la dynamique de l’organisation en charge de la solution ou du standard, la courbe d’apprentissage, les coûts élevés de développement et de maintenance, etc.

**Opportunités : éléments de l'environnement que la solution pourrait exploiter à son avantage**

A ce niveau, on cherchera à évaluer les tendances du marché. Il s’agit de déterminer si la solution envisagée fait partie d’un marché émergent et permet de gagner en compétitivité et en innovation. L’évaluation des aspects d’évolutivité et de généralisation de la solution est primordiale.

**Menaces : éléments de l'environnement qui pourraient causer des problèmes concernant le choix de la solution.**

On cherchera à évaluer les risques externes susceptibles de menacer le choix réalisé, tels que la saturation du marché, l’évolution de la règlementation qui pourrait remettre en cause ce choix, l’obsolescence technologique, la dépendance trop forte à une technologie ou à un éditeur, l’incapacité à migrer vers une autre technologie, etc

Cette analyse SWOT est ensuite représentée sous la forme d’un tableau qui permet de visualiser comment les risques internes (Forces et faiblesses) et externes (Opportunités et Menaces) à la solution interagissent et affectent la stratégie du choix de la solution envisagée.

<div class="figure" style='text-align: center;'>
    <img src="swot.png" alt="swot" title="Matrice SWOT" style="width:40%;">
    <figcaption><b>Matrice SWOT</b></figcaption>
</div>

<table style="border-collapse:collapse;border:none;">
    <tbody>
        <tr>
            <td style="width: 226.55pt;border: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><span style="color:windowtext;">S</span></span><span style="color:#404040;font-style:italic;">trenghs</span></p>
            </td>
            <td style="width: 226.55pt;border-top: 1pt solid windowtext;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-image: initial;border-left: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><em><span style="color:black;">Weaknesses</span></em></p>
            </td>
        </tr>
        <tr>
            <td style="width: 226.55pt;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong>Identification des avantages</strong></span><span style="color:#404040;font-style:italic;">&nbsp;: quels sont les b&eacute;n&eacute;fices et les avantages comp&eacute;titifs de la solution (cf crit&egrave;res cit&eacute;s pr&eacute;c&eacute;demment pour les Forces) ?</span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong>Evaluer les succ&egrave;s d&rsquo;impl&eacute;mentation pass&eacute;s de la solution</strong></span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong>Acc&egrave;s au support et &agrave; l&rsquo;expertise</strong></span><span style="color:#404040;font-style:italic;">&nbsp;: avons-nous au niveau national la capacit&eacute; &agrave; supporter les &eacute;diteurs et &agrave; apporter de l&rsquo;expertise concernant la solution ?</span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong>Evaluer la disponibilit&eacute; des ressources</strong></span><span style="color:#404040;font-style:italic;">&nbsp;: ressources financi&egrave;res, humaines ou mat&eacute;rielles sur lesquelles il est possible de s&rsquo;appuyer.</span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong>Evaluer le degr&eacute; d&rsquo;adoption</strong></span><span style="color:#404040;font-style:italic;">&nbsp;: l&rsquo;&eacute;cosyst&egrave;me a-t-il d&eacute;j&agrave; connaissance de la solution envisag&eacute;e et l&rsquo;a-t-il d&eacute;j&agrave; adopt&eacute;e en partie ?</span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong>Passer en revue les outils et les ressources disponibles</strong></span><span style="color:#404040;font-style:italic;">&nbsp;: existence de guides d&rsquo;impl&eacute;mentation, outils de tests disponibles.</span></p>
            </td>
            <td style="width: 226.55pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:windowtext;">Evaluer les limitations de la solution envisag&eacute;e</span></strong></span><span style="color:#404040;font-style:italic;"><span style="color:windowtext;">&nbsp;: tous les aspects &eacute;valu&eacute;s lors de l&rsquo;analyse des forces peuvent faire l&rsquo;objet d&rsquo;une faiblesse</span></span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:windowtext;">Analyser les retours d&rsquo;exp&eacute;rience pass&eacute;s</span></strong></span><span style="color:#404040;font-style:italic;"><span style="color:windowtext;">&nbsp;: quels sont les retours d&rsquo;exp&eacute;rience d&rsquo;une impl&eacute;mentation pass&eacute;e au niveau international ?</span></span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:windowtext;">Acc&egrave;s aux ressources</span></strong></span><span style="color:#404040;font-style:italic;"><span style="color:windowtext;">&nbsp;: les ressources (financi&egrave;res, mat&eacute;rielles, en expertise) sont-elles suffisantes ?</span></span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:windowtext;">Impact des faiblesses</span></strong></span><span style="color:#404040;font-style:italic;"><span style="color:windowtext;">&nbsp;: quel est l&rsquo;impact des faiblesses de la solution sur la capacit&eacute; &agrave; atteindre les objectifs poursuivis ?</span></span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:windowtext;">Outils et ressources disponibles</span></strong></span></p>
            </td>
        </tr>
        <tr>
            <td style="width: 226.55pt;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><em><span style="color:black;">Opportunities</span></em></p>
            </td>
            <td style="width: 226.55pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><em><span style="color:black;">Threats</span></em></p>
            </td>
        </tr>
        <tr>
            <td style="width: 226.55pt;border-right: 1pt solid windowtext;border-bottom: 1pt solid windowtext;border-left: 1pt solid windowtext;border-image: initial;border-top: none;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:windowtext;">Exploration des capacit&eacute;s de la solution&nbsp;</span></strong></span><span style="color:#404040;font-style:italic;"><span style="color:windowtext;">: quelles capacit&eacute;s sp&eacute;cifiques &agrave; la solution peuvent r&eacute;pondre aux objectifs poursuivis&nbsp;?</span></span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:windowtext;">Identifier les tendances du march&eacute;</span></strong></span><span style="color:#404040;font-style:italic;"><span style="color:windowtext;">&nbsp;</span></span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:windowtext;">Evaluer les possibilit&eacute;s de collaboration</span></strong></span><span style="color:#404040;font-style:italic;"><span style="color:windowtext;">&nbsp;: collaboration et partenariats qui pourraient aider &agrave; l&rsquo;impl&eacute;mentation de la solution choisie</span></span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:windowtext;">Analyser le contexte r&eacute;glementaire</span></strong></span><span style="color:#404040;font-style:italic;"><span style="color:windowtext;">&nbsp;: le contexte r&eacute;glementaire est-il favorable au choix de la solution envisag&eacute;e ?</span></span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:windowtext;">Evaluer l&rsquo;aspect financier</span></strong></span><span style="color:#404040;font-style:italic;"><span style="color:windowtext;">&nbsp;: quelles possibilit&eacute;s de budget (interne ou externe) pour supporter l&rsquo;initiative ?</span></span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><span style="color:windowtext;font-style:normal;">&nbsp;</span></span></p>
            </td>
            <td style="width: 226.55pt;border-top: none;border-left: none;border-bottom: 1pt solid windowtext;border-right: 1pt solid windowtext;padding: 0cm 5.4pt;vertical-align: top;">
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:windowtext;">Evaluer les risques et les d&eacute;fis</span></strong></span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:windowtext;">Evaluer l&rsquo;obsolescence de la solution</span></strong></span><span style="color:#404040;font-style:italic;"><span style="color:windowtext;">&nbsp;: n&eacute;cessite d&rsquo;anticiper les strat&eacute;gies de maintenance des normes/standards et des solutions d&eacute;velopp&eacute;es par les organisations en charge de ces sp&eacute;cifications.</span></span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:windowtext;">Impact r&eacute;glementaire</span></strong></span><span style="color:#404040;font-style:italic;"><span style="color:windowtext;">&nbsp;: n&eacute;cessite de conna&icirc;tre la r&eacute;glementation en vigueur et d&rsquo;anticiper les &eacute;volutions.</span></span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:windowtext;">Evaluer les co&ucirc;ts de d&eacute;veloppement, de maintenance et de ressources</span></strong></span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:windowtext;">Evaluer les d&eacute;lais potentiels de mise en &oelig;uvre</span></strong></span><span style="color:#404040;font-style:italic;"><span style="color:windowtext;">&nbsp;: quels facteurs pourraient retarder l&rsquo;adoption et l&rsquo;impl&eacute;mentation de la solution ?</span></span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:windowtext;">Evaluer le degr&eacute; d&rsquo;acceptation</span></strong></span><span style="color:#404040;font-style:italic;"><span style="color:windowtext;">&nbsp;par l&rsquo;&eacute;cosyst&egrave;me</span></span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:windowtext;">Evaluer les co&ucirc;ts additionnels de licence</span></strong></span><span style="color:#404040;font-style:italic;"><span style="color:windowtext;">&nbsp;: la solution choisie n&eacute;cessite t&rsquo;elle des co&ucirc;ts additionnels de souscription ou de licence (notamment pour les aspects s&eacute;mantiques) ?</span></span></p>
                <p style='margin-top:0cm;margin-right:0cm;margin-bottom:10.0pt;margin-left:0cm;text-align:left;line-height:115%;font-size:13px;font-family:"Aptos",sans-serif;'><span style="color:#404040;font-style:italic;"><strong><span style="color:windowtext;">Evaluer la fin de la maintenance de la solution par l&rsquo;organisation qui la porte</span></strong></span><span style="color:#404040;font-style:italic;"><span style="color:windowtext;">&nbsp;: durabilit&eacute; &agrave; long terme de la solution et quelles sont les trajectoires pr&eacute;vues en cas de fin de maintenance ?</span></span></p>
            </td>
        </tr>
    </tbody>
</table>

### Résultat de sondage

Dans certains cas, il peut être envisagé de réaliser un sondage auprès d’un groupe restreint préalable à la phase de concertation publique. Dans ce cas, les résultats de ce sondage sont consignés au niveau de ce chapitre.

### Conclusion et proposition d'une solution

Dans certains cas, il peut y avoir une mise en concertation publique de l’étude des normes et standards, qui justifie la solution envisagée (norme/standard, profil IHE, guide d’implémentation FHIR, etc.).
