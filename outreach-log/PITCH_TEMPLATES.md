# ✉️ Шаблоны питчей

## 🧩 Структура письма (как в раунде 4)
1. 👋 **Приветствие** редакции (по имени, если оно известно).
2. 🪝 **Крючок**: почему именно это издание. Ссылаемся на их рубрику или страницу для авторов.
3. 🙋 **Кто я**: «Велан (Руслан Гагиев), основатель без инженерного образования, Гамбург; руководил ИИ-ассистентами, которые писали код Titan».
4. 📂 **Публичные факты** с цифрами и ссылкой на репозиторий.
5. ⚖️ **Ограничения**, прямо: пользователей нет, аудита нет, подписей нет.
6. 💡 **Что предлагаю**: тема и объём. Углы: **A** — сам Titan; **B** — основатель без инженерного образования, который строит с ИИ-ассистентами; **C** — прослеживаемость и EU AI Act.
7. ❓ **Вопрос** редакции (подходит ли формат и объём).
8. 🏷️ **Строка прозрачности** (обязательна).
9. ✍️ **Подпись**: `Velan (Ruslan Gagiev)` / `velantrim@gmail.com`. Для изданий, где нужно настоящее имя: «Руслан Гагиев».

Длина 130–200 слов.

## 🧱 Факты о Titan (перепроверять перед каждым раундом)
- github.com/velantrian/Velantrim-ExoCortex-Titan (MIT). ⚠️ Не `velantrim/`: такой адрес отдаёт 404.
- 647 коммитов, 4 769 тестов, в 98 коммитах соавторами указаны ИИ.
- SHA-256 цепочка по записям памяти, SQLite «только добавление», `verify_chain()`.
- Нет пользователей, нет внешнего аудита, нет подписей цепочки. Офлайн-верификатор и квитанции (отправка, хранение, удаление) только запланированы.

## 🏷️ Строка прозрачности (обязательна)
- **EN:** Transparency: this email was drafted with AI assistance and reviewed by me. Anything published under my name I write myself.
- **RU:** Прозрачность: это письмо подготовлено с помощью ИИ и проверено мной. Всё, что публикуется под моим именем, я пишу сам.
- **PT:** Transparência: este e-mail foi redigido com ajuda de IA e revisado por mim. Tudo o que for publicado com meu nome, eu mesmo escrevo.

Все тексты карточек раунда 4 (EN, RU, PT, ES, FR) лежат в [`sources/cards_r4.json`](sources/cards_r4.json). Базовый русский текст для Северного Кавказа: [`sources/PITCH_DRAFTS_ROUND5-24.md`](sources/PITCH_DRAFTS_ROUND5-24.md).

## 📄 Реальные примеры (отправлены 31.10.2026)

### 🇬🇧 EN: TechEconomy (Нигерия) (`info@techeconomy.ng`), раунд 4, карточка №62

**Тема:** Guest writer pitch: what an AI agent's memory log can prove

```text
Dear TechEconomy editors,

Your site runs a Guest Writer section with pieces on AI; I'd like to contribute one.

I'm Velan (Ruslan Gagiev), a non-engineer founder based in Hamburg. I directed AI coding assistants to build Titan, an open-source (MIT) prototype of memory for AI agents. Every memory write goes into an append-only audit log linked by SHA-256 hashes, so later edits become visible.

The record is public: github.com/velantrian/Velantrim-ExoCortex-Titan — 647 commits, 4,769 tests, 98 commits crediting AI co-authors. Most of the code was written by AI assistants under my direction. The limits, plainly: Titan has no users, no external audit, and the hash chain is not signed yet.

I'd like to offer a short piece on what a tamper-evident memory log can and cannot prove about an AI agent, written from the builder's side, limits included.

Would a 900-word guest article fit?

Transparency: this email was drafted with AI assistance and reviewed by me. Anything published under my name I write myself.

Velan (Ruslan Gagiev)
velantrim@gmail.com
```

### 🇷🇺 RU: TechInsider (блоги экспертов) (Россия) (`a.bakanova@imedia.ru`), раунд 4, карточка №10

**Тема:** Предложение экспертной колонки: память ИИ-агентов с журналом аудита

```text
Здравствуйте!

На странице блогов вы предлагаете экспертам представиться и предложить темы — делаю это.

Меня зовут Велан (Руслан Гагиев), я основатель без инженерного образования, живу в Гамбурге. Я руководил ИИ-ассистентами для программирования и с их помощью собрал Titan — open-source (MIT) прототип памяти для ИИ-агентов. Каждая запись в память попадает в журнал аудита, связанный хешами SHA-256, поэтому поздние правки становятся заметны.

Всё открыто: github.com/velantrian/Velantrim-ExoCortex-Titan — 647 коммитов, 4 769 тестов, в 98 коммитах соавторами указаны ИИ. Большую часть кода написали ИИ-ассистенты под моим руководством. Ограничения честно: пользователей нет, внешнего аудита нет, подписей цепочки пока нет.

Предлагаю короткий материал о том, что журнал памяти с защитой от подмены может и чего не может доказать про ИИ-агента — с позиции автора, с ограничениями.

Могу предложить 2–3 темы на выбор и прислать план первой колонки.

Прозрачность: это письмо подготовлено с помощью ИИ и проверено мной. Всё, что публикуется под моим именем, я пишу сам.

Велан (Руслан Гагиев)
velantrim@gmail.com
```

### 🇧🇷 PT: ABRACD (Seja um colunista) (Бразилия) (`abracd@abracd.org`), раунд 4, карточка №33

**Тема:** Proposta de coluna: memória auditável para agentes de IA

```text
Olá, equipe editorial da ABRACD,

Vi a chamada para colunistas (800–1.800 palavras, experiência real, ética e governança de IA) e envio um resumo.

Sou Velan (Ruslan Gagiev), fundador sem formação em engenharia, baseado em Hamburgo. Dirigi assistentes de IA de programação para construir o Titan, um protótipo open source (MIT) de memória para agentes de IA. Cada gravação na memória entra num registro de auditoria encadeado por hashes SHA-256, o que torna alterações posteriores visíveis.

Tudo é público: github.com/velantrian/Velantrim-ExoCortex-Titan — 647 commits, 4.769 testes, 98 commits creditam coautores de IA. A maior parte do código foi escrita por assistentes de IA sob minha direção. Os limites, com franqueza: não há usuários, não há auditoria externa e a cadeia ainda não tem assinaturas.

Proponho um texto curto sobre o que um registro de memória à prova de adulteração pode e não pode provar sobre um agente de IA, com os limites incluídos.

Posso enviar um texto de cerca de 1.200 palavras. Faz sentido para vocês?

Transparência: este e-mail foi redigido com ajuda de IA e revisado por mim. Tudo o que for publicado com meu nome, eu mesmo escrevo.

Velan (Ruslan Gagiev)
velantrim@gmail.com
```
