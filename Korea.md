# 비정형 OSINT 가이드

#### 지금까지 본 것 중 가장 특이한 OSINT 가이드. 이 리포지토리는 지루한 전문가만을 위한 것입니다. 

#### PR을 환영합니다! 작은 수정부터 번역, 문서 또는 추가하고 싶은 도구까지 무엇이든 풀 리퀘스트를 제출해 주세요.

> 고지사항: 모든 정보(도구, 링크, 문서, 텍스트, 이미지 등)는 교육 목적으로만 제공됩니다! 또한 모든 정보는 공개 출처의 데이터를 기반으로 합니다. 작성자가 아닌 귀하의 행동에 대한 책임은 전적으로 귀하에게 있습니다** ❗️

[![지원 프로젝트](https://img.shields.io/badge/Support-Project-critical)](https://github.com/OffcierCia/support/blob/main/README.md)
       [![메일](https://img.shields.io/badge/Mail-offcierciapr%40protonmail.com-brightgreen)](mailto:offcierciapr@protonmail.com)


# 여기서 시작

**체크 아웃:**

- 탐색(내 기사)](https://officercia.mirror.xyz/Uc1sf64yUCb0uo1DxR_nuif5EmMPs-RAshDyoAGEZZY)
- 원본 기사](https://officercia.mirror.xyz/5KSkJOTgMtvgC36v1GqZ987N-_Oj_zwvGatOk0A47Ws)
- [여기에도 게시!](https://officercia.medium.com/the-atypical-osint-guide-2023-276a8d00959)

오늘은 좋은 OSINT 수사관이되는 방법에 대해 이야기하고 싶지만 대화를 계속하기 위해 약간의 면책 조항을 만들고 싶습니다. 주제가 매우 방대하고 단일 가이드에서 모든 것을 설명 할 수 없기 때문에 일부 측면 만 말씀 드리지만이 길을 통과하는 방법과 방법을 보여 드리려고 노력할 것입니다. 이 매뉴얼은 OSINT 전문가들의 수년간의 작업의 정점입니다. 이 가이드북을 조언과 경로의 모음집이라고 생각하세요!

이 에세이는 교육용으로 작성되었음을 명심하세요! 자신의 행동을 신중하게 고려하지 않으면 기소되거나 더 나쁜 결과를 초래할 수 있습니다! 항상 윤리 및 관련 법률(예: GDPR 등)을 염두에 두세요... 개인이 종종 해킹과 전쟁을 낭만적으로 생각하는 것과 같은 방식으로 OSINT 및 온체인 조사를 낭만적으로 생각해서는 안 됩니다!

- [보스턴 폭탄 테러: 인터넷 수사관들이 잘못한 방법](https://www.bbc.com/news/technology-22214511)
- [osint? wtf??](https://ohshint.gitbook.io/oh-shint-its-a-blog/osint/osint-wtf)

> 마지막으로, 여러분이 하는 모든 일은 여러분이 달성해야 하는 결과를 기반으로 합니다! 모든 도구와 링크를 사용하는 대신 신뢰할 수 있고 검증된 출처를 선택할 수 있어야 합니다. 주어진 경로를 통해 자신만의 여정을 구성할 수 있어야 합니다! 그 다음에는 제가 안전하다고 판단하고 고객에게 추천하는 방법에 대해 알려 드리겠습니다! OSINT 전문가들은 수십 년 동안 이 매뉴얼을 개발하면서 모든 단어에 그들의 전문 지식을 공유했습니다. 다시 한 번, 이 가이드북은 조언과 경로를 정리한 것이라고 생각하세요.

또한 OSINT는 주변 세계에 대해 배울 수 있는 또 다른 수단일 뿐 "즉시 돈을 벌기 위한" 방법이 아니라는 점을 명심하세요. 재충전을 위해 항상 휴식을 취하세요! 여러분의 몸과 마음이 중요합니다!

- 언제 멈춰야 하는지 아는 법](https://www.lennysnewsletter.com/p/how-to-know-when-to-stop)
- [1000세 뱀파이어가 되는 방법](https://www.lesswrong.com/posts/5QpufhoH2ASnppsjs/how-to-become-a-1000-year-old-vampire)
- [빨리 배우는 방법](https://degatchi.com/articles/how-to-learn-fast/)
- 마인드맵을 사용하여 두뇌의 창의성과 잠재력을 발휘하는 방법](https://lifehacker.com/how-to-use-mind-maps-to-unleash-your-brains-creativity-1348869811)
- [누구나 OSINT를 할 수 있나요?](https://medium.com/osintfun/can-everybody-do-osint-f5d5e6128445)
- 대리 트라우마](https://osintcurio.us/2020/06/08/vicarious-trauma-and-osint-a-practical-guide/)

이 정보는 당신을 더 좋게 만들거나 나쁘게 만들지 않습니다. 인간은 종으로서 주변 환경에 적응하려는 성향을 가지고 있으며, 이는 우리 모두가 알다시피 지식, 관찰, 방법론에서 시작됩니다. 자신을 돌보고, 행동의 결과를 고려하며, 타인의 프라이버시를 존중하세요. 빨간 선을 넘지 마세요!

<details>
<summary>확장</summary>
<br />

- [OSINT + 암호화](https://www.forensicxs.com/blockchain-osint-decentraland/)
- 암호화폐 해킹과 보안 사고를 조사하는 방법](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List)
- [osint.sh 올인원 OSINT 도구 목록](https://osint.sh/)
- OSINT의 아직 개발되지 않은 금광: 기회, 열린 도전과 미래 트렌드](https://www.researchgate.net/publication/338495014_The_Not_Yet_Exploited_Goldmine_of_OSINT_Opportunities_Open_Challenges_and_Future_Trends)

</details>

행동하기 전에 항상 두 번 생각하고, 법을 준수하고, 보안 규칙을 따르세요. 사회 조사를 돕거나 수행하고 싶지만 경험이 부족하다면, 피해자나 피해자를 구하려는 사람들에게 해를 끼치지 않도록 경험이 많은 사람에게 도움을 요청하세요. 한편, 제 글에서는 실사 및 민간 금융 정보에서 영감을 받아 **민간** 애플리케이션에 초점을 맞춘 OSINT의 또 다른 적용 사례를 소개합니다. 이것이 바로 저의 비전이며, 여러분도 이 비전을 받아들여 주시길 바랍니다.

- 정보 연구: 정보 수집의 유형](https://usnwc.libguides.com/c.php?g=494120&p=3381426)
- [다양한 유형의 정보 수집 분야 이해](https://www.maltego.com/blog/understanding-the-different-types-of-intelligence-collection-disciplines/)
- 인텔테크놀로지스닷컴](https://inteltechniques.com)
- [OSINT의 역사: 스파이 정보 제공부터 거짓말 탐지까지](https://www.skopenow.com/news/a-history-of-osint)
- 오픈 소스 정보 조사: 전략에서 실행까지](https://www.researchgate.net/publication/321531302_Open_Source_Intelligence_Investigation_From_Strategy_to_Implementation)
- [역 이미지 검색](https://www.numlookup.com/reverse-image-search)

### **포스가 함께하길!**

# 소개 민간 OSINT

우선, 악수 이론을 기본으로 하여 보안회사 직원이 수행하는 독싱, 군사용 GEO-INT 또는 VC 펀드 직원이 투자할 새로운 프로젝트를 찾기 위해 수행하는 미디어 OSINT와 직접적으로 연관될 수 있기 때문에 OSINT를 일련의 기술 또는 마인드셋으로 간주하겠다고 말하고 싶습니다....

- [OSINT는 마음의 상태](https://medium.com/secjuice/osint-as-a-mindset-7d42ad72113d)
- 오픈소스 인텔리전스(OSINT)의 인지 편향과 비판적 사고](https://deepsec.net/docs/Slides/2014/Cognitive_Bias_and_Critical_Thinking_in_Open_Source_Intelligence_(OSINT)_-_Benjamin_Brown.pdf)
- 오픈 소스 인텔리전스의 간략한 역사](https://www.bellingcat.com/resources/articles/2016/07/14/a-brief-history-of-open-source-intelligence/)
- 미국 역사상 최대 규모의 범죄 수사를 지원한 오픈소스 정보](https://www.isdglobal.org/digital_dispatches/jan-6-series-how-osint-powered-the-largest-criminal-investigation-in-us-history/)

...또는 주요 웹3.0 해킹 사건을 조사하는 암호화 포렌식 전문가에게도 유용합니다. 즉, 정보를 다루고 평가하고 순위를 매기는 방법일 뿐이기 때문에 삶의 모든 영역에서 사용할 수 있으며, 우리 모두가 정보 시대에 살고 있다는 사실을 잊지 마세요.

<details>
<summary>확장</summary>
<br />

- 암호화폐 해커와 사기꾼을 추적하는 블록체인 형사들을 만나보세요](https://www.vice.com/en/article/xgd9zw/meet-the-blockchain-detectives-who-track-cryptos-hackers-and-scammers)
- [특별 "블록체인 수사" 모음집](https://t.me/officer_cia/236)
- 암호화폐 해킹 및 보안 사고 조사 방법: A-Z](https://officercia.mirror.xyz/BFzv17UwH6QG4q711NAljtSiP8eKR17daLjTdmAgbHw)
- 온체인 조사 핸드북](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List)
- 오픈소스 인텔리전스(OSINT) 초보자 가이드]() 기법과 도구](https://medium.com/@mohitdeswal_35470/the-beginners-guide-to-open-source-intelligence-osint-techniques-and-tools-6a91b9c37ee1)
- [어썸 인텔리전스](https://github.com/ARPSyndicate/awesome-intelligence)

</details>

위에서 말한 모든 것은 스스로 개발할 수 있지만 모든 방향의 본질은 정보의 흐름에있는 동안 귀중한 정보, 이상을 알아 차리고 차이점을보고 사실을주의 깊게 분석하고 논리적 체인을 구축하는 능력과 동일합니다. 자신의 정보와 자신의 데이터를 확인하는 것부터 시작하세요: 자신에 대한 OSINT 조사를 해보세요. 모든 데이터를 수집하고, 시각화한 다음, SERM/ORM 기법을 사용하여 지우세요.

- SERM](https://thebusinessprofessor.com/seo-social-media-direct-marketing/search-engine-reputation-management-definition)
- [ORM](https://medium.com/elfsight-blog/introduction-to-search-engine-reputation-management-serm-44467c891c0b)
- OSINT 수행 시 보안 및 개인정보 보호 실패 사례](https://www.osintme.com/index.php/2022/01/17/examples-of-opsec-and-privacy-fails-when-doing-osint/)
- 왓브리치](https://github.com/Ekultek/WhatBreach)
- [더 많은 옵섹 연구](https://github.com/lawsecnet/OPSEC)
- OSINT 연구자를 위한 기본 OPSEC 팁 & 트릭](https://web.archive.org/web/20221108024236/https://osintcurio.us/2019/04/18/basic-opsec-tips-and-tricks-for-osint-researchers/amp/)
- 텔레그램 OSINT와 프라이버시에 대한 궁극의 가이드](https://www.osintme.com/index.php/2022/10/18/the-osint-me-ultimate-guide-to-telegram-osint-and-privacy/)
- "누군가"가 하기 전에 스스로 멍청해지기](https://osintteam.blog/dork-yourself-before-someone-does-aa49d0c1929f)

첫 번째 강의, 제가 조언 할 모든 리소스를 알려 드리고자합니다. 저는 이전에 혼자서 공부했습니다:

- [그래서 당신은 구글을 할 수 있다고 생각하십니까? - Henk van Ess와 함께하는 워크샵](https://youtu.be/uyqXS5lL-mc)
- [OSINT 오리진 #1 - Jean-Marc Manach/@manhack](https://youtu.be/XrTFzZ77eEI)
- [멋진 OSINT 마인드맵](http://files.mtg-bi.com/MindMap.jpg)
- 텔레그램 & 디스코드 보안 모범 사례](https://officercia.mirror.xyz/dlf6ZEXq3FLE21ZY2jeJ0cBDyuZu8XIF9DEJAQ07nk8)
- OSINT 목적의 사용자 이름 생성에 대한 결정적인 가이드](https://github.com/soxoj/username-generation-guide)
- 결정론적 사고에 저항하기](https://zephoria.medium.com/resisting-deterministic-thinking-52ef8d78248c)

# 마인드 매핑

먼저 마인드 매핑과 같은 개념을 세분화해 보겠습니다. 다양한 기준에 따라 정보를 정렬하는 방법을 가르치는 것은 매우 중요하며, 원하는 정보를 절대적으로 정렬하는 연습을 할 수 있다고 생각합니다!

- 마인드맵](https://en.wikipedia.org/wiki/Mind_map)
- [중급 오스틴터가 되려면 무엇이 필요하나요? 쇼단이 OSINT 조사에 어떻게 기여할 수 있나요?](https://podtail.com/en/podcast/osintcurious/episode-51-what-do-you-need-to-become-an-intermedi/)
- 오픈소스 리서치 시작을 위한 첫걸음](https://www.bellingcat.com/resources/2021/11/09/first-steps-to-getting-started-in-open-source-research/)
- 오픈소스 인텔리전스 및 OSINT 수사에 관한 모든 것](https://www.maltego.com/blog/what-is-open-source-intelligence-and-how-to-conduct-osint-investigations/)

**Maltego란 무엇이며 왜 OSINT에 사용하나요?](https://wondersmithrae.medium.com/a-beginners-guide-to-osint-investigation-with-maltego-6b195f7245cc)** Maltego는 다양한 오픈소스 데이터 리소스를 마이닝하고 해당 데이터를 사용하여 연결 분석을 위한 그래프를 생성하는 데이터 마이닝 도구입니다. 그래프를 통해 이름, 이메일 조직 구조, 도메인, 문서 등의 정보를 쉽게 연결할 수 있습니다. Maltego는 Java를 사용하므로 Windows, Mac, Linux에서 실행할 수 있으며 Buscador나 Kali와 같은 많은 OSINT Linux 배포판에서 사용할 수 있습니다. 

기본적으로 많은 양의 정보를 구문 분석하고 다양한 오픈 소스 웹사이트를 검색한 다음, 조각들을 조합하는 데 도움이 되는 멋진 그래프를 제공합니다. Maltego는 조사 중 언제든 리소스로 사용할 수 있지만, 타겟이 도메인인 경우 처음부터 Maltego로 네트워크 매핑을 시작하는 것이 좋습니다.

#### 학교 다닐 때 다들 치트 시트 만들지 않았나요? 앞으로는 말테고 스킬로 발전할 것이기 때문에 다시 만들어야 할 때입니다!

- [귀하와 귀하의 팀을 위한 최고의 OSINT 및 인포섹 리소스 (2022 에디션): 100개 이상의 블로그, 팟캐스트, 유튜브, 책 등!](https://www.maltego.com/blog/top-osint-infosec-resources-for-you-and-your-team/)
- Maltego를 사용한 OSINT 조사 초보자 가이드](https://wondersmithrae.medium.com/a-beginners-guide-to-osint-investigation-with-maltego-6b195f7245cc)
- 말테고 - 사이버 무기 연구소 - OSINT 분석가처럼 조사하기](https://youtu.be/46st98FUf8s)
- OSINT 기술 학습/개발을 위한 무료 디지털 배지](https://www.reddit.com/r/OSINT/comments/kgew5d/free_digital_badges_for_learning_developing_osint/)
- 자녀가 과외 활동에 참여하도록 장려하는 팁](https://talentgum.com/blog/tips-to-encourage-your-child-to-participate-in-extracurricular-activities)
- 체스를 잘하기 위해 필요한 기술 + 체스를 향상시키는 방법](https://skillspointer.com/skills-for-chess/)

> 작은 팁 - [파워 서칭](https://www.edx.org/course/power-searching-with-google)을 다른 IP, 다른 시간대, 다른 [검색 엔진](https://github.com/tasos-py/Search-Engines-Scraper)을 통해 수행하세요.

VEEXH](https://wondersmithrae.medium.com/a-beginners-guide-to-osint-investigation-with-maltego-6b195f7245cc)에 따른 ## OSINT 기초 이해:

- a. OSINT의 개념과 정보 수집에서 그 중요성을 파악합니다.
- b. OSINT 출처의 유형(예: 소셜 미디어, 공공 기록, 온라인 포럼, 뉴스 매체)을 숙지합니다.
- c. OSINT 수집 시 윤리적 및 법적 고려 사항을 숙지합니다.

**기술 능력 개발 :**

- a. 기본적인 컴퓨터 및 인터넷 사용법을 습득합니다.
- b. 검색 엔진 및 연산자를 사용하여 고급 검색 기술을 배웁니다.
- c. 익명성의 중요성을 이해하고 VPN, 프록시 및 Tor 네트워크 사용 기술을 습득합니다.
- 말테고, 쇼단, 구글 도크스 등 필수 OSINT 도구에 익숙해집니다.

**OSINT 컬렉션 마스터하기 :**

- a. 인텔리전스 요구 사항을 식별하고 우선순위를 정하는 방법을 배웁니다.
- b. 다양한 출처에서 데이터를 수집하는 체계적인 접근 방식을 개발합니다.
- c. 사회 공학, 수동 정찰, 온라인 정찰 기술을 연마합니다.
- 디. 지리적 위치, 이미지 분석, 개인 및 조직에 대한 정보 추적에 대한 전문 지식을 습득합니다.

**정보분석 및 평가(OSINT) :**

- 가. 링크 분석, 타임라인 분석, 감성 분석 등 다양한 분석 기법을 학습합니다.
- 비. 비판적 사고와 인지적 편향에 대한 인식을 기릅니다.
- 씨. 정보 주기의 중요성을 이해하고 이를 OSINT 분석에 적용합니다.
- 디. 출처와 정보의 신뢰성과 신뢰성을 평가합니다.

**OSINT 전파 및 보고 :**

- a. 효과적인 커뮤니케이션의 원칙을 숙지한다.
- b. 정보 보고서, 브리핑, 시각화 작성 방법을 익힙니다.
- c. 다양한 청중에 맞게 보고를 조정하는 것의 중요성을 이해합니다.
- 디. 명확하고 간결하며 실행 가능한 방식으로 조사 결과를 제시하는 능력을 개발합니다.

**지속적인 개선 및 네트워킹:**

- a. 최신 OSINT 트렌드, 도구 및 기법에 대한 최신 정보를 파악합니다.
- b. 관련 온라인 커뮤니티, 포럼, 소셜 미디어 그룹에 참여합니다.
- c. OSINT 컨퍼런스, 워크샵, 웨비나에 참석합니다.

이 프레임워크를 따르면 초보자도 체계적으로 OSINT 기술을 개발하고 오픈 소스 인텔리전스 수집, 분석, 배포에 능숙해질 수 있습니다. 오픈소스 인텔리전스(OSINT)는 모의 침투 테스트 프로세스의 중요한 단계이기도 합니다. 

공개적으로 사용 가능한 정보를 철저히 조사하면 취약한 시스템을 찾거나, 비밀번호 스프레이를 통해 유효한 자격 증명을 얻거나, 소셜 엔지니어링을 통해 발판을 마련할 수 있는 기회를 높일 수 있습니다.

# 몰입형 및 게임형 학습: 트릭(a)

내성적인 분들에게 적합한 흥미로운 하위 문화로 눈을 돌리는 것도 추천할 수 있습니다! 나는 모든 사람들이 어떤 식 으로든 다양한 이상한 현상에 관심이 있다고 확신합니다. 인터넷 스토킹 환경에 빠져보세요! 

때때로 평범한 사람들은 OSINT와 GEOINT만으로 경찰이 수년 동안 해결할 수 없었던 범죄를 해결할 수있었습니다 (여기에 하위 레딧, 영화 및 뉴스 링크를 넣을 수 있지만 여러분과 저는 이제 OSINT를하고 있으므로 직접 찾아 보는 것이 좋습니다).

<details>
<summary>확장</summary>
<br />

- [넷스토킹이란?](https://graph.org/What-is-Netstalking-Netstalking-Information-Survivors-04-06)
- [geoguessr](https://somerandomstuff1.wordpress.com/2019/02/08/geoguessr-the-top-tips-tricks-and-techniques/)
- 선캘크 계산기](http://suncalc.net/)
- 마인드 해킹 - 심리 프로파일링, 그리고 OSINT 수사에서의 정신 건강](https://youtu.be/104WpJm_eGk)
- 개인화된 클라우드 기반 연습을 이용한 오픈소스 인텔리전스(OSINT) 교육 방법](https://www.researchgate.net/publication/340023320_A_Method_for_Teaching_Open_Source_Intelligence_OSINT_Using_Personalised_Cloud-based_Exercises)
- 공격 시뮬레이션 방법: 예시](https://istrosec.com/service/attack-simulations/)

</details>

**또한 확인해보세요:**

- 대체 현실 게임](http://en.wikipedia.org/wiki/Alternate_reality_game)
- [reddit.com/r/ARG](http://reddit.com/r/ARG)
- [Net.art](https://officercia.mirror.xyz/VD9IDI8b4jVBHbr5uaGcI_ev6NEKZUuuOhL9IpEfpZs)
- 응용 인류학 연구 방법](https://en.wikipedia.org/wiki/Applied_Anthropology_Research_Methods)
- 응용 인류학자가 되기 위한 성찰](https://www.jstor.org/stable/25605413)
- [응용인류학(정말, 공부해 보세요!)](https://oxfordre.com/anthropology/browse;jsessionid=469E22D5E27E148C59A31BA5715AD18D?page=3&pageSize=20&sort=titlesort&subSite=anthropology&t0=ORE_ANT%3AREFANT001)

기억해야 할 가장 중요한 것은 당신의 건강이며, 무엇보다도 당신이 보는 것에 의해 당신의 원칙이 흔들리지 않도록하는 것입니다. 당신은 관찰자입니다! 여기 [SCP 연구원](https://scp-wiki.wikidot.com/)의 심리학을 이해하는 데 도움이됩니다 (아무것도 명확하지 않지만 과학적 방법이 모든 것을 제자리에 두는 데 도움이 될 때).

<details>
<summary>확장</summary>
<br />

- [넷스토킹: 심층](https://graph.org/What-is-Netstalking-Netstalking-Information-Survivors-04-06)
- OSINT 전술을 사용하는 초기 솔라나 생태계 개발자를 찾은 방법](https://telegra.ph/How-I-found-early-Solana-ecosystem-Developers-using-OSINT-tactics-01-04)
- [온라인 익명성을 위한 히치하이커 가이드](https://web.archive.org/web/20220302223645/https://anonymousplanet.org/guide.html)
- 옵섹 연구 및 데이터 터미널 - 기여를 환영합니다.](https://github.com/OffcierCia/Crypto-OpSec-SelfGuard-RoadMap)
- [누군가보다 먼저 자신을 괴롭히세요!](https://yvesei.medium.com/dork-yourself-before-someone-does-aa49d0c1929f)

</details>

글로벌 인터넷의 이 부분(인터넷 스토킹뿐만 아니라 OSINT 전반을 의미함)에서 적극적으로 문제를 찾거나 감정을 표현해야 하는 사람들의 비율은 다른 곳과 다르지 않다는 것을 명심하세요!

- [사자처럼 행동하세요 🦁](https://twitter.com/jpurd17/status/1648669362910552067?s=20)
- [obsidian.md OSINT 템플릿](https://github.com/WebBreacher/obsidian-osint-templates)
- [OSINT 브라우저 확장](https://github.com/cqcore/OSINT-Browser-Extensions)

**과학 + OSINT:**

- [마음 들여다보기: 인공지능과 대규모 언어 모델을 통한 심리 프로파일링](https://www.linkedin.com/pulse/peering-mind-psychological-profiling-through-ai-large-smith)
- 옥캄의 면도기](https://www.britannica.com/topic/Occams-razor)
- 옥캄의 면도기 작동 방식](https://science.howstuffworks.com/innovation/scientific-experiments/occams-razor.htm)
- [과학적 원리로서의 옥캄의 면도기](https://study.com/learn/lesson/occams-razor-scientific-principle.html#:~:text=Occam's%20Razor%20is%20a%20principle%20which%20states%20that%20plurality%20should,20be%little%20more%loosely%사용되어야%한다는%원리.)
- 사례 연구: 성격 프로파일링과 OSINT의 힘](https://brightplanet.com/2016/11/09/case-study-receptiviti-power-osint/)
- OSINT 상관관계, 분석, 시각화 및 공유 기능을 개선하기 위한 강화된 위협 인텔리전스 플랫폼](https://www.sciencedirect.com/science/article/abs/pii/S2214212620308589)
- ['추론' 대 '유도' 대 '납치'](https://www.merriam-webster.com/words-at-play/deduction-vs-induction-vs-abduction)
- [연역적 추론과 귀납적 추론의 차이점](https://danielmiessler.com/p/the-difference-between-deductive-and-inductive-reasoning/)
- [귀납적 수사학](https://www.studysmarter.co.uk/explanations/english/rhetoric/induction-rhetoric/)
- [연역적 추론과 귀납적 추론: 정의, 차이점 및 예시](https://mundanopedia.com/economics/microeconomics/deductive-and-inductive-reasoning-methods/)

**연습하기:**

> 따라서, 운영원칙을 준수하고 실수를 너무 많이 하지 마세요. 별도의 격리된 기기에서 활동을 수행하세요.

- 사이버 보안을 위한 OSINT의 프라이버시 우려 및 수용 요인: 대표 설문조사](https://petsymposium.org/popets/2023/popets-2023-0028.pdf)
- [휴리스틱이란 무엇인가요?](https://www.verywellmind.com/what-is-a-heuristic-2795235)
- 콜 오브 사이옵스](https://steemit.com/news/@rusticus/call-of-psyops-video-games-psychological-war-in-the-21st-century)
- 2023년 이후의 OSINT 트렌드](https://blog.sociallinks.io/osint-trends-for-2023-and-beyond/)
- [군사 정보에서 OSINT의 광범위한 활용](https://blog.sociallinks.io/uses-of-osint-in-military-intelligence/)
- 공개적으로 이용 가능한 정보(PAI) 설명](https://www.babelstreet.com/blog/pai-explained)
- 공개적으로 이용 가능한 정보: 디지털 전장](https://censa.net/publications/publicly-available-information-the-digital-battlefield/)
- 공개 정보 더 잘 활용하기](https://www.jstor.org/stable/pdf/resrep20002.7.pdf)
- 과학의 관행: 오탐과 미탐](https://manoa.hawaii.edu/exploringourfluidearth/chemical/matter/properties-matter/practices-science-false-positives-and-false-negatives)
- [정보 보안의 오탐과 미탐](https://www.guardrails.io/blog/false-positives-and-false-negatives-in-information-security/)
- OSINT 조사에서 오탐 최소화하기](https://mediasonar.com/reports/minimize-false-positives-osint-investigations/)

**OSINT 수행 시 인지적 편향 완화 및 의사 결정]**

완벽한 실무자-분석가는 없으며, 모든 사람은 실수를 저지르고 (일생에 적어도 한 번은) 어려운 모호한 상황에 빠지며, 특히 집중적이고 만성적인 업무 과부하 조건에서 더욱 그렇습니다. 그리고 실무자 분석가는 그러한 상황을 알고 이해하는 것이 절대적으로 필요합니다. 

인지적 취약성은 (확립된 이해에서) 사고의 결함에 대한 노출 및 / 또는 경향입니다 : 심각한인지 왜곡, 잘못된 신념,인지 편향 (편견) 또는 인지 실패에 대한 개인의 성향의 기초를 만들고 [사고 과정](https://telegra.ph/Cognitive-vulnerabilities-of-the-practitioner-analyst-04-17)의 왜곡과 기능 장애로 이어지는 고정 관념화 된 사고 패턴.

- 실무자-분석가의 인지적 취약성](https://telegra.ph/Cognitive-vulnerabilities-of-the-practitioner-analyst-04-17)
- 인지 편향 완화](https://www.researchgate.net/publication/317702457_Cognitive_Bias_Mitigation)
- 인지 편향 완화 - 위키](https://en.m.wikipedia.org/wiki/Cognitive_bias_mitigation)
- [인지 편향 인식 및 완화: 객관성에 대한 위협](https://www.theiia.org/en/content/communications/press-releases/2022/may/new-recognizing-and-mitigating-cognitive-biases-a-threat-to-objectivity/)
- [인지 편향 완화: 어떻게 하면 합리적인 의사 결정을 내릴 수 있을까요?](https://ideas.repec.org/p/fau/wpaper/wp2020_01.html)
- [인지 편향이 전문가의 의사 결정에 미치는 영향: 네 가지 직업 영역에 대한 검토](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8763848/)
- [하킹: 결과가 알려진 후 가설 세우기](https://pubmed.ncbi.nlm.nih.gov/15647155/)
- [결과가 알려진 후 가설 세우기(HARKing)](https://embassy.science/wiki/Theme:Cc742a7b-826d-4201-b33e-457f2ef79fb9) & [논문](https://www2.psych.ubc.ca/~schaller/528Readings/Kerr1998.pdf)
- 인지 취약성](https://en.m.wikipedia.org/wiki/Cognitive_vulnerability)
- 대안 중에서 선택할 때 왜 한 가지 특성에 집중하여 비교하는가](https://thedecisionlab.com/biases/take-the-best-heuristic) & [더 보기](https://fourweekmba.com/take-the-best-heuristic/)
- 해커의 두뇌를 해킹하려는 IARPA의 계획](https://fcw.com/security/2023/04/iarpas-plan-hack-brains-hackers/385123/)
- [사이버 공격자의 사고는 빠르고 느릴까?](https://journals.sagepub.com/doi/pdf/10.1177/1071181319631096)
- [DMBOK2](https://www.dama.org/cpages/body-of-knowledge)
- [미국 위원회 보고서 - 2005](https://govinfo.library.unt.edu/wmd/about.html)
- [5가지 인지 편향이 OSINT 조사에 영향을 미칠 수 있다](https://www.linkedin.com/pulse/5-cognitive-biases-could-affect-your-osint-investigations-?utm_source=share&utm_medium=guest_mobile_web&utm_campaign=copy)

우리 대부분은 집을 구할 때 새로운 매물에 즉각적으로 호감을 느끼거나 싫어하는 등 설명할 수 없는 '직감'을 경험하거나 새로운 사람을 만나면 순식간에 판단을 내리는 경우가 많습니다. 이제 연구자들은 이러한 감정(또는 직관)이 실제 존재하며 직감을 진지하게 받아들여야 한다고 말합니다. 

한 가지 접근 방식에만 국한하지 말고 실험을 시도하는 것을 두려워하지 마시고, 그러한 접근 방식의 결과는 항상 **두 번 확인**해야 한다는 점을 명심하세요. 이러한 정보는 조사자에게 실제적인 조언이라기보다는 학습 도구의 역할을 합니다. 다음 웹사이트를 방문하세요:

- [직관은 단순한 직감 그 이상, 새로운 연구에 따르면](https://www.sciencedaily.com/releases/2008/03/080305144210.htm)
- [출현으로서의 직관: 심리학, 철학, 조직 과학의 연결](https://www.frontiersin.org/articles/10.3389/fpsyg.2021.787428/full)
- [지능 분석: 구조화된 방법인가, 직관인가?](https://www.academia.edu/4259879/Intelligence_Analysis_Structured_Methods_or_Intuition)
- 지능과 직관 통합의 잠재력](https://www.thecipherbrief.com/the-potential-of-integrating-intelligence-and-intuition)
- [사회 공학과 고가치 표적 보호](https://www.hensoldt-analytics.com/2023/01/23/social-engineering-osint/)
- [내 그림자 추적 게임](https://myshadow.org/trace-my-shadow)
- [OSINT에 대해 이야기할 때 이야기하는 것](https://www.authentic8.com/blog/definition-of-osint)
- 공개 정보: 미분류 데이터의 비밀, 1부](https://overthehorizonmdos.wpcomstaging.com/2019/04/08/publicly-available-information-the-secret-to-unclassified-data-part-i/) 및 [복사](https://web.archive.org/web/20191117062938/https://othjournal.com/2019/04/08/publicly-available-information-the-secret-to-unclassified-data-part-i/)

**또한:**

**원더스미스래](https://wondersmithrae.medium.com/training-yourself-to-be-an-analytical-thinker-476bdb7e7c99)**에 따르면: 고전 수사학에서 아리스토텔레스가 만든 "상황의 요소"는 오랫동안 수사학적 질문을 분석하는 데 사용되어 왔습니다. 이러한 요소는 현대의 분석에도 적용되며 조사를 위한 기초로 사용될 수 있습니다. **(누가, 무엇을, 언제, 어디서, 왜, 어떤 방식으로, 어떤 수단으로)**

이 요소들을 압축하면서도 똑같이 가치 있는 버전은 "5W와 H" 또는 누가, 무엇을, 언제, 어디서, 왜, 어떻게라고 부릅니다. 이러한 질문은 고대 그리스부터 수사학, 종교 연구, 경찰 수사, 저널리즘, 변호사들이 사용해 왔습니다. 모든 W와 H에 답할 수 있을 때까지 조사는 진정으로 완료될 수 없다고 합니다. 

OSINT 조사에도 동일한 요소를 적용하면 비슷한 질문을 하고 답할 수 있습니다. 5W에 답하면 수집한 데이터에서 내러티브가 드러나기 시작합니다. 이제 이 점들을 간결하게 연결하는 것은 분석가인 우리의 몫입니다. 문제는 조사를 해본 사람이라면 누구나 정보가 밝혀지기 시작하면 토끼굴에 갇히기 쉽다는 것을 알고 있다는 것입니다. 

- [감각을 차단하는 힘: 창의력을 높이고 맑은 정신을 갖는 방법](https://buffer.com/resources/the-power-of-shutting-down-your-senses-how-to-boost-your-creativity-and-have-a-clear-mind/amp/)
- [분석적 사고자가 되기 위한 훈련](https://wondersmithrae.medium.com/training-yourself-to-be-an-analytical-thinker-476bdb7e7c99)
- 더 나은 온라인 조사를 위한 OSINT 마인드 스테이트 활용](https://www.sans.org/webcasts/atmic-talk-osint-mind-state-online-investigations-114115/)
- SOCMINT, OSINT 및 사이버 심리학의 최신 동향](https://www.toddington.com/wp-content/uploads/1Day_OSINT_Masterclass-1-1.pdf)
- [OSINT 수사에 영향을 미칠 수 있는 5가지 인지 편향](https://www.liferaftinc.com/blog/5-cognitive-biases-that-could-affect-your-osint-investigations)
- 시민 OSINT 분석가: 오픈소스 인텔리전스 자원 봉사자들의 동기](https://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1670900&dswid=-6049)
- 오픈소스 수사에서 가해자 조사 및 매핑에 관한 새로운 가이드](https://piac.asn.au/2023/03/29/new-guide-on-investigating-and-mapping-perpetrators-in-open-source-investigations/)
- [해외 사업가가 사망하고 460만 달러를 남겼기 때문에, 사기꾼에게 사기 치기 위해 OSINT와 소셜 엔지니어링을 사용했습니다](https://hatless1der.com/an-overseas-businessman-died-and-left-me-4-6m-so-i-used-osint-social-engineering-to-scam-a-scammer/)
- [Cchatgpt-언락-지리적 위치 데이터](https://www.digitaldigging.org/p/4-chatgpt-unlock-geolocation-data)
- [텔레그램-osint-vm-part-2](https://www.cqcore.uk/telegram-osint-vm-part-2/)
- [지능 연구](https://t.me/devil_may_spy/160)
- [OSINT 보호: 허위 정보 조작으로부터 보호](https://osintteam.blog/safeguarding-osinters-shielding-against-disinformation-manipulation-dfbbfbf1db08)
- [디지털 탐정 공개: 수사관을 위한 필수 OSINT 도구 및 기법](https://osintteam.blog/unveiling-the-digital-detective-essential-osint-tools-and-techniques-for-investigators-adf486ad2ccd)

정보를 구별하고 분류할 수 있게 되면 다음으로 할 수 있는 일은 연습을 시작하는 것입니다. 아시다시피, **좋은 연습에는 좋은 동기가 필요합니다**! 한 가지 알아야 할 것은 사람들은 지능이 고정되어 있다고 생각하지만 그렇지 않다는 것입니다. 두뇌는 근육과 같아서 더 많이 사용할수록 더 많이 성장합니다. 교육은 더 이상 일회성 이벤트가 아니라 평생의 경험입니다.

<details>
<summary>확장</summary>
<br />

- 초보자 현장 가이드: OSINT를 배울 수 있는 곳과 방법](https://medium.com/the-sleuth-sheet/beginners-field-guide-where-how-to-learn-osint-bd2e11469f31)
- 사이버 탐정이 사용하는 트랩...](https://medium.com/@ibederov_en/traps-used-by-cyber-detectives-c778b4853f1a)
- [MAC 주소 조사](https://t.me/ibederov_en/18)
- 인텔리전스 보고서 작성을 위한 궁극의 가이드](https://www.intelligence101.com/the-ultimate-guide-to-writing-intelligence-reports-complete-with-templates-examples/)
- 비즈니스 복원력 리소스](https://start.me/p/wMgzM5/business-resilience)
- 개인 정보 보호 관점에서 본 개인 OSINT 조사 워크플로](https://www.osintme.com/index.php/2022/08/31/person-osint-investigation-workflow-from-a-privacy-perspective/)
- [도덕적 나침반 설정하기: OSINT에 적용된 윤리를 위한 통합 문서](https://ethicaljournalismnetwork.org/setting-your-moral-compass-a-workbook-for-applied-ethics-in-osint)
- 레딧 수사국](https://www.reddit.com/r/RBI/)
- OSINT의 암흑 예술](https://av.tib.eu/en/media/38959)
- [OSINT 위키](https://www.reddit.com/r/OSINT/wiki/index/)
- OSINT 지도](https://cipher387.github.io/osintmap)

</details>

**또한 확인해보세요:**

> 최근 설문조사](https://4discovery.com/2019/09/10/litigating-in-an-e-world-e-discovery-forensics-and-open-source-intelligence-in-legal-research/)에 따르면 97% 이상의 기업이 클라우드에 데이터를 저장하고 있습니다. 클라우드 데이터의 잠재적 출처를 식별하고, 증거개시 요청을 발행하고, 소송 보류를 구현하는 방법과 클라우드 데이터를 보존, 수집, 필터링, 검토 및 생성하는 방법에 대해 알아보세요.

> 소송과 관련된 정보](https://4discovery.com/2019/09/10/litigating-in-an-e-world-e-discovery-forensics-and-open-source-intelligence-in-legal-research/)는 일반적으로 인터넷에 잘 보이지 않는 곳에 숨어 있습니다. 비즈니스 기록, 도메인 이름 등록, 웹사이트, 온라인 사용자 ID, 소셜 미디어 게시물, 사진, 동영상은 검색 쿼리만 하면 쉽게 찾을 수 있습니다. 어떻게 찾을 수 있는지 알고 계신가요? 오픈 소스 정보가 광범위한 문제에 어떤 영향을 미칠 수 있는지, 정보의 출처를 효과적으로 식별하고 오픈 소스 데이터를 검색하는 방법을 알아보세요.

- 심리언어학 관점에서 본 범죄자의 언어](https://www.paperdue.com/essay/criminals-language-from-a-psycholinguistics-1851)
- [범죄자 식별 및 평가를 위한 언어 분석 활용](https://www.researchgate.net/publication/340985509_FORENSIC_PSYCHOLINGUISTICS_USING_LANGUAGE_ANALYSIS_FOR_IDENTIFYING_AND_ASSESSING_OFFENDERS)
- [식별 및 평가를 위해 언어 분석을 사용하는 법의학 심리언어학](https://criminalprofiling.com/forensic-psycholinguistics-using-language-analysis-for-identifying-and-assessing/)
- 인간 지능(HUMINT)에 대한 궁극적인 가이드](https://www.intelligence101.com/the-ultimate-guide-to-human-intelligence-humint/)
- 오픈 소스 정보 수집을 이용한 사회 공학 약화](https://www.researchgate.net/publication/283250856_Undermining_social_engineering_using_open_source_intelligence_gathering)
- [시그널 OSINT - SIGINT](https://worldwidescience.org/topicpages/o/osint+signals+intelligence.html)
- [법률 연구에서의 전자증거개시, 포렌식, 오픈소스 인텔리전스](https://4discovery.com/2019/09/10/litigating-in-an-e-world-e-discovery-forensics-and-open-source-intelligence-in-legal-research/)
- [반대에서 OSINT로? 역할, 평판 및 수익에 대한 이해, 영향력, 보호](https://complexdiscovery.com/from-dissent-to-osint-understanding-influencing-and-protecting-roles-reputation-and-revenue/)
- [기본 사항: 전자증거개시란 무엇인가요?](https://cdslegal.com/knowledge/the-basics-what-is-e-discovery/)
- 오픈 소스 인텔리전스를 정리, 수집 및 제시하는 시스템](https://link.springer.com/article/10.1007/s42488-022-00068-4)

# 교육 및 실습

**좋은 교육 자료:**

- [OSINT를 위한 파이썬 21일](https://github.com/cipher387/python-for-OSINT-21-days)
- [구글도킹](https://tryhackme.com/room/googledorking) + [도크서치닷컴](https://dorksearch.com/)
- [서치라이트토신트](https://tryhackme.com/room/searchlightosint)
- [쇼단](https://tryhackme.com/room/shodan)
- [지오로케이팅이미지](https://tryhackme.com/room/geolocatingimages)
- 인스트루먼트 온 더 라디오 웨이브](https://telegra.ph/Instruments-on-the-radio-waves-02-01) + [websdr.org](https://websdr.org) + [시도 😅](http://websdr.ewi.utwente.nl:8901/?tune=4625)
- [Somesint](https://tryhackme.com/room/somesint)
- [osintframework.com](https://osintframework.com)
- [OSINT 앳홈 유튜브 재생 목록](https://www.youtube.com/playlist?list=PLrFPX1Vfqk3ehZKSFeb9pVIHqxqrNW8Sy)
- [myosint.training](https://www.myosint.training/)
- [멋진 사이버 기술](https://github.com/joe-shenouda/awesome-cyber-skills)
- [멋진지도](https://github.com/simsieg/awesome-maps)

다음은 [OSINT](https://twitter.com/hashtag/OSINT?src=hashtag_click)에서 누구에게나 매우 중요한 기술인 연상적 사고를 훈련하는 데 도움이되는 아주 좋은 두뇌 스트레칭 게임입니다:

- [위키백과:위키 게임](https://en.wikipedia.org/wiki/Wikipedia:Wiki_Game)

어렸을 때 우리는 "라그나로크까지 5 단계"를했습니다. 목표는 임의의 Wikipedia 페이지에서이 신화에 대한 페이지를 5 단계 (5 번 클릭)로 찾는 것이 었습니다! 🙂.

**최고의 OSINT 전문가 팔로우하기 :**

- [twitter.com/UKOSINT](https://twitter.com/UKOSINT) - 뉴스, 도구, 농담
- [twitter.com/dutch_osintguy](https://twitter.com/dutch_osintguy) - 유명한 전문가, 연사
- twitter.com/jakecreps](https://twitter.com/jakecreps) - 매주 목요일 멋진 도구 게시
- twitter.com/OSINTtechniques](https://twitter.com/OSINTtechniques) - 디지털 브레드크럼을 팔로우하세요.
- [슬루스 시트](https://medium.com/the-sleuth-sheet)
- [OSINT 에센셜](https://osintessentials.medium.com/)
- [Sector035](https://medium.com/@sector035) - 주간 OSINT
- 이고르 베데로프](https://medium.com/@ibederov_en) - 디지털 시대의 셜록 홈즈 ...
- 트위터](https://twitter.com/OSINTHK) - OSINT를 사용하는 자원 봉사자
- 글로벌 OSINT 커뮤니티](https://osintfr.com/en/home/) - 프랑스의 OSINT 커뮤니티
- [twitter.com/OSINT_Research](https://twitter.com/OSINT_Research) - 도구 및 멋진 데이터
- [twitter.com/OSINTtechniques](https://twitter.com/OSINTtechniques) - 도구와 멋진 데이터
- [twitter.com/OsintJobs](https://twitter.com/OsintJobs) - OSINT의 채용 정보
- [www.reddit.com/r/OSINT](https://www.reddit.com/r/OSINT) - 가장 큰 주제별 서브 레딧
- OSINT, 해킹, 보안 등에 관한 채널](https://telegra.ph/Channels-about-OSINT-Hacking-Security-and-so-on-04-19)

**추가 리소스:**

> [잘못된 결정을 덜 내리게 하는 전통적인 기능 외에도](https://www.researchgate.net/publication/331073990_Digital_Open_Source_Intelligence_and_International_Security_A_Primer) 현대 인텔리전스의 대상은 국가나 기업 경영진을 넘어 일반 대중으로 확대되고 있습니다. 더 이상 단순한 경고 메커니즘이 아니라 예기치 않은 위기 상황에서 문제를 해결하기 위한 노하우 저장소이자 즉흥적인 풀입니다.
 
- [어썸 OSINT + 크립토](https://github.com/aaarghhh/awesome_osint_criypto_web3_stuff)
- [구글 해킹](https://seckrd.com/google-hacking)
- [GOSI: GIAC 오픈소스 인텔리전스](https://www.giac.org/certification/open-source-intelligence-gosi)
- [SEC487: 오픈소스 인텔리전스(OSINT) 수집 및 분석](https://www.sans.org/cyber-security-courses/open-source-intelligence-gathering/)
- 인텔테크놀로지스넷](https://www.inteltechniques.net/)
- IT 보안 강연](https://github.com/bkimminich/it-security-lecture/)
- [r4ven 도구](https://github.com/spyboy-productions/r4ven)
- [언레드캐터](https://github.com/BishopFox/unredacter)
- 포렌식닷](https://www.forensicdots.de/)
- 메타시크릿 앱](https://github.com/meta-secret)
- [이미지 리서치 OSINT](https://github.com/cqcore/Image-Research-OSINT)
- 보안 분석가로서 알아야 할 15가지 도구](https://osintteam.blog/15-tools-you-should-know-as-a-security-analyst-f95007e94d99)
- 휴대용 시크릿 앱](https://mprimi.github.io/portable-secret/)
- 오픈 소스 인텔리전스 기법](https://inteltechniques.com/book1.html)
- 인터넷 인텔리전스 및 조사 핸드북](https://www.amazon.com/Internet-Intelligence-Investigation-Handbook-practical/dp/B096TJMV7J)
- NATO OSINT 핸드북](https://github.com/lawsecnet/OPSEC/blob/master/NATO%20OSINT%20Handbook%20v1.2%20-%20Jan%202002.pdf)
- [osintnewsletter.com](https://osintnewsletter.com/)
- [지리적 위치 OSINT](https://github.com/cqcore/Geolocation-OSINT)
- 지오디텍티브](https://geodetective.io/)
- [또 다른 멋진 OSINT 책](https://t.me/osintkanal/2049)
- [소셜 미디어 OSINT](https://github.com/cqcore/Social-Media-OSINT)
- [얼굴을 검색하는 매혹적인 검색 엔진](https://www.makeuseof.com/tag/3-fascinating-search-engines-search-faces/)
- [OSINT 도구 메가리스트](https://pastebin.com/z0FUgiGb)
- [OSINT의 미래: ChatGPT로 검색하는 사람들](https://dorksearch.com/blog/future-of-osint-people-searching/)
- 지오로케이션: 리테일 파크에서](https://nixintel.info/osint/geolocation-at-the-retail-park/)

**도구(AI, ChatGPT, ML, 기타):**

> [최근 몇 년 사이 오픈소스 인텔리전스 수집 및 분석](https://www.sans.org/webcasts/atmic-talk-osint-mind-state-online-investigations-114115/)에 대한 대중의 관심이 기하급수적으로 증가하고 있습니다. 이러한 관심이 높아지면서 분석 프로세스를 뒤로한 채 도구와 자동화에 의존하는 OSINT 조사가 점점 더 많아지고 있습니다. OSINT를 사고 과정으로 간주해야 합니다. 조사 단계를 추적하고, 올바른 도구와 소스를 선택하고, 데이터를 분석하고, 실행 가능한 인텔리전스를 생성하기 위해 보고하는 데 있어 "OSINT 상태"가 핵심입니다!

- OSINT 도구 맵](https://metaosint.github.io/chart)
- [셜록](https://github.com/sherlock-project/sherlock)
- [gpt.censys.io](https://gpt.censys.io/)
- ChatGeoPT](https://github.com/earth-genome/ChatGeoPT)
- OSINT용 ChatGPT: 예제](https://t.me/osintkanal/2009) | 팁: deepl.com](https://www.deepl.com/translator) 사용
- 이모티콘 OSINT](https://www.dutchosintguy.com/post/cryptography-osint-can-you-read-emoji)
- [Advangle](http://advangle.com/)
- searchcode.com](https://searchcode.com/)
- [dorkgpt.com](https://www.dorkgpt.com/)
- [OSINT & ChatGPT: 103 아이디어](https://t.me/irozysk/9377)
- [OSINT + AI](https://github.com/jiep/offensive-ai-compilation)
- [OSINT-SAN](https://github.com/Bafomet666/OSINT-SAN)
- [OSINT 버디](https://github.com/jerlendds/osintbuddy)
- [ChatGPT: OSINT를 위한 AI 기반 비밀 무기](https://blog.gopenai.com/chatgpt-the-ai-powered-secret-weapon-for-osint-133a68d8302e)
- [도구를 모든 작업에 대해 실버 불러처럼 취급하지 마십시오!](https://osintessentials.medium.com/the-one-osint-tool-you-must-have-to-supercharge-your-investigations-94f5015b6318)
- [새로운 OSINT 치트 코드: ChatGPT](https://medium.com/the-sleuth-sheet/the-new-osint-cheat-code-chatgpt-cd54c190fa11)
- [OSINT를 위한 ChatGPT의 힘 활용하기: 인공지능 OSINT 어시스턴트를 위한 실용적인 가이드](https://hackernoon.com/harnessing-the-power-of-chatgpt-for-osint-a-practical-guide-to-your-ai-osint-assistant)
- [멋진 무료 ChatGPT](https://github.com/LiLittleCat/awesome-free-chatgpt)
- [공격적 AI](https://github.com/jiep/offensive-ai-compilation)
- 비트코인 조사 매뉴얼 AML](https://www.amazon.com/Bitcoin-Investigation-Manual-AML-Money-Laundering/dp/1077484070)

# 따라갈 경로 선택하기...

[이 주제가 마음에 들면 내 채널 읽기](https://t.me/officer_cia)... 또는 누군가가 지금 날마다 성장하고있는 [AD-INT](https://medium.com/@ibederov_en/mac-address-osint-e539504ae925)에 들어갈 수도 있습니다. GEOINT 기술 교육을 받으려면 [geoguessr.com](https://geoguessr.com/) 및 [whereami.io](https://whereami.io/)를 확인하는 것이 좋습니다.

**이 멋진 마인드맵을 한번 보세요.

- 나를 클릭하세요!](http://files.mtg-bi.com/MindMap.jpg)

**데이터 터미널 살펴보기:**

- 오픈 소스 인텔리전스(OSINT) 정찰](https://z3r0trust.medium.com/open-source-intelligence-osint-reconnaissance-9f0bafd672b2)
- OSINT를 위한 수백 가지 온라인 도구 모음](https://github.com/cipher387/osint_stuff_tool_collection)
- 오픈 소스 조사를 좋아하는 모든 사람을 위한 페이지](https://start.me/p/DPYPMz/the-ultimate-osint-collection)
- [Start.me + OSINT](https://start.me/p/Pwy0X4/osint-inception)
- [5시간 만에 배우는 오픈소스 인텔리전스(OSINT) - 전체 과정 - OSINT 배우기!](https://youtu.be/qwA6MmbeGNo)
- [팔로우!](https://twitter.com/Sector035)
- [myosint.training/courses/](https://myosint.training/courses/)
- DNSTwist, DNSRazzle과 같은 OSINT 타이포스쿼팅 도구와 볼스터의 타이포스쿼팅 모니터링 비교](https://securityboulevard.com/2022/02/comparing-osint-typosquatting-tools-like-dnstwist-dnsrazzle-against-bolsters-typosquatting-monitoring/)
- [* 저 글꼴은 뭐죠?](https://osintessentials.medium.com/wtf-be0de2230ed2)
- OSINT 치트시트](https://thekaiz3n.com/cheatsheet/2022/01/12/osint.html)
- 이론 중심 사회학 연구의 설계 및 분석을 위한 납치 및 회귀 추론의 적용](https://journals.sagepub.com/doi/10.5153/sro.2819)
- [회귀의 한 측면으로서의 납치](http://www.commens.org/encyclopedia/article/chiasson-phyllis-abduction-aspect-retroduction)
- [귀납의 한 측면으로서의 귀납 - 2](https://www.degruyter.com/document/doi/10.1515/semi.2005.2005.153-1-4.223/html?lang=en)
- 납치 추론](https://en.wikipedia.org/wiki/Abductive_reasoning)

텔레그램 사용자의 익명화를 해제하거나 ([이 채널 읽기](https://t.me/ibederov_en)) 반대로 [counter-OSINT](https://github.com/soxoj/counter-osint-guide-en) 형제에 가입할 수도 있습니다. 그러나 그렇게 할 때 정보 검색, 정보 분석 및 정보 응용의 핵심 기술을 잊지 말 것을 촉구합니다 ...

<details>
<summary>확장</summary>
<br />

- 카운터 OSINT 가이드](https://github.com/soxoj/counter-osint-guide-en)
- 휴민트 VS 사회공학 리소스](https://telegra.ph/HUMINT-VS-Social-Engineering-Resources-03-24)
- [망각에서 조명으로. 1부 | 창의성과 방어의 경계에서](https://mirror.xyz/0xc34B1730BA53abD717a1E57A358F39C046053581/Ra_UVvUwOrO5W56k2QpP4jKhYAGMhsNnfvwrdKWQ1EI)
- [무엇이든 배우는 방법](https://twitter.com/sahilbloom/status/1662453471608446976)

</details>

저는 몇 가지 기본적인 조언을 강조하겠습니다. 다양한 기준에 따라 정보를 평가하고, 항상 "기본 설정"을 알고 있으면 정신 건강에 좋으며, 찾은 것들이 기초를 망쳐서는 안됩니다! 그것을 연습하고, 일상 생활에서 그것을하고, 아래에 언급 된 것처럼 분명하지 않은 것처럼 보이는 곳에 OSINT를 적용하십시오:

- [OSINT가 커리어에 도움이 되는 5가지 방법! - 노매드 OSINT](https://knowmad-osint.com/5-ways-osint-can-help-your-career/)
- [공격의 기술](https://books.google.nl/books? id=j583EAAAQBAJ&pg=PT10&lpg=PT10&dq=how+to+think+like+an+osint+mindset&source=bl&ots=JeHrgDkP0q&sig=ACfU3U0UC_u94QQs3wdSXmIt2VsZcJNcyw&hl=en&sa=X&ved=2ahUKEwjIvNrwlcj3AhXD0qQKHZfUA50Q6AF6BAgiEAM#v=onepage&q=how%20to%20think%20like%20an%20osint%20mindset&f=false)
- 오픈 소스 인텔리전스를 위한 온톨로지 모집단](https://ceur-ws.org/Vol-2161/paper27.pdf)
- [암호화 및 OSINT - 기초](https://www.dutchosintguy.com/post/cryptography-osint-the-fundamentals)
- [제로 너비 문자를 사용하여 텍스트에서 비밀 메시지 숨기기 (및 누출 공개)](https://null-byte.wonderhowto.com/how-to/use-zero-width-characters-hide-secret-messages-text-even-reveal-leaks-0198692/)
- OSINT: 사용자 이름 검색 도구](https://www.secjuice.com/osint-username-search-tool/)
- 지리적 위치 챌린지 글](https://osintteam.blog/geolocation-challenge-writeup-1cd5d5aa299f)
- 웹 정찰 및 OSINT에 관한 모든 것](https://github.com/pr0xh4ck/web-recon)
- [고통없는 엿보기 도구 - GEOINT](https://github.com/adacable/painlessPeek)
- ChatGPT-osint 도구](https://github.com/gigz/gpt-osint)
- 쿼리 툴](https://github.com/oryon-osint/querytool)

# 몰입형 & 게임형 학습: 게임 (b)

물론 커뮤니티에 가입하고 채팅, 채팅! 아래에서는 영어권 커뮤니티만 언급했지만 현지 커뮤니티도 있으니 직접 조사해 보세요. 저는 여러분을 100% 확신합니다! 당신은 성공할 것입니다! 친구들과 어울리는 것을 좋아하시나요? 그렇다면 도저나 인카운터(또는 암호 해독, 위치 추적, 탈출, 자물쇠 따기 등을 기반으로 한 나이트 게임)를 함께 플레이해 보세요! 

- 도조르 팀 야간 게임](https://en.wikipedia.org/wiki/Dozor)
- [코드브레이킹](https://en.m.wikipedia.org/wiki/Codebreaking)
- 지오캐싱](https://en.m.wikipedia.org/wiki/Geocaching)
- 탈출학](https://en.wikipedia.org/wiki/Escapology)
- [자물쇠 따기](https://www.art-of-lockpicking.com/how-to-pick-a-lock-guide/)

**체크 아웃:**

- [인그레스](https://www.ingress.com/)
- [지오캐싱](https://education.nationalgeographic.org/resource/geocaching/)
- [탈출학](https://www.escapology.com/en)
- 정보 수집을위한 최고의 도구 🔎](https://github.com/Moham3dRiahi/Th3inspector)
- 굉장한 지능](https://github.com/ARPSyndicate/awesome-intelligence)

**OSINT-Games:**

- [케이세나리오스닷컴](https://kasescenarios.com/)
- [소싱 게임](https://sourcing.games/)
- [OSINT 연습 #018](https://gralhix.com/list-of-osint-exercises/osint-exercise-018/)
- [osint.games](https://www.osint.games/)
- [스파이 챌린지](http://spyingchallenge.com/)
- [10가지 초급 OSINT CTF 솔루션](https://geckosint.medium.com/10-beginner-osint-ctf-solutions-ae89e557a4b)
- [더 많은 OSINT CTF](https://warnerchad.medium.com/osint-ctfs-9993129c10c7)
- [OSINT 챌린지 목록 - 레딧](https://www.reddit.com/r/OSINT/comments/vu9i43/looking_for_osint_challenges_ctfs/)
- [2가지 훌륭한 OSINT 교육 도구](https://nixintel.info/osint/two-great-osint-training-tools/)
- [OSINT 관련 게임 - 레딧](https://www.reddit.com/r/OSINT/comments/i62fhp/osint_related_games/)
- [최고의 위치 기반 게임 10선](https://www.digitaltrends.com/gaming/best-location-based-gps-games/)
- [야외 탐험을 위한 7가지 위치 기반 게임](https://www.samsung.com/uk/explore/entertainment/7-geolocation-games-to-get-you-exploring-the-outdoors/)
- [위치 기반 게임](https://en.wikipedia.org/wiki/Location-based_game)
- [햄 라디오에서 여우 사냥이란?](https://hamradioplanet.com/what-is-a-fox-hunt-in-ham-radio/)
- 함께할 수 없을 때 즐길 수 있는 9가지 가상 게임](https://www.realsimple.com/work-life/entertainment/virtual-games)

이러한 리소스를주의 깊게 연구하고 말벌의 세계를 여행 할 때 다시 돌아와서 뿌리를 잊지 마세요. 이 기사는 질문에 대한 답을 제시하는 것이 아니라, 여러분이 무언가에 대해 생각하도록 유도하기 위해 몇 가지 수사학적 질문을 제기합니다!

<details>
<summary>확장</summary>
<br />

- 종합 카운터 OSINT](https://github.com/soxoj/counter-osint-guide-en)
- 카운터 OSINT](https://github.com/CScorza/OSINTAnonymous)
- 오픈 소스 인텔리전스 조사: 전략에서 실행까지](https://www.researchgate.net/publication/321531302_Open_Source_Intelligence_Investigation_From_Strategy_to_Implementation)
- [인터넷 시대의 인텔리전스: 오픈 소스 인텔리전스(OSINT)의 출현과 진화](https://www.sciencedirect.com/science/article/abs/pii/S0747563211002585)
- 오픈소스 인텔리전스(OSINT) 가이드](https://greydynamics.com/a-guide-to-open-source-intelligence-osint/)
- [지능형 증거: 형사 절차에서 오픈 소스 인텔리전스(OSINT) 활용하기](https://www.researchgate.net/publication/309015913_Intelligent_evidence_Using_open_source_intelligence_OSINT_in_criminal_proceedings)
- [인텔리전스 주기: OSINF에서 OSINT 생성](https://www.skopenow.com/news/the-intelligence-cycle-creating-osint-from-osinf)

</details>

이 가이드는 비정형적인 가이드이므로 어떤 식으로든 OSINT와 관련이 있다고 생각되는 TV 프로그램과 영화 목록을 제공하는 것이 가치가 있다고 생각합니다:

- OSINT 영화 목록](https://www.aware-online.com/en/osint-films/)
- 검색](https://youtu.be/3Ro9ebQxEOY)
- 인터넷에서 가장 미움받는 남자](https://youtu.be/ySFpxEdKxMw)
- [왜 날 죽였어?](https://youtu.be/QEXV8Rif8Vc)
- [웹 오브 메이크 빌리브: 죽음, 거짓말 그리고 인터넷](https://youtu.be/Z_l702HNPAA)
- [고양이와 장난치지 마세요: 인터넷 살인범 사냥](https://youtu.be/x41SMm-9-i4)
- [레딧이 그들의 삶을 망쳤다: 인터넷 정의의 무고한 희생자들](https://youtu.be/hi14dP5Rdm0)
- [사이버 지옥: 인터넷 공포의 실체](https://youtu.be/hpceNxQASKw)
- [나는 누구인가 - 안전한 시스템은 없다](https://www.imdb.com/title/tt3042408/)
- [아날로그 호러의 역사](https://youtu.be/-I_4ph-L19U)
- 다크 웹: 시카다 3301](https://www.imdb.com/title/tt8110246/)
- 영화 43 (LOL)](https://youtu.be/A9fBCkwDW8c)
- 미스터 로봇](https://www.imdb.com/title/tt4158110/)
- 오픈 윈도우](https://m.imdb.com/title/tt2409818/)
- [맨 썸 하타르 크비너](https://m.imdb.com/title/tt1132620/)

**참고자료:**

> [오픈 소스 인텔리전스, 일반적으로 OSINT라고도 함](https://www.skopenow.com/news/osintforgood-the-philanthropic-application-of-osint)는 공개적으로 이용 가능한 정보를 수집, 대조 및 분석하는 것입니다. OSINT는 국가 안보 분야에서 개발된 기법으로, 현재는 법 집행, 저널리즘, 기업 보안, 학술 연구, 법률 분야 등 다양한 분야로 확대되었습니다. OSINT는 자선 단체를 지원하는 데에도 사용할 수 있습니다!

- OSINT와 관련된 멋진 영화가 있나요?](https://www.reddit.com/r/OSINT/comments/owxp7r/any_cool_movies_related_to_osint/)
- OSINT 영화 목록](https://twitter.com/AllForOsint/status/1581244439271350272)
- 휴일을 위한 OSINT 영화 시간](https://medium.com/@sector035/osint-movie-time-for-the-holidays-7a5f74f18f44)
- OSINT에 관한 최고의 영화](https://medium.com/@ibederov_en/the-best-films-about-osint-5c3ab580f56)
- 스파이, 스파이, 정보 및 간첩에 관한 정보 텔레비전 및 영화](https://www.intelligence101.com/my-favourite-intelligence-television-and-movies-about-spies-spying-intelligence-and-espionage/)
- [국방부 영화 목록 - 스프레드시트 버전](https://www.spyculture.com/dod-film-list-spreadsheet-version/)
- [OSINT 2020-12 주간](https://sector035.nl/articles/2020-12)
- [ARG 서브 레딧](https://www.reddit.com/r/ARG/)
- [OSINT 서브 레딧](https://www.reddit.com/r/OSINT/)
- [블록체인 OSINT](https://www.forensicxs.com/blockchain-osint-decentraland/)
- [존 도 스트라이크 어게인](https://hamzaharooon.medium.com/john-doe-strikes-again-n00bzctf-osint-d2122d54c508)
- [측정 및 서명 인텔리전스 (MASINT)](https://irp.fas.org/program/masint.htm)
- [하나의 검색으로 모든 것을 지배하라 - 이미지에 대한 부울 검색](https://nixintel.info/osint/one-search-to-rule-them-all-boolean-searches-for-images/)
- SOC 퍼펫 제작 가이드](https://medium.com/the-sleuth-sheet/soc-puppet-creation-guide-888768dce96e)
- [위협 인텔리전스를 위한 세 가지 유형의 인텔리전스: 종합 가이드](https://medium.com/the-sleuth-sheet/the-three-types-of-intelligence-for-threat-intelligence-a-comprehensive-guide-e8bbf1f26164)
- OSINT 마스킹 풀기: 데이터 집계 여정](https://medium.com/@VEEXH/unmasking-osint-a-data-aggregation-journey-14bea88eb045)

**OSINT 책장:**

- 내가 최근에 읽은 OSINT 및 보안 서적 - 추천](https://www.osintme.com/index.php/2021/04/30/my-recently-read-osint-security-books-recommendations/)
- [지오데텍티브.io 교육](https://geodetective.io/)
- 오픈 소스 인텔리전스 분석 책장](https://medium.com/the-sleuth-sheet/the-open-source-intelligence-analysis-bookshelf-942dc05a16bd)
- [모든 분석가가 읽어야 할 7가지 OSINT 책](https://www.liferaftinc.com/blog/7-osint-books-every-analyst-should-read?hs_amp=true)
- 마이클 바젤의 책](https://inteltechniques.com/book1.html)
- 정보 및 스파이 활동을 이해하기 위해 읽어야 할 책](https://www.wgu.edu/career-guide/information-technology/osint-career.html#openSubscriberModal)
- [공식 CIA 속임수와 기만 매뉴얼 - H. 키스 멜튼, 로버트 월리스 (2009)](https://www.bokus.com/bok/9780061943331/official-cia-manual-of-trickery-and-deception/) & [링크](https://www.google.se/books/edition/The_Official_CIA_Manual_of_Trickery_and/LbrzMtkyCGUC?hl=ru&gbpv=1&dq=inauthor:%22H.+Keith+Melton%22&printsec=frontcover) & [링크2](https://www.bokus.com/bok/9780061943331/official-cia-manual-of-trickery-and-deception/)
- 공격적인 OSINT 도구](https://github.com/wddadk/Offensive-OSINT-Tools)
- 스파이크래프트](https://books.google.se/books/about/Spycraft.html?id=eJg0WV6sGlEC&redir_esc=y) & [링크](https://www.google.se/books/edition/Spycraft/RHWH7gVIO9cC?hl=ru&gbpv=1&dq=inauthor:%22H.+Keith+Melton%22&printsec=frontcover)
- 궁극의 스파이](https://www.google.se/books/edition/Ultimate_Spy/EObtBgAAQBAJ?hl=ru&gbpv=1&dq=inauthor:%22H.+Keith+Melton%22&printsec=frontcover)
- 케빈 미트닉의 베스트셀러 도서](https://www.mitnicksecurity.com/bestselling-books-by-kevin-mitnick)

**제텔카스텐 방법:**

- 흑요석을 이용한 제텔카스텐 방법-스마트 노트 작성법](https://beingpax.medium.com/zettelkasten-method-with-obsidian-how-to-take-smart-notes-with-examples-cdaf348febbd)
- 옵시디언에서 제텔카스텐 설정하기: 노트 필기 앱 그 이상](https://facedragons.com/productivity/setting-up-a-zettelkasten-in-obsidian/)
- [옵시디언-제텔카스텐](https://mattgiaro.com/obsidian-zettelkasten/)
- [제텔카스텐 시작하기](https://obsidian.rocks/getting-started-with-zettelkasten-in-obsidian/)
- 어썸 OSINT](https://github.com/jivoi/awesome-osint)
- OSINT 가이드](https://github.com/drull1000/OSINT-guide)

# Work: A-Z

저는 이것을 외국어를 배우는 것으로 봅니다. 좋아, 당신은 그것을 배웠고 그 언어를 사용하는 나라에 와서 살고 있습니다. 하지만 그곳의 모든 사람들은 이 언어를 알고 있습니다. 따라서 다른 것을 추가로 아는 것이 중요합니다. 일반적으로 글쓰기 능력이 있거나 사람들과 잘 교류하거나 변호사가 될 필요가 있습니다. 하지만 접근 방식에 따라 다른 기술과 사고방식이 필요합니다!

> OSINT는 "일종의 [프런트 러닝/테일게이팅](https://www.investopedia.com/terms/f/frontrunning.asp) 또는 스캘핑이 아니라 실제 생활에서의 스캘핑"이라는 점을 명심하세요!

<details>
<summary>확장</summary>
<br />

- ["오픈소스 인텔리전스 같은 것은 없다"](https://threadreaderapp.com/thread/1633909123988242438.html)
- 오픈소스 인텔리전스(OSINT) 조사자가 되는 방법](https://www.wgu.edu/career-guide/information-technology/osint-career.html#close)
- [공격과 방어에 관한 훌륭한 책](https://www.amazon.com/Network-Attacks-Defenses-Hands-Approach-ebook/dp/B00A8SN8WQ)
- [OSINT 가이드 - 오픈 소스 인텔리전스](https://www.osintguide.com/2023/01/04/start-a-consulting-business-as-an-osint-expert/)
- [선제적 방어의 기술: OSINT 도구로 위협 헌팅 마스터하기](https://medium.com/@mohitdeswal_35470/the-art-of-proactive-defense-mastering-threat-hunting-with-osint-tools-336683d6d53b)
- [OSINT 교육의 놓친 한 학기](https://medium.com/the-sleuth-sheet/the-missing-semester-of-your-osint-education-60b7bd48b7e9)
- [사람 검색을 위한 OSINT](https://docs.google.com/spreadsheets/d/1JxBbMt4JvGr--G0Pkl3jP9VDTBunR2uD3_faZXDvhxc/edit#gid=1978517898)
- 아론CTI의 OSINT 리소스 컬렉션](https://docs.google.com/spreadsheets/d/1klugQqw6POlBtuzon8S0b18-gpsDwX-5OYRrB7TyNEw/htmlview)

</details>

**작업:**

- [anonfriendly.com](http://anonfriendly.com/)
- [osintjobs](https://twitter.com/osintjobs)
- [OSINT를 사용하여 돈을 버는 방법을 보여 드리겠습니다](https://0xtechrock.gumroad.com/)
- [OSINT 21 일용 파이썬](https://github.com/cipher387/python-for-OSINT-21-days)
- [osintjobs.sociallinks.io](https://osintjobs.sociallinks.io/)
- 온체인 조사 도구 목록](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List)
- 웹3에서 일자리를 찾는 방법](web.archive.org/web/20220618210743/https://twitter.com/_prestwich/status/1538267150917308416)
- www.jobprotocol.xyz](https://www.jobprotocol.xyz/) & [HR 게임](https://sourcing.games/) 체험하기!
- 실사
- [이미 존재하는 승무원과 함께...](https://osintfr.com/en/our-osinters-are-talented/)
- 저널리즘
- SMM
- [AML/암호화폐 조사](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List)
- [전략트라이브](https://strategytribe.io)
- 아르바이트](https://telegra.ph/Scamfari-04-28)
- OSINT 공격면 관리로 개인정보 유출 탐지](https://osintteam.blog/detect-personal-information-leakage-with-osint-attack-surface-management-4a46923dd2fd)

# 외부 데이터

**업무에 사용할 수 있는 더 많은 도구(무작위) :**

- [mullvad.net/ko/브라우저](https://mullvad.net/en/browser)
- [타이니체크](https://github.com/KasperskyLab/TinyCheck)
- [lampyre.io](https://lampyre.io/)
- [osintui](https://github.com/wssheldon/osintui)
- [Detect.Expert](https://Detect.Expert)
- [OSINT-브라우저 확장](https://github.com/cqcore/OSINT-Browser-Extensions)
- [cylect.io](https://cylect.io/)
- [tazeros.com/webanalytics](https://tazeros.com/webanalytics)
- [dorkgenius.com](https://dorkgenius.com)
- [X-osint](https://github.com/TermuxHackz/X-osint)
- [메타 웹 도구](https://meta-webtools.com/)
- [베나토르 브라우저](https://t.me/venatorbrowser)
- [app.shadowmap.org](https://app.shadowmap.org/)
- [dnstwist](https://github.com/elceef/dnstwist)
- [자동 웹 사이트 테이크다운](https://bolster.ai/automated-website-takedown)
- [OSINT+ChatGPT PDF](https://t.me/osintil/332)
- [GVision](https://github.com/GONZOsint/gvision?s=35)
- [geohints.com](https://geohints.com/)
- 소셜 미디어 OSINT 도구 모음](https://github.com/osintambition/Social-Media-OSINT-Tools-Collection)

**특정(업데이트 예정):**

> **[골든올빼미](https://osintteam.blog/safeguarding-osinters-shielding-against-disinformation-manipulation-dfbbfbf1db08)에 따르면:** 허위 정보와의 전쟁이 치열해짐에 따라 OSINT 실무자들은 조작으로부터 자신을 보호하기 위해 경계를 늦추지 말아야 합니다. 비판적 사고방식 채택, 정보 출처 다양화, 소셜 미디어 정보 확인, 사실 확인 도구 활용, 허위 정보 기법에 대한 최신 정보 유지, 신뢰할 수 있는 커뮤니티와의 협력, 다른 사람 교육, [윤리 기준 유지](https://osintteam.blog/safeguarding-osinters-shielding-against-disinformation-manipulation-dfbbfbf1db08), 정보 교차 확인 등을 통해 OSINT 종사자들은 조작으로부터 자신을 강화하고 연구의 무결성을 지킬 수 있습니다. 

- [ChatGPT + OSINT](https://m.youtube.com/watch?v=L5OlYdCWzRs&feature=youtu.be)
- [보너스 OSINT 트위터 암호화 도구 세트](https://telegra.ph/Bonus-OSINT-Twitter-Crypto-toolset-04-15)
- [어썸 OSINT 웹3](https://github.com/aaarghhh/awesome_osint_criypto_web3_stuff)
- [tgscanrobot](https://t.me/tgscanrobot)
- [벨로시랩터 앱](https://docs.velociraptor.app)
- [Web3/NFT OSINT](https://twitter.com/fuzzinglabs/status/1676226856553521153)
- [maigret_osint_bot](https://t.me/maigret_osint_bot)
- [telesint_bot](https://t.me/telesint_bot)
- [seekr 도구](https://github.com/seekr-osint/seekr)
- 데이터 저널리즘 리소스](https://github.com/r3mlab/datajournalism-resources)
- 디지털 포렌식 가이드](https://github.com/mikeroyal/Digital-Forensics-Guide)
- [트위터에서 TG 봇으로](https://t.me/TwttrToTG_Bot)
- [벨링캣 해커톤 - 스트라토스피어 프로젝트](https://github.com/elehcimd/stratosphere)
- [osint-브라질](https://github.com/osintbrazuca/osint-brazuca)
- [스파이더풋](https://github.com/smicallef/spiderfoot)
- 어썸 TG 채널](https://t.me/osintil)
- [인페인트-애니씽](https://github.com/geekyutao/Inpaint-Anything)
- 메타오신트](https://metaosint.github.io/chart)
- 말테고 트랜스폼 목록](https://github.com/cipher387/maltego-transforms-list)
- OSINT 오픈소스 도구 카탈로그](https://github.com/HowToFind-bot/osint-tools)
- 새로운 OSINT 명령줄 도구 템플릿](https://github.com/soxoj/osint-cli-tool-skeleton)
- 데프콘의 사회 공학 경진대회에서 나온 상위 OSINT 소스와 비싱 구실](https://medium.com/@chris.kirsch/top-osint-sources-and-vishing-pretexts-from-def-cons-social-engineering-competition-8e08de4c8ea8)

**멋진 기사(외부):**

> 실습에서 알 수 있듯이](https://medium.com/@ibederov_en/military-intelligence-using-osint-methods-4aae1df2d812), 현대 무력 충돌은 오픈 데이터의 수집과 분석을 조직화하는 새로운 접근 방식을 필요로 하며, 우리는 OSINT의 프레임워크 내에서 운영합니다. 행동하기 전에 신중하고 두 번 생각해야 합니다.

- [디지털 방어의 휴먼 터치: 사이버 위협에 맞서 싸우는 가상 휴민트](https://osintteam.blog/human-touch-in-digital-defense-virtual-humints-battle-against-cyber-threats-33b81b3be53b)
- [제로에서 구글 도킹 히어로로: OSINT 무기고 강화하기](https://osintteam.blog/mastering-osint-the-art-of-google-dorking-for-investigators-e0a908055873)
- [OSINT에 ddg.gg 사용](https://www.ghacks.net/2023/04/24/duckduckgo-disables-most-search-filters-from-search/?amp)
- [cybdetective.substack.com](https://cybdetective.substack.com)
- [숨겨진 연결 발견하기: 말테고 홀헤를 사용하여 개인의 디지털 발자국 매핑하기](https://medium.com/@philipbcase/uncovering-hidden-connections-using-maltego-holehe-to-map-out-a-person-digital-footprint-90914d6bcbff)
- 스파이 활동 PDF](https://t.me/irozysk/9243)
- 핵토리아 - 인신매매](https://medium.com/@wirec47/hacktoria-human-traffickers-b9bb00638c6a)
- 비밀번호 OSINT](https://viruszzwarning.medium.com/password-osint-fc4fd750ea8c)
- AI를 사용하여 사실적인 양말 인형 계정 개발](https://www.raebaker.net/blog/using-ai-to-develop-realistic-sock-puppet-accounts)
- [아카이빙 & OSINT](https://latenightafa.noblogs.org/archiving-and-osint/)
- [어썸 OSINT](https://github.com/jivoi/awesome-osint)
- [어썸 텔레그램 OSINT](https://github.com/ItIsMeCall911/Awesome-Telegram-OSINT)
- 다크넷 시각화](https://medium.com/@cosmograph.app/visualizing-darknet-6846dec7f1d7)
- 오픈 소스 인텔리전스: OSINT 초보자 가이드](https://www.liferaftinc.com/blog/the-beginners-guide-to-osint)
- 다크넷 OSINT 가이드](https://medium.com/the-sleuth-sheet/darknet-osint-guide-984f68fb7ab3)
- 초보자 필드 가이드: OSINT를 배울 수 있는 곳과 방법](https://medium.com/the-sleuth-sheet/beginners-field-guide-where-how-to-learn-osint-bd2e11469f31)
- 오픈 소스 인텔리전스 도구 및 리소스 핸드북 2020](https://i-intelligence.eu/uploads/public-documents/OSINT_Handbook_2020.pdf)
- [정보 운영 인식: 비선형 분석에서 의사 결정까지](https://arxiv.org/pdf/1901.10876.pdf)
- TOR 재단의 OSINT 분석](https://arxiv.org/pdf/1803.05201.pdf)
- 닉네임 조사를 위한 상위 10가지 OSINT 도구](https://medium.com/@ibederov_en/my-top-10-osint-tools-for-nickname-investigation-40e292fa5c84)

**몇 가지 뛰어난 도구:**

 > 기억하세요, 당신의 임무](https://medium.com/@ronkaminskyy/from-zero-to-sherlock-the-ultimate-osint-adventure-5f9d8c45ae2) 마지막 단계는 OSINT 기술을 유지 및 향상시키기 위한 계획을 세우는 것입니다. 지속적인 학습을 위해 몇 가지 리소스를 선택하고, 참여할 수 있는 챌린지를 찾고, OSINT 커뮤니티 가입을 고려하세요. 마지막으로, 윤리 지침을 검토하여 항상 책임감 있고 정중하게 일하고 있는지 확인하세요. - [론 카민스키](https://medium.com/@ronkaminskyy/from-zero-to-sherlock-the-ultimate-osint-adventure-5f9d8c45ae2)

- 데이터쉐어](https://datashare.icij.org)
- 핀포인트](https://journaliststudio.google.com/pinpoint/collections)
- [dtsearch.com](https://www.dtsearch.com/)
- [베나토르](https://t.me/venatorbrowser)
- [차세대 크롤링 및 스파이더링 프레임워크](https://github.com/projectdiscovery/katana)
- [스타트미](https://about.start.me/)
- [dorksearch.com](https://dorksearch.com)
- [E4GL30S1NT](https://github.com/C0MPL3XDEV/E4GL30S1NT)
- [어드뱅글](http://advangle.com)
- 어썸-챗그프](https://github.com/sindresorhus/awesome-chatgpt)
- [옵시디언](https://obsidian.md/)
- [dorkgenius.com](https://dorkgenius.com)
- [카나리아 토큰](https://canarytokens.org/generate)
- [iplogger.org](https://iplogger.org)
- 유니버설 검색](https://t.me/UniversalSearchRobot)
- 인터셉터-NG](http://sniff.su/)
- [메타데이터투고닷컴](https://www.metadata2go.com)
- [suip.biz](https://suip.biz/)
- [어썸 디블러링](https://github.com/subeeshvasu/Awesome-Deblurring)

**심층(외부):**

> **[알레산드라 아디나](https://medium.com/@alessandraadina/how-to-do-cyber-reconnaissance-a-guide-to-osint-for-non-tech-professionals-da6c7db48699)에 따르면:** 인텔리전스 사이클은 원시 정보를 실행 가능한 인텔리전스로 개발하는 과정을 나타냅니다. 이 프로세스를 통해 의사결정권자는 조사 결과를 바탕으로 적절한 조치를 취할 수 있습니다. 조직마다 다양한 인텔리전스 주기를 사용하지만, 가장 널리 사용되는 주기는 5단계 주기입니다: **계획, 수집, 분석, 배포, 피드백**의 5단계 주기가 널리 사용됩니다.

- OSINT: 누구에 대한 정보를 찾는 방법](https://osintteam.blog/osint-how-to-find-information-on-anyone-5029a3c7fd56)
- OSINT - 초보자 가이드(파트 1)](https://medium.com/@Aardwarewolf/what-is-osint-part-1-91aaa3890643)
- [OSINT: 기초](https://i-intelligence.eu/courses/osint-foundations)
- OSINT를 사용하여 데이터 유출 및 침해를 탐지하는 방법](https://www.liferaftinc.com/blog/how-to-use-osint-to-detect-data-leaks-and-breaches)
- OSINT 소개](https://infosecwriteups.com/introduction-to-osint-2c92597988d1)
- [소셜 미디어를 사용하여 사이버 공격 탐지를 개선하는 방법](https://www.geeksforgeeks.org/how-to-improve-cyber-attack-detection-using-social-media/)
- 웹에서 정보가 유출되고 있나요? 이 도구를 사용하여 알아보세요](https://www.tech.gov.sg/media/technews/are-you-leaking-information-on-the-web)
- OSINT: 데이터 유출 및 데이터 침해](https://www.osintguru.com/blog/osint-data-leaks-and-data-breaches)
- [OSINT와 gOSINT](https://brandefense.io/blog/osint-with-gosint/)
- OSINT 웹 리소스 목록](https://github.com/OhShINT/ohshint.gitbook.io/blob/main/Lists_of_OSINT_Web_Resources/1-Complete-List-of-OSINT-Web-Resources.md)
- OSINT/SOCMINT 마인드맵](http://files.mtg-bi.com/MindMap.jpg)
- [찾는 방법 - 로봇](https://t.me/HowToFind)
- 비밀번호 게임](https://neal.fun/password-game/)
- 사이버 보안에서 OSINT를 사용하는 방법](https://www.molfar.global/en-blog/how-to-use-osint-in-cybersecurity)
- [오픈소스 인텔리전스(OSINT) - 해킹하기 어려워진다!](https://somprt.com/our-series/osint-open-source-intelligence/)
- 깃허브 OSINT 토픽](https://github.com/topics/open-source-intelligence?o=desc&s=stars)
- [SOCMINT - 또는 소셜 미디어의 OSINT](https://research.securitum.com/socmint-or-rather-osint-of-social-media/)

**더 구체적인 리소스(외부):**

> **[알레산드라 아디나](https://medium.com/@alessandraadina/how-to-do-cyber-reconnaissance-a-guide-to-osint-for-non-tech-professionals-da6c7db48699)에 따르면:** OSINT 영역에서 접할 수 있는 용어는 '회색문헌(grey literature)'입니다. 이는 공개용으로 의도되지 않은 내부 문서이지만, 안타깝게도 검색이 가능한 곳에 쉽게 노출될 수 있습니다. 예를 들면 기술 보고서, 뉴스레터, 송장, 사업 제안서, 제안 요청서 등이 있습니다.

> 조직 정보의 가치, 잠재적인 공격 벡터, 피싱 공격이나 기타 유형의 소셜 엔지니어링의 표적이 될 수 있는 사람을 이해하는 것은 필수적입니다. OSINT는 이러한 위험을 평가하고 적절한 방어를 계획하는 데 도움을 줄 수 있습니다.

- [뉴럴 매칭을 이용한 2D 퍼블릭 맵에서의 오리엔터넷 시각적 로컬라이제이션](https://github.com/facebookresearch/OrienterNet)
- [OSINT 도구 - 에어테이블](https://airtable.com/embed/shrYXDdO1V5y33lIX/tblgDtMXI4fxtg9Op)
- [OSINT - 휴민트](https://docs.google.com/spreadsheets/d/1JxBbMt4JvGr--G0Pkl3jP9VDTBunR2uD3_faZXDvhxc/edit#gid=1978517898)
- [궁극의 OSINT](https://start.me/p/DPYPMz/the-ultimate-osint-collection)
- OSINT 목록](https://start.me/p/ZME8nR/osint)
- [큐레이팅된 OSINT 목록](https://start.me/p/7kxyy2/osint-tools-curated-by-lorand-bodo)
- [OSINT Inception](https://start.me/p/Pwy0X4/osint-inception)
- [Geolocation-OSINT](https://github.com/cqcore/Geolocation-OSINT)
- [researchaide.org](https://www.researchaide.org/)
- [botster.io/bots 크롤링](https://botster.io/bots)
- [또 다른 멋진 OSINT 목록](https://start.me/p/rx6Qj8/nixintel-s-osint-resource-list)
- [암호화폐 OSINT](https://start.me/p/ek4rxK/cryptocurrency)
- [멋진 온체인 조사 핸드북](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List/blob/main/README.md)
- [조사자 도구](https://start.me/p/gyaOJz/investigator-tools)
- OSINT를 위한 수백 가지 온라인 도구 모음](https://github.com/cipher387/osint_stuff_tool_collection)
- 로섹의 사이버 보안 인벤토리](https://inventory.raw.pm/tools.html#title-tools-osint)
- [OSINT-도구-CLI](https://github.com/Coordinate-Cat/OSINT-TOOLS-CLI)
- 지오에스티메이션](https://labs.tib.eu/geoestimation/)
- OSINT 검색 엔진을 사용하여 사이버 위협 인텔리전스 수집](https://osintteam.blog/using-osint-search-engines-to-collect-cyber-threat-intelligence-3e9ace82eb64)
- [그래프센스 말테고 트랜스폼](https://github.com/INTERPOL-Innovation-Centre/GraphSense-Maltego-transform)
- [leakix.net](https://leakix.net/)
- Officer_CIA X MaxWorld: 콘텐츠 개요](https://officercia.medium.com/officer-cia-x-maxwayld-content-overview-39fa3011a73f)
- [다크 사이드 탐험: 다크 웹 운영의 마스크를 벗기기 위한 OSINT 도구 및 기법](https://www.sans.org/blog/exploring-the-dark-side-osint-tools-and-techniques-for-unmasking-dark-web-operations/)

**텔레그램 + 디스코드: 보안, OSINT, SOCMINT:**

 > 론 카민스키](https://osintteam.blog/unveiling-the-digital-detective-essential-osint-tools-and-techniques-for-investigators-adf486ad2ccd)에 따르면: OSINT는 수사의 세계에 혁명을 일으켜 개인과 조직이 귀중한 정보를 발견하고 복잡한 문제를 해결하며 정보에 입각한 결정을 내릴 수 있도록 지원합니다. [오픈 소스에서 사용할 수 있는 방대한 양의 데이터를 활용할 수 있는 능력](https://osintteam.blog/unveiling-the-digital-detective-essential-osint-tools-and-techniques-for-investigators-adf486ad2ccd)은 새로운 가능성을 열어주고 수사 환경을 변화시켰습니다. 수사관들은 OSINT 도구를 효과적으로 활용함으로써 시간을 절약하고, 포괄적인 정보를 수집하고, 숨겨져 있을 수 있는 연관성을 발견할 수 있습니다. 이 가이드에서 살펴보는 기술과 방법론은 철저하고 성공적인 OSINT 조사를 수행하기 위한 로드맵을 제공합니다.

- 휴대폰, 태블릿 또는 PC의 정확한 위치를 찾는 방법](https://medium.com/@ibederov_en/how-to-find-the-exact-location-of-phone-tablet-or-pc-b953a60421a9)
- osint-mindset.gitbook.io](https://osint-mindset.gitbook.io) | 팁: deepl.com](https://www.deepl.com/translator) 사용!
- 디스코드 OSINT 툴셋](https://telegra.ph/Discord-OSINT-Toolset-04-11)
- [DiscordOSINT](https://github.com/AtonceInventions/DiscordOSINT)
- [텔레그램 OSINT](https://github.com/cqcore/Telegram-OSINT)
- [OSINT 디스코드 리소스](https://github.com/Dutchosintguy/OSINT-Discord-resources)
- [텔레그램온라인스파이](https://github.com/Forichok/TelegramOnlineSpy)
- [디스코드 & 텔레그램 OSINT 참고자료](https://github.com/Ginsberg5150/Discord-and-Telegram-OSINT-references)
- [어썸 디스코드](https://github.com/jacc/awesome-discord)
- [어썸 텔레그램 OSINT](https://github.com/ItIsMeCall911/Awesome-Telegram-OSINT)
- [다베스터](https://github.com/darvester/darvester)
- 텔레그램 & 디스코드 옵섹](https://officercia.mirror.xyz/dlf6ZEXq3FLE21ZY2jeJ0cBDyuZu8XIF9DEJAQ07nk8)
- 서버용 디스코드 옵섹](https://officercia.mirror.xyz/x4nGX6YwhhmHj8TaQ53kBR5b5M1Ei_Y9_l1Vpext-Hk)
- 사기를 당했다면...](https://officercia.mirror.xyz/X5Q0uPwvlgZ6BrvCmyqXlXHFgLAWrMtzAHSvjzrDS7c)

**내 기사 확인하기:**

- 탐색 (내 글)](https://officercia.mirror.xyz/Uc1sf64yUCb0uo1DxR_nuif5EmMPs-RAshDyoAGEZZY)
- 원본 기사](https://officercia.mirror.xyz/5KSkJOTgMtvgC36v1GqZ987N-_Oj_zwvGatOk0A47Ws)
- [스마트해지는 옵섹](https://officercia.mirror.xyz/fsRT9NC29GzeQAl-zvAMJ9L-hYUYvX1CPUkt97Vuuwo)
- [OpSec Going Smarter](https://officercia.mirror.xyz/B9hBom4jGhkV0C-47E4YBz8tBJkb0a7zVwQR0jITIyM)
- [더 스마트해지는 옵섹: 스마트폰 보안](https://officercia.mirror.xyz/0tlSSF2LDTOnnMN41R5Uc1kTpo-G-kXljn8pT0a1YLY)
- [생활과 직장을 위한 신뢰할 수 있는 VPN 제공업체 선택](https://officercia.mirror.xyz/x91hTIDFrAL0lgqICRgWU7fLouuCMgvopQ9ZRvRXCLg)
- 온체인 생존자가 안전을 유지하기 위해 지켜야 할 최고의 규칙 목록](https://officercia.mirror.xyz/_nD1Rtxe1PplK-NQzIq9sl-KNtajQG0aKqYsV36RTjA)
- QR 코드: 과소평가된 위험](https://officercia.mirror.xyz/aN6giRkUsNd0o0bmjZVeZb2htkO_Ve16gMsARU6RBfM)
- 커뮤니케이션 발전의 가장 중요한 이정표](https://officercia.mirror.xyz/G4782jMUpA_kkIpwakphbd6djX85cxRGS-pjBipc8Yk)
- 전쟁에서 승리하고, KGB를 속이고, 스테가노그래피에 의한 도난으로부터 암호화 자산을 보호하는 방법](https://officercia.mirror.xyz/8ecJG-s_5E6J1t-h8gUNGqV3hbX8If-E5NnrFrOJHUA)
- 대표 샘플을 통한 공격: 신화와 현실](https://officercia.mirror.xyz/WeAilwJ9V4GIVUkYa7WwBwV2II9dYwpdPTp3fNsPFjo)
- [어떻게 하면 1인 기업형 OSINT 전문가가 될 수 있을까요?](https://officercia.mirror.xyz/5KSkJOTgMtvgC36v1GqZ987N-_Oj_zwvGatOk0A47Ws)
- 텔레그램 & 디스코드 보안 모범 사례](https://officercia.mirror.xyz/dlf6ZEXq3FLE21ZY2jeJ0cBDyuZu8XIF9DEJAQ07nk8)

# 지원 프로젝트

지원은 저에게 **매우** 중요하며, 이를 통해 직장에서 보내는 시간을 줄이고 제가 좋아하는 일, 즉 디파이 및 암호화폐 사용자 교육에 집중할 수 있습니다 :sparkling_heart:

제 작업을 지원하고 싶으시다면 다음 주소로 후원을 고려해 주세요:

- **[0xB25C5E8fA1E53eEb9bE3421C59F6A66B786ED77A](https://etherscan.io/address/0xB25C5E8fA1E53eEb9bE3421C59F6A66B786ED77A)** — ERC20 & ETH [officercia.eth](https://etherscan.io/enslookup-search?search=officercia.eth)

- **[17Ydx9m7vrhnx4XjZPuGPMqrhw3sDviNTU](https://blockchair.com/bitcoin/address/17Ydx9m7vrhnx4XjZPuGPMqrhw3sDviNTU)** - BTC

- **4AhpUrDtfVSWZMJcRMJkZoPwDSdVG6puYBE3ajQABQo6T533cVvx5vJRc5fX7sktJe67mXu1CcDmr7orn1CrGrqsT3ptfds** - Monero XMR

이 저장소](https://github.com/OffcierCia/support)의 주소로 기부금을 보내주실 수도 있습니다!

**이것도 확인해보세요:**

- 내 블로그 미러](https://officercia.mirror.xyz/UpFfG7-1E4SDJttnmuQ7v4BMc4KrCXzo80vtx7qV-YY)

### 고마워요! 🙏
