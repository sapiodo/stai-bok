# Learning Paths — пути входа в BoK

Три способа потребить материал. Выбирай по типу твоей задачи, не по «как принято».

## Путь 1: Linear — последовательно по занятиям

**Когда выбирать:**
- У тебя есть свободные 10-15 часов на 2-3 недели
- Хочешь освоить методологию целостно, не вырывая куски
- Готовишься к Showcase / экзамену / финальной защите

**Маршрут:**

| Шаг | Действие | Время |
|---|---|---|
| 1 | Конспект `lessons/L1-introduction.md` | 15 мин |
| 2 | Концепт `cynefin` через `/study-concept cynefin` | 30 мин |
| 3 | Конспект `lessons/L2-problem-definition.md` | 30 мин |
| 4 | Квиз `self-tests/Q2-problem-formulation.md` | 15 мин |
| 5 | Концепты `problem-formulation`, `five-whys` (deep-study) | 1.5 ч |
| 6 | Конспект `lessons/L3-iceberg-cld.md` + квиз `Q3` | 1 ч |
| 7 | Концепты `iceberg-model`, `causal-loop-diagrams` (deep-study) | 2 ч |
| 8 | Конспект `lessons/L4-archetypes.md` + квиз `Q5` | 1 ч |
| 9 | Концепт `system-archetypes` (deep-study) | 1 ч |
| 10 | Конспект `lessons/L5-leverage-points.md` + квизы `Q6-Q7` | 1.5 ч |
| 11 | Концепты `leverage-points`, `stakeholder-map`, `effort-impact` | 1.5 ч |
| 12 | Конспект `lessons/L6-validation-experiments.md` | 45 мин |
| 13 | Концепты `experiment-design`, `evaporating-cloud`, `hypothesis-portfolio` | 1.5 ч |
| 14 | Конспект `lessons/L7-strategic-bridge.md` | 45 мин |
| 15 | Концепты `creative-tension`, `scenario-thinking`, `strategic-bets` | 1.5 ч |
| 16 | Финал — запустить `/solve-problem` на собственном кейсе | 2-3 ч |

**Итого:** ~15-18 часов чистого времени.

## Путь 2: Problem-driven — есть конкретная проблема

**Когда выбирать:**
- У тебя есть реальная ситуация, которую хочешь разобрать
- Не хочешь сначала «учить теорию» — учишься через применение
- Готов потратить 2-4 часа на полный pipeline

**Маршрут:**

1. Запустить `/solve-problem` — pipeline сам поведёт через 4 фазы
2. На каждой фазе AI указывает, какие концепты применяются
3. Если на любом шаге не понимаешь, какой инструмент использовать — прервись и запусти `/study-concept <slug>`, потом вернись
4. Артефакт = ПЗ с полным разбором + портфель гипотез + план экспериментов

**Преимущество:** концепты усваиваются в контексте применения, не как абстрактная теория. Запоминаются на 6-12 месяцев.

**Риск:** ты можешь обойти концепт, который тебе пригодился бы в другом контексте. Восполняй позже через Path 3 (concept-driven), когда возникнет вопрос.

## Путь 3: Concept-driven — выборочно по концептам

**Когда выбирать:**
- Тебе нужны конкретные инструменты под конкретную задачу
- Время ограничено (1-3 часа в неделю), но есть несколько недель
- Не нужен Showcase / экзамен — учишься для практики

**Маршрут по ролям:**

### Продакт-менеджер (~4-5 часов)
1. `/study-concept problem-formulation` — формулировка проблемы
2. `/study-concept iceberg-model` — диагноз ментальных моделей пользователя/команды
3. `/study-concept leverage-points` — где воздействовать
4. `/study-concept hypothesis-portfolio` — портфель гипотез
5. `/study-concept experiment-design` — валидация

### Тимлид / руководитель команды (~3-4 часа)
1. `/study-concept cynefin` — какой тип задачи
2. `/study-concept system-archetypes` — узнать повторяющиеся паттерны в команде
3. `/study-concept stakeholder-map` — карта влияния
4. `/study-concept creative-tension` — видение vs реальность команды

### Стратег / основатель (~4-5 часов)
1. `/study-concept creative-tension` — рамка видения
2. `/study-concept scenario-thinking` — подготовка к неопределённости
3. `/study-concept strategic-bets` — ОНМС
4. `/study-concept leverage-points` — где рычаг в твоей системе
5. `/study-concept system-archetypes` — какие архетипы блокируют рост

### Аналитик / консультант (~5-6 часов)
1. `/study-concept iceberg-model` — глубинный анализ
2. `/study-concept causal-loop-diagrams` — петли обратной связи
3. `/study-concept system-archetypes` — распознавание паттернов
4. `/study-concept evaporating-cloud` — разбор конфликтов
5. `/study-concept compare iceberg-model causal-loop-diagrams` — когда какой инструмент

### Студент университета (готовится к Showcase) (~10-12 часов)
1. Linear-путь, но без квизов и без концептов с difficulty `low` (`stakeholder-map`, `effort-impact`)
2. Финал — `/solve-problem` на учебном кейсе с командной защитой

## Гибридные сценарии

- **Concept-first, problem-finish:** освой 3-5 концептов под роль, потом примени через `/solve-problem`
- **Problem-first, concept-deep-dive:** запусти `/solve-problem`, в местах слабости — погружайся в концепт
- **Команда:** каждый член команды берёт свой Concept-driven путь под роль, общий `/solve-problem` ведёшь вместе

## Ритм

- **Спринт (1 неделя, 8-10 часов):** Linear до L4 + один `/solve-problem`
- **Курс (4 недели, 4-5 часов в неделю):** полный Linear + два `/solve-problem`
- **Параллельно с работой (10 недель × 2 часа):** Concept-driven по роли + один `/solve-problem` в месяц

Не пытайся пройти всё за неделю. Системное мышление формируется через повторное применение, не через однократное прочтение.
