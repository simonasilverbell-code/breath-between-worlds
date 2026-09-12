# Related work and positioning

Breath Between Worlds sits in a growing family of persistent multi-agent and embodied-agent experiments. This page records adjacent work so the project can be evaluated against prior art rather than presented as if the category did not already exist.

## Generative Agents / Smallville

Stanford's *Generative Agents: Interactive Simulacra of Human Behavior* demonstrated agents with memory, reflection, planning and social propagation inside a small simulated town.

https://github.com/joonspk-research/generative_agents

What we learn from it: memory architecture matters most when earlier experience can alter later behavior in ways that are inspectable.

## AI Town

a16z's AI Town is a deployable virtual town where AI characters live, chat and socialize. Its backend emphasizes persistent shared state and an extensible simulation foundation.

https://github.com/a16z-infra/ai-town

What we learn from it: a persistent world needs a robust state engine and an interface that makes ongoing activity easy to inspect.

## Voyager

Voyager explores lifelong skill acquisition in Minecraft using an automatically growing skill library.

https://github.com/MineDojo/Voyager

What we learn from it: persistent memory becomes more compelling when experience changes future practical capability rather than only adding narrative history.

## AgentWorld and other world-driven agent experiments

Recent open-source projects are explicitly exploring the distinction between task-driven agents and agents placed inside persistent environments with identity, memory and relationships. This is an active area, not an empty niche.

One example is AgentWorld, an open runtime for autonomous agent societies with persistent state, relationships and multi-step planning. Recent community discussions also ask what changes when agents are given a world rather than a task.

The existence of closely related projects is useful: it gives this project concrete peers for comparison and makes experimental differentiation more important than branding claims.

## Current differentiation of Breath Between Worlds

The present experiment emphasizes a different combination of constraints:

- no scalar reward, leaderboard or mandatory economic objective;
- rest, solitude, refusal and unfinished projects are valid resident states;
- abstract non-human manifestations rather than fixed human avatars;
- separate private memory and voluntary public sharing;
- structured resident-created artifacts stored in the world record;
- local perception and provenance of socially transferred information;
- a preserved deterministic baseline before the LLM decision phase;
- public provenance hashes and explicit separation of verified events from interpretation.

These are design choices, not claims that the project is categorically superior or unprecedented.

## Research direction

The next useful comparison is not which project produces the most dramatic stories. It is whether we can measure:

1. biography-conditioned decisions;
2. acquired skill rather than fixed-menu variation;
3. effects of richer spatial causality;
4. provenance-preserving social knowledge transfer;
5. longitudinal changes that survive restart and can be inspected later.

If related work should be added or a comparison here is inaccurate, please open a research-feedback issue.
