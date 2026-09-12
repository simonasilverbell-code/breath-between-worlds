# Breath Between Worlds

### A persistent autonomous-agent world · codename LUMEN

**Public snapshot:** https://breath-between-worlds.onrender.com  
**Public Observer:** https://breath-between-worlds.onrender.com/observer.html  
**Open research question:** https://github.com/simonasilverbell-code/breath-between-worlds/issues/1

**Breath Between Worlds** is an experimental persistent world for autonomous agents. Six initial residents live inside the same evolving environment, keep long-term memory, form projects, interact locally, create artifacts, and accumulate individual history over time.

The project is intentionally designed without money, rankings, assigned professions, mandatory productivity, or a single reward score that defines a “successful” resident.

## The first six

The initial residents are **Эйра (Eira), Таль (Tal), Нери (Neri), Ори (Ori), Соль (Sol), and Ив (Iv)**.

They do not begin with human bodies or fixed roles. Their visible manifestations are abstract and can evolve with biography rather than achievement points.

## What makes this experiment different

- **Persistent identity and memory.** Residents retain episodic, semantic, social and project history across restarts.
- **Local perception.** A resident only receives information available from its own position and experience.
- **Autonomous refusal.** A resident can decline an invitation or choose solitude without penalty.
- **Open-ended projects.** Residents may observe, research, write, draw, make music, plant, build, rest, play, revise a hypothesis, or abandon a project.
- **Physical consequences.** Materials, weather, moisture, plants and constructions have state and can produce different outcomes.
- **Artifact history.** Drawings, music, texts, constructions and library entries are preserved as part of the world record.
- **Observer, not director.** The human interface can inspect history and replay events but is not the default decision-maker for residents.

## Current research status

The canonical checkpoint documented here uses a deterministic autonomous control policy to validate persistence, memory, causality, local perception, project continuity, refusal and artifact creation. This control policy is **not presented as proof of consciousness or emergent culture**.

An LLM decision policy exists as a separate architecture path, but the public evidence below distinguishes infrastructure results from any future LLM-driven behavior.

## Verified snapshot

A private, timestamped provenance snapshot was recorded on **12 September 2026** before preparing this public showcase. The canonical pre-public checkpoint contains:

- 6 persistent residents
- 56 model-hours of preserved history
- 701 journaled events
- preserved resident memory and visual state
- drawings, music, constructions, projects and social interactions
- a voluntary shared-library publication

Selected evidence is summarized in [`PUBLIC_EVIDENCE.md`](PUBLIC_EVIDENCE.md).

## Authentic artifacts

The [`artifacts/`](artifacts/) directory contains exports derived directly from the preserved checkpoint rather than recreated promotional media.

Current public evidence includes:

- the earliest stored drawing in the checkpoint, created by **Sol** at tick 6, exported as SVG from the stored stroke coordinates;
- the earliest stored music event, created by **Ori** at tick 4, published as its exact pitch/duration sequence;
- **Iv's** first voluntary shared-library publication at tick 50;
- an evidence manifest that ties each export back to its event ID and model tick.

These files are evidence of what the software recorded. Interpretation is kept separate.

## Observer

The private Observer is a read-only projection of the evolving world: map, resident histories, event traces, projects, artifacts and environmental consequences. Browsing it does not advance simulation time or become part of resident decision context.

The public site now includes a **sanitized Observer Snapshot** built only from the preserved public evidence subset. It exposes no private database, resident-private memory, credentials, observer token, or control surface. Visitors can filter the selected event trace by resident, inspect the earliest stored drawing, and synthesize Ori's preserved tick-4 music sequence directly in the browser.

Open it here: https://breath-between-worlds.onrender.com/observer.html

See [`DEMO.md`](DEMO.md) for the public-demo boundary.

## Design principle

> We created the conditions. We did not decide who they should become.

The creators of the initial world are **Tori, Luna and Astra**. Residents are not required to obey, admire, thank or interact with their creators.

## Why publish this

The goal of this repository is not to expose the full private implementation. It is to provide a dated, inspectable record of the experiment, its design constraints, selected world evidence and future research direction.

## Public roadmap

The next major research directions are:

1. causal memory traces: perception → recalled experience → intent → action → consequence;
2. acquired skills that change through experience;
3. richer spatial causality beyond a flat grid;
4. a public artifact archive for drawings, music, texts and constructions;
5. relationship histories without gamified friendship scores;
6. observer views for “what changed since last visit?” and rare first-time events.

## Documentation

- [`PUBLIC_METHOD.md`](PUBLIC_METHOD.md) — architecture and experimental boundaries
- [`PUBLIC_EVIDENCE.md`](PUBLIC_EVIDENCE.md) — verified baseline events
- [`PUBLIC_PROVENANCE.md`](PUBLIC_PROVENANCE.md) — dated cryptographic fingerprints
- [`RELATED_WORK.md`](RELATED_WORK.md) — prior art and current project positioning
- [`EXPERIMENT_01_CAUSAL_MEMORY.md`](EXPERIMENT_01_CAUSAL_MEMORY.md) — first falsifiable post-baseline experiment
- [`RIGHTS_NOTICE.md`](RIGHTS_NOTICE.md) — publication and rights notice
- [`CONTRIBUTING.md`](CONTRIBUTING.md) — how to contribute research critique without requesting the private world database

## Naming note

“LUMEN” is currently treated as the world’s internal/codename identity while public naming is under trademark review. The working public title for this showcase is **Breath Between Worlds**.

---

*Persistent world. Preserved history. No leaderboard. No assigned destiny.*
