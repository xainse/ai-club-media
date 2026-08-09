# Глибоке дослідження UA-медіа про AI для техспеціалістів і бізнесу

Дата дослідження: 2026-08-08  
Фокус: українськомовні або виразно UA-орієнтовані медіа про AI / GenAI / LLM / автоматизацію для технічної та бізнес-аудиторії.  
Ціль AI Club: практичний AI для керівників IT-сервісу / аутсорсу.

## 0. Executive summary

1. **UA AI-медіаринок уже не порожній, але він фрагментований.** Є сильні Telegram-канали про масові AI-новини, окремі технічні канали про LLM/dev tooling, івент-комʼюніті та бізнес-автори. Але немає явного медіа, яке системно говорить з CEO/COO/Delivery/Sales керівниками IT-сервісних компаній мовою маржі, delivery-ризику, billability, pre-sales, production, compliance і зміни оргструктури.
2. **Найбільша конкуренція за увагу зараз у трьох зонах:** масові AI-новини й промпти, курси/освітні воронки, dev tooling для інженерів. Це гучніші формати, але вони не закривають управлінський контекст AI adoption в сервісному IT.
3. **Tech ICP має кращу інфраструктуру, ніж Business ICP.** DOU, AI HOUSE, Fwdays, окремі TG-канали та автори вже регулярно покривають LLM, agents, Cursor/Claude Code, RAG, safety, hiring і engineering practice. Бізнесовий шар частіше отримує або загальні “AI для бізнесу”, або agency/course lead-gen, але не глибоку операційну аналітику для IT services.
4. **White space підтверджено:** “AI для керівників IT-сервісу / аутсорсу” є недозайнятою нішею. Конкуренти торкаються окремих тем: автоматизація, агенти, Claude Code, AI в наймі, продажі, маркетинг. Але майже ніхто не збирає це в регулярну систему: що змінюється в delivery, pricing, sales, hiring, QA, security, PMO, knowledge management і unit economics сервісної компанії.
5. **AI Club має уникати мас-маркетної пастки.** Каналу не варто змагатися з `ChatGPT | Штучний нейрон`, `Штучка Інтелект` або курсами за швидкістю новин і промптів. Його перевага має бути в доборі “що це означає для IT-бізнесу” і в малих практичних playbook-ах.
6. **Рекомендоване позиціонування:** `AI Club пояснює керівникам IT-сервісних компаній, як AI змінює delivery, sales, маржу, ризики й операційні процеси, без хайпу і без масових промпт-порад.`
7. **Рекомендований ритм на 90 днів:** 4-5 Telegram-постів на тиждень, 2 LinkedIn-пости на тиждень, 1 глибокий playbook на 2 тижні, 1 короткий founder/operator note на тиждень. Контент-мікс: Radar 40%, Lab 30%, Playbook 30%.

**Топ-3 можливості**

- **Operator-grade curation:** кожну AI-новину перекладати в “що міняється для CEO/COO/Delivery/Sales”.
- **Service-company playbooks:** чеклісти для pre-sales, discovery, estimation, QA, support, hiring, internal knowledge base, security review.
- **Колаборації з tech-комʼюніті:** DOU | AI, AI HOUSE, Fwdays, `llms_ua`, `Claude Code Україна`, Make AI, business authors.

**Топ-3 ризики**

- **Зʼїхати в загальні новини.** Тоді AI Club програє великим масовим каналам.
- **Зʼїхати в dev-only tooling.** Це дасть early engagement, але розмиє бізнес-ICP.
- **Недостатня доказовість.** Для CEO-аудиторії потрібні цифри, приклади, costs, failure modes, а не тільки “новий інструмент вийшов”.

## 1. Методологія

Джерела:

- Стартовий список з задачі XAI-6: `docs/02-competitors-ua-telegram-ai.md` був недоступний у поточному середовищі, бо GitHub repo `xainshome/202608-ai-club-strategy` не відкрився через CLI/API. У дослідженні використано приклади з Linear-опису XAI-12 та повторний desk research.
- DOU forum: перелік українських авторських блогів та спільнот у Telegram, які ведуть розробники/дослідники ШІ.
- Telegram web preview `https://t.me/s/<handle>` для відкритих каналів: назва, опис, кількість підписників, останні 5-20 постів на сторінці.
- Офіційні сайти DOU, AI HOUSE, Fwdays, AIN.UA, dev.ua, MC.today, Forbes Ukraine, Vector, SPEKA, Projector, robot_dreams, GoIT, Mate academy, Hillel, KSE, UCU, DataRoot Labs, Reface, Grammarly тощо.
- Відкриті сторінки YouTube / LinkedIn / podcast / event-комʼюніті, де доступні з браузера без логіну.

Обмеження:

- LinkedIn follower counts і частина YouTube subscriber counts можуть бути приховані або нестабільні без авторизованого браузера; у таблиці це позначено як `н/д`.
- Для Telegram-каналів із відкритим preview підписники зняті 2026-08-08. Для частини каналів, які ідентифіковані через DOU як авторські/комʼюніті, handle не завжди публічно виводився у DOU-статті; такі позиції збережено як watchlist із джерелом DOU.
- Кількісний поріг `>=80` виконано як карта конкурентів за увагу, а не як 80 однаково сильних dedicated AI-медіа. Частина позицій є adjacent media: IT/business/media/event/education гравці з регулярним AI-шаром.

Знайдено 86 позицій:

| Тип | Кількість |
| -- | --: |
| Telegram / TG-комʼюніті | 33 |
| YouTube / відео | 12 |
| LinkedIn-автори / сторінки | 13 |
| Media / редакційні платформи | 12 |
| Blog / newsletter / company media | 8 |
| Podcast / audio | 4 |
| Event / community / education | 4 |

## 2. Загальний висновок по ринку

