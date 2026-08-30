# Redemption Windows and Second Roads Bible

## Status

This document defines the Persistence System for *Beyond the Ridge*.

The system applies after major loss, dark endings, and selected campaign defeats.

It does not describe an implemented engine build.

## Purpose

A loss can close the road that the player chose.

The game can still preserve a smaller form of agency.

The Persistence System lets the player discover that remaining agency through attention, memory, relationship, skill, place, or grace.

The system never erases the original loss.

It offers a second road, not a hidden undo.

## System promise

> You can lose the road that you chose without losing every possible road.

The system supports four ideas.

1. Loss remains real.
2. Attention can reveal what survived.
3. Recovery requires a cost.
4. Hope can change form.

The design does not equate persistence with remaining in danger.

Leaving, surrendering, calling for help, changing a goal, or setting a boundary can express persistence.

The deeper rule is:

> Do not give up on the capacity to choose again.

## Definitions

### Persistence System

The Persistence System manages hidden continuation opportunities after selected losses.

It reads the saved world state and determines whether a credible second road remains.

### Redemption Window

A Redemption Window is a limited period in a final scene when player control quietly remains.

The interface does not announce the window.

The player can linger, look, listen, approach, examine, remember, or leave.

### Second Road

A Second Road is a new recovery arc that begins after the player activates a Redemption Window.

The road can restore agency without restoring the original goal.

### Redemption Seed

A Redemption Seed is a person, object, place, record, capability, relationship, or act of grace that can support a Second Road.

A seed must have a causal place in the world.

### Apparent Ending

An Apparent Ending is a complete and valid losing ending.

The player may accept it without activating a Redemption Window.

### Legacy Chapter

A Legacy Chapter continues through another character after Mara dies in a permadeath mode.

Mara remains dead.

Her work, record, or relationships can still affect the world.

## Relationship to the loss architecture

The game uses three loss layers.

### Encounter defeat

An encounter defeat ends the immediate attempt.

Standard modes usually reload a checkpoint.

A Redemption Window is not required because the encounter can restart.

### Persistent defeat

A persistent defeat autosaves.

Examples include injury, lost equipment, failed education, severed relationships, lost contracts, location bans, or wrongful accusations.

Persistent defeats are the primary home of the Persistence System.

### Campaign loss

A campaign loss ends the current playthrough.

A campaign loss can still contain one optional final Redemption Window.

Iron Ridge death can use a Legacy Chapter instead of resurrection.

## Core persistence loop

```text
Lose -> Linger -> Notice -> Reach -> Accept the cost -> Repair what remains -> Choose a second road
```

### Lose

The game shows the consequence in full.

The player does not receive an immediate consolation prompt.

### Linger

The final scene remains interactive after the apparent ending settles.

The player can leave and accept the ending.

### Notice

The player detects a seed through ordinary attention.

The seed is not decorated as loot or a quest marker.

### Reach

The player approaches, examines, calls out, listens, remembers, or asks for help.

### Accept the cost

The Second Road requires a meaningful cost.

Possible costs include confession, restitution, service, delay, public vulnerability, dependency, lost status, changed goals, or firm boundaries.

### Repair what remains

The player identifies what can still change.

Some losses cannot change.

### Choose a second road

The player commits to a new path.

The path can succeed, fail, or remain unfinished.

## Design laws

### The original loss remains canon

A Second Road never rewinds the loss.

A lost contract remains lost.

A death remains a death.

An injury remains part of the body state.

A public accusation remains in the record until the player changes the record through play.

### A Second Road is not the true ending

The apparent ending remains valid.

The hidden continuation is another possibility.

The game does not shame a player who accepts the first ending.

### The seed must exist before the ending

A shadow character must appear at least twice before activation.

An object must have a prior practical or emotional use.

A place must already belong to the world.

An institution must have a visible rule or seam that supports the new path.

### The seed must support the new road

A seed cannot exist only as visual poetry.

It must provide access, knowledge, testimony, equipment, shelter, training, transport, employment, or another credible resource.

### Recovery requires work

The new road starts a playable arc.

It does not display a final sentence that promises future success.

### The Second Road can fail

The player can reject accountability, lose the appeal, exhaust resources, damage the new relationship, or abandon the recovery.

A second chance is not immunity.

### Safety never disqualifies redemption

Calling for help, leaving danger, de-escalating, using accessibility options, or refusing abuse cannot close a Persistence System path.

### Abuse is not redeemed through victim labor

The system does not require Mara to restore an abusive relationship.

A character who caused harm cannot receive a redemption arc by demanding more care from Mara.

Mara can build a second road without reconciliation.

### Hope can change the goal

Persistence does not always restore the former plan.

An injury can lead to design or teaching instead of heavy repair.

A lost scholarship can lead to another institution, paid work, or a different vocation.

A destroyed family business can lead to a safer cooperative.

