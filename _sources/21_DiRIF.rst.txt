SIRIUS, le SAGT de la DiRIF
###################################################

Création de SIRIUS
**********************
Dans les années 1990-2005, des investissements considérables ont été consacrés à la gestion du trafic, sur le réseau routier national de l'Ile de France.
Sur la partie la plus dense du réseau, des points de mesure du trafic ont été implantés tous les 500 mètres. 
Un SAGT a été conçu de toutes pièces avec des moyens d'ingénierie propres 
et le recours à des sociétés de services.
Une telle réalisation était excetionnelle en 2000.

Pour construire SIRIUS il a fallu un travail de conception fonctionnelle d'une part et le développement du SI d'autre part.
Ce chantier a reposé sur des équipes de MOA nombreuses (USSO : Unité de la stratégie et des systèmes opérationnels)  
qui ont été dispersées une fois le travail achevé.

Evolutions de SIRIUS et notamment FCD
***************************************
Après la mise en place du socle logiciel initial, SIRIUS n'a connu que des évolutions limitées. 
Cela s'explique par la richesse de l'outil, mais aussi par la réduction des moyens humains et financiers.

Une fois la dynamique cassées, il est difficile de changer de régime. 
Les évolutions qui ont été faites étaient des réponses à des besoins particuliers comme la création de voies réservées 
ou le projet C-ITS SCOOP.

Il n'existe pas de feuille de route des évolutions fonctionnelles, comme c'est le cas pour SAGACITE. 
L'une des raisons est que l'on ne dispose pas des moyens de cette reflexion.

La principale évolution fonctionnelle de SIRIUS des 15 dernières années a été l'utilisation des FCD qui se substituent en partie aux points de mesure du trafic.

La DiRIF utilise les FCD depuis 10 ans environ. Avec la dégradation de la disponibilité des données issues des points de mesure du trafic, les FCD sont devenues la principale source d'information sur l'état du trafic sur le réseau. Les FCD ont permis d'étendre le périmètre sur lequel la DiRIF peut visualiser l'état du trafic. 
On dispose de plus de 5000 ségments FCD, quand il ne reste plus que 800 points de mesure par boucles, dont plus de la moitié est hors service.

Les données FCD sont des données de vitesse moyenne, elles présentent donc un retard de 6 à 20 minutes sur les mesures faites sur le terrain en temps réel. Mais la plus grosse différence tient au fait que les données des points de mesures sont principalement des données de débit et de taux d'occupation alors que les FCD sont des mesures de vitesses.

On aurait pu s'attendre à ce que l'arrivée des FCD donne lieu à une évolution fonctionnelle significative de SIRIUS pour tenir compte de leurs spécificités.
En fait, les FCD ont été introduites avec le minimum de transformation possible du SI.
Le flux FCD est présenté à SIRIUS comme s'il s'agissait de données issues de stations de comptage classiques.
Le document de spécification fonctionnel n'a d'ailleurs pas même été mis à jour à cette occasion.

En 2023, lors du renouvellement du marché d'acquisition des données FCD, la DIRIF a ajouté 2000 segments dans le cahier des charges. 
Cela devait permettre de connaitre le fonctionnement des bretelles et d'autres arcs connexes au réseau national.  
En dépit de cette extension de 40% de la commande, le coût d'acquisition pour la DiRIF a été divisé par 2.

Cependant, les données nouvelles n'ont pas été intégrées Dans SIRIUS. 
On a pensé que SIRIUS ne parvenait pas à traiter ce volume supplémentaire de données, mais il s'agit plutot d'une mauvaise coordination
des acteurs.

Cet exemple des données FCD montre que la DiRIF n'a plus les moyens concevoir une évolution fonctionnelle significative de SIRIUS et de tirer toute la valeur potentielle d'une évolution technologique telle que les FCD.