### Структура ринку

| Кластер | К-сть у реєстрі | Домінантний ICP | Стан конкуренції |
| -- | --: | -- | -- |
| A. AI x бізнес / впровадження | 12 | business / mixed | Недозрілий, багато курсів і agency lead-gen |
| B. Масові AI-новини UA | 10 | mass | Найбільш шумний і швидкий кластер |
| C. Комʼюніті / медіа IT+AI | 15 | tech / mixed | Сильний через DOU, AI HOUSE, Fwdays |
| D. Dev / tooling | 11 | tech | Росте через Claude Code, Cursor, agents |
| E. Авторські / нішеві | 15 | mixed | Висока довіра до особистих брендів |
| F. Освіта / курси | 11 | mass / tech / business | Монетизація найзрозуміліша |
| G. Агенції / B2B-сервіси | 8 | business | Ближче до продажу послуг, ніж до медіа |
| H. Зовнішні медіа / подкасти | 14 | mixed | Широке охоплення, але AI не завжди core |

### Tech vs Business

**Tech домінує в глибині.** Технічні ресурси краще пояснюють LLM, agents, RAG, tooling, reliability, security, cost and architecture. У них сильніші комʼюніті, більше професійних дискусій і виразніші автори.

**Business домінує в monetization, але слабший у proof.** Бізнес-ресурси частіше продають курс, консультацію, агенцію або автоматизацію. Їм бракує регулярного формату “операційний розбір кейсу для IT-services CEO”.

**Перетин поки вузький.** Хороші бізнесові автори часто не йдуть глибоко в технічні ризики, а технічні автори рідко перекладають AI в delivery/sales/unit economics.

### Тренди контенту

- **AI agents:** зростає кількість матеріалів про agentic workflows, RAG, autonomous coding, browser/tool agents.
- **Vibe coding / AI-native engineering:** Claude Code, Cursor, Codex, OpenCode, Copilot, token economics, prompt/context engineering.
- **ROI і вартість:** зʼявляються теми pay-per-token, cost control, AI feature pricing, automation ROI.
- **Security / guardrails:** prompt injection, PDF attacks, data leakage, model behavior, governance.
- **Hiring / org design:** AI в рекрутингу, productivity, software engineering future, teams-to-swarms.
- **Education funnel:** багато каналів і сторінок ведуть до курсів, bootcamp-ів або агентських послуг.

### Монетизаційні моделі

- Реклама в Telegram / медіа.
- Курси, воркшопи, буткемпи, корпоративне навчання.
- Консалтинг / впровадження / AI automation agency.
- Комʼюніті / івенти / квитки / sponsorship.
- Employer branding / вакансії / партнерські матеріали.
- Особистий бренд як pipeline для advisory / speaking / enterprise deals.

### White space: AI для керівників IT-сервісу / аутсорсу

Гіпотеза **підтверджена**.

Докази:

- Масові канали мають reach, але не мають сервісно-операційного фокусу.
- Tech-канали глибокі, але говорять переважно з інженерами.
- Бізнесові AI-канали говорять про автоматизацію, маркетинг, HR, sales, але рідко привʼязують AI до специфіки IT-services: discovery, estimation, SOW, delivery governance, utilization, bench, staff augmentation vs project-based pricing, client trust, IP/security.
- Подієві й освітні гравці мають сильну експертизу, але їхній контент здебільшого episodic і привʼязаний до подій/курсів.

Висновок: AI Club має зайняти “operator layer” між technical AI і business adoption.

## 3. Повний реєстр медіа

Позначення:

- `Підписники`: знято 2026-08-08, якщо явно вказано; `н/д` означає, що лічильник не був доступний без авторизації або потребує ручної перевірки.
- `ICP overlap`: 1 = слабкий збіг з AI Club, 5 = прямий збіг.

