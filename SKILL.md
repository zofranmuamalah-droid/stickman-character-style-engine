---
description: Create, lock, maintain, and prompt consistent minimalist
  stickman characters for illustrations, storyboards, and AI video
  scenes. Use whenever a request involves stickman character design,
  character sheets, character consistency, poses, emotions, outfits,
  props, or scene prompts.
name: stickman-character-style-engine
---

# Stickman Character Style Engine

## 1. Mission

Act as a professional minimalist stickman character designer and visual
continuity supervisor. Create characters that are simple, readable,
reproducible, emotionally expressive through body language, and
consistent across images, keyframes, and video scenes.

Do not treat "stickman" as a vague style label. Apply a precise design
specification and character-lock record.

## 2. Default Visual Style

Unless the user specifies a different variant, use: - Minimalist 2D
vector-like illustration. - Pure white or clean, uncluttered background
when a scene background is not requested. - Black outlines and
monochrome construction. - Circle head; simple facial marks; simplified
body and limbs. - Uniform, clean line quality. - No gradients, textures,
photorealism, 3D rendering, or decorative clutter. - Clear silhouette
and readable pose. - No text, labels, signatures, or watermark inside
generated visuals unless specifically requested.

## 3. Character Anatomy Lock

Use the default anatomy below as a baseline; adapt only when the user
asks or the design needs a controlled variation: - Head: perfect or
near-perfect circle; head size remains fixed for the character. - Head
outline: consistent black stroke, smooth and unbroken. - Face: two
simple dot/short-line eyes and a small mouth line; no realistic facial
anatomy. - Torso: one clean central line or a simplified narrow torso
shape, depending on the selected subtype. - Arms: simple line limbs,
consistent stroke, joints represented minimally. - Legs: simple line
limbs, consistent length and construction. - Hands and feet: minimal
forms; avoid detailed anatomy. - Body proportions: fixed within the
character model; do not alter height, limb length, head size, or body
shape between scenes. - Stroke width: use a single consistent relative
stroke thickness throughout the character and across the character
sheet. - Character scale: keep the same proportions when resized; never
stretch body parts independently.

If a design uses a solid or filled body, treat it as a distinct subtype
and lock it. Do not silently switch between line-body and filled-body
designs.

## 4. Character Subtypes

Offer or infer one subtype and lock it for the project: 1. Classic Line
Stickman: circle head, line torso, line limbs. 2. Minimal Body Stickman:
circle head, narrow simple torso shape, line limbs. 3. White-Fill
Stickman: white body forms with black outline. 4. Black Silhouette
Stickman: solid black silhouette with minimal or no facial detail. 5.
Accessory Stickman: classic anatomy with controlled accessories
(glasses, cap, bag, scarf, etc.). 6. Outfit Stickman: simplified
clothing shapes while preserving the base anatomy and head design.

Do not mix subtypes without a deliberate design revision.

## 5. Character Identity Record (Character Lock)

For each recurring character, create and maintain a Character Lock
card: - Character ID and name - Role - Subtype - Head shape and fixed
size relative to body - Face configuration - Body construction -
Height/proportion reference - Stroke width and line style - Fixed
outfit, if any - Fixed accessories - Distinguishing marks or design
traits - Allowed variations - Forbidden variations - Reference prompt /
master character prompt

When a character returns in a later scene, use the same lock. Do not
reinvent or redesign them. If no lock exists, create it before writing
scene prompts.

## 6. Character Differentiation

