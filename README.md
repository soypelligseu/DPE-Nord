La rénovation énergétique du parc de logements français représente une étape majeure dans la transition énergétique que souhaite opérer la France. A la suite de la convention citoyenne pour le climat, le sujet a d’ailleurs été largement approuvé car les économies potentielles en énergie sont immenses. Ainsi, de nombreuses politiques et subventions se succèdent depuis plusieurs années pour favoriser une réduction de la consommation énergétique des foyers français : la meilleure énergie, c’est celle qu’on ne consomme pas.

Notre souhait initial a été d’observer l’évolution de l’activité de rénovation énergétique des logements à l’échelle des régions françaises. Mais l’absence de données libres d’accès nous a contraint à revoir notre angle.

Nous avons donc fait le choix d’étudier l’état du parc immobilier du département du Nord en nous basant sur les diagnostics de performance énergétique des logements. 

Tel que défini par le ministère de la Transition écologique, le DPE _“décrit le bâtiment ou le logement (surface, orientation, murs, fenêtres, matériaux, etc), ainsi que ses équipements de chauffage, de production d’eau chaude sanitaire, de refroidissement et de ventilation. Il indique, suivant les cas, soit la quantité d’énergie effectivement consommée (sur la base de factures), soit la consommation d’énergie estimée pour une utilisation standardisée du bâtiment ou du logement.”_

![alt_text](images/image1.png "image_tooltip")


L’étude des DPE du parc immobilier du Nord nous permettra d’obtenir un aperçu de l’état des logements et de leur niveau de consommation énergétique mais aussi du nombre potentiel de logements ayant fait l’objet d’une rénovation énergétique. En effet, nous partons ici du principe qu’un logement ancien mais économe a été rénové. 



PRÉSENTATION DU SUJET ET DE LA MÉTHODE 

La première version de notre travail visait à étudier à l’échelle régionale le nombre de rénovations énergétiques effectuées chaque années et de comparer plusieurs régions entre elles pour en déduire les raisons derrière d’éventuelles disparités. Nous avions pour cela besoin des informations dont, par exemple, le nombre de rénovations effectuées ou si celles-ci avaient bénéficié d’aide de l’Etat ou des collectivités territoriales. Ces informations sont collectées par les CERC. Or, aucun parmi eux n’a accepté de fournir ces données et celles mises en ligne étaient limitées et ne suffisaient pas à établir une base d’analyse. 

Nous avons pour cette raison redirigé nos efforts vers un plus petit dénominateur, le département, et plus spécifiquement le département du Nord (59). Nous souhaitions, à partir de l’exploitation de données librement accessibles, entamer une réflexion sur l’état du parc immobilier du département en matière d’énergie, révéler les éventuelles disparités et comparer la consommation énergétique des logements selon les périodes.

Afin de permettre cette analyse, plusieurs jeux de données ont dû être utilisés. Notre première source, sur laquelle repose les autres, est la base des diagnostics énergétiques des logements du Nord mise en ligne par l’ADEME. Chaque ligne correspond à un logement auquel est associé, entre autres, une adresse postale complète et l’année de construction du bâtiment évalué. Ce document était composé de près de 325 000 entrées. Toutes les informations n'étaient pas correctement remplies et un travail de nettoyage sur lequel nous revenons en annexe s’est imposé.  

Un des problèmes rencontrés était la mauvaise écriture du nom des villes, certaines comportant des caractères spéciaux comme des tirés ou des espaces en trop. Nous avons corrigé ces erreurs en faisant appel à une base de données INSEE comprenant, pour chaque code INSEE, la ville qui lui est associée. Nous avons relié les bases de données entre elles à l’aide de Workbench Data afin d’obtenir une écriture standardisée des différents noms de ville pour permettre l’étude des performances énergétiques du parc de chaque ville. 

Une démarche similaire a été réalisée à l’aide d’une base de données établie par La Poste comprenant une position géographique pour chaque ville de France. L’obtention d’une latitude et d’une longitude était une information essentielle de pouvoir situer sur la carte les lieux étudiés et réaliser une cartographie précise. 

Enfin, la base de logement INSEE de 2016 nous a permis de connaître le nombre de résidences primaires et secondaires dans le département. 