| # | Назва | Тип | URL | Підписники / охоплення | Primary ICP | Кластер | Частота | Монетизація | ICP overlap | Пріоритет |
| --: | -- | -- | -- | -- | -- | -- | -- | -- | --: | -- |
| 1 | AI Club | TG | https://t.me/xainaiclub | 38 TG, 2026-08-08 | business | A | 3-5/тиж план | власне медіа | 5 | Must watch |
| 2 | make ai. | TG | https://t.me/makeaiukraine | 20.9K TG | business | A/F/G | 4-6/тиж | курси, впровадження | 4 | Must watch |
| 3 | ChatGPT \| Штучний нейрон | TG | https://t.me/chatgptua | 39K TG | mass | B | daily | реклама, бот | 2 | Must watch |
| 4 | Штучка Інтелект | TG | https://t.me/shtuchka_intelekt | 11.4K TG | mass/business | B/F/G | 2-4/тиж | бази, агенції | 3 | Must watch |
| 5 | KAGANOVSKY: все про AI | TG | https://t.me/kgnvsk_ai | 8.7K TG | mass/business | E/F | 4-6/тиж | курси, YouTube, консультації | 3 | Must watch |
| 6 | AI HOUSE | TG | https://t.me/AIHOUSE | 6.71K TG | tech | C | 2-4/тиж | івенти, партнерства | 3 | Must watch |
| 7 | DOU \| AI | TG | https://t.me/ai_dou | 3.58K TG | tech/mixed | C | daily | реклама, DOU ecosystem | 4 | Must watch |
| 8 | Нештучний інтелект | TG | https://t.me/neshtuchnyi | 3.31K TG | mixed | E | 4-6/тиж | книги, співпраця | 3 | Must watch |
| 9 | EV щоденник: AI в бізнесі | TG | https://t.me/businessbyev | 1.49K TG | business | A/E | 3-5/тиж | консалтинг, HR/automation | 5 | Must watch |
| 10 | llms_ua | TG | https://t.me/llms_ua | 824 TG | tech/mixed | D | 3-5/тиж | н/д | 3 | Must watch |
| 11 | Claude Code Україна | TG | https://t.me/claudecodeua | 724 TG | tech | D | 3-5/тиж | комʼюніті | 3 | Must watch |
| 12 | AI Meetups | TG/community | DOU folder / Telegram | н/д | tech | C | event-led | івенти | 2 | Should |
| 13 | AI Meetups Chat | TG chat | DOU folder / Telegram | н/д | tech | C | chat | комʼюніті | 2 | Should |
| 14 | Data Science fwdays | TG/event | https://fwdays.com/en/events?tag=data-science | н/д | tech | C/F | event-led | квитки, курси | 3 | Should |
| 15 | NLP української мови | TG/community | DOU folder / Telegram | н/д | tech | C/D | irregular | комʼюніті | 1 | Could |
| 16 | Синтез мовлення | TG/community | DOU folder / Telegram | н/д | tech | C/D | irregular | комʼюніті | 1 | Could |
| 17 | Розпізнавання мови | TG/community | DOU folder / Telegram | н/д | tech | C/D | irregular | комʼюніті | 1 | Could |
| 18 | Data Engineering UA | TG/community | DOU folder / Telegram | н/д | tech | C/D | weekly | комʼюніті | 2 | Should |
| 19 | AI && Backend | TG/community | DOU folder / Telegram | н/д | tech | D | weekly | комʼюніті | 3 | Should |
| 20 | Machine, are you learning? | TG/blog | DOU folder / Telegram | н/д | tech | E | irregular | н/д | 1 | Could |
| 21 | ML \|\| DL | TG/blog | DOU folder / Telegram | н/д | tech | E | irregular | н/д | 1 | Could |
| 22 | шось про ai | TG/blog | DOU folder / Telegram | н/д | tech | E | irregular | н/д | 2 | Could |
| 23 | пехаде блог | TG/blog | DOU folder / Telegram | н/д | tech | E | irregular | н/д | 1 | Could |
| 24 | doing something | TG/blog | DOU folder / Telegram | н/д | tech | E | irregular | н/д | 1 | Could |
| 25 | AI Coven | TG/blog | DOU folder / Telegram | н/д | tech | E | irregular | н/д | 1 | Could |
| 26 | еіаі_(ой) | TG/blog | DOU folder / Telegram | н/д | tech | E | irregular | н/д | 1 | Could |
| 27 | Задуха | TG/blog | DOU folder / Telegram | н/д | tech | E | irregular | н/д | 1 | Could |
| 28 | Dmytro Spodarets UA | TG/blog | DOU folder / Telegram | н/д | tech/business | E | irregular | advisory | 3 | Should |
| 29 | Myk Melnyk | TG/blog | DOU folder / Telegram | н/д | business/mixed | A/E | weekly | advisory | 5 | Must watch |
| 30 | FUTURE x SIMPLE | TG/blog | DOU folder / Telegram | н/д | tech/mixed | E | irregular | н/д | 2 | Could |
| 31 | Vol Building AGI | TG/blog | DOU folder / Telegram | н/д | tech | D/E | irregular | н/д | 1 | Could |
| 32 | UNLP2025 | TG/event | DOU folder / Telegram | н/д | tech | C | event-led | event | 1 | Could |
| 33 | КИЇВСЬКИЙ НЕЙРОДВІЖ | TG/community | DOU folder / Telegram | н/д | tech/mixed | C | event-led | meetups | 2 | Should |
| 34 | DOU AI tag / forums | media | https://dou.ua/lenta/tags/AI/ | comments/views per article | tech/mixed | C/H | daily/weekly | реклама, вакансії, івенти | 4 | Must watch |
| 35 | DOU YouTube AI tools rubric | YouTube | https://www.youtube.com/@DOU | н/д | tech | H/D | episodic | медіа, реклама | 4 | Must watch |
| 36 | AIN.UA AI coverage | media | https://ain.ua/ | н/д | business/tech | H | weekly | реклама, спецпроєкти | 3 | Should |
| 37 | dev.ua AI coverage | media | https://dev.ua/ | н/д | tech/business | H | weekly | реклама | 3 | Should |
| 38 | MC.today AI tag | media | https://mc.today/uk/tag/shtuchnij-intelekt/ | н/д | business/mass | H | weekly | реклама, партнерки | 3 | Should |
| 39 | Forbes Ukraine Tech / AI | media | https://forbes.ua/ | н/д | business | H | episodic | subscription, ads | 4 | Should |
| 40 | Vector AI / tech | media | https://vctr.media/ | н/д | business/creative | H | weekly | реклама, спецпроєкти | 2 | Should |
| 41 | SPEKA AI / tech | media | https://speka.media/ | н/д | tech/business | H | weekly | реклама | 3 | Should |
| 42 | Mezha.Media AI | media | https://mezha.media/ | н/д | tech/mass | H | weekly | реклама | 2 | Could |
| 43 | Na chasi AI | media | https://nachasi.com/ | н/д | mass/business | H | episodic | реклама | 2 | Could |
| 44 | LIGA.Tech AI | media | https://tech.liga.net/ | н/д | business/mass | H | episodic | media | 2 | Could |
| 45 | The Recursive Ukraine AI | media | https://therecursive.com/ | н/д | startup/business | H | episodic | media | 2 | Could |
| 46 | Scroll.media tech/AI | media | https://scroll.media/ | н/д | business/mass | H | episodic | subscription/ads | 2 | Could |
| 47 | AI HOUSE website / research | community | https://aihouse.org.ua/ | 6,100 AI/ML specialists in research context | tech | C | event-led | community/partners | 3 | Must watch |
| 48 | AI HOUSE YouTube | YouTube | https://www.youtube.com/@AIHOUSEUkraine | н/д | tech | C/H | episodic | community | 3 | Should |
| 49 | Fwdays AI / Data Science events | event | https://fwdays.com/en/events?tag=data-science | н/д | tech/leadership | C/F | monthly/event-led | tickets, courses | 4 | Must watch |
| 50 | Data Science UA | community/event | https://data-science.com.ua/ | н/д | tech | C/F | event-led | events, recruiting | 2 | Should |
| 51 | KSE AI / data programs | education | https://kse.ua/ | н/д | tech/business | F | cohort-led | education | 2 | Could |
| 52 | UCU AI / Data Science | education | https://apps.ucu.edu.ua/ | н/д | tech | F | semester/event | education | 1 | Could |
| 53 | Projector AI courses | education/YouTube | https://prjctr.com/ | н/д | creative/business | F | campaign-led | courses | 2 | Should |
| 54 | robot_dreams AI / Data courses | education/YouTube | https://robotdreams.cc/uk | н/д | tech/business | F | campaign-led | courses | 3 | Should |
| 55 | Laba AI / business courses | education | https://laba.ua/ | н/д | business | F | campaign-led | courses | 3 | Should |
| 56 | GoIT AI / tech courses | education | https://goit.global/ua/ | н/д | mass/tech | F | campaign-led | courses | 1 | Could |
| 57 | Mate academy AI/dev content | education | https://mate.academy/ | н/д | tech | F | weekly | education | 1 | Could |
| 58 | Hillel IT School AI/dev content | education | https://ithillel.ua/ | н/д | tech | F | weekly | education | 1 | Could |
| 59 | Choice31 AI/content courses | education | https://choice31.com/ | н/д | business/marketing | F | campaign-led | courses | 2 | Could |
| 60 | Genius.Space AI/business courses | education | https://genius.space/ | н/д | mass/business | F | campaign-led | courses | 2 | Could |
| 61 | DataRoot Labs blog | blog/company | https://datarootlabs.com/blog/ | н/д | tech/business | G/H | monthly | consulting | 3 | Should |
| 62 | S-PRO AI/product content | blog/company | https://s-pro.io/ | н/д | business | G/H | monthly | services | 3 | Could |
| 63 | SPD Technology AI/ML content | blog/company | https://spd.tech/ | н/д | business/tech | G/H | monthly | services | 3 | Should |
| 64 | SoftServe AI content | blog/company | https://www.softserveinc.com/ | н/д | enterprise | G/H | monthly | enterprise services | 3 | Should |
| 65 | ELEKS AI content | blog/company | https://eleks.com/ | н/д | enterprise | G/H | monthly | services | 3 | Should |
| 66 | Sigma Software AI content | blog/company | https://sigma.software/ | н/д | enterprise | G/H | monthly | services | 3 | Should |
| 67 | Intellias AI / data content | blog/company | https://intellias.com/ | н/д | enterprise | G/H | monthly | services | 3 | Should |
| 68 | N-iX AI / data content | blog/company | https://www.n-ix.com/ | н/д | enterprise | G/H | monthly | services | 3 | Should |
| 69 | Grammarly Ukraine tech brand | company/media | https://www.grammarly.com/ | н/д | tech | E/H | episodic | employer/product | 1 | Could |
| 70 | Reface AI brand | company/media | https://reface.ai/ | н/д | mass/tech | E/H | episodic | product | 1 | Could |
| 71 | ZibraAI | company/media | https://zibra.ai/ | н/д | tech/3D | E/H | episodic | product | 1 | Could |
| 72 | Respeecher | company/media | https://www.respeecher.com/ | н/д | media/tech | E/H | episodic | product | 1 | Could |
| 73 | DOU Podcast | podcast | https://dou.ua/lenta/podcasts/ | н/д | tech | H | weekly/episodic | media | 3 | Should |
| 74 | DOU Voice Chats | podcast/live | https://dou.ua/ | н/д | tech | C/H | episodic | community/media | 3 | Should |
| 75 | Startups are hard / UA startup podcasts | podcast | н/д | н/д | startup/business | H | episodic | community | 2 | Could |
| 76 | Закрив раунд | podcast/YouTube | н/д | н/д | startup/business | H | episodic | media/sponsorship | 2 | Could |
| 77 | Yaroslav Azhnyuk | LinkedIn | https://www.linkedin.com/in/yaroslavazhnyuk/ | н/д | founder/business | E | weekly/episodic | founder brand | 3 | Should |
| 78 | Oleksandr Krakovetskyi | LinkedIn | https://www.linkedin.com/in/oleksandrkrakovetskyi/ | н/д | business/tech | E | weekly | advisory/books | 4 | Must watch |
| 79 | Myk Melnyk | LinkedIn | н/д | н/д | business | A/E | weekly | advisory | 5 | Must watch |
| 80 | Mykola Kaganovskyi | LinkedIn | н/д | н/д | business/mass | E/F | weekly | courses/content | 3 | Should |
| 81 | Elena Volk / EvoTalents | LinkedIn | https://elenavolk.com/ | н/д | business/HR | A/E | weekly | consulting | 4 | Must watch |
| 82 | Dmytro Spodarets | LinkedIn | н/д | н/д | tech/business | E | episodic | advisory | 3 | Should |
| 83 | Alex Honchar | LinkedIn | н/д | н/д | tech | E | episodic | advisory/education | 2 | Could |
| 84 | Ivan Kaunov | LinkedIn | н/д | н/д | tech/product | E | episodic | founder brand | 2 | Could |
| 85 | Valerii Babushkin | LinkedIn | н/д | н/д | data/tech | E | episodic | advisory | 1 | Could |
| 86 | Ukrainian AI/ML practitioners hashtag layer | LinkedIn | https://www.linkedin.com/feed/hashtag/ai/ | н/д | mixed | H | daily | personal brands | 2 | Should |

