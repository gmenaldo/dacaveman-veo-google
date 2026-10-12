# DaCaveman — Google Veo 3.1 Track

Paid production track for the DaCaveman comedy skit, parallel to the open-source `dacaveman-skit` repo. Same script, same story — different engine.

**Goal:** Generate the skit with Google's Veo 3.1 (Flow / Google AI Studio) and compare against the open-source Wan 2.2 / LTX-Video render.

## What's in this repo

- `screenplay.md` — the full four-scene screenplay, lightly cleaned for readability (Dave → Tom, fir → fur, illusion of safety, twenty-four hours). Story and dialogue untouched.
- `character-sheets.md` — canonical descriptions of Dan, Tom, the shop workers, the owner, and the female cavewoman for consistent prompting.
- `veo-prompts.md` — paste-ready prompts for Veo 3.1, scene by scene, built for Ingredients to Video.
- `workflow.md` — the step-by-step to run it in Flow.

## Quick start

1. Read `screenplay.md` once.
2. Generate the character reference images (Nano Banana in Flow, or Imagen in AI Studio).
3. Paste the scene prompts from `veo-prompts.md` into Flow's Ingredients to Video mode, attaching the matching reference images.
4. Generate, review, extend clips as needed.

Full walkthrough: `workflow.md`.

## Cost note

Veo 3.1 has no free tier. Fast is $0.10/s at 720p, Standard is $0.40/s. An 8-second clip runs roughly $0.80 (Fast) to $3.20 (Standard). Budget accordingly — the skit is ~81 shots, so start with one scene to test before committing to all four.

## Comparison

Render the same scene in both repos and compare: character consistency, prompt adherence, audio quality, and how much manual cleanup each needs.