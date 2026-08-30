# Action and Loss Systems

## Status

This document extends the gameplay interaction contract for *Beyond the Ridge*.

It defines stronger physical action, meaningful danger, persistent defeat, and optional hard-loss modes.

It does not describe an implemented engine build.

## Design correction

The existing design favors fail-forward outcomes.

That principle protects story access, but it can also make danger feel theatrical.

The game needs moments when the player can fail a task, lose an opportunity, suffer a lasting injury, lose a valued asset, or die.

Loss must be fair, readable, and connected to player action.

Loss must not reward abuse, punish a player for seeking safety, or treat trauma as a mastery test.

## Comparative lessons

The project studies several games for system ideas.

### Red Dead Redemption 2

Use contextual focus and in-world interaction.

The player can focus on a person, animal, machine, or point of interest.

Face buttons then provide context actions without moving the player to a separate dialogue screen.

Borrow:

- a living world that reacts to visible condition and prior behavior,
- horse care and travel,
- contextual interaction,
- local reputation,
- unscripted incidents,
- equipment wear,
- and physical consequence.

Do not copy:

- a global honor meter,
- gunplay as the main answer,
- or a morality scale that reduces complex relationships to one number.

### Death Stranding

Use weight, balance, terrain, and preparation as action.

Borrow:

- left and right grip control,
- load distribution,
- route planning,
- terrain reading,
- cargo damage,
- and the decision to continue or turn back.

### The Long Dark

Use weather, fatigue, scarcity, and death as credible threats.

Borrow:

- condition management,
- resource pressure,
- limited information,
- optional permadeath,
- and challenge runs.

### Pentiment

Use limited time and incomplete investigation.

Borrow:

- leads that compete for time,
- the inability to inspect everything,
- accusations that can be wrong,
- and consequences that remain visible years later.

### The Last of Us Part II

Use layered difficulty and strong control customization.

Borrow:

- independent difficulty settings,
- optional chapter or campaign permadeath,
- reduced-HUD modes,
- control remapping,
- hold and toggle alternatives,
- and adjustable game speed.

### Kingdom Come: Deliverance

Use multiple approaches and a reactive social world.

Borrow:

- practical skill growth,
- reputation by community,
- legal consequences,
- stealth, persuasion, bribery, flight, and direct confrontation,
- and quests that can end in different practical states.

## Revised player promise

```text
Prepare -> Venture -> Work -> Survive disruption -> Decide -> Pay the cost -> Return -> Live with the result
```

The player should feel capable but never invulnerable.

The world should permit improvisation but remember recklessness.

## Action pillars

### Physical work

Repair, salvage, fabrication, hauling, sorting, rigging, lifting, cutting, welding, testing, and cleanup.

### Travel

Walking, sprinting, climbing, horse travel, vehicle travel, route planning, and weather response.

### Rescue

Emergency shutdown, stabilization, first response, fire control, extraction, transport, and calling for help.

### Investigation

Observation, evidence preservation, photography, interviews, records, route reconstruction, and competing explanations.

### Social action

Greeting, questioning, joking, appealing, challenging, bargaining, refusing, lying by omission, silence, and departure.

### Evasion and confrontation

Hiding, trespassing, escaping, blocking, dodging, breaking a grip, shoving, using the environment, calling for help, and surrendering.

Violence is possible, but it is not the default progression system.

### Performance and study

Rehearsal, stage work, timing, public speaking, note-taking, exam preparation, research, and deadline management.

## Expanded control grammar

One input keeps one stable meaning across modes.