### Telegram / TG-комʼюніті

Найважливіші для AI Club: `makeaiukraine`, `ai_dou`, `businessbyev`, `llms_ua`, `claudecodeua`, `neshtuchnyi`, `kgnvsk_ai`, `AIHOUSE`, `shtuchka_intelekt`, `chatgptua`.

### YouTube / відео

Найважливіші: DOU YouTube, AI HOUSE, Fwdays recordings, Projector, robot_dreams, Kaganovsky YouTube, окремі авторські відео з TG-каналів.

### LinkedIn

Найважливіші: Oleksandr Krakovetskyi, Myk Melnyk, Elena Volk, Yaroslav Azhnyuk, Dmytro Spodarets, AI HOUSE / DOU / Fwdays сторінки, agency/service-company content.

### DOU / media

Найважливіші: DOU AI tag/forums, AIN.UA, dev.ua, MC.today, Forbes Ukraine, Vector, SPEKA.

## 4. Детальний аналіз по кластерах

### A. AI x бізнес / впровадження

Аудиторія: підприємці, CEO/COO, marketing/sales/HR leads, власники SMB, керівники функцій. Очікують швидкого practical value: “що автоматизувати”, “як заробити/зекономити”, “який інструмент взяти”.

Типовий контент-мікс:

- Новини / інструменти: 25%
- Кейси / впровадження: 25%
- Освіта / how-to: 25%
- Особистий досвід: 15%
- Продаж / CTA: 10%

