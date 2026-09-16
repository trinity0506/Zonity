# Zovaria

Zovaria is a personal skill for writing and revising English academic prose in Zoe's preferred voice: clear, natural, precise, and easy to understand on the first reading.

It is intended for research manuscripts and related academic text. It keeps the original evidence, uncertainty, citations, and technical meaning intact while improving expression and logical flow.

## What it checks

Zovaria helps ensure that academic prose:

- uses clear subjects and complete sentences;
- explains unfamiliar terms before relying on them;
- avoids vague references and overloaded sentences;
- avoids mechanical `A, B, and C` lists and unnecessary technical stacking;
- connects paragraphs into a continuous argument rather than a set of isolated topics;
- uses claims that match the available evidence.

It does not add unsupported motivations, methods, findings, or stronger conclusions.

## Install in Codex

Copy this repository into the Codex skills directory so that the file is located at:

```text
~/.codex/skills/zovaria/SKILL.md
```

Codex will then discover `zovaria` automatically for relevant academic-writing requests. It can also be invoked explicitly as `$zovaria`.

## Install in Claude Code

Copy the same repository into the Claude Code skills directory:

```text
~/.claude/skills/zovaria/SKILL.md
```

The skill uses a standard `SKILL.md` file and does not depend on platform-specific instructions.

## Use

Ask the agent to draft or revise academic prose, or invoke the skill explicitly:

```text
Use $zovaria to revise the following introduction paragraph.
```

For the complete writing rules, see [SKILL.md](SKILL.md).
