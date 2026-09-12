# Public evidence snapshot

This file contains selected facts verified against the preserved SQLite checkpoint used for the pre-public snapshot. It intentionally reports **what happened**, not what the behavior “means.” Interpretations belong in separate analysis.

## Snapshot totals

Checkpoint state at model tick **56**:

- **6** residents
- **701** journaled events
- **93** rest events
- **20** solitude/seclusion events
- **35** project-state events
- **25** research events
- **15** play events
- **14** personal record events
- **12** reflection events
- **12** planting events
- **10** writing events
- **10** crafted-object events
- **9** drawing events
- **8** movement events
- **6** construction attempts
- **6** directed experience-sharing events
- **5** music events
- **4** explicit refusals
- **3** invitations
- **3** requests to share observations
- **1** acceptance
- **1** voluntary shared-library publication
- **1** shared-library read

Perception events are journaled separately and account for **336** events in the same snapshot.

## Verified examples

### 1. Refusal exists as a real action

Four explicit refusals are present in the checkpoint:

- tick 13 · **Нери → Таль**: “Сейчас хочется тишины.”
- tick 17 · **Эйра → Соль**: “Сейчас хочется тишины.”
- tick 49 · **Ив → Соль**: “Сейчас хочется тишины.”
- tick 55 · **Соль → Ив**: “Сейчас хочется тишины.”

These are stored as refusal events rather than silently converting into cooperation.

### 2. A failed construction was followed by a different construction outcome

At tick 23, **Таль** attempted a reed construction titled `Незавершённая линия · звучание` with height 3 and span 7. The recorded condition is **collapsed**.

At tick 26, Таль attempted another reed construction with the same title, height 1 and span 2. The recorded condition is **standing**.

This is a physical outcome difference in the environment. The public snapshot does not claim that the second result proves learned engineering skill; future skill-trace work should test that question explicitly.

### 3. The first voluntary library publication

At tick 48, **Ив** measured soil moisture at **0.27**.

At tick 50, Ив voluntarily published a shared-library entry:

- title: `Запись о местном опыте`
- category: `observation`
- text: `Измеряет влажность почвы: 0.27`

The publication is stored as a distinct event and entry rather than automatically exposing all personal memory.

### 4. Artifacts are structured data, not only captions

The checkpoint contains drawings as stored stroke coordinates and colors, and music as stored pitch/duration sequences.

Examples:

- tick 35 · **Эйра** · drawing `Изменчивое место · звучание`
- tick 36 · **Ив** · drawing `Промежуток · паузы`
- tick 39 · **Ори** · drawing `Незавершённая линия · почва`
- tick 42 · **Ори** · music `Незавершённая линия · почва`
- tick 52 · **Ив** · music `Отголосок · паузы`

### 5. Social information can be transferred with provenance

At tick 56, **Соль → Ив** shared the measured statement:

`Измеряет растение: размер 0.090`

The event marks the information as `measured` and records its source relationship.

### 6. Projects can start, pause, complete or remain unfinished

Project state is persistent. For example:

- **Ори** completed `Изменчивое место · почва` at tick 30.
- Ори later paused `Незавершённая линия · почва` at tick 47.
- a different project with that title was subsequently started at tick 50 and completed at tick 55.
- **Эйра** completed `Отголосок · звучание` at tick 38 and later completed `Незавершённая линия · звучание` at tick 54.

## What this snapshot does not prove

This evidence does **not** establish consciousness, subjective experience, self-awareness, or the spontaneous emergence of an independent culture.

The documented canonical snapshot uses a deterministic autonomous control policy designed to test infrastructure and causal continuity. The value of publishing this evidence is that later experimental phases can be compared against a preserved baseline rather than against memory or marketing claims.

## Reproducibility / provenance

The private source repository retains the full checkpoint and a timestamped SHA-256 manifest. The public showcase discloses selected evidence while keeping private databases, personal-memory internals and operational credentials outside the public repository.