Maintenance de SIRIUS
************************
Les outils informatiques (systèmes d'exploitation, gestionnaires de bases de données, utilitaires ...) sur lesquels repose un SI évoluent. 
Cela impose en principe d'adapter les codes des applications tous les 5 à 10 ans.
Les logiciels modernes sont plus fiables, plus flexibles, plus sûrs et moins chers à maintenir.

SIRIUS a pris beaucoup de retard dans cette matière.

Aujourd'hui, SIRIUS fonctionne mais certains de ses modules reposent sur des systèmes d'exploitation (OS) qui ne sont plus maintenus par leurs concepteurs tels que Windows XP. 
Cette situation entraine des pannes et présente des risques en termes de cybersécurité.

Trois agents de la DiRIF assurent la maitrise d'ouvrage de la maintenance de SIRIUS. Ces personnes travaillent sur ce SI depuis plus de 20 ans. 
Les entreprises qui se sont succédées, comme titulaires du marché de maintenance, rencontrent des difficultés à trouver les compétences capables de travailler avec les outils d'il y a 20 ans et les agents de la DiRIF sont fortement solicitées pour les former ou pour se substituer à elles quand des aléas surgissent.

Adéquation fonctionnelle de SIRIUS
***************************************
Les responsables fonctionnels de SIRIUS sont également à cette  place depuis très longtemps. 
Ils ont su faire faire beaucoup de choses au système, mais ne l'utilisent pas toujours selon les représentations des concepteurs. 
Une partie des fonctions introduites initialement dans SIRIUS ne sont plus utilisées ou le sont d'une manière différente de celle qui avait été imaginée.

Ayant acquis une virtuosité dans la manipulation de SIRIUS et ne connaissant pas tout ce qui se fait ailleurs, les responsables fonctionnels ne sont pas demandeurs d'évolutions significatives. Ils craignent en revanche de se voir imposé un autre SAGT avec les aléas que cela comporte et sur lequel ils peineraient à reproduire les fonctions qu'ils utilisent aujourd'hui.

La documentation fonctionnelle de SIRIUS n'est plus consultée par les exploitants et ne rend pas toujours bien compte de la manière dont SIRIUS est effectivement utilisé. 
Cette situation est un obstacle supplémentaire à l'évolution de SIRIUS.

Même une modernisation logicielle qui se voudrait *isofonctionnelle* rencontrerait des difficultés en l'absence d'une spécification fonctionnelle formalisée correspondant à la pratique effective des utilisateurs.

Compétences présentes à la DiRIF en 2024
*****************************************
Les effectifs dédiés à SIRIUS qui demeurent à la DiRIF sont des administrateurs système et des exploitants qui font fonctionner SIRIUS.

Compétences fonctionnelles
============================
Aujourd'hui, à la DiRIF, la compétence fonctionnelle se situe à UCTIR, à UIRC et dans les PCTT. 
Il s'agit d'une connaissance à la manière dont l'outil SIRIUS est utilisé à la DiRIF.

Les personnes présentes seront essentielles pour la conception d'un nouvel SAGT, mais elles ne sont pas en mesure de faire le travail de spécification fonctionnelle nécessaire. 
Ce travail nécessite des compétences différentes d'analyse et de modélisation.

Il faut aussi avoir du recul pour envisager de faire certaines choses autrement qu'aujourd'hui. 
Il faut enfin examiner ce qui se fait ailleurs, car de nombreux SAGT ont été développés dans le monde et il y certainement des enseignements à en tirer.

Quelque soit le scénario d'évolution retenu et même avec l'apui d'AMO externes, il sera nécessaire de se doter de compétences pour piloter la spécification des évolutions fonctionnelles et l'adaptation des pratiques de nos opérateurs.


Compétences informatiques
============================
Au sein d'UIRC, plusieurs agents travaillent avec SIRIUS depuis plus de 20 ans. 
Ces personnes détiennent la compétence critique de maintenir SIRIUS en fonctionnement. 
Avec l'obsolescence croissante des composants logiciels, leur expertise est de plus en plus nécessaire et difficile à substituer.

Pour ces personnes, la disparition de SIRIUS imposera une reconvertion qui sera aussi un enrichissement des tâches.

La maîtrise d'ouvrage
**********************
MOA d'un SI
==============
La maitrise d'ouvrage d'un SI qui évolue représente une fonction plus importante que la MOA de la construction d'un ouvrage routier.

La définition des besoins avec les utilisateurs, l'accompagnement du changement, la validation des productions demandent des moyens aussi importants que la construction elle-même.

La MOA du projet SAGACITE mobilise environ 10 personnes dans les DIR et autant chez les AMO (EGIS & SOPRA STERIA).

Comme SIRIUS évolue très peu, l'activité de MOA est faible. Néanmoins, pour se préparer à mener des évolutions, il faudrait déjà mettre en place une organisation de la MOA adaptée.


Qui pilote SIRIUS ?
=======================
Pour UIRC, la MOA de SIRIUS est portée par le DETT car ces à ce niveau que les décions sont prises, mais la maîtrise d'ouvrage ne se limite pas à la seule validation et il n'y a pas de ressource dédiée à cette fonction au niveau DETT.

UCTIR supervise les utilisateurs qui sont les *clients* de SIRIUS, mais les moyens dédiés à cette fontion sont faibles et elle est exercée à minima.
UCTIR est autonome ou du moins leader pour la configuration de SIRIUS, quand il faut mettre en place de nouveaux plans de gestion du trafic ou intégrer des équipements. Cela fait d'UCTIR le client mais pas le MOA du SAGT SIRIUS.

C'est UIRC qui rédige et gère le marché pour l'exploitation et la TMA du système. C'est UIRC qui obtient et engage les crédits.

SIRIUS connait de fréquents aléas et c'est un agent d'UIRC qui est d'astreinte pour y faire face.

Les investissements qui ont été envisagés et présentés à la DMR en 2021 sont uniquement prévus pour répondre à des besoins informatiques et ne prennent pas en considération des évolutions fonctionnels. UIRC était donc autonome dans la definition de ces investissements. 


Projet d'évolution de 2021
=============================
En 2021, UIRC et le titulaire du marché de maintenance OPEN ont élaboré un projet de mise à jour informatique de SIRIUS. 
Ce projet évalué à 4M€ a été présenté à la DMR mais n'a pas été approuvé.

Comme une partie des fonctionnalités de SIRIUS ne sont pas utilisées, la refonte informatique envisagée en 2021 aurait conduit à reconstruire des branches inutiles du systèmes. 

Il manquait à ce projet une dimension fonctionnelle, la remise en cause de l'activité autour du SAGT et l'expliciation des impacts sur ses fonctionnalités.

Besoin de reconstruire une MOA
================================
Les projets de SI sont des projets complexes et il est fréquent que ces projets échouent, après avoir consommé des crédits importants. 
La principale cause des échecs est la faiblesse de la MOA. 
C'est particulièrement vrai dans le secteur public qui a du mal à recruter des ingénieurs expérimentés.

Pour faire évoluer SIRIUS ou pour développer un autre SAGT capable de le remplacer, la plus grosse difficulté sera de mettre en place une MOA compétente sur les aspects fonctionnels.

Pour rénover le SAGT de la DIRIF, il faudra certes des crédits, mais il faudra aussi une organisation de la MOA performante. C'est un vrai défi.

Si la solution est un SAGT mutualisé à l'échelle national, la complexité sera plus grande et les moyens de MOA plus importants.
C'est peu être une ambition irréaliste ou du moins très risquée.