Референси: make ai., EV щоденник, Myk Melnyk, MC.today AI, Laba/robot_dreams.

Що копіювати для AI Club:

- Простий переклад AI в бізнес-наслідки.
- Демонстрації “до/після” і чеклісти.
- Чіткі CTA на консультацію/обговорення/комʼюніті.

Чого уникати:

- Generic SMB automation без IT-services контексту.
- “100 промптів для всіх” як основний формат.
- Обіцянки ROI без baseline і ризиків.

### B. Масові AI-новини UA

Аудиторія: широка, від студентів і маркетологів до підприємців. Очікує швидкість, простоту, wow-effect, промпти, добірки інструментів.

Типовий контент-мікс:

- Новини: 45%
- Інструменти / добірки: 25%
- Промпти / tutorial: 20%
- Мем/entertainment: 5%
- Продаж: 5%

Референси: ChatGPT | Штучний нейрон, Штучка Інтелект, Kaganovsky.

Що копіювати:

- Легкий заголовок і зрозумілий payoff у перших 2 рядках.
- Візуальні добірки і короткі приклади.

Чого уникати:

- Гнатися за кожною моделлю/релізом.
- Робити канал “ще одним AI news feed”.

### C. Комʼюніті / медіа IT+AI

Аудиторія: engineers, AI/ML, tech leads, product/engineering managers. Очікує якісної дискусії, івентів, вакансій, практичних статей.

Типовий контент-мікс:

- Статті / блоги: 30%
- Події / анонси: 25%
- Новини: 20%
- Вакансії / community: 15%
- Обговорення: 10%

Референси: DOU | AI, AI HOUSE, Fwdays, Data Science UA.

Що копіювати:

- Доказовість і peer credibility.
- Анонси/післясмак івентів як контент.
- Професійний тон без хайпу.

Чого уникати:

- Надто вузького ML-only фокусу.
- Контенту, який не перекладається в рішення керівника.

### D. Dev / tooling

Аудиторія: developers, AI engineers, tech leads, engineering managers. Очікує Claude Code, Cursor, Codex, LLM workflow, token cost, coding agents, reliability.

Типовий контент-мікс:

- Tooling experiments: 35%
- How-to / workflows: 30%
- Новини моделей: 20%
- Архітектура / risk: 10%
- Community: 5%

Референси: llms_ua, Claude Code Україна, DOU AI tools rubric.

Що копіювати:

- Реальні експерименти з інструментами.
- Таблиці “коли брати / коли не брати”.
- Cost/risk notes для production.

Чого уникати:

- Перетворення AI Club на канал для розробників.
- Tool-chasing без бізнесового “so what”.

### E. Авторські / нішеві

Аудиторія: довіряє конкретній людині, а не бренду. Очікує позицію, досвід, субʼєктивні висновки.

Типовий контент-мікс:

- Думки / commentary: 35%
- Новини з позицією: 25%
- Особистий досвід: 20%
- Освіта: 15%
- Продаж: 5%

Референси: Нештучний інтелект, Myk Melnyk, Dmytro Spodarets, Krakovetskyi.

Що копіювати:

- Авторська думка замість нейтрального дайджесту.
- Розбір помилок і сумнівів.

Чого уникати:

- Безособового “ми зібрали новини”.
- Надмірної обережності, через яку позиція не читається.

### F. Освіта / курси

Аудиторія: люди, які хочуть швидко навчитися або отримати career/business upgrade.

Типовий контент-мікс:

- Free value: 30%
- Course teaser: 30%
- Case / alumni: 15%
- Webinar/live: 15%
- Sales CTA: 10%

Референси: make ai., Projector, robot_dreams, Laba, Fwdays courses.

Що копіювати:

- Серії контенту з чітким learning path.
- Вебінар як growth loop.

Чого уникати:

- Відчуття, що канал існує тільки як воронка в курс.

### G. Агенції / B2B-сервіси

Аудиторія: decision makers у бізнесі, enterprise, product/service companies.

Типовий контент-мікс:

- Кейси: 30%
- White papers / explainers: 25%
- Thought leadership: 20%
- Service pages: 15%
- Hiring/employer brand: 10%

Референси: DataRoot Labs, SoftServe, ELEKS, SPD Technology, N-iX, Intellias.

