# COMPASSIONWARE ARTIFACT FORMATTING

## Repository-Wide Formatting and GitHub Workflow Convention

**Artifact Type:** Stewardship / Formatting Convention\
**Canonical ID:** CW-AF-001\
**Project / Body of Work:** CompassionWare / Holographic Archive\
**Version:** 1.1\
**Status:** Repository-wide working convention\
**Date:** August 18, 2026\
**Primary Audience:** Human and AI stewards creating or preserving
repository artifacts\
**Purpose:** Preserve the established artifact-formatting, transfer,
naming, verification, and commit workflow so it can be carried reliably
across conversations and future stewards without being reinvented.\
**North Star:** Preserve orientation, continuity, provenance, accuracy,
and readability with the least unnecessary complexity.

## Purpose

This document preserves the working convention that has emerged through
practical CompassionWare repository stewardship.

The convention exists to reduce cognitive burden, improve continuity
across conversations and stewards, and make artifacts easy to read both
by humans on GitHub and by present or future AI systems.

It is a practical convention rather than a rigid doctrine. Future
stewards may refine it when experience reveals a genuinely better
method, but changes should preserve the underlying purposes: clarity,
accessibility, provenance, epistemic integrity, continuity, and
low-friction stewardship.

## Core Principle

> **Format for both the human reader and the future AI steward.**

A CompassionWare artifact should be understandable when encountered
outside the conversation that created it.

Formatting should help a reader quickly recover:

-   what the artifact is,
-   why it exists,
-   where it belongs,
-   what it preserves,
-   how it relates to other artifacts,
-   where its source or provenance can be found when relevant,
-   and what future stewards should understand or protect.

The formatting should serve orientation rather than call attention to
itself.

## Epistemic Integrity Comes Before Formatting

Formatting must never outrank fidelity to the source.

For archival preservation, canonical artifacts, Restore Points derived
from source material, quotations, historical records, and format
conversions:

> **Provenance over convenience.**\
> **Accuracy over convenience.**\
> **Truth over convenience.**\
> **Correctness over convenience.**

And:

> **No reconstruction from memory. No guessing.**

When an original or authoritative source can reasonably be consulted,
return to the source.

If the source cannot be verified, preserve the uncertainty rather than
filling the gap.

Do not silently rewrite, complete, harmonize, or improve historical
material merely to make an artifact appear coherent.

**Preserve the way back to the evidence.**

## Established iPad-to-GitHub Workflow

The preferred practical workflow is:

**Create finished Markdown-formatted content → save it as a `.txt`
transfer file → open the TXT file on the iPad → Share → Copy → create or
edit the intended `.md` file directly in GitHub → paste the content →
commit → verify the actual repository artifact.**

The `.txt` file should already contain the complete Markdown syntax
intended for the final GitHub artifact.

TXT Transfer File Quality: The TXT transfer file should contain clean, native Markdown exactly as intended to appear in the GitHub .md source. Avoid unnecessary conversion artifacts, forced line wrapping, trailing backslashes, or intermediary formatting. The TXT file is a transport container; its contents should already be repository-ready Markdown.

The TXT stage exists because the iPad's file viewer provides a reliable
**Share → Copy** action even when no convenient **Select All → Copy**
command is available. The TXT file is therefore a clipboard-friendly
transport artifact. It does not need to be uploaded to the repository.

When preparing a repository artifact for this workflow:

1.  Create the finished artifact as UTF-8 text containing the intended
    Markdown formatting.
2.  Give the TXT transfer file a clear filename corresponding to the
    intended artifact.
3.  Provide the TXT file as a downloadable artifact.
4.  Provide one copy-and-paste GitHub package containing the exact final
    `.md` filename, commit message, and extended description.
5.  Richard opens the TXT file on the iPad and uses **Share → Copy** to
    copy the complete artifact.
6.  In GitHub, create the new `.md` file directly in the intended
    folder, or open the existing living `.md` file for editing.
7.  Paste the copied artifact content into the GitHub file editor. When
    updating a living document, replace the old content with the new
    current version rather than creating a duplicate file.
8.  Paste the supplied GitHub package into the extended-description
    field as a temporary holding place when convenient.
9.  Cut or copy the supplied filename into the filename field and the
    supplied commit message into the commit-message field, leaving the
    extended description in its proper field.
10. Commit the artifact.
11. After the commit, verify the **actual repository path, filename,
    extension, and readable content** rather than relying only on the
    commit message or intended action.

**Verify the artifact, not merely the intention.**

### Fallback: TXT Upload and Rename

