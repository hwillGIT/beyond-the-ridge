# Control and Feedback Model

## Goal

The controls should make physical work, observation, and social response feel like one continuous play space.

Do not stop the game for a menu when the player can act in the world.

## Baseline controller map

| Input | Default action | Context behavior |
|---|---|---|
| Left stick | Move | Walk, position around work surfaces, steer when driving |
| Right stick | Camera | Look, inspect, track speakers, read hazards |
| South face button | Act | Use tool, open door, pick up item, confirm physical action |
| West face button | Inspect | Focus on material state, evidence, route detail, or body language |
| East face button | Step back | Cancel action, leave conversation, release tool, create distance |
| North face button | Speak | Ask, answer, call out, or interrupt when a response window exists |
| Left trigger | Attention hold | Slow camera slightly and emphasize nearby readable details without pausing time |
| Right trigger | Tool use | Apply the currently held tool or controlled machine input |
| Left bumper | Tool cycle | Move between immediately available tools |
| Right bumper | Recall | Surface a short contextual memory or observation when available |
| D-pad up | Paper map | Open the physical map |
| D-pad right | Field notebook | Open the evidence journal |
| D-pad down | Accessibility quick menu | Open subtitle, contrast, camera, and input assists |
| Menu button | Pause | Settings, save, quit, restart review checkpoint |

Keyboard and mouse mappings must provide the same functions.

All repeated or held inputs require remapping and hold-toggle alternatives.

## Interaction grammar

Use the same sequence across major activities:

```text
Approach -> Read -> Commit -> Adjust -> Observe result
```

### Approach

The player moves into a useful physical position.

Do not pull Mara into an invisible interaction rail from several meters away.

### Read

The player can inspect the relevant object, person, or route.

Readable information depends on context and capability.

### Commit

The player chooses an action through tool use, movement, speech, or deliberate silence.

### Adjust

The situation can change while the action is underway.

The player may need to stop, switch tools, reposition, answer someone, or abandon the task.

### Observe result

Show the immediate practical and social response before moving to the next objective.

## Attention mode

Attention mode supports close reading without becoming detective vision.

While held, it can:

- reduce camera sensitivity,
- quiet irrelevant ambient mix slightly,
- make nearby usable contact points easier to distinguish,
- keep the current speaker readable,
- and surface a short observation already available to Mara.

It must not:

- reveal hidden future consequences,
- outline every useful object,
- identify the correct answer,
- or freeze active hazards.

## Tool use

Tools behave like physical objects.

A wrench, chalk, flashlight, radio, herb jar, notebook, or map should remain visible when practical.

The player should not manage a large inventory grid in the prototype.

Use a small context tool set tied to the current work area or carried kit.

## Conversation during activity

Conversation should not automatically lock player movement.

Use three response types:

### Immediate response

A short response window appears when timing matters.

Examples include calling out a hazard or answering a direct question.

### Deferred response

The player can finish a physical action before answering.

The character may react to the delay.

### Behavioral response

The player's action communicates an answer.

Examples include stopping a machine, continuing work, handing over a tool, leaving the room, or making a phone call.

## Dialogue presentation

When a choice is necessary, show short intent phrases rather than complete speeches.

Examples:

- Ask what changed.
- Defend the repair.
- Joke it away.
- Say only part.
- Stay quiet.
- Leave.

Do not display relationship-point outcomes beside an intent.

## Hazard feedback

A hazard should communicate through ordinary cues first.

Use:

- sound change,
- vibration,
- object motion,
- chain tension,
- material deformation,
- character gaze,
- dust or fluid movement,
- and machine rhythm.

Accessibility options can add stronger contrast, direction, vibration, or timing support.

Do not require perfect hearing, color vision, or reaction speed.

## Relationship feedback

Never show `Trust +5` or an equivalent score.

Use consequences such as:

- a person offers help,
- a person refuses access,
- a private name or nickname changes,
- a character repeats or withholds information,
- eye contact changes,
- physical distance changes,
- a door remains open or closes,
- a later conversation starts differently.

## Evidence feedback

The field notebook uses physical grouping and revision.

The player can see:

- what Mara observed,
- what another person claimed,
- what Mara concluded,
- which conclusion changed,
- and what remains unresolved.

The journal should never celebrate uncertainty as failure.

## Navigation feedback

Use roads, landmarks, shop fronts, church architecture, ridgelines, traffic patterns, and repeated routes.

The paper map can add handwritten marks as Mara learns the area.

Optional accessibility settings can add a compass or stronger route guidance.

The default presentation should not depend on a minimap.

## Camera rules

### Work

Keep the camera close enough to read hand placement, material contact, and hazards.

### Dialogue

Do not force shot-reverse-shot editing during active tasks.

Let the player choose whether to look at the speaker.

### Travel

Preserve road visibility before cinematic framing.

### Home

Use wider two-person or family compositions when silence, power, or divided attention matters.

### Reflection

Use slower camera movement and more negative space.

Do not use sepia or dream blur as a universal memory effect.

## Feedback priority

When several signals compete, use this priority:

1. Immediate safety information.
2. Current physical action.
3. Speaker and social response.
4. Objective context.
5. Optional interpretive detail.

A stylish presentation must not hide a higher-priority signal.

## Youth readability test

A reviewer should be able to answer these questions without reading this file:

- What can I do here?
- What is changing right now?
- Who is reacting to me?
- What could I try instead?
- What changed because of what I did?

If the interface must explain these answers after the scene, redesign the interaction before adding more text.