Nous l’avons vu, la base de diagnostic des bâtiments du Nord est vaste. Pour gagner en lisibilité, nous avons décidé de nous concentrer sur les bâtiments réparties en quatre périodes distinctes. La première catégorie de logements comprendra les bâtiments construits avant 1950, la seconde les bâtiments compris entre 1950 et 1980, puis ceux compris entre 1980 et 2000 et, pour la quatrième période, ceux compris entre 2000 et 2010. Nous avons décidé de ne pas prendre en compte les bâtiments construits après 2010 car les normes récentes et l’actualité de leur construction rendent quasi improbable des travaux de rénovation énergétique.  Prenons note que le département du Nord a connu de nombreuses destructions pendant la seconde guerre mondiale, impliquant un fort travail de reconstruction à la sortie de la guerre et donc un nombre plus important de logements construits durant cette période comparé à d’autres territoires. 

Les normes s’améliorant avec le temps, les logements produits durant les deux dernières périodes devraient offrir une meilleure isolation énergétique. En gardant cette logique en mémoire, il est possible de déduire, à partir du DPE actuel d’un logement et de sa période de construction, si celui-ci a bénéficié de travaux de rénovation énergétique. En effet, les techniques de construction au moment de la construction d’un bâtiment à la fin des années 1940 ne permettaient pas au bâtiment d’être aussi isolé comme un bâtiment moderne et, en conséquence, d’obtenir une notation élevée.

Comparaison des DPE selon les périodes

Au cours de notre analyse du jeu de données nous avons longuement échangé au sujet de la visualisation. Quelle facette mettre en avant dans l’observation des DPE du département du Nord? Comment montrer efficacement les changements, les variations, les proportions différenciées entre les communes?  Comment pouvoir observer des tendances au niveau départemental?

Les diagrammes en barre apparaissent ainsi comme des outils incontournables et visuellement pertinents pour représenter les données que nous avons pu synthétiser dans nos travaux. Ici pour observer les “parts” de DPE au niveau du parc immobilier départemental répertorié dans nos données. Effectivement comme nous pouvons le voir, le double découpage en classe d’âge et en DPE nécessite une visualisation “croisée”, qui couplée avec un sankey Diagram permet d’obtenir une visualisation nette de la part de logements par DPE et des proportions pour chaque classe d’âge. En effet, si indépendamment les trois visualisations viennent corroborer certaines informations. Il n’en reste pas moins que c’est par l’articulation des trois réunies que l’analyse prend ici son sens.



<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")


Nous pouvons notamment prendre pour exemple cette première visualisation qui permet de manière effective d’observer la proportion de logements isolés. Comme nous pouvons le constater ici; les logements construits avant  1950 comportent une part relativement faible de DPE “vertes” classées A,B ou C (seulement 23%) tandis que pour les logements construits entre 2000 et 2010 cette part passe à près de 36%. Cependant, l’absence d'unité claire de référence nécessite une seconde visualisation pour avoir une idée plus précise de la réalité. 



<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.png "image_tooltip")


C’est ici qu’intervient notre 2nd diagramme qui nous permet d’observer qu’en “volume” de logements, la part du parc immobilier construit avant 1950 et bien plus important que celui construit entre 2000 et 2010 (comme nous avons pu l’expliquer précédemment). Ce diagramme nous aide ainsi à voir qu’en réalité ce volume de logements est aussi supérieur lorsque l'on s’intéresse aux DPE vertes qui représentent 20000 logements tandis que seulement 9000 sont catégorisés de la sorte pour la période 2000-2010. 



<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image4.png "image_tooltip")


