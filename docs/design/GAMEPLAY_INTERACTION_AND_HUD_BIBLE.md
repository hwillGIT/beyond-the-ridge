# Gameplay Interaction and HUD Bible

## Status

This document defines the player interaction contract for *Beyond the Ridge*.

It does not describe an implemented engine build.

The project uses this contract to judge gameplay keyframes, trailers, animatics, prototypes, and future builds.

## Player promise

The player controls Mara during work, travel, conversation, investigation, care, and reflection.

The game does not separate physical action from human consequence.

A player should understand four things in each active scene:

1. What Mara is trying to do.
2. What Mara can do now.
3. What pressure changes the decision.
4. What changed because of the action.

A frame that shows only atmosphere is concept art.

A frame that shows a task, controls, alternatives, pressure, and feedback is gameplay previsualization.

## Core loop

```text
Notice -> Choose -> Act -> Interpret -> Return
```

### Notice

Read a machine, room, road, person, sound, record, or contradiction.

### Choose

Select an approach. Decide whom to involve. Decide which risk to accept.

### Act

Perform the work. Timing, preparation, skill, tools, and attention matter.

### Interpret

State, revise, or withhold what Mara thinks happened.

### Return

Home and community respond. Access, pressure, trust, and later retellings change.

## Interaction principles

### One control has one stable meaning

A button can support different contextual actions. Its meaning must stay stable.

- **Engage** starts or confirms an interaction.
- **Examine** reads or manipulates the target.
- **Communicate** addresses another person.
- **Disengage** releases, stops, withdraws, or leaves.
- **Brace** steadies Mara, a tool, a load, or a vehicle.
- **Perform** applies the primary physical action.
- **Alternate** tests, measures, changes grip, or uses a secondary technique.

### The world does not pause for every choice

Characters continue to eat, work, move, and speak.

The player can keep working while listening.

The player can stop work and give full attention.

The game records that difference.

### The interface shows known information

The interface can show what Mara has observed or learned.

It does not reveal unknown future consequences.

The interface can say:

> Crack widens during rotation.

It must not say:

> This choice causes a later injury.

### Safety remains playable

Refusal, outside help, de-escalation, and leaving must continue the story.

The game never requires repeated harm for mastery.

### People are not score targets

The game does not score obedience, faith, family loyalty, trauma, or medical choices.

Mechanical work can receive mastery feedback.

Relationships use qualitative state and multi-axis records.

## Proposed controller contract

The final prototype can revise button assignments after usability tests.

The meanings below remain stable.

| Input | Keyboard and mouse | Stable meaning | Examples |
|---|---|---|---|
| Left stick | WASD | Move | Walk, climb position, steer |
| Left-stick click | Shift | Increase pace | Jog, sprint, faster movement |
| Right stick | Mouse | Look and direct attention | Track cable, watch speaker, scan road |
| Right-stick click | Q | Attention focus | Listen closely, inspect sound, study wear |
| A | E | Engage | Pick up, open, climb, sit, speak, confirm |
| X | F | Examine or manipulate | Rotate hub, inspect wound, read notice |
| Y | C | Communicate | Ask, warn, call out, request help |
| B | Escape | Disengage | Release, step back, stay silent, leave |
| Left trigger | Right mouse | Brace or focus | Hold part, steady hands, prepare grip |
| Right trigger | Left mouse | Perform | Apply force, cut, prepare, accelerate |
| Left bumper | Tab | Tool or supply wheel | Tools, herbs, camera, notebook |
| Right bumper | R | Alternate or test | Measure, verify, change grip |
| D-pad up | J | Journal | Saw, Heard, Concluded, Revised |
| D-pad left and right | 1 through 4 | Quick tools | Wrench, chalk, flashlight, notebook |
| D-pad down | M | Route and objective | Current task, known routes, source notes |

## Player action vocabulary

### Movement and traversal

The player can:

