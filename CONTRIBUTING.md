# Contributing

## Before you start

Read these files:

1. `README.md`
2. `RIGHTS_AND_USE.md`
3. `docs/fidelity/README.md`
4. `docs/WRITING_STANDARD.md`
5. The relevant package README

## Choose one change type

Use one primary change type for each pull request:

- `design`
- `narrative`
- `fidelity`
- `art`
- `production`
- `accessibility`
- `documentation`
- `rights`

## Branch names

Use this pattern:

```text
<change-type>/<short-purpose>
```

Examples:

```text
design/repair-risk-loop
fidelity/cedar-gate-signage
narrative/supper-version-dialogue
documentation/location-index
```

## Change process

1. Create a focused branch.
2. Open a draft pull request early.
3. State the conflict or risk.
4. State the mechanical change.
5. State the expected repository state.
6. Link the source, test, or decision record.
7. Request each required domain review.
8. Update the changelog for a completed public release.

## Source requirements

A source-derived change must identify:

- The source chapter or source record.
- The extracted detail or tension.
- The original transformation.
- The ethical guardrail.

Do not paste a long source passage into an issue or pull request.

## Documentation requirements

Use American English.

Use active voice when the actor matters.

Use one stable term for each concept.

Define a specialized term at first important use.

Keep a descriptive sentence at 25 words or fewer.

Keep a procedural sentence at 20 words or fewer.

Do not use contractions or semicolons in prose.

Do not use promotional filler or unsupported comparisons.

## Artifact requirements

Do not edit only a PDF when an editable source file exists.

Update the editable source first. Export the review file from that source.

Record the source application and export settings in the package README.

## Pull request summary

Use this order:

1. Failure risk or conflict.
2. Mechanical fix.
3. Guaranteed repository state at completion.

See `.github/PULL_REQUEST_TEMPLATE.md` for the required format.