## Eligibility contract

The Persistence System evaluates a losing state at the final-scene checkpoint.

A Redemption Window can become eligible when all required conditions pass.

### Required conditions

- The loss is stable and saved.
- The seed has prior world evidence.
- The seed survives the loss.
- The Second Road differs from a simple retry.
- The recovery cost is meaningful.
- The original consequence remains visible.
- The new path preserves player agency.
- The path passes content-care and rights review.

### Optional conditions

- A minor character remembers Mara.
- The player preserved evidence.
- The player repaired or returned an object.
- A relationship contains trust, respect, clarity, or unresolved care.
- A capability can transfer to a new use.
- An institution contains an appeal, job, waiver, night shift, or alternate route.
- Another character freely offers help.

### Disqualifying conditions

- The path requires Mara to return to active abuse.
- The path erases a death or permanent injury.
- The seed appears only in the final scene.
- The activation depends on an inaccessible visual detail alone.
- The continuation functions as a disguised reload.
- The game labels the first ending as invalid.
- The path rewards harmful endurance.

## State machine

```text
DORMANT
  -> FORESHADOWED
  -> ELIGIBLE
  -> PRESENT IN FINAL SCENE
  -> NOTICED
  -> ACTIVATED
  -> ACCEPTED or DECLINED
  -> SECOND ROAD ACTIVE
  -> RECOVERY, TRANSFORMATION, LEGACY, or SECOND LOSS
```

### Dormant

The seed exists in the world but has not gained narrative meaning.

### Foreshadowed

The player sees or hears the seed during normal play.

### Eligible

The final saved state contains the required causal links.

### Present in final scene

The seed appears without a quest marker.

### Noticed

The player maintains attention or performs a related action.

### Activated

The game reveals one stable contextual verb.

### Accepted or declined

The player starts the Second Road or accepts the apparent ending.

### Second Road active

A new objective chain begins in the changed world state.

### Outcome

The new road can produce recovery, transformation, legacy, or another loss.

## Redemption Seed categories

### Shadow character

A minor character remains near the edge of the final scene.

The character has prior behavior, work, and values.

Examples include a stagehand, clerk, custodian, mechanic, librarian, driver, nurse, or church volunteer.

### Undecorated object

An ordinary object survives.

Examples include a receipt, carbon copy, cassette, map, timetable, tool, letter, photograph, library card, or blank page.

### Unfinished place

A place appears closed but still contains access.

Examples include a side door, basement, archive annex, workshop bay, maintenance entrance, ranger station, or repeater shed.

### Preserved truth

A trace remains after the public story closes.

Examples include a duplicate transcript, photograph, radio recording, marked cable, witness note, copied record, or earlier journal version.

### Transformed capability

A skill survives even when its original use is lost.

Repair can become design, inspection, teaching, stagecraft, or safety work.

Performance can become writing, directing, teaching, or community work.

### Legacy carrier

Another character receives Mara's record or unfinished work after her death.

The carrier can act on the legacy without replacing Mara.

### Returned favor

A person helps because Mara previously offered labor, dignity, repair, shelter, or truth.

The response remains causal but does not become a visible kindness score.

### Unearned grace

A character freely offers help because that choice fits the character's values.

The player did not purchase the help through hidden virtue points.

### Institutional seam

A rule contains a lawful alternate route.

Examples include an appeal, night position, tuition waiver, public defender, transfer course, restricted permit, supervised access, or community-service agreement.

## Dwell-focus activation

The default activation uses the existing attention control.

The player aims the camera at the seed and holds focus.

The default dwell time is 15 seconds.

The timer stays hidden.

### Feedback sequence

#### 0 to 5 seconds

The scene remains ordinary.

The credits, ambient action, or final music can continue.

#### 5 to 9 seconds

The seed gives a small response.

A person looks back.

A page moves.

A light turns on.

A radio catches one syllable.

#### 9 to 13 seconds

The sound mix narrows.

The seed becomes easier to distinguish.

A background character changes posture or enters partial light.

#### 13 to 15 seconds

One contextual verb appears.

Examples include:

- Examine.
- Approach.
- Call out.
- Recall.
- Listen.
- Open.

The game never displays a redemption label.

### Focus tolerance

The focus zone includes a small margin.

The timer decays slowly when the camera slips away.

It does not reset immediately.

The player can move closer while maintaining progress.

### Alternate activation verbs

Not every window uses visual focus.

A seed can activate through:

- listening to a repeated sound,
- following a person,
- returning to a place,
- opening the journal,
- tuning a radio,
- reading the reverse of a document,
- waiting through silence,
- or choosing not to leave.

## Hiddenness levels

### Level 1: visible continuation

The seed remains easy to notice.

Use this level in Story mode and for early Persistence System teaching.

### Level 2: contextual continuation

