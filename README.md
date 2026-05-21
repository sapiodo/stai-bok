# Systems Thinking with AI — Body of Knowledge

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

**Что это:** структурированная база знаний по системному и стратегическому мышлению для самостоятельного и наставнического изучения. Репозиторий рассчитан на работу через [Claude Code](https://claude.ai/code) — два встроенных навыка (`/solve-problem` и `/study-concept`) превращают BoK в интерактивный тренажёр и справочник.

**Источник:** методология курса **12-CM-STAI** (Systems Thinking with AI) программы Master Strategy. Автор методологии — Дмитрий Безуглый. Адаптация для академического запуска — курс **514-CM-MIPT** (МФТИ, 3-й курс).

---

## Быстрый старт

1. **Клонируй репозиторий:**
   ```bash
   git clone <repo-url> stai-bok
   cd stai-bok
   ```

2. **Открой в Claude Code:**
   ```bash
   claude
   ```

3. **Выбери путь входа** (`docs/learning-paths.md`):
   - **Linear** — последовательно по 7 занятиям (`lessons/L1..L7`)
   - **Problem-driven** — есть конкретная проблема → `/solve-problem`
   - **Concept-driven** — хочешь изучить одну модель → `/study-concept iceberg-model`

4. **Проверь усвоение** — квизы в `self-tests/`.

---

## Структура

```
stai-bok/
├── concepts/         # 16 концепт-карточек по 5-слойной LO
├── lessons/          # 7 лекционных конспектов
├── illustrations/    # SVG/PNG диаграммы
├── self-tests/       # квизы Q2-Q7 + ключи
├── docs/             # how-to, learning-paths, glossary
└── .claude/
    ├── commands/     # /solve-problem, /study-concept
    └── skills/       # реализации двух навыков
```

## Два навыка

### `/solve-problem` — orchestration

4-фазный pipeline системного решения проблемы:

```
Формулирование → Д1 ⛔ → Диагностика → Д2 ⛔ →
Решение → Д3 ⛔ → Реализация и сопровождение → Д4 ⛔
```

Каждая фаза заканчивается диалоговой стоп-точкой (Д) — ты подтверждаешь, корректируешь или возвращаешься.

### `/study-concept`

Прохождение одной концепции по 5-слойной структуре Learning Object:

| Слой | Что делаешь | Стоп |
|---|---|---|
| 1 Знакомство | Опознаёшь концепт в своём опыте | С1 ⛔ |
| 2 Понимание | Принципы и правила «если → то» | С2 ⛔ |
| 3 Применение | Применяешь на своём кейсе | С3 ⛔ |
| 4 Рефлексия | Сравниваешь контрастные кейсы | С4 ⛔ |
| 5 Интеграция | Границы, связи, эволюция мышления | — |

---

## Состав концептов

**Системное мышление:**
- 01. Cynefin — классификация контекста
- 02. Problem Formulation — 5 элементов + gap
- 03. Five Whys — углублённый поиск корневой причины
- 04. Iceberg Model — 4 уровня анализа
- 05. Causal Loop Diagrams — петли обратной связи
- 06. System Archetypes — 5 канонических архетипов
- 07. Stocks and Flows — накопления и потоки
- 08. Leverage Points — 5 уровней рычага Медоуз

**От системного к решению:**
- 09. Stakeholder Map — карта влияния × интереса
- 10. Effort / Impact — приоритизация
- 11. Hypothesis Portfolio — портфель решений
- 12. Experiment Design — Plan/Test/Metric/Decision
- 13. Evaporating Cloud — анализ конфликта (TOC)

**Стратегическое мышление:**
- 14. Creative Tension — видение vs реальность (Senge)
- 15. Scenario Thinking — матрица 2×2
- 16. Strategic Bets — ОНМС (обоснованность, необратимость, масштаб, субъектность)

---

## Лицензия и атрибуция

Материалы распространяются под [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/).

**Кратко:** можно использовать и адаптировать с указанием авторства, нельзя в коммерческих целях, производные работы — под той же лицензией.

При цитировании используй формат из `CITATION.cff`.

## Обратная связь

Замечания и предложения — через GitHub Issues. PR с улучшениями (правки опечаток, дополнительные кейсы, переводы) приветствуются.

---

*Версия 1.0 · 2026-05-21 · Master Strategy*
