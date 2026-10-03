# Durable state and editor handoff

Use a project folder with human-readable ordered assets and a compact manifest. Store provider job/media IDs but no credentials or presigned upload secrets. References must be portable or clearly marked unavailable; no other chat should need the original conversation to understand the project.

Minimum project record:
- source: original name/path or durable URL, version, fps, duration, dimensions;
- brand: supplied source, verified font/color values, access status;
- approved visual rules and references;
- scenes: stable IDs, spoken excerpts, source in/out in seconds and frame convention;
- concept version and approval evidence;
- storyboard image order, state descriptions, approval version;
- requested output count/unit and duration;
- overlay requirements and side/identity mappings;
- generation: model, settings, prompt, references, cost estimate, actual charge if known, job ID, status;
- QA: checks performed, actual event times, critical failures, known limitations;
- delivery: durable final paths, overlay blend/alpha details, insertion points, trims/retiming, acceptance status.

Suggested scene states: source-reviewed → concept-proposed → concept-approved → storyboard-produced → storyboard-approved → generation-authorized → generating → qa-failed / qa-passed → delivered → user-accepted. These are tracking labels, not new approval demands: reuse prior explicit authorization.

For grading downstream, preserve original provider export. Record known codec, bit depth, color metadata and actual fps from probing; write unknown rather than inventing Rec.709/log/HDR status. Do not bake unnecessary creative LUTs or transform skin tones to enforce a brand palette.

For final editing downstream, distinguish intended cue timing from achieved animation timing. Explain how labels map to sides if narration supplies the meaning. Provide separate graphics and no speech captions unless requested. If a user later asks to assemble, grade or publish, route that new scope to its appropriate workflow.