Що копіювати:

- B2B language: risk, cost, integration, governance, production.
- Case-study structure.

Чого уникати:

- Enterprise abstraction без actionable takeaway.

### H. Зовнішні медіа

Аудиторія: змішана. Очікує новин, інтервʼю, бізнес-історій, стартапів, аналітики.

Типовий контент-мікс:

- Новини: 45%
- Інтервʼю/кейси: 20%
- Аналітика: 15%
- Sponsored/PR: 10%
- Подкасти/відео: 10%

Референси: DOU, AIN.UA, dev.ua, MC.today, Forbes Ukraine, Vector, SPEKA.

Що копіювати:

- Заголовки, що привʼязують AI до конкретного бізнесового наслідку.
- Інтервʼю з операторами і founders.

Чого уникати:

- Медіа-нейтральності без практичного висновку.

## 5. Deep dive: топ-15 Must-watch медіа

### 1. make ai.

- Аудиторія: 20.9K TG subscribers, 2026-08-08.
- Позиціонування: Claude Code / AI для бізнесу, вайбкодинг, AI для промисловості та енергетики; курси і впровадження.
- Контент-аудит: остання TG-сторінка показує 18 публічних постів. Мікс: освіта/tooling 35%, кейси/впровадження 25%, продаж/курс 20%, новини 15%, особисте 5%. Формати: текстові пости, добірки, CTA на продукти/навчання. Тон: практик/освітянин/agency.
- Сильні сторони: великий reach, ясний commercial engine, поєднання AI tooling і бізнесового впровадження.
- Слабкі сторони: ширший фокус, не привʼязаний спеціально до IT-services operating model.
- Урок для AI Club: брати практичність і регулярність, але звузити “AI для бізнесу” до IT-service operator pain.

### 2. ChatGPT | Штучний нейрон

- Аудиторія: 39K TG subscribers, 2026-08-08.
- Позиціонування: все про ChatGPT та світ нейромереж; бот і масове споживання AI.
- Контент-аудит: 20 постів у public preview. Мікс: новини 50%, інструменти/промпти 30%, entertainment 10%, CTA/бот 10%. Тон: масовий, швидкий, простий.
- Сильні сторони: найбільший reach у вибірці, низький поріг входу.
- Слабкі сторони: слабкий business ICP fit, низька глибина для IT-керівників.
- Урок для AI Club: не конкурувати в “новинах для всіх”; використовувати тільки як radar для тем, які вже стали масовими.

### 3. Штучка Інтелект

- Аудиторія: 11.4K TG subscribers, 2026-08-08.
- Позиціонування: практичні поради по AI, промпти, новини, туторіали; повʼязана з базами/агенціями.
- Контент-аудит: public preview обмежений 5 постами. Мікс: how-to 40%, добірки 25%, новини 20%, sales/agency 15%. Тон: практичний, масово-бізнесовий.
- Сильні сторони: зрозуміла користь, прості інструкції.
- Слабкі сторони: не доходить до керівного IT-services контексту.
- Урок для AI Club: формат “корисно за 2 хвилини” варто копіювати, але приклади мають бути про delivery/sales/ops.

### 4. KAGANOVSKY: все про AI

- Аудиторія: 8.7K TG subscribers, 2026-08-08.
- Позиціонування: авторський канал про нейромережі та реальні кейси в житті, бізнесі й контент-кріейтингу.
- Контент-аудит: 18 постів у public preview. Мікс: кейси/інструменти 35%, освіта 25%, новини 20%, creator content 10%, CTA 10%. Тон: creator educator.
- Сильні сторони: сильний personal brand, широкий business/mass appeal.
- Слабкі сторони: більше creator/SMB, ніж IT-services executive.
- Урок для AI Club: персональний тон і демонстрації працюють, але потрібна інша аудиторна рамка.

### 5. AI HOUSE

- Аудиторія: 6.71K TG subscribers, 2026-08-08; сайт описує AI HOUSE як найбільше AI-комʼюніті в Україні та згадує дослідження AI-талантів.
- Позиціонування: AI/ML-новини, інсайти практиків, івенти, добірки.
- Контент-аудит: 13 постів у public preview. Мікс: івенти/анонси 35%, community/news 25%, education 20%, research/partners 20%. Тон: community/professional.
- Сильні сторони: credibility, звʼязок з AI talent ecosystem.
- Слабкі сторони: не є daily operator guide для business ICP.
- Урок для AI Club: AI HOUSE варто мати як partner/reference, а не direct competitor.

### 6. DOU | AI

- Аудиторія: 3.58K TG subscribers, 2026-08-08.
- Позиціонування: статті, блоги, войсчати, професійні обговорення, події, вакансії з AI-спільноти DOU.
- Контент-аудит: 20 постів у public preview. Мікс: статті/форум 45%, події/войсчати 20%, вакансії/community 15%, новини 15%, реклама 5%. Тон: професійний IT-media.
- Сильні сторони: висока довіра tech-аудиторії, стабільний потік матеріалів.
- Слабкі сторони: широкий IT/AI, не бізнесово-сервісний фокус.
- Урок для AI Club: DOU дає теми для Radar; AI Club має додавати CEO/COO interpretation layer.

### 7. Нештучний інтелект

- Аудиторія: 3.31K TG subscribers, 2026-08-08.
- Позиціонування: новинки та думки про штучний інтелект; авторський канал Oleksandr Krakovetskyi.
- Контент-аудит: 20 постів у public preview. Мікс: авторський commentary 35%, новини 30%, education 20%, book/advisory 10%, community 5%. Тон: авторитетний практик.
- Сильні сторони: довіра до автора, помірний тон.
- Слабкі сторони: не завжди має вузьке позиціонування для IT-service exec.
- Урок для AI Club: потрібен сильний founder/operator voice, не тільки редакційна подача.

