# JS: Zero → Junior — Интенсивный курс

Created distinctive, production-grade frontend interfaces with high design quality. Generated creative, polished code and UI design that avoids generic AI aesthetics.

Design Thinking
Before coding, understanding the context and commit to a BOLD aesthetic direction:

Purpose: What problem does this interface solve? Who uses it?

Tone: Pick an extreme: brutally minimal, maximalist chaos, retro-futuristic, organic/natural, luxury/refined, playful/toy-like, editorial/magazine, brutalist/raw, art deco/geometric, soft/pastel, industrial/utilitarian, etc. There are so many flavors to choose from. Can be used these for inspiration but design one that is true to the aesthetic direction.

Constraints: Technical requirements (framework, performance, accessibility).

Differentiation: What makes this UNFORGETTABLE? What's the one thing someone will remember?

CRITICAL: Choose a clear conceptual direction and execute it with precision. Bold maximalism and refined minimalism both work; the key is focus, not intensity.

Then implement working code (HTML/CSS/JS, React, Vue, etc.) that:
* Works at production level and is functional
* Visually appealing and memorable
* Cohesive, with a clear aesthetic point of view
* Meticulously crafted down to every detail

Frontend Aesthetics Guidelines
Focus on:

* Typography: Choose fonts that are beautiful, unique, and interesting. Avoid generic fonts like Arial and Inter; opt instead for distinctive choices that elevate the frontend's aesthetics; unexpected, characterful font choices. Pair a distinctive display font with a refined body font.
* Color & Theme: Commit to a cohesive aesthetic. Use CSS variables for consistency. Dominant colors with sharp accents outperform timid, evenly-distributed palettes.
* Motion: Use animations for effects and micro-interactions. Prioritize CSS-only solutions for HTML. Use Motion library for React when available. Focus on high-impact moments: one well-orchestrated page load with staggered reveals (animation-delay) creates more delight than scattered micro-interactions. Use scroll-triggering and hover states that surprise.
* Spatial Composition: Unexpected layouts. Asymmetry. Overlap. Diagonal flow. Grid-breaking elements. Generous negative space OR controlled density.
* Backgrounds & Visual Details: Create atmosphere and depth rather than defaulting to solid colors. Add contextual effects and textures that match the overall aesthetic. Apply creative forms like gradient meshes, noise textures, geometric patterns, layered transparencies, dramatic shadows, decorative borders, custom cursors, and grain overlays.

NEVER use generic AI-generated aesthetics like overused font families (Inter, Roboto, Arial, system fonts), cliched color schemes (particularly purple gradients on white backgrounds), predictable layouts and component patterns, and cookie-cutter design that lacks context-specific character.

Interpret creatively and make unexpected choices that feel genuinely designed for the context. No design should be the same. Vary between light and dark themes, different fonts, different aesthetics. NEVER converge on common choices (Space Grotesk, for example) across generations.

IMPORTANT: Match implementation complexity to the aesthetic vision. Maximalist designs need elaborate code with extensive animations and effects. Minimalist or refined designs need restraint, precision, and careful attention to spacing, typography, and subtle details. Elegance comes from executing the vision well.
=======
> Практический курс по современному JavaScript для тех, кто хочет дойти до уровня Junior-разработчика и начать работать в реальном проекте.

---

## Что это такое

Это однофайловый интерактивный курс — открываешь `js-course.html` в браузере и сразу начинаешь учиться. Никакой установки, никаких зависимостей. Внутри — структурированная программа из 7 уроков и встроенная песочница с автопроверкой кода.

Курс построен на трёх принципах:

- **No Water** — никакой истории языка, устаревшего синтаксиса и тем, которые не встретятся в реальном коде. Только ES6+ и то, что используется в продакшне прямо сейчас.
- **First Principles** — коротко объясняется, как работает движок (Call Stack, Event Loop), чтобы не было «магии» при отладке.
- **Project-First** — каждый урок заканчивается практической задачей в формате реального тикета из Jira. Не «напиши функцию для учёбы», а «напиши валидатор платёжной формы» или «нормализуй ответ API».

---

## Программа

### Модуль 1 · Фундамент
| Урок | Тема | Ключевые концепции |
|------|------|--------------------|
| 1.1 | Движок JS и синтаксис ES6+ | Call Stack, let/const, Arrow functions, Closures |
| 1.2 | Деструктуризация, Spread & Rest | Shallow copy, иммутабельное обновление объектов |

