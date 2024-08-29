SIRIUS, le SAGT de la DiRIF
###################################################

Création de SIRIUS
**********************
Dans les années 1990-2005, des investissements considérables ont été consacrés à la gestion du trafic, sur le réseau routier national de l'Ile de France.
Sur la partie la plus dense du réseau, des points de mesures du trafic ont été implantés tous les 500 mètres. 
Un SAGT a été conçu de toutes pièces avec des moyens d'ingénierie propres et le recours à des sociétés de services.
Une telle réalisation était inédite en 2000.

Pour construire SIRIUS il a fallu un travail de conception fonctionnelle d'une part et le développement du SI d'autre part.
Ce chantier a reposé sur des équipes de MOA nombreuses qui ont été dispersées une fois le travail achevé.

Maintenance de SIRIUS
************************
Alors que SIRIUS avait bénéficié initialement de crédits abondants, les moyens pour le maintenir par la suite ont été très insuffisants. Dans ces conditions, les évolutions fonctionelles ont été rares. 

Les outils informatiques (systèmes d'exploitation, gestionnaires de bases de données, utilitaires ...) sur lesquels repose un SI évoluent. Cela impose en principe d'adapter les codes des applications tous les 5 à 10 ans.
SIRIUS a pris beaucoup de retard dans cette matière.

Aujourd'hui, SIRIUS fonctionne mais certains de ses modules reposent sur des systèmes d'exploitation (OS) qui ne sont plus maintenus par leurs concepteurs tels que Windows XP. Cette situation présente des risques en termes de cybersécurité.

Trois agents de la DiRIF assurent la maitrise d'ouvrage de la maintenance de SIRIUS. Ces personnes travaillent sur ce SI depuis plus de 20 ans. Les entreprises qui se sont succédées, comme titulaires du marché de maintenance, rencontrent des difficultés à trouver les compétences capables de travailler avec les outils d'il y a 20 ans et les agents de la DiRIF sont fortement solicitées pour les assister ou pour se substituer à elles quand des aléas surgissent.

Adéquation fonctionnelle de SIRIUS
***************************************
Les responsables fonctionnels de SIRIUS sont également présents dans cette fonction depuis très longtemps. Ils ont su faire beaucoup de choses au système mais ne l'utilisent pas toujours selon les représentations des concepteurs. Une partie des fonctions introduites initialement dans SIRIUS ne sont plus utilisées.

Ayant acquis une virtuosité de SIRIUS et ne connaissant pas d'autre outil, ils ne sont pas demandeurs d'évolutions significatives. Ils craignent en revanche de se voir imposé un autre SAGT sur lequel ils seront débutants et peineront à reproduire les fonctions qu'ils utilisent aujourd'hui.

La documentation fonctionnelle de SIRIUS n'est plus consultée et ne rend pas bien compte de la manière dont SIRIUS est effectivement utilisé. Cette situation est un obstacle supplémentaire à l'évolution de SIRIUS.

Même une évolution qui se voudrait *isofonctionnelle* rencontrerait des difficultés en l'absence d'une spécification fonctionnelle correspondant à la pratique des utilisateurs.

Introduction des données FCD dans SIRIUS
**********************************************
La principale évolution de SIRIUS des 15 dernières années a été l'utilisation des FCD qui se substituent en partie aux points de mesure du trafic.

La DiRIF utilise les FCD depuis 10 ans environ. Avec la dégradation de la disponibilité des données issues des points de mesure du trafic, les FCD sont devenues la principale source d'information sur l'état du réseau. Les FCD ont permis d'étendre le réseau sur lequel la DiRIF peut visualiser l'état du trafic. On dispose de plus de 5000 mesures quand il ne reste plus que 800 points de mesure dont plus de la moitié est hors service.

Les données FCD sont des données de vitesse moyenne, elles présentent donc un retard de 6 à 20 minutes sur les mesures faites sur le terrain en temps réel. Mais la plus grosse différence tient au fait que les données des points de mesures sont principalement des données de débit et de taux d'occupation alors que les FCD sont des mesures de vitesses.

On aurait pu s'attendre à ce que l'arrivée des FCD donne lieu à une évolution fonctionnelle significative de SIRIUS.
En fait, les FCD ont été introduite avec le minimum de transformation possible du SI.
Le flux FCD est présenté à SIRIUS comme s'il s'agissait de données issues de stations de comptage classiques.
Le document de spécification fonctionnel n'a pas été mis à jour.

En 2023, lors du renouvellement du marché d'acquisition des données FCD, la DIRIF a ajouté 2000 segments dans le cahier des charges. Cela devait permettre de connaitre le fonctionnement des bretelles et d'autres arc connexe au réseau national.

En dépit de cette extension de 40%, le coût pour la DiRIF a été divisé par 2.

Cependant, les données nouvelles n'ont pas pu être intégrées car SIRIUS ne parvenait pas à traiter ce volume supplémentaire de données.

Cette exemple des données FCD montrent que la DiRIF n'est pas organisé pour concevoir des évolutions fonctionnelles significatives de SIRIUS.

Compétences présente à la DiRIF en 2024
*****************************************
Les équipes de développement qui ont fait SIRIUS ont quitté la DiRIF. Les effectifs qui demeurent sont des exploitants qui font fonctionner SIRIUS.

Compétences fonctionnelles
============================
Aujourd'hui, à la DiRIF, la compétence fonctionnelle se situe à UCTIR et dans les PCTT. 
Il s'agit d'une connaissance  à la manière dont l'outil SIRIUS est utilisé à la DiRIF.

Les personnes présentes seront essentielles pour la conception d'un nouvel SAGT, mais elles ne sont pas en mesure de faire le travail de spécification fonctionnelle nécessaire. Ce travail nécessite des compétences différentes  d'analyse et de modélisation.

Il faut aussi avoir du recul pour envisager de faire certaines choses autrement qu'aujourd'hui. Il faut enfin examiner ce qui se fait ailleurs car de nombreux SAGT ont été développés ailleurs dans le monde.

Compétences informatiques
============================
Au sein d'UIRC, plusieurs agents travaillent avec SIRIUS depuis plus de 20 ans. 
Ces personnes sont très compétentes pour maintenir SIRIUS en fonctionnement. 
Avec la vetusté des composants, leur expertise est de plus en plus nécessaire et difficile à substituer.
Pour ces personnes, la disparition de SIRIUS sera une grosse perte car leur expertise  des outils archaïques n'aura plus d'utilité.
Leur participation constructive au remplacement de SIRIUS sera influencée par ce *conflit d'intérêts*.

La maîtrise d'ouvrage
*******************************************
Qui pilote SIRIUS ?
=======================
Quand on interroge les agents d'UIRC, ils répondent que la MOA de SIRIUS est portée par le DETT ou par UCTIR. 

Il est vrai que UCTIR supervise les utilisateurs qui sont les *clients* de SIRIUS. UCTIR est autonome ou du moins leader pour la configuration de SIRIUS, quand il faut mettre en place de nouveaux plans de gestion du trafic ou intégrer des équipements. Cela fait d'UCTIR le client mais pas le MOA du SAGT SIRIUS.

C'est UIRC qui rédige et gère le marché pour l'exploitation et la TMA du système. C'est UIRC qui obtient et engage les crédits.

SIRIUS connait de fréquents aléas et c'est un agent d'UIRC qui est d'astreinte pour y faire face.

Les investissements qui ont été envisagés et présentés à la DMR en 2021 sont uniquement prévus pour répondre à des besoins informatiques et ne prennent pas en considération de besoins fonctionnels. UIRC était donc autonome dans la definition de ces investissements. 

C'est donc UIRC qui assure la MOA effective mais il s'agit d'une MOA par défaut. La dimension fonctionnelle de cette MOA est faible.

Projet d'évolution de 2021
=============================
En 2021, UIRC et le titulaire du marché de maintenance OPEN ont élaboré un projet de mise à jour informatique de SIRIUS. Ce projet évalué à 4M€ a été présenté à la DMR mais n'a pas été approuvé.

Comme une partie des fonctionnalités de SIRIUS ne sont pas utilisées, la refonte informatique envisagée en 2021 aurait conduit à reconstruire des branches inutiles du systèmes. 

En phase de test on se serait trouvé dans l'impossibilité de trouver des utilisateurs capables de valider des fonctions qui leur sont étrangères. 
On n'aurait cependant pas pu tester que les utilisations non formalisées de SIRIUS étaient toujours disponibles.

Besoin de reconstruire une MOA
================================
Les projets de SI sont des projets complexes et il est fréquent que ces projets échouent, après avoir consommé des crédits importants. La principale cause des échecs est la faiblesse de la MOA. C'est particulièrement vrai dans le secteur public qui a du mal à recruter des informaticiens expérimentés.

Pour faire évoluer SIRIUS ou pour développer un autre SAGT capable de le remplacer, la plus grosse difficulté sera de mettre en place une MOA compétente sur les aspects fonctionnels.

















