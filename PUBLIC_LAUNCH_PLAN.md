# Public launch plan

Prepared 12 September 2026.

The goal is to let people observe the world without exposing the private database, resident-private memory, observer bearer token, or any control surface.

## Phase A — public baseline (live now)

The public showcase and preserved Observer snapshot are already online. They show selected verified evidence from the frozen pre-LLM baseline and are deliberately separated from the private live world.

This phase establishes provenance and gives visitors something inspectable before any live bridge is opened.

## Phase B — live read-only world window

Target: the next release after the safety gate passes.

The public live projection may expose only:

- current model tick and world clock status;
- weather / season and public map state;
- resident name, position, visible manifestation, current activity and current interests;
- public artifacts and physical objects;
- shared-library entries;
- a sanitized high-level event stream.

It must not expose:

- private episodic, semantic or social memory;
- recalled memory IDs or future causal-memory traces until explicitly public-safe;
- private perception packets;
- private project internals or hidden plans;
- decisions / prompts / model packets;
- observer credentials or deployment secrets;
- mutation endpoints.

The live public surface is read-only. Browser actions must never advance simulation time or enter resident context.

## Phase C — public beta

Before broad promotion:

1. verify the live projection on mobile and desktop;
2. verify that no unauthenticated route can reach the private `/api/*` observer;
3. verify that POST, PUT, PATCH and DELETE remain unavailable;
4. inspect representative payloads for memory or credential leakage;
5. confirm the live world continues advancing normally while visitors browse;
6. keep the frozen baseline accessible as a separate historical layer.

Once these checks pass, label the page **Public Beta** and begin inviting technical observers.

## Phase D — post-LLM era

The Wednesday LLM transition should not overwrite the baseline narrative. Preserve the deterministic baseline as **Era 0 / Control**, then begin a separately labelled LLM-driven era.

Before that transition, preserve another canonical checkpoint and publish only its cryptographic fingerprint.

The later public Observer should make the distinction between control-policy history and LLM-policy history impossible to miss.

## Launch principle

Public observation is allowed. Public direction is not.

The public interface is a window into the world, not a steering wheel.