- Walk, jog, and sprint.
- Climb ladders, roofs, rock faces, and industrial structures.
- Balance across unstable surfaces.
- Duck, crawl, brace, and step away.
- Carry, drag, lift, and hand off objects.
- Mount and ride a horse.
- Drive trucks and cars.
- Select safe, fast, known, or unexplored routes.
- Navigate with landmarks, weather, local directions, and annotated maps.

### Work and repair

The work loop is:

```text
Diagnose -> Plan -> Prepare -> Perform -> Verify
```

The player can:

- Inspect wear, heat, alignment, sound, material, and load.
- Rotate or move a component to expose a fault.
- Compare the object with a manual or diagram.
- Select a tool.
- Brace a component.
- Loosen, tighten, cut, clamp, measure, clean, weld, or replace.
- Improvise with available material.
- Ask another person to hold, lift, watch, or advise.
- Test the completed work.
- Stop the job when conditions are unsafe.

### Observation and investigation

The player can:

- Look at a person, object, road, machine, sign, or trace.
- Listen while continuing another activity.
- Stop and give full attention.
- Inspect physical evidence.
- Compare witness accounts.
- Examine receipts, notes, maps, books, records, and manuals.
- Mark an object or location.
- Preserve or disturb evidence.
- Revisit an earlier conclusion.
- Name uncertainty.

### Conversation

The player chooses intent before exact wording.

Available intents include:

- Ask.
- Challenge.
- Appeal.
- Offer evidence.
- Join the joke.
- Correct one detail.
- Deflect.
- Stay silent.
- Leave.

Exact dialogue depends on knowledge, relationship state, emotional state, and context.

### Care

The player can:

- Inspect an injury.
- Check symptoms.
- Ask the patient what happened.
- Gather supplies.
- Prepare a remedy.
- Stabilize the patient.
- Monitor change.
- Call a clinic or emergency service.
- Arrange transport.
- Wait and observe.
- Challenge another person’s certainty.

### Evidence and memory

The journal has four layers.

- **Saw:** Direct observation and physical traces.
- **Heard:** Testimony, rumor, teaching, or accusation.
- **Concluded:** Mara’s current interpretation.
- **Revised:** A new conclusion that preserves the earlier trace.

The journal does not provide an omniscient reconstruction.

## HUD architecture

The HUD uses three density levels.

### Low density

Use low density during exploration, arrival, discovery, and emotional reflection.

Visible elements can include:

- A short objective.
- A nearby contextual prompt.
- A subtle physical-state warning.
- A route or journal notification.

### Contextual density

Use contextual density during driving, conversation, town activity, meals, and routine work.

Visible elements can include:

- Objective and time pressure.
- Contextual verbs.
- Conversation intents.
- Active route or social information.
- A subtle tool or inventory state.

### Full interaction density

Use full density during repair, dynamic danger, care, and journal analysis.

Visible elements can include:

- Objective.
- Tool state.
- Material state.
- Known facts.
- Risk state.
- Available actions.
- Timing or balance feedback.
- Verification state.

## HUD zones

### Top left: objective and pressure

Example:

```text
MAKE THE TRUCK SAFE FOR THE QUARRY RUN
Load expected before 10:30
```

The objective fades after the player understands it.

It returns when the situation changes.

### Lower left: physical state

Show only relevant conditions.

- Fatigue.
- Cold or heat.
- Injury.
- Breath.
- Balance.
- Carried weight.

### Lower right: tool and material state

Show:

- Equipped tool.
- Alternate tool.
- Brace state.
- Relevant material.
- Wear state.
- Test state.
- Remaining consumables.

### Center: contextual verbs

Prompts appear near the active object.

```text
X  INSPECT
LT BRACE
RT LOOSEN
Y  ASK ELI
B  STOP WORK
```

### Right side: known facts

Show only facts Mara can support.

```text
KNOWN
• Hub moves under load
• Crack widens during rotation
• Replacement part may be available in Cedar Gate
```

### Bottom center: conversation intent

Example:

```text
ASK WHY    OFFER PROOF    DEFLECT    STAY SILENT
```

The player can continue moving or working while these choices remain available.

### Journal notification

Use a short message.

```text
New testimony added to HEARD
```

