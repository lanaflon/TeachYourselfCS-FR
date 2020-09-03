# Apprenez les sciences informatiques

> This document is a French translation of [TeachYourselfCS](https://teachyourselfcs.com), written by [Ozan Onay](https://twitter.com/oznova_) and [Myles Byrne](https://twitter.com/quackingduck).

:warning: Work in progress :warning:  

Que vous soyez autodidacte, hobbyiste, ou jeune apprenant vous vous devez d'apprendre et comprendre les sciences informatiques.  
Heureusement, il n'est pas nécessaire de perdre des années et une fortune pour obtenir ces connaissances.

Il existe aujourd'hui de nombreuses ressources mais certaines sont meilleurs que d'autres. Vous n'avez pas besoin d'une énième liste "200 cours en ligne gratuits".
Ce dont vous avez besoin, ce sont des réponses à ces questions : 
* **Quels sujets** devez vous apprendre et pourquoi ?
*  Quel est le **meilleur livre ou série de vidéos** pour chaque sujet ?

Ce guide est notre réponse à ces questions.

## TL;DR: (Résumé)

Etudiez les neufs sujets ci-dessous, plus ou moins dans l'ordre d'apparition. En utilisant soit le livre proposé ou les leçons vidéos, idéalement les deux.
Visez entre 100 et 200 heures d'étude pour chaque sujet. Et revisitez vos cours favoris au cours de votre carrière 🚀.


| Sujet                                           | Pourquoi étudier ?                                                                                                                                | Livre                                              | Vidéos                      |
|---------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------|-----------------------------------|
| **[Programmation](#programmation)**                   | Ne soyez pas celui qui n'a jamais vraiment compris quelque chose comme la récursion | _Structure and Interpretation of Computer Programs_     | Brian Harvey Berkeley CS 61A    |
| **[Architecture informatique](#architecture-informatique)**  | Si vous n'avez pas une vision précise du fonctionnement d'un ordinateur, toutes vos abstractions de haut niveau seront fragiles      | _Computer Systems: A Programmer's Perspective_ | Berkeley CS 61C |
| **[Algorithmes et structures de données](#algorithmes-et-structures-de-données)**| Si vous ne comprennez pas les structures de données comme les piles, les files ou les arbres il vous sera difficile de résoudre des problèmes complexes | _The Algorithm Design Manual_ | Conférences de Steven Skiena          |
| **[Mathématiques pour l'informatique](#mathématiques-pour-linformatique)** | L'informatique, c'est des mathématiques. Comprendre les mathématiques vous donnera un avantage concurrentiel | _Mathematics for Computer Science_ | Tom Leighton MIT 6.042J         |
| **[Systèmes d'exploitation](#systèmes-dexploitation)**   | Le gros du code que vous écrivez est exécuté par un système d'exploitation, vous vous devez donc de savoir comment ceux-ci fonctionnent. | _Operating Systems: Three Easy Pieces_ | Berkeley CS 162                   |
| **[Réseaux informatiques](#réseaux-informatiques)**           | Internet est omniprésent, il est important de comprendre comment il fonctionne pour en exploiter tout le potentiel. | _Computer Networking: A Top-Down Approach_ | Stanford CS 144 |
| **[Bases de données](#bases-de-données)**                 | Les bases de données sont au cœur de la plupart des programmes mais rares sont ceux qui comprennent comment fonctionnent réellement ces systèmes	 | _Readings in Database Systems_                          | Joe Hellerstein Berkeley CS 186 |
| **[Langages et compilateurs](#langages-et-compilateurs)**       | Si vous comprenez comment les langages et les compilateurs fonctionnent réellement, vous écrirez un code de meilleure  qualité et apprendrez de nouveaux langages plus facilement.  | _Crafting Interpreters_ | Cours d'Alex Aiken sur edX |
| **[Systèmes distribués](#systèmes-distribués)** | De nos jours, la plupart des systèmes sont des systèmes distribués. | _Designing Data-Intensive Applications_ | MIT 6.824          

## C'est trop ?
Si l'idée d'étudier 9 sujets en autodidacte sur plusieurs années vous semble trop difficile, nous vous suggérons de vous concentrer sur deux livres : [_Computer Systems: A programmer's perspective (CS:APP)_](http://csapp.cs.cmu.edu/3e/home.html) et [_Designing Data-Intensive Applications_](https://www.amazon.fr/Designing-Data-Intensive-Applications-Martin-Kleppmann/dp/1449373321) 
Ces deux livres offrent un très bon retour sur investissement, en particulier pour les ingénieurs autodidactes et les diplômés des bootcamps qui travaillent sur des applications en réseau. Ils peuvent également servir de passerelle pour les autres sujets énumérés ci-dessus.

## Pourquoi apprendre les sciences informatiques ? 
Il existe deux types d'ingénieurs logiciels : ceux qui comprennent suffisamment bien l'informatique pour en faire un travail stimulant et innovant, 
et ceux qui s'en sortent simplement parce qu'ils utilisent des outils de haut niveau.  

> Le système mondial de SMS traite environ 20 milliards de messages par jour. Whatsapp en fait plus de 42 milliards, avec 57 ingénieurs. [pic.twitter.com/zZrtSIzhlR](https://t.co/zZrtSIzhlR)

> — Benedict Evans (@BenedictEvans) [2 Février 2016](https://twitter.com/BenedictEvans/status/694342874729545729)

Tous deux se disent ingénieurs et on tendance à gagner des salaires similaires en début de carrière. 
Mais la première catégorie progresse plus vite vers un travail mieux rémunéré, qu'il s'agisse d'un travail à forte valeur ajoutée, 
ou de projets open-source innovants ou d'un rôle de leader.

La catégorie 1 trouve des moyens d'apprendre les sciences informatiques en profondeur, de façons conventionnelles ou en apprenant sans 
relâche tout au long de leur carrière. La catégorie 2 quant à elle reste généralement à la surface, apprend des outils et techniques précises plutôt que leurs bases, 
n'acquérant de nouvelles compétences que lorsque le vent de la mode technique souffle.

Actuellement, le nombre de personnes qui entrent dans l'industrie augmente fortement, tandis que le nombre de diplômés de l'enseignement supérieur stagne.
Cette offre excédentaire d'informaticiens de catégorie 2 commence à réduire les possibilités d'emploi. Que vous vous efforciez de devenir un développeur
de catégorie 1, ou que vous êtes seulement à la recherche d'une sécurité de l'emploi, 
l'apprentissage de l'informatique à sa source est la seule voie fiable.

> Note traducteur : Les livres payants présentés dans ce document sont disponibles sur Amazon, mais vous pouvez les récupérer gratuitement sur internet avec un peu de recherche.

## Guide des sujets 

### Programmation 

La plus part des cursus universitaires commencent par une introduction à la programmation informatique.  
Les meilleurs cours ne sont pas uniquement destinés aux novices, mais aussi à ceux qui ont manqué des concepts utiles en apprenant à programmer.

Notre recommandation de référence pour ce sujet est le classique _Structure and Interpretation of Computer Programs_ qui est disponible gratuitement sous la forme d'un [ebook](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html) ou d'une [série de conférences du MIT](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/).  
Bien que ces conférences soient bonnes, nous suggérons plutôt les conférences [SICP de Brian Harvey](https://archive.org/details/ucberkeley-webcast-PL3E89002AA9B9879E?sort=titleSorter) (Pour le cours 61A de l'université de Berkeley). Ces cours sont plus détaillés et mieux adaptés aux nouveaux étudiants que les cours du MIT.

Depuis la première publication de ce guide en 2016, l'une des questions 
les plus fréquemment posées a été de savoir si nous recommandons désormais 
les enregistrements d'une version plus récente de 61A enseignée cette fois par John DeNero, et/ou le livre correspondant [Composing Programs](https://composingprograms.com/), 
qui est "dans la tradition du SICP" mais utilise Python. Nous pensons que les vidéos de DeNero sont excellentes et que certains étudiants pourraient finir par les préférer, 
mais nous suggérons tout de même les cours de SICP de Brian Harvey avec Scheme comme première série de ressources à essayer.  

Pourquoi ? Parce que SICP est unique et à la capacité à modifier vos croyances fondamentales sur l'informatique et la programmation.  
Tout le monde ne ressentira pas ça. Certains détesteront le livre, d'autres ne dépasseront pas les premières pages. Mais la récompence potentielle fait qu'il vaut la peine d'être lu.  

Si vous n'aimez vraiment pas SICP, essayez donc _Composing Programs_. Si cela ne vous convient toujours pas, essayez alors [How To Design Programs](http://www.htdp.org/).
Et si aucune de ces propositions ne semble récompenser vos efforts, c'est peut être le signe que vous devriez vous concentrer sur d'autres sujets pour le moment, et revenir à celui ci dans un an ou deux.  

Enfin, point important  : ce guide n'est PAS conçu pour ceux qui sont entièrement nouveaux dans la programmation. Nous partons du principe que vous êtes un programmeur sans réelle formation cherchant à combler certaines lacunes.  
Le fait que nous ayons inclus le sujet Programmation est simplement un rappel qu'il y a peut être plus à apprendre. 
Pour ceux qui n'ont jamais codé auparavant, mais qui aimeraient le faire, vous préférerez peut-être un guide comme [celui-ci](https://www.reddit.com/r/learnprogramming/wiki/faq#wiki_getting_started).

![Livre SICP](https://teachyourselfcs.com/sicp.jpg)


### Architecture Informatique 

L'architecture informatique, parfois appelée "système informatique" est un premier aperçu important de ce qui se passe sous la couche logicielle. Selon notre expérience, c'est le domaine le plus souvent négligé par les autodidactes. 

Notre livre d'introduction favori est [_Computer Systems: A programmer's perspective (CS:APP)_](http://csapp.cs.cmu.edu/3e/home.html). 
Un cours typique d'introduction à l'architecture informatique [couvrirait](http://csapp.cs.cmu.edu/3e/courses.html) les chapitres de 1 à 6.

CS:APP est apprécié pour son approche pratique pensée pour les programmeurs. Ce livre est un bon point de départ pour ceux qui souhaitent comprendre les systèmes informatiques dans l'objectif d'écrire des logiciels plus fiables et efficients. 
Pour ceux qui préfèrent une introduction plus accessible entre le matériel et les logiciels nous suggérons le cours _The elements of computing systems_ aussi connu sous le nom de [Nand2Tetris](https://www.nand2tetris.org). Il s'agit d'un livre qui tente de vous donner une bonne compréhension de la façon dont tout fonctionne dans un ordinateur. Chaque chapitre implique la création d'une petite partie du système informatique, de l'écriture des portes logiques élémentaires en HDL en passant par le processeur, l'assembleur jusqu'à une application de la taille d'un jeu Tetris.  

Nous vous recommandons de lire les six premiers chapitres du livre et de réaliser les projets associés. Cela vous permettra de mieux appréhender la relation entre l'architecture machine et le logiciel. 

La première moitié du livre (et tous ses projets) sont disponibles gratuitement sur [Nand2Tetris](https://www.nand2tetris.org). Il est aussi disponible sous la forme de deux cours Coursera : 
- [Nand2Tetris I (Matériel, chapitre 1-6)](https://www.coursera.org/learn/build-a-computer)
- [Nand2Tetris II (Logiciel, chapitre 7-12)](https://www.coursera.org/learn/nand2tetris2)

Ce que Nand2Tetris gagne en simplicité, il le perd en profondeur, en particulier sur le [pipelining](https://fr.wikipedia.org/wiki/Pipeline_(architecture_des_processeurs)) et la [hierarchie de mémoire](https://fr.wikipedia.org/wiki/Hiérarchie_de_mémoire). Tous deux sont absents des textes.

Une fois que vous vous sentirez à l'aise avec le contenu de ce cours, nous vous suggérons soit de revenir à CS:APP, soit de vous penchez sur [_Computer Organization and Design_](https://www.amazon.fr/Computer-Organization-Design-MIPS-Interface/dp/0124077269) de Patterson et Hennessy, un excellent texte désormais classique. Toutes les parties de ce livre ne sont pas essentielles; nous vous conseillons de suivre le cours de l'université de Berkeley [_CS61C_](http://inst.eecs.berkeley.edu/~cs61c/sp15/) _Great ideas in computer architecture_ pour des lectures spécifiques. Les notes de cours et les archives des anciens cours sont disponibles sur l'[Internet Archive](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iCl2-D-FS5mk0jFF6cYSJs_).

<img src="https://teachyourselfcs.com/csapp.jpg" alt="Livre SICP" width="207"/>

> Le matériel est la plateforme
> 
> — Mike Acton, Directeur moteur chez Insomniac Games
> ([Regarder sa conférence CppCon](https://www.youtube.com/watch?v=rX0ItVEVjHc))


### Algorithmes et structures de données

L'un des aspect les plus valorisants d'une formation classique en informatique est l'apprentissage des algorithmes et structures de données les plus utilisés. C'est également un bon endroit pour améliorer ses capacités de résolution de problèmes, qui seront utiles dans tous les autres domaines d'étude.

Il y a des centaines de livres à ce sujet, mais notre préféré est [_The Algorithm Design Manual_](https://www.amazon.fr/Algorithm-Design-Manual-Steven-Skiena/dp/1849967202) de Steven Skiena. Il est clair qu'il aime la résolution de problèmes algorithmiques et réussit à transmettre son enthousiasme chez ses élèves et lecteurs. Selon nous, les deux textes les plus couramment proposés (CLRS et Sedgewick) ont tendance à être trop chargés en matières de preuves pour un lecteur dont l'objectif principal et d'améliorer ses capacités de résolution de problèmes. 

Pour ceux qui préfèrent les vidéo-conférences, [_Steven Skiena propose généreusement ses vidéos sur Youtube_](https://www.youtube.com/watch?v=A2bFN3MyNDA&list=PLOtl7M3yp-DX32N0fVIyvn7ipWKNGmwpp). On apprécie aussi celles de Tim Roughgarden disponibles sur [Coursera](https://www.coursera.org/specializations/algorithms), le choix entre Skiena et Roughgarden est simplement une question de préférence. D'ailleurs, il y a des dizaines d'alternatives pour l'étude algorithmique et les structures de données, alors si vous en trouvez une à votre goût, nous vous encourageons à continuer.

Pour la pratique, on recommande de résoudre des problèmes sur des sites comme : 
- [Leetcode](https://leetcode.com)
- [CodeWars](https://www.codewars.com)
- [CodingGame](https://www.codingame.com)  

Il s'agit le plus souvent de problèmes intéressants et proches de cas réels accompagnés de solutions et d'échanges avec les autres joueurs. Nous vous suggérons de résoudre une centaine de problèmes aléatoires dans le cadre de vos études.

> Note traducteur : Il me semble plus utile d'utiliser ces sites tout au long de votre carrière quand vous avez un peu de temps libre.

Enfin nous vous recommandeons vivement [How To Solve It](https://www.amazon.fr/How-Solve-Aspect-Mathematical-Method-dp-069116407X/dp/069116407X/ref=dp_ob_title_bk) qui est un excellent et unide guide pour la résolution de problèmes; il est autant applicable aux mathématiques qu'en informatique.  

![Livre Skiena](https://teachyourselfcs.com/skiena.jpg) ![Livre HTSI](https://teachyourselfcs.com/polya.jpg)

### Mathématiques pour l'informatique

Dans un sens, l'informatique est une branche des mathématiques appliquées qui a pris de l'ampleur. Bien que de nombreux développeurs essaient et réussissent plus ou moins à ignorer cela, nous vous encourageons fortement à l'accepter. Si vous y parvenez, vous bénéficierez d'un avantage énorme sur les autres.

Le domaine mathématique le plus pertinent pour l'informatique est appelé _mathématiques discrètes_ où "discret" est l'opposé de "continu". L'objectif est de développer une compréhension pratique de la logique, de l'analyse combinatoire, des probabilités, de la théorie des ensembles, de la théorie des graphes et un peu de la théories des nombres pour la cryptographie.

L'algrèbre linéaire est un autre domain d'étude important, compte tenu de son importance dans l'infographie et le machine learning. 

Notre suggestion pour débuter les mathématiques discrètes est le [jeu de notes de cours de László Lovász](http://www.cs.elte.hu/~lovasz/dmbook.ps). Le professeur Lovász a réalisé un bon travail pour rendre le contenu accessible et intuitif, ce qui en fait un meilleur point de départ que la plupart des textes plus formels. 

Pour un traitement plus avancé, nous vous conseillons [Mathematics for Computer Science](https://courses.csail.mit.edu/6.042/spring17/mcs.pdf), le livre de notes pour le cours MIT du même nom. Nous recommandons aussi les conférences de ce cours, disponibles gratuitement.

Quant à l'algèbre linéaire, nous conseillons de commencer avec la série youtube [Essence of linear algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) suivie du travail de Gilber Strang, son livre [Introduction to Linear Algebra](https://www.amazon.fr/Introduction-Linear-Algebra-Gilbert-Strang/dp/0980232775) et [ses conférences](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/)

> Si les gens ne croient pas que les mathématiques sont simples, c'est seulement parce qu'ils ne réalisent pas à quel point la vie est compliquée.
> 
> — John von Neumann

### Systèmes d'exploitation

[_Operating System Concepts_](https://www.amazon.fr/Operating-System-Concepts-Abraham-Silberschatz/dp/1118063333) et [_Modern Operating Systems_](https://www.amazon.fr/Modern-Operating-Systems-Andrew-Tanenbaum/dp/1292061421) sont tous deux des classiques dans le domaine des systèmes d'exploitation. Mais tous deux ont été critiqués pour leur manque de clarté et d'accessibilité pour les étudiants. 

_Operating Systems: Three Easy Pieces_ (OSTEP) est une bonne alternative, disponible gratuitement [ici](http://pages.cs.wisc.edu/~remzi/OSTEP/) ainsi que sur [github](https://github.com/mthipparthi/operating-systems-three-easy-pieces/blob/master/book.pdf). Nous apprécions particulièrement la structure et la lisiblité de ce livre et nous pensons que les différents exercices de celui ci en valent la peine. 

Après avoir lu OSTEP, nous vous encourageons à creuser les décisions de conception des OS qui vous intéressent. Comme par exemple [_Lion's commentary on Unix_](https://www.amazon.fr/Lions-Commentary-Unix-Source-Code/dp/1573980137), [_The design and Implementation of the FreeBSD Operating System_](https://www.amazon.fr/Design-Implementation-FreeBSD-Operating-System/dp/0321968972) et [_Mac OS X Internals_](https://www.amazon.fr/Singh-Mac-OS-Internals-_p1/dp/0134426541).
Pour Linux, nous recommandons le fantastique ouvrage de Robert Love [_Linux Kernel Development_](https://www.amazon.fr/Linux-Kernel-Development-Robert-Love/dp/0672329468).

Une bonne façon de consolider votre compréhension des systèmes d'exploitation est de lire le code d'un petit noyau et d'y ajouter des fonctionnalités. L'un des choix possible est [_xv6_](https://pdos.csail.mit.edu/6.828/2016/xv6.html), un port d'Unix V6 vers ANSI C pour microprocesseurs x86, maintenu pour un cours du MIT. OSTEP dispose d'une section dédiée à xv6 avec de bonnes idées pour de potentiels projets.

![Livre OSTEP](https://teachyourselfcs.com/ostep.jpeg)

### Réseaux informatiques

Étant donné qu'une grande partie du génie logiciel se trouve sur des serveurs et clients web, l'un des secteurs les plus importants de l'informatique est celui des réseaux. Les autodidactes qui étudient méthodiquement ce domaine comprendront enfin termes, concepts et protocoles qui les entourent depuis des années.

Notre livre préféré sur le sujet est [_Computer Networking: A Top-Down Approach_](https://www.amazon.fr/Computer-Networking-Top-Down-Approach-International/dp/0273768964). Les différents projets et exercices du livre valent la peine d'être faits, et nous apprécions particulièrement les "Wireshark labs" qu'ils ont [généreusement mis à disposition en ligne](http://www-net.cs.umass.edu/wireshark-labs/). 

![Livre CNATDA](https://teachyourselfcs.com/top-down.jpg)

### Bases de données

Apprendre par soi-même les bases de données demande plus de travail que les autres matières. C'est un domaine d'étude relativement récent (postérieur à 1970) avec de fortes pressions commerciales pour que les nouvelles idées ne s'ébruitent pas. De plus, de nombreux auteurs de livres potentiellement excellents ont préféré rejoindre ou créer des entreprises.

Compte tenu des circonstances, nous conseillons aux autodidactes d'éviter les livres et de commencer par le cours sur les bases de données de Joe Hellerstein à Berkeley : [_CS 186_](https://www.youtube.com/user/CS186Berkeley/videos) et de passer ensuite à la lecture papier.

Un document particulièrement intéressant pour les débutants est [_Architecture of a Database System_](https://dsf.berkeley.edu/papers/fntdb07-architecture.pdf), qui offre une vue haut niveau sur le fonctionnement des systèmes de gestion de bases de données relationnelles (SGBDR). Ce document servira de base utile pour des études plus approfondies.

Readings in Database Systems, mieux connu sous le nom de [_the databases "Red Book"_](http://www.redbook.io), est un recueil de textes compilés et édités par Peter Bailis, Joe Hellerstein et Michael Stonebraker. Pour ceux qui ont terminé le contenu de CS 186, le Red Book devrait être votre prochaine étape.

Si vous tenez absolument aux livres, nous recommandons [_Database Management Systems_](https://www.amazon.fr/Database-Management-Systems-Raghu-Ramakrishnan/dp/0072465638) de Ramakrishnan et Gehrke. Pour les étudiants avancés, le classique [_Transaction Processing: Concepts and Techniques_](https://www.amazon.fr/Transaction-Processing-Techniques-Jim-Gray/dp/1558601902) de Jim Gray est intéressant. Mais nous déconseillons de l'utiliser comme première ressource. 

Pour finir, la modélisation des données est un aspect négligé et souvent mal enseigné. Sur ce sujet, nous proposons le livre [_Data and Reality: A Timeless Perspective on Perceiving and Managing Information in Our Imprecise World_](https://www.amazon.fr/Data-Reality-Perspective-Perceiving-Information/dp/1935504215) aussi disponible via [github](https://github.com/jhulick/bookstuff/blob/master/Data%20and%20Reality.pdf)

![redbook](https://teachyourselfcs.com/redbook.jpg) ![datareality](https://teachyourselfcs.com/data-reality.jpg)


### Langages et compilateurs

La plupart des programmeurs apprennent des langages spécifiques, alors qu'il est préférable de se concentrer sur les technologies dans leur globalités. Cela permet de généraliser ses connaissances et de comprende plus facilement et profondément la logique et le fonctionnement d'un nouveau langage.

Nous vous conseillons le texte disponible gratuitement de Bob Nystrom intitulé [_Crafting Interpreters_](https://craftinginterpreters.com/contents.html). Il est bien structuré et très divertissant ce qui est parfait pour des personnes dont l'objectif est de simplement mieux comprendre les langages de programmation. Nous recommandons de suivre le cours complet et de relever les défis qui vous motivent. 

Le livre [_Compilers: Principles, Techniques & Tools_](http://ce.sharif.edu/courses/94-95/1/ce414-2/resources/root/Text%20Books/Compiler%20Design/Alfred%20V.%20Aho,%20Monica%20S.%20Lam,%20Ravi%20Sethi,%20Jeffrey%20D.%20Ullman-Compilers%20-%20Principles,%20Techniques,%20and%20Tools-Pearson_Addison%20Wesley%20(2006).pdf) aussi appelé "Dragon Book" représente une approche plus traditionnelle mais nous ne le recommandons pas pour de l'apprentissage autodidacte. En effet, celui ci est plus adapté aux professeurs qui souhaitent y sélectionner des sujets pour leurs cours.

Si vous décidez d'utiliser le Dragon Book, il est alors essentiel de bien choisir les sujets, idéalement avec l'aide d'une personne plus experimentée. D'ailleurs, la façon dont nous recommandosn l'utilisation du Dragon Book est en tant que ressource supplémentaire pour les cours de Alex Aiken sur [edX](https://www.edx.org/course/compilers) 

![Dragon Book](https://teachyourselfcs.com/dragon.jpg)


### Systèmes distribués

Les ordinateurs ne se sont pas seulement multipliés ces 15 dernières années, ils se sont aussi répandus. Alors qu'auparavant les entreprises achetaient d'énormes ordinateurs centraux, il est maintenant courant, même pour de très petites application de s'éxecuter sur plusieurs machines. Le domaine des systèmes distribués est l'étude de la manière de réfléchir aux compromis que cela implique.

Pour de l'apprentissage autodidacte, nous suggérons le livre [_Designing Data–Intensive Applications_ (DDIA)](https://www.amazon.fr/Designing-Data-Intensive-Applications-Martin-Kleppmann/dp/1449373321) de Martin Kleppmann. Bien meilleur qu'un livre traditionnel, DDIA est avant tout simple à lire et est pensé pour la pratique sans toutefois perdre en rigueur et profondeur.

Pour ceux à la recherche d'un texte plus traditionnel, ou qui préféreraient simplement une ressource disponible gratuitement, nous suggérons [_Distributed Systems, 3rd edition_](https://www.distributed-systems.net/index.php/books/ds3/), de Maarten van Steen et Andrew Tanenbaum.

Enfin, pour ceux qui préfèrent la vidéo, [_6.824 du MIT_](https://www.youtube.com/watch?v=cQP8WApzIQQ&list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB) est un excellent cours enseigné par Robert Morris avec des documents texte disponible [ici](https://pdos.csail.mit.edu/6.824/schedule.html)

Quel que soit votre choix, l'étude des systèmes distribués exige la lecture de documents texte. Une bonne liste est disponible [ici](http://dsrg.pdos.csail.mit.edu/papers/) et nous vous encourageons fortement à participer au chapitre de votre région de [_Papers We Love_](http://paperswelove.org/)

> Notre traducteur : [Pour plus d'informations sur Papers We love](https://github.com/papers-we-love/organizers)

<img src="https://teachyourselfcs.com/ddia.jpg" alt="Livre DDIA" width="207"/>


## Questions fréquemment posées

### A qui s'adresse ce guide ? 

Ce guide vise les autodidactes, les lycéens, les professionnels. Savoir quand se lancer dans ce projet est tout à fait personnel mais la majorité des gens à tendance à tirer profit d'une expérience professionnelle avant de plonger en profondeur dans les sciences informatiques. Par exemple, nous avons remarqué que les étudiants aiment en apprendre plus sur les bases de données s'ils ont déjà eu à travailler avec celles-ci professionnellement, de même pour le réseau avec une exérience de projet web. 

### Qu'en est-il de l'IA/Programmation graphique/sujet-X... ?

Nous avons essayé de limiter notre liste à ce qui nous semblait le plus pertinent pour chaque ingénieur indépendamment de sa spécialité ou industrie. Selon notre expérience, ces sujets offrent le meilleur retour sur investissement pour la majorité de nos étudiants et constituent une base solide pour une éventuelle poursuite d'études. Vous serez alors en bien meilleure posture pour étudier des manuels plus traditionnels ou des articles scientifiques. Voici quelques points de départ pour des cours facultatifs : 
 - Intelligence Artificielle : suivez le [cours d'introduction à l'IA](http://ai.berkeley.edu/) de Berkeley en réalisant aussi l'excellent projet Pacman. Pour ce qui est d'un livre, [_Artificial Intelligence : A Modern Approach_](https://www.amazon.fr/Artificial-Intelligence-Approach-Stuart-Russell/dp/0136042597) de Russel et Norvig est un bon choix.
 - Machine Learning : Faites le cours d'Andrew Ng :[_Machine learning_](https://fr.coursera.org/learn/machine-learning) sur Coursera. Restez patient et assurez-vous de bien assimiler les principes fondamentaux avant de vous lancer dans des sujets plus.. attirants comme le deep learning.  
 - Programmation graphique : Suivez les cours [_CS184_](http://inst.eecs.berkeley.edu/~cs184/fa12/onlinelectures.html) de l'université de Berkeley et utilisez [_Computer Graphics: Principles and practice_](https://www.amazon.fr/Computer-Graphics-Principles-John-Hughes/dp/0321399528) comme livre.
 
### Quelle est la rigueur de la séquence d'apprentissage proposée ?

En pratique, tous les sujets proposés se recoupent et se renvoient les uns aux autres. Par exemple, la relation entre les mathématiques et l'algorithmie : Apprendre les mathématiques en priorité vous aiderait à analyser et à comprendre vos algorithmes plus efficacement, mais apprendre l'algorithmique d'abord vous motiverait d'avantage et fournirait un meilleur contexte. Idéalement, vous devriez revenir sur ces deux sujets plusieurs fois durant votre carrière.

Ainsi, notre ordre d'apprentissage est d'avantage là pour vous aider à démarrer quelque part. Si vous avez une raison de préférer une séquence différente, alors allez-y. Les "pré-requis" les plus importants sont : l'architecture informatique avant les systèmes d'exploitation ou les bases de données et les réseaux informatiques et les systèmes d'exploitation avant les systèmes distribués.

### Quelle est la différence entre votre guide et Open Source Society ou freeCodeCamp ?

Quand ce guide a été rédigié pour la première fois en 2016, le guide [OSS (Open Source Society)](https://github.com/ossu/computer-science) comportait trop de sujets, suggérait des ressources de moins bonne qualité et ne fournissait aucune justification sur les raisons pour lesquelles certains cours sont considérés utiles. 
Nous nous sommes efforcés à restreindre notre liste de modules à ceux qu'un ingénieur informatique se doit de connaître et à vous aider à comprendre pourquoi chaque cours est inclus. Ces dernières années, OSS s'est amélioré, mais nous pensons toujours que nous offrons une vision plus claire et cohérente.

freeCodeCamp est axé sur la programmation uniquement, pour savoir pourquoi il est important d'apprendre l'informatique dans sa globalité, voir [ci-dessus](#Pourquoi-apprendre-les-sciences-informatiques-? ). Si vous êtes débutant en programmation, alors concentrez dessus et revenez à ce guide dans un an ou deux.

### Qu'en est-il du langage-X ?

L'apprentissage un langage de programmation précis est beaucoup plus facile mais moins utile pour votre carrière. Si vous en connaissez déjà quelques-uns, nous vous conseillons alors de suivre notre guide et d'apprendre de nouveaux langages entre les blancs, ou de remettre cela à plus tard. Si vous maitrisez la [Programmation](#programmation) et les [ compilateurs](#langages-et-compilateurs) alors il ne vous faudra pas plus d'un week-end pour apprendre les bases d'un nouveau langage, après quoi il vous suffira de vous familiariser avec son écosystème sur le tas.

### Qu'en est-il de la technologie du moment ?

Aucune technologie à elle seule n'est assez importante pour que son apprentissage soit au coeur de votre éducation. Cela dit, il est bon d'être excité à l'idée d'apprendre des choses. L'astuce est d'apprendre en profondeur les concepts de cette technologie à la mode avant de voir comment celle-ci s'intègre dans le tableau d'ensemble. 

### Pouquoi recommandez vous toujours SICP ?

Essayez. Certaines personnes trouvent le SICP époustouflant, une caractéristique que partagent très peu d'autres livres. Si vous n'aimez pas, vous pouvez toujours essayer autre chose et peut-être revenir à SICP plus tard.

### Pourquoi recommendez vous toujours le Dragon Book ?

Le Dragon Book est encore aujourd'hui le livre le plus complet sur les compilateurs. Il est généralement mal vu car il s'attarde trop sur certains sujets moins à la mode de nos jours, comme l'analyse syntaxique. Le fait est que ce livre n'a pas été pensé pour l'étude en détail mais plutôt comme une source d'informations pour les préparations de cours des professeurs. De la même façon, un autodidacte peut tracer son propre chemin à travers ce livre, ou mieux encore, suivre les suggestions des instructeurs de cours en ligne.

### Comment puis-je obtenir ces livres à bas prix ?

La plupart des livres proposés sont disponibles gratuitement en ligne grâce à la générosité de leurs auteurs. Pour ceux qui ne le sont pas, il est alors possible d'acheter des exemplaires d'occasion d'anciennes éditions. En général, une ancienne édition convient parfaitement. Il est peu probable que la dernière édition soit 10x meilleure qu'une ancienne.

### Qui est derrière ce guide ? 

Ce guide a été écrit par [Oz Nova](https://twitter.com/oznova_) et [Myles Byrnes][https://twitter.com/quackingduck], avec une mise à jour en 2020 par Oz. Il est basé sur notre expérience de formateurs avec plus de 1000 diplômés de bootcamp, pour la plupart autodidactes, dans de petits groupes à San Francisco et en ligne. Merci à tous nos étudiants pour leurs retours sur les ressources d'auto apprentissage.

Nous sommes très confiants quant à votre capacité à tout apprendre par vous même avec beaucoup de temps et de motivation. Mais si vous préférez un programme intensif, plus structuré et dirigé par un formateur, vous pourriez alors être intéressé par notre [_cours intensif_](https://bradfieldcs.com/csi/).