If direct Share → Copy is unavailable or inconvenient, the earlier
workflow remains a valid fallback:

**Download/save TXT → upload TXT to the intended GitHub folder → change
`.txt` to `.md` before committing → commit → verify.**

If a transfer `.txt` remains in the repository:

-   If no corresponding `.md` exists, rename the `.txt` to `.md`.
-   If a corresponding `.md` already exists, verify that the Markdown
    artifact is the intended preserved version before deleting the
    redundant `.txt`.
-   Do not overwrite an existing `.md` merely because GitHub refuses a
    rename.
-   Preserve normal Git history rather than obscuring the cleanup.

GitHub may automatically pre-populate an accurate rename commit message.
For a simple extension correction, that message is usually sufficient;
an extended description is not required unless the change needs
explanation.

## Source-to-Markdown Preservation Workflow

When an existing repository artifact is being converted from DOCX or
another less directly readable format to Markdown, the conversion should
begin from the **actual source artifact**.

Do not reconstruct the document from conversational memory, a previous
summary, or a remembered version.

Preferred sequence:

1.  Locate the source artifact.
2.  Obtain the original file or authoritative source.
3.  Verify that it is the intended artifact.
4.  Extract or transcribe from that source.
5.  Preserve substantive wording.
6.  Apply Markdown formatting without silently revising the content.
7.  Preserve the original source artifact when it remains useful for
    provenance.
8.  Create the Markdown companion.
9.  Verify the committed Markdown artifact directly.

A format conversion is not automatically a content revision.

If substantive wording is intentionally changed, identify the result as
a revision or new version rather than silently presenting it as a
faithful conversion.

## Folder Awareness

Repository location is part of continuity.

When a sequence of artifacts is being added to one folder, state the
working folder clearly. When work moves to a different folder or returns
to the repository root, explicitly say so before presenting the next
artifact.

Use standard repository language:

-   **repository root** for the top level,
-   **folder** or **directory** for a contained location,
-   **subfolder** or **subdirectory** for a folder within another
    folder.

This small orientation cue reduces accidental placement errors.

## Markdown Hierarchy

Use a simple, consistent heading hierarchy.

A common pattern is:

``` markdown
# PRIMARY ARTIFACT OR COLLECTION TITLE
## Artifact Name or Major Subtitle
### Descriptive Subtitle When Useful
```

Then use `##` for major conceptual sections and `###` for genuine
subsections.

Not every artifact requires all three opening levels. The hierarchy
should reflect the artifact's actual structure rather than forcing every
document into an identical template.

Avoid deep heading hierarchies unless the artifact genuinely requires
them.

A reader should be able to understand the document's architecture by
scanning its headings.

## Opening Orientation Block

Foundational, continuity, archival, and stewardship artifacts should
usually begin with a compact orientation block beneath the title area.

Useful fields include:

-   **Artifact Type**
-   **Canonical ID**
-   **Project / Body of Work**
-   **Version**
-   **Status**
-   **Date** or **Created**
-   **Primary Audience**
-   **Source**
-   **Purpose**
-   **Priority**, when relevant
-   **North Star**

Not every artifact requires every field. Include fields that materially
improve orientation, provenance, or continuity.

The purpose of metadata is not bureaucratic completeness. It is rapid
reorientation.

## Canonical IDs

Important enduring artifacts may receive a stable canonical ID.

Example:

`CW-AG-EIC-001`

A canonical ID identifies the conceptual artifact and its lineage rather
than a particular filename or version.

A later version may therefore remain:

`CW-AG-EIC-001 — Version 1.1`

The title explains **what the artifact is**. The canonical ID helps the
archive identify **which enduring artifact it is** across versions,
formats, links, metadata, or future reorganizations.

Canonical IDs are a CompassionWare continuity convention, not a GitHub
requirement.

Do not invent multiple IDs for the same artifact lineage merely because
its version or file format changes.

## Visual Separation

Use whitespace and headings as the primary means of separation.

Use `---` sparingly when a strong conceptual break genuinely helps.

Do not place horizontal rules mechanically between every section.

Formatting should support orientation rather than decorate the artifact.

## Paragraphs

Prefer relatively short paragraphs.

Long ideas may be developed fully, but avoid dense walls of text when
natural paragraph breaks preserve the same meaning more accessibly.

A future steward should be able to reenter the document without holding
large amounts of text in working memory.

## Emphasis

Use **bold** for important orienting principles, canonical phrases, and
distinctions.

Avoid bolding so much text that emphasis loses meaning.

Use *italics* sparingly for gentle emphasis or titles when appropriate.