Do not force the journal open.

## Challenge design

### Mechanical challenge

The player must understand:

- What the object should do.
- What condition it is in.
- Which parts carry load.
- Which tool fits.
- What can be improvised.
- How to verify the result.

### Environmental challenge

Hazards include:

- Suspended loads.
- Unstable scrap.
- Failing cables.
- Hot metal.
- Powered machinery.
- Poor visibility.
- Black ice.
- Storms.
- Damaged roads.
- Fatigue.
- Low fuel.
- Missing safety equipment.

### Time and scarcity challenge

Pressure can include:

- A deadline.
- Limited daylight.
- One usable replacement part.
- Low fuel.
- A worsening storm.
- An unfinished promise.
- A person demanding a faster method.

### Social challenge

A correct technical action can create a social cost.

Examples:

- Protective equipment reduces risk but signals distrust.
- Outside help exposes private information.
- A public correction protects one person and threatens another.
- Silence preserves access and hardens a false account.
- Accepting help creates intimacy or dependence.

### Interpretive challenge

The player can hold physical evidence, conflicting testimony, rumor, and an earlier conclusion at the same time.

The challenge is to decide what Mara can responsibly claim.

## Feedback and scoring

### No global morality score

The game does not use a good and evil meter.

It tracks factual outcomes, capabilities, relationships, evidence, access, promises, and consequences.

### Practical outcome state

| Dimension | Possible states |
|---|---|
| Condition | Unsafe, temporary, serviceable, reliable |
| Verification | Untested, partly tested, confirmed |
| Safety | Exposed, reduced risk, protected |
| Time | Early, on schedule, delayed |
| Resources | Conserved, used, depleted |
| Evidence | Preserved, altered, lost |

### Capability progression

Generic XP is replaced by demonstrated competence.

| Capability | Growth verbs |
|---|---|
| Repair | Diagnose, prepare, perform, verify |
| Fieldcraft | Navigate, track, read weather, ride |
| Care | Triage, stabilize, craft, refer |
| Research | Locate, compare, cite, revise |
| Performance | Rehearse, time, project, ensemble |
| Voice | Ask, challenge, explain, set a boundary |

Progress changes available verbs, speed, reliability, and information quality.

It does not increase damage numbers.

### Relationship state

Relationships track:

- Trust.
- Respect.
- Fear.
- Dependence.
- Clarity.

The player sees qualitative summaries.

Examples:

- Abel respects your mechanical judgment.
- Eliza believes you noticed the moved chalk mark.
- Ruth depends on your help but avoids the clinic question.
- Caleb understands why you changed the subject.

### Evidence state

Evidence can be:

- Supported.
- Disputed.
- Incomplete.
- Unverified.
- Contradicted.
- Revised.

### Map and access state

Progress also appears through:

- New routes.
- New buildings.
- New institutional access.
- Maps annotated by different people.
- Tools and vehicles.
- Rooms that open or close.
- Invitations.
- Promises fulfilled or broken.
- Characters who will accompany Mara.

### Optional work mastery

Mechanical, traversal, and exploration challenges can use a work-only mastery summary.

| Measure | Range |
|---|---|
| Precision | 0 to 3 marks |
| Safety | 0 to 3 marks |
| Resourcefulness | 0 to 3 marks |
| Verification | 0 to 3 marks |

Work mastery can unlock techniques, optional challenges, alternate animations, and tool familiarity.

It must not score belief, obedience, trauma, loyalty, or medical choices.

## Failure and recovery

Failure changes the situation.

It does not normally erase the scene.

Possible changes include:

- A tool breaks.
- Weather advances.
- The task takes longer.
- A repair becomes temporary.
- Someone intervenes.
- An injury becomes more serious.
- A relationship changes.
- Evidence is lost.
- Mara must accept help.

Recovery can require care, time, repair, a new route, or outside assistance.

## Example interaction: The Hairline Crack

### Initial state

