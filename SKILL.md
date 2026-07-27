---
name: sticker-collage-video
description: Create or refine editable sticker-collage videos from talking-head recordings, voice-led explainers, product screenshots, screen recordings, logos, mascots, and reference videos. Use for sticker-style video editing, consistent sticker treatment of every non-background foreground element, mixed talking-head and visual-only explainers, vintage paper or fabric collage treatments, transcript-synced motion graphics, product relationship diagrams, and quality review of an existing editable video project.
---

# Sticker Collage Video

Build a story-led video that feels assembled from physical stickers, cut paper, photographs, and moving UI—not a slide deck with decorative borders. Keep the edit editable, synchronize every visual beat to the spoken content, and verify the result from rendered pixels.

## Choose the execution path

Prefer an editable video editor over a flattened render.

- When ChatCut is available, use its skills in this order as needed: project basics, asset import, transcription, talking-head editing, motion-graphic creation, verification, and export.
- Use a design or image-generation tool only to prepare textures, cutouts, mascots, or decorative sticker assets. Do not treat it as the timeline editor.
- Place long screen recordings and camera footage as normal video items. Use motion graphics for frames, backgrounds, labels, connectors, and short embedded accents.
- Export only after the user approves the editable timeline or explicitly requests a render.

## Build the video

### 1. Lock the content model

Write a one-sentence thesis and a short fact sheet before editing.

Record:

- the viewer’s main question;
- the answer the video must leave behind;
- the entities, products, or concepts being introduced;
- the exact relationships among them;
- claims that require proof;
- names and capitalization that must remain exact.

Do not invent dates, slogans, metrics, labels, or relationships. Resolve ambiguity before drawing a diagram.

### 2. Analyze the reference

Extract a reusable visual grammar instead of copying isolated frames.

Identify:

- dominant and accent colors;
- paper, linen, print, grain, or aged-surface textures;
- cutout edge treatment;
- shadow direction and depth;
- typography roles;
- average visual density;
- how often the speaker appears;
- how stickers enter, sway, collide, connect, and exit;
- the rhythm between camera, screenshots, and visual-only scenes.

Turn these observations into a small style system. Keep it consistent throughout the video.

### 3. Inventory the assets

Create an asset map grouped by narrative beat, not merely by filename.

For every asset, note:

- what spoken claim it supports;
- whether it is a logo, screenshot, photograph, screen recording, cutout, texture, or proof;
- whether it is official and current;
- whether it must be shown completely;
- its safe crop and focal point;
- the minimum readable hold time;
- whether it should move or remain stable.

Use official vector logos whenever possible. Never regenerate a brand logo with AI or substitute a look-alike icon.

### 4. Transcribe before timing

Treat the spoken audio as the timing anchor.

- Generate or read the transcript.
- Locate the exact phrase that introduces every new topic.
- Anchor scene changes, overlays, and person appearances to those phrase timestamps.
- Keep a beat map containing phrase, start, end, scene type, supporting asset, and transition.
- Use timeline timestamps returned by the editor or transcript tool. Do not estimate timing from the script alone.

Preserve the original speech unless the user asks for a content cut. Do not use visual-edit tools to make transcript-based speech selections.

### 5. Build the narrative skeleton

Use this adaptable structure:

| Beat | Approximate share | Viewer job |
|---|---:|---|
| Hook | 0–8% | State the central promise or tension |
| Problem | 8–22% | Visualize the fragmented or difficult current state |
| Credibility | 22–35% | Show evidence, research, users, or results |
| Mechanism | 35–52% | Explain the foundational idea or architecture |
| Applications | 52–80% | Introduce products, features, or use cases one at a time |
| Relationship summary | 80–92% | Clarify hierarchy and connections |
| Close | 92–100% | Restate the takeaway and invite the next action |

Adjust proportions to the speech. Never force a beat that the narration does not contain.

### 6. Establish the timeline architecture

Use separate layers with clear responsibilities:

| Layer | Responsibility |
|---|---|
| V1 | Original camera or primary source video |
| A1 | Clean speech anchor |
| V2 | Full-frame backgrounds and major scene compositions |
| V3 | Speaker cutouts and foreground sticker accents |
| V4 | Screen recordings, demonstrations, and moving B-roll |
| V5 | Deliberate top-layer refinements or replacements |
| Captions | A single managed caption overlay when requested |

Use the top refinement layer sparingly for intentional replacements. Do not hide structural timeline mistakes under many overlapping patches.

### 7. Rotate among three scene modes