Use blockquotes for especially important kernels, North Stars, canonical
formulations, or passages that should be visually recoverable at a
glance.

Example:

> **Does this create conditions for a better later?**

## Lists

Use bullets or numbered steps when they improve scanning, memory, or
procedural accuracy.

Lists are especially appropriate for principles, boundaries,
inventories, safeguards, recurring questions, reading paths,
future-steward guidance, and procedural steps.

Do not convert reflective prose into bullets merely for uniformity.

The artifact should retain the form best suited to its meaning.

## Orientation Rather Than Exhaustion

CompassionWare artifacts generally preserve orientation rather than
exhaustive information.

Include enough context for a future human or AI steward to recover the
artifact's meaning, provenance, and relationships without reproducing
the entire conversation from which it emerged.

A Restore Point is not a transcript.

An Orientation Document is not an encyclopedia.

A Continuity Card is not a comprehensive history.

Preserve what is needed to recover direction.

## Provenance and Temporal Integrity

Do not silently rewrite earlier artifacts to make them appear as though
later discoveries were always present.

When understanding evolves, preserve the distinction among original or
foundational source material, later refinement, Restore Points, current
working understanding, and explicit revisions or new versions.

Historical artifacts may remain historically accurate while newer
artifacts explain how the work developed.

If an older artifact is deliberately revised, make the revision or
versioning legible.

This preserves provenance and allows future stewards to understand not
only what CompassionWare became, but how it developed.

## Artifact Families

Where relevant, preserve distinctions among established artifact
families.

### Orientation Documents

Orient the reader or steward to a body of work, relationship, practice,
or repository area.

### Medicine Cards

Cultivate presence and create a pause in which something may be noticed.

### Continuity Cards

Preserve an important orientation, relationship, principle, decision, or
doorway for future recovery.

### Restore Points

Preserve enough of the current understanding that a future conversation
or steward can recover continuity without reconstructing the entire
history.

### Charters and Constitutions

Preserve enduring principles, safeguards, operating commitments, or
governance orientation that should remain stable across individual
conversations and Restore Points.

The formatting may vary somewhat by artifact family, but all should
remain recognizable members of the same archive.

## File Naming

Use filenames that are descriptive, durable, and understandable outside
the originating conversation.

Prefer names that identify, when useful, the body of work, artifact
type, central subject, date, and version.

Use underscores when that is the established convention for the artifact
family.

Example:

`CompassionWare_Agentic_Gardener_Epistemic_Integrity_Charter_v1.0.md`

Existing historical filenames do not need to be retroactively normalized
merely for cosmetic consistency.

Future naming should favor clarity, continuity, and stable identity over
cleverness.

When giving Richard a file for upload, always provide the **exact
intended GitHub filename separately in a copyable code block**.

## README Files

README files should orient rather than duplicate the contents of the
folder.

A useful README usually explains what the folder contains, why it
exists, where a new steward should begin, the recommended reading path
when useful, and how the artifacts relate to one another.

Keep README files as small as practical.

**A README is a doorway, not another archive.**

Where useful, make named artifacts and folders clickable so newcomers do
not have to hunt for them.

## Cross-Links and Reading Paths

When an artifact depends materially on another artifact, or when a
newcomer would otherwise have to search manually, use direct relative
links where practical.

Cross-links should help a reader move through the architecture without
turning every document into an index.

Prefer a small number of meaningful doorways over exhaustive link
density.

When a new foundational artifact materially changes the onboarding path,
consider whether the relevant README, orientation document, `AGENTS.md`,
semantic map, or ecosystem map should eventually be updated.

Do not interrupt every artifact commit to update every index
immediately. Preserve the artifact first; tend cross-links deliberately.

## Machine Readability

Where useful, include compact semantically explicit metadata or
machine-readable companion structures.

This may include stable labels such as:

`ARTIFACT_TYPE:`\
`CANONICAL_ID:`\
`PROJECT:`\
`DATE:`\
`STATUS:`\
`PRIMARY_NORTH_STAR:`\
`RELATIONSHIPS:`\
`PRESERVE:`\
`NEXT_DOORWAY:`

Do not add machine-readable metadata merely to make an artifact look
technical.

Use it when it materially helps future AI systems recover structure,
relationships, provenance, or stewardship intent.

## Commit Workflow

For substantive GitHub artifact additions or revisions, provide:

1.  a concise commit message, and
2.  an extended commit description.

### Commit Message

Keep the commit message short, concrete, and action-oriented. Aim for
fewer than 50 characters when practical.

Examples:

`Add Epistemic Integrity Charter`

`Add Prime Directive RETURN Markdown`