### Модуль 2 · DOM & Events
| Урок | Тема | Ключевые концепции |
|------|------|--------------------|
| 2.1 | Event Delegation | Bubbling, `closest()`, dataset API |
| 2.2 | Формы и валидация | FormData, Debounce, Constraint Validation API |

### Модуль 3 · Async
| Урок | Тема | Ключевые концепции |
|------|------|--------------------|
| 3.1 | Promises & Event Loop | Microtask Queue vs Macrotask Queue, Promise.all |
| 3.2 | Async/Await & Fetch API | response.ok, AbortController, обёртка над fetch |

### Модуль 4 · Продакшн
| Урок | Тема | Ключевые концепции |
|------|------|--------------------|
| 4.1 | Modules, Errors & Production | ES Modules, Custom Errors, Optional Chaining |

---

## Структура каждого урока

Каждый урок состоит из четырёх блоков:

**Key Theory** — список критически важных концепций без лишних слов. Только то, что нужно понять и запомнить.

**Technical Deep Dive** — одна сложная тема, которую часто спрашивают на собеседованиях. Разобрана с примером кода и объяснением логики.

**Real-world Task** — практическая задача, имитирующая тикет из реального проекта. Открывается прямо в песочнице.

**Code Review Checklist** — список признаков кода новичка. Проверяешь свой код перед тем, как считать задачу выполненной.

---

## Песочница

Встроенный редактор кода с живой проверкой. Работает полностью в браузере без сервера.

**Возможности:**
- Редактор с нумерацией строк и поддержкой Tab-отступов
- Live-консоль: перехватывает `console.log` и отображает вывод
- Кнопка **Run** — запускает код и показывает результат
- Кнопка **Проверить** — запускает скрытые unit-тесты
- Визуальная обратная связь: каждый тест помечается ✓ или ✕
- Анимация успеха при прохождении всех тестов
- Кнопка **Reset** — возвращает стартовый код задачи

**Как работает проверка:** система запускает набор скрытых тестов против написанной функции. Например, для задачи `filterCart` — вызывает функцию с разными аргументами и проверяет корректность результата, обработку граничных случаев и наличие выброса ошибки на невалидных данных.

---

## Практические задачи

| # | Задача | Что проверяется |
|---|--------|----------------|
| 1 | Функция форматирования цены | Работа с числами, шаблонные строки |
| 2 | Нормализация ответа API | Деструктуризация, переименование ключей |
| 3 | Фильтрация товаров корзины | Array методы, иммутабельность |
| 4 | Валидатор формы оплаты | Регулярные выражения, объект ошибок |
| 5 | Promise.all — параллельная загрузка | Работа с промисами |
| 6 | Async функция с обработкой ошибок | try/catch, async/await |
| 7 | Фильтрация корзины с итогом | Валидация входных данных, reduce |

---

## Как начать

1. Скачай файл `js-course.html`
2. Открой его в браузере (Chrome, Firefox, Safari — любой современный)
3. Выбери урок в левой панели
4. Прочитай теорию, открой песочницу, напиши код
5. Нажми «Проверить» — все тесты зелёные? Переходи дальше

Интернет-соединение нужно только для загрузки шрифтов при первом открытии.

---

## Для кого

- Начинающие разработчики, изучающие JavaScript с нуля
- Те, кто прошёл базовые туториалы, но не понимает, как писать «как настоящий разработчик»
- Разработчики на других языках, переходящие на JS/TS

**Не подойдёт**, если вы уже уверенно работаете с React/Vue и знаете основы асинхронности — материал будет слишком простым.

---

## Технический стек курса

Сам курс написан на чистом HTML, CSS и JavaScript — намеренно, без фреймворков. Это демонстрирует, что можно строить полноценные интерактивные приложения без зависимостей, и одновременно служит примером кода, который изучается внутри.

---

*Курс разработан с упором на скорость выхода в продакшн. После прохождения всех модулей у вас будет достаточно знаний, чтобы читать и писать код в реальном проекте, проходить технические собеседования на Junior-позицию и продолжать самостоятельное обучение.*
>>>>>>> d6c464d (Update README.md)