Avoid showing the speaker continuously.

1. **Speaker-led scene**  
   Place a complete speaker cutout beside one main visual. Use it for hooks, transitions, and high-emphasis claims.

2. **Visual-only sticker scene**  
   Let icons, photos, screenshots, and connectors interact without a person. Use it for systems, comparisons, and explanations.

3. **Demonstration scene with speaker accent**  
   Let a complete screenshot or screen recording dominate. Add a smaller speaker cutout only when it helps orientation or emphasis.

Change mode when the narration changes function, not on an arbitrary timer.

### 8. Construct the sticker visual system

Use a restrained shared language:

- bright brand-led background color;
- subtle aged paper, linen, fabric, ink, or print texture;
- warm cream paper instead of pure white;
- irregular cut-paper silhouettes;
- a clear white or cream sticker edge;
- one consistent offset shadow;
- one display typeface for short headings;
- one highly readable typeface for small labels;
- limited accent colors.

Treat sticker treatment as a foreground-system rule, not an occasional decoration:

- Except for an intentional full-frame background, every visible foreground element must read as a physical sticker, cut-paper object, taped fragment, or printed cutout.
- Apply this rule to people, person-backing circles or ovals, logos, mascots, screenshots, diagrams, nodes, labels, icons, connector marks, and decorative accents.
- Give every foreground object a visible material boundary. Use a warm-white cut edge, an opaque paper silhouette, a taped edge, or another style-consistent physical boundary.
- Separate foreground objects from the background with one consistent offset shadow. Do not rely on glow alone.
- Keep related pieces visually varied. “Everything is a sticker” does not mean placing everything inside the same rectangular card.

Use one of these treatments according to the object:

1. **Die-cut sticker**  
   Use the object’s natural silhouette, a cream or white cut edge, and an offset shadow. Prefer this for people, logos, mascots, and icons.

2. **Paper cutout**  
   Use an opaque paper surface, irregular cut edges, and an offset shadow. Prefer this for screenshots, proof, short titles, and diagrams.

3. **Printed or taped mark**  
   Give lines, arrows, underlines, and small accents a physical ink, tape, or cut-strip form. Do not leave generic vector strokes floating directly on the background.

The full-frame background may remain a continuous textured surface. Do not add a sticker border around the entire canvas unless the reference explicitly uses one.

Avoid notebook grids, generic presentation cards, and a single flat color with no material character.

Keep text scarce. Prefer:

- one short heading;
- one product or concept name;
- one proof label;
- one closing action.

Do not convert the narration into paragraphs of on-screen text.

### 9. Integrate the speaker correctly

Treat every person appearance as a designed scene, not a floating cutout.

- Use a complete, contiguous source segment that matches the active spoken phrase.
- Keep the full visible cutout inside the canvas with safe margins.
- Fit the person with `contain`; never stretch the body.
- Place an oval sticker, circular sticker, torn-paper field, or other physical backing object behind the person.
- Give the person and backing shape the same geometric center.
- Keep the backing shape visible for the entire person segment.
- Treat the person and backing as one compound foreground sticker that enters, holds, sways, and exits together.
- Make a circular or oval backing visibly separate from the full-frame background: use an opaque paper or printed surface, a clear warm-white cut edge, and a consistent right-down offset shadow.
- Do not use a flat colored ellipse, a thin outline, or a glow-only halo as the person backing.
- Preserve the backing’s sticker edge and shadow at every scale; reduce the person or backing together instead of allowing the edge to disappear.
- Maintain stable size and position across consecutive source slices.
- Leave enough time for the viewer to register the person; avoid one-second flashes.
- Keep the person away from product names, charts, controls, and meaningful screenshot regions.

Use a light entrance and exit. Do not make the person appear mid-word, disappear before the phrase ends, or jump between adjacent clips.

### 10. Integrate screenshots and recordings

Show evidence completely before stylizing it.

- Use `contain` when the application name, algorithm name, chart label, or UI context must remain visible.
- Preserve the screenshot’s aspect ratio.
- Place the complete image inside a paper cutout rather than cropping the source to create the torn edge.
- Hold complex proof long enough to read.
- Zoom only when the narration focuses on a specific detail.
- Use the real screen recording when motion is being described.
- Keep a recording on a stable video track and place the decorative sticker frame on another layer.

Do not embed long videos inside frequently remounted motion graphics; this can cause flashes or resets.

### 11. Draw relationships semantically

Decide the meaning before drawing the line.

