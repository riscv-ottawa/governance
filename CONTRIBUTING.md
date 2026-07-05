# Contributing to the RVO planning worksheet

This worksheet is a living document for **RISC-V Ottawa (RVO)**, maintained in the open. Anyone in the community is welcome to improve it: fill in a TBD, sharpen a value statement, correct a fact, or add a section the group has decided it needs. This guide explains how the documents are organized and how to make a change cleanly.

If you are reviewing as a group rather than editing, you can see the [README index](README.md) to find the right sections. The rest of this guide is for people making edits.

## How the documents are organized

The worksheet is split into numbered files at the repository root, one per major section, in reading order. The [README index](README.md#how-to-use-this) is the canonical list of files, with a one-line description of each.

Each file opens with an H1 title and a one-line status header, for example:

```markdown
# Structure & Governance

> Status: 🚧 In progress
```

Sub-points keep the numbering used inside their file (governance section 5.2 lives in `05-structure-and-governance.md`, and so on), so a reference like "§5.5" is unambiguous about which file it points to.

## Status conventions

The status header on each file, and the status column in the README index, use the same set of values, defined in the [README status legend](README.md#how-this-is-organized). When a section is 🚧 In progress, mark the specific heading with 🚧 too, so it is easy to spot.

When your edit changes a section's maturity (for instance, you fill in the last TBD in a 🚧 section), update both the file's status header and the matching row in the README index in the same change.

## Making a change

1. Edit the relevant file directly. Most structured sections are written as bulleted lists (a bold item heading with labelled sub-bullets to fill in) rather than tables, because lists are easier to extend and edit; follow that pattern rather than reformatting it. A few stable, narrow tables remain (the founding-team list and the README index); leave those as tables.
2. Update the `Last updated` date in the file's status header.
3. If the change affects status, update the README index row to match.
4. Keep edits scoped to one section per change where you can, so a working group can review a single file at a time.

## Adding a new section

1. Create the next numbered file (for example `09-...md`) so reading order stays intact.
2. Give it an H1 title and a status header, following the pattern above.
3. Add a row to the index table in the [README](README.md).
4. If other documents should point to it, link them with relative paths (see below).

## Links and cross-references

Link between documents with relative paths so they keep working as files move, and point at a specific heading with its GitHub-style anchor (lowercase, punctuation removed, spaces as hyphens, dots dropped):

```markdown
See [§5.5](05-structure-and-governance.md#55-financing-the-layered-model).
```

When you rename a heading, search for links to its old anchor and update them.

## Style

The worksheet aims to be plain, direct, and easy to scan. Keep prose tight, use the existing bulleted-list and checklist structure for fill-in content, and avoid filler. Images and other assets live in `assets/`; reference them with relative paths.

## Who maintains this

The founding team carries the worksheet today (see [Foundations §1.3](01-foundations.md#13-founding-team-check-the-rule-of-22)). As the steering group forms, section ownership will be shared out; until then, open a discussion in [Discord](https://discord.gg/EfryE4wfk4) or a pull request on [GitHub](https://github.com/riscv-ottawa) and a maintainer will help land your change.
