# 07 — Verification of addresses and new org contacts (31.10.2026)

Research only. **Nothing was sent, no Gmail drafts created, no web forms filled, nobody contacted.**
Checked 31.10.2026, ~14:10–14:40 Berlin (CET, UTC+1), via curl / WebFetch of the official pages listed.

## 1. Top-8 organisations from `04-*` (NLnet, Hub71 excluded)

Top 8 = the 7 ⭐ entries (#1–4, #6–8) + #9 Wellcome.

| # | Organisation | Address | Status | Source (official) |
|---|---|---|---|---|
| 1 | Digital Public Goods Alliance | hello@digitalpublicgoods.net | FOUND (mailto on homepage) | https://www.digitalpublicgoods.net |
| 2 | ITU – AI for Good | ai@itu.int | FOUND (on aiforgood.itu.int article page) | https://aiforgood.itu.int/tell-the-world-about-your-ai-for-good-project-on-itus-ai-repository/ |
| 3 | Fondation Botnar | info@fondationbotnar.org | FOUND | https://www.fondationbotnar.org/contact/ |
| 4 | Patrick J. McGovern Foundation | communications@mcgovern.org | FOUND | https://www.mcgovern.org/contact/ |
| 6 | Wadhwani AI | partnerships@wadhwaniai.org (general: contact@wadhwaniai.org) | FOUND | https://www.wadhwaniai.org/contact-us/ |
| 7 | Community Jameel | — | NOT FOUND (contact page renders by script, no address in HTML) | https://www.communityjameel.org/contact |
| 8 | Nesta | information@nesta.org.uk | FOUND | https://www.nesta.org.uk/contact-us/ |
| 9 | Wellcome Trust | message@wellcome.org | FOUND, but official page says: use the contact form first, email only if the form fails | https://wellcome.org/about-us/problems-submitting-our-contact-form |

## 2. Addresses marked `snippet` / `UNVERIFIED` (files 02, 05)

File 06 contains no `snippet`/`UNVERIFIED` marks in the .md.

| File | Entity | Address | Result | Source |
|---|---|---|---|---|
| 02 | Le Soir (Cartes blanches) | forum@lesoir.be | ✅ VERIFIED (WebFetch; curl 403) | https://www.lesoir.be/art/envoyez-un-courrier-ou-une-carte-blanche-au-service-for_t-20060329-0050NH.html |
| 02 | Anti-Malware.ru | author@anti-malware.ru | ✅ address confirmed ("author (at) anti-malware.ru"), but ⛔ **Russian outlet (ООО «АМ Медиа», Roskomnadzor registration) → excluded by rule (Russia). Do not send.** | https://www.anti-malware.ru/send_article |
| 05 | Finland, Ministry of Education and Culture | kirjaamo.okm@gov.fi | ❔ NOT VERIFIED (403 for curl and WebFetch) | https://okm.fi/yhteystiedot |
| 05 | Lithuania, Ministry of Education, Science and Sport | smmin@smsm.lt | ✅ VERIFIED (reception desk) | https://smsm.lrv.lt/lt/struktura-ir-kontaktine-informacija/kontaktai-1/ |
| 05 | Latvia, Ministry of Education and Science | pasts@izm.gov.lv | ✅ VERIFIED ("pasts [at] izm.gov.lv") | https://www.izm.gov.lv/en/iestades-kontakti-en |
| 05 | Norway, Ministry of Education and Research | postmottak@kd.dep.no | ✅ VERIFIED | https://www.regjeringen.no/no/dep/kd/kontakt/id594/ |
| 05 | Sweden, Ministry of Education and Research | u.registrator@regeringskansliet.se | ⚠️ PATTERN ONLY: page gives rule `departementsnamnet.registrator@regeringskansliet.se`; exact address not printed | https://www.regeringen.se/kontaktuppgifter/e-post-till-regeringen-och-regeringskansliet/ |
| 05 | Italy, MUR (URP) | urp@mur.gov.it | ✅ VERIFIED | https://www.mur.gov.it/it/urp |
| 05 | New Zealand, MBIE | info@mbie.govt.nz | ❔ NOT VERIFIED (Incapsula block) | https://www.mbie.govt.nz/about/contact-us |
| 05 | Australia, Dept. of Industry, Science and Resources | enquiries@industry.gov.au | ❔ NOT VERIFIED (timeout / 500) | https://www.industry.gov.au/contact-us |
| 05 | Kenya, MICDE | info@information.go.ke | ✅ VERIFIED (shown on ict.go.ke) | https://ict.go.ke/contact-us |
| 05 | UAE, MoIAT | info@moiat.gov.ae | ❌ NOT FOUND on page (form only) | https://www.moiat.gov.ae/en/contact-us/contact-us-form |
| 05 | Saudi Arabia, MCIT | info@mcit.gov.sa | ❔ NOT VERIFIED (403 / timeout) | https://my.gov.sa/en/agencies/17597 |
| 05 | Jordan, MoDEE | modee@modee.gov.jo | ✅ VERIFIED | https://www.modee.gov.jo/EN/Pages/Contact_Us |
| 05 | India, MeitY | moeit@gov.in | ✅ VERIFIED ("moeit[at]gov[dot]in", minister's office) | https://www.meity.gov.in/connect/directory |
| 05 | Indonesia, Komdigi | humas@mail.kominfo.go.id | ❔ NOT VERIFIED (page renders by script, no address) | https://www.komdigi.go.id/lainnya/hubungi-kami |
| 05 | France, Higher Education & Research | form | FORM confirmed; recipient shown in form: sve.recherche@recherche.gouv.fr (form only, not filled) | https://www.enseignementsup-recherche.gouv.fr/fr/categorie-sve/ecrire-au-ministre |
| 05 | Spain, Science ministry | form | FORM confirmed (not filled) | https://www.ciencia.gob.es/site-web/Formularios/ConsultasGenerales.html |
| 05 | Wellcome | message@wellcome.org | ✅ VERIFIED (form first) | see above |

Totals (ministries, 16): ✅ 8 verified · ⚠️ 1 pattern-only · ❌ 1 not found (UAE) · ❔ 4 blocked · 2 form-only.

## 3. Sent-folder dedupe (velantrim@gmail.com)

- Sent folder read: 116 messages, 111 unique recipient addresses.
- Round-6 address set (02, 03, 05, 06 + new 04 addresses above): 239 unique addresses.
- **Overlap: 10 addresses — all are the bounced round-4 addresses** that appear in 02 only in the "replacements" table. **No new duplicates** among round-6 targets. Domain-level overlap: only the same bounced outlets (+ gmail.com).

## 4. Inbox check (since last check ~12:37 Berlin)

- 📩 **New reply:** Moldova Matters (david@moldovamatters.md), 13:09 Berlin — polite **decline** ("going to pass on this one"). Not answered.
- 🔁 New bounces after 12:37: **none**. All 12 known bounces confirmed in inbox.
- Note: the iProfesional DSN names `catchall@iprofesional.com` as blocked (the sent address `contacto@` is forwarded there), so iProfesional effectively **did** bounce; file 02 says "contacto@ sent without bounce" — this is inconsistent with HISTORY.md and the DSN.

## 5. Replacements for bounced round-4 addresses (re-opened today)

| Outlet | Replacement | Re-check |
|---|---|---|
| The Gulf Magazine | hello@thegulfmagazine.com | ✅ on https://thegulfmagazine.com/contact-us/ |
| DeshiAI | editorial@deshiai.in (+ contact@) | ✅ on https://deshiai.in/masthead-and-editorial-team/ (same server rejected contributors@ → risk) |
| Nova Gazeta | novagazetadirector@gmail.com | ✅ on https://novagazeta.co.ao/contactos |
| iProfesional | info@iprofesional.com | ✅ on https://www.iprofesional.com/contacto (contacto@ forwards to blocked catchall@) |
| Technologue | crm@kivaa.in | ✅ on site footer (parent company, non-editorial; /contact now 404) |
| Tanzania Business Journal | newsroom@tanzaniabusinessjournal.com | ✅ on homepage (same domain → likely bounce again) |
| AI in Asia, Africa Digital News, Bahrain Economy, Max Portal | — | no replacement (unchanged) |

Resending requires a new explicit approval from Ruslan.

## 6. Emails (EN) for 04 organisations — ✅ SENT 31.10.2026 17:27–17:28 Berlin by Ruslan (Send pressed himself; signature "Velan, Hamburg"); see SENT_LOG.md R6-1…R6-7

Common body (greeting + hook vary per org, see below):

```text
I'm Velan (Ruslan Gagiev), a non-engineer founder based in Hamburg. I directed AI coding assistants to build Titan, an open-source (MIT) early research prototype of memory for AI agents: every memory write goes into an append-only SQLite log linked by SHA-256 hashes, checkable with verify_chain(). Code: github.com/velantrian/Velantrim-ExoCortex-Titan (647 commits, 4,769 tests).

To be clear about the limits: it has no users, no external audit and no clinical validation, and chain signatures are not implemented yet. It does not solve anything today. It is not fantasy but research: a question of whether AI agents' memory can be made traceable for people who depend on it.

{ASK}

Transparency: this text was prepared with AI assistance and reviewed by me (Velan). Anything published under my name I write myself.

Velan (Ruslan Gagiev)
velantrim@gmail.com
```

| To | Subject | Greeting + hook | {ASK} |
|---|---|---|---|
| hello@digitalpublicgoods.net | Question: is an early open-source AI-memory prototype a fit for the DPG registry? | Dear DPGA team, the DPG Standard is the clearest public benchmark for open-source tools aimed at the SDGs, so I'd value your view. | Is a project at this early stage eligible to apply to the registry, or what should it reach first? |
| ai@itu.int | Research prototype: traceable memory for AI agents | Dear AI for Good team, your platform connects AI work with SDG use cases such as health. | Would it be appropriate to submit it to the AI for Good repository or Neural Network, and who would be the right contact? |
| info@fondationbotnar.org | Research question: traceable AI-agent memory and young people's wellbeing | Dear Fondation Botnar team, your work on AI and digital tools for young people's health and wellbeing is why I'm writing. | Is there a person or programme for early research dialogue, or should I only follow your open calls? |
| communications@mcgovern.org | Early research: traceable memory for AI agents in nonprofits | Dear Patrick J. McGovern Foundation team, your focus on AI and data for good and on nonprofit capacity is close to this question. | Could you point me to the right person for an early research conversation? |
| partnerships@wadhwaniai.org | Research prototype: auditable memory for AI agents | Dear Wadhwani AI team, your AI for public health and agriculture in the Global South depends on systems people can trust. | Would a short exchange with your team on whether this is useful for field AI be possible? |
| information@nesta.org.uk | Research question: traceable AI-agent memory for public-good AI | Dear Nesta team, your missions on early years and healthy life, and your work on AI for public good, motivate this note. | Is there a team at Nesta working on AI accountability that would be open to a short conversation? |
| message@wellcome.org (⚠️ official form first) | Research question: traceable memory for AI agents in health | Dear Wellcome team, your work on data science in health is the reason for this note. | Which funding scheme or team, if any, would fit such an early-stage prototype? |

Community Jameel: no draft (no official address found).