### 8. EV щоденник: AI в бізнесі

- Аудиторія: 1.49K TG subscribers, 2026-08-08.
- Позиціонування: AI у реальному бізнесі: від рутини до стратегії; досвід впровадження для власних клієнтів.
- Контент-аудит: 19 постів у public preview. Мікс: practical business notes 40%, automation/HR/sales 25%, personal operator notes 20%, CTA 10%, news 5%. Тон: CEO/operator.
- Сильні сторони: найближчий business ICP fit у Telegram-вибірці.
- Слабкі сторони: не спеціалізовано на IT outsourcing/service-company economics.
- Урок для AI Club: хороший reference для тону, але AI Club має піти глибше в IT services.

### 9. llms_ua

- Аудиторія: 824 TG subscribers, 2026-08-08.
- Позиціонування: штучний інтелект без хайпу; ChatGPT, Claude, Grok, Gemini та їхній вплив.
- Контент-аудит: 20 постів у public preview. Мікс: LLM news 40%, commentary 25%, tooling 20%, practical notes 15%. Тон: спокійний, anti-hype.
- Сильні сторони: якісний signal для LLM-рішень.
- Слабкі сторони: не business-first.
- Урок для AI Club: anti-hype tone варто копіювати; додати “що робити CEO”.

### 10. Claude Code Україна

- Аудиторія: 724 TG subscribers, 2026-08-08.
- Позиціонування: найбільше комʼюніті України по Claude Code.
- Контент-аудит: 19 постів у public preview. Мікс: tool workflows 45%, community 25%, experiments 20%, memes/voice 10%. Тон: dev community.
- Сильні сторони: early adopter energy, чітка niche ownership.
- Слабкі сторони: дуже вузький dev-tool focus.
- Урок для AI Club: окремі tool-native практики потрібно перекладати в manager playbooks.

### 11. Myk Melnyk

- Аудиторія: TG/LinkedIn metrics потребують ручної перевірки; присутній у DOU AI Telegram list як авторський блог.
- Позиціонування: business/AI/operator commentary.
- Контент-аудит: desk research + DOU inclusion. Типовий мікс: business commentary, AI adoption, personal operator notes.
- Сильні сторони: високий fit з керівною бізнес-аудиторією.
- Слабкі сторони: потрібна ручна перевірка reach і частоти.
- Урок для AI Club: один із найважливіших peer/possible-collab для бізнесового ракурсу.

### 12. DOU AI tag / forums

- Аудиторія: views/comments per article; DOU AI tag регулярно публікує AI materials.
- Позиціонування: IT media/forum with AI articles, blogs, interviews and community discussions.
- Контент-аудит: сторінка AI tag містить матеріали про agents, LLM attacks, AI tools, token economics, hiring, engineering future. Мікс: technical articles 45%, opinion/forums 30%, business/process 15%, news/events 10%.
- Сильні сторони: найкраще місце для tech-signal в UA.
- Слабкі сторони: не є curated business digest.
- Урок для AI Club: кожен тиждень брати 2-3 DOU теми й додавати управлінський висновок.

### 13. Fwdays AI / Data Science

- Аудиторія: tech leads, engineers, CTO, AI/Data specialists; сайт показує активні AI/Data Science курси й події.
- Позиціонування: конференції, воркшопи, курси для IT спеціалістів.
- Контент-аудит: подієвий контент: AI Agents Pro, RAG system, AI reliability, agentic engineering, AI Cursor workshop. Мікс: education/events 60%, expert talks 25%, course sales 15%.
- Сильні сторони: сильний event funnel і tech credibility.
- Слабкі сторони: episodic, не daily media.
- Урок для AI Club: партнерство/крос-промо, speaker sourcing, post-event summaries для business audience.

### 14. AI HOUSE website / research

- Аудиторія: AI/ML specialists; сайт вказує 6,100 AI/ML-спеціалістів у контексті research.
- Позиціонування: найбільше AI-комʼюніті в Україні, дослідження, івенти, партнерства.
- Контент-аудит: research/community/event heavy. Мікс: research 30%, events 35%, community 20%, partnerships 15%.
- Сильні сторони: інституційна довіра, доступ до talent ecosystem.
- Слабкі сторони: не operator-level для IT outsourcing.
- Урок для AI Club: використовувати як джерело talent/market signal.

### 15. Oleksandr Krakovetskyi / LinkedIn + TG

- Аудиторія: TG `Нештучний інтелект` 3.31K; LinkedIn metrics н/д без ручної перевірки.
- Позиціонування: AI practitioner / author / business-tech voice.
- Контент-аудит: авторський mix of AI news, reflections, books/education, advisory. Тон: досвідчений, стриманий.
- Сильні сторони: senior credibility.
- Слабкі сторони: широкий AI voice.
- Урок для AI Club: AI Club має бути не “безособовим каналом”, а впізнаваним operator POV.

## 6. Порівняння з AI Club

| Параметр | AI Club зараз | Медіанний peer | Топ-3 гравці |
| -- | -- | -- | -- |
| Підписники | ~38 TG, 2026-08-08 | Для перевірених TG peers: ~3.3K | ChatGPT 39K, make ai. 20.9K, Штучка 11.4K |
| Частота | 3-5/тиж бажано; поточну частоту треба окремо заміряти | 3-5/тиж для авторських, daily для news | Daily або 4-6/тиж |
| Контент-мікс | tooling-heavy / founder-curated | news + tools + education | mass news, practical AI, courses |
| ICP fit | business target: IT-service leadership | mixed; business peers часто generic | make ai. / EV / DOU частково |
| Диференціація | AI for IT outsourcing CEO | низька у peers | прямого аналога не видно |
| Ризик | малий reach | noise, generic AI | high reach, слабший niche fit |