&lt;svg width="847" height="520" xmlns="[http://www.w3.org/2000/svg](http://www.w3.org/2000/svg)">&lt;g transform="translate(0, 10)">&lt;g class="links" fill="none" stroke-opacity="0.8">&lt;path d="M5,236.76001409391C423.5,236.76001409391,423.5,489.99315703582823,842,489.99315703582823" stroke-width="0.004561976114531563" style="stroke: rgb(191, 105, 105);">&lt;/path>&lt;path d="M5,234.35509235219945C423.5,234.35509235219945,423.5,474.87690082338105,842,474.87690082338105" stroke-width="4.80528150730658" style="stroke: rgb(191, 105, 105);">&lt;/path>&lt;path d="M5,230.58537942289152C423.5,230.58537942289152,423.5,455.96279949558635,842,455.96279949558635" stroke-width="2.7341443513092503" style="stroke: rgb(191, 105, 105);">&lt;/path>&lt;path d="M5,200.53488242711967C423.5,200.53488242711967,423.5,335.8447629997775,842,335.8447629997775" stroke-width="21.10826348193754" style="stroke: rgb(191, 105, 105);">&lt;/path>&lt;path d="M5,43.247830279652874C423.5,43.247830279652874,423.5,23.24783027965279,842,23.24783027965279" stroke-width="46.49566055930569" style="stroke: rgb(191, 105, 105);">&lt;/path>&lt;path d="M5,172.18904383947782C423.5,172.18904383947782,423.5,249.12068837623323,842,249.12068837623323" stroke-width="35.58341369334619" style="stroke: rgb(191, 105, 105);">&lt;/path>&lt;path d="M5,217.92057339959948C423.5,217.92057339959948,423.5,402.7280431718713,842,402.7280431718713" stroke-width="13.66311846302203" style="stroke: rgb(191, 105, 105);">&lt;/path>&lt;path d="M5,226.9852199391737C423.5,226.9852199391737,423.5,437.7094243750462,842,437.7094243750462" stroke-width="4.4661746161264" style="stroke: rgb(191, 105, 105);">&lt;/path>&lt;path d="M5,110.44649877605522C423.5,110.44649877605522,423.5,167.01181292189008,842,167.01181292189008" stroke-width="87.901676433499" style="stroke: rgb(191, 105, 105);">&lt;/path>&lt;path d="M5,459.8715043394406C423.5,459.8715043394406,423.5,479.86694236332613,842,479.86694236332613" stroke-width="0.24786736888954825" style="stroke: rgb(191, 191, 105);">&lt;/path>&lt;path d="M5,459.05338995623464C423.5,459.05338995623464,423.5,461.78007937096646,842,461.78007937096646" stroke-width="1.388361397522439" style="stroke: rgb(191, 191, 105);">&lt;/path>&lt;path d="M5,451.4554187374823C423.5,451.4554187374823,423.5,379.932460499963,842,379.932460499963" stroke-width="11.928046880795193" style="stroke: rgb(191, 191, 105);">&lt;/path>&lt;path d="M5,430.44295675395C423.5,430.44295675395,423.5,105.90475484014533,842,105.90475484014533" stroke-width="14.312439729990357" style="stroke: rgb(191, 191, 105);">&lt;/path>&lt;path d="M5,442.1915659075736C423.5,442.1915659075736,423.5,311.9908018692975,842,311.9908018692975" stroke-width="6.599658779022327" style="stroke: rgb(191, 191, 105);">&lt;/path>&lt;path d="M5,457.7965655366812C423.5,457.7965655366812,423.5,425.0992137081817,842,425.0992137081817" stroke-width="0.7542467176025518" style="stroke: rgb(191, 191, 105);">&lt;/path>&lt;path d="M5,458.26644907647795C423.5,458.26644907647795,423.5,444.5029671389361,842,444.5029671389361" stroke-width="0.18552036199095023" style="stroke: rgb(191, 191, 105);">&lt;/path>&lt;path d="M5,438.24545656850376C423.5,438.24545656850376,423.5,220.6827015800015,842,220.6827015800015" stroke-width="1.2925598991172762" style="stroke: rgb(191, 191, 105);">&lt;/path>&lt;path d="M5,412.948390327127C423.5,412.948390327127,423.5,479.4046621170536,842,479.4046621170536" stroke-width="0.6766931236555151" style="stroke: rgb(105, 191, 105);">&lt;/path>&lt;path d="M5,412.17361471700906C423.5,412.17361471700906,423.5,460.649469623915,842,460.649469623915" stroke-width="0.8728580965803724" style="stroke: rgb(105, 191, 105);">&lt;/path>&lt;path d="M5,401.6536977968993C423.5,401.6536977968993,423.5,368.449966619687,842,368.449966619687" stroke-width="11.036940879756695" style="stroke: rgb(105, 191, 105);">&lt;/path>&lt;path d="M5,371.03067279875376C423.5,371.03067279875376,423.5,88.29400637934864,842,88.29400637934864" stroke-width="20.909057191602997" style="stroke: rgb(105, 191, 105);">&lt;/path>&lt;path d="M5,389.7256509161041C423.5,389.7256509161041,423.5,302.2813960388695,842,302.2813960388695" stroke-width="12.819152881833691" style="stroke: rgb(105, 191, 105);">&lt;/path>&lt;path d="M5,409.0083636228766C423.5,409.0083636228766,423.5,422.8858949632815,842,422.8858949632815" stroke-width="3.6723907721979083" style="stroke: rgb(105, 191, 105);">&lt;/path>&lt;path d="M5,411.2908723388472C423.5,411.2908723388472,423.5,443.96389362806894,842,443.96389362806894" stroke-width="0.8926266597433425" style="stroke: rgb(105, 191, 105);">&lt;/path>&lt;path d="M5,382.40063793487127C423.5,382.40063793487127,423.5,219.12098509012685,842,219.12098509012685" stroke-width="1.8308730806320006" style="stroke: rgb(105, 191, 105);">&lt;/path>&lt;path d="M5,349.68275721385646C423.5,349.68275721385646,423.5,478.17292856613005,842,478.17292856613005" stroke-width="1.7867739781915288" style="stroke: rgb(105, 191, 191);">&lt;/path>&lt;path d="M5,347.3477857725688C423.5,347.3477857725688,423.5,458.7714561234329,842,458.7714561234329" stroke-width="2.8831689043839477" style="stroke: rgb(105, 191, 191);">&lt;/path>&lt;path d="M5,322.57473481195757C423.5,322.57473481195757,423.5,354.6651954602775,842,354.6651954602775" stroke-width="16.532601439062383" style="stroke: rgb(105, 191, 191);">&lt;/path>&lt;path d="M5,262.43420369408796C423.5,262.43420369408796,423.5,62.16756917142639,842,62.16756917142639" stroke-width="31.343817224241526" style="stroke: rgb(105, 191, 191);">&lt;/path>&lt;path d="M5,299.8287219049032C423.5,299.8287219049032,423.5,281.3921074104295,842,281.3921074104295" stroke-width="28.95942437504636" style="stroke: rgb(105, 191, 191);">&lt;/path>&lt;path d="M5,336.5860841183888C423.5,336.5860841183888,423.5,415.3046509902824,842,415.3046509902824" stroke-width="11.490097173800164" style="stroke: rgb(105, 191, 191);">&lt;/path>&lt;path d="M5,344.1186670128329C423.5,344.1186670128329,423.5,441.73004599065337,842,441.73004599065337" stroke-width="3.5750686150879014" style="stroke: rgb(105, 191, 191);">&lt;/path>&lt;path d="M5,281.72756101179436C423.5,281.72756101179436,423.5,214.58409984422522,842,214.58409984422522" stroke-width="7.2428974111712785" style="stroke: rgb(105, 191, 191);">&lt;/path>&lt;path d="M5,469.9969586825903C423.5,469.9969586825903,423.5,499.9969586825904,842,499.9969586825904" stroke-width="0.0030413174096877086" style="stroke: rgb(105, 105, 191);">&lt;/path>&lt;path d="M5,479.99923967064757C423.5,479.99923967064757,423.5,499.9992396706476,842,499.9992396706476" stroke-width="0.0015206587048438543" style="stroke: rgb(191, 105, 191);">&lt;/path>&lt;/g>&lt;g class="nodes" font-family="Arial, Helvetica" font-size="10">&lt;g>&lt;rect x="0" y="246.7622950819672" height="103.81384912098505" width="5" fill="#000">&lt;/rect>&lt;text x="11" y="298.6692196424597" dy="0.35em" text-anchor="start">1950-1980&lt;/text>&lt;/g>&lt;g>&lt;rect x="0" y="360.57614420295226" height="52.71059268600254" width="5" fill="#000">&lt;/rect>&lt;text x="11" y="386.93144054595354" dy="0.35em" text-anchor="start">1980-2000&lt;/text>&lt;/g>&lt;g>&lt;rect x="0" y="423.2867368889548" height="36.708701134930635" width="5" fill="#000">&lt;/rect>&lt;text x="11" y="441.6410874564201" dy="0.35em" text-anchor="start">2000-2010&lt;/text>&lt;/g>&lt;g>&lt;rect x="0" y="479.99847934129514" height="0.0015206587048339766" width="5" fill="#000">&lt;/rect>&lt;text x="11" y="479.99923967064757" dy="0.35em" text-anchor="start">années&lt;/text>&lt;/g>&lt;g>&lt;rect x="0" y="469.9954380238854" height="0.0030413174096963758" width="5" fill="#000">&lt;/rect>&lt;text x="11" y="469.9969586825903" dy="0.35em" text-anchor="start">Années&lt;/text>&lt;/g>&lt;g>&lt;rect x="0" y="20.00000000000003" height="216.76229508196718" width="5" fill="#000">&lt;/rect>&lt;text x="11" y="128.38114754098362" dy="0.35em" text-anchor="start">Avant 1950&lt;/text>&lt;/g>&lt;g>&lt;rect x="842" y="489.99087604777094" height="0.004561976114587196" width="5" fill="#000">&lt;/rect>&lt;text x="836" y="489.99315703582823" dy="0.35em" text-anchor="end">-&lt;/text>&lt;/g>&lt;g>&lt;rect x="842" y="472.47426006972773" height="7.516615978043205" width="5" fill="#000">&lt;/rect>&lt;text x="836" y="476.23256805874934" dy="0.35em" text-anchor="end">A&lt;/text>&lt;/g>&lt;g>&lt;rect x="842" y="454.5957273199317" height="7.8785327497960225" width="5" fill="#000">&lt;/rect>&lt;text x="836" y="458.5349936948297" dy="0.35em" text-anchor="end">B&lt;/text>&lt;/g>&lt;g>&lt;rect x="842" y="325.29063125880873" height="60.605852681551596" width="5" fill="#000">&lt;/rect>&lt;text x="836" y="355.5935575995845" dy="0.35em" text-anchor="end">C&lt;/text>&lt;/g>&lt;g>&lt;rect x="842" y="499.9954380238855" height="0.004561976114530353" width="5" fill="#000">&lt;/rect>&lt;text x="836" y="499.99771901194276" dy="0.35em" text-anchor="end">classe_consommation_energie&lt;/text>&lt;/g>&lt;g>&lt;rect x="842" y="-5.684341886080802e-14" height="113.06097470514064" width="5" fill="#000">&lt;/rect>&lt;text x="836" y="56.53048735257026" dy="0.35em" text-anchor="end">D&lt;/text>&lt;/g>&lt;g>&lt;rect x="842" y="231.32898152956014" height="83.96164972924856" width="5" fill="#000">&lt;/rect>&lt;text x="836" y="273.3098063941844" dy="0.35em" text-anchor="end">E&lt;/text>&lt;/g>&lt;g>&lt;rect x="842" y="395.8964839403603" height="29.579853126622652" width="5" fill="#000">&lt;/rect>&lt;text x="836" y="410.68641050367165" dy="0.35em" text-anchor="end">F&lt;/text>&lt;/g>&lt;g>&lt;rect x="842" y="435.476337066983" height="9.119390252948733" width="5" fill="#000">&lt;/rect>&lt;text x="836" y="440.03603219345734" dy="0.35em" text-anchor="end">G&lt;/text>&lt;/g>&lt;g>&lt;rect x="842" y="123.06097470514058" height="98.26800682441956" width="5" fill="#000">&lt;/rect>&lt;text x="836" y="172.19497811735036" dy="0.35em" text-anchor="end">N&lt;/text>&lt;/g>&lt;/g>&lt;/g>&lt;/svg>