| Input | Stable meaning | On foot | Work and rescue | Horse and vehicle | Social and investigation |
|---|---|---|---|---|---|
| Left stick | Move body or vehicle | Walk and position | Shift stance and load | Steer | Move within live scenes |
| Left-stick click | Increase pace | Sprint | Faster reposition | Gallop or accelerate response | Leave quickly |
| Right stick | Direct attention | Look | Track hands, load, fire, or patient | Look around or check mirrors | Watch speaker, sign, or evidence |
| Right-stick click | Close attention | Read tracks or sound | Precision view | Inspect road or animal state | Focus a person or claim |
| A | Engage | Vault, climb, mount, enter | Pick up, secure, carry, confirm | Mount, enter, exit safely | Greet, accept, approach |
| X | Examine or manipulate | Search, inspect, interact | Rotate, test, cut power, inspect injury | Inspect horse, dashboard, or damage | Question, read, compare |
| Y | Communicate | Call horse or companion | Warn, command, request help | Speak, use radio, calm horse | Ask, challenge, call out |
| B | Disengage or reduce exposure | Step back, crouch, dodge | Release, abort, create distance | Brake away, dismount, bail only when safe | Deflect, refuse, stay silent, leave |
| Left trigger | Brace, guard, or focus | Guard, aim attention | Left grip, brace, stabilize | Rein, brake, steady | Focus a person or object |
| Right trigger | Perform or apply force | Push, throw, use held tool | Right grip, torque, pull, extinguish | Accelerate, spur, apply control | Commit selected intent |
| Left bumper | Open carried kit | Quick equipment wheel | Tool, care, or rescue wheel | Horse or vehicle kit | Camera, notebook, evidence kit |
| Right bumper | Alternate technique | Quick turn, hand action | Measure, change grip, verify | Handbrake, gear, calm technique | Recall, offer proof, mark contradiction |
| D-pad up | Journal and current thread | Open journal | Record observation | Review route note | Saw, Heard, Concluded, Revised |
| D-pad left | Light and visual tool | Flashlight or camera | Work light | Headlights | Photograph or inspect |
| D-pad right | Radio and companion | Call or signal | Request help | Radio, whistle, horn | Contact a person |
| D-pad down | Route and condition | Map and condition | Objective and hazard status | Route, fuel, weather | Schedule and access |
| View button | Immediate status | Condition and load | Task state | Mount or vehicle state | Relationship and evidence summary |
| Menu button | Pause and save | Settings | Restart checkpoint | Settings | Review controls |

### Two-hand actions

Some actions use both triggers.

Examples include carrying a heavy axle, holding a rope, controlling a frightened horse, or stabilizing an injured person.

The player can release one side to shift grip.

Every two-hand action requires a toggle or single-button accessibility alternative.

## Focus interaction

Hold the left trigger near a person, animal, machine, or point of interest.

The focused target receives four stable options.

- **A — Engage:** Approach, greet, accept, mount, or help.
- **X — Examine:** Inspect, question, read, or compare.
- **Y — Communicate:** Warn, challenge, call, direct, or request.
- **B — Disengage:** Ignore, step away, refuse, surrender, or leave.

Context changes the action label, but not the input meaning.

## New action systems

### Heavy-load and balance system

Mara can carry engines, beams, toolboxes, injured people, scrap bundles, and stage equipment.

The load has:

- weight,
- shape,
- grip points,
- center of mass,
- sharp or hot surfaces,
- and a safe carrying limit.

The player uses left and right grip controls to correct balance.

A poor grip can cause:

- a dropped part,
- damaged cargo,
- a foot or hand injury,
- blocked access,
- lost time,
- or a fatal crush in extreme cases.

### Horse system

A horse has health, stamina, fear, trust, load, and footing.

The player can:

- approach and calm,
- feed and brush,
- inspect hooves and tack,
- distribute a load,
- lead through dangerous ground,
- mount and dismount,
- lean and brace,
- jump small obstacles,
- and release the horse rather than force a route.

A frightened or exhausted horse can bolt, refuse, fall, or throw Mara.

A horse can die in Frontier and Iron Ridge modes.

### Vehicle system

Vehicles have fuel, traction, temperature, brakes, electrical condition, cargo security, and mechanical wear.

The player can:

- inspect before departure,
- start and warm the engine,
- use mirrors,
- select a route,
- manage speed,
- brake on loose ground,
- use a handbrake,
- shift weight and cargo,
- make a roadside repair,
- abandon the vehicle,
- or call for help.

A rushed repair can fail later at speed.

### Climbing and rope system

The player can climb rock, industrial structures, ladders, roofs, and stage rigging.

Grip, stamina, weather, carried weight, and anchor quality affect the route.

The player can:

- test an anchor,
- place or remove a rope,
- transfer weight,
- assist another climber,
- lower equipment,
- catch a slip,
- retreat,
- or cut a load free.

A fall can cause injury or death.

### Fire and environmental emergency system

Fire can spread through fuel, oil, dry timber, cloth, and wind.

The player can:

- cut power,
- move fuel,
- use an extinguisher,
- smother a small fire,
- open or close airflow,
- rescue a person,
- call the fire department,
- or abandon a structure.

The player cannot save every object and every person in every fire.

### Wildlife system

Wildlife reacts to distance, food, sound, weather, injury, and the player’s behavior.

The player can:

- observe tracks,
- avoid an animal,
- make noise,
- back away,
- climb,
- use a flare,
- protect livestock,
- or use a firearm where the campaign and rating permit it.

Firearms remain rare tools for hunting, predator defense, or warning.

The game does not become a shooting gallery with a memoir attached.

### Stealth and trespass system

The player can enter a closed yard, archive, office, ridge route, or industrial site without permission.

