# Beyond the Ridge

**A grounded, third-person narrative game concept about work, family, belief, memory, and the cost of choosing a wider world.**

![World and character overview](assets/previews/world-montage.png)

> [!IMPORTANT]
> **Beyond the Ridge** is a provisional title for a classroom design exercise.
> The project draws thematic and environmental inspiration from Tara Westover's memoir *Educated*.
> It is not an authorized adaptation.

## Project summary

The player controls Mara Vale, a teenager raised inside a remote mountain family economy near the turn of the millennium.

Mara repairs machines, gathers remedies, travels mountain routes, works in town, studies unfamiliar ideas, and interprets conflicting accounts.

Each practical task changes a human situation. A fast repair can earn approval and increase danger. A request for help can protect someone and expose a family secret.

The project uses one central question:

> How far will you go to learn what lies beyond the world you were given?

## Player experience

The game combines grounded action with social interpretation.

The player can:

- Repair, salvage, fabricate, and inspect machines.
- Cross mountain routes by foot, horse, and vehicle.
- Gather herbs and make care decisions with incomplete information.
- Listen, observe, ask, challenge, deflect, remain silent, or leave.
- Compare physical evidence, testimony, records, rumors, and memory.
- Return home and face consequences at breakfast, supper, and family work.
- Develop mechanical skill, fieldcraft, observation, persuasion, history, self-direction, and collaboration.

The game has no morality bar. Relationships track trust, respect, fear, loyalty, dependence, and clarity as separate states.

## Design principles

1. **Work is gameplay.** Skills grow through meaningful labor.
2. **Relationships are systems.** Each relationship can hold several conflicting states.
3. **Worldviews shape perception.** Beliefs affect what a character notices, praises, fears, or denies.
4. **Home is the consequence hub.** Choices return to the family table.
5. **Every solution has a cost.** The interface does not promise a perfect outcome.
6. **Curiosity opens the map.** Questions, trust, maps, and capability reveal new places.

## Current project state

The repository contains design and previsualization material. It does not contain a playable engine build.

| Area | State | Primary artifact |
|---|---|---|
| World design | Defined | `packages/foundation/01-world-bible/` |
| Character design | Defined | `packages/foundation/02-character-bible/` |
| Art direction | Defined | `packages/foundation/03-art-bible/` |
| Chapter adaptation | Mapped | `packages/playable-vision/adaptation-matrix/` |
| Gameplay systems | Defined | `packages/playable-vision/gameplay-systems/` |
| Opening slice | Storyboarded | `packages/playable-vision/opening-storyboard/` |
| Dialogue and memory | Defined | `packages/fidelity/dialogue-voice-memory/` |
| Locations and routes | Defined | `packages/fidelity/location-route-memory/` |
| Trailer and animatic | Planned | `packages/previsualization/` |
| Engine prototype | Not started | See `ROADMAP.md` |

See [STATUS.md](STATUS.md) for scope limits and evidence.

## Review paths

### Ten-minute review

1. Read this page.
2. Open the [project overview](docs/README.md).
3. View the [foundation montage](assets/previews/foundation-overview.jpg).
4. View the [systems montage](assets/previews/systems-montage.png).
5. View the [storyboard montage](assets/previews/storyboard-montage.png).

### Design review

1. Read the [design index](docs/design/README.md).
2. Review the World Bible, Character Bible, and Art Bible.
3. Review the Gameplay Systems Bible.
4. Review the opening vertical slice.
5. Record conflicts in an architecture decision record.

### Source-fidelity review

1. Read the [source and fidelity guide](docs/fidelity/README.md).
2. Review the chapter adaptation matrix.
3. Check the source register before adding a named place, memory, or form of address.
4. Apply the transformation guardrails in `RIGHTS_AND_USE.md`.

### Production review

1. Read the [production index](docs/production/README.md).
2. Review the cuebook and animatic production bible.
3. Confirm character, location, prop, interface, and sound continuity.
4. Test each sequence against the vertical-slice success criteria.

## Repository map

```text
.
├── assets/                 Preview images and book-informed visual references
├── docs/                   Design guides, decisions, glossary, and traceability
├── packages/               Canonical presentation, PDF, and spreadsheet artifacts
├── source/                 Source register and rules for protected source material
├── .github/                Contribution templates and documentation checks
├── AGENTS.md               Rules for development agents and writing agents
├── CONTRIBUTING.md         Change process and review requirements
├── GOVERNANCE.md           Decision ownership and approval boundaries
├── RIGHTS_AND_USE.md       Adaptation, attribution, and content-use limits
├── ROADMAP.md              Ordered project work
└── STATUS.md               Capability and evidence status
```

## Source relationship

The project borrows thematic and environmental material from *Educated*.

Recognizable anchors include the mountain, family labor, salvage work, herbal care, religious interpretation, performance, education, and contested memory.

Names, mission plots, player choices, character biographies, dialogue, and game outcomes are original project material unless a source note states otherwise.

The source register uses four labels:

- **Direct fact:** A specific detail found in the memoir.
- **Composite influence:** Several passages inform one fictional element.
- **Original transformation:** The game changes the source material into a new mechanic, place, or scene.
- **Restricted material:** The repository records a citation but does not store the source text or image.

See [Source and fidelity](docs/fidelity/README.md) for the working method.

## Rights and content care

Keep this repository private until a rights review approves another visibility level.

Do not commit the full text of *Educated*, audiobook files, publisher artwork, or other protected source copies.

Do not convert trauma into a reward loop, collectible, spectacle, or boss fight.

Do not treat rural people or religious people as visual shorthand for ignorance or danger.

See [RIGHTS_AND_USE.md](RIGHTS_AND_USE.md) for the full boundary.

## Documentation standard

Repository prose follows the `write-timeless-technical-prose` skill from `hwillGIT/library-of-context`.

The documentation uses American English, active voice, stable terms, short sentences, and defined project vocabulary.

The documentation avoids edit history, promotional claims, vague quality claims, and unsupported comparisons.

The project does not claim formal ASD-STE100 compliance. Human review must confirm approved terms and intended meaning.

See [Writing standard](docs/WRITING_STANDARD.md) for the local rules and source links.

## Contribution entry point

Read [CONTRIBUTING.md](CONTRIBUTING.md) before you change a canonical artifact.

Use a focused branch. Open a draft pull request early. Link each change to a source, design principle, test, or decision record.

## Project ownership

Hubert Williams directs the concept and repository scope.

The project uses a review model rather than a hero-author model. Design, source fidelity, accessibility, faith representation, and content care require separate review.
