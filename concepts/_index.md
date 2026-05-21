# Concepts — карта BoK

16 концептов, структурированных по 5-слойной модели Learning Object. Каждая карточка самодостаточна — изучается через `/study-concept <slug>`.

## По блокам

### Блок 1 — Формулирование и контекст

| Slug | Название | Trudn. | Связан с |
|---|---|---|---|
| `cynefin` | Cynefin Framework | medium | `problem-formulation`, `system-archetypes` |
| `problem-formulation` | Формулирование проблемы (5 элементов + gap) | low | `cynefin`, `five-whys`, `iceberg-model` |
| `five-whys` | 5 Почему | low | `problem-formulation`, `iceberg-model`, `causal-loop-diagrams` |

### Блок 2 — Диагностика системы

| Slug | Название | Trudn. | Связан с |
|---|---|---|---|
| `iceberg-model` | Iceberg Model (4 уровня) | medium | `problem-formulation`, `causal-loop-diagrams`, `system-archetypes`, `leverage-points` |
| `causal-loop-diagrams` | Causal Loop Diagrams | high | `iceberg-model`, `system-archetypes`, `stocks-and-flows` |
| `system-archetypes` | 5 системных архетипов | high | `causal-loop-diagrams`, `leverage-points` |
| `stocks-and-flows` | Stocks and Flows | medium | `causal-loop-diagrams`, `leverage-points` |

### Блок 3 — От диагноза к решению

| Slug | Название | Trudn. | Связан с |
|---|---|---|---|
| `leverage-points` | 5 уровней рычага (Meadows) | medium | `iceberg-model`, `system-archetypes`, `hypothesis-portfolio` |
| `stakeholder-map` | Карта стейкхолдеров (Mendelow) | low | `problem-formulation`, `hypothesis-portfolio` |
| `effort-impact` | Effort / Impact матрица | low | `leverage-points`, `hypothesis-portfolio` |
| `hypothesis-portfolio` | Портфель гипотез | medium | `leverage-points`, `effort-impact`, `experiment-design` |

### Блок 4 — Реализация и сопровождение

| Slug | Название | Trudn. | Связан с |
|---|---|---|---|
| `experiment-design` | Plan / Test / Metric / Decision | medium | `hypothesis-portfolio`, `evaporating-cloud` |
| `evaporating-cloud` | Грозовая туча (TOC) | medium | `problem-formulation`, `hypothesis-portfolio`, `experiment-design` |

### Блок 5 — Стратегическое мышление

| Slug | Название | Trudn. | Связан с |
|---|---|---|---|
| `creative-tension` | Creative Tension (Senge) | medium | `system-archetypes`, `scenario-thinking`, `strategic-bets` |
| `scenario-thinking` | Сценарное мышление (2×2) | medium | `creative-tension`, `strategic-bets` |
| `strategic-bets` | Стратегические ставки (ОНМС) | high | `creative-tension`, `scenario-thinking`, `hypothesis-portfolio` |

## Граф связей (ASCII)

```
                      Cynefin
                       │
                       ▼
              Problem-Formulation
                  │     │     │
                  ▼     ▼     ▼
              5-Whys  Iceberg  Stakeholder-Map
                        │           │
                        ▼           ▼
        ┌─────────── CLD ──────► Stocks/Flows
        │            │
        ▼            ▼
  Archetypes ──► Leverage-Points ───► Effort/Impact
                       │                    │
                       └─► Hypothesis ◄─────┘
                              │
                              ▼
                       Experiment-Design ─► Evaporating-Cloud
                              │
                              ▼
                   ┌─► Creative-Tension ──┐
                   │                       ▼
                   └─► Scenario ─────► Strategic-Bets (ОНМС)
```

## По сложности

- **Low (3):** `problem-formulation`, `five-whys`, `stakeholder-map`, `effort-impact`
- **Medium (9):** `cynefin`, `iceberg-model`, `stocks-and-flows`, `leverage-points`, `hypothesis-portfolio`, `experiment-design`, `evaporating-cloud`, `creative-tension`, `scenario-thinking`
- **High (3):** `causal-loop-diagrams`, `system-archetypes`, `strategic-bets`

## По авторам методологии

- **Snowden:** `cynefin`
- **Senge:** `system-archetypes`, `creative-tension`
- **Meadows:** `leverage-points`, `stocks-and-flows`
- **Forrester / Sterman:** `causal-loop-diagrams`
- **Toyoda (Toyota) + Goldratt (TOC расширение):** `five-whys`
- **Goldratt:** `evaporating-cloud`
- **Wack / Schwartz / Shell:** `scenario-thinking`
- **Mendelow / Eden & Ackermann:** `stakeholder-map`
- **Ries / Lean Startup:** `experiment-design`
- **Master Strategy / Безуглый (адаптация и авторские):** `problem-formulation` (типизация задач + две проблемы), `iceberg-model` (мультистейкхолдерность), `hypothesis-portfolio`, `strategic-bets` (ОНМС)

## Карты применения

### Path: «У меня проблема, не понимаю, какая модель применяется»

Маршрут: `problem-formulation` → `cynefin` → `five-whys` → определение типа корневой причины → один из трёх:
- Простая → углублённый `five-whys`
- Убеждения → `iceberg-model`
- Динамика → `causal-loop-diagrams` (часто после `iceberg-model`)

### Path: «Диагноз есть, не знаю, что делать»

Маршрут: `system-archetypes` → `leverage-points` → `stakeholder-map` + `effort-impact` → `hypothesis-portfolio` → `experiment-design`.

### Path: «Думаю над долгосрочной стратегией»

Маршрут: `creative-tension` → `scenario-thinking` → `strategic-bets`. С опорой на `system-archetypes` (Eroding Goals как риск) и `leverage-points` (уровень 4-5 для парадигмальных ставок).