The seed appears in a normal composition with one audio or motion cue.

This level is the default.

### Level 3: deep continuation

The seed requires memory, place knowledge, or a transferred capability.

Use this level for optional late-game windows and Iron Ridge legacy paths.

A deep continuation cannot depend on unreadable microtext or a single color cue.

## Accessibility contract

The player can adjust:

- dwell time at 3, 8, or 15 seconds,
- hold or toggle focus,
- focus-zone size,
- timer decay rate,
- sound-direction cues,
- controller vibration,
- subtle contrast support,
- subtitle detail,
- and Persistent Discovery Cues.

Persistent Discovery Cues strengthen ordinary world feedback.

They do not place a redemption icon over the seed.

The player can replay the final scene from the Ending Archive.

The system does not require a frame-perfect input.

## Save and replay contract

The game creates a final-scene checkpoint before the Apparent Ending.

The loss state remains locked in that checkpoint.

Activating a Second Road creates a new branch save.

The Ending Archive stores:

- the apparent ending,
- the activated window,
- the Second Road start,
- and any later Second Road ending.

The player can revisit the apparent ending without overwriting the continued branch.

Iron Ridge mode preserves its selected permadeath rule.

A Legacy Chapter cannot restore the dead campaign character.

## Recovery cost categories

### Confession

Mara admits that she overstated, hid, or misunderstood something.

### Restitution

Mara repairs practical harm, returns property, pays a debt, or supports the harmed person.

### Service

Mara accepts difficult work that builds access or trust.

### Delay

The new path takes longer than the original plan.

### Lost status

Mara gives up reputation, rank, a role, or public certainty.

### Dependency

Mara accepts help, instruction, supervision, or shared control.

### Public vulnerability

Mara speaks before people who may reject the correction.

### Boundary setting

Mara protects the new road by refusing harmful access or contact.

### Goal transformation

Mara stops trying to restore the original path and builds another one.

## Earned grace and unearned grace

The system supports both causal reciprocity and free help.

### Earned causal seed

A prior action creates a credible return.

Examples include repairing a bus, preserving a record, helping a stagehand, returning a tool, or treating a minor character with dignity.

### Unearned grace

A character offers help because service, mercy, fairness, or courage belongs to that character's worldview.

The offer does not require a hidden kindness threshold.

The player still decides whether to accept the help and its cost.

## World-state persistence

A Second Road begins inside the changed world.

The system carries forward:

- injuries,
- deaths,
- lost assets,
- debt,
- weather and season,
- evidence state,
- official records,
- location bans,
- family accounts,
- community standing,
- promises,
- and relationship dimensions.

The new arc can add access, tools, allies, skills, testimony, or another institution.

It cannot silently restore deleted state.

## UI and presentation rules

### No redemption meter

The player never sees a hope bar, persistence score, or second-chance percentage.

### No decorated seed

The seed has no glow, rarity frame, floating icon, or loot sound.

### One stable prompt

After activation, the interface shows one normal contextual verb.

### Fact-based summaries

A Second Road start screen can state known facts.

Example:

```text
A SECOND ROUTE IS AVAILABLE

Changed
- Quarry contract remains lost
- Vale truck remains destroyed
- Tess has access to a night garage bay
- Mara still has the failed repair diagram

Choose
- Approach Tess
- Leave the yard
```

The heading can be removed in deep hiddenness modes.

The game does not promise success.

### Credits behavior

Credits can begin while limited camera control remains.

Moving, focusing, or approaching pauses credit acceleration but does not stop ambient action.

The player can skip to the complete apparent ending at any time.

## Audio and visual grammar

### Visual cues

Use:

- a person moving from shadow into partial light,
- an ordinary object catching natural light,
- a door opening for practical reasons,
- a page turning in wind,
- a hand stopping over an object,
- an unfinished action,
- or a repeated route detail.

Do not use:

- magical glow,
- fantasy particles,
- a redemption color,
- a halo effect,
- or a camera that points at the answer.

### Audio cues

Use:

- a tool sound from an earlier scene,
- a radio call sign,
- a bus brake,
- a piano phrase,
- a page scrape,
- a remembered nickname,
- a door latch,
- or a voice that was previously background sound.

The cue should belong to the world.

## Moral and content-care grammar

The system uses five moral distinctions.

### Hope without cheap reversal

The loss remains.

### Persistence without denial

Mara names the damage before she acts again.

### Grace without transaction

Help can arrive without a hidden virtue purchase.

### Repentance without guaranteed forgiveness

A correction can be right even when another person does not forgive Mara.

### Legacy without resurrection

A dead character can influence the world without returning.

## Example Second Roads

### Night Shift

**Loss:** The quarry contract and family truck are lost.

**Apparent ending:** The salvage yard begins an auction.

**Seed:** Tess loads a portable welding unit and studies Mara's repair diagram.

