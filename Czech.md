# Atypický průvodce OSINT

#### Nejneobvyklejší průvodce OSINT, jakého jste kdy viděli. Úložiště je určeno pouze pro znuděné profesionály. 

PR na #### jsou vítány! Neváhejte a pošlete pull request s čímkoli od drobných oprav po překlady, dokumenty nebo nástroje, které byste chtěli přidat.

> **Odmítnutí odpovědnosti: Veškeré informace (nástroje, odkazy, články, texty, obrázky atd.) jsou poskytovány pouze pro vzdělávací účely! Všechny informace jsou rovněž založeny na údajích z veřejných zdrojů. Za své kroky nesete výhradní odpovědnost vy, nikoli autor** ❗️.

[![Projekt podpory](https://img.shields.io/badge/Support-Project-critical)](https://github.com/OffcierCia/support/blob/main/README.md)
       [![Mail](https://img.shields.io/badge/Mail-offcierciapr%40protonmail.com-brightgreen)](mailto:offcierciapr@protonmail.com)

# Začněte zde

**Zkontrolujte si:**

- [Navigace (mé články)](https://officercia.mirror.xyz/Uc1sf64yUCb0uo1DxR_nuif5EmMPs-RAshDyoAGEZZY)
- [Původní článek](https://officercia.mirror.xyz/5KSkJOTgMtvgC36v1GqZ987N-_Oj_zwvGatOk0A47Ws)
- [Zde také zveřejněno!](https://officercia.medium.com/the-atypical-osint-guide-2023-276a8d00959)

Dnes bych se rád věnoval tomu, jak se stát dobrým vyšetřovatelem OSINT, ale na pokračování bych rád učinil malé zřeknutí se odpovědnosti - povím vám jen některé aspekty, protože téma je velmi rozsáhlé a nemohu vše popsat v jednom návodu, nicméně se vám pokusím ukázat cestu a způsob, jak tuto cestu projít. Tato příručka je vyvrcholením mnohaleté práce profesionálů v oblasti OSINT. Považujte tuto příručku za souhrn rad a cest!

Mějte na paměti, že tato esej má sloužit jako návod! Pečlivě zvažte své jednání, jinak budete stíháni nebo hůře! Vždy mějte na paměti etiku a související zákony - jako GDPR atd... Neměli byste si OSINT a vyšetřování na řetězci romantizovat stejným způsobem, jakým si jednotlivci často romantizují hackerství a válčení, vřele vám to doporučuji!

- [Bostonský bombový útok: Jak se internetoví detektivové velmi zmýlili](https://www.bbc.com/news/technology-22214511)
- [OSINT? WTF??](https://ohshint.gitbook.io/oh-shint-its-a-blog/osint/osint-wtf)

> V neposlední řadě vše, co děláte, vychází z výsledků, kterých potřebujete dosáhnout! Měli byste si umět vybrat spolehlivé a prověřené zdroje, místo abyste používali všechny nástroje a odkazy. Prostřednictvím daných cest byste měli být schopni zkonstruovat svou vlastní cestu! V návaznosti na to vám řeknu o způsobech, které považuji za bezpečné a doporučuji svým klientům! Odborníci na OSINT strávili desítky let vývojem této příručky a v každém slově se podělili o své odborné znalosti. Považujte tuto příručku opět za souhrn rad a cest.

Je také zásadní si uvědomit, že OSINT je pouze dalším prostředkem k poznávání světa kolem vás a není to způsob, jak "dostat okamžitě zaplaceno". Vždy si udělejte přestávku, abyste načerpali síly! Vaše zdraví a mysl jsou důležité!

- [Jak poznat, kdy přestat](https://www.lennysnewsletter.com/p/how-to-know-when-to-stop)
- Jak se stát tisíciletým upírem](https://www.lesswrong.com/posts/5QpufhoH2ASnppsjs/how-to-become-a-1000-year-old-vampire)
- Jak se rychle učit](https://degatchi.com/articles/how-to-learn-fast/)
- Jak pomocí myšlenkových map uvolnit kreativitu a potenciál svého mozku](https://lifehacker.com/how-to-use-mind-maps-to-unleash-your-brains-creativity-1348869811)
- [Umí OSINT každý?](https://medium.com/osintfun/can-everybody-do-osint-f5d5e6128445)
- [Vicarious trauma](https://osintcurio.us/2020/06/08/vicarious-trauma-and-osint-a-practical-guide/)

Tyto informace vás nečiní lepšími ani horšími. Lidstvo jako druh má sklon přizpůsobovat se svému okolí, což, jak všichni víme, začíná znalostmi, pozorováním a metodikou. Dávejte na sebe pozor, zvažte důsledky svých činů a respektujte soukromí ostatních. Nepřekračujte červené linie!

<detaily>
<summary>Rozšířit</summary>
<br />

- [OSINT + Crypto](https://www.forensicxs.com/blockchain-osint-decentraland/)
- Zde se zabýváme tím, jak lze vyšetřovat kryptografické hackery a bezpečnostní incidenty!" [https://github.com/OffcierCia/On-Chain-Investigations-Tools-List].
- [osint.sh All in One OSINT Tools List](https://osint.sh/)
- Zatím nevyužitý zlatý důl OSINT: příležitosti, otevřené výzvy a budoucí trendy](https://www.researchgate.net/publication/338495014_The_Not_Yet_Exploited_Goldmine_of_OSINT_Opportunities_Open_Challenges_and_Future_Trends)

</details>

Vždy dvakrát přemýšlejte, než začnete jednat, dodržujte zákony a pravidla OpSec. Pokud chcete pomáhat nebo provádět sociální vyšetřování, ale nemáte dostatek zkušeností, obraťte se na zkušenější osoby, abyste neublížili obětem nebo těm, kteří se je snaží zachránit. Ve svých článcích naopak odhaluji jiné použití OSINT, inspirované due diligence a civilním finančním zpravodajstvím, se zaměřením na **civilní** aplikace. To je moje vize, kterou, jak doufám, přijmete...

- [Zpravodajské studie: Druhy shromažďování zpravodajských informací](https://usnwc.libguides.com/c.php?g=494120&p=3381426)
- Pochopení různých typů disciplín shromažďování zpravodajských informací](https://www.maltego.com/blog/understanding-the-different-types-of-intelligence-collection-disciplines/)
- [inteltechniques.com](https://inteltechniques.com)
- Historie OSINT: Od informování špionů k odhalování lží](https://www.skopenow.com/news/a-history-of-osint)
- Zpravodajské vyšetřování z otevřených zdrojů: Od strategie k realizaci](https://www.researchgate.net/publication/321531302_Open_Source_Intelligence_Investigation_From_Strategy_to_Implementation) [Open Source Intelligence Investigation: From Strategy to Implementation](https://www.researchgate.net/publication/321531302_Open_Source_Intelligence_Investigation_From_Strategy_to_Implementation)
- [Rverse Image Search](https://www.numlookup.com/reverse-image-search)

### **Ať vás provází síla!**

# Úvod: Civilní OSINT

Na úvod chci říci, že OSINT budu považovat za soubor dovedností nebo způsob myšlení, protože může přímo souviset s doxingem, vojenským GEO-INT prováděným zaměstnancem bezpečnostní firmy nebo jen mediálním OSINT prováděným zaměstnancem fondu rizikového kapitálu s cílem najít nové projekty pro investice, přičemž za základ vezmu teorii podávání rukou...

- [OSINT Is A State Of Mind](https://medium.com/secjuice/osint-as-a-mindset-7d42ad72113d)
- Kognitivní předpojatost a kritické myšlení ve zpravodajství z otevřených zdrojů (OSINT)](https://deepsec.net/docs/Slides/2014/Cognitive_Bias_and_Critical_Thinking_in_Open_Source_Intelligence_(OSINT)_-_Benjamin_Brown.pdf)
- [Stručná historie zpravodajských služeb s otevřeným zdrojovým kódem](https://www.bellingcat.com/resources/articles/2016/07/14/a-brief-history-of-open-source-intelligence/)
- Jak OSINT podpořil největší kriminální vyšetřování v dějinách USA](https://www.isdglobal.org/digital_dispatches/jan-6-series-how-osint-powered-the-largest-criminal-investigation-in-us-history/)

...Nebo dokonce specialista na kryptoforenzní analýzu vyšetřující velký případ hackerského útoku na Web3.0. Jinými slovy, lze ji využít ve všech sférách života, protože jde pouze o metodu práce s informacemi, jejich vyhodnocování a třídění - nikdy nezapomínejte, že všichni žijeme v informační éře.

<detaily>
<summary>Rozšířit</summary>
<br />

- Seznamte se s blockchainovými detektivy, kteří sledují kryptografické hackery a podvodníky](https://www.vice.com/en/article/xgd9zw/meet-the-blockchain-detectives-who-track-cryptos-hackers-and-scammers)
- [Speciální kompilace "Blockchain Investigations"](https://t.me/officer_cia/236)
- [Jak vyšetřuji kryptografické hackery a bezpečnostní incidenty: od A do Z](https://officercia.mirror.xyz/BFzv17UwH6QG4q711NAljtSiP8eKR17daLjTdmAgbHw)
- [Příručka vyšetřování na řetězci](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List)
- Průvodce začátečníka zpravodajstvím z otevřených zdrojů (OSINT) [The Beginner's Guide to Open-Source Intelligence (OSINT): Techniky a nástroje](https://medium.com/@mohitdeswal_35470/the-beginners-guide-to-open-source-intelligence-osint-techniques-and-tools-6a91b9c37ee1)
- [Awesome Intelligence](https://github.com/ARPSyndicate/awesome-intelligence)

</details>

Vše, co jsem uvedl výše, můžete rozvíjet sami v sobě, ale podstata všech směrů je stejná - schopnost všímat si cenných informací, anomálií, vidět rozdíly, pečlivě analyzovat fakta a vytvářet logický řetězec - a přitom být v toku informací. Začněte od prověřování vlastních informací a vlastních dat: proveďte OSINT výzkum proti sobě. Shromážděte všechna data, vizualizujte je a poté je vymažte - s využitím technik SERM/ORM.

- SERM](https://thebusinessprofessor.com/seo-social-media-direct-marketing/search-engine-reputation-management-definition)
- [ORM](https://medium.com/elfsight-blog/introduction-to-search-engine-reputation-management-serm-44467c891c0b)
- Příklady selhání opsec a ochrany soukromí při provádění OSINT](https://www.osintme.com/index.php/2022/01/17/examples-of-opsec-and-privacy-fails-when-doing-osint/).
- [WhatBreach](https://github.com/Ekultek/WhatBreach)
- [Další studie opsec](https://github.com/lawsecnet/OPSEC)
- [Základní tipy a triky OPSEC pro výzkumníky OSINT](https://web.archive.org/web/20221108024236/https://osintcurio.us/2019/04/18/basic-opsec-tips-and-tricks-for-osint-researchers/amp/)
- [The Osint Me ultimate guide to Telegram OSINT and privacy](https://www.osintme.com/index.php/2022/10/18/the-osint-me-ultimate-guide-to-telegram-osint-and-privacy/)
- [Otupujte se dřív, než to udělá "někdo"](https://osintteam.blog/dork-yourself-before-someone-does-aa49d0c1929f)

Rád bych vám dal první lekci, všechny zdroje, které vám poradím - jsem si nastudoval sám dříve:

- [So You Think You Can Google? - Workshop With Henk van Ess](https://youtu.be/uyqXS5lL-mc)
- [OSINT Origins #1 - Jean-Marc Manach/@manhack](https://youtu.be/XrTFzZ77eEI).
- [Úžasná myšlenková mapa OSINT](http://files.mtg-bi.com/MindMap.jpg)
- [Nejlepší bezpečnostní postupy pro Telegram a Discord](https://officercia.mirror.xyz/dlf6ZEXq3FLE21ZY2jeJ0cBDyuZu8XIF9DEJAQ07nk8)
- [Definitivní průvodce generováním uživatelských jmen pro účely OSINT](https://github.com/soxoj/username-generation-guide)
- [Odolávání deterministickému myšlení](https://zephoria.medium.com/resisting-deterministic-thinking-52ef8d78248c)

# Mind-Mapping

Nejprve si rozebereme takový pojem, jako je mapování mysli. Je velmi důležité naučit se třídit informace podle různých kritérií, věřím, že si můžete procvičit třídění naprosto libovolných informací!

- [Myšlenková mapa](https://en.wikipedia.org/wiki/Mind_map)
- Co potřebujete, abyste se stali středně pokročilým OSINTerem? Jak může Šodan přispět k vyšetřování OSINT?"](https://podtail.com/en/podcast/osintcurious/episode-51-what-do-you-need-to-become-an-intermedi/).
- První kroky, jak začít s výzkumem otevřených zdrojů] [https://www.bellingcat.com/resources/2021/11/09/first-steps-to-getting-started-in-open-source-research/].
- Vše o zpravodajství s otevřeným zdrojovým kódem a vyšetřování OSINT](https://www.maltego.com/blog/what-is-open-source-intelligence-and-how-to-conduct-osint-investigations/)

**[Co je Maltego a proč ho používat pro OSINT?](https://wondersmithrae.medium.com/a-beginners-guide-to-osint-investigation-with-maltego-6b195f7245cc)** Maltego je nástroj pro dolování dat, který doluje různé zdroje dat z otevřených zdrojů a používá tato data k vytváření grafů pro analýzu souvislostí. Grafy umožňují snadno vytvářet souvislosti mezi informacemi, jako je jméno, organizační struktura e-mailu, domény, dokumenty atd. Maltego používá Javu, takže může běžet v systémech Windows, Mac a Linux a je k dispozici v mnoha distribucích OSINT Linux, jako je Buscador nebo Kali. 

V podstatě za vás zpracuje velké množství informací a prohledá různé webové stránky s otevřeným zdrojovým kódem a pak vám vyhodí pěkně vypadající graf, který vám pomůže poskládat jednotlivé části dohromady. Maltego lze použít jako zdroj informací kdykoli během vyšetřování, nicméně pokud je vaším cílem doména, má smysl začít mapovat síť pomocí Maltego hned od začátku.

#### Copak si ve škole všichni nedělali taháky? Je čas to udělat znovu, protože v budoucnu by se měly vyvinout v dovednost Maltego!

- Top OSINT & Infosec Resources for You and Your Team (2022 Edition) [Nejlepší zdroje OSINT a Infosec pro vás a váš tým (vydání 2022): Více než 100 blogů, podcastů, YouTube, knih a dalších!] (https://www.maltego.com/blog/top-osint-infosec-resources-for-you-and-your-team/)
- [Průvodce začátečníka vyšetřováním OSINT s nástrojem Maltego] (https://wondersmithrae.medium.com/a-beginners-guide-to-osint-investigation-with-maltego-6b195f7245cc)
- Maltego - Cyber Weapons Lab - Výzkum jako analytik OSINT](https://youtu.be/46st98FUf8s)
- Bezplatné digitální odznaky pro výuku / rozvoj dovedností OSINT](https://www.reddit.com/r/OSINT/comments/kgew5d/free_digital_badges_for_learning_developing_osint/)
- Tipy, jak povzbudit dítě k účasti na mimoškolních aktivitách](https://talentgum.com/blog/tips-to-encourage-your-child-to-participate-in-extracurricular-activities)
- Jaké dovednosti potřebujete k tomu, abyste byli dobří v šachu + jak je zlepšit] (https://skillspointer.com/skills-for-chess/) [Jaké dovednosti potřebujete k tomu, abyste byli dobří v šachu + jak je zlepšit] (https://skillspointer.com/skills-for-chess/)

> Drobný tip - provádějte [výkonné vyhledávání](https://www.edx.org/course/power-searching-with-google) s použitím různých IP adres, v různých časových rozmezích a prostřednictvím různých [vyhledávačů](https://github.com/tasos-py/Search-Engines-Scraper).

## Pochopení základů OSINT podle [VEEXH](https://wondersmithrae.medium.com/a-beginners-guide-to-osint-investigation-with-maltego-6b195f7245cc):

- a. Pochopit pojem OSINT a jeho význam při shromažďování zpravodajských informací.
- b. Seznámit se s typy zdrojů OSINT (např. sociální média, veřejné záznamy, online fóra, zpravodajské zdroje).
- c. Seznámit se s etickými a právními aspekty při shromažďování OSINT.

**Rozvoj technických dovedností:**

- a. Získat dovednosti v základním používání počítače a internetu.
- b. Naučit se pokročilé techniky vyhledávání pomocí vyhledávačů a operátorů.
- c. Pochopit význam anonymity a získat dovednosti v používání VPN, proxy serverů a sítě Tor.
- d. Seznámit se se základními nástroji OSINT, jako jsou Maltego, Shodan a Google Dorks.

**Zvládnutí shromažďování informací OSINT:**

- a. Naučte se identifikovat a stanovit priority zpravodajských požadavků.
- b. Vypracujte si systematický přístup ke shromažďování údajů z různých zdrojů.
- c. Zdokonalte své dovednosti v oblasti sociálního inženýrství, pasivního průzkumu a online průzkumu.
- d. Získejte odborné znalosti v oblasti geolokace, analýzy snímků a vyhledávání informací o jednotlivcích a organizacích.

**Analýza a vyhodnocování v rámci systému iOSINT:**

- a. Naučte se různé analytické techniky, jako je analýza odkazů, analýza časové osy a analýza nálad.
- b. Rozvíjet kritické myšlení a povědomí o kognitivních zkresleních.
- c. Pochopit význam zpravodajského cyklu a aplikovat jej na analýzu OSINT.
- d. Vyhodnotit důvěryhodnost a spolehlivost zdrojů a informací.

**Šíření a podávání zpráv o OSINT:**

- a. Seznámit se se zásadami účinné komunikace.
- b. Naučit se vytvářet zpravodajské zprávy, briefingy a vizualizace.
- c. Pochopit, jak je důležité přizpůsobit své zprávy různým skupinám příjemců.
- d. Rozvíjet schopnost prezentovat zjištění jasným, stručným a použitelným způsobem.

**Neustálé zlepšování a vytváření sítí:**

- a. Udržujte si přehled o nejnovějších trendech, nástrojích a technikách OSINT.
- b. Účastněte se příslušných online komunit, fór a skupin na sociálních sítích.
- c. Účastnit se konferencí, seminářů a webinářů o OSINT.

Dodržováním tohoto rámce mohou začátečníci systematicky rozvíjet své dovednosti v oblasti OSINT a stát se zkušenými ve sběru, analýze a šíření zpravodajských informací z otevřených zdrojů. OSINT (Open-source Intelligence) je také klíčovou fází procesu penetračního testování. 

Důkladné prozkoumání veřejně dostupných informací může zvýšit šance na nalezení zranitelného systému, získání platných přihlašovacích údajů pomocí sprejování hesel nebo získání opory prostřednictvím sociálního inženýrství.

# Pohlcující a herní učení: Triky (a)

Mohu vám také doporučit, abyste se obrátili na zajímavou subkulturu, která je vhodná pro introverty! Jsem si jistý, že každý se tak či onak zajímá o různé podivné jevy. Ponořte se do prostředí net-stalkingu! 

Někdy se obyčejným lidem podařilo vyřešit zločiny, které policie nedokázala vyřešit celá léta jen pomocí OSINTu a GEOINTu (mohl bych sem dát odkazy na subreddity, filmy a zprávy, ale protože my dva se teď zabýváme OSINTem, doporučuji vám, abyste si to našli sami).

<detaily>
<summary>Rozšířit</summary>
<br />

- Co je to Netstalking?] (https://graph.org/What-is-Netstalking-Netstalking-Information-Survivors-04-06)
- [GEOGUESSR](https://somerandomstuff1.wordpress.com/2019/02/08/geoguessr-the-top-tips-tricks-and-techniques/)
- [SunCalc Calculator](http://suncalc.net/)
- Mind Hacks - Psychologické profilování a duševní zdraví při vyšetřování OSINT](https://youtu.be/104WpJm_eGk)
- [Metoda výuky zpravodajství z otevřených zdrojů (OSINT) pomocí personalizovaných cvičení v cloudu](https://www.researchgate.net/publication/340023320_A_Method_for_Teaching_Open_Source_Intelligence_OSINT_Using_Personalised_Cloud-based_Exercises)
- [Metoda simulací útoků: příklad](https://istrosec.com/service/attack-simulations/)

</details>

**Také se podívejte na:**

- [Hra alternativní reality](http://en.wikipedia.org/wiki/Alternate_reality_game)
- [reddit.com/r/ARG](http://reddit.com/r/ARG)
- [Net.art](https://officercia.mirror.xyz/VD9IDI8b4jVBHbr5uaGcI_ev6NEKZUuuOhL9IpEfpZs)
- [Výzkumné metody aplikované antropologie](https://en.wikipedia.org/wiki/Applied_Anthropology_Research_Methods)
- [Reflections on Becoming an Applied Anthropologist](https://www.jstor.org/stable/25605413)
- Aplikovaná antropologie (opravdu, studujte ji!)](https://oxfordre.com/anthropology/browse;jsessionid=469E22D5E27E148C59A31BA5715AD18D?page=3&pageSize=20&sort=titlesort&subSite=anthropology&t0=ORE_ANT%3AREFANT001)

Hlavně nezapomínejte na své zdraví, to je nade vše, nenechte se otřást svými zásadami tím, co vidíte. Jste přece pozorovatel! Zde dobře pomáhá pochopit psychologii [výzkumníků SCP](https://scp-wiki.wikidot.com/) (kdy nic není jasné, ale vědecká metoda pomáhá vše uvést na pravou míru).

<detaily>
<summary>Rozšířit</summary>
<br />

- [Netstalking: Do hloubky](https://graph.org/What-is-Netstalking-Netstalking-Information-Survivors-04-06).
- Jak jsem našel první vývojáře ekosystému Solana pomocí taktiky OSINT](https://telegra.ph/How-I-found-early-Solana-ecosystem-Developers-using-OSINT-tactics-01-04)
- [Stopařův průvodce online anonymitou](https://web.archive.org/web/20220302223645/https://anonymousplanet.org/guide.html)
- [Výzkumy OpSec a datové terminály - příspěvky jsou vítány](https://github.com/OffcierCia/Crypto-OpSec-SelfGuard-RoadMap).
- [Otupujte se dřív, než to udělá někdo jiný!](https://yvesei.medium.com/dork-yourself-before-someone-does-aa49d0c1929f)

</details>

Mějte na paměti, že v této části globálního internetu (mám na mysli OSINT obecně, nejen Net-stalking) se procento lidí, kteří aktivně hledají problémy nebo potřebují vyjádřit své emoce, neliší od jiných míst!

- [Chovej se jako lev 🦁] (https://twitter.com/jpurd17/status/1648669362910552067?s=20)
- [obsidian.md OSINT Templates](https://github.com/WebBreacher/obsidian-osint-templates)
- [Rozšíření prohlížeče OSINT](https://github.com/cqcore/OSINT-Browser-Extensions)

**Věda + OSINT:**

- Nahlížení do mysli [Peering into the Mind: ](https://www.linkedin.com/pulse/peering-mind-psychological-profiling-through-ai-large-smith): Psychologické profilování prostřednictvím umělé inteligence a velkých jazykových modelů...
- [Occamova břitva](https://www.britannica.com/topic/Occams-razor)
- Jak funguje Occamova břitva](https://science.howstuffworks.com/innovation/scientific-experiments/occams-razor.htm)
- Occamova břitva jako vědecký princip](https://study.com/learn/lesson/occams-razor-scientific-principle.html#:~:text=Occamova%20břitva%20je%20princip%20který%20stanoví%20že%20pluralita%20by měla,být%20používána%20trochu%20volněji).
- [PŘÍPADOVÁ STUDIE: Profilování osobnosti a síla OSINT](https://brightplanet.com/2016/11/09/case-study-receptiviti-power-osint/)
- [Platforma obohaceného zpravodajství o hrozbách pro zlepšení možností korelace, analýzy, vizualizace a sdílení OSINT](https://www.sciencedirect.com/science/article/abs/pii/S2214212620308589).
- ["Dedukce" vs. "Indukce" vs. "Únos"](https://www.merriam-webster.com/words-at-play/deduction-vs-induction-vs-abduction)
- [Rozdíl mezi deduktivním a induktivním uvažováním](https://danielmiessler.com/p/the-difference-between-deductive-and-inductive-reasoning/)
- [Rétorika indukce](https://www.studysmarter.co.uk/explanations/english/rhetoric/induction-rhetoric/)
- Deduktivní a induktivní uvažování: definice, rozdíly a příklady](https://mundanopedia.com/economics/microeconomics/deductive-and-inductive-reasoning-methods/)

**Praktika:**

> Dodržujte tedy pravidla OpSec a nedělejte příliš mnoho chyb. Provádějte své činnosti z odděleného, izolovaného zařízení.

- Obavy o soukromí a faktory přijetí OSINT pro kybernetickou bezpečnost [Privacy Concerns and Acceptance Factors of OSINT for Cybersecurity: A Representative Survey](https://petsymposium.org/popets/2023/popets-2023-0028.pdf)
- Co jsou to heuristiky?] (https://www.verywellmind.com/what-is-a-heuristic-2795235)
- Call of PSYOPS](https://steemit.com/news/@rusticus/call-of-psyops-video-games-as-psychological-warfare-in-the-21st-century).
- Trendy OSINT pro rok 2023 a další roky](https://blog.sociallinks.io/osint-trends-for-2023-and-beyond/)
- Široké využití OSINT ve vojenském zpravodajství](https://blog.sociallinks.io/uses-of-osint-in-military-intelligence/)
- [Vysvětlení veřejně dostupných informací (PAI)](https://www.babelstreet.com/blog/pai-explained)
- [Veřejně dostupné informace: Digitální bojiště](https://censa.net/publications/publicly-available-information-the-digital-battlefield/)
- [Lepší využití veřejně dostupných informací](https://www.jstor.org/stable/pdf/resrep20002.7.pdf)
- [Vědecké postupy: Falešně pozitivní a falešně negativní výsledky](https://manoa.hawaii.edu/exploringourfluidearth/chemical/matter/properties-matter/practices-science-false-positives-and-false-negatives)
- [Falešně pozitivní a falešně negativní výsledky v informační bezpečnosti](https://www.guardrails.io/blog/false-positives-and-false-negatives-in-information-security/)
- [Minimalizace falešně pozitivních výsledků při vyšetřování OSINT](https://mediasonar.com/reports/minimize-false-positives-osint-investigations/)

**Snižování kognitivních zkreslení a rozhodování při provádění OSINT:**

Neexistují dokonalí praktici-analytici, každý dělá chyby a dostává se do obtížných nejednoznačných situací (alespoň jednou v životě), tím spíše v podmínkách akutně intenzivního a chronického pracovního přetížení. A je naprosto nezbytné, aby praktik-analytik takové situace znal a rozuměl jim. 

Kognitivní zranitelnosti (v zavedeném chápání) jsou expozice a/nebo tendence k defektům v myšlení: významná kognitivní zkreslení, chybná přesvědčení, kognitivní biasy (předsudky) nebo stereotypní vzorce myšlení, které vytvářejí základ pro predispozici člověka ke kognitivním selháním a vedou ke zkreslení a dysfunkcím [myšlenkových procesů](https://telegra.ph/Cognitive-vulnerabilities-of-the-practitioner-analyst-04-17).

- Kognitivní zranitelnosti praktika-analytika](https://telegra.ph/Cognitive-vulnerabilities-of-the-practitioner-analyst-04-17).
- [Zmírnění kognitivních zkreslení](https://www.researchgate.net/publication/317702457_Cognitive_Bias_Mitigation).
- [Zmírňování kognitivních zkreslení - Wiki](https://en.m.wikipedia.org/wiki/Cognitive_bias_mitigation)
- Rozpoznání a zmírnění kognitivních předsudků: hrozba pro objektivitu](https://www.theiia.org/en/content/communications/press-releases/2022/may/new-recognizing-and-mitigating-cognitive-biases-a-threat-to-objectivity/).
- [Zmírňování kognitivních předsudků: Jak učinit rozhodování racionálním?](https://ideas.repec.org/p/fau/wpaper/wp2020_01.html).
- Vliv kognitivních předsudků na rozhodování odborníků [The Impact of Cognitive Biases on Professionals' Decision-Making: A Review of Four Occupational Areas](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8763848/)
- [HARKing: vytváření hypotéz poté, co jsou známy výsledky](https://pubmed.ncbi.nlm.nih.gov/15647155/)
- [Hypothesizing after the results are known (HARKing)](https://embassy.science/wiki/Theme:Cc742a7b-826d-4201-b33e-457f2ef79fb9) & [Paper](https://www2.psych.ubc.ca/~schaller/528Readings/Kerr1998.pdf)
- [Kognitivní zranitelnost](https://en.m.wikipedia.org/wiki/Cognitive_vulnerability)
- Proč se při výběru mezi alternativami zaměřujeme na jednu vlastnost, kterou porovnáváme?" (https://thedecisionlab.com/biases/take-the-best-heuristic) & [Více](https://fourweekmba.com/take-the-best-heuristic/)
- [Plán IARPA na hackování mozků hackerů](https://fcw.com/security/2023/04/iarpas-plan-hack-brains-hackers/385123/).
- [Myslí kybernetičtí útočníci rychle a pomalu?](https://journals.sagepub.com/doi/pdf/10.1177/1071181319631096)
- [DMBOK2](https://www.dama.org/cpages/body-of-knowledge)
- [Zpráva US Comission - 2005](https://govinfo.library.unt.edu/wmd/about.html)
- 5 kognitivních předsudků, které mohou ovlivnit vaše vyšetřování OSINT](https://www.linkedin.com/pulse/5-cognitive-biases-could-affect-your-osint-investigations-?utm_source=share&utm_medium=guest_mobile_web&utm_campaign=copy)

Většina z nás zažívá "instinktivní pocity", které nedokážeme vysvětlit, jako je okamžité zamilování si (nebo nenávist) nové nemovitosti při hledání domu nebo rychlé úsudky, které děláme při setkání s novými lidmi. Vědci nyní tvrdí, že tyto pocity (nebo intuice) jsou skutečné a že bychom své předtuchy měli brát vážně. 

Neomezujte se na jeden přístup, nebojte se zkoušet experimenty, ale mějte na paměti, že výsledky takových přístupů je třeba vždy **dvakrát ověřit**. Slouží spíše jako učební pomůcky než jako skutečné rady pro vyšetřovatele. Navštivte následující webové stránky:

- [Intuice je víc než jen tušení, tvrdí nový výzkum](https://www.sciencedaily.com/releases/2008/03/080305144210.htm)
- [Intuice jako vznik: Intuice: propojení psychologie, filozofie a organizační vědy](https://www.frontiersin.org/articles/10.3389/fpsyg.2021.787428/full).
- [Intelligence Analysis: Structured Methods or Intuition?] (https://www.academia.edu/4259879/Intelligence_Analysis_Structured_Methods_or_Intuition).
- [Potenciál integrace inteligence a intuice](https://www.thecipherbrief.com/the-potential-of-integrating-intelligence-and-intuition)
- [Sociální inženýrství a ochrana vysoce ceněných cílů](https://www.hensoldt-analytics.com/2023/01/23/social-engineering-osint/)
- [Trace My Shadow Game](https://myshadow.org/trace-my-shadow)
- O čem mluvíme, když mluvíme o OSINT](https://www.authentic8.com/blog/definition-of-osint)
- [Veřejně dostupné informace: Tajemství neutajovaných dat, část I](https://overthehorizonmdos.wpcomstaging.com/2019/04/08/publicly-available-information-the-secret-to-unclassified-data-part-i/) & [Kopie](https://web.archive.org/web/20191117062938/https://othjournal.com/2019/04/08/publicly-available-information-the-secret-to-unclassified-data-part-i/)

**Také:**

**Podle [wondersmith_rae](https://wondersmithrae.medium.com/training-yourself-to-be-an-analytical-thinker-476bdb7e7c99)**: V klasické rétorice se "prvky okolností" vytvořené Aristotelem používají k analýze řečnických otázek již odedávna. Uplatňují se i při současné analýze a lze je použít jako základ pro zkoumání. **(kdo, co, kdy, kde, proč, jakým způsobem, jakými prostředky)**.

Zkrácená, ale stejně hodnotná verze těchto prvků se nazývá "5W a H" neboli Kdo, co, kdy, kde, proč a jak. Tyto otázky se používají v rétorice, religionistice, policejním vyšetřování, žurnalistice a právníky již od dob starověkého Řecka. Říká se, že vyšetřování nemůže být skutečně úplné, dokud se nepodaří zodpovědět všechny W a H. 

Při použití stejných prvků na naše vyšetřování OSINT můžeme klást a zodpovídat podobné otázky. Zodpovězením 5 W se z našich shromážděných údajů začne rýsovat příběh. Nyní je na nás, analyticích, abychom si jednotlivé body stručně propojili. Háček je v tom, že každý, kdo se někdy zabýval výzkumem, ví, že když se začnou odkrývat informace, je snadné uvíznout v králičí noře. 

- [Síla vypnutí smyslů: Jak zvýšit svou kreativitu a mít čistou mysl](https://buffer.com/resources/the-power-of-shutting-down-your-senses-how-to-boost-your-creativity-and-have-a-clear-mind/amp/).
- Trénink analytického myšlení] [Training Yourself to be an Analytical Thinker](https://wondersmithrae.medium.com/training-yourself-to-be-an-analytical-thinker-476bdb7e7c99).
- [Využití stavu mysli OSINT pro lepší online vyšetřování](https://www.sans.org/webcasts/atmic-talk-osint-mind-state-online-investigations-114115/)
- [Nejnovější trendy v SOCMINT, OSINT a kybernetické psychologii](https://www.toddington.com/wp-content/uploads/1Day_OSINT_Masterclass-1-1.pdf)
- 5 kognitivních předsudků, které mohou ovlivnit vaše vyšetřování OSINT](https://www.liferaftinc.com/blog/5-cognitive-biases-that-could-affect-your-osint-investigations)
- [Citizen OSINT Analysts: Motivations of Open-Source Intelligence Volunteers](https://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1670900&dswid=-6049)
- Nový průvodce vyšetřováním a mapováním pachatelů při vyšetřování s využitím otevřených zdrojů](https://piac.asn.au/2023/03/29/new-guide-on-investigating-and-mapping-perpetrators-in-open-source-investigations/) [New guide on investigating and mapping perpetrators in open-source investigations](https://piac.asn.au/2023/03/29/new-guide-on-investigating-and-mapping-perpetrators-in-open-source-investigations/)
- [Zahraniční podnikatel zemřel a odkázal mi 4,6 milionu dolarů, tak jsem použil OSINT a sociální inženýrství k podvodu na podvodníka](https://hatless1der.com/an-overseas-businessman-died-and-left-me-4-6m-so-i-used-osint-social-engineering-to-scam-a-scammer/)
- Cchatgpt-unlock-geolocation-data](https://www.digitaldigging.org/p/4-chatgpt-unlock-geolocation-data)
- [Telegram-osint-vm-díl-2](https://www.cqcore.uk/telegram-osint-vm-part-2/)
- [Studies in Intelligence](https://t.me/devil_may_spy/160)
- [Safeguarding OSINTers: Shielding Against Disinformation Manipulation](https://osintteam.blog/safeguarding-osinters-shielding-against-disinformation-manipulation-dfbbfbf1db08)
- Odhalení digitálního detektiva [Unveiling the Digital Detective: Základní nástroje a techniky OSINT pro vyšetřovatele](https://osintteam.blog/unveiling-the-digital-detective-essential-osint-tools-and-techniques-for-investigators-adf486ad2ccd).

Jakmile dokážete rozlišit informace, roztřídit je, pak další věc, kterou můžete udělat, je začít cvičit. Jak víte, **dobrá praxe vyžaduje dobrou motivaci**! Potřebujete vědět jen jednu věc: lidé si myslí, že zpravodajství je pevně dané - ale není tomu tak. Váš mozek je jako sval; čím více ho používáte, tím více roste. Vzdělávání už není jednorázová záležitost, ale celoživotní zkušenost.

<detaily>
<summary>Rozšířit</summary>
<br />

- [Průvodce pro začátečníky v terénu: Kde a jak se učit OSINT](https://medium.com/the-sleuth-sheet/beginners-field-guide-where-how-to-learn-osint-bd2e11469f31)
- Pasti používané kybernetickými detektivy...](https://medium.com/@ibederov_en/traps-used-by-cyber-detectives-c778b4853f1a)
- [Vyšetřování adres MAC](https://t.me/ibederov_en/18)
- [ULTIMÁTNÍ průvodce psaním zpravodajských zpráv...](https://www.intelligence101.com/the-ultimate-guide-to-writing-intelligence-reports-complete-with-templates-examples/)
- [Zdroje o odolnosti podniků](https://start.me/p/wMgzM5/business-resilience)
- Pracovní postup vyšetřování osob OSINT z hlediska ochrany osobních údajů](https://www.osintme.com/index.php/2022/08/31/person-osint-investigation-workflow-from-a-privacy-perspective/)
- [Setting Your Moral Compass: A Workbook for Applied Ethics in OSINT](https://ethicaljournalismnetwork.org/setting-your-moral-compass-a-workbook-for-applied-ethics-in-osint)
- [Reddit Bureau of Investigation](https://www.reddit.com/r/RBI/)
- [The Dark Arts of OSINT](https://av.tib.eu/en/media/38959)
- [OSINT Wiki](https://www.reddit.com/r/OSINT/wiki/index/)
- [Mapa OSINT](https://cipher387.github.io/osintmap)

</details>

**Také se podívejte na:**

> [Nedávné průzkumy ukazují](https://4discovery.com/2019/09/10/litigating-in-an-e-world-e-discovery-forensics-and-open-source-intelligence-in-legal-research/), že více než 97 % podniků ukládá data v cloudu. Zjistěte, jak identifikovat potenciální zdroje dat v cloudu, vystavovat žádosti o zjištění a provádět zadržení soudních sporů a jak data v cloudu uchovávat, shromažďovat, filtrovat, kontrolovat a vytvářet.

> [Informace relevantní](https://4discovery.com/2019/09/10/litigating-in-an-e-world-e-discovery-forensics-and-open-source-intelligence-in-legal-research/) pro váš případ se nacházejí na internetu a obvykle se skrývají na očích. Obchodní záznamy, registrace doménových jmen, webové stránky, identity online uživatelů, příspěvky na sociálních sítích, fotografie a videa jsou vzdáleny pouze na vyhledávací dotaz. Víte, jak je najít? Zjistěte, jak mohou informace z otevřených zdrojů ovlivnit širokou škálu záležitostí a jak efektivně identifikovat zdroje informací a vyhledávat data z otevřených zdrojů.

- Jazyk zločinců z pohledu psycholingvistiky](https://www.paperdue.com/essay/criminals-language-from-a-psycholinguistics-1851)
- [VYUŽITÍ JAZYKOVÉ ANALÝZY PRO IDENTIFIKACI A HODNOCENÍ PACHATELŮ TRESTNÝCH ČINŮ](https://www.researchgate.net/publication/340985509_FORENSIC_PSYCHOLINGUISTICS_USING_LANGUAGE_ANALYSIS_FOR_IDENTIFYING_AND_ASSESSING_OFFENDERS).
- Forenzní psycholingvistika [využití jazykové analýzy pro identifikaci a posuzování pachatelů](https://criminalprofiling.com/forensic-psycholinguistics-using-language-analysis-for-identifying-and-assessing/).
- [Konečný průvodce lidským zpravodajstvím (HUMINT)](https://www.intelligence101.com/the-ultimate-guide-to-human-intelligence-humint/)
- [Podkopávání sociálního inženýrství pomocí shromažďování zpravodajských informací z otevřených zdrojů](https://www.researchgate.net/publication/283250856_Undermining_social_engineering_using_open_source_intelligence_gathering)
- Signal OSINT - SIGINT](https://worldwidescience.org/topicpages/o/osint+signals+intelligence.html) [Signal OSINT - SIGINT](https://worldwidescience.org/topicpages/o/osint+signals+intelligence.html)
- [E-Discovery, forenzní analýza a zpravodajství z otevřených zdrojů v právním výzkumu](https://4discovery.com/2019/09/10/litigating-in-an-e-world-e-discovery-forensics-and-open-source-intelligence-in-legal-research/)
- [From Dissent to OSINT? Pochopení, ovlivňování a ochrana rolí, reputace a příjmů](https://complexdiscovery.com/from-dissent-to-osint-understanding-influencing-and-protecting-roles-reputation-and-revenue/).
- [Základy: Co je e-Discovery?](https://cdslegal.com/knowledge/the-basics-what-is-e-discovery/)
- [Systém pro organizaci, shromažďování a prezentaci zpravodajských informací z otevřených zdrojů](https://link.springer.com/article/10.1007/s42488-022-00068-4)

# Školení a praxe

**Dobré školicí materiály:**

- [Python for OSINT 21 days](https://github.com/cipher387/python-for-OSINT-21-days)
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
- [Úžasné mapy](https://github.com/simsieg/awesome-maps)

Zde je velmi dobrá hra na protažení mozku, která pomůže trénovat asociativní myšlení - velmi důležitou dovednost pro každého, kdo se zabývá [OSINT](https://twitter.com/hashtag/OSINT?src=hashtag_click):

- [Wikipedia:Wiki Game](https://en.wikipedia.org/wiki/Wikipedia:Wiki_Game)

Když jsem byl malý, hráli jsme hru "5 kroků do Ragnaroku" - cílem bylo v 5 krocích (5 kliknutích) z libovolné náhodné stránky Wikipedie najít stránku o této báji! 🙂.

**Sledujte nejlepší specialisty na OSINT:**

- [twitter.com/UKOSINT](https://twitter.com/UKOSINT) - novinky, nástroje, vtipy
- [twitter.com/dutch_osintguy](https://twitter.com/dutch_osintguy) - známý specialista, řečník
- [twitter.com/jakecreps](https://twitter.com/jakecreps) - každý čtvrtek zveřejňuje úžasné nástroje.
- [twitter.com/OSINTtechniques](https://twitter.com/OSINTtechniques) - sledujte digitální drobky chleba
- The Sleuth Sheet](https://medium.com/the-sleuth-sheet)
- [OSINT Essentials](https://osintessentials.medium.com/)
- Sector035](https://medium.com/@sector035) - Týden v OSINTu.
- Igor S. Bederov](https://medium.com/@ibederov_en) - Sherlock Holmes digitálního věku...
- [twitter.com/OSINTHK](https://twitter.com/OSINTHK) - dobrovolníci využívající OSINT
- Globální komunita OSINT](https://osintfr.com/en/home/) - komunita OSINT z Francie.
- [twitter.com/OSINT_Research](https://twitter.com/OSINT_Research) - nástroje a úžasná data.
- [twitter.com/OSINTtechniques](https://twitter.com/OSINTtechniques) - nástroje a úžasná data
- [twitter.com/OsintJobs](https://twitter.com/OsintJobs) - pracovní místa v OSINTu
- [www.reddit.com/r/OSINT](https://www.reddit.com/r/OSINT) - největší tematický subReddit
- Kanály o OSINT, hackingu, bezpečnosti a tak dále](https://telegra.ph/Channels-about-OSINT-Hacking-Security-and-so-on-04-19)

**Další zdroje:**

> [Kromě tradiční funkce umožnit méně chybných rozhodnutí](https://www.researchgate.net/publication/331073990_Digital_Open_Source_Intelligence_and_International_Security_A_Primer) se publikum moderních zpravodajských služeb rozšiřuje i mimo vedení států či korporací a rozšiřuje se na veřejnost. Již není pouhým varovným mechanismem, ale také zásobárnou know-how a improvizačním fondem pro řešení záležitostí v době neočekávaných krizí.
 
- [Awesome OSINT + Crypto](https://github.com/aaarghhh/awesome_osint_criypto_web3_stuff)
- [Google Hacking](https://seckrd.com/google-hacking)
- [GOSI: GIAC Open Source Intelligence](https://www.giac.org/certification/open-source-intelligence-gosi)
- [SEC487: Sběr a analýza informací z otevřených zdrojů (OSINT)](https://www.sans.org/cyber-security-courses/open-source-intelligence-gathering/)
- [Inteltechniques.net](https://www.inteltechniques.net/)
- [Přednáška o bezpečnosti IT](https://github.com/bkimminich/it-security-lecture/)
- [r4ven Tool](https://github.com/spyboy-productions/r4ven)
- [Unredacter](https://github.com/BishopFox/unredacter)
- [forensicdots.de](https://www.forensicdots.de/)
- [Meta-secret App](https://github.com/meta-secret)
- [Image Research OSINT](https://github.com/cqcore/Image-Research-OSINT)
- [15 nástrojů, které byste měli znát jako bezpečnostní analytici](https://osintteam.blog/15-tools-you-should-know-as-a-security-analyst-f95007e94d99)
- [Portable Secret App](https://mprimi.github.io/portable-secret/)
- [Open Source Intelligence Techniques](https://inteltechniques.com/book1.html)
- [Příručka internetového zpravodajství a vyšetřování](https://www.amazon.com/Internet-Intelligence-Investigation-Handbook-practical/dp/B096TJMV7J)
- [NATO OSINT HandBook](https://github.com/lawsecnet/OPSEC/blob/master/NATO%20OSINT%20Handbook%20v1.2%20-%20Jan%202002.pdf)
- [osintnewsletter.com](https://osintnewsletter.com/)
- [Geolocation OSINT](https://github.com/cqcore/Geolocation-OSINT)
- [geodetective.io](https://geodetective.io/)
- [Další úžasná kniha o OSINT](https://t.me/osintkanal/2049)
- [Social Media OSINT](https://github.com/cqcore/Social-Media-OSINT)
- [Fascinující vyhledávače, které hledají tváře](https://www.makeuseof.com/tag/3-fascinating-search-engines-search-faces/)
- [MegaSeznam nástrojů OSINT](https://pastebin.com/z0FUgiGb)
- [Budoucnost OSINT: vyhledávání lidí pomocí ChatGPT](https://dorksearch.com/blog/future-of-osint-people-searching/)
- [Geolokalizace: V maloobchodním parku](https://nixintel.info/osint/geolocation-at-the-retail-park/)

**Nástroje (AI, ChatGPT, ML, další):**

> [V posledních letech exponenciálně vzrostl zájem veřejnosti o shromažďování a analýzu zpravodajských informací z otevřených zdrojů](https://www.sans.org/webcasts/atmic-talk-osint-mind-state-online-investigations-114115/). S růstem tohoto zájmu se stále více vyšetřování OSINT spoléhá na nástroje a automatizaci a opouští proces analýzy. OSINT byste měli považovat za myšlenkový proces. "Stav mysli OSINT" je klíčový pro sledování vyšetřovacích kroků, výběr správných nástrojů a zdrojů, analýzu dat a podávání zpráv s cílem získat využitelné zpravodajské informace!

- [Mapa nástrojů OSINT](https://metaosint.github.io/chart)
- [Sherlock](https://github.com/sherlock-project/sherlock)
- [gpt.censys.io](https://gpt.censys.io/)
- [ChatGeoPT](https://github.com/earth-genome/ChatGeoPT)
- [ChatGPT pro OSINT: Příklad](https://t.me/osintkanal/2009) | Tip: Použijte [deepl.com](https://www.deepl.com/translator)
- [Emoji OSINT](https://www.dutchosintguy.com/post/cryptography-osint-can-you-read-emoji)
- [Advangle](http://advangle.com/)
- [searchcode.com](https://searchcode.com/)
- [dorkgpt.com](https://www.dorkgpt.com/)
- [OSINT & ChatGPT: 103 nápadů](https://t.me/irozysk/9377)
- [OSINT + AI](https://github.com/jiep/offensive-ai-compilation)
- [OSINT - SAN](https://github.com/Bafomet666/OSINT-SAN)
- [OSINT Buddy](https://github.com/jerlendds/osintbuddy)
- [ChatGPT: Tajná zbraň pro OSINT poháněná umělou inteligencí](https://blog.gopenai.com/chatgpt-the-ai-powered-secret-weapon-for-osint-133a68d8302e)
- [Nezacházejte s nástrojem jako se stříbrným bucharem pro všechny úkoly!](https://osintessentials.medium.com/the-one-osint-tool-you-must-have-to-supercharge-your-investigations-94f5015b6318)
- Nový kód pro OSINT: ChatGPT](https://medium.com/the-sleuth-sheet/the-new-osint-cheat-code-chatgpt-cd54c190fa11) [The New OSINT Cheat Code: ChatGPT](https://medium.com/the-sleuth-sheet/the-new-osint-cheat-code-chatgpt-cd54c190fa11)
- Využití síly nástroje ChatGPT pro OSINT: Praktický průvodce pro vašeho asistenta OSINT s umělou inteligencí](https://hackernoon.com/harnessing-the-power-of-chatgpt-for-osint-a-practical-guide-to-your-ai-osint-assistant)
- [Úžasný bezplatný ChatGPT](https://github.com/LiLittleCat/awesome-free-chatgpt)
- [Ofenzivní AI](https://github.com/jiep/offensive-ai-compilation)
- [Bitcoin Investigation Manual AML](https://www.amazon.com/Bitcoin-Investigation-Manual-AML-Money-Laundering/dp/1077484070)

# Výběr cesty, kterou se vydat...

Někoho bude bavit [analyzovat obrázky](https://29a.ch/photo-forensics/#forensic-magnifier), [satelitní snímky](https://spectator.earth/), počítat čas a místo z [úhlu stínů z fotografie](https://www.suncalc.org/#/40.1789,-3.5156,3/2022.05.05/12:15/1/3) nebo měřit hory [velikost vrcholů](https://www.peakfinder.org/), aby mohl provádět soukromé detektivní vyšetřování. Nebo, řekněme, [dělat OSINT v oblasti kryptografie](https://graph.org/TX-Analysis-tools-04-19), například, v takovém případě budou vaší motivací peníze a seberealizace... Nebo [pátrání po vzácných příbězích](https://www.atlasobscura.com/articles/buying-volcanoes-robert-ripley-paricutin-whakaari.amp) dokonce!

[Čtěte můj kanál, pokud se vám toto téma líbí](https://t.me/officer_cia)... Nebo se někdo může pustit i do [AD-INT](https://medium.com/@ibederov_en/mac-adresa-osint-e539504ae925), který právě teď roste každým dnem. Pro školení dovedností GEOINT doporučuji podívat se na [geoguessr.com](https://geoguessr.com/) & [whereami.io](https://whereami.io/).

**Jen se podívejte na tuto úžasnou myšlenkovou mapu:**

- [Klikni na mě!](http://files.mtg-bi.com/MindMap.jpg).

**Prozkoumejte datové terminály:**

- [Open-Source Intelligence (OSINT) Reconnaissance](https://z3r0trust.medium.com/open-source-intelligence-osint-reconnaissance-9f0bafd672b2).
- Sbírka několika set online nástrojů pro OSINT](https://github.com/cipher387/osint_stuff_tool_collection).
- Tato stránka je určena všem, kdo mají rádi vyšetřování s otevřeným zdrojovým kódem](https://start.me/p/DPYPMz/the-ultimate-osint-collection)
- [Start.me + OSINT](https://start.me/p/Pwy0X4/osint-inception)
- [Open-Source Intelligence (OSINT) za 5 hodin - kompletní kurz - Naučte se OSINT!](https://youtu.be/qwA6MmbeGNo)
- [Follow!](https://twitter.com/Sector035)
- [myosint.training/courses/](https://myosint.training/courses/)
- Srovnání nástrojů OSINT pro typosquatting, jako jsou DNSTwist, DNSRazzle, s monitorováním typosquattingu společnosti Bolster](https://securityboulevard.com/2022/02/comparing-osint-typosquatting-tools-like-dnstwist-dnsrazzle-against-bolsters-typosquatting-monitoring/)
- [* Co je to za písmo?] (https://osintessentials.medium.com/wtf-be0de2230ed2)
- [OSINT Cheatsheet](https://thekaiz3n.com/cheatsheet/2022/01/12/osint.html)
- [Aplikace abduktivního a retrospektivního odvozování pro návrh a analýzu sociologického výzkumu založeného na teorii](https://journals.sagepub.com/doi/10.5153/sro.2819)
- [Abdukce jako aspekt retrodukce](http://www.commens.org/encyclopedia/article/chiasson-phyllis-abduction-aspect-retroduction)
- [Abdukce jako aspekt retrodukce - 2](https://www.degruyter.com/document/doi/10.1515/semi.2005.2005.153-1-4.223/html?lang=en)
- [Abduktivní uvažování](https://en.wikipedia.org/wiki/Abductive_reasoning)

Možná budete chtít i deanonymizovat uživatele telegramu ([čtěte tento kanál](https://t.me/ibederov_en)) nebo se naopak připojit k [counter-OSINT](https://github.com/soxoj/counter-osint-guide-en) bros. Vyzývám vás však, abyste při tom nezapomínali na klíčové dovednosti v oblasti vyhledávání informací, informační analýzy a aplikace informací...

<detaily>
<summary>Rozšíření</summary>
<br />

- Příručka [Counter OSINT Guide](https://github.com/soxoj/counter-osint-guide-en)
- Zdroje [HUMINT VS Social Engineering](https://telegra.ph/HUMINT-VS-Social-Engineering-Resources-03-24)
- Od zapomnění k osvícení [From oblivion to illumination. Část 1 | Na linii kreativity a obrany](https://mirror.xyz/0xc34B1730BA53abD717a1E57A358F39C046053581/Ra_UVvUwOrO5W56k2QpP4jKhYAGMhsNnfvwrdKWQ1EI)
- Jak se něco naučit](https://twitter.com/sahilbloom/status/1662453471608446976) [How to learn anything.

</details>

Vyzdvihnu pro vás několik základních rad - vyhodnocujte informace podle různých kritérií, vždy si zjistěte své "základní nastavení" - je to dobré pro duševní zdraví, nalezené věci by vám neměly zničit základy! Praktikujte to, dělejte to v každodenním životě, aplikujte OSINT tam, kde se to zdá být nesamozřejmé, jak je uvedeno níže:

- [5 způsobů, jak může OSINT pomoci vaší kariéře! - Knowmad OSINT](https://knowmad-osint.com/5-ways-osint-can-help-your-career/).
- Umění útoku](https://books.google.nl/books? id=j583EAAAQBAJ&pg=PT10&lpg=PT10&dq=jak+myslet+jako+osint+mindset&source=bl&ots=JeHrgDkP0q&sig=ACfU3U0UC_u94Qs3wdSXmIt2VsZcJNcyw&hl=en&sa=X&ved=2ahUKEwjIvNrwlcj3AhXD0qQKHZfUA50Q6AF6BAgiEAM#v=onepage&q=jak%20to%20myslet%20jako%20osint%20mindset&f=false)
- [Ontology Population for Open-Source Intelligence](https://ceur-ws.org/Vol-2161/paper27.pdf)
- [Kryptografie a OSINT - základy](https://www.dutchosintguy.com/post/cryptography-osint-the-fundamentals)
- [Využití znaků s nulovou šířkou ke skrytí tajných zpráv v textu (a dokonce k odhalení úniků)](https://null-byte.wonderhowto.com/how-to/use-zero-width-characters-hide-secret-messages-text-even-reveal-leaks-0198692/)
- [OSINT: nástroj pro vyhledávání uživatelských jmen](https://www.secjuice.com/osint-username-search-tool/)
- [Geolocation Challenge Writeup](https://osintteam.blog/geolocation-challenge-writeup-1cd5d5aa299f)
- [Vše o webovém průzkumu a OSINT](https://github.com/pr0xh4ck/web-recon)
- [PainlessPeek Tool - GEOINT](https://github.com/adacable/painlessPeek)
- [ChatGPT-osint Tool](https://github.com/gigz/gpt-osint)
- [Querytool](https://github.com/oryon-osint/querytool)

# Immersive & Gamified Learning: Hry (b)

Připojte se ke komunitám, samozřejmě a chatujte, chatujte! Níže jsem zmínil pouze anglicky mluvící komunity, ale existují i místní, udělejte si vlastní průzkum. Jsem si stoprocentně jistý v kramflecích! Uspějete! Rádi se stýkáte s přáteli? Pokud ano, zkuste si společně zahrát Dozor nebo Encounter (nebo jakoukoli NightGame založenou na luštění kódů nebo geolokaci nebo Escapology nebo Lock-Picking)! 

- [Týmová noční hra DozoR](https://en.wikipedia.org/wiki/Dozor)
- [Lámání kódů](https://en.m.wikipedia.org/wiki/Codebreaking)
- [GeoCaching](https://en.m.wikipedia.org/wiki/Geocaching)
- [Escapology](https://en.wikipedia.org/wiki/Escapology)
- [Lock-Picking](https://www.art-of-lockpicking.com/how-to-pick-a-lock-guide/)

**Podívejte se na:**

- [Ingress](https://www.ingress.com/)
- [Geocaching](https://education.nationalgeographic.org/resource/geocaching/)
- [Escapology](https://www.escapology.com/en)
- [Nejlepší nástroj pro sběr informací 🔎](https://github.com/Moham3dRiahi/Th3inspector)
- [Úžasná inteligence](https://github.com/ARPSyndicate/awesome-intelligence)

**OSINT-hry:**

- [kasescenarios.com](https://kasescenarios.com/)
- [Sourcing.games](https://sourcing.games/)
- [OSINT Exercise #018](https://gralhix.com/list-of-osint-exercises/osint-exercise-018/)
- [osint.games](https://www.osint.games/)
- [spyingchallenge.com](http://spyingchallenge.com/)
- 10 řešení pro začátečníky v oblasti OSINT CTF](https://geckosint.medium.com/10-beginner-osint-ctf-solutions-ae89e557a4b)
- [Další řešení OSINT CTF](https://warnerchad.medium.com/osint-ctfs-9993129c10c7)
- [Seznam výzev OSINT - Reddit](https://www.reddit.com/r/OSINT/comments/vu9i43/looking_for_osint_challenges_ctfs/)
- [2 skvělé tréninkové nástroje OSINT](https://nixintel.info/osint/two-great-osint-training-tools/)
- [Hry související s OSINT - Reddit](https://www.reddit.com/r/OSINT/comments/i62fhp/osint_related_games/)
- [10 nejlepších her založených na lokaci](https://www.digitaltrends.com/gaming/best-location-based-gps-games/)
- 7 geolokačních her, které vás přimějí prozkoumat venkovní prostředí](https://www.samsung.com/uk/explore/entertainment/7-geolocation-games-to-get-you-exploring-the-outdoors/)
- [Hra založená na určování polohy](https://en.wikipedia.org/wiki/Location-based_game)
- Co je to hon na lišku v ham rádiu?" [What is a Fox Hunt in Ham Radio?](https://hamradioplanet.com/what-is-a-fox-hunt-in-ham-radio/)
- 9 virtuálních her, které si zahrajete, když nemůžete být spolu](https://www.realsimple.com/work-life/entertainment/virtual-games)

Pečlivě prostudujte tyto zdroje a vraťte se k nim při svém putování světem sršňů, nezapomeňte na kořeny. Tento článek neodpovídá na otázky, ale spíše nastoluje některé řečnické otázky, aby vás podnítil k zamyšlení!

<detaily>
<summary>Rozšíření</summary>
<br />

- [Comprehensive Counter OSINT](https://github.com/soxoj/counter-osint-guide-en)
- [Counter OSINT](https://github.com/CScorza/OSINTAnonymous)
- [Zpravodajské vyšetřování z otevřených zdrojů: Od strategie k realizaci](https://www.researchgate.net/publication/321531302_Open_Source_Intelligence_Investigation_From_Strategy_to_Implementation)
- Zpravodajství ve věku internetu [Intelligence in the internet age: Vznik a vývoj zpravodajských služeb s otevřeným zdrojovým kódem (OSINT)](https://www.sciencedirect.com/science/article/abs/pii/S0747563211002585)
- [Průvodce zpravodajstvím z otevřených zdrojů (OSINT)](https://greydynamics.com/a-guide-to-open-source-intelligence-osint/)
- [Inteligentní důkazy: Využití zpravodajských informací z otevřených zdrojů (OSINT) v trestním řízení](https://www.researchgate.net/publication/309015913_Intelligent_evidence_Using_open_source_intelligence_OSINT_in_criminal_proceedings)
- [Zpravodajský cyklus: Vytváření OSINT z OSINF](https://www.skopenow.com/news/the-intelligence-cycle-creating-osint-from-osinf)

</details>

Protože se jedná o netypického průvodce, myslím, že stojí za to nabídnout vám seznam televizních pořadů a filmů, které podle mého názoru tak či onak zahrnují OSINT:

- [Seznam filmů OSINT](https://www.aware-online.com/en/osint-films/)
- [VYHLEDÁVÁNÍ](https://youtu.be/3Ro9ebQxEOY)
- Nejnenáviděnější muž na internetu](https://youtu.be/ySFpxEdKxMw)
- [Proč jsi mě zabil?](https://youtu.be/QEXV8Rif8Vc)
- [Web of Make Believe: Death, Lies and the Internet](https://youtu.be/Z_l702HNPAA)
- [Don't F**k With Cats: Hunting an Internet Killer](https://youtu.be/x41SMm-9-i4)
- [Reddit jim zničil život: Nevinné oběti internetové justice](https://youtu.be/hi14dP5Rdm0)
- [Cyber Hell: Exposing an Internet Horror](https://youtu.be/hpceNxQASKw)
- [Who Am I - Kein System ist sicher](https://www.imdb.com/title/tt3042408/)
- [Historie analogového hororu](https://youtu.be/-I_4ph-L19U)
- [Dark Web: Cicada 3301](https://www.imdb.com/title/tt8110246/)
- [Movie 43 (LOL)](https://youtu.be/A9fBCkwDW8c)
- [Pan Robot](https://www.imdb.com/title/tt4158110/)
- [Otevřená okna](https://m.imdb.com/title/tt2409818/)
- [Män som hatar kvinnor](https://m.imdb.com/title/tt1132620/)

**Odkazy:**

> [Open Source Intelligence, běžně označované jako OSINT,](https://www.skopenow.com/news/osintforgood-the-philanthropic-application-of-osint) je sběr, shromažďování a analýza veřejně dostupných informací. OSINT je řemeslo vyvinuté v oblasti národní bezpečnosti, které se nyní rozšířilo do celé řady odvětví, včetně prosazování práva, žurnalistiky, podnikové bezpečnosti, akademického výzkumu a právního sektoru. OSINT lze využít i na podporu charitativních cílů!

- [Nějaké zajímavé filmy týkající se OSINT?] (https://www.reddit.com/r/OSINT/comments/owxp7r/any_cool_movies_related_to_osint/)
- [Seznam filmů o OSINT](https://twitter.com/AllForOsint/status/1581244439271350272)
- [OSINT Movie Time for the Holidays](https://medium.com/@sector035/osint-movie-time-for-the-holidays-7a5f74f18f44)
- Nejlepší filmy o OSINTu](https://medium.com/@ibederov_en/nejlepsi-filmy-o-osINTu-5c3ab580f56)
- Televizní a zpravodajské filmy o špionech, špionáži, rozvědce a špionáži](https://www.intelligence101.com/my-favourite-intelligence-television-and-movies-about-spies-spying-intelligence-and-espionage/)
- [Seznam filmů ministerstva obrany - tabulková verze](https://www.spyculture.com/dod-film-list-spreadsheet-version/)
- Týden v OSINT 2020-12](https://sector035.nl/articles/2020-12)
- [ARG SubReddit](https://www.reddit.com/r/ARG/)
- [OSINT SubReddit](https://www.reddit.com/r/OSINT/)
- [Blockchain OSINT](https://www.forensicxs.com/blockchain-osint-decentraland/)
- [John Doe opět útočí](https://hamzaharooon.medium.com/john-doe-strikes-again-n00bzctf-osint-d2122d54c508)
- [Measurement and Signature Intelligence (MASINT)](https://irp.fas.org/program/masint.htm)
- [One Search To Rule Them All - Boolean Searches For Images](https://nixintel.info/osint/one-search-to-rule-them-all-boolean-searches-for-images/)
- [Průvodce tvorbou loutek SOC](https://medium.com/the-sleuth-sheet/soc-puppet-creation-guide-888768dce96e)
- Tři typy zpravodajských informací pro zpravodajství o hrozbách: Komplexní průvodce](https://medium.com/the-sleuth-sheet/the-three-types-of-intelligence-for-threat-intelligence-a-comprehensive-guide-e8bbf1f26164)
- [Unmasking OSINT: A Data Aggregation Journey](https://medium.com/@VEEXH/unmasking-osint-a-data-aggregation-journey-14bea88eb045)

**OSINT Bookshelf:**

- [Moje nedávno přečtené knihy o OSINT a bezpečnosti - doporučení](https://www.osintme.com/index.php/2021/04/30/my-recently-read-osint-security-books-recommendations/)
- Školení [geodetective.io](https://geodetective.io/)
- The Open Source Intelligence Analysis Bookshelf](https://medium.com/the-sleuth-sheet/the-open-source-intelligence-analysis-bookshelf-942dc05a16bd)
- 7 knih o OSINT, které by si měl přečíst každý analytik](https://www.liferaftinc.com/blog/7-osint-books-every-analyst-should-read?hs_amp=true)
- [Knihy Michaela Bazzella](https://inteltechniques.com/book1.html)
- Co číst, abyste porozuměli zpravodajství a špionáži](https://www.wgu.edu/career-guide/information-technology/osint-career.html#openSubscriberModal)
- Oficiální příručka CIA o tricích a podvodech - H. Keith Melton, Robert Wallace (2009)](https://www.bokus.com/bok/9780061943331/official-cia-manual-of-trickery-and-deception/) & [Link](https://www.google.se/books/edition/The_Official_CIA_Manual_of_Trickery_and/LbrzMtkyCGUC?hl=ru&gbpv=1&dq=inauthor:%22H.+Keith+Melton%22&printsec=frontcover) & [Link2](https://www.bokus.com/bok/9780061943331/official-cia-manual-of-trickery-and-deception/)
- [Ofenzivní nástroje OSINT](https://github.com/wddadk/Offensive-OSINT-Tools)
- [Spycraft](https://books.google.se/books/about/Spycraft.html?id=eJg0WV6sGlEC&redir_esc=y) & [Link](https://www.google.se/books/edition/Spycraft/RHWH7gVIO9cC?hl=ru&gbpv=1&dq=inauthor:%22H.+Keith+Melton%22&printsec=frontcover)
- [Ultimate Spy](https://www.google.se/books/edition/Ultimate_Spy/EObtBgAAQBAJ?hl=ru&gbpv=1&dq=inauthor:%22H.+Keith+Melton%22&printsec=frontcover)
- [Nejprodávanější knihy Kevina Mitnicka](https://www.mitnicksecurity.com/bestselling-books-by-kevin-mitnick)

**Metoda Zettelkasten:**

- [Zettelkastenova metoda s Obsidianem- Jak si dělat chytré poznámky](https://beingpax.medium.com/zettelkasten-method-with-obsidian-how-to-take-smart-notes-with-examples-cdaf348febbd)
- Nastavení Zettelkastenu v Obsidianu: víc než jen aplikace pro psaní poznámek](https://facedragons.com/productivity/setting-up-a-zettelkasten-in-obsidian/) [Setting Up a Zettelkasten in Obsidian: More Than a Note-Taking App](https://facedragons.com/productivity/setting-up-a-zettelkasten-in-obsidian/)
- [obsidian-zettelkasten](https://mattgiaro.com/obsidian-zettelkasten/)
- [Začínáme se Zettelkasten](https://obsidian.rocks/getting-started-with-zettelkasten-in-obsidian/)
- [Úžasný OSINT](https://github.com/jivoi/awesome-osint)
- [Průvodce OSINT](https://github.com/drull1000/OSINT-guide)

# Práce: A-Z

Viděl bych to jako učení se cizímu jazyku. Dobře, naučili jste se ho a přijeli jste do země, kde se jím mluví, žít. Ale všichni tam tento jazyk znají... Takže je důležité umět ještě něco navíc. Typicky je třeba umět psát, dobře komunikovat s lidmi nebo být právníkem. Se vším, co bylo řečeno, různé přístupy vyžadují různé dovednosti a myšlení!

> Mějte na paměti, že OSINT NENÍ "něco jako [front-running/tailgating](https://www.investopedia.com/terms/f/frontrunning.asp) nebo skalpování, ale v reálném životě"!

<detaily>
<summary>Rozšíření</summary>
<br />

- ["Neexistuje nic takového jako zpravodajství s otevřeným zdrojovým kódem"](https://threadreaderapp.com/thread/1633909123988242438.html)
- Jak se stát vyšetřovatelem zpravodajských služeb s otevřeným zdrojem (OSINT)](https://www.wgu.edu/career-guide/information-technology/osint-career.html#close)
- [Vlastně skvělá kniha o útocích a obraně](https://www.amazon.com/Network-Attacks-Defenses-Hands-Approach-ebook/dp/B00A8SN8WQ)
- Průvodce OSINT - Open Source Intelligence](https://www.osintguide.com/2023/01/04/start-a-consulting-business-as-an-osint-expert/)
- The Art of Proactive Defense: Mastering Threat Hunting with OSINT Tools](https://medium.com/@mohitdeswal_35470/the-art-of-proactive-defense-mastering-threat-hunting-with-osint-tools-336683d6d53b) [Umění proaktivní obrany: zvládnutí lovu hrozeb pomocí nástrojů OSINT].
- [Chybějící semestr vašeho vzdělání v oblasti OSINT](https://medium.com/the-sleuth-sheet/the-missing-semester-of-your-osint-education-60b7bd48b7e9)
- [OSINT pro pátrající lidi](https://docs.google.com/spreadsheets/d/1JxBbMt4JvGr--G0Pkl3jP9VDTBunR2uD3_faZXDvhxc/edit#gid=1978517898)
- [AaronCTI's OSINT Resource Collection](https://docs.google.com/spreadsheets/d/1klugQqw6POlBtuzon8S0b18-gpsDwX-5OYRrB7TyNEw/htmlview)

</details>

**Práce:**

- [anonfriendly.com](http://anonfriendly.com/)
- [osintjobs](https://twitter.com/osintjobs)
- [Ukážu vám, jak vydělat peníze pomocí OSINT](https://0xtechrock.gumroad.com/)
- [Python for OSINT 21 days](https://github.com/cipher387/python-for-OSINT-21-days)
- [osintjobs.sociallinks.io](https://osintjobs.sociallinks.io/)
- [Seznam nástrojů pro vyšetřování na řetězci](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List)
- Jak najít práci ve Web3?](web.archive.org/web/20220618210743/https://twitter.com/_prestwich/status/1538267150917308416)
- [www.jobprotocol.xyz](https://www.jobprotocol.xyz/) & vyzkoušejte [HR hry](https://sourcing.games/)!
- Due Diligence
- [Připojte se k již existující posádce...](https://osintfr.com/en/our-osinters-are-talented/)
- Žurnalistika
- SMM
- [AML/Crypto Investigations](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List)
- [strategytribe.io](https://strategytribe.io)
- [Úkoly na částečný úvazek](https://telegra.ph/Scamfari-04-28)
- Detekce úniku osobních informací pomocí OSINT Attack Surface Management](https://osintteam.blog/detect-personal-information-leakage-with-osint-attack-surface-management-4a46923dd2fd)

# Externí data

**Další nástroje (namátkou) k použití v práci:**

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

**Specifické (budou aktualizovány):**

> **Podle [GoldenOwl](https://osintteam.blog/safeguarding-osinters-shielding-against-disinformation-manipulation-dfbbfbf1db08):** Vzhledem k tomu, že boj proti dezinformacím se zintenzivňuje, musí být pracovníci OSINT ostražití a chránit se před manipulací. Osvojením si kritického myšlení, diverzifikací informačních zdrojů, ověřováním informací ze sociálních médií, využíváním nástrojů pro ověřování faktů, udržováním aktuálních informací o dezinformačních technikách, spoluprací s důvěryhodnými komunitami, vzděláváním ostatních, [dodržováním etických standardů](https://osintteam.blog/safeguarding-osinters-shielding-against-disinformation-manipulation-dfbbfbf1db08) a křížovou kontrolou informací se mohou pracovníci OSINT proti manipulaci opevnit a udržet integritu svého výzkumu. 

- [ChatGPT + OSINT](https://m.youtube.com/watch?v=L5OlYdCWzRs&feature=youtu.be)
- [Bonusová sada nástrojů OSINT Twitter Crypto](https://telegra.ph/Bonus-OSINT-Twitter-Crypto-toolset-04-15)
- [Úžasný OSINT Web3](https://github.com/aaarghhh/awesome_osint_criypto_web3_stuff)
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
- [osint-Brazilsko](https://github.com/osintbrazuca/osint-brazuca)
- [spiderfoot](https://github.com/smicallef/spiderfoot)
- [Úžasný kanál TG](https://t.me/osintil)
- [Inpaint-Anything](https://github.com/geekyutao/Inpaint-Anything)
- [metaosint.github.io](https://metaosint.github.io/chart)
- [Maltego Transforms List](https://github.com/cipher387/maltego-transforms-list)
- [OSINT open-source tools catalogue](https://github.com/HowToFind-bot/osint-tools)
- [Šablona pro nové nástroje příkazového řádku OSINT](https://github.com/soxoj/osint-cli-tool-skeleton)
- [Nejlepší zdroje OSINT a záminky pro vishing ze soutěže v sociálním inženýrství na DEF CONu](https://medium.com/@chris.kirsch/top-osint-sources-and-vishing-pretexts-from-def-cons-social-engineering-competition-8e08de4c8ea8)

**Úžasné články (externí):**

> [Jak ukazuje praxe](https://medium.com/@ibederov_en/military-intelligence-using-osint-methods-4aae1df2d812), moderní ozbrojené konflikty vyžadují nové přístupy k organizaci sběru a analýze otevřených dat, které provozujeme v rámci OSINT. Buďte s nimi opatrní a dvakrát si rozmyslete, než začnete jednat.

- Lidský dotek v digitální obraně [Human Touch in Digital Defense: HUMINT v boji proti kybernetickým hrozbám](https://osintteam.blog/human-touch-in-digital-defense-virtual-humints-battle-against-cyber-threats-33b81b3be53b).
- Od nuly k hrdinovi Google Dorking: vylepšení vašeho arzenálu OSINT](https://osintteam.blog/mastering-osint-the-art-of-google-dorking-for-investigators-e0a908055873).
- [Využití ddg.gg pro OSINT](https://www.ghacks.net/2023/04/24/duckduckgo-disables-most-search-filters-from-search/?amp)
- [cybdetective.substack.com](https://cybdetective.substack.com)
- Odhalování skrytých spojení [Uncovering Hidden Connections: Použití Maltego Holehe k mapování digitální stopy osoby](https://medium.com/@philipbcase/uncovering-hidden-connections-using-maltego-holehe-to-map-out-a-persons-digital-footprint-90914d6bcbff)
- [Špionáž PDF](https://t.me/irozysk/9243)
- [Hacktoria - Obchodníci s lidmi](https://medium.com/@wirec47/hacktoria-human-traffickers-b9bb00638c6a)
- [Password OSINT](https://viruszzwarning.medium.com/password-osint-fc4fd750ea8c)
- [Použití umělé inteligence k vývoji realistických účtů Sock Puppet](https://www.raebaker.net/blog/using-ai-to-develop-realistic-sock-puppet-accounts)
- [ARCHIVACE A OSINT](https://latenightafa.noblogs.org/archiving-and-osint/)
- [Úžasný OSINT](https://github.com/jivoi/awesome-osint)
- [Awesome Telegram OSINT](https://github.com/ItIsMeCall911/Awesome-Telegram-OSINT)
- [Vizualizace Darknetu](https://medium.com/@cosmograph.app/visualizing-darknet-6846dec7f1d7)
- [Open Source Intelligence: Průvodce OSINT pro začátečníky](https://www.liferaftinc.com/blog/the-beginners-guide-to-osint)
- [DarkNet OSINT Guide](https://medium.com/the-sleuth-sheet/darknet-osint-guide-984f68fb7ab3)
- [Průvodce pro začátečníky: Kde a jak se učit OSINT](https://medium.com/the-sleuth-sheet/beginners-field-guide-where-how-to-learn-osint-bd2e11469f31)
- [PŘÍRUČKA NÁSTROJŮ A ZDROJŮ OPEN SOURCE INTELLIGENCE 2020](https://i-intelligence.eu/uploads/public-documents/OSINT_Handbook_2020.pdf)
- [Rozpoznávání informačních operací: od nelineární analýzy k rozhodování](https://arxiv.org/pdf/1901.10876.pdf)
- [Analýza OSINT z fondu TOR](https://arxiv.org/pdf/1803.05201.pdf)
- 10 nejlepších nástrojů OSINT pro vyšetřování přezdívek](https://medium.com/@ibederov_en/my-top-10-osint-tools-for-nickname-investigation-40e292fa5c84)

**Několik vynikajících nástrojů:**

 > [Nezapomeňte, že Vaším úkolem pro tento](https://medium.com/@ronkaminskyy/from-zero-to-sherlock-the-ultimate-osint-adventure-5f9d8c45ae2) závěrečný krok je vytvořit plán pro udržování a zlepšování Vašich dovedností v oblasti OSINT. Vyberte si nějaké zdroje pro neustálé vzdělávání, najděte si nějaké výzvy, kterých se můžete zúčastnit, a zvažte možnost zapojení do komunity OSINT. Nakonec zkontrolujte své etické zásady, abyste se ujistili, že vždy pracujete zodpovědně a s respektem. - Ron Kaminsky](https://medium.com/@ronkaminskyy/from-zero-to-sherlock-the-ultimate-osint-adventure-5f9d8c45ae2)

- [datashare.icij.org](https://datashare.icij.org)
- [Pinpoint](https://journaliststudio.google.com/pinpoint/collections)
- [dtsearch.com](https://www.dtsearch.com/)
- [Venator](https://t.me/venatorbrowser)
- [Rámec pro procházení a pavoukování nové generace](https://github.com/projectdiscovery/katana)
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

**Detailní (externí):**

> **Podle [Alessandra Adina](https://medium.com/@alessandraadina/how-to-do-cyber-reconnaissance-a-guide-to-osint-for-non-tech-professionals-da6c7db48699):** Zpravodajský cyklus představuje proces vývoje surových informací do podoby použitelných zpravodajských informací. Tento proces může umožnit osobám s rozhodovací pravomocí přijmout na základě zjištěných skutečností vhodná opatření. Ačkoli různé organizace používají různé varianty zpravodajských cyklů, oblíbený je pětistupňový cyklus: **Plánování, shromažďování, analýza, šíření a zpětná vazba**.

- [OSINT: Jak zjistit informace o komkoli](https://osintteam.blog/osint-how-to-find-information-on-anyone-5029a3c7fd56)
- OSINT - Průvodce pro začátečníky (část 1)](https://medium.com/@Aardwarewolf/what-is-osint-part-1-91aaa3890643).
- [OSINT: ZÁKLADY](https://i-intelligence.eu/courses/osint-foundations)
- Jak používat OSINT k odhalování úniků a narušení bezpečnosti dat](https://www.liferaftinc.com/blog/how-to-use-osint-to-detect-data-leaks-and-breaches)
- [Úvod do OSINT](https://infosecwriteups.com/introduction-to-osint-2c92597988d1)
- Jak zlepšit odhalování kybernetických útoků pomocí sociálních médií?" [How to Improve Cyber Attack Detection Using Social Media?](https://www.geeksforgeeks.org/how-to-improve-cyber-attack-detection-using-social-media/)
- Uniká na webu informace? Pomocí těchto nástrojů to zjistíte](https://www.tech.gov.sg/media/technews/are-you-leaking-information-on-the-web) [Are you leaking information on the web? Use these tools to find out](https://www.tech.gov.sg/media/technews/are-you-leaking-information-on-the-web)
- OSINT: Úniky a narušení bezpečnosti dat](https://www.osintguru.com/blog/osint-data-leaks-and-data-breaches)
- OSINT s gOSINTem](https://brandefense.io/blog/osint-with-gosint/)
- [Seznam webových zdrojů OSINT](https://github.com/OhShINT/ohshint.gitbook.io/blob/main/Lists_of_OSINT_Web_Resources/1-Complete-List-of-OSINT-Web-Resources.md)
- [Myšlenková mapa OSINT/SOCMINT](http://files.mtg-bi.com/MindMap.jpg)
- [Jak najít - Robot](https://t.me/HowToFind)
- [Hra s hesly](https://neal.fun/password-game/)
- [Jak používat OSINT v kybernetické bezpečnosti](https://www.molfar.global/en-blog/how-to-use-osint-in-cybersecurity)
- OSINT (OPEN-SOURCE INTELLIGENCE) - staňte se těžko hacknutelnými!" [OSINT (OPEN-SOURCE INTELLIGENCE) - become hard to hack!](https://somprt.com/our-series/osint-open-source-intelligence/)
- [Téma GitHub OSINT](https://github.com/topics/open-source-intelligence?o=desc&s=stars)
- [SOCMINT - nebo spíše OSINT sociálních médií](https://research.securitum.com/socmint-or-rather-osint-of-social-media/)

**Další konkrétní zdroje (externí):**

> **Podle [Alessandra Adina](https://medium.com/@alessandraadina/how-to-do-cyber-reconnaissance-a-guide-to-osint-for-non-tech-professionals-da6c7db48699):** Termín, se kterým se můžete setkat v oblasti OSINT, je "šedá literatura". Jedná se o interní dokumenty, které nejsou určeny pro veřejné použití, ale bohužel se mohou snadno dostat na místa, kde je lze vyhledávat. Příkladem mohou být technické zprávy, bulletiny, faktury, obchodní nabídky nebo žádosti o návrhy.

> Zásadní je porozumět hodnotě informací vaší organizace, potenciálním vektorům útoku a tomu, kdo může být cílem phishingových útoků nebo jiných typů sociálního inženýrství. OSINT vám může pomoci při vyhodnocování těchto rizik a plánování vhodné obrany.

- [OrienterNet Visual Localization in 2D Public Maps with Neural Matching](https://github.com/facebookresearch/OrienterNet)
- Nástroje OSINT - Airtable](https://airtable.com/embed/shrYXDdO1V5y33lIX/tblgDtMXI4fxtg9Op)
- [OSINT - HUMINT](https://docs.google.com/spreadsheets/d/1JxBbMt4JvGr--G0Pkl3jP9VDTBunR2uD3_faZXDvhxc/edit#gid=1978517898)
- [Ultimate OSINT](https://start.me/p/DPYPMz/the-ultimate-osint-collection)
- [Seznam OSINT](https://start.me/p/ZME8nR/osint)
- [Curated OSINT List](https://start.me/p/7kxyy2/osint-tools-curated-by-lorand-bodo)
- [OSINT Inception](https://start.me/p/Pwy0X4/osint-inception)
- [Geolocation-OSINT](https://github.com/cqcore/Geolocation-OSINT)
- [researchaide.org](https://www.researchaide.org/)
- [botster.io/bots Crawling](https://botster.io/bots)
- [Další úžasný seznam OSINT](https://start.me/p/rx6Qj8/nixintel-s-osint-resource-list)
- [Cryptocurrency OSINT](https://start.me/p/ek4rxK/cryptocurrency)
- [Awesome On-Chain Investigations HandBook](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List/blob/main/README.md)
- [Investigator tools](https://start.me/p/gyaOJz/investigator-tools)
- [Sbírka několika set online nástrojů pro OSINT](https://github.com/cipher387/osint_stuff_tool_collection)
- [Rawsec's CyberSecurity Inventory](https://inventory.raw.pm/tools.html#title-tools-osint)
- [OSINT-TOOLS-CLI](https://github.com/Coordinate-Cat/OSINT-TOOLS-CLI)
- [Geoestimation](https://labs.tib.eu/geoestimation/)
- [Použití vyhledávačů OSINT ke shromažďování informací o kybernetických hrozbách](https://osintteam.blog/using-osint-search-engines-to-collect-cyber-threat-intelligence-3e9ace82eb64)
- [GraphSense Maltego Transform](https://github.com/INTERPOL-Innovation-Centre/GraphSense-Maltego-transform)
- [leakix.net](https://leakix.net/)
- [Officer_CIA X MaxWayld: Přehled obsahu](https://officercia.medium.com/officer-cia-x-maxwayld-content-overview-39fa3011a73f)
- Kanály o OSINT, hackingu, bezpečnosti a tak dále](https://graph.org/Channels-about-OSINT-Hacking-Security-and-so-on-04-19)
- [Zkoumání temné strany: Nástroje a techniky OSINT pro odhalování operací na temném webu](https://www.sans.org/blog/exploring-the-dark-side-osint-tools-and-techniques-for-unmasking-dark-web-operations/).

**Telegram + Discord: Bezpečnost, OSINT, SOCMINT:**

 > Podle [Rona Kaminského](https://osintteam.blog/unveiling-the-digital-detective-essential-osint-tools-and-techniques-for-investigators-adf486ad2ccd): OSINT způsobil revoluci ve světě vyšetřování a umožňuje jednotlivcům i organizacím odhalovat cenné informace, řešit složité problémy a přijímat informovaná rozhodnutí. [Schopnost využívat](https://osintteam.blog/unveiling-the-digital-detective-essential-osint-tools-and-techniques-for-investigators-adf486ad2ccd) obrovské množství dat dostupných v otevřených zdrojích otevřela nové možnosti a změnila prostředí vyšetřování. Efektivním využíváním nástrojů OSINT mohou vyšetřovatelé ušetřit čas, shromáždit komplexní informace a odhalit souvislosti, které by jinak mohly zůstat skryté. Techniky a metodiky zkoumané v této příručce poskytují plán pro vedení důkladných a úspěšných vyšetřování OSINT.

- Jak zjistit přesnou polohu telefonu, tabletu nebo počítače](https://medium.com/@ibederov_en/how-to-find-the-exact-location-of-phone-tablet-or-pc-b953a60421a9)
- [osint-mindset.gitbook.io](https://osint-mindset.gitbook.io) | Tip: Použijte [deepl.com](https://www.deepl.com/translator)!
- [Discord OSINT Toolset](https://telegra.ph/Discord-OSINT-Toolset-04-11)
- [DiscordOSINT](https://github.com/AtonceInventions/DiscordOSINT)
- [Telegram OSINT](https://github.com/cqcore/Telegram-OSINT)
- [Zdroje OSINT Discord](https://github.com/Dutchosintguy/OSINT-Discord-resources)
- [TelegramOnlineSpy](https://github.com/Forichok/TelegramOnlineSpy)
- [Odkazy na Discord a Telegram OSINT](https://github.com/Ginsberg5150/Discord-and-Telegram-OSINT-references)
- [Úžasný Discord](https://github.com/jacc/awesome-discord)
- [Awesome Telegram OSINT](https://github.com/ItIsMeCall911/Awesome-Telegram-OSINT)
- [Darvester](https://github.com/darvester/darvester)
- [Telegram & Discord OpSec](https://officercia.mirror.xyz/dlf6ZEXq3FLE21ZY2jeJ0cBDyuZu8XIF9DEJAQ07nk8)
- [Discord OpSec pro servery](https://officercia.mirror.xyz/x4nGX6YwhhmHj8TaQ53kBR5b5M1Ei_Y9_l1Vpext-Hk)
- [If you have been scammed...](https://officercia.mirror.xyz/X5Q0uPwvlgZ6BrvCmyqXlXHFgLAWrMtzAHSvjzrDS7c)

**Podívejte se na mé články:**

- [Navigace (mé články)](https://officercia.mirror.xyz/Uc1sf64yUCb0uo1DxR_nuif5EmMPs-RAshDyoAGEZZY)
- [Původní článek](https://officercia.mirror.xyz/5KSkJOTgMtvgC36v1GqZ987N-_Oj_zwvGatOk0A47Ws)
- [OpSec Going Smart](https://officercia.mirror.xyz/fsRT9NC29GzeQAl-zvAMJ9L-hYUYvX1CPUkt97Vuuwo)
- [OpSec Going Smarter](https://officercia.mirror.xyz/B9hBom4jGhkV0C-47E4YBz8tBJkb0a7zVwQR0jITIyM)
- [OpSec Going Smarter: Secure Smartphones](https://officercia.mirror.xyz/0tlSSF2LDTOnnMN41R5Uc1kTpo-G-kXljn8pT0a1YLY)
- [Výběr spolehlivého poskytovatele VPN pro život i práci](https://officercia.mirror.xyz/x91hTIDFrAL0lgqICRgWU7fLouuCMgvopQ9ZRvRXCLg)
- [Ultimátní seznam pravidel, kterými by se měl řídit každý přeživší na řetězci, aby zůstal v bezpečí!] (https://officercia.mirror.xyz/_nD1Rtxe1PplK-NQzIq9sl-KNtajQG0aKqYsV36RTjA)
- [QR kód: podceňované nebezpečí](https://officercia.mirror.xyz/aN6giRkUsNd0o0bmjZVeZb2htkO_Ve16gMsARU6RBfM)
- [Nejvýznamnější milníky ve vývoji komunikací](https://officercia.mirror.xyz/G4782jMUpA_kkIpwakphbd6djX85cxRGS-pjBipc8Yk)
- Jak vyhrát válku, obelstít KGB a ochránit svůj kryptoaktivní majetek před krádeží pomocí steganografie](https://officercia.mirror.xyz/8ecJG-s_5E6J1t-h8gUNGqV3hbX8If-E5NnrFrOJHUA).
- Útoky prostřednictvím reprezentativního vzorku : mýty a realita](https://officercia.mirror.xyz/WeAilwJ9V4GIVUkYa7WwBwV2II9dYwpdPTp3fNsPFjo)
- Jak se můžete stát specialistou OSINT v jedné armádě?" [How can you become a one-man-army OSINT specialist?] (https://officercia.mirror.xyz/5KSkJOTgMtvgC36v1GqZ987N-_Oj_zwvGatOk0A47Ws)
- [Nejlepší bezpečnostní postupy pro Telegram a Discord](https://officercia.mirror.xyz/dlf6ZEXq3FLE21ZY2jeJ0cBDyuZu8XIF9DEJAQ07nk8)

# Projekt podpory

Podpora je pro mě **velmi** důležitá, díky ní můžu trávit méně času v práci a dělat to, co mě baví - vzdělávat uživatele DeFi & Crypto :sparkling_heart:

Pokud chcete podpořit mou práci, zvažte prosím možnost přispět mi na adresu:

- **[0xB25C5E8fA1E53eEb9bE3421C59F6A66B786ED77A](https://etherscan.io/address/0xB25C5E8fA1E53eEb9bE3421C59F6A66B786ED77A)** — ERC20 & ETH [officercia.eth](https://etherscan.io/enslookup-search?search=officercia.eth)

- **[17Ydx9m7vrhnx4XjZPuGPMqrhw3sDviNTU](https://blockchair.com/bitcoin/address/17Ydx9m7vrhnx4XjZPuGPMqrhw3sDviNTU)** - BTC

- **4AhpUrDtfVSWZMJcRMJkZoPwDSdVG6puYBE3ajQABQo6T533cVvx5vJRc5fX7sktJe67mXu1CcDmr7orn1CrGrqsT3ptfds** - Monero XMR

Můžete mi také poslat dar na adresu z [tohoto úložiště](https://github.com/OffcierCia/support)!

**Podívejte se také na:**

- [Můj blog na serveru Mirror](https://officercia.mirror.xyz/UpFfG7-1E4SDJttnmuQ7v4BMc4KrCXzo80vtx7qV-YY).

### Děkuji! 🙏