The system tracks:

- visibility,
- sound,
- lighting,
- witness identity,
- property damage,
- evidence handled,
- and whether Mara is recognized.

The player can hide, distract, talk, surrender, flee, or accept removal.

Being caught can create fines, bans, confiscation, school discipline, arrest, or a damaged relationship.

### Confrontation and escape system

Direct conflict is short, dangerous, and usually avoidable.

The player can:

- guard,
- dodge,
- break a grip,
- shove,
- block a doorway,
- use furniture or terrain,
- shout for help,
- escape,
- or surrender.

A successful escape can still leave an injury or social consequence.

Repeated aggression increases injury, legal, and relationship risk.

### Deadline investigation system

Time advances while the player travels, works, rests, studies, and interviews people.

The player cannot inspect every lead.

A lead can expire because:

- a witness leaves,
- weather destroys a trace,
- a store closes,
- a shift begins,
- a bus departs,
- a document is moved,
- or another character acts first.

The player may have to make a decision with incomplete evidence.

### Performance and academic challenge system

Performance and study use preparation rather than trivia alone.

The player manages:

- rehearsal time,
- sleep,
- travel,
- costume or equipment,
- unfamiliar vocabulary,
- asking for help,
- and public pressure.

Failure can mean a missed cue, lost role, failed course, probation, or lost scholarship.

An academic loss must not imply that education is the only valid life path.

## Condition model

The game tracks three player-facing condition groups.

### Body

Health, injury, pain, temperature, illness, and impairment.

### Energy

Stamina, fatigue, hunger, hydration, and sleep debt.

### Attention

Breath, balance, overload, precision, and immediate situational awareness.

The game does not use attention as a measure of intelligence or worth.

## Loss architecture

Loss uses three layers.

### Layer 1: encounter defeat

An encounter defeat ends the immediate attempt.

Examples include:

- Mara dies in a fall, fire, crash, machinery accident, exposure event, or wildlife attack.
- A rescue target dies in an encounter that cannot continue without that person.
- A critical vehicle or structure is destroyed with no alternate route.
- Mara becomes trapped in an unrecoverable technical state.

Standard mode reloads the latest encounter checkpoint.

Frontier mode can reload the start of the day.

Iron Ridge mode can end the chapter, act, or campaign.

### Layer 2: persistent defeat

A persistent defeat does not reload.

The game autosaves the result.

Examples include:

- a broken wrist that reduces repair speed,
- a concussion that limits attention mode,
- a burn or frost injury,
- a dead horse,
- a destroyed truck,
- a lost quarry contract,
- depleted medicine or fuel,
- a closed store-credit account,
- confiscated evidence,
- a location ban,
- arrest or school discipline,
- a severed relationship,
- an innocent person blamed,
- a witness who leaves,
- a lost role,
- a failed course,
- or a missed scholarship deadline.

The campaign continues through a different state.

### Layer 3: campaign loss

A campaign loss ends the current playthrough.

Possible causes include:

- Mara dies with campaign permadeath enabled.
- Mara reaches a hard seasonal deadline with no viable livelihood, education, performance, or community path.
- All required transport and support routes become unavailable, and no recovery route remains.
- A major crisis destroys the last viable route while Mara lacks the capability or ally needed to recover.

A local life can be a valid win.

Remaining near the mountain is not itself a failure.

The loss condition is the destruction of agency, not the rejection of college.

## Dark endings are not always game over

The player can complete the campaign with major losses.

Examples include:

- the family’s false account becomes the accepted public account,
- Mara leaves but loses every family relationship,
- Mara stays but gives up authorship of her own account,
- an ally dies,
- a sibling takes the blame,
- or the family business survives through unsafe practices.

These endings should feel consequential without being labeled good or evil.

## Valid campaign wins

The game supports several sustainable paths.

Examples include:

- a skilled and safer trade or workshop path,
- a research or academic path,
- a performance or teaching path,
- a trained care or public-service path,
- a community leadership path,
- or a local path with clear personal boundaries.

A win requires:

- survival,
- a viable chosen path,
- enough capability or support to act on that path,
- and a self-authored account that Mara can revise.

The player does not need universal approval.

## Difficulty modes

### Story

- Critical death reloads immediately.
- Persistent consequences remain.
- Generous checkpoints.
- Simplified balance and timing.
- Strong hazard and navigation cues.

### Standard

- Death reloads the current encounter.
- Injuries, asset loss, missed opportunities, and relationship loss persist.
- Normal scarcity and HUD support.

### Frontier