```text
OBJECTIVE
Make the truck safe enough for the quarry run.

KNOWN
• Hub wobbles during rotation
• Abel expects the truck before 10:30
• One replacement bearing remains in storage

TOOLS
Socket set | Chalk | Jack | Service manual

ACTIONS
X Inspect       LB Tool Roll
LT Brace        RT Loosen
Y Ask Eli       B Stop Work
```

### Careful diagnosis

The player can:

1. Chalk the suspected crack.
2. Rotate the hub.
3. Compare movement.
4. Check the manual.
5. Ask Eli to watch the line.
6. Identify the failed component.
7. Install or source a replacement.
8. Verify the repair under controlled load.

Possible effects:

- Reliable repair.
- Delayed departure.
- Increased repair capability.
- Increased respect from Abel.
- Increased tension about the delay.
- Preserved evidence of earlier wear.

### Fast improvisation

The player can skip the manual and use a temporary part.

Possible effects:

- Temporary repair.
- Early departure.
- Immediate approval.
- Increased future wear.
- A later breakdown that provides new evidence.

### Shared work

The player can ask Eli, Jonah, Caleb, or another available person to help.

Possible effects:

- A different technical solution.
- A changed relationship state.
- Another witness who knows what happened.
- Reduced family control over the later account.

### Stop the job

The player can refuse to continue under an unsafe load.

Possible effects:

- Reduced immediate risk.
- Conflict with Abel.
- Missed deadline.
- A new route to parts or outside help.
- Continued story access.

### Dynamic interruption

When the chain moves, the HUD changes.

```text
LOAD SHIFTING

RT STABILIZE
X  CUT POWER
A  PULL ELI CLEAR
Y  WARN ABEL
B  MOVE BACK
```

Earlier preparation changes reaction time and available actions.

- Gloves improve grip.
- An extra cable enables a second stabilization action.
- Missing protection reduces reaction time.
- Eli’s assigned position changes rescue distance.
- Earlier chain inspection gives a longer warning.

## Gameplay keyframe contract

The project uses 12 revised gameplay keyframes.

| Keyframe | Required gameplay evidence | HUD density |
|---|---|---|
| Ridge Dawn | Objective, movement, camera, ladder prompt, known locations | Low |
| Breakfast Pressure | Player gaze, overlapping dialogue, four intents | Contextual |
| Hairline Crack | Tool wheel, socket, brace, torque, known risk | Full |
| Suspended Load | Emergency actions, hazard, timing, partner location | Full |
| Mercy House | Symptoms, supplies, patient action, clinic option | Full |
| County Road | Driving, road condition, route, CB interaction | Contextual |
| Cedar Gate | Store choice, parts, rumor, Heard update | Contextual |
| Supper Version | Join, Correct, Ask, Leave with live action | Contextual |
| Memory Journal | Saw, Heard, Concluded, Revised | Full |
| Ridge Signal | Equipment, weather, fatigue, route, triangulation | Low |
| College Threshold | Navigation, schedule, unknown rule, ask or observe | Contextual |
| Wider World | Capabilities, map growth, access, next objective | Low |

## Keyframe acceptance gates

A keyframe passes only when a viewer can identify:

- The current task.
- The controlled character.
- The active tool or capability.
- At least two possible actions.
- The pressure or risk.
- One visible consequence or state change.

A keyframe fails when:

- It reads only as a movie still.
- The interface exposes unknown consequences.
- The player has one meaningful action.
- The HUD covers the human performance.
- The UI uses unexplained meters.
- The frame uses a morality score.
- A refusal or safety choice ends the story.

## Accessibility contract

The prototype must support:

- Adjustable text size.
- Complete subtitles.
- Speaker names.
- High-contrast prompts.
- Remappable inputs.
- Hold, tap, and toggle options.
- Simplified timing.
- Reduced motion.
- Camera sensitivity controls.
- Advance content notices.
- Fade-to-black options.
- No requirement to repeat harm for mastery.

## Next production gate

The next visual pass must create four full-UI gameplay frames:

1. Hairline Crack.
2. Suspended Load.
3. Mercy House.
4. Memory Journal.

These frames establish the control language before the project revises the remaining eight keyframes.