- Use vertical position for hierarchy.
- Put foundations below the things built on them.
- Use branches for shared foundations.
- Use arrows only when direction, flow, or causality is explicitly meaningful.
- Connect only items with a real relationship.
- Give each node an image or recognizable mark, not merely a name.
- Keep labels short and adjacent to their node.

If a line requires explanation to understand why it exists, remove or redesign it.

### 12. Add motion with physical restraint

Make stickers feel lightly handled, not constantly animated.

Recommended motion ranges:

- sway: roughly 0.5–1.5 degrees;
- bob: roughly 2–6 pixels;
- drift: roughly 2–5 pixels;
- stagger: roughly 4–10 frames;
- entrance: a short spring or paper-drop motion;
- hold: mostly stable with a slow, low-amplitude loop;
- exit: a small slide, peel, or scale-down.

Animate related elements in sequence. Do not move every item at the same time.

Use motion to communicate:

- arrival;
- grouping;
- transfer;
- branching;
- emphasis;
- completion.

### 13. Synchronize and smooth boundaries

At every scene boundary:

- verify the phrase that starts the new idea;
- verify the visual starts on or just before that phrase;
- ensure the outgoing visual has finished its meaning;
- preserve speaker continuity;
- inspect the last frame before and first frames after the cut;
- avoid overlapping full-frame owners;
- avoid duplicate borders, logos, and background surfaces.

Use short visual transitions only when they improve continuity. A clean cut on a semantic beat is often better than a decorative transition.

## Review the video

Complete three separate review passes.

### Pass 1: meaning and timing

Verify:

- every scene supports the current spoken idea;
- no product, asset, or diagram appears before it is introduced;
- diagrams express the correct hierarchy;
- speaker appearances match the active phrase;
- proof remains visible long enough to understand.

### Pass 2: pixel and layout inspection

Render representative frames, including:

- the settled state of every scene;
- every scene boundary;
- the start, middle, and end of every person segment;
- complex screenshots;
- the final frame.

Inspect the actual pixels. Check:

- complete logos;
- undistorted marks and people;
- complete screenshots and visible names;
- consistent safe margins;
- person and backing-shape centering;
- visible sticker treatment on every non-background foreground element;
- person-backing circles and ovals with an opaque surface, cut edge, and offset shadow;
- connector lines and accents that look printed, taped, or cut rather than like unstyled vectors;
- no border collisions;
- no accidental debug outlines;
- no clipped titles;
- no placeholder or invented text;
- no excessive empty space or clutter.

### Pass 3: motion and playback

Play or render short ranges around:

- each video insert;
- each person entrance and exit;
- each source-slice boundary;
- each major transition;
- the ending.

Check for flashing, resets, frozen frames, sudden scale changes, audio drift, and one-frame artifacts. Still frames alone cannot prove motion quality.

Do not claim completion until all three passes succeed.

## Avoid these failure modes

- Building a presentation and adding sticker borders afterward.
- Filling the screen with subtitles disguised as design.
- Using text where an image, logo, screenshot, or physical metaphor would communicate faster.
- Cropping a screenshot so its identity or evidence disappears.
- Recreating official logos with rough vector shapes or AI generation.
- Distorting a mascot, person, logo, or screenshot to fit a card.
- Showing a speaker without a centered backing field.
- Drawing the person’s circle or oval directly onto the background instead of treating it as a separate sticker.
- Using only a thin outline or glow around a person backing, with no paper edge or offset shadow.
- Letting a backing field disappear while the speaker remains.
- Mixing finished sticker assets with flat, unstyled foreground vectors.
- Making speaker shots flash briefly or break continuity.
- Guessing audio timing instead of reading the transcript timestamps.
- Connecting unrelated assets because empty space invites a line.
- Using arrows without a defined direction or causal meaning.
- Showing a lower-level product as the foundation of its actual foundation.
- Stacking several borders around the same content.
- Letting decorative textures reduce readability.
- Animating every sticker continuously at the same amplitude.
- Using long embedded video inside a remounted motion graphic and causing flicker.
- Patching repeatedly without reviewing the entire timeline.
- Declaring success from tool metadata without inspecting rendered pixels.
- Exporting before the editable timeline is approved.
- Leaving temporary frames or generated files scattered in the user’s project folders.

## Delivery contract

Leave the user with:

- an editable timeline;
- organized and recognizable assets;
- no temporary review files in the user’s content folders;
- a concise summary of structural edits;
- the reviewed project link;
- an export only when requested.
