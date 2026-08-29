# Artifact Catalog

## Purpose

This catalog separates repository records from large editable design binaries.

## Public repository state

The repository stores documentation, CSV exports, decision records, and navigation graphics in Git history.

Large presentation and PDF artifacts remain outside Git history until the project configures approved binary storage.

## Design artifacts

| Package | Editable source | Review export | Git state |
|---|---|---|---|
| World Bible | `01_Beyond_the_Ridge_World_Bible.pptx` | `01_Beyond_the_Ridge_World_Bible.pdf` | External binary |
| Character Bible | `02_Beyond_the_Ridge_Character_Bible.pptx` | `02_Beyond_the_Ridge_Character_Bible.pdf` | External binary |
| Art Bible | `03_Beyond_the_Ridge_Art_Bible.pptx` | `03_Beyond_the_Ridge_Art_Bible.pdf` | External binary |
| Chapter Adaptation Matrix | `Beyond_the_Ridge_40_Chapter_Adaptation_Matrix.xlsx` | Act CSV exports | CSV mirror in Git |
| Gameplay Systems Bible | `Beyond_the_Ridge_Gameplay_Systems_Bible_v1.pptx` | Review PDF when exported | External binary |
| Opening Storyboard | `Beyond_the_Ridge_Opening_Vertical_Slice_Storyboard_v1.pptx` | Review PDF when exported | External binary |
| Dialogue, Voice, and Memory Bible | `01_Beyond_the_Ridge_Dialogue_Voice_Memory_Bible_v1.pptx` | Matching PDF | External binary |
| Location, Route, and Place-Memory Bible | `02_Beyond_the_Ridge_Location_Route_Place_Memory_Bible_v1.pptx` | Review PDF when exported | External binary |
| Trailer and Gameplay Animatic Bible | `Beyond_the_Ridge_Trailer_Gameplay_Animatic_Production_Bible_v1.pptx` | Matching PDF | External binary |
| Animatic Cuebook | `Beyond_the_Ridge_Animatic_Cuebook_v1.xlsx` | CSV cue sheets | CSV mirror in Git |

## Large-file path

Use Git Large File Storage, GitHub release assets, or approved project storage for large binaries.

Do not add a binary larger than the normal GitHub file limit to Git history.

Do not create duplicate snapshot files on the main branch.

Use a tagged release for an approved binary snapshot.