- Reduced health and slower recovery.
- Greater weather, hunger, fatigue, and resource pressure.
- Fewer HUD cues.
- Day-start reload after death.
- Horses, vehicles, tools, and contracts are easier to lose permanently.

### Iron Ridge

The player selects one save rule:

- chapter permadeath,
- act permadeath,
- or campaign permadeath.

The game clearly explains the rule before play begins.

### Custom

The player can adjust these systems separately:

- injury severity,
- resource scarcity,
- hazard timing,
- weather severity,
- navigation help,
- relationship feedback,
- investigation deadlines,
- checkpoint frequency,
- permadeath scope,
- and HUD density.

Accessibility settings remain available at every difficulty.

## Example loss tree: Suspended Load

### Best practical result

The player notices the chain, cuts power, and moves Eli.

- No major injury.
- Work stops.
- Contract delay.
- Evidence remains available.

### Rescue with asset loss

The player pulls Eli clear but does not stabilize the load.

- Eli survives.
- The truck and engine block are damaged.
- The quarry contract is lost.
- The family economy changes.

### Rescue with player injury

The player stabilizes the load without gloves or a second cable.

- Eli escapes.
- Mara suffers a hand or shoulder injury.
- Repair actions become slower for several days.

### Persistent tragedy

The player gives only a warning and reacts too late.

- Eli can suffer permanent injury or death, depending on campaign mode and content settings.
- The household labor system changes.
- Witness accounts conflict.
- The supper scene becomes an accusation scene.

### Encounter defeat

Mara remains under the moving load.

- Mara dies.
- Standard mode reloads the emergency checkpoint.
- Iron Ridge applies the selected permadeath rule.

## Example loss tree: County Road

The player drives during rain while choosing conversation responses.

Possible causes include speed, poor tires, fatigue, a temporary repair, unsecured cargo, and missed road signs.

Possible outcomes include:

- a harmless skid,
- lost cargo,
- a damaged axle,
- a stranded night,
- passenger injury,
- arrest after property damage,
- or fatal collision.

The seatbelt, earlier repair quality, route choice, and driving speed affect the result.

## Example loss tree: Investigation

The player has time to follow two of four leads.

Possible outcomes include:

- enough evidence to support one claim,
- a disputed accusation,
- an innocent person punished,
- the real cause remaining unknown,
- a relationship severed,
- or the official record becoming difficult to change.

The game must not reveal a hidden truth percentage.

## Loss feedback

Loss feedback states facts.

It does not scold the player.

### Encounter defeat screen

```text
CRITICAL FAILURE
Load collapse

Known conditions
- Machine remained powered
- Eli remained inside the danger zone
- Emergency stop was reachable

RETRY CHECKPOINT
REVIEW CONTROLS
RETURN TO TITLE
```

### Persistent defeat summary

```text
OUTCOME: QUARRY CONTRACT LOST

Changed
- Expected income removed
- Replacement bearing remains unpaid
- Abel’s dependence on Mara increased
- Cedar Gate credit is now important

The story continues
```

The summary shows immediate known changes.

It does not expose distant hidden consequences.

## Reputation without a morality bar

The game tracks local standing rather than universal goodness.

Possible standing groups include:

- Vale household,
- Cedar Gate workers,
- church community,
- county services,
- theater company,
- college faculty,
- and student peers.

A community can respect Mara and still misunderstand her.

Another community can distrust Mara for a truthful action.

Standing affects prices, credit, invitations, warnings, witnesses, shelter, and help.

## Accessibility and loss

Challenge and accessibility are independent.

The player can use:

- full remapping,
- hold or toggle alternatives,
- repeated-input assistance,
- game-speed adjustment,
- simplified balance,
- extended response windows,
- strong sound-direction indicators,
- high-contrast hazards,
- and content skips with factual summaries.

These options do not disable persistent consequences unless the player changes that setting.

## Prototype additions

The next interaction prototype should add these proof encounters:

1. Heavy engine carry with balance and grip.
2. Horse route during wind and loose footing.
3. Vehicle skid caused by speed, weather, and repair quality.
4. Short nonlethal escape from a confrontation.
5. Ridge exposure event with a real turn-back decision.
6. Timed investigation where two leads expire.
7. Persistent injury that changes later controls.
8. A complete campaign-loss screen in Iron Ridge mode.

## Acceptance gates

The system passes only when:

- players can identify the danger before failure,
- controls remain consistent across action types,
- a skilled player can improve the result,
- bad preparation has visible consequences,
- death feels attributable rather than random,
- persistent losses meaningfully alter later play,
- safe withdrawal remains a legitimate action,
- difficulty does not disable accessibility,
- and youth testers still want to retry after a hard loss.