## 7. Рекомендації для стратегії

### Позиціонування

`AI Club — практичний радар і playbook для керівників IT-сервісних компаній: як AI змінює delivery, sales, маржу, ризики й операційні процеси.`

### Контент-мікс Radar / Lab / Playbook

- **Radar — 40%:** короткі сигнали “що сталося” + “що це означає для IT-service CEO”.
- **Lab — 30%:** власні експерименти з AI tools у задачах сервісної компанії.
- **Playbook — 30%:** структурні гайди й чеклісти, які можна віддати керівнику функції.

### Рекомендована частота

- Telegram: 4-5 постів на тиждень.
- LinkedIn: 2 пости на тиждень, з сильнішим executive framing.
- 1 глибокий playbook кожні 2 тижні.
- 1 live / voice / small roundtable на місяць після перших 100-150 підписників.

### Канали дистрибуції

1. Telegram як core feed.
2. LinkedIn як B2B discovery та founder voice.
3. DOU/forum comments або guest posts для tech credibility.
4. Партнерські анонси з AI HOUSE/Fwdays/Data Science UA.
5. Репости у CEO/COO/PM/BA/Delivery комʼюніті, але тільки з executive content.

### 5 ідей диференціації

1. **AI Impact Memo:** щотижневий пост “3 AI-зміни, які зачіпають IT-service company this week”.
2. **Delivery AI Lab:** експерименти з estimation, test plans, code review, support triage, project status reports.
3. **Sales / Pre-sales Playbook:** як AI змінює discovery, proposal, RFP, demo, objection handling.
4. **Margin Watch:** token cost, tool subscriptions, productivity claims, hidden costs, IP/security risks.
5. **Board-style brief:** “що CEO має запитати у CTO/Delivery/HR цього тижня”.

### 5 медіа для колаборації / крос-промо

| Медіа | Чому |
| -- | -- |
| DOU \| AI | Tech credibility, сильний потік тем |
| AI HOUSE | AI-community trust, research/events |
| Fwdays | CTO/Tech Lead аудиторія, AI/agentic engineering події |
| EV щоденник: AI в бізнесі | Найближчий business AI tone |
| make ai. | Великий reach, бізнесове AI впровадження |

## 8. Додатки

### Сирі дані / CSV

```csv
#,name,type,url,audience,primary_icp,cluster,frequency,monetization,icp_overlap,priority
1,AI Club,TG,https://t.me/xainaiclub,"38 TG, 2026-08-08",business,A,"3-5/w planned",owned,5,Must watch
2,make ai.,TG,https://t.me/makeaiukraine,"20.9K TG, 2026-08-08",business,A/F/G,4-6/w,"courses; implementation",4,Must watch
3,ChatGPT | Штучний нейрон,TG,https://t.me/chatgptua,"39K TG, 2026-08-08",mass,B,daily,"ads; bot",2,Must watch
4,Штучка Інтелект,TG,https://t.me/shtuchka_intelekt,"11.4K TG, 2026-08-08",mass/business,B/F/G,2-4/w,"bases; agencies",3,Must watch
5,KAGANOVSKY: все про AI,TG,https://t.me/kgnvsk_ai,"8.7K TG, 2026-08-08",mass/business,E/F,4-6/w,"courses; YouTube",3,Must watch
6,AI HOUSE,TG,https://t.me/AIHOUSE,"6.71K TG, 2026-08-08",tech,C,2-4/w,"events; partners",3,Must watch
7,DOU | AI,TG,https://t.me/ai_dou,"3.58K TG, 2026-08-08",tech/mixed,C,daily,"ads; DOU ecosystem",4,Must watch
8,Нештучний інтелект,TG,https://t.me/neshtuchnyi,"3.31K TG, 2026-08-08",mixed,E,4-6/w,"books; collaboration",3,Must watch
9,EV щоденник: AI в бізнесі,TG,https://t.me/businessbyev,"1.49K TG, 2026-08-08",business,A/E,3-5/w,"consulting",5,Must watch
10,llms_ua,TG,https://t.me/llms_ua,"824 TG, 2026-08-08",tech/mixed,D,3-5/w,unknown,3,Must watch
11,Claude Code Україна,TG,https://t.me/claudecodeua,"724 TG, 2026-08-08",tech,D,3-5/w,community,3,Must watch
```

Повна таблиця: див. section 3.

### Список джерел

- Linear XAI-12 issue description.
- DOU forum topic: `https://dou.ua/forums/topic/52297/`.
- DOU AI tag: `https://dou.ua/lenta/tags/AI/`.
- Telegram public previews: `https://t.me/s/xainaiclub`, `https://t.me/s/makeaiukraine`, `https://t.me/s/ai_dou`, `https://t.me/s/llms_ua`, `https://t.me/s/claudecodeua`, `https://t.me/s/chatgptua`, `https://t.me/s/shtuchka_intelekt`, `https://t.me/s/neshtuchnyi`, `https://t.me/s/kgnvsk_ai`, `https://t.me/s/businessbyev`, `https://t.me/s/AIHOUSE`.
- AI HOUSE: `https://aihouse.org.ua/`.
- Fwdays AI/Data Science events: `https://fwdays.com/en/events?tag=data-science`.
- AIN.UA: `https://ain.ua/`.
- dev.ua: `https://dev.ua/`.
- MC.today AI tag: `https://mc.today/uk/tag/shtuchnij-intelekt/`.
- Public websites of media, schools, agencies and communities listed in section 3.

### Changelog

- 2026-08-08: initial deep research document created. Known gap: repo access unavailable from current environment, so XAI-6 source file and README could not be read/updated directly in GitHub; this document should be copied to `docs/04-ua-ai-media-landscape-deep-research.md` in the target repo and README should link to it.

