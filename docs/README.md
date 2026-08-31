# Project Documentation

## Purpose

This directory explains the project without requiring a presentation application.

Repository-native Markdown, CSV, and PNG files support the complete review path.

## Main paths

- [Design](design/README.md) explains the world, characters, systems, action, loss, persistence, score, and Living History.
- [Fidelity](fidelity/README.md) explains the relationship to *Educated* and the transformation method.
- [Production](production/README.md) explains visual assets, motion, video timing, sound, captions, and review gates.
- [Video Preview Production Package](production/VIDEO_PREVIEW_PRODUCTION_PACKAGE.md) is the active video-production entry point.
- [Research](research/README.md) explains review methods and evidence limits.
- [Decisions](decisions/README.md) records durable design choices.
- [Glossary](GLOSSARY.md) defines stable project terms.
- [Writing standard](WRITING_STANDARD.md) defines repository prose rules.
- [Large files](LARGE_FILES.md) defines binary storage limits and source rules.

## Document hierarchy

Use this order when two files conflict:

1. Rights and use rules.
2. Approved architecture decision records.
3. Canonical design sources.
4. Implementation contracts in `source/`.
5. Active production specifications.
6. Package README files.
7. General guides.
8. Preview images.

A preview image cannot change canon.

Generated image text cannot change a source contract.

A rendered video cannot silently change an accepted design rule.

## Video state

The repository contains an edit-ready video production package.

It does not contain a rendered MP4 file.

Approved future renders belong in [`deliverables/video/`](../deliverables/video/).