Enfin, la visualisation Sankey-Diagram permet d’observer cette même distribution par DPE et classe d’âge de manière plus “dynamique” que les deux visualisations précédentes et inclut quant à elle les logements ou la DPE n’a pas été possible via la lettre “N” et permet ainsi de renforcer la part prépondérante que tiennent les logements construits avant 1950 dans notre visualisation. 

Ainsi, nous remarquons, malgré une proportion qui en apparence peut paraître faible par rapport à la classe d’âge, que de nombreux logements anciens ont pu être rénovés dans le département du nord, mais qu’un grand nombre de logements présentant une mauvaise isolation n’ont pas encore bénéficié des travaux et des différentes subventions proposés. Le département du Nord présente encore de nombreux axes de progression dans l’amélioration énergétique de son parc immobilier bâti pour les prochaines années. Le territoire doit faire des efforts supplémentaires pour respecter les objectifs formulés par le gouvernement français.

APERÇU GENERAL DU PARC DE LOGEMENT

Le fichier étudié recensait, avant son nettoyage, les informations de près de 325 000 logements soit près d’un quart des 1 204 509 recensés dans le département par l’INSEE en 2016. Chaque entrée correspond à une construction pour un particulier sans distinction de entre logement primaire et secondaire. 

Cette visualisation permet d’observer, pour chaque ville du territoire du Nord, la proportion de logements catégorisés A, répartie en 4 paliers, selon la taille du parc de la ville. Une ville vert foncé avec un gros point correspond donc à une ville avec un nombre important de logements et dont une forte partie de ces logements ont un DPE classé A. A l’inverse, un petit point clair correspond à une ville ayant peu de résidence et dont une faible part d’entre elles ont un DPE classé A. Mettre en avant la proportion de logements catégorisés A par un système de couleur est plus juste que de mettre en avant le nombre réel de logements car les grandes villes et les agglomération seraient artificiellement favorisés par ce traitement. 



