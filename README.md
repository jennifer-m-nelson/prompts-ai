# Prompts

A collection of reusable prompts I run across projects. Each file is a standalone prompt, ready to paste into a new chat.

## Index

| Prompt | Use when |
|---|---|
| `claude-md-generator.md` | Starting a new project folder in Cowork or Claude Code and want Claude to interview you and generate CLAUDE.md files (global, project, and subfolder-level instructions) so future sessions don't need re-explaining. |

## Conventions

- One prompt per file, named `kebab-case.md`.
- Each file starts with a one-line comment describing what it does and when to run it.
- Prompts are kept as plain text, no placeholders that need find-and-replace unless noted at the top of the file.

## Adding a new prompt

1. Drop the `.md` file in this folder.
2. Add a row to the index table above with the filename and a short "use when" description.
3. Commit with a message naming the prompt, e.g. `add: meeting-notes-summarizer prompt`.