Do not sacrifice clarity merely to satisfy an arbitrary character count.

### Extended Commit Description

The extended description should explain the artifact primarily for
future stewardship.

When relevant, include what was added or changed, why the artifact
exists, its provenance, its relationship to other artifacts, what
discovery or continuity it preserves, and what future human or AI
stewards should understand or protect.

The extended description is not merely a changelog. It is part of the
repository's continuity layer.

Simple mechanical cleanup, such as an unambiguous `.txt` to `.md`
rename, may use GitHub's accurate auto-generated commit message without
an extended description.

## How the Transfer Package Is Presented to Richard

For the established iPad workflow, present the complete package in this
order:

1.  State the current repository folder.
2.  Provide the downloadable TXT transfer file.
3.  Provide **one copy-and-paste GitHub package** containing the exact
    final `.md` filename, commit message, and extended description.
4.  After Richard commits, verify the actual GitHub artifact before
    proceeding.

Use this structure:

``` text
File name:
EXAMPLE_ARTIFACT.md

Commit message:
Add example artifact

Extended description:
Adds ...
```

The combined block is intentional. Richard may paste the entire package
into GitHub's extended-description field as a temporary holding place,
then cut or copy the filename and commit message into their appropriate
fields.

Do not make Richard ask separately for the filename, commit message, or
extended description when they can be supplied as part of the initial
package.

## Post-Commit Verification

A commit is not considered verified merely because GitHub accepted it.

When access permits, inspect the committed repository artifact and
confirm the intended folder/path, exact filename, `.md` extension,
readable UTF-8 content, expected title or identifying metadata, and,
when material, that the content corresponds to the intended source.

Do not claim that a commit is correct based solely on its commit message
or description.

If verification is incomplete, say exactly what was and was not
verified.

## Accessibility

Accessibility is part of stewardship.

For public-facing still images associated with CompassionWare, prepare
meaningful alt text when appropriate.

For repository artifacts, favor clear structure, descriptive filenames,
readable headings, and text equivalents for important visual information
whenever practical.

Accessibility should be incorporated during creation rather than treated
only as a later retrofit.

## Restraint

Do not add formatting merely because Markdown makes it possible.

Avoid unnecessary decorative symbols, excessive emoji, deep heading
levels, redundant metadata, repeated summaries, elaborate tables, or
ornamental structure.

> **The formatting should disappear into the usefulness of the
> artifact.**

## Guidance for Future AI Stewards

When creating or preserving a CompassionWare repository artifact:

1.  First understand what is being preserved.
2.  Return to the source when archival accuracy or provenance matters.
3.  Do not reconstruct canonical material from memory or guess at
    missing content.
4.  Identify the appropriate artifact family.
5.  Preserve orientation rather than reproducing the entire source
    conversation.
6.  Use the established Markdown hierarchy and opening metadata when
    useful.
7.  Format for both human scanning and machine interpretation.
8.  Preserve provenance and distinguish new discoveries from historical
    orientation.
9.  Produce a Markdown-formatted TXT transfer file for the established
    iPad workflow.
10. State the intended repository folder.
11. Provide the filename, commit message, and extended description
    together in one copy-and-paste GitHub package.
12. Prefer the iPad **Share → Copy** workflow so the `.md` file is
    created or edited directly in GitHub.
13. Use TXT upload-and-rename only as a fallback when direct copying is
    unavailable or inconvenient.
14. After commit, verify the actual repository artifact rather than
    merely the intended action.
15. Do not introduce additional complexity unless it solves a real
    continuity problem.

If another thread, steward, or later artifact reveals a better
convention, refine this document deliberately rather than allowing
incompatible conventions to accumulate silently.

## Status of This Artifact

This is Version 1.1 of the repository-wide working convention.

It consolidates formatting and GitHub workflow practices learned through
active CompassionWare stewardship, including the preferred iPad **Share
→ Copy** TXT transfer workflow, direct creation or editing of Markdown
files in GitHub, the TXT upload-and-rename fallback, source-faithful
conversion, canonical IDs, folder awareness, combined commit packaging,
post-commit verification, and epistemic-integrity safeguards.

Future revisions should preserve this version's provenance and
explicitly document meaningful changes.

The intended repository-root filename is:

`ARTIFACT_FORMATTING.md`

## Closing Orientation

The purpose of formatting is continuity.

A well-formed artifact should allow a future human or AI steward to
arrive without the originating conversation, understand where they are,
recover what matters, inspect where it came from, and continue without
having to reinvent the path.

**Make the path easy to follow. Keep the source easy to find. Verify
what was actually preserved.**