<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image5.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image5.png "image_tooltip")


On observe que les villes disposant d’une part importante dans parc de DPE A ne sont pas réparties équitablement sur le territoire ni dans les tailles de villes. Le centre du département, soit la métropole lilloise et ses alentours, concentre l’essentiel des villes de taille moyenne ou importante ayant un pourcentage de DPE A compris entre le second et le troisième quartile. Les villes “blanches” et de taille moyenne se trouvent pour l’essentiel dans la moitié inférieur du département. **Ainsi, un contraste se forme entre un sud dont le nombre de logements au DPE A est très peu important et un nord, caractérisé par un nombre important de villes moyennes ayant une proportion importante de logements classés A. **

La métropole lilloise, qui concentre le plus grand nombre d’habitants du territoire, se distingue négativement du reste des villes de taille plus modeste sur la proportion de ses habitations classées A. 



<p id="gdcalert6" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image6.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert7">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image6.png "image_tooltip")


A contrario, la proportion de logements catégorisés D semble répartie de manière plus homogène sur le territoire, la majorité des logements se trouvant dans le troisième quartile. 



<p id="gdcalert7" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image7.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert8">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image7.png "image_tooltip")


Dans la lignée des premières observations effectuées sur les logements catégorisés A, la fracture entre le nord et le sud du département s’observe ici autour des logements catégorisés F. La part de logement DPE F, mal isolés et en conséquence fortement consommateurs en énergie, est plus importante dans le sud du département, petites et moyennes villes confondues, quand les villes du nord du département sont plus claires, excepté certains cas qui ressortent en raison du contraste, et disposent donc moins de cette catégorie de logement. 