**Activation:** Focus on Tess or the diagram.

**Second Road:** Open an unused garage bay for small night repairs.

**Cost:** Start without family tools, credit, or approval.

**Irreversible loss:** The quarry contract remains gone.

### The Second Record

**Loss:** Mara makes an accusation that harms an innocent person.

**Apparent ending:** The official record closes.

**Seed:** A courthouse clerk saves a carbon copy with different wording.

**Activation:** Focus on the clerk or discarded copy.

**Second Road:** Correct the record through confession, evidence, and public restitution.

**Cost:** Mara loses credibility and may face discipline.

**Irreversible loss:** The harmed person may never forgive her.

### The Late Form

**Loss:** Mara loses a scholarship or misses an academic deadline.

**Apparent ending:** The registrar closes and the campus empties.

**Seed:** A custodian uncovers a night job with a tuition waiver.

**Activation:** Watch the custodian or read the uncovered notice.

**Second Road:** Work nights, appeal the decision, or transfer.

**Cost:** Delay, fatigue, and reduced status.

**Irreversible loss:** The original scholarship remains gone.

### One Letter

**Loss:** Mara leaves after a permanent family break.

**Apparent ending:** No family member comes to the station.

**Seed:** A quiet relative leaves an envelope on a bench.

**Activation:** Stay after the bus doors close and examine the envelope.

**Second Road:** Build one limited long-distance relationship.

**Cost:** Slow contact and firm boundaries.

**Irreversible loss:** The whole family does not reunite.

### Different Hands

**Loss:** Mara permanently loses hand function after an accident.

**Apparent ending:** Heavy repair work becomes unavailable.

**Seed:** A stagehand uses an adaptive jig that performs the lost function.

**Activation:** Inspect the jig or ask who built it.

**Second Road:** Enter adaptive tool design, inspection, teaching, or stage rigging.

**Cost:** Learn again and accept help.

**Irreversible loss:** The injury remains permanent.

### What She Left

**Loss:** Mara dies in Iron Ridge mode.

**Apparent ending:** Credits begin over an empty room or mountain.

**Seed:** A minor character finds Mara's journal, map, or repair diagram.

**Activation:** Focus on the object during the credits.

**Second Road:** Play a short Legacy Chapter through the carrier.

**Cost:** The carrier risks status, safety, or belonging.

**Irreversible loss:** Mara remains dead.

## Redemption Window budget

A losing ending can contain:

- one major Redemption Window,
- no more than two supporting microcues,
- and one clear activation subject.

Not every losing ending receives a window.

A campaign should include enough closed endings to protect the credibility of loss.

The target range is:

- 40 to 60 percent of persistent-defeat endings contain a window,
- 20 to 35 percent of dark campaign endings contain a window,
- and Iron Ridge death uses only selected Legacy Chapter seeds.

These ranges require youth and narrative testing.

## Prototype requirements

The first Persistence System prototype includes four windows.

1. Quarry contract loss and Tess in the shadows.
2. Wrong accusation and the carbon copy.
3. Permanent hand injury and the adaptive jig.
4. Iron Ridge death and the journal carrier.

Each prototype must support:

- the complete apparent ending,
- player departure without activation,
- dwell-focus activation,
- an accessible alternate cue,
- a branch save,
- a playable recovery cost,
- and a possible Second Road failure.

## Instrumentation

Record only design events.

Required events include:

- time spent in the final scene,
- whether the player moved the camera,
- first seed focus,
- activation time,
- window accepted or declined,
- first recovery action,
- Second Road quit point,
- and desire to continue.

Do not infer trauma history, religion, family relationships, or mental health from these events.

## Acceptance gates

The Persistence System passes only when:

- the original loss still feels real,
- the seed feels present before the ending,
- the player can discover the seed without a guide,
- accessibility support does not reveal the answer outright,
- the activation feels earned by attention,
- the new road requires a meaningful cost,
- the path does not require unsafe reconciliation,
- the Second Road can fail,
- the apparent ending remains valid,
- and youth testers describe the system as hopeful rather than manipulative.

## Review questions

- Did the player understand that control remained?
- Did the player notice a world cue before a prompt?
- Did the seed feel causal or convenient?
- Did the player feel tricked by the hidden window?
- Did the recovery cost fit the loss?
- Did the path preserve boundaries and safety?
- Did the player want to continue after activation?
- Did the player accept any closed ending without assuming that content was missing?

## Next visual proof frames

The next loss-state visual set should show:

1. Engine-load imbalance with grip, center-of-mass, and crush risk.
2. Rain-road crash with speed, traction, fatigue, and repair-quality causes.
3. Ridge exposure with temperature, fatigue, route, shelter, and turn-back actions.
4. Wrong-accusation consequence with the closed record and hidden carbon-copy seed.

Each frame must show a credible losing state and at least one player action that could have changed it.
