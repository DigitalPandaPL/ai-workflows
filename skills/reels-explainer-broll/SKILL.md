---
name: reels-explainer-broll
description: Plan and produce realistic explanatory video cutaways for an existing spoken reel, using approved concepts and ordered visual storyboards before paid video generation. Use for reels B-roll that illustrates a speaker’s explanation. Does not select raw takes, grade the full reel, add speech captions, or assemble the final reel unless separately requested.
---

# Reels explainer B-roll

Create dynamic, photorealistic cutaways that make the speaker’s meaning easier to understand. Deliver separate usable footage and editor handoff data. A storyboard guides ONE continuous requested clip; its images are not orders for separate video generations.

Default conversation language: match the user. Prefer their existing provider and approved visual direction. Be candid: references reduce errors but cannot guarantee flawless generative output. Do not advertise a successful prompt as a guarantee.

## Read only what is needed

- During intake, concept and storyboard: [planning.md](references/planning.md).
- Before provider/model selection and generation: [generation.md](references/generation.md).
- Before accepting output or deciding a retry: [quality.md](references/quality.md).
- When persisting work or delivering to another editor/agent: [handoff.md](references/handoff.md).

## Workflow and approval state

1. **Inspect source.** Identify the latest correct source reel, script, visual references and branding. Actually inspect video frames and its speech timing; a script alone is not evidence of the recorded timing. Resolve discrepancies in favor of the actual recording and user corrections.
2. **Propose in text.** Map each proposed cutaway to a spoken passage and exact source interval. Explain what the viewer should understand, the visible actions, continuity, duration and endpoint. Ask for concept agreement before creating the storyboard. If the user already approved the concept, proceed without asking again.
3. **Make ordered storyboard images.** Use real image generation/editing tools, not verbal descriptions masquerading as images. Cover each meaningful state change, preserving subject, geometry and style. Show images in narrative order. Keep a separate reusable prompt and state description for each image. Ask for storyboard agreement before paid video generation; prior approval applies only to the approved version and scope.
4. **Plan generation.** Separate exact overlays from cinematic content. Choose the least costly route that meets quality and control requirements. For complex photoreal scenes prioritize quality. Preflight cost and state model, resolution, duration, outputs and estimated total. Already-authorized generation does not require redundant permission. A material cost/scope change does.
5. **Generate the agreed unit.** One approved continuous cutaway means one final continuous video. Send the full narrative including its opening and ending, not only the section recently corrected. Include ordered reference roles, state invariants, timestamps and rendering requirements. Do not silently split it into separately billed videos. If the requested sequence cannot fit model limits, propose a concrete alternative before changing that plan.
6. **Inspect output.** Compare actual frames and timing with the approved storyboard. Inspect transitions and critical moments more densely than static holds. Check the actual media; a tool’s completed status only confirms generation finished.
7. **Deliver or narrowly repair.** Report verified results and material remaining limitations. Keep accepted assets fixed. Deliver durable files, source timing, side mappings, overlay instructions and generation metadata. Do not declare a defective clip final.

## Operating invariants

- Keep concept approval, storyboard approval, paid-generation authorization and delivery acceptance distinct. Honor explicit user overrides and approvals from earlier turns.
- Track what is approved; do not make the user repeat the same decisions after a pause or context reset.
- Fix ambiguity before spending video credits. Small visual errors in a keyframe can propagate throughout a video.
- Do not attach a faulty earlier video as an unrestricted reference. State precisely which aspects may be reused and which must be replaced.
- No default subtitles, logos, timeline, sound, text labels or complete-reel montage. Include only approved elements.
- Preserve real epistemic meaning: a clinician’s anecdote must not become a measured trial, a comparison must not imply a guaranteed outcome, and glowing markers must not fabricate numerical severity.
- For exact numbers, counters, charts and typography, default to deterministic motion graphics in a separate asset. A generative attempt is optional when explicitly requested; inspect every value and do not repeatedly pay to solve deterministic errors.
- Use scene-specific negative constraints, not huge generic ban lists. Specific positive actions and visible end states are primary.
- Never run indefinite paid retries. Default one approved attempt per cutaway unless the user has set a retry budget. After a failed generation, diagnose and prepare a concrete repair brief; request additional spend only if not already authorized. Do not resubmit a transport-timeout job until its submission status is resolved.

## Scope boundary

This skill owns explanatory cutaways and their separate overlays. Source-take selection, full color grading, speech-caption authoring, full reel assembly and publishing belong to later workflows. Preserve neutral, consistent, gradeable imagery here; do not impose a heavy look that conflicts with later grading. Agent handoff should use saved files and a manifest, not require access to this conversation.