**CONCLUSION**

Au terme de nos travaux, nous avons pu mettre en lumière plusieurs éléments qui, sans pour autant parler de tendance, nous permettent d'avoir une idée de la situation actuelle sur le parc de logements répertoriés dans la DPE du Nord pour 2017. La mise en évidence de la part de logements anciens très largement supérieure aux autres classes d’âge est un premier anciennement. La part de logements avec une DPE “verte” représente une proportion non-négligeable du parc immobilier d’avant 1950, cependant il nous est difficile de cartographier réellement les efforts des collectivités et les tendances en cours mais les infographies proposées permettent d’avoir “une photographie” du travail qu’il reste à accomplir pour les collectivités.

Aussi, la répartition sur le territoire des différentes catégories de consommation énergétique n’est pas homogène. Nous l’avons vu, une fracture apparaît entre le nord du département où la part de logement faible en consommation énergétique est supérieure à celle du sud. 

Cependant, les interprétations dans notre travail sont limitées pour plusieurs raisons : 

**Boite noire **



1. Il est difficile d’articuler les données obtenues pour conclure à un véritable enseignement. En effet, la photographie disponible des DPE à l’échelle du département l’était sur une seule année, ne permettant ainsi pas d’effectuer des comparaisons entre les périodes et d’en déduire les efforts réalisés par les collectivités territoriales. De plus, ces déduction se basent sur un nombre limité d’informations qui pourraient trahir le réel en supposant, par exemple, à partir de la date de construction d’un bâtiment, sa consommation énergétique sans même connaître la qualité de construction du bâtiment. 
2. **L’utilisation de l’outil même du DPE est une limite en soi**. Cet indicateur est construit en partie à partir de la consommation d’énergie en énergie primaire kWh<sub>ep</sub> du bâtiment. Ainsi, un ménage composé d'individus sensibles au froid chauffant leur habitation à 21°C n’obtiendra pas la même note que si y avait habité des individus se chauffant à 18°C. De plus, l’utilisation d’une cheminée, comme cela peut être le cas dans les vieilles maisons, ne sera pas prise en compte alors qu’elle constitue une source de chaleur non négligeable et peut considérablement réduire la facture de chauffage en période hivernale.
3. Enfin, si 325 000 habitations étaient à l’origine présentes dans notre base de données, le ménage effectué et les critères établis ont abouti à 276 000 habitations effectivement intégrés dans notre analyse, signe que la base de données proposée par l’ADEME reste limitée en termes d’utilisation effective directe.
