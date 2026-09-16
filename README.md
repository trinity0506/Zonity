# Zonity

Zonity is a personal skill for writing and revising English academic prose in Zoe's preferred voice: clear, natural, precise, and easy to understand on the first reading.

It is intended for research manuscripts and related academic text. It keeps the original evidence, uncertainty, citations, and technical meaning intact while improving expression and logical flow.

## What it checks

Zonity helps ensure that academic prose:

- uses clear subjects and complete sentences;
- explains unfamiliar terms before relying on them;
- avoids vague references and overloaded sentences;
- avoids mechanical `A, B, and C` lists and unnecessary technical stacking;
- connects paragraphs into a continuous argument rather than a set of isolated topics;
- uses claims that match the available evidence.

It preserves normal, precise academic verbs such as `utilize`, `enable`, `facilitate`, and `demonstrate`. Removing an artificial tone should not make the prose conversational or less exact.

It does not add unsupported motivations, methods, findings, or stronger conclusions.

## Install in Codex

Copy this repository into the Codex skills directory so that the file is located at:

```text
~/.codex/skills/zonity/SKILL.md
```

Codex will then discover `zonity` automatically for relevant academic-writing requests. It can also be invoked explicitly as `$zonity`.

## Install in Claude Code

Copy the same repository into the Claude Code skills directory:

```text
~/.claude/skills/zonity/SKILL.md
```

The skill uses a standard `SKILL.md` file and does not depend on platform-specific instructions.

## Use

Ask the agent to draft or revise academic prose, or invoke the skill explicitly:

```text
Use $zonity to revise the following introduction paragraph.
```

For the complete writing rules, see [SKILL.md](SKILL.md).
