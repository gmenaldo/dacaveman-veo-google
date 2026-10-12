# Workflow — DaCaveman on Google Veo 3.1

Estimated time: about one hour for a first test render of Scene One. Full skit will take longer.

## Step 1 — Open Flow

Go to **flow.google.com** (or Google AI Studio at aistudio.google.com for the API route). Sign in with your Google account. Veo 3.1 requires a paid plan — no free tier.

## Step 2 — Generate character references

In Flow, use **Nano Banana** (image mode) to create three reference images per main character: Dan, Tom, the shop worker, the owner, and the female cavewoman. Plain background, consistent style. Use the descriptions in `character-sheets.md`.

Save these — they are your "ingredients" for every video shot.

## Step 3 — Generate Scene One test

Switch to **Ingredients to Video**. Attach Dan's full-body reference and Tom's reference. Paste Shot 1.4 from `veo-prompts.md` (the dialogue beat). Generate.

Review: do the faces hold? Do the nails read as ancient and thick? If not, regenerate with the same prompt — Veo is stochastic, so the second or third try often lands.

## Step 4 — Iterate per scene

Work scene by scene. For each scene:
1. Pick the 2–4 most important shots.
2. Paste the matching prompt, attach the right ingredients.
3. Generate, pick the best take, extend if needed.

## Step 5 — Transformation shots

For Shots 4.2 and 4.4, use **Frames to Video**: supply the "before" still (normal caveman in winter gear / at the counter) as the start frame and the "after" still (transformed, sackcloth, nails exposed) as the end frame. Veo will interpolate between them.

## Step 6 — Assemble

Download the clips. Stitch in any free editor (CapCut, DaVinci Resolve) with the dialogue synced. Compare against the open-source render from the `dacaveman-skit` repo.

## Cost guardrail

Before committing to all 81 shots: render one scene fully, count what it costs, then decide. Fast at $0.10/s is the sane default for drafts; Standard at $0.40/s only for final takes you love.

## If something blocks

Soften "sackcloth exposing chest hair" to "simple cloth garment." Keep the nails description — that's the character's signature and the least likely to trigger filters.