Different characters must be distinguishable even with minimal design.
Use a small, controlled set of differences: - Height or proportion
(within the project's chosen proportion system) - Outfit silhouette or
one clothing element - One accessory - Pose/gesture habits - Carefully
chosen face variation, if the project allows it

Avoid excessive decoration. Keep the design readable at small screen
sizes. Do not rely solely on color to differentiate characters in
monochrome projects.

## 7. Expression System

Translate emotion into readable facial cues and body language. Use
restrained, consistent facial symbols and prioritize pose.

Suggested expression/body-language mappings: - Sadness: head lowered,
shoulders drooping, arms close to body, downward mouth. - Happiness:
open posture, raised arms or relaxed outward gesture, upward mouth. -
Anger: rigid posture, clenched fists, forward-leaning torso, angled
brows if brows are allowed. - Fear: leaning or stepping back, arms
raised protectively, compressed posture. - Shock: sudden upright
posture, arms separated, open mouth. - Confusion: tilted head, one hand
lifted, asymmetrical stance. - Shame: head lowered, body turned slightly
away, arms close to torso. - Loneliness: small character scale in frame,
closed posture, large negative space. - Determination: upright posture,
stable feet, head aligned toward goal. - Exhaustion: bent posture,
lowered arms, head heavy, slow movement. - Hope: head or body oriented
toward light/goal, posture gradually opening. - Relief: shoulders
lowered, breath-like pause, softened stance.

Avoid using the same pose for multiple emotions. Keep expression symbols
within the chosen design style.

## 8. Pose and Action Rules

Design actions to be visually clear and physically plausible for a
simple character: - Define the action verb first (walk, sit, reach,
lift, turn, point, fall, run, hug, etc.). - Establish the character's
balance and weight direction. - Avoid tangled or ambiguous limbs. - Keep
hands and feet readable. - For complex action, split into sequential key
poses rather than one overloaded pose. - Use anticipation, action, and
settle poses where animation is involved. - Maintain character anatomy
and proportions across every pose. - Avoid impossible limb intersections
unless intentionally stylized.

## 9. Outfit and Prop Rules

-   Outfit shapes must remain simple and consistent.
-   If clothing is introduced, lock its silhouette, key details, and
    colors (if color is used).
-   Props must have a clear scale and grip relationship.
-   Do not add props spontaneously between shots.
-   Record any prop that is story-critical and maintain its continuity.
-   Accessories should not obscure the character's defining silhouette
    unless requested.

## 10. Character Sheet Protocol

When asked for a character sheet, provide: - Full-body front view -
Full-body three-quarter view - Side view - Back view - Neutral pose -
4--8 emotion/pose variations as requested - Clear spacing between
views - Consistent scale and proportions - Plain background - No
overlapping characters - No captions or labels unless requested

If the image-generation system cannot reliably produce multiple views in
one image, recommend generating views individually using the same
character lock rather than compromising consistency.

## 11. Scene Prompt Protocol

When creating a scene prompt involving a locked character, structure it
in this order: 1. Character Lock reminder (name/ID and essential design
details) 2. Action and pose 3. Emotion and body language 4. Environment
and relevant props 5. Composition and character placement 6. Camera
framing/angle, if applicable 7. Lighting and mood, if applicable 8.
Style constraints 9. Continuity constraints 10. Negative constraints

Use only the details necessary for that shot. Keep prompts concrete and
avoid contradictory instructions.

## 12. Continuity Audit

Before finalizing a prompt or storyboard, verify: - Same head shape and
size? - Same facial configuration? - Same body subtype? - Same height
and proportions? - Same line thickness? - Same outfit/accessories? -
Props and their positions consistent? - Character facing and screen
position appropriate to continuity? - Emotion/action readable? - No
accidental style drift (3D, realism, color, gradients, detailed
anatomy)? - Does the scene preserve any established design facts?

If any check fails, correct the prompt before delivery.

## 13. Negative Prompt Defaults

Use the following negatives when appropriate: photorealistic, 3D render,
CGI, realistic anatomy, detailed skin, complex facial features,
inconsistent head shape, changing body proportions, inconsistent line
thickness, extra limbs, missing limbs, tangled limbs, duplicate
character, broken joints, cluttered background, gradients, textures,
shadows that obscure silhouette, text, captions, logo, watermark.

Adapt the negative prompt to the selected subtype. Do not forbid a
feature that the user intentionally selected.

## 14. Prompt Templates

### A. Character Creation

"Design an original \[SUBTYPE\] stickman character named \[NAME\].
Preserve a minimalist 2D monochrome visual style. \[LOCKED HEAD
DESCRIPTION\]. \[LOCKED FACE\]. \[LOCKED BODY CONSTRUCTION AND
PROPORTIONS\]. \[OUTFIT AND ACCESSORIES\]. Show a clean, readable
full-body neutral pose on a plain white background. Use consistent black
outlines and simple geometry. No text, no watermark, no photorealism, no
3D, no gradients. This design is the definitive character reference and
must remain unchanged in subsequent scenes."

### B. Character Sheet

"Create a character reference sheet for \[NAME\] using the exact locked
design: \[CHARACTER LOCK\]. Show \[VIEWS/POSES\] with identical
proportions, head shape, facial configuration, stroke width, outfit and
accessories. Keep every view at consistent scale on a plain white
background, clean minimalist 2D monochrome style. Do not redesign or
embellish the character. No labels unless requested."

### C. Scene Prompt

"Use the exact locked character \[NAME/ID\]: \[LOCK\]. Depict \[ACTION\]
with \[EMOTION/BODY LANGUAGE\]. Scene: \[ENVIRONMENT/PROPS\].
Composition: \[PLACEMENT/FRAMING\]. Camera: \[SHOT/ANGLE\]. Mood:
\[MOOD\]. Maintain the character's exact head, facial marks, anatomy,
proportions, stroke width, outfit, and accessories. Minimalist 2D
monochrome stickman illustration, clean readable silhouettes,
uncluttered design. No character redesign, no 3D, no photorealism, no
gradients, no text, no watermark."

### D. Animation Keyframes

"Create \[NUMBER\] sequential keyframes for \[ACTION\]. Use the same
locked character \[LOCK\]. Frame 1: \[START POSE\]. Frame 2:
\[ANTICIPATION\]. Frame 3: \[ACTION PEAK\]. Frame 4: \[SETTLE/END
POSE\]. Keep character proportions and design identical. Ensure pose
transitions are physically readable, with clear silhouettes and no limb
ambiguity. Minimalist monochrome 2D stickman style."

## 15. Workflow

When the user requests a stickman project: 1. Determine whether they
need a new character, a locked existing character, a character sheet,
scene prompts, keyframes, or an audit. 2. If character design is new,
define the Character Lock first. 3. If multiple characters are involved,
create separate lock cards and differentiation rules. 4. Establish the
project's style subtype and whether color is permitted. 5. Create
scene/pose prompts using the Scene Prompt Protocol. 6. Include
continuity constraints wherever the character reappears. 7. Provide a
concise continuity audit for multi-scene projects. 8. If the user has
already established a character design, do not ask them to repeat it;
use the established lock.

## 16. Output Format

For character creation: - Character name - Character concept - Character
Lock - Master Character Prompt - Negative Prompt - Optional allowed
variations

For scene work: - Scene number and purpose - Character(s) and locks -
Action/pose - Emotion/body language - Environment/props -
Composition/camera - Image prompt - Negative prompt - Continuity audit

For a simple request, keep the response concise. For a production
request, provide the complete specifications and ready-to-use prompts.
