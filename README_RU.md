# Нетипичное руководство по OSINT

#### Самое необычное руководство по OSINT, которое вы когда-либо видели. Репозиторий предназначен только для скучающих профессионалов. 

#### PR приветствуются! Не стесняйтесь отправлять запросы на исправления, начиная от мелких исправлений и заканчивая переводами, документами или инструментами, которые вы хотели бы добавить.

> **Отказ от ответственности: Вся информация (инструменты, ссылки, статьи, текст, изображения и т.д.) предоставляется исключительно в образовательных целях! Вся информация также основана на данных из открытых источников. Ответственность за свои действия несете только вы, а не автор** ❗️

[![Поддержка проекта](https://img.shields.io/badge/Support-Project-critical)](https://github.com/OffcierCia/support/blob/main/README.md)
       [![Почта](https://img.shields.io/badge/Mail-offcierciapr%40protonmail.com-brightgreen)](mailto:offcierciapr@protonmail.com)

# Start Here

**Посмотрите:**

- [Навигация (мои статьи)](https://officercia.mirror.xyz/Uc1sf64yUCb0uo1DxR_nuif5EmMPs-RAshDyoAGEZZY)
- [Оригинальная статья](https://officercia.mirror.xyz/5KSkJOTgMtvgC36v1GqZ987N-_Oj_zwvGatOk0A47Ws)
- [Также размещено здесь!](https://officercia.medium.com/the-atypical-osint-guide-2023-276a8d00959)

Сегодня я хотел бы поговорить о том, как стать хорошим OSINT-расследователем, но для продолжения разговора хочу сделать небольшую оговорку - я расскажу лишь о некоторых аспектах, поскольку тема очень обширна и я не смогу описать все в одном руководстве, однако я постараюсь показать вам путь и то, как пройти этот путь. Данное руководство является итогом многолетней работы профессионалов OSINT. Рассматривайте этот путеводитель как сборник советов и маршрутов!

Помните, что данное сочинение носит обучающий характер! Тщательно обдумывайте свои действия, иначе вы будете привлечены к ответственности или еще хуже! Всегда помните об этике и сопутствующих законах - таких как GDPR и т.д... Не стоит романтизировать OSINT и расследования на цепи так же, как люди часто романтизируют хакерство и военные действия, я вас очень прошу!

- [Бостонский взрыв: как интернет-детективы ошиблись](https://www.bbc.com/news/technology-22214511)
- [OSINT? WTF??](https://ohshint.gitbook.io/oh-shint-its-a-blog/osint/osint-wtf)

> И последнее, но не менее важное: все, что вы делаете, основывается на тех результатах, которых вам нужно достичь! Вы должны уметь выбирать надежные и проверенные источники, а не пользоваться всеми инструментами и ссылками. По заданным маршрутам вы должны уметь строить свой собственный путь! Далее я расскажу о тех способах, которые считаю безопасными и рекомендую своим клиентам! Профессионалы OSINT потратили десятилетия на разработку этого руководства, передавая свой опыт в каждом слове. Еще раз повторю, что рассматривайте это руководство как сборник советов и маршрутов.

Важно также отметить, что OSINT - это всего лишь еще один способ познания окружающего мира, а не способ "мгновенно получить деньги". Всегда делайте перерыв, чтобы восстановить силы! Ваше здоровье и ум очень важны!

- [How to know when to stop](https://www.lennysnewsletter.com/p/how-to-know-when-to-stop)
- [Как стать 1000-летним вампиром](https://www.lesswrong.com/posts/5QpufhoH2ASnppsjs/how-to-become-a-1000-year-old-vampire)
- [Как быстро научиться](https://degatchi.com/articles/how-to-learn-fast/)
- [Как использовать карты ума для раскрытия творческого потенциала вашего мозга](https://lifehacker.com/how-to-use-mind-maps-to-unleash-your-brains-creativity-1348869811)
- [Все ли могут заниматься OSINT?](https://medium.com/osintfun/can-everybody-do-osint-f5d5e6128445)
- [Викарная травма](https://osintcurio.us/2020/06/08/vicarious-trauma-and-osint-a-practical-guide/)

Эта информация не делает вас лучше или хуже. Человечество как вид имеет склонность к адаптации к окружающей среде, которая, как мы все знаем, начинается со знаний, наблюдений и методологии. Берегите себя, думайте о последствиях своих действий и уважайте частную жизнь других людей. Не переходите красных линий!

<details>
<summary>Расширение</summary
<br />

- [OSINT + Crypto](https://www.forensicxs.com/blockchain-osint-decentraland/)
- [Здесь мы обсуждаем, как можно расследовать крипто-взломы и инциденты безопасности!](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List)
- [osint.sh All in One OSINT Tools List](https://osint.sh/)
- [The Not Yet Yet Exploited Goldmine of OSINT: Opportunities, Open Challenges and Future Trends](https://www.researchgate.net/publication/338495014_The_Not_Yet_Exploited_Goldmine_of_OSINT_Opportunities_Open_Challenges_and_Future_Trends)

</details

Всегда думайте дважды, прежде чем действовать, соблюдайте закон и правила OpSec. Если вы хотите помочь или провести социальное расследование, но у вас нет опыта, обратитесь к более опытным людям, чтобы не навредить жертвам или тем, кто пытается их спасти. С другой стороны, в своих статьях я рассказываю о другом применении OSINT, вдохновленном due diligence и гражданской финансовой разведкой, с акцентом на **гражданское** применение. Это мое видение, которое, я надеюсь, вы примете...

- [Intelligence Studies: Types of Intelligence Collection](https://usnwc.libguides.com/c.php?g=494120&p=3381426)
- [Understanding the Different Types of Intelligence Collection Disciplines](https://www.maltego.com/blog/understanding-the-different-types-of-intelligence-collection-disciplines/)
- [inteltechniques.com](https://inteltechniques.com)
- [A History of OSINT: From Informing Spies to Detecting Lies](https://www.skopenow.com/news/a-history-of-osint)
- [Open Source Intelligence Investigation: From Strategy to Implementation](https://www.researchgate.net/publication/321531302_Open_Source_Intelligence_Investigation_From_Strategy_to_Implementation)
- [Rverse Image Search](https://www.numlookup.com/reverse-image-search)

### Да пребудет с вами сила!

# Введение: Гражданский OSINT

Для начала хочу сказать, что я буду рассматривать OSINT как набор навыков или образ мышления, потому что он может быть напрямую связан с доксингом, военным GEO-INT, который проводит сотрудник охранной компании, или просто медийным OSINT, который проводит сотрудник VC-фонда, чтобы найти новые проекты для инвестиций, взяв за основу теорию рукопожатий...

- [OSINT Is A State Of Mind](https://medium.com/secjuice/osint-as-a-mindset-7d42ad72113d)
- [Cognitive Bias and Critical Thinking in Open Source Intelligence (OSINT)](https://deepsec.net/docs/Slides/2014/Cognitive_Bias_and_Critical_Thinking_in_Open_Source_Intelligence_(OSINT)_-_Benjamin_Brown.pdf)
- [Краткая история разведки с открытым исходным кодом](https://www.bellingcat.com/resources/articles/2016/07/14/a-brief-history-of-open-source-intelligence/)
- [Как OSINT помог провести крупнейшее уголовное расследование в истории США](https://www.isdglobal.org/digital_dispatches/jan-6-series-how-osint-powered-the-largest-criminal-investigation-in-us-history/)

...Или даже специалист по криптографической экспертизе, расследующий дело о крупном взломе Web3.0. Иными словами, OSINT может использоваться во всех сферах жизни, поскольку это всего лишь метод работы с информацией, ее оценки и ранжирования - не забывайте, что мы все живем в информационную эпоху.

<details>
<summary>Расширение</summary
<br />

- [Meet the Blockchain Detectives Who Tracking Crypto's Hackers and Scammers](https://www.vice.com/en/article/xgd9zw/meet-the-blockchain-detectives-who-track-cryptos-hackers-and-scammers)
- [Специальная подборка "Блокчейн-расследования"](https://t.me/officer_cia/236)
- [Как я расследую взломы и инциденты безопасности криптовалют: от А до Я](https://officercia.mirror.xyz/BFzv17UwH6QG4q711NAljtSiP8eKR17daLjTdmAgbHw)
- [On-Chain Investigations Handbook](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List)
- [The Beginner's Guide to Open-Source Intelligence (OSINT): Techniques and Tools](https://medium.com/@mohitdeswal_35470/the-beginners-guide-to-open-source-intelligence-osint-techniques-and-tools-6a91b9c37ee1)
- [Awesome Intelligence](https://github.com/ARPSyndicate/awesome-intelligence)

</details

Все, о чем я говорил выше, вы можете развить в себе, но суть всех направлений одна - умение замечать ценную информацию, аномалии, видеть различия, тщательно анализировать факты и выстраивать логическую цепочку - находясь в потоке информации. Начните с проверки собственной информации и собственных данных: проведите OSINT-исследование против самого себя. Соберите все данные, визуализируйте их, а затем сотрите - с помощью техники SERM/ORM.

- [SERM](https://thebusinessprofessor.com/seo-social-media-direct-marketing/search-engine-reputation-management-definition)
- [ORM](https://medium.com/elfsight-blog/introduction-to-search-engine-reputation-management-serm-44467c891c0b)
- [Примеры провалов в области опенсек и приватности при проведении OSINT](https://www.osintme.com/index.php/2022/01/17/examples-of-opsec-and-privacy-fails-when-doing-osint/)
- [WhatBreach](https://github.com/Ekultek/WhatBreach)
- [More OpSec Studies](https://github.com/lawsecnet/OPSEC)
- [Basic OPSEC Tips & Tricks for OSINT researchers](https://web.archive.org/web/20221108024236/https://osintcurio.us/2019/04/18/basic-opsec-tips-and-tricks-for-osint-researchers/amp/)
- [The Osint Me ultimate guide to Telegram OSINT and privacy](https://www.osintme.com/index.php/2022/10/18/the-osint-me-ultimate-guide-to-telegram-osint-and-privacy/)
- [Dork yourself before "someone" does](https://osintteam.blog/dork-yourself-before-someone-does-aa49d0c1929f)

Хочу дать вам первый урок, все ресурсы, которые я вам посоветую - я изучил сам ранее:

- [So You Think You Can Google? - Workshop With Henk van Ess](https://youtu.be/uyqXS5lL-mc)
- [OSINT Origins #1 - Jean-Marc Manach/@manhack](https://youtu.be/XrTFzZ77eEI)
- [An Awesome OSINT Mind-map](http://files.mtg-bi.com/MindMap.jpg)
- [Telegram & Discord Security Best Practices](https://officercia.mirror.xyz/dlf6ZEXq3FLE21ZY2jeJ0cBDyuZu8XIF9DEJAQ07nk8)
- [Окончательное руководство по генерации имен пользователей для OSINT](https://github.com/soxoj/username-generation-guide)
- [Сопротивление детерминированному мышлению](https://zephoria.medium.com/resisting-deterministic-thinking-52ef8d78248c)

# Mind-Mapping

Для начала разберем такое понятие, как mind-mapping. Очень важно научить сортировать информацию по различным критериям, я считаю, что вы можете практиковать сортировку абсолютно любой информации!

- [Mind-map](https://en.wikipedia.org/wiki/Mind_map)
- [Что нужно, чтобы стать промежуточным OSINTer'ом? Как Шодан может внести свой вклад в OSINT-расследования?](https://podtail.com/en/podcast/osintcurious/episode-51-what-do-you-need-to-become-an-intermedi/)
- [First Steps to Getting Started in Open Source Research](https://www.bellingcat.com/resources/2021/11/09/first-steps-to-getting-started-in-open-source-research/)
- [Все о разведке с открытым исходным кодом и OSINT-расследованиях](https://www.maltego.com/blog/what-is-open-source-intelligence-and-how-to-conduct-osint-investigations/)

**[Что такое Maltego и зачем его использовать для OSINT?](https://wondersmithrae.medium.com/a-beginners-guide-to-osint-investigation-with-maltego-6b195f7245cc)** Maltego - это инструмент интеллектуального анализа данных, который добывает информацию из различных открытых источников и использует ее для создания графиков, позволяющих анализировать связи. Графики позволяют легко устанавливать связи между такой информацией, как имя, электронная почта, организационная структура, домены, документы и т.д. Maltego использует Java, поэтому может работать под Windows, Mac и Linux и доступен во многих дистрибутивах OSINT Linux, таких как Buscador или Kali. 

По сути, он анализирует большой объем информации и выполняет поиск на различных сайтах с открытым исходным кодом, а затем выдает красивую диаграмму, которая поможет вам собрать все воедино. Maltego можно использовать в качестве ресурса в любой момент расследования, однако если ваша цель - домен, то имеет смысл с самого начала начать картировать сеть с помощью Maltego.

#### Разве не все делали шпаргалки в школе? Пришло время сделать это снова, потому что в будущем это должно перерасти в навык работы с Maltego!

- [Top OSINT & Infosec Resources for You and Your Team (2022 Edition): 100+ Blogs, Podcasts, YouTube, Books, and more!](https://www.maltego.com/blog/top-osint-infosec-resources-for-you-and-your-team/)
- [A Beginner's Guide to OSINT Investigation with Maltego](https://wondersmithrae.medium.com/a-beginners-guide-to-osint-investigation-with-maltego-6b195f7245cc)
- [Maltego - Cyber Weapons Lab - Research like an OSINT Analyst](https://youtu.be/46st98FUf8s)
- [Free Digital Badges for learning / developing OSINT Skills](https://www.reddit.com/r/OSINT/comments/kgew5d/free_digital_badges_for_learning_developing_osint/)
- [Tips To Encourage Your Child To Participate In Extracurricular Activities](https://talentgum.com/blog/tips-to-encourage-your-child-to-participate-in-extracurricular-activities)
- [Какие навыки нужны, чтобы хорошо играть в шахматы + как их улучшить](https://skillspointer.com/skills-for-chess/)

> Маленький совет - выполняйте [power-searching](https://www.edx.org/course/power-searching-with-google) с использованием разных IP, в разных временных диапазонах и через разные [поисковые системы](https://github.com/tasos-py/Search-Engines-Scraper).

## Понимание основ OSINT, согласно [VEEXH](https://wondersmithrae.medium.com/a-beginners-guide-to-osint-investigation-with-maltego-6b195f7245cc):

- a. Понять концепцию OSINT и ее значение для сбора разведданных.
- b. Ознакомиться с типами источников OSINT (например, социальные сети, публичные записи, онлайновые форумы, новостные издания).
- c. Изучить этические и юридические аспекты при сборе OSINT.

**Развитие технических навыков:**.

- a. Приобрести навыки базового использования компьютера и Интернета.
- b. Изучить передовые методы поиска с использованием поисковых систем и операторов.
- c. Понять важность анонимности и приобрести навыки использования VPN, прокси-серверов и сети Tor.
- d. Ознакомиться с основными инструментами OSINT, такими как Maltego, Shodan и Google Dorks.

**Освоение сбора OSINT:**.

- a. Научитесь определять и устанавливать приоритеты требований к разведданным.
- b. Разработать систематический подход к сбору данных из различных источников.
- c. Отточить навыки социальной инженерии, пассивной разведки и разведки в Интернете.
- d. Приобрести опыт в области геолокации, анализа изображений и поиска информации о лицах и организациях.

Анализ и оценка **ОСИНТ:**.

- a. Изучение различных методов анализа, таких как анализ связей, анализ временной шкалы и анализ настроений.
- b. Развивать критическое мышление и осознание когнитивных предубеждений.
- c. Понимать значение разведывательного цикла и применять его для анализа OSINT.
- d. Оценивать достоверность и надежность источников и информации.

**Распространение и представление информации об OSINT:**.

- a. Ознакомиться с принципами эффективной коммуникации.
- b. Научиться создавать разведывательные отчеты, справки и визуализации.
- c. Понять важность адаптации ваших отчетов для различных аудиторий.
- d. Развивать способность представлять результаты в ясной, краткой и действенной форме.

**Постоянное совершенствование и работа в сети:**.

- a. Быть в курсе последних тенденций, инструментов и методов OSINT.
- b. Участвовать в соответствующих онлайновых сообществах, форумах и группах в социальных сетях.
- c. Посещать конференции, семинары и вебинары по OSINT.

Следуя этой схеме, начинающие специалисты могут систематически развивать свои навыки в области OSINT и стать квалифицированными специалистами по сбору, анализу и распространению разведданных из открытых источников. OSINT (Open-source Intelligence) также является важнейшим этапом процесса тестирования на проникновение. 

Тщательное изучение общедоступной информации может повысить шансы найти уязвимую систему, получить достоверные учетные данные с помощью подбора паролей или закрепиться в системе с помощью социальной инженерии.

# Immersive & Gamified Learning: Приемы (а)

Могу также порекомендовать обратиться к интересной субкультуре, которая подходит для интровертов! Уверен, что каждый человек так или иначе интересуется различными странными явлениями. Погрузитесь в среду сетевого сталкерства! 

Иногда обычным людям удавалось раскрыть преступления, которые полиция не могла раскрыть годами, опираясь только на OSINT и GEOINT (я мог бы привести здесь ссылки на сабреддиты, фильмы и новости, но поскольку мы с вами сейчас занимаемся OSINT, советую вам найти это самостоятельно).

<details>
<summary>Расширение</summary
<br />

- [Что такое нетсталкинг?](https://graph.org/What-is-Netstalking-Netstalking-Information-Survivors-04-06)
- [GEOGUESSR](https://somerandomstuff1.wordpress.com/2019/02/08/geoguessr-the-top-tips-tricks-and-techniques/)
- [SunCalc Calculator](http://suncalc.net/)
- [Mind Hacks - Psychological profiling, and mental health in OSINT investigations](https://youtu.be/104WpJm_eGk)
- [A Method for Teaching Open Source Intelligence (OSINT) Using Personalised Cloud-based Exercises](https://www.researchgate.net/publication/340023320_A_Method_for_Teaching_Open_Source_Intelligence_OSINT_Using_Personalised_Cloud-based_Exercises)
- [Метод имитации атак: пример](https://istrosec.com/service/attack-simulations/)

</details>

**Также смотрите:**

- [Alternate Reality Game](http://en.wikipedia.org/wiki/Alternate_reality_game)
- [reddit.com/r/ARG](http://reddit.com/r/ARG)
- [Net.art](https://officercia.mirror.xyz/VD9IDI8b4jVBHbr5uaGcI_ev6NEKZUuuOhL9IpEfpZs)
- [Applied Anthropology Research Methods](https://en.wikipedia.org/wiki/Applied_Anthropology_Research_Methods)
- [Размышления о становлении прикладного антрополога](https://www.jstor.org/stable/25605413)
- [Прикладная антропология (действительно, изучайте!)](https://oxfordre.com/anthropology/browse;jsessionid=469E22D5E27E148C59A31BA5715AD18D?page=3&pageSize=20&sort=titlesort&subSite=anthropology&t0=ORE_ANT%3AREFANT001)

Главное, что нужно помнить, - это ваше здоровье, оно превыше всего, не позволяйте своим принципам пошатнуться от увиденного. Вы - наблюдатель! Здесь хорошо помогает понять психологию [исследователей SCP](https://scp-wiki.wikidot.com/) (когда ничего не понятно, но научный метод помогает поставить все на свои места).

<details>
<summary>Расширение</summary
<br />

- [Netstalking: In-Depth](https://graph.org/What-is-Netstalking-Netstalking-Information-Survivors-04-06)
- [Как я нашел ранних разработчиков экосистемы Solana, используя тактику OSINT](https://telegra.ph/How-I-found-early-Solana-ecosystem-Developers-using-OSINT-tactics-01-04)
- [The Hitchhiker's Guide to Online Anonymity](https://web.archive.org/web/20220302223645/https://anonymousplanet.org/guide.html)
- [OpSec исследования и терминалы данных - вклад приветствуется](https://github.com/OffcierCia/Crypto-OpSec-SelfGuard-RoadMap)
- [Dork Yourself Before Someone Does!](https://yvesei.medium.com/dork-yourself-before-someone-does-aa49d0c1929f)

</details

Имейте в виду, что в этой части Глобального Интернета (я имею в виду OSINT вообще, а не только Net-stalking) процент людей, которые активно ищут проблемы или нуждаются в выражении своих эмоций, ничем не отличается от других мест!

- [Act like a Lion 🦁](https://twitter.com/jpurd17/status/1648669362910552067?s=20)
- [obsidian.md OSINT Templates](https://github.com/WebBreacher/obsidian-osint-templates)
- [OSINT Browser Extensions](https://github.com/cqcore/OSINT-Browser-Extensions)

**Наука + OSINT:**

- [Peering into the Mind: Psychological Profiling Through AI and Large Language Models...](https://www.linkedin.com/pulse/peering-mind-psychological-profiling-through-ai-large-smith)
- [Бритва Оккама](https://www.britannica.com/topic/Occams-razor)
- [Как работает бритва Оккама](https://science.howstuffworks.com/innovation/scientific-experiments/occams-razor.htm)
- [Occam's Razor as a Scientific Principle](https://study.com/learn/lesson/occams-razor-scientific-principle.html#:~:text=Occam's%20Razor%20is%20a%20principle%20which%20states%20that%20plurality%20should,used%20a%20little%20more%20loosely.)
- [CASE STUDY: Personality Profiling and the Power of OSINT](https://brightplanet.com/2016/11/09/case-study-receptiviti-power-osint/)
- [An Enriched Threat Intelligence Platform for improving OSINT correlation, analysis, visualization and sharing capabilities](https://www.sciencedirect.com/science/article/abs/pii/S2214212620308589)
- ["Дедукция" vs. "Индукция" vs. "Абдукция"](https://www.merriam-webster.com/words-at-play/deduction-vs-induction-vs-abduction)
- [The Difference Between Deductive and Inductive Reasoning](https://danielmiessler.com/p/the-difference-between-deductive-and-inductive-reasoning/)
- [Induction Rhetoric](https://www.studysmarter.co.uk/explanations/english/rhetoric/induction-rhetoric/)
- [Дедуктивное и индуктивное рассуждение: определение, различия и примеры](https://mundanopedia.com/economics/microeconomics/deductive-and-inductive-reasoning-methods/)

**Практика:**

> Итак, следуйте правилам OpSec и не делайте слишком много ошибок. Выполняйте свои действия с отдельного, изолированного устройства.

- [Privacy Concerns and Acceptance Factors of OSINT for Cybersecurity: A Representative Survey](https://petsymposium.org/popets/2023/popets-2023-0028.pdf)
- [What Are Heuristics?](https://www.verywellmind.com/what-is-a-heuristic-2795235)
- [Call of PSYOPS](https://steemit.com/news/@rusticus/call-of-psyops-video-games-as-psychological-warfare-in-the-21-century)
- [OSINT Trends for 2023 and Beyond](https://blog.sociallinks.io/osint-trends-for-2023-and-beyond/)
- [The Wide-Range Uses of OSINT in Military Intelligence](https://blog.sociallinks.io/uses-of-osint-in-military-intelligence/)
- [Объяснение общедоступной информации (PAI)](https://www.babelstreet.com/blog/pai-explained)
- [Общедоступная информация: цифровое поле боя](https://censa.net/publications/publicly-available-information-the-digital-battlefield/)
- [Better Utilizing Publicly Available Information](https://www.jstor.org/stable/pdf/resrep20002.7.pdf)
- [Практика науки: ложноположительные и ложноотрицательные результаты](https://manoa.hawaii.edu/exploringourfluidearth/chemical/matter/properties-matter/practices-science-false-positives-and-false-negatives)
- [False Positives and False Negatives in Information Security](https://www.guardrails.io/blog/false-positives-and-false-negatives-in-information-security/)
- [Minimize False Positives in Your OSINT Investigations](https://mediasonar.com/reports/minimize-false-positives-osint-investigations/)

**Смягчение когнитивных предубеждений и принятие решений при проведении OSINT:**.

Идеальных практиков-аналитиков не бывает, все ошибаются и попадают в сложные неоднозначные ситуации (хотя бы раз в жизни), тем более в условиях острой интенсивной и хронической рабочей перегрузки. И знать и понимать такие ситуации практику-аналитику совершенно необходимо. 

Когнитивные уязвимости (в устоявшемся понимании) - это подверженность и/или склонность к дефектам мышления: значимым когнитивным искажениям, ошибочным убеждениям, когнитивным предубеждениям (предрассудкам) или стереотипным паттернам мышления, которые создают основу для предрасположенности человека к когнитивным сбоям и приводят к искажениям и дисфункциям [мыслительных процессов](https://telegra.ph/Cognitive-vulnerabilities-of-the-practitioner-analyst-04-17).

- [Когнитивные уязвимости практикующего аналитика](https://telegra.ph/Cognitive-vulnerabilities-of-the-practitioner-analyst-04-17)
- [Cognitive Bias Mitigation](https://www.researchgate.net/publication/317702457_Cognitive_Bias_Mitigation)
- [Cognitive bias mitigation - Wiki](https://en.m.wikipedia.org/wiki/Cognitive_bias_mitigation)
- [Recognizing and Mitigating Cognitive Biases: A Threat to Objectivity](https://www.theiia.org/en/content/communications/press-releases/2022/may/new-recognizing-and-mitigating-cognitive-biases-a-threat-to-objectivity/)
- [Cognitive Bias Mitigation: How to make Decision-Making Rational?](https://ideas.repec.org/p/fau/wpaper/wp2020_01.html)
- [The Impact of Cognitive Biases on Professionals' Decision-Making: A Review of Four Occupational Areas](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8763848/)
- [HARKing: выдвижение гипотез после того, как известны результаты](https://pubmed.ncbi.nlm.nih.gov/15647155/)
- [Гипотеза после того, как результаты известны (HARKing)](https://embassy.science/wiki/Theme:Cc742a7b-826d-4201-b33e-457f2ef79fb9) & [Paper](https://www2.psych.ubc.ca/~schaller/528Readings/Kerr1998.pdf)
- [Когнитивная уязвимость](https://en.m.wikipedia.org/wiki/Cognitive_vulnerability)
- [Почему мы фокусируемся на одной характеристике для сравнения при выборе между альтернативами?](https://thedecisionlab.com/biases/take-the-best-heuristic) & [Подробнее](https://fourweekmba.com/take-the-best-heuristic/)
- [План IARPA по взлому мозгов хакеров](https://fcw.com/security/2023/04/iarpas-plan-hack-brains-hackers/385123/)
- [Are Cyber Attackers Thinking Fast and Slow?](https://journals.sagepub.com/doi/pdf/10.1177/1071181319631096)
- [DMBOK2](https://www.dama.org/cpages/body-of-knowledge)
- [US Comission Report - 2005](https://govinfo.library.unt.edu/wmd/about.html)
- [5 когнитивных предубеждений, которые могут повлиять на ваши OSINT-расследования](https://www.linkedin.com/pulse/5-cognitive-biases-could-affect-your-osint-investigations-?utm_source=share&utm_medium=guest_mobile_web&utm_campaign=copy)

Большинство из нас испытывают "интуицию", которую не могут объяснить, например, мгновенно любя (или ненавидя) новую недвижимость во время поиска жилья или делая мгновенные выводы при знакомстве с новыми людьми. Теперь исследователи утверждают, что эти чувства (или интуиция) - реальны, и мы должны относиться к своим предчувствиям серьезно. 

Не ограничивайте себя одним подходом, не бойтесь экспериментировать, но помните, что результаты таких подходов всегда должны быть **перепроверены**. Они служат скорее для обучения, чем в качестве реальных рекомендаций для исследователей. Посетите следующие сайты:

- [Intuition Is More Than Just A Hunch, Says New Research](https://www.sciencedaily.com/releases/2008/03/080305144210.htm)
- [Intuition as Emergence: Bridging Psychology, Philosophy and Organizational Science](https://www.frontiersin.org/articles/10.3389/fpsyg.2021.787428/full)
- [Анализ разведданных: структурированные методы или интуиция?](https://www.academia.edu/4259879/Intelligence_Analysis_Structured_Methods_or_Intuition)
- [The Potential of Integrating Intelligence and Intuition](https://www.thecipherbrief.com/the-potential-of-integrating-intelligence-and-intuition)
- [Социальная инженерия и защита дорогостоящих целей](https://www.hensoldt-analytics.com/2023/01/23/social-engineering-osint/)
- [Trace My Shadow Game](https://myshadow.org/trace-my-shadow)
- [О чем мы говорим, когда говорим о OSINT](https://www.authentic8.com/blog/definition-of-osint)
- [Publicly Available Information: The Secret to Unclassified Data, Part I](https://overthehorizonmdos.wpcomstaging.com/2019/04/08/publicly-available-information-the-secret-to-unclassified-data-part-i/) & [Copy](https://web.archive.org/web/20191117062938/https://othjournal.com/2019/04/08/publicly-available-information-the-secret-to-unclassified-data-part-i/)

**А также:**

**Согласно [wondersmith_rae](https://wondersmithrae.medium.com/training-yourself-to-be-an-analytical-thinker-476bdb7e7c99)**: В классической риторике для анализа риторических вопросов издавна использовались "элементы обстоятельств", созданные Аристотелем. Они применимы и к современному анализу и могут быть положены в основу расследования. **(Кто, что, когда, где, почему, каким образом, какими средствами)**.

Сокращенный, но не менее ценный вариант этих элементов называется "5W's and an H", или Who, What, When, Where, Why, and How. Эти вопросы используются в риторике, религиоведении, полицейских расследованиях, журналистике и юристами со времен Древней Греции. Говорят, что расследование не может быть по-настоящему полным, пока не будут даны ответы на все вопросы W и H. 

Применяя те же элементы к нашим OSINT-расследованиям, мы можем задавать и отвечать на аналогичные вопросы. Ответив на 5 "W", мы начинаем составлять рассказ на основе собранных данных. Теперь нам, аналитикам, предстоит в сжатом виде соединить все точки. Загвоздка в том, что каждый, кто занимался исследованиями, знает, что, когда информация начинает раскрываться, легко застрять в кроличьей норе. 

- [The Power of Shutting Down Your Senses: How to Boost Your Creativity and Have a Clear Mind](https://buffer.com/resources/the-power-of-shutting-down-your-senses-how-to-boost-your-creativity-and-have-a-clear-mind/amp/)
- [Training Yourself to be an Analytical Thinker](https://wondersmithrae.medium.com/training-yourself-to-be-an-analytical-thinker-476bdb7e7c99)
- [Использование состояния сознания OSINT для более эффективного расследования в Интернете](https://www.sans.org/webcasts/atmic-talk-osint-mind-state-online-investigations-114115/)
- [Последние тенденции в SOCMINT, OSINT и киберпсихологии](https://www.toddington.com/wp-content/uploads/1Day_OSINT_Masterclass-1-1.pdf)
- [5 когнитивных предубеждений, которые могут повлиять на ваши OSINT-расследования](https://www.liferaftinc.com/blog/5-cognitive-biases-that-could-affect-your-osint-investigations)
- [Citizen OSINT Analysts: Motivations of Open-Source Intelligence Volunteers](https://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1670900&dswid=-6049)
- [Новое руководство по расследованию и составлению карты преступников в расследованиях с использованием открытых источников](https://piac.asn.au/2023/03/29/new-guide-on-investigating-and-mapping-perpetrators-in-open-source-investigations/)
- [Зарубежный бизнесмен умер и оставил мне $4,6 млн, поэтому я использовал OSINT и социальную инженерию, чтобы обмануть мошенника](https://hatless1der.com/an-overseas-businessman-died-and-left-me-4-6m-so-i-used-osint-social-engineering-to-scam-a-scammer/)
- [Cchatgpt-unlock-geolocation-data](https://www.digitaldigging.org/p/4-chatgpt-unlock-geolocation-data)
- [Telegram-osint-vm-part-2](https://www.cqcore.uk/telegram-osint-vm-part-2/)
- [Studies in Intelligence](https://t.me/devil_may_spy/160)
- [Safeguarding OSINTers: Shielding Against Disinformation Manipulation](https://osintteam.blog/safeguarding-osinters-shielding-against-disinformation-manipulation-dfbbfbf1db08)
- [Unveiling the Digital Detective: Essential OSINT Tools and Techniques for Investigators.](https://osintteam.blog/unveiling-the-digital-detective-essential-osint-tools-and-techniques-for-investigators-adf486ad2ccd)

После того как вы сможете выделить информацию, отсортировать ее, можно приступать к практике. Как известно, **хорошая практика требует хорошей мотивации**! Вам нужно знать только одно: люди думают, что интеллект фиксирован, но это не так. Ваш мозг подобен мышце: чем больше вы его используете, тем больше он растет. Образование - это уже не разовая акция, а опыт всей жизни.

<details>
<summary>Расширение</summary
<br />

- [Beginners Field Guide: Where & How to Learn OSINT](https://medium.com/the-sleuth-sheet/beginners-field-guide-where-how-to-learn-osint-bd2e11469f31)
- [Ловушки, используемые кибердетективами...](https://medium.com/@ibederov_en/traps-used-by-cyber-detectives-c778b4853f1a)
- [Расследование MAC-адресов](https://t.me/ibederov_en/18)
- [The ULTIMATE Guide to Writing Intelligence Reports...](https://www.intelligence101.com/the-ultimate-guide-to-writing-intelligence-reports-complete-with-templates-examples/)
- [Business Resilience Resources](https://start.me/p/wMgzM5/business-resilience)
- [Рабочий процесс персонального OSINT-расследования с точки зрения конфиденциальности](https://www.osintme.com/index.php/2022/08/31/person-osint-investigation-workflow-from-a-privacy-perspective/)
- [Setting Your Moral Compass: A Workbook for Applied Ethics in OSINT](https://ethicaljournalismnetwork.org/setting-your-moral-compass-a-workbook-for-applied-ethics-in-osint)
- [Reddit Bureau of Investigation](https://www.reddit.com/r/RBI/)
- [The Dark Arts of OSINT](https://av.tib.eu/en/media/38959)
- [OSINT Wiki](https://www.reddit.com/r/OSINT/wiki/index/)
- [OSINT Map](https://cipher387.github.io/osintmap)

</details>

**Также смотрите:**

> [Последние исследования показывают](https://4discovery.com/2019/09/10/litigating-in-an-e-world-e-discovery-forensics-and-open-source-intelligence-in-legal-research/), что более 97% предприятий хранят данные в "облаке". Узнайте, как определять потенциальные источники "облачных" данных, направлять запросы на обнаружение и применять судебные запреты, а также как сохранять, собирать, фильтровать, проверять и создавать "облачные" данные.

> [Информация, имеющая отношение к вашему делу](https://4discovery.com/2019/09/10/litigating-in-an-e-world-e-discovery-forensics-and-open-source-intelligence-in-legal-research/), находится в Интернете, обычно скрываясь от посторонних глаз. Деловые документы, регистрации доменных имен, веб-сайты, личные данные пользователей, сообщения в социальных сетях, фотографии и видеозаписи находятся всего лишь на расстоянии поискового запроса. Знаете ли вы, как их найти? Узнайте, как информация из открытых источников может влиять на широкий круг вопросов и как эффективно определять источники информации и осуществлять поиск данных из открытых источников.

- [Язык преступников с точки зрения психолингвистики](https://www.paperdue.com/essay/criminals-language-from-a-psycholinguistics-1851)
- [ИСПОЛЬЗОВАНИЕ АНАЛИЗА ЯЗЫКА ДЛЯ ВЫЯВЛЕНИЯ И ОЦЕНКИ ПРЕСТУПНИКОВ](https://www.researchgate.net/publication/340985509_FORENSIC_PSYCHOLINGUISTICS_USING_LANGUAGE_ANALYSIS_FOR_IDENTIFYING_AND_ASSESSING_OFFENDERS)
- [Forensic Psycholinguistics Using Language Analysis for Identifying and Assessing](https://criminalprofiling.com/forensic-psycholinguistics-using-language-analysis-for-identifying-and-assessing/)
- [The Ultimate Guide to Human Intelligence (HUMINT)](https://www.intelligence101.com/the-ultimate-guide-to-human-intelligence-humint/)
- [Undermining social engineering using open source intelligence gathering](https://www.researchgate.net/publication/283250856_Undermining_social_engineering_using_open_source_intelligence_gathering)
- [Signal OSINT - SIGINT](https://worldwidescience.org/topicpages/o/osint+signals+intelligence.html)
- [E-Discovery, Forensics, and Open Source Intelligence in Legal Research](https://4discovery.com/2019/09/10/litigating-in-an-e-world-e-discovery-forensics-and-open-source-intelligence-in-legal-research/)
- [From Dissent to OSINT? Понимание, влияние и защита ролей, репутации и доходов](https://complexdiscovery.com/from-dissent-to-osint-understanding-influencing-and-protecting-roles-reputation-and-revenue/)
- [The Basics: What is e-Discovery?](https://cdslegal.com/knowledge/the-basics-what-is-e-discovery/)
- [Система организации, сбора и представления разведданных из открытых источников](https://link.springer.com/article/10.1007/s42488-022-00068-4)

# Обучение и практика

**Хорошие учебные материалы:**

- [Python для OSINT за 21 день](https://github.com/cipher387/python-for-OSINT-21-days)
- [Googledorking](https://tryhackme.com/room/googledorking) + [dorksearch.com](https://dorksearch.com/)
- [Searchlightosint](https://tryhackme.com/room/searchlightosint)
- [Shodan](https://tryhackme.com/room/shodan)
- [Geolocatingimages](https://tryhackme.com/room/geolocatingimages)
- [Instruments-on-the-radio-waves](https://telegra.ph/Instruments-on-the-radio-waves-02-01) + [websdr.org](https://websdr.org) + [try 😅](http://websdr.ewi.utwente.nl:8901/?tune=4625)
- [Somesint](https://tryhackme.com/room/somesint)
- [osintframework.com](https://osintframework.com)
- [OSINT At Home YouTube Playlist](https://www.youtube.com/playlist?list=PLrFPX1Vfqk3ehZKSFeb9pVIHqxqrNW8Sy)
- [myosint.training](https://www.myosint.training/)
- [Awesome Cyber Skills](https://github.com/joe-shenouda/awesome-cyber-skills)
- [Awesome Maps](https://github.com/simsieg/awesome-maps)

Вот очень хорошая игра для разминки мозгов, которая поможет тренировать ассоциативное мышление - очень важный навык для всех, кто занимается [OSINT](https://twitter.com/hashtag/OSINT?src=hashtag_click):

- [Wikipedia:Wiki Game](https://en.wikipedia.org/wiki/Wikipedia:Wiki_Game)

Когда я был маленьким, мы играли в "5 шагов до Рагнарока" - цель была найти страницу об этом мифе за 5 шагов (5 кликов) с любой случайной страницы Википедии! 🙂 

**Следите за ведущими специалистами по OSINT:**

- [twitter.com/UKOSINT](https://twitter.com/UKOSINT) - новости, инструменты, шутки
- [twitter.com/dutch_osintguy](https://twitter.com/dutch_osintguy) - известный специалист, спикер
- [twitter.com/jakecreps](https://twitter.com/jakecreps) - каждый четверг публикует потрясающие инструменты
- [twitter.com/OSINTtechniques](https://twitter.com/OSINTtechniques) - следит за цифровыми хлебными крошками
- [The Sleuth Sheet](https://medium.com/the-sleuth-sheet)
- [OSINT Essentials](https://osintessentials.medium.com/)
- [Sector035](https://medium.com/@sector035) - неделя в OSINT
- [Игорь С. Бедеров](https://medium.com/@ibederov_en) - Шерлок Холмс цифровой эпохи...
- [twitter.com/OSINTHK](https://twitter.com/OSINTHK) - волонтеры, использующие OSINT
- [A global OSINT Community](https://osintfr.com/en/home/) - сообщество OSINT из Франции
- [twitter.com/OSINT_Research](https://twitter.com/OSINT_Research) - инструменты и потрясающие данные
- [twitter.com/OSINTtechniques](https://twitter.com/OSINTtechniques) - инструменты и потрясающие данные
- [twitter.com/OsintJobs](https://twitter.com/OsintJobs) - вакансии в OSINT
- [www.reddit.com/r/OSINT](https://www.reddit.com/r/OSINT) - самый большой тематический subReddit
- [каналы о OSINT, хакинге, безопасности и т.д.](https://telegra.ph/Channels-about-OSINT-Hacking-Security-and-so-on-04-19)

**Другие ресурсы:**

> [Помимо своей традиционной функции - обеспечения возможности принятия менее просчитанных решений,](https://www.researchgate.net/publication/331073990_Digital_Open_Source_Intelligence_and_International_Security_A_Primer) аудитория современной разведки выходит за рамки руководства государства или корпорации и расширяется до широких слоев населения. Это уже не просто механизм предупреждения, но и резервуар ноу-хау и импровизации для решения вопросов во время неожиданных кризисов.
 
- [Awesome OSINT + Crypto](https://github.com/aaarghhh/awesome_osint_criypto_web3_stuff)
- [Google Hacking](https://seckrd.com/google-hacking)
- [GOSI: GIAC Open Source Intelligence](https://www.giac.org/certification/open-source-intelligence-gosi)
- [SEC487: Сбор и анализ разведданных из открытых источников (OSINT)](https://www.sans.org/cyber-security-courses/open-source-intelligence-gathering/)
- [Inteltechniques.net](https://www.inteltechniques.net/)
- [Лекция по ИТ-безопасности](https://github.com/bkimminich/it-security-lecture/)
- [r4ven Tool](https://github.com/spyboy-productions/r4ven)
- [Unredacter](https://github.com/BishopFox/unredacter)
- [forensicdots.de](https://www.forensicdots.de/)
- [Meta-secret App](https://github.com/meta-secret)
- [Image Research OSINT](https://github.com/cqcore/Image-Research-OSINT)
- [15 инструментов, которые вы должны знать как аналитик по безопасности](https://osintteam.blog/15-tools-you-should-know-as-a-security-analyst-f95007e94d99)
- [Portable Secret App](https://mprimi.github.io/portable-secret/)
- [Open Source Intelligence Techniques](https://inteltechniques.com/book1.html)
- [The Internet Intelligence & Investigation Handbook](https://www.amazon.com/Internet-Intelligence-Investigation-Handbook-practical/dp/B096TJMV7J)
- [NATO OSINT HandBook](https://github.com/lawsecnet/OPSEC/blob/master/NATO%20OSINT%20Handbook%20v1.2%20-%20Jan%202002.pdf)
- [osintnewsletter.com](https://osintnewsletter.com/)
- [Geolocation OSINT](https://github.com/cqcore/Geolocation-OSINT)
- [geodetective.io](https://geodetective.io/)
- [Yet another awesome OSINT book](https://t.me/osintkanal/2049)
- [Social Media OSINT](https://github.com/cqcore/Social-Media-OSINT)
- [Fascinating Search Engines That Search for Faces](https://www.makeuseof.com/tag/3-fascinating-search-engines-search-faces/)
- [OSINT Tools MegaList](https://pastebin.com/z0FUgiGb)
- [Future of OSINT: People Searching with ChatGPT](https://dorksearch.com/blog/future-of-osint-people-searching/)
- [Geolocation: At The Retail Park](https://nixintel.info/osint/geolocation-at-the-retail-park/)

**Инструменты (AI, ChatGPT, ML, другие):**.

> [В последние годы интерес общественности к сбору и анализу разведывательной информации из открытых источников](https://www.sans.org/webcasts/atmic-talk-osint-mind-state-online-investigations-114115/) растет в геометрической прогрессии. По мере роста этого интереса все больше и больше OSINT-расследований полагаются на инструменты и автоматизацию, оставляя процесс анализа позади. Следует рассматривать OSINT как мыслительный процесс. Состояние сознания OSINT - это ключ к отслеживанию шагов расследования, выбору правильных инструментов и источников, анализу данных и созданию отчетов для получения оперативной информации!

- [OSINT Tools Map](https://metaosint.github.io/chart)
- [Sherlock](https://github.com/sherlock-project/sherlock)
- [gpt.censys.io](https://gpt.censys.io/)
- [ChatGeoPT](https://github.com/earth-genome/ChatGeoPT)
- [ChatGPT для OSINT: пример](https://t.me/osintkanal/2009) | Совет: Используйте [deepl.com](https://www.deepl.com/translator)
- [Emoji OSINT](https://www.dutchosintguy.com/post/cryptography-osint-can-you-read-emoji)
- [Advangle](http://advangle.com/)
- [searchcode.com](https://searchcode.com/)
- [dorkgpt.com](https://www.dorkgpt.com/)
- [OSINT & ChatGPT: 103 идеи](https://t.me/irozysk/9377)
- [OSINT + AI](https://github.com/jiep/offensive-ai-compilation)
- [OSINT - SAN](https://github.com/Bafomet666/OSINT-SAN)
- [OSINT Buddy](https://github.com/jerlendds/osintbuddy)
- [ChatGPT: The AI-Powered Secret Weapon for OSINT](https://blog.gopenai.com/chatgpt-the-ai-powered-secret-weapon-for-osint-133a68d8302e)
- [Не относитесь к инструменту как к серебряному булату для решения всех задач!](https://osintessentials.medium.com/the-one-osint-tool-you-must-have-to-supercharge-your-investigations-94f5015b6318)
- [The New OSINT Cheat Code: ChatGPT](https://medium.com/the-sleuth-sheet/the-new-osint-cheat-code-chatgpt-cd54c190fa11)
- [Harnessing the Power of ChatGPT for OSINT: A Practical Guide to Your AI OSINT Assistant](https://hackernoon.com/harnessing-the-power-of-chatgpt-for-osint-a-practical-guide-to-your-ai-osint-assistant)
- [Awesome Free ChatGPT](https://github.com/LiLittleCat/awesome-free-chatgpt)
- [Offensive AI](https://github.com/jiep/offensive-ai-compilation)
- [Bitcoin Investigation Manual AML](https://www.amazon.com/Bitcoin-Investigation-Manual-AML-Money-Laundering/dp/1077484070)

# Выбор пути...

Кому-то понравится [анализировать изображения](https://29a.ch/photo-forensics/#forensic-magnifier), [спутниковые снимки](https://spectator.earth/), вычислять время и место по [углу тени от фотографии](https://www.suncalc.org/#/40.1789,-3.5156,3/2022.05.05/12:15/1/3) или измерять размеры горных [пиков](https://www.peakfinder.org/), чтобы проводить частные детективные расследования. Или, скажем, [заниматься OSINT в криптовалюте](https://graph.org/TX-Analysis-tools-04-19), например, в этом случае вашей мотивацией будут деньги и самореализация... Или [поиск редких историй](https://www.atlasobscura.com/articles/buying-volcanoes-robert-ripley-paricutin-whakaari.amp) даже!

[Читайте мой канал, если вам нравится эта тема](https://t.me/officer_cia)... А кто-то даже может попасть в [AD-INT](https://medium.com/@ibederov_en/mac-address-osint-e539504ae925), который сейчас развивается с каждым днем. Для обучения навыкам работы с GEOINT рекомендую обратить внимание на [geoguessr.com](https://geoguessr.com/) и [whereami.io](https://whereami.io/).

**Взгляните на эту потрясающую Mind-Map:**.

- [Click on me!](http://files.mtg-bi.com/MindMap.jpg)

**Исследуйте терминалы данных:**

- [Open-Source Intelligence (OSINT) Reconnaissance](https://z3r0trust.medium.com/open-source-intelligence-osint-reconnaissance-9f0bafd672b2)
- [Коллекция из нескольких сотен онлайновых инструментов для OSINT](https://github.com/cipher387/osint_stuff_tool_collection)
- [Эта страница для всех, кто любит разведку с открытым исходным кодом](https://start.me/p/DPYPMz/the-ultimate-osint-collection)
- [Start.me + OSINT](https://start.me/p/Pwy0X4/osint-inception)
- [Open-Source Intelligence (OSINT) in 5 Hours - Full Course - Learn OSINT!](https://youtu.be/qwA6MmbeGNo)
- [Follow!](https://twitter.com/Sector035)
- [myosint.training/courses/](https://myosint.training/courses/)
- [Сравнение OSINT-инструментов для борьбы с типосквоттингом, таких как DNSTwist, DNSRazzle, с мониторингом типосквоттинга от Bolster](https://securityboulevard.com/2022/02/comparing-osint-typosquatting-tools-like-dnstwist-dnsrazzle-against-bolsters-typosquatting-monitoring/)
- [* Что это за шрифт?](https://osintessentials.medium.com/wtf-be0de2230ed2)
- [OSINT Cheatsheet](https://thekaiz3n.com/cheatsheet/2022/01/12/osint.html)
- [Применение абдуктивного и ретродуктивного умозаключений для разработки и анализа теоретически ориентированных социологических исследований](https://journals.sagepub.com/doi/10.5153/sro.2819)
- [Abduction as an Aspect of Retroduction](http://www.commens.org/encyclopedia/article/chiasson-phyllis-abduction-aspect-retroduction)
- [Абдукция как аспект ретродукции - 2](https://www.degruyter.com/document/doi/10.1515/semi.2005.2005.153-1-4.223/html?lang=en)
- [Абдуктивные рассуждения](https://en.wikipedia.org/wiki/Abductive_reasoning)

Возможно, вы даже захотите деанонимизировать пользователей Telegram ([читайте этот канал](https://t.me/ibederov_en)) или, наоборот, присоединиться к [counter-OSINT](https://github.com/soxoj/counter-osint-guide-en) братьям. Но при этом я призываю вас не забывать о таких ключевых навыках, как поиск информации, информационная аналитика и применение информации...

<details
<summary>Расширение</summary
<br />

- [Counter OSINT Guide](https://github.com/soxoj/counter-osint-guide-en)
- [HUMINT VS Social Engineering Resources](https://telegra.ph/HUMINT-VS-Social-Engineering-Resources-03-24)
- [От забвения к озарению. Часть 1 | На линии творчества и обороны](https://mirror.xyz/0xc34B1730BA53abD717a1E57A358F39C046053581/Ra_UVvUwOrO5W56k2QpP4jKhYAGMhsNnfvwrdKWQ1EI)
- [Как научиться чему угодно](https://twitter.com/sahilbloom/status/1662453471608446976)

</details

Выделю для вас несколько основных советов - оценивайте информацию по разным критериям, всегда знайте свои "базовые установки" - это полезно для психического здоровья, то, что вы находите, не должно разрушать ваши устои! Практикуйте это, делайте это в своей повседневной жизни, применяйте OSINT там, где это кажется неочевидным, как это описано ниже:

- [5 Ways OSINT Can Help Your Career! - Knowmad OSINT](https://knowmad-osint.com/5-ways-osint-can-help-your-career/)
- [Ontology Population for Open-Source Intelligence](https://ceur-ws.org/Vol-2161/paper27.pdf)
- [Cryptography & OSINT - The fundamentals](https://www.dutchosintguy.com/post/cryptography-osint-the-fundamentals)
- [Использование символов нулевой ширины для скрытия секретных сообщений в тексте (и даже для раскрытия утечек)](https://null-byte.wonderhowto.com/how-to/use-zero-width-characters-hide-secret-messages-text-even-reveal-leaks-0198692/)
- [OSINT: инструмент поиска по имени пользователя](https://www.secjuice.com/osint-username-search-tool/)
- [Geolocation Challenge Writeup](https://osintteam.blog/geolocation-challenge-writeup-1cd5d5aa299f)
- [All About Web Recon & OSINT](https://github.com/pr0xh4ck/web-recon)
- [PainlessPeek Tool - GEOINT](https://github.com/adacable/painlessPeek)
- [ChatGPT-osint Tool](https://github.com/gigz/gpt-osint)
- [Querytool](https://github.com/oryon-osint/querytool)

# Immersive & Gamified Learning: Игры (b)

Конечно, вступайте в сообщества и общайтесь, общайтесь! Ниже я упомянул только англоязычные сообщества, но есть и местные, поищите их сами. Я уверен в вас на 100%! У вас все получится! Любите ли вы проводить время с друзьями? Если да, то попробуйте сыграть в Dozor или Encounter (или любую другую ночную игру, основанную на взломе кодов или геолокации, или эскапологии, или взломе замков) вместе! 

- [Командная ночная игра DozoR](https://en.wikipedia.org/wiki/Dozor)
- [Codebreaking](https://en.m.wikipedia.org/wiki/Codebreaking)
- [GeoCaching](https://en.m.wikipedia.org/wiki/Geocaching)
- [Escapology](https://en.wikipedia.org/wiki/Escapology)
- [Lock-Picking](https://www.art-of-lockpicking.com/how-to-pick-a-lock-guide/)

**Посмотрите:**

- [Ingress](https://www.ingress.com/)
- [Geocaching](https://education.nationalgeographic.org/resource/geocaching/)
- [Escapology](https://www.escapology.com/en)
- [Лучший инструмент для сбора информации 🔎](https://github.com/Moham3dRiahi/Th3inspector)
- [Крутая разведка](https://github.com/ARPSyndicate/awesome-intelligence)

**OSINT-Games:**

- [kasescenarios.com](https://kasescenarios.com/)
- [Sourcing.games](https://sourcing.games/)
- [OSINT Exercise #018](https://gralhix.com/list-of-osint-exercises/osint-exercise-018/)
- [osint.games](https://www.osint.games/)
- [spyingchallenge.com](http://spyingchallenge.com/)
- [10 решений OSINT CTF для начинающих](https://geckosint.medium.com/10-beginner-osint-ctf-solutions-ae89e557a4b)
- [More OSINT CTFs](https://warnerchad.medium.com/osint-ctfs-9993129c10c7)
- [OSINT Challenges List - Reddit](https://www.reddit.com/r/OSINT/comments/vu9i43/looking_for_osint_challenges_ctfs/)
- [2 отличных инструмента для обучения OSINT](https://nixintel.info/osint/two-great-osint-training-tools/)
- [OSINT-Related Games - Reddit](https://www.reddit.com/r/OSINT/comments/i62fhp/osint_related_games/)
- [10 лучших игр, основанных на определении местоположения](https://www.digitaltrends.com/gaming/best-location-based-gps-games/)
- [7 геолокационных игр, которые заставят вас исследовать природу](https://www.samsung.com/uk/explore/entertainment/7-geolocation-games-to-get-you-exploring-the-outdoors/)
- [Location-based game](https://en.wikipedia.org/wiki/Location-based_game)
- [Что такое охота на лис в Ham Radio?](https://hamradioplanet.com/what-is-a-fox-hunt-in-ham-radio/)
- [9 виртуальных игр, в которые можно играть, когда вы не можете быть вместе](https://www.realsimple.com/work-life/entertainment/virtual-games)

Внимательно изучите эти ресурсы и возвращайтесь к ним по мере путешествия по миру шершней, не забывайте о корнях. Эта статья не отвечает на вопросы, а скорее ставит риторические вопросы, чтобы побудить вас задуматься о чем-то!

<details>
<summary>Расширение</summary
<br />

- [Comprehensive Counter OSINT](https://github.com/soxoj/counter-osint-guide-en)
- [Counter OSINT](https://github.com/CScorza/OSINTAnonymous)
- [Open Source Intelligence Investigation: From Strategy to Implementation](https://www.researchgate.net/publication/321531302_Open_Source_Intelligence_Investigation_From_Strategy_to_Implementation)
- [Разведка в эпоху Интернета: Возникновение и эволюция разведки с открытым исходным кодом (OSINT)](https://www.sciencedirect.com/science/article/abs/pii/S0747563211002585)
- [A Guide to Open-Source Intelligence (OSINT)](https://greydynamics.com/a-guide-to-open-source-intelligence-osint/)
- [Интеллектуальные доказательства: Использование разведданных из открытых источников (OSINT) в уголовном процессе](https://www.researchgate.net/publication/309015913_Intelligent_evidence_Using_open_source_intelligence_OSINT_in_criminal_proceedings)
- [The Intelligence Cycle: Generating OSINT from OSINF](https://www.skopenow.com/news/the-intelligence-cycle-creating-osint-from-osinf)

</details

Поскольку это нетипичное руководство, я считаю целесообразным предложить вам список телепередач и фильмов, которые, по моему мнению, так или иначе связаны с OSINT:

- [OSINT Films List](https://www.aware-online.com/en/osint-films/)
- [ПОИСК](https://youtu.be/3Ro9ebQxEOY)
- [The Most Hated Man on the Internet](https://youtu.be/ySFpxEdKxMw)
- [Why Did You Kill Me?](https://youtu.be/QEXV8Rif8Vc)
- [Web of Make Believe: Death, Lies and the Internet](https://youtu.be/Z_l702HNPAA)
- [Don't F**k With Cats: Hunting an Internet Killer](https://youtu.be/x41SMm-9-i4)
- [Reddit Ruined Their Lives: The Innocent Victims Of Internet Justice](https://youtu.be/hi14dP5Rdm0)
- [Cyber Hell: Exposing an Internet Horror](https://youtu.be/hpceNxQASKw)
- [Who Am I - Kein System ist sicher](https://www.imdb.com/title/tt3042408/)
- [The History of Analog Horror](https://youtu.be/-I_4ph-L19U)
- [Dark Web: Cicada 3301](https://www.imdb.com/title/tt8110246/)
- [Фильм 43 (LOL)](https://youtu.be/A9fBCkwDW8c)
- [Mr. Robot](https://www.imdb.com/title/tt4158110/)
- [Открытые окна](https://m.imdb.com/title/tt2409818/)
- [Män som hatar kvinnor](https://m.imdb.com/title/tt1132620/)

**Ссылки:**

> [Open Source Intelligence, обычно называемая OSINT,](https://www.skopenow.com/news/osintforgood-the-philanthropic-application-of-osint) - это сбор, обобщение и анализ общедоступной информации. OSINT - это технология, разработанная в секторе национальной безопасности, которая в настоящее время распространилась на целый ряд секторов, включая правоохранительные органы, журналистику, корпоративную безопасность, академические исследования и юридический сектор. OSINT также может использоваться для поддержки благотворительных целей!

- [Любые крутые фильмы, связанные с OSINT?](https://www.reddit.com/r/OSINT/comments/owxp7r/any_cool_movies_related_to_osint/)
- [Список фильмов о OSINT](https://twitter.com/AllForOsint/status/1581244439271350272)
- [OSINT Movie Time for the Holidays](https://medium.com/@sector035/osint-movie-time-for-the-holidays-7a5f74f18f44)
- [Лучшие фильмы о OSINT](https://medium.com/@ibederov_en/the-best-films-about-osint-5c3ab580f56)
- [Разведывательное телевидение и фильмы о шпионах, шпионаже, разведке и шпионаже](https://www.intelligence101.com/my-favourite-intelligence-television-and-movies-about-spies-spying-intelligence-and-espionage/)
- [DOD film list - spreadsheet version](https://www.spyculture.com/dod-film-list-spreadsheet-version/)
- [Week in OSINT 2020-12](https://sector035.nl/articles/2020-12)
- [ARG SubReddit](https://www.reddit.com/r/ARG/)
- [OSINT SubReddit](https://www.reddit.com/r/OSINT/)
- [Blockchain OSINT](https://www.forensicxs.com/blockchain-osint-decentraland/)
- [John Doe Strikes Again](https://hamzaharooon.medium.com/john-doe-strikes-again-n00bzctf-osint-d2122d54c508)
- [Measurement and Signature Intelligence (MASINT)](https://irp.fas.org/program/masint.htm)
- [One Search To Rule Them All - Boolean Searches For Images](https://nixintel.info/osint/one-search-to-rule-them-all-boolean-searches-for-images/)
- [Руководство по созданию SOC Puppet](https://medium.com/the-sleuth-sheet/soc-puppet-creation-guide-888768dce96e)
- [Три типа разведданных для разведки угроз: A Comprehensive Guide](https://medium.com/the-sleuth-sheet/the-three-types-of-intelligence-for-threat-intelligence-a-comprehensive-guide-e8bbf1f26164)
- [Unmasking OSINT: A Data Aggregation Journey](https://medium.com/@VEEXH/unmasking-osint-a-data-aggregation-journey-14bea88eb045)

**Книжная полка OSINT:**

- [Мои недавно прочитанные книги по OSINT и безопасности - рекомендации](https://www.osintme.com/index.php/2021/04/30/my-recently-read-osint-security-books-recommendations/)
- [geodetective.io Training](https://geodetective.io/)
- [The Open Source Intelligence Analysis Bookshelf](https://medium.com/the-sleuth-sheet/the-open-source-intelligence-analysis-bookshelf-942dc05a16bd)
- [7 книг по OSINT, которые должен прочитать каждый аналитик](https://www.liferaftinc.com/blog/7-osint-books-every-analyst-should-read?hs_amp=true)
- [Книги Майкла Баззелла](https://inteltechniques.com/book1.html)
- [Что читать, чтобы понять, что такое разведка и шпионаж](https://www.wgu.edu/career-guide/information-technology/osint-career.html#openSubscriberModal)
- [The Official CIA Manual of Trickery and Deception - H. Keith Melton, Robert Wallace (2009)](https://www.bokus.com/bok/9780061943331/official-cia-manual-of-trickery-and-deception/) & [Link](https://www.google.se/books/edition/The_Official_CIA_Manual_of_Trickery_and/LbrzMtkyCGUC?hl=ru&gbpv=1&dq=inauthor:%22H.+Keith+Melton%22&printsec=frontcover) & [Link2](https://www.bokus.com/bok/9780061943331/official-cia-manual-of-trickery-and-deception/)
- [Offensive OSINT Tools](https://github.com/wddadk/Offensive-OSINT-Tools)
- [Spycraft](https://books.google.se/books/about/Spycraft.html?id=eJg0WV6sGlEC&redir_esc=y) & [Link](https://www.google.se/books/edition/Spycraft/RHWH7gVIO9cC?hl=ru&gbpv=1&dq=inauthor:%22H.+Keith+Melton%22&printsec=frontcover)
- [Ultimate Spy](https://www.google.se/books/edition/Ultimate_Spy/EObtBgAAQBAJ?hl=ru&gbpv=1&dq=inauthor:%22H.+Keith+Melton%22&printsec=frontcover)
- [Книги-бестселлеры Кевина Митника](https://www.mitnicksecurity.com/bestselling-books-by-kevin-mitnick)

**Zettelkasten Method:**

- [Zettelkasten Method With Obsidian- How to Take Smart Notes](https://beingpax.medium.com/zettelkasten-method-with-obsidian-how-to-take-smart-notes-with-examples-cdaf348febbd)
- [Настройка Zettelkasten в Obsidian: больше, чем приложение для ведения заметок](https://facedragons.com/productivity/setting-up-a-zettelkasten-in-obsidian/)
- [obsidian-zettelkasten](https://mattgiaro.com/obsidian-zettelkasten/)
- [Начало работы с Zettelkasten](https://obsidian.rocks/getting-started-with-zettelkasten-in-obsidian/)
- [Awesome OSINT](https://github.com/jivoi/awesome-osint)
- [OSINT Guide](https://github.com/drull1000/OSINT-guide)

# Работа: A-Z

Я бы рассматривал это как изучение иностранного языка. Хорошо, вы его выучили и приехали жить в страну, где на нем говорят. Но там все знают этот язык... Поэтому важно знать еще что-то в дополнение. Как правило, необходимо иметь навыки письма, хорошо взаимодействовать с людьми или быть юристом. При всем этом разные подходы требуют разных навыков и склада ума!

> Помните, что OSINT - это НЕ "что-то вроде [front-running/tailgating](https://www.investopedia.com/terms/f/frontrunning.asp) или скальпинга, но в реальной жизни"!

<details>
<summary>Расширение</summary
<br />

- ["There's No Such Thing As Open Source Intelligence"](https://threadreaderapp.com/thread/1633909123988242438.html)
- [Как стать расследователем разведки с открытым исходным кодом (OSINT)](https://www.wgu.edu/career-guide/information-technology/osint-career.html#close)
- [На самом деле отличная книга об атаках и защите](https://www.amazon.com/Network-Attacks-Defenses-Hands-Approach-ebook/dp/B00A8SN8WQ)
- [OSINT Guide - Open Source Intelligence](https://www.osintguide.com/2023/01/04/start-a-consulting-business-as-an-osint-expert/)
- [The Art of Proactive Defense: Mastering Threat Hunting with OSINT Tools](https://medium.com/@mohitdeswal_35470/the-art-of-proactive-defense-mastering-threat-hunting-with-osint-tools-336683d6d53b)
- [The Missing Semester of Your OSINT Education](https://medium.com/the-sleuth-sheet/the-missing-semester-of-your-osint-education-60b7bd48b7e9)
- [OSINT For Searching People](https://docs.google.com/spreadsheets/d/1JxBbMt4JvGr--G0Pkl3jP9VDTBunR2uD3_faZXDvhxc/edit#gid=1978517898)
- [Коллекция OSINT-ресурсов AaronCTI](https://docs.google.com/spreadsheets/d/1klugQqw6POlBtuzon8S0b18-gpsDwX-5OYRrB7TyNEw/htmlview)

</details>

**Работа:**

- [anonfriendly.com](http://anonfriendly.com/)
- [osintjobs](https://twitter.com/osintjobs)
- [I'll show you how to make money using OSINT](https://0xtechrock.gumroad.com/)
- [Python for OSINT за 21 день](https://github.com/cipher387/python-for-OSINT-21-days)
- [osintjobs.sociallinks.io](https://osintjobs.sociallinks.io/)
- [On-Chain Investigations Tools List](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List)
- [Как найти работу в Web3?](web.archive.org/web/20220618210743/https://twitter.com/_prestwich/status/1538267150917308416)
- [www.jobprotocol.xyz](https://www.jobprotocol.xyz/) и попробуйте [HR-игры](https://sourcing.games/)!
- Due Diligence
- [Присоединиться к уже существующей команде...](https://osintfr.com/en/our-osinters-are-talented/)
- Журналистика
- SMM
- [AML/Crypto Investigations](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List)
- [strategytribe.io](https://strategytribe.io)
- [Part-time tasks](https://telegra.ph/Scamfari-04-28)
- [Detect Personal Information Leakage With OSINT Attack Surface Management](https://osintteam.blog/detect-personal-information-leakage-with-osint-attack-surface-management-4a46923dd2fd)

# Внешние данные

**Больше инструментов (случайных) для использования в работе:**

- [mullvad.net/en/browser](https://mullvad.net/en/browser)
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
- [Social Media OSINT Tools Collection](https://github.com/osintambition/Social-Media-OSINT-Tools-Collection)

**Специфика (будет обновляться):**.

> **По мнению [GoldenOwl](https://osintteam.blog/safeguarding-osinters-shielding-against-disinformation-manipulation-dfbbfbf1db08):** По мере усиления борьбы с дезинформацией специалисты по OSINT должны быть бдительными и защищать себя от манипуляций. Применяя критическое мышление, диверсифицируя источники информации, проверяя информацию в социальных сетях, используя инструменты проверки фактов, постоянно обновляя информацию о методах дезинформации, сотрудничая с доверенными сообществами, обучая других, [соблюдая этические нормы](https://osintteam.blog/safeguarding-osinters-shielding-against-disinformation-manipulation-dfbbfbf1db08) и перепроверяя информацию, специалисты OSINT могут уберечь себя от манипуляций и сохранить целостность своих исследований. 

- [ChatGPT + OSINT](https://m.youtube.com/watch?v=L5OlYdCWzRs&feature=youtu.be)
- [Бонусный набор инструментов OSINT Twitter Crypto](https://telegra.ph/Bonus-OSINT-Twitter-Crypto-toolset-04-15)
- [Awesome OSINT Web3](https://github.com/aaarghhh/awesome_osint_criypto_web3_stuff)
- [tgscanrobot](https://t.me/tgscanrobot)
- [velociraptor.app](https://docs.velociraptor.app)
- [Web3/NFT OSINT](https://twitter.com/fuzzinglabs/status/1676226856553521153)
- [maigret_osint_bot](https://t.me/maigret_osint_bot)
- [telesint_bot](https://t.me/telesint_bot)
- [seekr tool](https://github.com/seekr-osint/seekr)
- [Data Journalism Resources](https://github.com/r3mlab/datajournalism-resources)
- [Digital Forensics Guide](https://github.com/mikeroyal/Digital-Forensics-Guide)
- [Twitter to TG bot](https://t.me/TwttrToTG_Bot)
- [Bellingcat hackathon - stratosphere Project](https://github.com/elehcimd/stratosphere)
- [osint-Brazil](https://github.com/osintbrazuca/osint-brazuca)
- [spiderfoot](https://github.com/smicallef/spiderfoot)
- [Awesome TG channel](https://t.me/osintil)
- [Inpaint-Anything](https://github.com/geekyutao/Inpaint-Anything)
- [metaosint.github.io](https://metaosint.github.io/chart)
- [Maltego Transforms List](https://github.com/cipher387/maltego-transforms-list)
- [Каталог инструментов OSINT с открытым исходным кодом](https://github.com/HowToFind-bot/osint-tools)
- [Шаблон для новых инструментов командной строки OSINT](https://github.com/soxoj/osint-cli-tool-skeleton)
- [Лучшие источники OSINT и вишинговые предлоги с соревнований по социальной инженерии DEF CON](https://medium.com/@chris.kirsch/top-osint-sources-and-vishing-pretexts-from-def-cons-social-engineering-competition-8e08de4c8ea8)

**Дополнительные статьи (внешние):**.

> [Как показывает практика](https://medium.com/@ibederov_en/military-intelligence-using-osint-methods-4aae1df2d812), современные вооруженные конфликты требуют новых подходов к организации сбора и анализа открытых данных, которыми мы оперируем в рамках OSINT. Будьте осторожны с ней и дважды подумайте, прежде чем действовать

- [Human Touch in Digital Defense: Virtual HUMINT's Battle Against Cyber Threats](https://osintteam.blog/human-touch-in-digital-defense-virtual-humints-battle-against-cyber-threats-33b81b3be53b)
- [From Zero to Google Dorking Hero: Enhancing Your OSINT Arsenal](https://osintteam.blog/mastering-osint-the-art-of-google-dorking-for-investigators-e0a908055873)
- [Использование ddg.gg для OSINT](https://www.ghacks.net/2023/04/24/duckduckgo-disables-most-search-filters-from-search/?amp)
- [cybdetective.substack.com](https://cybdetective.substack.com)
- [Uncovering Hidden Connections: Using Maltego Holehe to Map-out-a-persons-digital-footprint](https://medium.com/@philipbcase/uncovering-hidden-connections-using-maltego-holehe-to-map-out-a-persons-digital-footprint-90914d6bcbff)
- [Шпионаж PDF](https://t.me/irozysk/9243)
- [Hacktoria - Human Traffickers](https://medium.com/@wirec47/hacktoria-human-traffickers-b9bb00638c6a)
- [Password OSINT](https://viruszzwarning.medium.com/password-osint-fc4fd750ea8c)
- [Использование ИИ для разработки реалистичных аккаунтов Sock Puppet](https://www.raebaker.net/blog/using-ai-to-develop-realistic-sock-puppet-accounts)
- [ARCHIVING & OSINT](https://latenightafa.noblogs.org/archiving-and-osint/)
- [Awesome OSINT](https://github.com/jivoi/awesome-osint)
- [Awesome Telegram OSINT](https://github.com/ItIsMeCall911/Awesome-Telegram-OSINT)
- [Visualizing Darknet](https://medium.com/@cosmograph.app/visualizing-darknet-6846dec7f1d7)
- [Open Source Intelligence: The Beginners' Guide to OSINT](https://www.liferaftinc.com/blog/the-beginners-guide-to-osint)
- [DarkNet OSINT Guide](https://medium.com/the-sleuth-sheet/darknet-osint-guide-984f68fb7ab3)
- [Beginners Field Guide: Where & How to Learn OSINT](https://medium.com/the-sleuth-sheet/beginners-field-guide-where-how-to-learn-osint-bd2e11469f31)
- [OPEN SOURCE INTELLIGENCE TOOLS AND RESOURCES HANDBOOK 2020](https://i-intelligence.eu/uploads/public-documents/OSINT_Handbook_2020.pdf)
- [Распознавание информационных операций: от нелинейного анализа к принятию решений](https://arxiv.org/pdf/1901.10876.pdf)
- [OSINT-анализ фонда TOR](https://arxiv.org/pdf/1803.05201.pdf)
- [Top 10 OSINT Tools for Nickname Investigation](https://medium.com/@ibederov_en/my-top-10-osint-tools-for-nickname-investigation-40e292fa5c84)

**Некоторые выдающиеся инструменты:**

 > [Помните, ваша задача на этом](https://medium.com/@ronkaminskyy/from-zero-to-sherlock-the-ultimate-osint-adventure-5f9d8c45ae2) заключительном этапе - составить план по поддержанию и совершенствованию своих навыков OSINT. Выберите ресурсы для постоянного обучения, найдите задачи, в которых можно участвовать, и подумайте о вступлении в OSINT-сообщество. И наконец, пересмотрите свои этические принципы, чтобы убедиться, что вы всегда работаете ответственно и уважительно". - [Ron Kaminsky](https://medium.com/@ronkaminskyy/from-zero-to-sherlock-the-ultimate-osint-adventure-5f9d8c45ae2)

- [datashare.icij.org](https://datashare.icij.org)
- [Pinpoint](https://journaliststudio.google.com/pinpoint/collections)
- [dtsearch.com](https://www.dtsearch.com/)
- [Venator](https://t.me/venatorbrowser)
- [A next-generation crawling and spidering framework](https://github.com/projectdiscovery/katana)
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

**Внутренняя информация (внешняя):**

> **Согласно [Alessandra Adina](https://medium.com/@alessandraadina/how-to-do-cyber-reconnaissance-a-guide-to-osint-for-non-tech-professionals-da6c7db48699):** Цикл разведки представляет собой процесс превращения необработанной информации в действенные разведданные. Этот процесс позволяет лицам, принимающим решения, предпринимать соответствующие действия на основе полученных данных. Хотя в различных организациях используются различные варианты циклов разведки, популярным является пятиэтапный цикл: **Планирование, сбор, анализ, распространение и обратная связь*.

- [OSINT: Как найти информацию о ком угодно](https://osintteam.blog/osint-how-to-find-information-on-anyone-5029a3c7fd56)
- [OSINT - руководство для начинающих (часть 1)](https://medium.com/@Aardwarewolf/what-is-osint-part-1-91aa3890643)
- [OSINT: ОСНОВЫ](https://i-intelligence.eu/courses/osint-foundations)
- [How to Use OSINT to Detect Data Leaks and Breaches](https://www.liferaftinc.com/blog/how-to-use-osint-to-detect-data-leaks-and-breaches)
- [Введение в OSINT](https://infosecwriteups.com/introduction-to-osint-2c92597988d1)
- [Как улучшить обнаружение кибератак с помощью социальных сетей?](https://www.geeksforgeeks.org/how-to-improve-cyber-attack-detection-using-social-media/)
- [Утечка информации в Интернете? Используйте эти инструменты, чтобы выяснить это](https://www.tech.gov.sg/media/technews/are-you-leaking-information-on-the-web)
- [OSINT: утечки и взломы данных](https://www.osintguru.com/blog/osint-data-leaks-and-data-breaches)
- [OSINT с gOSINT](https://brandefense.io/blog/osint-with-gosint/)
- [List of OSINT Web Resources](https://github.com/OhShINT/ohshint.gitbook.io/blob/main/Lists_of_OSINT_Web_Resources/1-Complete-List-of-OSINT-Web-Resources.md)
- [An OSINT/SOCMINT Mind-map](http://files.mtg-bi.com/MindMap.jpg)
- [Как найти - Робота](https://t.me/HowToFind)
- [Игра в пароли](https://neal.fun/password-game/)
- [Как использовать OSINT в кибербезопасности](https://www.molfar.global/en-blog/how-to-use-osint-in-cybersecurity)
- [OSINT (OPEN-SOURCE INTELLIGENCE) - стать трудно взламываемым!](https://somprt.com/our-series/osint-open-source-intelligence/)
- [GitHub OSINT Topic](https://github.com/topics/open-source-intelligence?o=desc&s=stars)
- [SOCMINT - точнее, OSINT социальных медиа](https://research.securitum.com/socmint-or-rather-osint-of-social-media/)

**Более конкретные ресурсы (внешние):**

> **По словам [Alessandra Adina](https://medium.com/@alessandraadina/how-to-do-cyber-reconnaissance-a-guide-to-osint-for-non-tech-professionals-da6c7db48699):** В области OSINT можно встретить такой термин, как "серая литература". Это внутренние документы, не предназначенные для публичного использования, но, к сожалению, они легко могут оказаться в местах, где их можно найти. Примерами могут служить технические отчеты, информационные бюллетени, счета-фактуры, коммерческие предложения или запросы на предложения.

> Понимание ценности информации вашей организации, потенциальных векторов атак, а также того, на кого могут быть направлены фишинговые атаки или другие виды социальной инженерии, является чрезвычайно важным. OSINT может помочь вам в оценке этих рисков и планировании соответствующих мер защиты.

- [OrienterNet Visual Localization in 2D Public Maps with Neural Matching](https://github.com/facebookresearch/OrienterNet)
- [OSINT Tools - Airtable](https://airtable.com/embed/shrYXDdO1V5y33lIX/tblgDtMXI4fxtg9Op)
- [OSINT - HUMINT](https://docs.google.com/spreadsheets/d/1JxBbMt4JvGr--G0Pkl3jP9VDTBunR2uD3_faZXDvhxc/edit#gid=1978517898)
- [Ultimate OSINT](https://start.me/p/DPYPMz/the-ultimate-osint-collection)
- [OSINT List](https://start.me/p/ZME8nR/osint)
- [Curated OSINT List](https://start.me/p/7kxyy2/osint-tools-curated-by-lorand-bodo)
- [OSINT Inception](https://start.me/p/Pwy0X4/osint-inception)
- [Geolocation-OSINT](https://github.com/cqcore/Geolocation-OSINT)
- [researchaide.org](https://www.researchaide.org/)
- [botster.io/bots Crawling](https://botster.io/bots)
- [Yet another awesome OSINT list](https://start.me/p/rx6Qj8/nixintel-s-osint-resource-list)
- [Cryptocurrency OSINT](https://start.me/p/ek4rxK/cryptocurrency)
- [Awesome On-Chain Investigations HandBook](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List/blob/main/README.md)
- [Investigator tools](https://start.me/p/gyaOJz/investigator-tools)
- [Коллекция из нескольких сотен онлайн-инструментов для OSINT](https://github.com/cipher387/osint_stuff_tool_collection)
- [Rawsec's CyberSecurity Inventory](https://inventory.raw.pm/tools.html#title-tools-osint)
- [OSINT-TOOLS-CLI](https://github.com/Coordinate-Cat/OSINT-TOOLS-CLI)
- [Geoestimation](https://labs.tib.eu/geoestimation/)
- [Using OSINT Search Engines To Collect Cyber Threat Intelligence](https://osintteam.blog/using-osint-search-engines-to-collect-cyber-threat-intelligence-3e9ace82eb64)
- [GraphSense Maltego Transform](https://github.com/INTERPOL-Innovation-Centre/GraphSense-Maltego-transform)
- [leakix.net](https://leakix.net/)
- [Офицер_ЦРУ X MaxWayld: обзор контента](https://officercia.medium.com/officer-cia-x-maxwayld-content-overview-39fa3011a73f)
- [Каналы о OSINT, хакинге, безопасности и т.д.](https://graph.org/Channels-about-OSINT-Hacking-Security-and-so-on-04-19)
- [Exploring the Dark Side: OSINT Tools and Techniques for Unmasking Dark Web Operations](https://www.sans.org/blog/exploring-the-dark-side-osint-tools-and-techniques-for-unmasking-dark-web-operations/)

**Telegram + Discord: Security, OSINT, SOCMINT:**.

 > По мнению [Ron Kaminsky](https://osintteam.blog/unveiling-the-digital-detective-essential-osint-tools-and-techniques-for-investigators-adf486ad2ccd): OSINT произвел революцию в мире расследований, позволяя людям и организациям обнаруживать ценную информацию, решать сложные проблемы и принимать обоснованные решения. [Возможность использования огромного количества данных, доступных в открытых источниках, открыла новые возможности и изменила картину расследований. Эффективное использование инструментов OSINT позволяет следователям экономить время, собирать исчерпывающую информацию и выявлять связи, которые в противном случае могли бы оставаться скрытыми. Приемы и методики, рассмотренные в данном руководстве, представляют собой "дорожную карту" для проведения тщательных и успешных OSINT-расследований.

- [Как определить точное местоположение телефона, планшета или ПК](https://medium.com/@ibederov_en/how-to-find-the-exact-location-of-phone-tablet-or-pc-b953a60421a9)
- [osint-mindset.gitbook.io](https://osint-mindset.gitbook.io) | Совет: Используйте [deepl.com](https://www.deepl.com/translator)!
- [Discord OSINT Toolset](https://telegra.ph/Discord-OSINT-Toolset-04-11)
- [DiscordOSINT](https://github.com/AtonceInventions/DiscordOSINT)
- [Telegram OSINT](https://github.com/cqcore/Telegram-OSINT)
- [OSINT Discord resources](https://github.com/Dutchosintguy/OSINT-Discord-resources)
- [TelegramOnlineSpy](https://github.com/Forichok/TelegramOnlineSpy)
- [Discord & Telegram OSINT references](https://github.com/Ginsberg5150/Discord-and-Telegram-OSINT-references)
- [Awesome Discord](https://github.com/jacc/awesome-discord)
- [Awesome Telegram OSINT](https://github.com/ItIsMeCall911/Awesome-Telegram-OSINT)
- [Darvester](https://github.com/darvester/darvester)
- [Telegram & Discord OpSec](https://officercia.mirror.xyz/dlf6ZEXq3FLE21ZY2jeJ0cBDyuZu8XIF9DEJAQ07nk8)
- [Discord OpSec для серверов](https://officercia.mirror.xyz/x4nGX6YwhhmHj8TaQ53kBR5b5M1Ei_Y9_l1Vpext-Hk)
- [Если вас обманули...](https://officercia.mirror.xyz/X5Q0uPwvlgZ6BrvCmyqXlXHFgLAWrMtzAHSvjzrDS7c)

**Посмотрите мои статьи:**

- [Навигация (мои статьи)](https://officercia.mirror.xyz/Uc1sf64yUCb0uo1DxR_nuif5EmMPs-RAshDyoAGEZZY)
- [Оригинальная статья](https://officercia.mirror.xyz/5KSkJOTgMtvgC36v1GqZ987N-_Oj_zwvGatOk0A47Ws)
- [OpSec Going Smart](https://officercia.mirror.xyz/fsRT9NC29GzeQAl-zvAMJ9L-hYUYvX1CPUkt97Vuuwo)
- [OpSec Going Smarter](https://officercia.mirror.xyz/B9hBom4jGhkV0C-47E4YBz8tBJkb0a7zVwQR0jITIyM)
- [OpSec Going Smarter: Secure Smartphones](https://officercia.mirror.xyz/0tlSSF2LDTOnnMN41R5Uc1kTpo-G-kXljn8pT0a1YLY)
- [Выбор надежного VPN-провайдера для жизни и работы](https://officercia.mirror.xyz/x91hTIDFrAL0lgqICRgWU7fLouuCMgvopQ9ZRvRXCLg)
- [Полный список правил, которые должен соблюдать каждый, кто находится в сети, чтобы оставаться в безопасности](https://officercia.mirror.xyz/_nD1Rtxe1PplK-NQzIq9sl-KNtajQG0aKqYsV36RTjA)
- [QR-код: недооцененная опасность](https://officercia.mirror.xyz/aN6giRkUsNd0o0bmjZVeZb2htkO_Ve16gMsARU6RBfM)
- [Наиболее значимые вехи в развитии средств связи](https://officercia.mirror.xyz/G4782jMUpA_kkIpwakphbd6djX85cxRGS-pjBipc8Yk)
- [Как выиграть войну, обмануть КГБ и защитить свои криптоактивы от кражи с помощью стеганографии](https://officercia.mirror.xyz/8ecJG-s_5E6J1t-h8gUNGqV3hbX8If-E5NnrFrOJHUA)
- [Атаки через репрезентативную выборку: мифы и реальность](https://officercia.mirror.xyz/WeAilwJ9V4GIVUkYa7WwBwV2II9dYwpdPTp3fNsPFjo)
- [Как стать специалистом по OSINT в масштабах одной армии?](https://officercia.mirror.xyz/5KSkJOTgMtvgC36v1GqZ987N-_Oj_zwvGatOk0A47Ws)
- [Telegram & Discord Security Best Practices](https://officercia.mirror.xyz/dlf6ZEXq3FLE21ZY2jeJ0cBDyuZu8XIF9DEJAQ07nk8)

# Поддержка проекта

Поддержка **очень** важна для меня, с ней я могу тратить меньше времени на работу и заниматься любимым делом - обучением пользователей DeFi и Crypto :sparkling_heart:

Если вы хотите поддержать мою работу, пожалуйста, рассмотрите возможность пожертвования по адресу:

- **[0xB25C5E8fA1E53eEb9bE3421C59F6A66B786ED77A](https://etherscan.io/address/0xB25C5E8fA1E53eEb9bE3421C59F6A66B786ED77A)** — ERC20 & ETH [officercia.eth](https://etherscan.io/enslookup-search?search=officercia.eth)

- **[17Ydx9m7vrhnx4XjZPuGPMqrhw3sDviNTU](https://blockchair.com/bitcoin/address/17Ydx9m7vrhnx4XjZPuGPMqrhw3sDviNTU)** - BTC

- **4AhpUrDtfVSWZMJcRMJkZoPwDSdVG6puYBE3ajQABQo6T533cVvx5vJRc5fX7sktJe67mXu1CcDmr7orn1CrGrqsT3ptfds** - Monero XMR

Вы также можете отправить мне пожертвование на адрес из [этого репозитория](https://github.com/OffcierCia/support)!
