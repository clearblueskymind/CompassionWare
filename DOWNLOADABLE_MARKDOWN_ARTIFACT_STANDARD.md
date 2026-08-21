# Downloadable Markdown Artifact Standard

**Status:** Canonical workflow instruction  
**Scope:** Reports, benchmark records, research papers, orientation documents, and other GitHub-ready Markdown artifacts

## Purpose

When a user asks for a Markdown file that they can save and upload to GitHub, the deliverable must be an actual downloadable `.md` file. Markdown displayed in chat is not an adequate substitute.

This standard records the delivery method that has been verified to work.

## Required workflow

1. Create a real UTF-8 file whose filename ends in `.md`.
2. Use a stable, descriptive, ASCII-safe filename.
3. Save the complete Markdown content in that file.
4. Verify that the file exists and retains the `.md` extension.
5. Present the file through a direct clickable sandbox link using this exact pattern:

   ```markdown
   [DESCRIPTIVE_FILENAME.md](sandbox:/absolute/path/to/DESCRIPTIVE_FILENAME.md)
   ```

6. Use the filename itself as the link label.
7. Tell the user where the file belongs in the repository.

## Acceptance test

The delivery is successful only when the user can:

- select the link;
- save or download the linked file directly;
- receive a file whose extension is `.md`; and
- upload that file to GitHub without recreating or renaming it.

## Do not substitute

Do not replace the downloadable Markdown artifact with:

- Markdown pasted only into the conversation;
- a fenced code block containing the document;
- a plain-text path with no clickable link;
- a `.txt` file renamed or described as Markdown;
- a `file://` link;
- a relative filesystem path; or
- a link whose label does not clearly identify the file.

## Example

```markdown
[AI_Human_Benefit_Index_Round_01_Comparative_Synthesis_Report_2026-08-20.md](sandbox:/workspace/example/AI_Human_Benefit_Index_Round_01_Comparative_Synthesis_Report_2026-08-20.md)
```

## Repository placement

Place this file at the repository root:

```text
DOWNLOADABLE_MARKDOWN_ARTIFACT_STANDARD.md
```

Keeping it at the root makes the instruction visible to human collaborators and future AI companions. If the repository has an `AGENTS.md`, contributor guide, or documentation index, add a short link from that file to this standard.

## Guiding principle

The artifact is not complete until the user can take possession of it in the requested format.
