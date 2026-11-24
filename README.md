# Людмила Маклакова — ИИ-ассистенты для образования и бизнеса

Методист онлайн-образования × промпт-инженер. Проектирую RAG-ассистентов, Telegram-ботов и автоматизации полного цикла: сценарии диалогов и промпт-архитектура → код → Docker-деплой → документация и поддержка.

**Заказать проект:** [Telegram @BeastMaster77](https://t.me/BeastMaster77) · [Портфолио на FL.ru](https://www.fl.ru/users/mkluckoff/portfolio/) · [Сайт](https://mkluckoff.ru)

---

## Витрина проектов

Живые демо и исходный код. Каждая витрина — рабочий продукт, а не учебный пример.

| Проект | Задача бизнеса | Стек | Статус |
|---|---|---|---|
| **[edu-assistant](https://github.com/BeastHealer/edu-assistant)** | ИИ-куратор онлайн-курса: поддержка студентов 24/7 без нагрузки на методистов | GigaChat, Chroma, TF-IDF, LangChain, Streamlit, Docker | ✅ Демо |
| **[faq-assistant](https://github.com/BeastHealer/faq-assistant)** | FAQ-виджет для сайта: ответы строго по материалам клиента, без галлюцинаций | FAISS, GigaChat, FastAPI, Tilda-интеграция | ✅ Демо |
| **[ai-reviews-worker](https://github.com/BeastHealer/ai-reviews-worker)** | Автообработка отзывов: классификация, автоответы, модерация, уведомления | GigaChat, YandexGPT, n8n, Telegram, e-mail | Рабочий |
| **[cold-call-audit](https://github.com/BeastHealer/cold-call-audit)** | Аудит холодных звонков B2B: транскрипция + оценка по чек-листу для РОПа | Yandex SpeechKit, GigaChat, YandexGPT, FastAPI | Рабочий |
| **[pro-women-assistant](https://github.com/BeastHealer/pro-women-assistant)** | Контент-процессы сообщества: дайджесты, рассылки, автопостинг | n8n, Senler, Yonote, VK, Telegram | Рабочий |
| **[smm-analyst](https://github.com/BeastHealer/smm-analyst)** | Аналитика статистики соцсетей: отчёты, графики, тренды | GigaChat, Pandas, Streamlit | Рабочий |
| **[tg-vk-reposter](https://github.com/BeastHealer/tg-vk-reposter)** | Автопостинг из закрытого Telegram-чата в группу ВКонтакте | Telegram Bot API, VK API | Рабочий |
| **[prompt-library](https://github.com/BeastHealer/prompt-library)** | Библиотека проверенных системных промптов с eval-тестами | JSON Schema, pytest | Активно |

---

## Как я работаю с клиентами

1. **Бриф 20 минут.** Понимаю задачу бизнеса, целевую аудиторию, ограничения по данным.
2. **ТЗ и смета за 1–2 дня.** Чёткий список функций, сроки, стоимость по этапам.
3. **Рабочее демо за 2–3 дня.** Прототип на ваших реальных материалах, до оплаты.
4. **Сдача с документацией.** Инструкция для команды, видео запуска, передача ключей API.
5. **Поддержка после запуска.** По договорённости — сопровождение, обновления, новые сценарии.

**Оплата:** 50% предоплата, 50% после приёмки. Возможны Безопасная сделка (FL.ru) и договор. Ключи API оформляются на ваши аккаунты — решение остаётся у вас.

---

## Результаты в проектах

- **ИИ-куратор курса** (`edu-assistant`): время ответа студенту на типовые вопросы сокращено с нескольких часов ожидания куратора до секунд; нагрузка на кураторов снижена по типовым вопросам на ~60–80%.
- **FAQ-виджет для сайта** (`faq-assistant`): на пилотном контуре среднее время ответа посетителю снизилось примерно на 25%. Все ответы — строго по базе клиента, с указанием источника.
- **Аудит звонков** (`cold-call-audit`): автоматическая оценка звонков по чек-листу РОПа заменяет ручной разбор; обработка записи 10 минут занимает минуты.
- **Обработка отзывов** (`ai-reviews-worker`): автоклассификация, автоответы с модерацией, уведомления команде — ручная работа сокращена в разы.

---

## Технологический стек

**LLM и RAG:** GigaChat, YandexGPT, OpenAI API, LangChain, ChromaDB, FAISS, Qdrant, TF-IDF
**Backend:** Python, FastAPI, Streamlit, Gradio, aiogram (Telegram Bot API), VK API
**Оркестрация:** n8n (self-hosted), Make
**Данные:** Pandas, Polars, PostgreSQL (pgvector), SQLite, MongoDB, Redis
**Инфраструктура:** Docker, Docker Compose, nginx, Let's Encrypt
**Интеграции:** 1С (Бит.Айболит, УНФ), CRM, Google Sheets, Tilda

---

## Образование и сертификаты

- **Промпт-инжиниринг** — Университет Зерокодер (2026). LLM, RAG, агенты, мультиагентные системы, локальное развёртывание моделей.
- **Методист онлайн-образования** — Eduson Academy (2025). ADDIE, андрагогика, таксономия Блума, проектирование образовательных программ.
- **Авторское право и коммерциализация интеллектуальной собственности** — сертификаты Роспатента и Московского инновационного кластера.
- **Психология** — базовое высшее (помогает проектировать сценарии общения и инклюзивные интерфейсы).

---

## Почему со мной надёжно

- **Системный подход.** Проектирую не «чат-бота», а экосистему: сценарии → код → обработка сбоев → документация → поддержка.
- **Двойная экспертиза.** Методист + промпт-инженер — редкое сочетание на рынке. Я понимаю и как обучать пользователей, и как технически реализовать это надёжно.
- **Честная работа с ИИ.** Не обещаю «100% без галлюцинаций». Проектирую гардрейлы: ассистент отвечает только по вашим материалам, указывает источник, не выдумывает и не выходит за рамки роли.
- **Передача права собственности.** Все ключи API, промпты, код и данные остаются у вас. Решение работает и после окончания проекта.

---

## Связаться

- **Telegram:** [@BeastMaster77](https://t.me/BeastMaster77) — самый быстрый способ
- **Email:** через сообщения на FL.ru или GitHub
- **Сайт:** [mkluckoff.ru](https://mkluckoff.ru)

-------------------------------------------------------------------------------------------------------------------------------------

## Architect of Inclusive EdTech Solutions and AI Automation

I am an automation specialist, experienced prompt engineer, and vibe coding practitioner. My unique expertise lies in synthesizing deep knowledge of psychology, neuroinclusive andragogy, and modern AI development.

My core philosophy: **Educational and work environments should adapt to the individual, not the other way around.**

### The Business Value I Bring to Your Project:

**For Helping Professionals:**
I reclaim up to 40% of your time from routine tasks. I build personalized AI assistants that handle initial query processing, content structuring, and scheduling, while strictly preserving the empathy and ethical standards of your practice.

**For EdTech Startup Founders:**
I enable rapid prototyping and reliable product scaling. I design system architectures that balance quality and cost, actively minimizing AI hallucinations and ensuring stable performance under load.

**For NGO Leaders in Neurodiversity Support:**
I develop digital tools that respect spectral perception differences (including ASD and ADHD). I design interaction scenarios and interfaces that make technology genuinely accessible and comfortable for diverse users.

### Measurable Results in My Projects:
- **Cost Optimization**: I design architectures with intelligent LLM routing. Simple tasks are handled by local models (Ollama/vLLM) at zero token cost, while complex logical chains are routed to GigaChat or YandexGPT. This reduces external API costs by up to 60% without compromising quality.
- **Deep Automation**: I seamlessly connect Telegram bots (aiogram) and CRM systems via self-hosted n8n. The bot independently qualifies leads, gathers requirements, and creates deals, saving team members up to 2 hours of work daily.
- **Security and RAG**: I deploy corporate knowledge bases using Qdrant and GigaChat. Employees receive accurate, natural-language answers from internal PDF/Word documents, ensuring that confidential data never leaves the company's secure perimeter.
- **High Performance**: I build backends using FastAPI with extensive asyncio implementation. This enables non-blocking LLM calls, accelerating query processing in systems by 3x compared to synchronous alternatives.

### Technology Stack (Focused on Reliability and Security):
- **AI & LLMs**: GigaChat, YandexGPT, OpenAI API, LangChain. Local deployment of ruGPT/Llama 3 via Ollama/vLLM for high-data-security tasks.
- **Backend & Python**: FastAPI (high-load APIs), Pydantic (strict validation of LLM JSON outputs), Asyncio/httpx, Pandas/Polars for data analytics.
- **Orchestration**: n8n (primarily self-hosted for data control and cost efficiency), Make, Zapier for rapid SaaS integrations.
- **Data & RAG**: Qdrant, pgvector (PostgreSQL) for resource efficiency, ChromaDB. Redis/MongoDB for caching and session management.
- **Interfaces**: Telegram Bot API (aiogram, complex FSM), VKontakte API, Streamlit/Gradio for rapid stakeholder demo dashboards.

### Why Partnering With Me is a Reliable Choice:
1. **Systemic Approach**: I do not just configure isolated tools; I architect resilient ecosystems with well-thought-out fallback mechanisms for potential failures.
2. **Validated Expertise**: I hold certificates from Rospatent and the Moscow Innovation Cluster on intellectual property commercialization, backed by formal education in instructional design, psychology, and prompt engineering.
3. **Maturity and Empathy**: My intentional career transition into AI automation after 50 allows me to find non-obvious, interdisciplinary solutions and build products that genuinely solve human problems.

### Open to Collaboration:
If you are looking for a responsible technical partner to build AI agents, automate educational processes, or develop inclusive digital products, I would be glad to discuss the specifics of your task.

**How to reach me**: [[Telegram]](https://t.me/BeastMaster77) or via GitHub messaging.
