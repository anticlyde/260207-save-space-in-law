# 260207-save-space-in-law
<a href="">goto main-home</>

Версия записана через дату. полноценная версия будет помечена
Эксперементальный подход:

промпт через чатжпт, 
промпт для кодекс:

1.
you are codex. write in russian. be blunt and practical.

task: produce a realistic plan + deliverables for a “turnkey” website with basic SEO for “Адвокатская контора №2 (подразделение МГКА)” under a hard budget cap of 300 (all-in, including SEO). budget will not increase. do not upsell. if it’s not viable, say so and propose the closest workable alternative within the same cap.

context:
- current site: https://www.ak2mgka.ru/ (old, weak, not SEO-friendly)
- about 30 lawyers; each works independently; shared office/billing costs; many older, low involvement
- goal: client acquisition from search (not just a визитка)
- geography: Moscow + can work across Russia
- practice areas include: уголовное, семейное, арбитраж, банкротство физ/юр лиц, трудовые споры, военное право, договорное право + broader “юридические услуги” (except very narrow niches)
- content: assume no one will write articles; unified copywriting preferred; avoid collecting long texts from each lawyer
- slight visual alignment with https://mgka1866.ru/ is ok, but no copying
- legal/organizational specifics: адвокатское образование, ордера, адвокатские запросы (номер), при обыске присутствуют представители адвокатского образования; registration constraints (Минюст) — mention correctly, don’t invent law

output requirements (structure exactly):
1) feasibility verdict: “viable / not viable” with 5–7 bullet reasons tied to budget and niche realities
2) mvp scope that fits 300: list pages + templates + cms choice; max 2 options (e.g., wordpress + theme vs tilda/webflow), explain tradeoffs
3) information architecture + url map: show a compact tree + example slugs
4) seo within budget: include ONLY what can realistically be done: technical baseline, semantics, on-page for key pages, local SEO. include what is excluded (e.g., content marketing, linkbuilding, dozens of articles)
5) copywriting plan under constraints: how to write “about lawyers” without long bios; propose a short standardized questionnaire + page template fields
6) timeline (weeks) + who does what: client vs contractor; include dependencies
7) acceptance criteria: measurable checks (core web vitals targets, indexing, sitemap/robots, analytics, forms, 404, redirects from old urls)
8) risks + mitigations: 8–12 bullets, including “no content”, “YMYL/legal trust”, “competition”, “slow feedback”, “budget cap”
9) exact list of questions to ask client (max 12) that unblock work; no fluff

constraints:
- no marketing tone, no “it depends” without a concrete decision path
- don’t promise rankings; talk in probabilities and controllables
- assume minimal integrations: call/whatsapp/telegram buttons, simple lead form, map
- propose a solution that is maintainable by non-technical staff

  </!--->
  2.
  you are codex. output in russian. be practical. no marketing language.

task:
generate a complete working MVP website (structure + content + code) for “Адвокатская контора №2 (подразделение МГКА)” optimized for low-budget deployment and basic SEO.

IMPORTANT:
- do NOT create a plan or explanation.
- immediately output ready-to-use project structure and code.
- assume hard budget cap = 300 (design + dev + SEO).
- solution must be simple, cheap, maintainable, and realistic.
- avoid complex frameworks requiring devops.

context:

current website: https://www.ak2mgka.ru/
reference (visual context only): https://mgka1866.ru/

organization specifics:

- ~30 lawyers, each independent
- shared office expenses
- many older users → admin must be extremely simple
- goal = client acquisition from search, not just a business card

practice areas:

- уголовное право
- семейное право
- арбитражные споры
- банкротство физ/юр лиц
- трудовые споры
- военное право
- договорное право
- общие юридические услуги

content constraints:

- assume no long texts from lawyers
- generate unified professional copywriting
- lawyer pages must be template-based

legal context:

- адвокатское образование
- ордера
- адвокатские запросы
- регистрация в Минюсте
- avoid fake legal claims

technical requirements:

- static or wordpress-based solution preferred
- SEO-ready markup
- fast loading
- mobile-first
- no heavy animations
- clean semantic HTML

output format:

1) project folder structure
2) full HTML for pages:

- index.html (главная)
- lawyers.html (список адвокатов)
- lawyer-template.html (карточка адвоката)
- services.html
- service-template.html
- about.html
- contacts.html

3) reusable components:

- header
- footer
- navigation
- service card
- lawyer card

4) CSS (single file style.css)

- minimal modern legal aesthetic
- neutral conservative style

5) SEO:

- title/meta for each page
- schema.org structured data for legal service
- semantic headings
- internal linking

6) placeholder content:

- generate realistic russian legal copywriting
- create 5 example lawyer profiles using templates

7) accessibility:

- alt texts
- aria labels
- readable typography

rules:

- no explanations.
- no comments about budget or feasibility.
- output ONLY ready-to-use code blocks and file structure.


deliver as plain text. no tables. no links besides the two given websites.
