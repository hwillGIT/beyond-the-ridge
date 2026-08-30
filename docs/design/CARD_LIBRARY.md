# Game-Design Card Library

## Purpose

The card library is the fast-reference layer between the large design bibles and production work.

The canonical dataset is `packages/card-library/card-library.csv`.

It contains 69 cards across seven families.

## Families

| Family | Count | Main question |
|---|---:|---|
| Character | 13 | Who is this person and what changes around them? |
| Location | 15 | What can the player do here and why does the place matter? |
| System | 10 | What rule turns input into consequence? |
| Encounter | 8 | What pressure makes several actions reasonable? |
| Worldview | 5 | What values shape interpretation? |
| Relationship State | 6 | What part of a relationship changed? |
| Gameplay Keyframe | 12 | What must one paused frame prove? |

## Card grammar

A production card uses this order:

1. Title.
2. Dominant image.
3. One-sentence design statement.
4. Player hook.
5. Pressure or trade-off.
6. Canonical anchor.

Do not put a paragraph on a card.

Do not show numerical relationship scores to the player.

Do not use a card to hide an unresolved design conflict.

## Visual grammar

Character cards use face, hands, clothing, and one environment cue.

Location cards use a navigable view with at least two visible routes or activities.

System cards use a real object or action before an abstract icon.

Encounter cards freeze the moment before commitment.

Worldview cards show ordinary behavior rather than symbolic propaganda.

Relationship cards use two people, distance, posture, access, or shared objects.

Keyframe cards use the full gameplay image without decorative cropping.

## Youth readability

A reviewer should understand the card's main idea in less than 20 seconds.

A card fails when its text explains what the image should already communicate.

A card also fails when the image looks attractive but does not imply a player action.

## Rendering order

Render the card families in this order:

1. Gameplay keyframes.
2. Character cards.
3. Encounter cards.
4. Location cards.
5. System cards.
6. Relationship-state cards.
7. Worldview cards.

This order tests the most concrete material before abstract design language.
