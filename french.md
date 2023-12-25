# Le guide OSINT atypique

#### Le guide OSINT le plus atypique que vous ayez jamais vu. Le dépôt est destiné uniquement aux professionnels qui s'ennuient. 

#### Les PRs sont les bienvenus ! N'hésitez pas à soumettre une demande d'extraction, avec tout ce que vous souhaitez, des petites corrections aux traductions, en passant par les documents ou les outils que vous aimeriez ajouter.

**Disclaimer : Toutes les informations (outils, liens, articles, textes, images, etc.) sont fournies à des fins éducatives uniquement ! Toutes les informations sont également basées sur des données provenant de sources publiques. Vous êtes seul responsable de vos actions, et non l'auteur** ❗️

[ ![Projet de soutien](https://img.shields.io/badge/Support-Project-critical)](https://github.com/OffcierCia/support/blob/main/README.md)
       [ ![Mail](https://img.shields.io/badge/Mail-offcierciapr%40protonmail.com-brightgreen)](mailto:offcierciapr@protonmail.com)

# Commencez ici

**Check out:**

- [Navigation (mes articles)](https://officercia.mirror.xyz/Uc1sf64yUCb0uo1DxR_nuif5EmMPs-RAshDyoAGEZZY)
- [Article original](https://officercia.mirror.xyz/5KSkJOTgMtvgC36v1GqZ987N-_Oj_zwvGatOk0A47Ws)
- [Également affiché ici !](https://officercia.medium.com/the-atypical-osint-guide-2023-276a8d00959)

Aujourd'hui j'aimerais parler de comment devenir un bon enquêteur OSINT, mais pour continuer la conversation j'aimerais faire un petit disclaimer - je vais vous dire seulement quelques aspects parce que le sujet est très vaste et je ne peux pas tout décrire dans un seul guide, cependant, j'essaierai de vous montrer le chemin et comment passer ce chemin. Ce manuel est l'aboutissement d'années de travail par des professionnels de l'OSINT. Considérez ce guide comme une compilation de conseils et d'itinéraires !

Gardez à l'esprit que cet essai se veut instructif ! Réfléchissez bien à vos actions sous peine d'être poursuivi ou pire ! Gardez toujours à l'esprit l'éthique et les lois connexes - comme le GDPR, etc. Vous ne devriez pas romancer l'OSINT et les enquêtes sur la chaîne de la même manière que les individus romancent souvent le piratage informatique et la guerre, je vous y encourage vivement !

- [Attentat de Boston : comment les détectives de l'internet se sont trompés](https://www.bbc.com/news/technology-22214511)
- [OSINT ? WTF ??](https://ohshint.gitbook.io/oh-shint-its-a-blog/osint/osint-wtf)

> Enfin et surtout, tout ce que vous faites est basé sur les résultats que vous devez atteindre ! Vous devriez être en mesure de sélectionner des sources fiables et vérifiées au lieu d'utiliser tous les outils et tous les liens. Grâce à des itinéraires donnés, vous devriez être en mesure de construire votre propre voyage ! Ensuite, je vous parlerai des méthodes que je considère comme sûres et que je recommande à mes clients ! Les professionnels de l'OSINT ont passé des décennies à élaborer ce manuel, partageant leur expertise dans chaque mot. Encore une fois, considérez ce guide comme une compilation de conseils et d'itinéraires.

Il est également essentiel de noter que l'OSINT n'est qu'un autre moyen d'apprendre à connaître le monde qui vous entoure et qu'il ne s'agit pas d'un moyen de "se faire payer instantanément". Faites toujours une pause pour vous ressourcer ! Votre santé et votre esprit sont importants !

- [Comment savoir quand s'arrêter](https://www.lennysnewsletter.com/p/how-to-know-when-to-stop)
- [Comment devenir un vampire de 1000 ans](https://www.lesswrong.com/posts/5QpufhoH2ASnppsjs/how-to-become-a-1000-year-old-vampire)
- [Comment apprendre rapidement](https://degatchi.com/articles/how-to-learn-fast/)
- [Comment utiliser les cartes heuristiques pour libérer la créativité et le potentiel de votre cerveau](https://lifehacker.com/how-to-use-mind-maps-to-unleash-your-brains-creativity-1348869811)
- [Tout le monde peut-il faire de l'OSINT ?](https://medium.com/osintfun/can-everybody-do-osint-f5d5e6128445)
- [Traumatisme vicariant](https://osintcurio.us/2020/06/08/vicarious-trauma-and-osint-a-practical-guide/)

Ces informations ne vous rendent ni meilleur ni pire. L'humanité, en tant qu'espèce, est encline à s'adapter à son environnement, ce qui, comme nous le savons tous, commence par la connaissance, l'observation et la méthodologie. Prenez soin de vous, réfléchissez aux conséquences de vos actes et respectez la vie privée des autres. Ne franchissez pas les lignes rouges !

<details>
<summary>Expansion</summary>
<br />

- [OSINT + Crypto](https://www.forensicxs.com/blockchain-osint-decentraland/)
- [Nous discutons ici de la manière dont on peut enquêter sur les piratages cryptographiques et les incidents de sécurité](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List)
- [osint.sh Liste d'outils OSINT tout-en-un](https://osint.sh/)
- [La mine d'or pas encore exploitée de l'OSINT : opportunités, défis ouverts et tendances futures](https://www.researchgate.net/publication/338495014_The_Not_Yet_Exploited_Goldmine_of_OSINT_Opportunities_Open_Challenges_and_Future_Trends)

</details>

Réfléchissez toujours à deux fois avant d'agir, respectez la loi et les règles OpSec. Si vous voulez aider ou mener des enquêtes sociales mais que vous manquez d'expérience, veuillez vous adresser à des personnes plus expérimentées afin de ne pas nuire aux victimes ou à ceux qui tentent de les sauver. Dans mes articles, en revanche, je révèle une application différente de l'OSINT, inspirée de la diligence raisonnable et du renseignement financier civil, en mettant l'accent sur les applications **civiles**. C'est ma vision, et j'espère que vous l'adopterez...

- [Études sur le renseignement : les types de collecte de renseignements](https://usnwc.libguides.com/c.php?g=494120&p=3381426)
- [Comprendre les différents types de disciplines de collecte de renseignements](https://www.maltego.com/blog/understanding-the-different-types-of-intelligence-collection-disciplines/)
- [inteltechniques.com](https://inteltechniques.com)
- [Histoire de l'OSINT : de l'information des espions à la détection des mensonges](https://www.skopenow.com/news/a-history-of-osint)
- [Enquête sur le renseignement à source ouverte : de la stratégie à la mise en œuvre](https://www.researchgate.net/publication/321531302_Open_Source_Intelligence_Investigation_From_Strategy_to_Implementation)
- [Rverse Image Search](https://www.numlookup.com/reverse-image-search)

### **May the Force be with you!**

# Introduction : OSINT civile

Pour commencer, je voudrais dire que je vais considérer l'OSINT comme un ensemble de compétences ou un état d'esprit, car il peut être directement lié au doxing, au GEO-INT militaire réalisé par un employé d'une société de sécurité ou simplement à l'OSINT médiatique réalisé par un employé d'un fonds de capital-risque afin de trouver de nouveaux projets d'investissement, en prenant la théorie des poignées de main comme base...

- [L'OSINT est un état d'esprit](https://medium.com/secjuice/osint-as-a-mindset-7d42ad72113d)
- [Biais cognitifs et pensée critique dans le renseignement à source ouverte (OSINT)](https://deepsec.net/docs/Slides/2014/Cognitive_Bias_and_Critical_Thinking_in_Open_Source_Intelligence_(OSINT)_-_Benjamin_Brown.pdf)
- [Une brève histoire du renseignement à source ouverte](https://www.bellingcat.com/resources/articles/2016/07/14/a-brief-history-of-open-source-intelligence/)
- [Comment l'OSINT a alimenté la plus grande enquête criminelle de l'histoire des États-Unis](https://www.isdglobal.org/digital_dispatches/jan-6-series-how-osint-powered-the-largest-criminal-investigation-in-us-history/)

...Ou même un spécialiste en crypto-forensics enquêtant sur un cas majeur de piratage Web3.0. En d'autres termes, l'OSINT peut être utilisé dans tous les domaines de la vie, car il s'agit uniquement d'une méthode de travail, d'évaluation et de classement de l'information - n'oubliez jamais que nous vivons tous dans l'ère de l'information.

<details>
<summary>Expansion</summary>
<br />

- [Rencontrez les détectives de la blockchain qui traquent les pirates et les escrocs de la crypto-monnaie](https://www.vice.com/en/article/xgd9zw/meet-the-blockchain-detectives-who-track-cryptos-hackers-and-scammers)
- [Compilation spéciale "Blockchain Investigations"](https://t.me/officer_cia/236)
- [Comment j'enquête sur les piratages de crypto-monnaies et les incidents de sécurité : A-Z](https://officercia.mirror.xyz/BFzv17UwH6QG4q711NAljtSiP8eKR17daLjTdmAgbHw)
- [Manuel d'enquêtes sur la chaîne](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List)
- [Le guide du débutant en matière de renseignement de source ouverte (OSINT) : Techniques et outils](https://medium.com/@mohitdeswal_35470/the-beginners-guide-to-open-source-intelligence-osint-techniques-and-tools-6a91b9c37ee1)
- [Awesome Intelligence](https://github.com/ARPSyndicate/awesome-intelligence)

</details>

Tout ce que j'ai dit ci-dessus, vous pouvez le développer en vous-même, mais l'essence de toutes les directions est la même - la capacité à remarquer des informations précieuses, des anomalies, à voir les différences, à analyser soigneusement les faits et à construire une chaîne logique - tout en étant dans le flux d'informations. Commencez par vérifier vos propres informations et vos propres données : faites une recherche OSINT contre vous-même. Recueillez toutes les données, visualisez-les, puis effacez-les en utilisant les techniques SERM/ORM.

- [SERM](https://thebusinessprofessor.com/seo-social-media-direct-marketing/search-engine-reputation-management-definition)
- [ORM](https://medium.com/elfsight-blog/introduction-to-search-engine-reputation-management-serm-44467c891c0b)
- [Exemples d'échecs en matière d'opsec et de protection de la vie privée dans le cadre de l'OSINT](https://www.osintme.com/index.php/2022/01/17/examples-of-opsec-and-privacy-fails-when-doing-osint/)
- [WhatBreach](https://github.com/Ekultek/WhatBreach)
- [Plus d'études sur l'OPSEC](https://github.com/lawsecnet/OPSEC)
- [Conseils et astuces OPSEC de base pour les chercheurs OSINT](https://web.archive.org/web/20221108024236/https://osintcurio.us/2019/04/18/basic-opsec-tips-and-tricks-for-osint-researchers/amp/)
- [Le guide ultime d'Osint Me sur l'OSINT et la vie privée sur Telegram](https://www.osintme.com/index.php/2022/10/18/the-osint-me-ultimate-guide-to-telegram-osint-and-privacy/)
- [Faites-vous plaisir avant que "quelqu'un" ne le fasse](https://osintteam.blog/dork-yourself-before-someone-does-aa49d0c1929f)

J'aimerais vous donner la première leçon, toutes les ressources que je vais vous conseiller - je les ai étudiées moi-même auparavant :

- [So You Think You Can Google - Workshop With Henk van Ess](https://youtu.be/uyqXS5lL-mc)
- [OSINT Origins #1 - Jean-Marc Manach/@manhack](https://youtu.be/XrTFzZ77eEI)
- [Une carte mentale OSINT géniale](http://files.mtg-bi.com/MindMap.jpg)
- [Meilleures pratiques de sécurité pour Telegram et Discord](https://officercia.mirror.xyz/dlf6ZEXq3FLE21ZY2jeJ0cBDyuZu8XIF9DEJAQ07nk8)
- [Un guide définitif pour générer des noms d'utilisateur à des fins OSINT](https://github.com/soxoj/username-generation-guide)
- [Résister à la pensée déterministe](https://zephoria.medium.com/resisting-deterministic-thinking-52ef8d78248c)

# La cartographie de l'esprit

Tout d'abord, décomposons le concept de mind-mapping. Il est très important d'enseigner comment trier les informations en fonction de différents critères. Je pense que vous pouvez vous entraîner à trier absolument toutes les informations que vous souhaitez !

- [Mind-map](https://en.wikipedia.org/wiki/Mind_map)
- [De quoi avez-vous besoin pour devenir un OSINTer intermédiaire ? Comment Shodan peut-il contribuer aux enquêtes OSINT?](https://podtail.com/en/podcast/osintcurious/episode-51-what-do-you-need-to-become-an-intermedi/)
- [Premiers pas dans la recherche sur les sources ouvertes](https://www.bellingcat.com/resources/2021/11/09/first-steps-to-getting-started-in-open-source-research/)
- [Tout sur l'Open Source Intelligence et les enquêtes OSINT](https://www.maltego.com/blog/what-is-open-source-intelligence-and-how-to-conduct-osint-investigations/)

**[Qu'est-ce que Maltego et pourquoi l'utiliser pour l'OSINT ?](https://wondersmithrae.medium.com/a-beginners-guide-to-osint-investigation-with-maltego-6b195f7245cc)** Maltego est un outil d'exploration de données qui exploite une variété de ressources de données open-source et utilise ces données pour créer des graphiques permettant d'analyser les connexions. Les graphiques vous permettent d'établir facilement des liens entre des informations telles que le nom, la structure organisationnelle du courrier électronique, les domaines, les documents, etc. Maltego utilise Java et peut donc fonctionner sous Windows, Mac et Linux. Il est disponible dans de nombreuses distributions Linux OSINT comme Buscador ou Kali. 

En gros, il analyse une grande quantité d'informations et effectue des recherches sur divers sites web à source ouverte pour vous, puis produit un joli graphique qui vous aidera à rassembler les pièces du puzzle. Maltego peut être utilisé comme ressource à tout moment de l'enquête, mais si votre cible est un domaine, il est logique de commencer à cartographier le réseau avec Maltego dès le début.

#### Tout le monde n'a pas fait des antisèches à l'école ? Il est temps de le faire à nouveau, car à l'avenir, cela devrait évoluer vers une compétence Maltego !

- [Top OSINT & Infosec Resources for You and Your Team (2022 Edition) : 100+ Blogs, Podcasts, YouTube, Livres, et plus !](https://www.maltego.com/blog/top-osint-infosec-resources-for-you-and-your-team/)
- [Guide du débutant pour l'investigation OSINT avec Maltego](https://wondersmithrae.medium.com/a-beginners-guide-to-osint-investigation-with-maltego-6b195f7245cc)
- [Maltego - Cyber Weapons Lab - Research like an OSINT Analyst](https://youtu.be/46st98FUf8s)
- [Badges numériques gratuits pour l'apprentissage / le développement des compétences OSINT](https://www.reddit.com/r/OSINT/comments/kgew5d/free_digital_badges_for_learning_developing_osint/)
- [Conseils pour encourager votre enfant à participer à des activités extrascolaires](https://talentgum.com/blog/tips-to-encourage-your-child-to-participate-in-extracurricular-activities)
- [Quelles sont les compétences nécessaires pour être bon aux échecs et comment les améliorer](https://skillspointer.com/skills-for-chess/)

> Un petit conseil : effectuez des [recherches puissantes](https://www.edx.org/course/power-searching-with-google) en utilisant différentes IP, sur différentes périodes et via différents [moteurs de recherche](https://github.com/tasos-py/Search-Engines-Scraper).

## Comprendre les principes fondamentaux de l'OSINT, selon [VEEXH](https://wondersmithrae.medium.com/a-beginners-guide-to-osint-investigation-with-maltego-6b195f7245cc) :

- a. Comprendre le concept d'OSINT et son importance dans la collecte de renseignements.
- b. Se familiariser avec les types de sources OSINT (par exemple, les médias sociaux, les archives publiques, les forums en ligne, les organes d'information).
- c. Apprendre les considérations éthiques et juridiques à prendre en compte lors de la collecte d'OSINT.

**Développement des compétences techniques:**

- a. Acquérir des compétences dans l'utilisation de base d'un ordinateur et d'Internet.
- b. Apprendre les techniques de recherche avancées en utilisant les moteurs de recherche et les opérateurs.
- c. Comprendre l'importance de l'anonymat et acquérir des compétences dans l'utilisation des VPN, des proxys et du réseau Tor.
- d. Se familiariser avec les outils OSINT essentiels, tels que Maltego, Shodan et Google Dorks.

**Maîtrise de la collecte de données OSINT:**

- a. Apprendre à identifier et à hiérarchiser les besoins en matière de renseignement.
- b. Développer une approche systématique de la collecte de données à partir de différentes sources.
- c. Perfectionner ses compétences en ingénierie sociale, en reconnaissance passive et en reconnaissance en ligne.
- d. Acquérir une expertise en matière de géolocalisation, d'analyse d'images et de recherche d'informations sur des individus et des organisations.

**Analyse et évaluation de l'OSINT**

- a. Apprendre diverses techniques d'analyse, telles que l'analyse des liens, l'analyse de la chronologie et l'analyse des sentiments.
- b. Développer la pensée critique et la conscience des biais cognitifs.
- c. Comprendre l'importance du cycle du renseignement et l'appliquer à l'analyse OSINT.
- d. Évaluer la crédibilité et la fiabilité des sources et des informations.

**Diffusion de l'OSINT et établissement de rapports:**

- a. Se familiariser avec les principes d'une communication efficace.
- b. Apprendre à créer des rapports de renseignement, des briefs et des visualisations.
- c. Comprendre l'importance d'adapter vos rapports à différents publics.
- d. Développer la capacité à présenter les résultats d'une manière claire, concise et exploitable.

**Amélioration continue et travail en réseau :** a. Se tenir au courant des dernières nouveautés en matière d'OSR.

- a. Se tenir au courant des dernières tendances, outils et techniques OSINT.
- b. Participer à des communautés en ligne, des forums et des groupes de médias sociaux pertinents.
- c. Participer à des conférences, des ateliers et des webinaires sur l'OSINT.

En suivant ce cadre, les débutants peuvent développer systématiquement leurs compétences OSINT et devenir compétents en matière de collecte, d'analyse et de diffusion de renseignements provenant de sources ouvertes. L'OSINT (Open-source Intelligence) est également une étape cruciale du processus de test de pénétration. 

Un examen approfondi des informations accessibles au public peut augmenter les chances de trouver un système vulnérable, d'obtenir des informations d'identification valides grâce à la pulvérisation de mots de passe ou de prendre pied grâce à l'ingénierie sociale.

# Apprentissage immersif et ludique : Trucs et astuces (a)

Je peux également vous recommander de vous tourner vers une sous-culture intéressante qui convient aux introvertis ! Je suis sûr que tout le monde s'intéresse d'une manière ou d'une autre à divers phénomènes étranges. Plongez dans un environnement de net-stalking ! 

Parfois, des gens ordinaires ont pu résoudre des crimes que la police ne pouvait pas résoudre pendant des années avec OSINT et GEOINT seulement (je pourrais mettre ici des liens vers des subreddits, des films et des nouvelles, mais puisque vous et moi faisons maintenant de l'OSINT, je vous conseille de le trouver par vous-même).

<details>
<summary>Expand</summary>
<br />

- [Qu'est-ce que le Netstalking ?](https://graph.org/What-is-Netstalking-Netstalking-Information-Survivors-04-06)
- [GEOGUESSR](https://somerandomstuff1.wordpress.com/2019/02/08/geoguessr-the-top-tips-tricks-and-techniques/)
- [Calculatrice SunCalc](http://suncalc.net/)
- [Mind Hacks - Profilage psychologique et santé mentale dans les enquêtes OSINT](https://youtu.be/104WpJm_eGk)
- [Méthode d'enseignement de l'Open Source Intelligence (OSINT) à l'aide d'exercices personnalisés basés sur le cloud](https://www.researchgate.net/publication/340023320_A_Method_for_Teaching_Open_Source_Intelligence_OSINT_Using_Personalised_Cloud-based_Exercises)
- [Méthode de simulation d'attaques: exemple](https://istrosec.com/service/attack-simulations/)

</details>

**Vérifiez aussi:**

- [Jeu de réalité alternative](http://en.wikipedia.org/wiki/Alternate_reality_game)
- [reddit.com/r/ARG](http://reddit.com/r/ARG)
- [Net.art](https://officercia.mirror.xyz/VD9IDI8b4jVBHbr5uaGcI_ev6NEKZUuuOhL9IpEfpZs)
- [Méthodes de recherche en anthropologie appliquée](https://en.wikipedia.org/wiki/Applied_Anthropology_Research_Methods)
- [Réflexions pour devenir un anthropologue appliqué](https://www.jstor.org/stable/25605413)
- [Anthropologie appliquée (vraiment, étudiez-la !)](https://oxfordre.com/anthropology/browse;jsessionid=469E22D5E27E148C59A31BA5715AD18D?page=3&pageSize=20&sort=titlesort&subSite=anthropology&t0=ORE_ANT%3AREFANT001)

L'essentiel à retenir, c'est votre santé, c'est avant tout de ne pas laisser vos principes être ébranlés par ce que vous voyez. Vous êtes un observateur ! Voilà qui aide bien à comprendre la psychologie des [chercheurs SCP](https://scp-wiki.wikidot.com/) (quand rien n'est clair, mais que la méthode scientifique aide à remettre chaque chose à sa place).

<details>
<summary>Expansion</summary>
<br />

- [Netstalking : In-Depth](https://graph.org/What-is-Netstalking-Netstalking-Information-Survivors-04-06)
- [Comment j'ai trouvé les premiers développeurs de l'écosystème Solana en utilisant des tactiques OSINT](https://telegra.ph/How-I-found-early-Solana-ecosystem-Developers-using-OSINT-tactics-01-04)
- [Le guide de l'auto-stoppeur sur l'anonymat en ligne](https://web.archive.org/web/20220302223645/https://anonymousplanet.org/guide.html)
- [Recherches OpSec et terminaux de données - les contributions sont les bienvenues](https://github.com/OffcierCia/Crypto-OpSec-SelfGuard-RoadMap)
- [Faites-vous plaisir avant que quelqu'un d'autre ne le fasse !](https://yvesei.medium.com/dork-yourself-before-someone-does-aa49d0c1929f)

</details>

Gardez à l'esprit que dans cette partie de l'Internet mondial (je parle de l'OSINT en général, pas seulement du Net-stalking), le pourcentage de personnes qui recherchent activement des problèmes ou qui ont besoin d'exprimer leurs émotions n'est pas différent de celui des autres endroits !

- [Act like a Lion 🦁](https://twitter.com/jpurd17/status/1648669362910552067?s=20)
- [obsidian.md OSINT Templates](https://github.com/WebBreacher/obsidian-osint-templates)
- [OSINT Browser Extensions](https://github.com/cqcore/OSINT-Browser-Extensions)

**Science + OSINT:**

- [L'esprit à la loupe : Profilage psychologique grâce à l'IA et aux grands modèles de langage](https://www.linkedin.com/pulse/peering-mind-psychological-profiling-through-ai-large-smith)
- [Le rasoir d'Occam](https://www.britannica.com/topic/Occams-razor)
- [Comment fonctionne le rasoir d'Occam](https://science.howstuffworks.com/innovation/scientific-experiments/occams-razor.htm)
- [Le rasoir d'Occam en tant que principe scientifique](https://study.com/learn/lesson/occams-razor-scientific-principle.html#:~:text=Le%20Razor%20d'Occam%20est%20un%20principe%20qui%20déclare%20que%20la%pluralité%20devrait%20être%20utilisée%20un%20peu%20plus%20solidement.)
- [ÉTUDE DE CAS : Profilage de la personnalité et puissance de l'OSINT](https://brightplanet.com/2016/11/09/case-study-receptiviti-power-osint/)
- [Une plateforme de renseignement sur les menaces enrichie pour améliorer les capacités de corrélation, d'analyse, de visualisation et de partage de l'OSINT](https://www.sciencedirect.com/science/article/abs/pii/S2214212620308589)
- ['Déduction' vs 'Induction' vs 'Abduction'](https://www.merriam-webster.com/words-at-play/deduction-vs-induction-vs-abduction)
- [La différence entre le raisonnement déductif et le raisonnement inductif](https://danielmiessler.com/p/the-difference-between-deductive-and-inductive-reasoning/)
- [Rhétorique de l'induction](https://www.studysmarter.co.uk/explanations/english/rhetoric/induction-rhetoric/)
- [Raisonnement déductif et inductif : définition, différences et exemples](https://mundanopedia.com/economics/microeconomics/deductive-and-inductive-reasoning-methods/)

**Pratiquer:**

> Suivez donc les règles de l'OpSec et ne faites pas trop d'erreurs. Menez vos activités à partir d'un appareil séparé et isolé.

- [Préoccupations en matière de protection de la vie privée et facteurs d'acceptation de l'OSINT pour la cybersécurité : A Representative Survey](https://petsymposium.org/popets/2023/popets-2023-0028.pdf)
- [Qu'est-ce qu'une heuristique ?](https://www.verywellmind.com/what-is-a-heuristic-2795235)
- [Call of PSYOPS](https://steemit.com/news/@rusticus/call-of-psyops-video-games-as-psychological-warfare-in-the-21st-century)
- [Tendances OSINT pour 2023 et au-delà](https://blog.sociallinks.io/osint-trends-for-2023-and-beyond/)
- [Les multiples utilisations de l'OSINT dans le renseignement militaire](https://blog.sociallinks.io/uses-of-osint-in-military-intelligence/)
- [Explication des informations accessibles au public (PAI)](https://www.babelstreet.com/blog/pai-explained)
- [Informations accessibles au public : le champ de bataille numérique](https://censa.net/publications/publicly-available-information-the-digital-battlefield/)
- [Meilleure utilisation des informations accessibles au public](https://www.jstor.org/stable/pdf/resrep20002.7.pdf)
- [Pratiques scientifiques : faux positifs et faux négatifs](https://manoa.hawaii.edu/exploringourfluidearth/chemical/matter/properties-matter/practices-science-false-positives-and-false-negatives)
- [Faux positifs et faux négatifs dans la sécurité de l'information](https://www.guardrails.io/blog/false-positives-and-false-negatives-in-information-security/)
- [Minimiser les faux positifs dans vos enquêtes OSINT](https://mediasonar.com/reports/minimize-false-positives-osint-investigations/)

**L'atténuation des biais cognitifs et la prise de décision dans le cadre de l'OSINT:**.

Il n'y a pas de praticiens-analystes parfaits, tout le monde fait des erreurs et se retrouve dans des situations ambiguës difficiles (au moins une fois dans sa vie), d'autant plus dans des conditions de surcharge de travail aiguë et chronique. Et il est absolument nécessaire pour un praticien-analyste de connaître et de comprendre ces situations. 

Les vulnérabilités cognitives (dans l'acception établie) sont des expositions et/ou des tendances à des défauts de pensée : distorsions cognitives significatives, croyances erronées, préjugés cognitifs (biais) ou schémas de pensée stéréotypés qui créent la base de la prédisposition d'une personne à des échecs cognitifs et conduisent à des distorsions et des dysfonctionnements des [processus de pensée](https://telegra.ph/Cognitive-vulnerabilities-of-the-practitioner-analyst-04-17).

- [Vulnérabilités cognitives du praticien-analyste](https://telegra.ph/Cognitive-vulnerabilities-of-the-practitioner-analyst-04-17)
- [Atténuation des biais cognitifs](https://www.researchgate.net/publication/317702457_Cognitive_Bias_Mitigation)
- [Atténuation des préjugés cognitifs - Wiki](https://en.m.wikipedia.org/wiki/Cognitive_bias_mitigation)
- [Reconnaître et atténuer les biais cognitifs : une menace pour l'objectivité](https://www.theiia.org/en/content/communications/press-releases/2022/may/new-recognizing-and-mitigating-cognitive-biases-a-threat-to-objectivity/)
- [Atténuation des biais cognitifs : comment rendre la prise de décision rationnelle ?](https://ideas.repec.org/p/fau/wpaper/wp2020_01.html)
- [L'impact des biais cognitifs sur la prise de décision des professionnels : A Review of Four Occupational Areas](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8763848/) & [L'impact des biais cognitifs sur la prise de décision des professionnels : un examen de quatre domaines professionnels](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8763848/)
- [HARKing : émettre des hypothèses après que les résultats sont connus](https://pubmed.ncbi.nlm.nih.gov/15647155/)
- [Hypothèses après que les résultats sont connus (HARKing)](https://embassy.science/wiki/Theme:Cc742a7b-826d-4201-b33e-457f2ef79fb9) & [Article](https://www2.psych.ubc.ca/~schaller/528Readings/Kerr1998.pdf)
- [Vulnérabilité cognitive](https://en.m.wikipedia.org/wiki/Cognitive_vulnerability)
- [Pourquoi nous concentrons-nous sur une caractéristique à comparer lorsque nous choisissons entre des alternatives ?](https://thedecisionlab.com/biases/take-the-best-heuristic) & [Plus](https://fourweekmba.com/take-the-best-heuristic/)
- [Le plan de l'IARPA pour pirater le cerveau des pirates](https://fcw.com/security/2023/04/iarpas-plan-hack-brains-hackers/385123/)
- [Les cyberattaquants pensent-ils vite et lentement ?](https://journals.sagepub.com/doi/pdf/10.1177/1071181319631096)
- [DMBOK2](https://www.dama.org/cpages/body-of-knowledge)
- Rapport de la commission américaine - 2005](https://govinfo.library.unt.edu/wmd/about.html)
- [5 biais cognitifs pourraient affecter vos enquêtes OSINT](https://www.linkedin.com/pulse/5-cognitive-biases-could-affect-your-osint-investigations-?utm_source=share&utm_medium=guest_mobile_web&utm_campaign=copy)

La plupart d'entre nous éprouvent des "sentiments instinctifs" inexplicables, comme le fait d'aimer (ou de détester) instantanément une nouvelle propriété lors de la recherche d'un logement ou les jugements rapides que nous portons lorsque nous rencontrons de nouvelles personnes. Aujourd'hui, des chercheurs affirment que ces sentiments (ou intuitions) sont réels et que nous devrions prendre nos intuitions au sérieux. 

Ne vous limitez pas à une seule approche ; n'ayez pas peur de tenter des expériences, mais gardez à l'esprit que les résultats de ces approches doivent toujours être **doublés**. Ils servent davantage d'outils d'apprentissage que de véritables conseils pour les enquêteurs. Visitez les sites web suivants :

- [L'intuition est plus qu'un simple pressentiment, selon une nouvelle étude](https://www.sciencedaily.com/releases/2008/03/080305144210.htm)
- [Intuition as Emergence : Bridging Psychology, Philosophy and Organizational Science](https://www.frontiersin.org/articles/10.3389/fpsyg.2021.787428/full)
- [Analyse du renseignement : méthodes structurées ou intuition ?](https://www.academia.edu/4259879/Intelligence_Analysis_Structured_Methods_or_Intuition)
- [Le potentiel d'intégration de l'intelligence et de l'intuition](https://www.thecipherbrief.com/the-potential-of-integrating-intelligence-and-intuition)
- [Ingénierie sociale et protection des cibles de grande valeur](https://www.hensoldt-analytics.com/2023/01/23/social-engineering-osint/)
- [Tracez mon jeu d'ombres](https://myshadow.org/trace-my-shadow)
- [Ce dont nous parlons lorsque nous parlons d'OSINT](https://www.authentic8.com/blog/definition-of-osint)
- [Informations accessibles au public : le secret des données non classifiées, première partie](https://overthehorizonmdos.wpcomstaging.com/2019/04/08/publicly-available-information-the-secret-to-unclassified-data-part-i/) & [Copie](https://web.archive.org/web/20191117062938/https://othjournal.com/2019/04/08/publicly-available-information-the-secret-to-unclassified-data-part-i/)

**Aussi:**

**Selon [wondersmith_rae](https://wondersmithrae.medium.com/training-yourself-to-be-an-analytical-thinker-476bdb7e7c99)** : Dans la rhétorique classique, les "éléments de circonstance" créés par Aristote ont été utilisés pour analyser les questions rhétoriques depuis des lustres. Ils s'appliquent également à l'analyse moderne et peuvent servir de base à une enquête. **(Qui, quoi, quand, où, pourquoi, de quelle manière, par quels moyens)**.

Une version condensée, mais tout aussi précieuse, de ces éléments est appelée "5W's and an H" (qui, quoi, quand, où, pourquoi et comment). Ces questions sont utilisées en rhétorique, dans les études religieuses, dans les enquêtes policières, dans le journalisme et par les avocats depuis la Grèce antique. On dit qu'une enquête ne peut pas être vraiment complète tant que l'on n'a pas répondu à tous les "W" et à tous les "H". 

En appliquant les mêmes éléments à nos enquêtes OSINT, nous pouvons poser des questions similaires et y répondre. En répondant aux 5W, un récit commence à émerger des données collectées. Il nous appartient maintenant, en tant qu'analystes, de relier les points de manière succincte. Le problème, c'est que tous ceux qui ont fait de la recherche savent que lorsque des informations commencent à être découvertes, il est facile de s'enfoncer dans un trou de lapin. 

- [Le pouvoir d'arrêter vos sens : Comment stimuler votre créativité et avoir l'esprit clair](https://buffer.com/resources/the-power-of-shutting-down-your-senses-how-to-boost-your-creativity-and-have-a-clear-mind/amp/)
- [Entraînez-vous à devenir un penseur analytique](https://wondersmithrae.medium.com/training-yourself-to-be-an-analytical-thinker-476bdb7e7c99)
- [Utiliser l'état d'esprit OSINT pour améliorer les enquêtes en ligne](https://www.sans.org/webcasts/atmic-talk-osint-mind-state-online-investigations-114115/)
- [Dernières tendances en matière de SOCMINT, OSINT et cyberpsychologie](https://www.toddington.com/wp-content/uploads/1Day_OSINT_Masterclass-1-1.pdf)
- [5 biais cognitifs qui pourraient affecter vos enquêtes OSINT](https://www.liferaftinc.com/blog/5-cognitive-biases-that-could-affect-your-osint-investigations)
- [Citoyens analystes OSINT : Motivations des volontaires du renseignement à source ouverte](https://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1670900&dswid=-6049)
- [Nouveau guide sur l'investigation et la cartographie des auteurs dans les enquêtes sur les sources ouvertes](https://piac.asn.au/2023/03/29/new-guide-on-investigating-and-mapping-perpetrators-in-open-source-investigations/)
- [Un homme d'affaires étranger est mort et m'a laissé 4,6 millions de dollars, j'ai donc utilisé l'OSINT et l'ingénierie sociale pour escroquer un escroc](https://hatless1der.com/an-overseas-businessman-died-and-left-me-4-6m-so-i-used-osint-social-engineering-to-scam-a-scammer/)
- [Cchatgpt-unlock-geolocation-data](https://www.digitaldigging.org/p/4-chatgpt-unlock-geolocation-data)
- [Telegram-osint-vm-part-2](https://www.cqcore.uk/telegram-osint-vm-part-2/)
- [Studies in Intelligence](https://t.me/devil_may_spy/160)
- [Safeguarding OSINTers : Shielding Against Disinformation Manipulation (Sauvegarde des spécialistes du renseignement opérationnel : protection contre la manipulation de la désinformation)](https://osintteam.blog/safeguarding-osinters-shielding-against-disinformation-manipulation-dfbbfbf1db08)
- [Dévoiler le détective numérique : Essential OSINT Tools and Techniques for Investigators](https://osintteam.blog/unveiling-the-digital-detective-essential-osint-tools-and-techniques-for-investigators-adf486ad2ccd)

Une fois que vous êtes en mesure de distinguer les informations, de les trier, la prochaine chose à faire est de vous entraîner. Comme vous le savez, **une bonne pratique nécessite une bonne motivation** ! Il vous suffit de savoir une chose : les gens pensent que l'intelligence est fixe - mais ce n'est pas le cas. Votre cerveau est comme un muscle ; plus vous l'utilisez, plus il se développe. L'éducation n'est plus un événement ponctuel, mais une expérience qui dure toute la vie.

<details>
<summary>Expansion</summary>
<br />

- [Guide de terrain pour les débutants : où et comment apprendre l'OSINT](https://medium.com/the-sleuth-sheet/beginners-field-guide-where-how-to-learn-osint-bd2e11469f31)
- [Pièges utilisés par les cyberdétectives...](https://medium.com/@ibederov_fr/traps-used-by-cyber-detectives-c778b4853f1a)
- [Enquête sur les adresses MAC](https://t.me/ibederov_en/18)
- [Le guide ULTIME de la rédaction de rapports de renseignement...](https://www.intelligence101.com/the-ultimate-guide-to-writing-intelligence-reports-complete-with-templates-examples/)
- [Ressources pour la résilience des entreprises](https://start.me/p/wMgzM5/business-resilience)
- [Le flux de travail d'une enquête OSINT sur une personne du point de vue de la protection de la vie privée](https://www.osintme.com/index.php/2022/08/31/person-osint-investigation-workflow-from-a-privacy-perspective/)
- [Setting Your Moral Compass : A Workbook for Applied Ethics in OSINT](https://ethicaljournalismnetwork.org/setting-your-moral-compass-a-workbook-for-applied-ethics-in-osint)
- [Reddit Bureau of Investigation](https://www.reddit.com/r/RBI/)
- [Les arts sombres de l'OSINT](https://av.tib.eu/en/media/38959)
- [Wiki OSINT](https://www.reddit.com/r/OSINT/wiki/index/)
- [Carte de l'OSINT](https://cipher387.github.io/osintmap)

</details>

**Vérifiez aussi:**

> [De récentes études montrent](https://4discovery.com/2019/09/10/litigating-in-an-e-world-e-discovery-forensics-and-open-source-intelligence-in-legal-research/) que plus de 97 % des entreprises stockent des données dans le nuage. Apprenez à identifier les sources potentielles de données dans le nuage, à émettre des demandes de découverte et à mettre en œuvre des mises en suspens en cas de litige, ainsi qu'à préserver, collecter, filtrer, examiner et produire des données dans le nuage.

> Les [informations pertinentes](https://4discovery.com/2019/09/10/litigating-in-an-e-world-e-discovery-forensics-and-open-source-intelligence-in-legal-research/) pour votre affaire se trouvent sur Internet, généralement à l'abri des regards. Les documents commerciaux, les enregistrements de noms de domaine, les sites web, les identités d'utilisateurs en ligne, les messages sur les médias sociaux, les photos et les vidéos ne sont qu'à une requête de recherche. Savez-vous comment les trouver ? Apprenez comment les informations de source ouverte peuvent avoir un impact sur un large éventail de sujets et comment identifier efficacement les sources d'information et rechercher des données de source ouverte.

- [Le langage des criminels du point de vue de la psycholinguistique](https://www.paperdue.com/essay/criminals-language-from-a-psycholinguistics-1851)
- [UTILISATION DE L'ANALYSE DU LANGAGE POUR L'IDENTIFICATION ET L'ÉVALUATION DES DÉLINQUANTS](https://www.researchgate.net/publication/340985509_FORENSIC_PSYCHOLINGUISTICS_USING_LANGUAGE_ANALYSIS_FOR_IDENTIFYING_AND_ASSESSING_OFFENDERS)
- [Psycholinguistique médico-légale : l'analyse du langage pour l'identification et l'évaluation](https://criminalprofiling.com/forensic-psycholinguistics-using-language-analysis-for-identifying-and-assessing/)
- [Le guide ultime du renseignement humain (HUMINT)](https://www.intelligence101.com/the-ultimate-guide-to-human-intelligence-humint/)
- [Saper l'ingénierie sociale à l'aide de la collecte de renseignements en source ouverte](https://www.researchgate.net/publication/283250856_Undermining_social_engineering_using_open_source_intelligence_gathering)
- [Signal OSINT - SIGINT](https://worldwidescience.org/topicpages/o/osint+signals+intelligence.html)
- [E-Discovery, Forensics, and Open Source Intelligence in Legal Research](https://4discovery.com/2019/09/10/litigating-in-an-e-world-e-discovery-forensics-and-open-source-intelligence-in-legal-research/)
- [De la dissidence à l'OSINT ? Comprendre, influencer et protéger les rôles, la réputation et les revenus](https://complexdiscovery.com/from-dissent-to-osint-understanding-influencing-and-protecting-roles-reputation-and-revenue/)
- [L'essentiel : qu'est-ce que l'administration de la preuve électronique ?](https://cdslegal.com/knowledge/the-basics-what-is-e-discovery/)
- [Système d'organisation, de collecte et de présentation de renseignements provenant de sources ouvertes](https://link.springer.com/article/10.1007/s42488-022-00068-4)

# Formation et pratique

**Bon matériel de formation:**

- [Python pour OSINT 21 jours](https://github.com/cipher387/python-for-OSINT-21-days)
- [Googledorking](https://tryhackme.com/room/googledorking) + [dorksearch.com](https://dorksearch.com/)
- [Searchlightosint](https://tryhackme.com/room/searchlightosint)
- [Shodan](https://tryhackme.com/room/shodan)
- [Geolocatingimages](https://tryhackme.com/room/geolocatingimages)
- [Instruments-sur-les-ondes](https://telegra.ph/Instruments-on-the-radio-waves-02-01) + [websdr.org](https://websdr.org) + [try 😅](http://websdr.ewi.utwente.nl:8901/?tune=4625)
- [Somesint](https://tryhackme.com/room/somesint)
- [osintframework.com](https://osintframework.com)
- [OSINT At Home YouTube Playlist](https://www.youtube.com/playlist?list=PLrFPX1Vfqk3ehZKSFeb9pVIHqxqrNW8Sy)
- [myosint.training](https://www.myosint.training/)
- [Compétences cybernétiques géniales](https://github.com/joe-shenouda/awesome-cyber-skills)
- [Cartes géniales](https://github.com/simsieg/awesome-maps)

Voici un très bon jeu d'étirement du cerveau qui permet d'entraîner la pensée associative - une compétence très importante pour toute personne travaillant dans le domaine de l'[OSINT](https://twitter.com/hashtag/OSINT?src=hashtag_click):

- [Wikipedia:Wiki Game](https://en.wikipedia.org/wiki/Wikipedia:Wiki_Game)

Quand j'étais jeune, nous jouions à "5 steps till Ragnarok" - le but était de trouver la page sur ce mythe en 5 étapes (5 clics) à partir de n'importe quelle page Wikipedia au hasard ! 🙂 **Suivez les spécialistes de l'OSINT:Wikipedia:Wiki Game

**Suivez les meilleurs spécialistes de l'OSINT:**

- [twitter.com/UKOSINT](https://twitter.com/UKOSINT) - nouvelles, outils, blagues
- [twitter.com/dutch_osintguy](https://twitter.com/dutch_osintguy) - spécialiste célèbre, conférencier
- [twitter.com/jakecreps](https://twitter.com/jakecreps) - publie des outils géniaux tous les jeudis
- [twitter.com/OSINTtechniques](https://twitter.com/OSINTtechniques) - suit les miettes de pain numérique
- [The Sleuth Sheet](https://medium.com/the-sleuth-sheet)
- [OSINT Essentials](https://osintessentials.medium.com/)
- [Sector035](https://medium.com/@sector035) - Semaine de l'OSINT
- [Igor S. Bederov](https://medium.com/@ibederov_en) - Sherlock Holmes de l'ère numérique...
- [twitter.com/OSINTHK](https://twitter.com/OSINTHK) - Des bénévoles qui utilisent l'OSINT
- [Une communauté OSINT mondiale](https://osintfr.com/en/home/) - Communauté OSINT en France
- [twitter.com/OSINT_Research](https://twitter.com/OSINT_Research) - outils et données impressionnantes
- [twitter.com/OSINTtechniques](https://twitter.com/OSINTtechniques) - outils et données géniales
- [twitter.com/OsintJobs](https://twitter.com/OsintJobs) - emplois dans le domaine de l'OSINT
- [www.reddit.com/r/OSINT](https://www.reddit.com/r/OSINT) - le plus grand subReddit thématique
- [Chaînes sur l'OSINT, le piratage, la sécurité, etc.](https://telegra.ph/Channels-about-OSINT-Hacking-Security-and-so-on-04-19)

**Plus de ressources:**

> [Outre sa fonction traditionnelle qui consiste à permettre de prendre des décisions moins erronées,](https://www.researchgate.net/publication/331073990_Digital_Open_Source_Intelligence_and_International_Security_A_Primer) le public des services de renseignement modernes ne se limite plus aux dirigeants des États ou des entreprises, mais s'étend au grand public. Il ne s'agit plus d'un simple mécanisme d'alerte, mais aussi d'un réservoir de savoir-faire et d'un bassin d'improvisation pour résoudre les problèmes en cas de crise inattendue.
 
- [Awesome OSINT + Crypto](https://github.com/aaarghhh/awesome_osint_criypto_web3_stuff)
- [Google Hacking](https://seckrd.com/google-hacking)
- [GOSI : GIAC Open Source Intelligence](https://www.giac.org/certification/open-source-intelligence-gosi)
- [SEC487 : Collecte et analyse de renseignements à source ouverte (OSINT)](https://www.sans.org/cyber-security-courses/open-source-intelligence-gathering/)
- [Inteltechniques.net](https://www.inteltechniques.net/)
- [Conférence sur la sécurité informatique](https://github.com/bkimminich/it-security-lecture/)
- [Outil r4ven](https://github.com/spyboy-productions/r4ven)
- [Unredacter](https://github.com/BishopFox/unredacter)
- [forensicdots.de](https://www.forensicdots.de/)
- [Meta-secret App](https://github.com/meta-secret)
- [Image Research OSINT](https://github.com/cqcore/Image-Research-OSINT)
- [15 outils que vous devez connaître en tant qu'analyste de sécurité](https://osintteam.blog/15-tools-you-should-know-as-a-security-analyst-f95007e94d99)
- [Portable Secret App](https://mprimi.github.io/portable-secret/)
- [Techniques de renseignement en source ouverte](https://inteltechniques.com/book1.html)
- [The Internet Intelligence & Investigation Handbook](https://www.amazon.com/Internet-Intelligence-Investigation-Handbook-practical/dp/B096TJMV7J)
- [Manuel OSINT de l'OTAN](https://github.com/lawsecnet/OPSEC/blob/master/NATO%20OSINT%20Handbook%20v1.2%20-%20Jan%202002.pdf)
- [osintnewsletter.com](https://osintnewsletter.com/)
- [Geolocation OSINT](https://github.com/cqcore/Geolocation-OSINT)
- [geodetective.io](https://geodetective.io/)
- [Encore un livre OSINT génial](https://t.me/osintkanal/2049)
- [Social Media OSINT](https://github.com/cqcore/Social-Media-OSINT)
- [Moteurs de recherche fascinants qui recherchent des visages](https://www.makeuseof.com/tag/3-fascinating-search-engines-search-faces/)
- [Méga liste d'outils OSINT](https://pastebin.com/z0FUgiGb)
- [L'avenir de l'OSINT : la recherche de personnes avec ChatGPT](https://dorksearch.com/blog/future-of-osint-people-searching/)
- [Géolocalisation : au parc de vente au détail](https://nixintel.info/osint/geolocation-at-the-retail-park/)

**Outils (IA, ChatGPT, ML, autres):**

> [Ces dernières années, l'intérêt du public pour la collecte et l'analyse de renseignements à partir de sources ouvertes](https://www.sans.org/webcasts/atmic-talk-osint-mind-state-online-investigations-114115/) a augmenté de façon exponentielle. Au fur et à mesure que cet intérêt grandit, de plus en plus d'enquêtes OSINT s'appuient sur des outils et l'automatisation, laissant de côté le processus d'analyse. Vous devriez considérer l'OSINT comme un processus de pensée. L'état d'esprit OSINT est essentiel pour suivre les étapes de l'enquête, choisir les bons outils et les bonnes sources, analyser les données et établir des rapports afin de générer des renseignements exploitables !

- [Carte des outils OSINT](https://metaosint.github.io/chart)
- [Sherlock](https://github.com/sherlock-project/sherlock)
- [gpt.censys.io](https://gpt.censys.io/)
- [ChatGeoPT](https://github.com/earth-genome/ChatGeoPT)
- [ChatGPT pour OSINT : Exemple](https://t.me/osintkanal/2009) | Astuce : Utiliser [deepl.com](https://www.deepl.com/translator)
- [Emoji OSINT](https://www.dutchosintguy.com/post/cryptography-osint-can-you-read-emoji)
- [Advangle](http://advangle.com/)
- [searchcode.com](https://searchcode.com/)
- [dorkgpt.com](https://www.dorkgpt.com/)
- [OSINT & ChatGPT : 103 idées](https://t.me/irozysk/9377)
- [OSINT + AI](https://github.com/jiep/offensive-ai-compilation)
- [OSINT - SAN](https://github.com/Bafomet666/OSINT-SAN)
- [OSINT Buddy](https://github.com/jerlendds/osintbuddy)
- [ChatGPT : L'arme secrète de l'IA pour l'OSINT](https://blog.gopenai.com/chatgpt-the-ai-powered-secret-weapon-for-osint-133a68d8302e)
- [Ne traitez pas un outil comme une bulle d'argent pour toutes les tâches !](https://osintessentials.medium.com/the-one-osint-tool-you-must-have-to-supercharge-your-investigations-94f5015b6318)
- [Le nouveau code secret de l'OSINT : ChatGPT](https://medium.com/the-sleuth-sheet/the-new-osint-cheat-code-chatgpt-cd54c190fa11)
- [Exploiter la puissance de ChatGPT pour l'OSINT : un guide pratique pour votre assistant IA OSINT](https://hackernoon.com/harnessing-the-power-of-chatgpt-for-osint-a-practical-guide-to-your-ai-osint-assistant)
- [Génial ChatGPT gratuit](https://github.com/LiLittleCat/awesome-free-chatgpt)
- [IA offensive](https://github.com/jiep/offensive-ai-compilation)
- [Manuel d'enquête sur le Bitcoin AML](https://www.amazon.com/Bitcoin-Investigation-Manual-AML-Money-Laundering/dp/1077484070)

# Choisir une voie à suivre...

Certains aimeront [analyser des images](https://29a.ch/photo-forensics/#forensic-magnifier), [des images satellites](https://spectator.earth/), calculer l'heure et le lieu à partir de [l'angle des ombres d'une photo](https://www.suncalc.org/#/40.1789,-3.5156,3/2022.05.05/12:15/1/3), ou mesurer la [taille des sommets des montagnes](https://www.peakfinder.org/) afin de mener des enquêtes de détective privé. Ou, disons, faire de l'OSINT en cryptographie, par exemple, auquel cas votre motivation sera l'argent et l'accomplissement personnel... Ou encore [rechercher des histoires rares](https://www.atlasobscura.com/articles/buying-volcanoes-robert-ripley-paricutin-whakaari.amp) !

[Lisez ma chaîne si vous aimez ce sujet](https://t.me/officer_cia)... Ou encore [AD-INT](https://medium.com/@ibederov_fr/mac-address-osint-e539504ae925) qui se développe de jour en jour en ce moment. Pour la formation en GEOINT, je suggère de consulter [geoguessr.com](https://geoguessr.com/) et [whereami.io](https://whereami.io/).

**Jetez un coup d'œil à cette impressionnante Mind-Map:**.

- [Cliquez sur moi !](http://files.mtg-bi.com/MindMap.jpg)

**Explorer les terminaux de données:**

- [Open-Source Intelligence (OSINT) Reconnaissance](https://z3r0trust.medium.com/open-source-intelligence-osint-reconnaissance-9f0bafd672b2)
- [Une collection de plusieurs centaines d'outils en ligne pour l'OSINT](https://github.com/cipher387/osint_stuff_tool_collection)
- [Cette page est destinée à tous ceux qui aiment les enquêtes sur les logiciels libres](https://start.me/p/DPYPMz/the-ultimate-osint-collection)
- [Start.me + OSINT](https://start.me/p/Pwy0X4/osint-inception)
- [Open-Source Intelligence (OSINT) in 5 Hours - Full Course - Learn OSINT !](https://youtu.be/qwA6MmbeGNo)
- [Suivez !](https://twitter.com/Sector035)
- [myosint.training/courses/](https://myosint.training/courses/)
- [Comparaison des outils OSINT de Typosquatting comme DNSTwist, DNSRazzle avec la surveillance du Typosquatting de Bolster](https://securityboulevard.com/2022/02/comparing-osint-typosquatting-tools-like-dnstwist-dnsrazzle-against-bolsters-typosquatting-monitoring/)
- [* C'est quoi cette police ?](https://osintessentials.medium.com/wtf-be0de2230ed2)
- [OSINT Cheatsheet](https://thekaiz3n.com/cheatsheet/2022/01/12/osint.html)
- [L'application de l'inférence abductive et rétroductive pour la conception et l'analyse de la recherche sociologique axée sur la théorie](https://journals.sagepub.com/doi/10.5153/sro.2819)
- [L'abduction en tant qu'aspect de la rétroduction](http://www.commens.org/encyclopedia/article/chiasson-phyllis-abduction-aspect-retroduction)
- [L'abduction en tant qu'aspect de la rétroduction - 2](https://www.degruyter.com/document/doi/10.1515/semi.2005.2005.153-1-4.223/html?lang=en)
- [Raisonnement abductif](https://en.wikipedia.org/wiki/Abductive_reasoning)

Vous pouvez même vouloir désanonymiser les utilisateurs de Telegram ([lire ce canal](https://t.me/ibederov_en)) ou, à l'inverse, rejoindre les frères [counter-OSINT](https://github.com/soxoj/counter-osint-guide-en). Mais ce faisant, je vous invite à ne pas oublier les compétences clés que sont la recherche d'information, l'analyse de l'information et l'application de l'information...

<details>
<summary>Expansion</summary>
<br />

- [Guide du contre-espionnage (Counter OSINT)](https://github.com/soxoj/counter-osint-guide-en)
- [HUMINT VS Social Engineering Resources](https://telegra.ph/HUMINT-VS-Social-Engineering-Resources-03-24)
- [De l'oubli à l'illumination. Partie 1 | Sur la ligne de la créativité et de la défense](https://mirror.xyz/0xc34B1730BA53abD717a1E57A358F39C046053581/Ra_UVvUwOrO5W56k2QpP4jKhYAGMhsNnfvwrdKWQ1EI)
- [Comment apprendre n'importe quoi](https://twitter.com/sahilbloom/status/1662453471608446976)

</details>

Je vais vous donner quelques conseils de base : évaluez les informations en fonction de différents critères, connaissez toujours vos "paramètres de base" - c'est bon pour la santé mentale, les choses que vous trouvez ne doivent pas ruiner vos fondations ! Mettez-le en pratique, faites-le dans votre vie quotidienne, appliquez l'OSINT là où cela ne semble pas évident, comme indiqué ci-dessous:

- [5 façons dont l'OSINT peut aider votre carrière - Knowmad OSINT](https://knowmad-osint.com/5-ways-osint-can-help-your-career/)
- [Population d'ontologies pour le renseignement à source ouverte](https://ceur-ws.org/Vol-2161/paper27.pdf)
- [Cryptographie et OSINT - Les principes fondamentaux](https://www.dutchosintguy.com/post/cryptography-osint-the-fundamentals)
- [Utiliser des caractères de largeur nulle pour cacher des messages secrets dans du texte (et même révéler des fuites)](https://null-byte.wonderhowto.com/how-to/use-zero-width-characters-hide-secret-messages-text-even-reveal-leaks-0198692/)
- [OSINT : outil de recherche de nom d'utilisateur](https://www.secjuice.com/osint-username-search-tool/)
- [Rédaction du défi de géolocalisation](https://osintteam.blog/geolocation-challenge-writeup-1cd5d5aa299f)
- [Tout sur le Web Recon et l'OSINT](https://github.com/pr0xh4ck/web-recon)
- [Outil PainlessPeek - GEOINT](https://github.com/adacable/painlessPeek)
- [Outil ChatGPT-osint](https://github.com/gigz/gpt-osint)
- [Querytool](https://github.com/oryon-osint/querytool)

# Apprentissage immersif et gamifié : Jeux (b)

Rejoignez des communautés, bien sûr, et discutez, discutez ! Ci-dessous, je n'ai mentionné que les communautés anglophones, mais il y en a aussi des locales, faites des recherches par vous-même. Je suis 100% sûr de vous ! Vous réussirez ! Vous aimez passer du temps avec vos amis ? Si oui, essayez de jouer à Dozor ou Encounter (ou tout autre NightGame basé sur le décryptage de codes, la géolocalisation, l'escapologie ou le crochetage de serrures) ensemble ! 

- [Jeu de nuit en équipe DozoR](https://en.wikipedia.org/wiki/Dozor)
- [Codebreaking](https://en.m.wikipedia.org/wiki/Codebreaking)
- [GeoCaching](https://en.m.wikipedia.org/wiki/Geocaching)
- [Escapologie](https://en.wikipedia.org/wiki/Escapology)
- [Crochetage de serrures](https://www.art-of-lockpicking.com/how-to-pick-a-lock-guide/)

**Check out:**

- [Ingress](https://www.ingress.com/)
- [Géocaching](https://education.nationalgeographic.org/resource/geocaching/)
- [Escapologie](https://www.escapology.com/en)
- [Meilleur outil de collecte d'informations 🔎](https://github.com/Moham3dRiahi/Th3inspector)
- [Awesome Intelligence](https://github.com/ARPSyndicate/awesome-intelligence)

**OSINT-Games:**

- [kasescenarios.com](https://kasescenarios.com/)
- [Sourcing.games](https://sourcing.games/)
- [Exercice OSINT #018](https://gralhix.com/list-of-osint-exercises/osint-exercise-018/)
- [osint.games](https://www.osint.games/)
- [spyingchallenge.com](http://spyingchallenge.com/)
- [10 solutions CTF OSINT pour débutants](https://geckosint.medium.com/10-beginner-osint-ctf-solutions-ae89e557a4b)
- [Plus de CTF OSINT](https://warnerchad.medium.com/osint-ctfs-9993129c10c7)
- [Liste des défis OSINT - Reddit](https://www.reddit.com/r/OSINT/comments/vu9i43/looking_for_osint_challenges_ctfs/)
- [2 excellents outils de formation OSINT](https://nixintel.info/osint/two-great-osint-training-tools/)
- [Jeux liés à l'OSINT - Reddit](https://www.reddit.com/r/OSINT/comments/i62fhp/osint_related_games/)
- [Les 10 meilleurs jeux basés sur la géolocalisation](https://www.digitaltrends.com/gaming/best-location-based-gps-games/)
- [7 jeux de géolocalisation pour explorer l'extérieur](https://www.samsung.com/uk/explore/entertainment/7-geolocation-games-to-get-you-exploring-the-outdoors/)
- [Jeu de géolocalisation](https://en.wikipedia.org/wiki/Location-based_game)
- [Qu'est-ce qu'une chasse au renard en radioamateur ?](https://hamradioplanet.com/what-is-a-fox-hunt-in-ham-radio/)
- [9 jeux virtuels à jouer lorsque vous ne pouvez pas être ensemble](https://www.realsimple.com/work-life/entertainment/virtual-games)

Étudiez attentivement ces ressources et revenez-y au cours de votre voyage dans le monde des frelons, sans oublier les racines. Cet article ne répond pas aux questions, mais soulève plutôt des questions rhétoriques pour vous inciter à réfléchir !

<details>
<summary>Expansion</summary>
<br />

- [Comprehensive Counter OSINT](https://github.com/soxoj/counter-osint-guide-en)
- [Contre-espionnage](https://github.com/CScorza/OSINTAnonymous)
- [Enquête sur le renseignement à source ouverte : de la stratégie à la mise en œuvre](https://www.researchgate.net/publication/321531302_Open_Source_Intelligence_Investigation_From_Strategy_to_Implementation)
- [Le renseignement à l'ère de l'internet : L'émergence et l'évolution de l'Open Source Intelligence (OSINT)](https://www.sciencedirect.com/science/article/abs/pii/S0747563211002585)
- [Guide du renseignement à source ouverte (OSINT)](https://greydynamics.com/a-guide-to-open-source-intelligence-osint/)
- [Des preuves intelligentes : L'utilisation du renseignement de source ouverte (OSINT) dans les procédures pénales](https://www.researchgate.net/publication/309015913_Intelligent_evidence_Using_open_source_intelligence_OSINT_in_criminal_proceedings)
- [Le cycle du renseignement : générer des renseignements à partir de l'OSINF](https://www.skopenow.com/news/the-intelligence-cycle-creating-osint-from-osinf)

</details>

Comme il s'agit d'un guide atypique, je pense qu'il vaut la peine de vous proposer une liste de séries télévisées et de films qui, selon moi, impliquent l'OSINT d'une manière ou d'une autre :

- [Liste des films OSINT](https://www.aware-online.com/en/osint-films/)
- [SEARCHING](https://youtu.be/3Ro9ebQxEOY)
- [L'homme le plus détesté d'Internet](https://youtu.be/ySFpxEdKxMw)
- [Pourquoi m'as-tu tué ?](https://youtu.be/QEXV8Rif8Vc)
- [Web of Make Believe : Death, Lies and the Internet](https://youtu.be/Z_l702HNPAA)
- [Don't F**k With Cats : Hunting an Internet Killer](https://youtu.be/x41SMm-9-i4)
- [Reddit a ruiné leur vie : les victimes innocentes de la justice sur Internet](https://youtu.be/hi14dP5Rdm0)
- [Cyber Hell : Exposing an Internet Horror](https://youtu.be/hpceNxQASKw)
- [Qui suis-je - Kein System ist sicher](https://www.imdb.com/title/tt3042408/)
- [L'histoire de l'horreur analogique](https://youtu.be/-I_4ph-L19U)
- [Dark Web : Cicada 3301](https://www.imdb.com/title/tt8110246/)
- [Movie 43 (LOL)](https://youtu.be/A9fBCkwDW8c)
- [Mr. Robot](https://www.imdb.com/title/tt4158110/)
- [Open Windows](https://m.imdb.com/title/tt2409818/)
- [Män som hatar kvinnor](https://m.imdb.com/title/tt1132620/)

**Références:**

> [Open Source Intelligence, communément appelé OSINT,](https://www.skopenow.com/news/osintforgood-the-philanthropic-application-of-osint) est la collecte, le regroupement et l'analyse d'informations accessibles au public. L'OSINT est un savoir-faire développé dans le secteur de la sécurité nationale qui s'est maintenant étendu à toute une série de secteurs, y compris l'application de la loi, le journalisme, la sécurité des entreprises, la recherche universitaire et le secteur juridique. L'OSINT peut également être utilisé pour soutenir des causes caritatives !

- [Des films sympas liés à l'OSINT ?](https://www.reddit.com/r/OSINT/comments/owxp7r/any_cool_movies_related_to_osint/)
- [Liste de films sur l'OSINT](https://twitter.com/AllForOsint/status/1581244439271350272)
- [Les meilleurs films sur l'OSINT](https://medium.com/@sector035/osint-movie-temps-pour-les-vacances-7a5f74f18f44)
- [Les meilleurs films sur l'OSINT](https://medium.com/@ibederov_fr/the-best-films-about-osint-5c3ab580f56)
- [Télévision et films sur les espions, l'espionnage, le renseignement et l'espionnage](https://www.intelligence101.com/my-favourite-intelligence-television-and-movies-about-spies-spying-intelligence-and-espionage/)
- [Liste des films de la Défense - version tableur](https://www.spyculture.com/dod-film-list-spreadsheet-version/)
- [Semaine de l'OSINT 2020-12](https://sector035.nl/articles/2020-12)
- [ARG SubReddit](https://www.reddit.com/r/ARG/)
- [OSINT SubReddit](https://www.reddit.com/r/OSINT/)
- [Blockchain OSINT](https://www.forensicxs.com/blockchain-osint-decentraland/)
- [John Doe frappe à nouveau](https://hamzaharooon.medium.com/john-doe-strikes-again-n00bzctf-osint-d2122d54c508)
- [Measurement and Signature Intelligence (MASINT)](https://irp.fas.org/program/masint.htm)
- [Une recherche pour tout régler - Recherches booléennes d'images](https://nixintel.info/osint/one-search-to-rule-them-all-boolean-searches-for-images/)
- [Guide de création de SOC Puppet](https://medium.com/the-sleuth-sheet/soc-puppet-creation-guide-888768dce96e)
- [Les trois types de renseignements pour la veille sur les menaces : Un guide complet](https://medium.com/the-sleuth-sheet/the-three-types-of-intelligence-for-threat-intelligence-a-comprehensive-guide-e8bbf1f26164)
- [Démasquer l'OSINT : un voyage d'agrégation de données](https://medium.com/@VEEXH/unmasking-osint-a-data-aggregation-journey-14bea88eb045)

**Livres OSINT:**

- [Mes livres récemment lus sur l'OSINT et la sécurité - recommandations](https://www.osintme.com/index.php/2021/04/30/my-recently-read-osint-security-books-recommendations/)
- [Formation geodetective.io](https://geodetective.io/)
- [The Open Source Intelligence Analysis Bookshelf](https://medium.com/the-sleuth-sheet/the-open-source-intelligence-analysis-bookshelf-942dc05a16bd)
- [7 livres OSINT que tout analyste devrait lire](https://www.liferaftinc.com/blog/7-osint-books-every-analyst-should-read?hs_amp=true)
- [Livres de Michael Bazzell](https://inteltechniques.com/book1.html)
- [Ce qu'il faut lire pour comprendre le renseignement et l'espionnage](https://www.wgu.edu/career-guide/information-technology/osint-career.html#openSubscriberModal)
- [The Official CIA Manual of Trickery and Deception - H. Keith Melton, Robert Wallace (2009)](https://www.bokus.com/bok/9780061943331/official-cia-manual-of-trickery-and-deception/) & [Link](https://www.google.se/books/edition/The_Official_CIA_Manual_of_Trickery_and/LbrzMtkyCGUC?hl=ru&gbpv=1&dq=inauthor:%22H.+Keith+Melton%22&printsec=frontcover) & [Link2](https://www.bokus.com/bok/9780061943331/official-cia-manual-of-trickery-and-deception/)
- [Outils OSINT offensifs](https://github.com/wddadk/Offensive-OSINT-Tools)
- [Spycraft](https://books.google.se/books/about/Spycraft.html?id=eJg0WV6sGlEC&redir_esc=y) & [Link](https://www.google.se/books/edition/Spycraft/RHWH7gVIO9cC?hl=ru&gbpv=1&dq=inauthor:%22H.+Keith+Melton%22&printsec=frontcover)
- [Ultimate Spy](https://www.google.se/books/edition/Ultimate_Spy/EObtBgAAQBAJ?hl=ru&gbpv=1&dq=inauthor:%22H.+Keith+Melton%22&printsec=frontcover)
- [Meilleures ventes de livres de Kevin Mitnick](https://www.mitnicksecurity.com/bestselling-books-by-kevin-mitnick)

**Méthode Zettelkasten:**

- [Méthode Zettelkasten avec Obsidian - Comment prendre des notes intelligentes](https://beingpax.medium.com/zettelkasten-method-with-obsidian-how-to-take-smart-notes-with-examples-cdaf348febbd)
- [Mise en place d'un Zettelkasten dans Obsidian : plus qu'une application de prise de notes](https://facedragons.com/productivity/setting-up-a-zettelkasten-in-obsidian/)
- [obsidian-zettelkasten](https://mattgiaro.com/obsidian-zettelkasten/)
- [Démarrer avec les Zettelkasten](https://obsidian.rocks/getting-started-with-zettelkasten-in-obsidian/)
- [Awesome OSINT](https://github.com/jivoi/awesome-osint)
- [Guide de l'OSINT](https://github.com/drull1000/OSINT-guide)

# Travail : A-Z

Je vois cela comme l'apprentissage d'une langue étrangère. D'accord, vous l'avez apprise et vous venez vivre dans un pays où elle est parlée. Mais tout le monde là-bas connaît cette langue... Il est donc important de connaître autre chose en plus. Typiquement, il est nécessaire d'avoir des compétences rédactionnelles, de bien interagir avec les gens, ou d'être juriste. Cela dit, différentes approches requièrent différentes compétences et différents états d'esprit !

> Gardez à l'esprit que l'OSINT n'est PAS une "sorte de [front-running/tailgating](https://www.investopedia.com/terms/f/frontrunning.asp) ou de scalping mais dans la vraie vie" !

<details>
<summary>Expansion</summary>
<br />

- ["Il n'y a rien de tel que l'intelligence à source ouverte"](https://threadreaderapp.com/thread/1633909123988242438.html)
- [Comment devenir un enquêteur dans le domaine du renseignement à source ouverte (OSINT)](https://www.wgu.edu/career-guide/information-technology/osint-career.html#close)
- [En fait, un excellent livre sur les attaques et les défenses](https://www.amazon.com/Network-Attacks-Defenses-Hands-Approach-ebook/dp/B00A8SN8WQ)
- [Guide OSINT - Open Source Intelligence](https://www.osintguide.com/2023/01/04/start-a-consulting-business-as-an-osint-expert/)
- [L'art de la défense proactive : maîtriser la chasse aux menaces avec les outils OSINT](https://medium.com/@mohitdeswal_35470/the-art-of-proactive-defense-mastering-threat-hunting-with-osint-tools-336683d6d53b)
- [Le semestre manquant de votre formation OSINT](https://medium.com/the-sleuth-sheet/the-missing-semester-of-your-osint-education-60b7bd48b7e9)
- [L'OSINT pour les personnes en recherche](https://docs.google.com/spreadsheets/d/1JxBbMt4JvGr--G0Pkl3jP9VDTBunR2uD3_faZXDvhxc/edit#gid=1978517898)
- [Collection de ressources OSINT d'AaronCTI](https://docs.google.com/spreadsheets/d/1klugQqw6POlBtuzon8S0b18-gpsDwX-5OYRrB7TyNEw/htmlview)

</details>

**Travail:**

- [anonfriendly.com](http://anonfriendly.com/)
- [osintjobs](https://twitter.com/osintjobs)
- [Je vous montrerai comment gagner de l'argent grâce à l'OSINT](https://0xtechrock.gumroad.com/)
- [Python pour OSINT 21 jours](https://github.com/cipher387/python-for-OSINT-21-days)
- [osintjobs.sociallinks.io](https://osintjobs.sociallinks.io/)
- [Liste d'outils d'investigation en chaîne](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List)
- [Comment trouver un emploi dans le Web3 ?](web.archive.org/web/20220618210743/https://twitter.com/_prestwich/status/1538267150917308416)
- [www.jobprotocol.xyz](https://www.jobprotocol.xyz/) & essayez [HR games](https://sourcing.games/) !
- Diligence raisonnable
- [Rejoindre une équipe déjà existante...](https://osintfr.com/en/our-osinters-are-talented/)
- Journalisme
- SMM
- [Enquêtes AML/Crypto](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List)
- [strategytribe.io](https://strategytribe.io)
- [Tâches à temps partiel](https://telegra.ph/Scamfari-04-28)
- [Détecter les fuites d'informations personnelles grâce à la gestion de la surface d'attaque OSINT](https://osintteam.blog/detect-personal-information-leakage-with-osint-attack-surface-management-4a46923dd2fd)

# Données externes

**Plus d'outils (au hasard) à utiliser au travail:**

- [mullvad.net/fr/browser](https://mullvad.net/en/browser)
- [TinyCheck](https://github.com/KasperskyLab/TinyCheck)
- [lampyre.io](https://lampyre.io/)
- [osintui](https://github.com/wssheldon/osintui)
- [Detect.Expert](https://Detect.Expert)
- [OSINT-Browser-Extensions](https://github.com/cqcore/OSINT-Browser-Extensions)
- [cylect.io](https://cylect.io/)
- [tazeros.com/webanalytics](https://tazeros.com/webanalytics)
- [dorkgenius.com](https://dorkgenius.com)
- [X-osint](https://github.com/TermuxHackz/X-osint)
- [meta-webtools.com](https://meta-webtools.com/)
- [Venatorbrowser](https://t.me/venatorbrowser)
- [app.shadowmap.org](https://app.shadowmap.org/)
- [dnstwist](https://github.com/elceef/dnstwist)
- [Automated Website Takedown](https://bolster.ai/automated-website-takedown)
- [OSINT+ChatGPT PDF](https://t.me/osintil/332)
- [GVision](https://github.com/GONZOsint/gvision?s=35)
- [geohints.com](https://geohints.com/)
- [Collection d'outils OSINT pour les médias sociaux](https://github.com/osintambition/Social-Media-OSINT-Tools-Collection)

**Spécifique (à mettre à jour):**

> **Selon [GoldenOwl](https://osintteam.blog/safeguarding-osinters-shielding-against-disinformation-manipulation-dfbbfbf1db08):** Alors que la lutte contre la désinformation s'intensifie, les praticiens de l'OSINT doivent être vigilants et se protéger contre la manipulation. En adoptant un esprit critique, en diversifiant les sources d'information, en vérifiant les informations des médias sociaux, en utilisant des outils de vérification des faits, en se tenant au courant des techniques de désinformation, en collaborant avec des communautés de confiance, en éduquant les autres, en [maintenant des normes éthiques](https://osintteam.blog/safeguarding-osinters-shielding-against-disinformation-manipulation-dfbbfbf1db08) et en recoupant les informations, les praticiens de l'OSINT peuvent se prémunir contre la manipulation et préserver l'intégrité de leurs recherches. 

- [ChatGPT + OSINT](https://m.youtube.com/watch?v=L5OlYdCWzRs&feature=youtu.be)
- [Bonus OSINT Twitter Crypto toolset](https://telegra.ph/Bonus-OSINT-Twitter-Crypto-toolset-04-15)
- [Awesome OSINT Web3](https://github.com/aaarghhh/awesome_osint_criypto_web3_stuff)
- [tgscanrobot](https://t.me/tgscanrobot)
- [velociraptor.app](https://docs.velociraptor.app)
- [Web3/NFT OSINT](https://twitter.com/fuzzinglabs/status/1676226856553521153)
- [maigret_osint_bot](https://t.me/maigret_osint_bot)
- [telesint_bot](https://t.me/telesint_bot)
- [outil seekr](https://github.com/seekr-osint/seekr)
- [Ressources sur le journalisme de données](https://github.com/r3mlab/datajournalism-resources)
- [Guide de la criminalistique numérique](https://github.com/mikeroyal/Digital-Forensics-Guide)
- [Twitter to TG bot](https://t.me/TwttrToTG_Bot)
- [Hackathon Bellingcat - Projet stratosphère](https://github.com/elehcimd/stratosphere)
- [osint-Brésil](https://github.com/osintbrazuca/osint-brazuca)
- [spiderfoot](https://github.com/smicallef/spiderfoot)
- [Awesome TG channel](https://t.me/osintil)
- [Inpaint-Anything](https://github.com/geekyutao/Inpaint-Anything)
- [metaosint.github.io](https://metaosint.github.io/chart)
- [Maltego Transforms List](https://github.com/cipher387/maltego-transforms-list)
- [Catalogue d'outils open-source OSINT](https://github.com/HowToFind-bot/osint-tools)
- [Modèle pour les nouveaux outils OSINT en ligne de commande](https://github.com/soxoj/osint-cli-tool-skeleton)
- [Top OSINT sources and vishing pretexts from DEF CON's social engineering competition](https://medium.com/@chris.kirsch/top-osint-sources-and-vishing-pretexts-from-def-cons-social-engineering-competition-8e08de4c8ea8)

**Articles intéressants (externes):**

> [Comme le montre la pratique](https://medium.com/@ibederov_fr/military-intelligence-using-osint-methods-4aae1df2d812), les conflits armés modernes nécessitent de nouvelles approches pour organiser la collecte et l'analyse des données ouvertes, que nous exploitons dans le cadre de l'OSINT. Soyez prudents et réfléchissez à deux fois avant d'agir.

- [Human Touch in Digital Defense : Virtual HUMINT's Battle Against Cyber Threats](https://osintteam.blog/human-touch-in-digital-defense-virtual-humints-battle-against-cyber-threats-33b81b3be53b)
- [Du zéro au héros de Google Dorking : améliorer votre arsenal OSINT](https://osintteam.blog/mastering-osint-the-art-of-google-dorking-for-investigators-e0a908055873)
- [Utilisation de ddg.gg pour l'OSINT](https://www.ghacks.net/2023/04/24/duckduckgo-disables-most-search-filters-from-search/?amp)
- [cybdetective.substack.com](https://cybdetective.substack.com)
- [Découvrir les connexions cachées : Using Maltego Holehe to Map Out a Person's Digital Footprint](https://medium.com/@philipbcase/uncovering-hidden-connections-using-maltego-holehe-to-map-out-a-persons-digital-footprint-90914d6bcbff)
- [Espionnage PDF](https://t.me/irozysk/9243)
- [Hacktoria - Trafiquants d'êtres humains](https://medium.com/@wirec47/hacktoria-trafiquants d'êtres humains-b9bb00638c6a)
- [Mot de passe OSINT](https://viruszzwarning.medium.com/password-osint-fc4fd750ea8c)
- [Utilisation de l'IA pour développer des comptes Sock Puppet réalistes](https://www.raebaker.net/blog/using-ai-to-develop-realistic-sock-puppet-accounts)
- [ARCHIVAGE ET OSINT](https://latenightafa.noblogs.org/archiving-and-osint/)
- [Awesome OSINT](https://github.com/jivoi/awesome-osint)
- [Awesome Telegram OSINT](https://github.com/ItIsMeCall911/Awesome-Telegram-OSINT)
- [Visualisation du Darknet](https://medium.com/@cosmograph.app/visualizing-darknet-6846dec7f1d7)
- [Open Source Intelligence : The Beginners' Guide to OSINT](https://www.liferaftinc.com/blog/the-beginners-guide-to-osint)
- [Guide de l'OSINT sur le DarkNet](https://medium.com/the-sleuth-sheet/darknet-osint-guide-984f68fb7ab3)
- [Guide de terrain pour les débutants : où et comment apprendre l'OSINT](https://medium.com/the-sleuth-sheet/beginners-field-guide-where-how-to-learn-osint-bd2e11469f31)
- [MANUEL DES OUTILS ET RESSOURCES DE RENSEIGNEMENT À SOURCE OUVERTE 2020](https://i-intelligence.eu/uploads/public-documents/OSINT_Handbook_2020.pdf)
- [Reconnaissance des opérations d'information : de l'analyse non linéaire à la prise de décision](https://arxiv.org/pdf/1901.10876.pdf)
- [Analyse OSINT de la Fondation TOR](https://arxiv.org/pdf/1803.05201.pdf)
- [Top 10 des outils OSINT pour les enquêtes sur les pseudonymes](https://medium.com/@ibederov_fr/my-top-10-osint-tools-for-nickname-investigation-40e292fa5c84)

**Quelques outils remarquables:**

 > La dernière étape consiste à élaborer un plan pour maintenir et améliorer vos compétences OSINT. Choisissez des ressources pour l'apprentissage continu, trouvez des défis à relever et envisagez de rejoindre une communauté OSINT. Enfin, passez en revue vos directives éthiques afin de vous assurer que vous travaillez toujours de manière responsable et respectueuse. - [Ron Kaminsky](https://medium.com/@ronkaminskyy/from-zero-to-sherlock-the-ultimate-osint-adventure-5f9d8c45ae2)

- [datashare.icij.org](https://datashare.icij.org)
- [Pinpoint](https://journaliststudio.google.com/pinpoint/collections)
- [dtsearch.com](https://www.dtsearch.com/)
- [Venator](https://t.me/venatorbrowser)
- [Un cadre de crawling et de spidering de nouvelle génération](https://github.com/projectdiscovery/katana)
- [Start.me](https://about.start.me/)
- [dorksearch.com](https://dorksearch.com)
- [E4GL30S1NT](https://github.com/C0MPL3XDEV/E4GL30S1NT)
- [Advangle](http://advangle.com)
- [Awesome-chatgpt](https://github.com/sindresorhus/awesome-chatgpt)
- [obsidian.md](https://obsidian.md/)
- [dorkgenius.com](https://dorkgenius.com)
- [canarytokens.org](https://canarytokens.org/generate)
- [iplogger.org](https://iplogger.org)
- [Universal Search](https://t.me/UniversalSearchRobot)
- [Intercepter-NG](http://sniff.su/)
- [metadata2go.com](https://www.metadata2go.com)
- [suip.biz](https://suip.biz/)
- [Awesome Deblurring](https://github.com/subeeshvasu/Awesome-Deblurring)

**En profondeur (externe):**

> **Selon [Alessandra Adina](https://medium.com/@alessandraadina/how-to-do-cyber-reconnaissance-a-guide-to-osint-for-non-tech-professionals-da6c7db48699):** Le cycle du renseignement représente le processus de développement d'informations brutes en renseignements exploitables. Ce processus peut permettre aux décideurs de prendre des mesures appropriées sur la base de leurs conclusions. Bien que différentes organisations utilisent des variations sur différents cycles de renseignement, un cycle populaire est un cycle en cinq étapes : **planification, collecte, analyse, diffusion et retour d'information**.

- [OSINT : Comment trouver des informations sur n'importe qui](https://osintteam.blog/osint-how-to-find-information-on-anyone-5029a3c7fd56)
- [OSINT - Guide du débutant (1ère partie)](https://medium.com/@Aardwarewolf/what-is-osint-part-1-91aaa3890643)
- [OSINT : FOUNDATIONS](https://i-intelligence.eu/courses/osint-foundations)
- [Comment utiliser l'OSINT pour détecter les fuites et les violations de données](https://www.liferaftinc.com/blog/how-to-use-osint-to-detect-data-leaks-and-breaches)
- [Introduction à l'OSINT](https://infosecwriteups.com/introduction-to-osint-2c92597988d1)
- [Comment améliorer la détection des cyberattaques à l'aide des médias sociaux](https://www.geeksforgeeks.org/how-to-improve-cyber-attack-detection-using-social-media/)
- [Fuyez-vous des informations sur le web ? Utilisez ces outils pour le savoir](https://www.tech.gov.sg/media/technews/are-you-leaking-information-on-the-web)
- [OSINT : Fuites et violations de données](https://www.osintguru.com/blog/osint-data-leaks-and-data-breaches)
- [OSINT avec gOSINT](https://brandefense.io/blog/osint-with-gosint/)
- [Liste des ressources web OSINT](https://github.com/OhShINT/ohshint.gitbook.io/blob/main/Lists_of_OSINT_Web_Resources/1-Complete-List-of-OSINT-Web-Resources.md)
- [Une carte heuristique OSINT/SOCMINT](http://files.mtg-bi.com/MindMap.jpg)
- [Comment trouver - Robot](https://t.me/HowToFind)
- [Jeu du mot de passe](https://neal.fun/password-game/)
- [Comment utiliser l'OSINT dans le domaine de la cybersécurité](https://www.molfar.global/en-blog/how-to-use-osint-in-cybersecurity)
- [OSINT (OPEN-SOURCE INTELLIGENCE) - Devenez difficile à pirater !](https://somprt.com/our-series/osint-open-source-intelligence/)
- [Sujet OSINT sur GitHub](https://github.com/topics/open-source-intelligence?o=desc&s=stars)
- [SOCMINT - ou plutôt OSINT des médias sociaux](https://research.securitum.com/socmint-or-rather-osint-of-social-media/)

**Ressources plus spécifiques (externes):**

> **Selon [Alessandra Adina](https://medium.com/@alessandraadina/how-to-do-cyber-reconnaissance-a-guide-to-osint-for-non-tech-professionals-da6c7db48699):** Un terme que vous pouvez rencontrer dans le domaine de l'OSINT est la "littérature grise". Il s'agit de documents internes qui ne sont pas destinés à un usage public, mais qui, malheureusement, peuvent facilement se retrouver dans des endroits où ils peuvent être recherchés. Il peut s'agir par exemple de rapports techniques, de bulletins d'information, de factures, de propositions commerciales ou d'appels d'offres.

> Il est essentiel de comprendre la valeur des informations de votre organisation, les vecteurs d'attaque potentiels et les personnes susceptibles d'être ciblées par des attaques de phishing ou d'autres types d'ingénierie sociale. L'OSINT peut vous aider à évaluer ces risques et à planifier des défenses appropriées.

- [OrienterNet Visual Localization in 2D Public Maps with Neural Matching](https://github.com/facebookresearch/OrienterNet)
- [Outils OSINT - Airtable](https://airtable.com/embed/shrYXDdO1V5y33lIX/tblgDtMXI4fxtg9Op)
- [OSINT - HUMINT](https://docs.google.com/spreadsheets/d/1JxBbMt4JvGr--G0Pkl3jP9VDTBunR2uD3_faZXDvhxc/edit#gid=1978517898)
- [Ultimate OSINT](https://start.me/p/DPYPMz/the-ultimate-osint-collection)
- [Liste OSINT](https://start.me/p/ZME8nR/osint)
- [Liste OSINT curatée](https://start.me/p/7kxyy2/osint-tools-curated-by-lorand-bodo)
- [OSINT Inception](https://start.me/p/Pwy0X4/osint-inception)
- [Géolocalisation-OSINT](https://github.com/cqcore/Geolocation-OSINT)
- [researchaide.org](https://www.researchaide.org/)
- [botster.io/bots Crawling](https://botster.io/bots)
- [Encore une autre liste OSINT géniale](https://start.me/p/rx6Qj8/nixintel-s-osint-resource-list)
- [Cryptocurrency OSINT](https://start.me/p/ek4rxK/cryptocurrency)
- [Awesome On-Chain Investigations HandBook](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List/blob/main/README.md)
- [Outils pour enquêteurs](https://start.me/p/gyaOJz/investigator-tools)
- [Une collection de plusieurs centaines d'outils en ligne pour l'OSINT](https://github.com/cipher387/osint_stuff_tool_collection)
- [Rawsec's CyberSecurity Inventory](https://inventory.raw.pm/tools.html#title-tools-osint)
- [OSINT-TOOLS-CLI](https://github.com/Coordinate-Cat/OSINT-TOOLS-CLI)
- [Géoestimation](https://labs.tib.eu/geoestimation/)
- [Utilisation de moteurs de recherche OSINT pour collecter des renseignements sur les cybermenaces](https://osintteam.blog/using-osint-search-engines-to-collect-cyber-threat-intelligence-3e9ace82eb64)
- [GraphSense Maltego Transform](https://github.com/INTERPOL-Innovation-Centre/GraphSense-Maltego-transform)
- [leakix.net](https://leakix.net/)
- [Officier_CIA X MaxWayld : Aperçu du contenu](https://officercia.medium.com/officer-cia-x-maxwayld-content-overview-39fa3011a73f)
- [Explorer le côté obscur : Outils et techniques OSINT pour démasquer les opérations du Dark Web](https://www.sans.org/blog/exploring-the-dark-side-osint-tools-and-techniques-for-unmasking-dark-web-operations/)

**Telegram + Discord : Sécurité, OSINT, SOCMINT:**

 > Selon [Ron Kaminsky](https://osintteam.blog/unveiling-the-digital-detective-essential-osint-tools-and-techniques-for-investigators-adf486ad2ccd): L'OSINT a révolutionné le monde des enquêtes, permettant aux individus et aux organisations de découvrir des informations précieuses, de résoudre des problèmes complexes et de prendre des décisions éclairées. [La capacité à exploiter](https://osintteam.blog/unveiling-the-digital-detective-essential-osint-tools-and-techniques-for-investigators-adf486ad2ccd) la grande quantité de données disponibles dans les sources ouvertes a ouvert de nouvelles possibilités et transformé le paysage de l'investigation. En utilisant efficacement les outils OSINT, les enquêteurs peuvent gagner du temps, recueillir des informations complètes et découvrir des liens qui, autrement, seraient restés cachés. Les techniques et méthodologies explorées dans ce guide constituent une feuille de route pour mener des enquêtes OSINT approfondies et fructueuses.

- [Comment trouver l'emplacement exact d'un téléphone, d'une tablette ou d'un PC](https://medium.com/@ibederov_fr/how-to-find-the-exact-location-of-phone-tablet-or-pc-b953a60421a9)
- [osint-mindset.gitbook.io](https://osint-mindset.gitbook.io) | Astuce : Utilisez [deepl.com](https://www.deepl.com/translator) !
- [Discord OSINT Toolset](https://telegra.ph/Discord-OSINT-Toolset-04-11)
- [DiscordOSINT](https://github.com/AtonceInventions/DiscordOSINT)
- [Telegram OSINT](https://github.com/cqcore/Telegram-OSINT)
- [Ressources OSINT Discord](https://github.com/Dutchosintguy/OSINT-Discord-resources)
- [TelegramOnlineSpy](https://github.com/Forichok/TelegramOnlineSpy)
- [Références OSINT sur Discord et Telegram](https://github.com/Ginsberg5150/Discord-and-Telegram-OSINT-references)
- [Awesome Discord](https://github.com/jacc/awesome-discord)
- [Awesome Telegram OSINT](https://github.com/ItIsMeCall911/Awesome-Telegram-OSINT)
- [Darvester](https://github.com/darvester/darvester)
- [OpSec Telegram & Discord](https://officercia.mirror.xyz/dlf6ZEXq3FLE21ZY2jeJ0cBDyuZu8XIF9DEJAQ07nk8)
- [OpSec Discord pour les serveurs](https://officercia.mirror.xyz/x4nGX6YwhhmHj8TaQ53kBR5b5M1Ei_Y9_l1Vpext-Hk)
- [Si vous avez été arnaqué...](https://officercia.mirror.xyz/X5Q0uPwvlgZ6BrvCmyqXlXHFgLAWrMtzAHSvjzrDS7c)

**Consultez mes articles:**

- [Navigation (mes articles)](https://officercia.mirror.xyz/Uc1sf64yUCb0uo1DxR_nuif5EmMPs-RAshDyoAGEZZY)
- [Article original](https://officercia.mirror.xyz/5KSkJOTgMtvgC36v1GqZ987N-_Oj_zwvGatOk0A47Ws)
- [L'OpSec devient intelligente](https://officercia.mirror.xyz/fsRT9NC29GzeQAl-zvAMJ9L-hYUYvX1CPUkt97Vuuwo)
- [OpSec Going Smarter](https://officercia.mirror.xyz/B9hBom4jGhkV0C-47E4YBz8tBJkb0a7zVwQR0jITIyM)
- [OpSec Going Smarter : Secure Smartphones](https://officercia.mirror.xyz/0tlSSF2LDTOnnMN41R5Uc1kTpo-G-kXljn8pT0a1YLY)
- [Choisir un fournisseur de VPN fiable pour la vie et le travail](https://officercia.mirror.xyz/x91hTIDFrAL0lgqICRgWU7fLouuCMgvopQ9ZRvRXCLg)
- [Une liste ultime de règles que tout survivant sur la chaîne devrait suivre pour rester en sécurité](https://officercia.mirror.xyz/_nD1Rtxe1PplK-NQzIq9sl-KNtajQG0aKqYsV36RTjA)
- [QR Code : un danger sous-estimé](https://officercia.mirror.xyz/aN6giRkUsNd0o0bmjZVeZb2htkO_Ve16gMsARU6RBfM)
- [Les étapes les plus importantes dans le développement des communications](https://officercia.mirror.xyz/G4782jMUpA_kkIpwakphbd6djX85cxRGS-pjBipc8Yk)
- [Comment gagner la guerre, tromper le KGB et protéger vos crypto-actifs contre le vol par stéganographie](https://officercia.mirror.xyz/8ecJG-s_5E6J1t-h8gUNGqV3hbX8If-E5NnrFrOJHUA)
- [Attaques via un échantillon représentatif : mythes et réalité](https://officercia.mirror.xyz/WeAilwJ9V4GIVUkYa7WwBwV2II9dYwpdPTp3fNsPFjo)
- [Comment devenir un spécialiste de l'OSINT à l'échelle de l'armée](https://officercia.mirror.xyz/5KSkJOTgMtvgC36v1GqZ987N-_Oj_zwvGatOk0A47Ws)
- [Meilleures pratiques de sécurité pour Telegram et Discord](https://officercia.mirror.xyz/dlf6ZEXq3FLE21ZY2jeJ0cBDyuZu8XIF9DEJAQ07nk8)

# Projet de soutien

Le soutien est **très** important pour moi, grâce à lui je peux passer moins de temps au travail et faire ce que j'aime - éduquer les utilisateurs de DeFi & Crypto :sparkling_heart :

Si vous voulez soutenir mon travail, envisagez de me faire un don à l'adresse suivante :

- **[0xB25C5E8fA1E53eEb9bE3421C59F6A66B786ED77A](https://etherscan.io/address/0xB25C5E8fA1E53eEb9bE3421C59F6A66B786ED77A)** — ERC20 & ETH [officercia.eth](https://etherscan.io/enslookup-search?search=officercia.eth)

- **[17Ydx9m7vrhnx4XjZPuGPMqrhw3sDviNTU](https://blockchair.com/bitcoin/address/17Ydx9m7vrhnx4XjZPuGPMqrhw3sDviNTU)** - BTC

- **4AhpUrDtfVSWZMJcRMJkZoPwDSdVG6puYBE3ajQABQo6T533cVvx5vJRc5fX7sktJe67mXu1CcDmr7orn1CrGrqsT3ptfds** - Monero XMR

Vous pouvez aussi m'envoyer un don à l'adresse de [ce dépôt] (https://github.com/OffcierCia/support) !

**Vérifiez aussi:**

- [Mon blog sur Mirror](https://officercia.mirror.xyz/UpFfG7-1E4SDJttnmuQ7v4BMc4KrCXzo80vtx7qV-YY)

### Merci ! 🙏

---
