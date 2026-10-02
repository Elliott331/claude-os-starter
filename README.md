# Claude OS Starter

**Your AI forgets you every time you open it. This folder fixes that.**

Open it in Claude Code, and the first session interviews you: eight questions about how you write, a few about what you're building. It saves the answers as plain files. From then on, every session starts already knowing who you are and how you sound, and it gets sharper the more you use it.

No install beyond the AI you already use. No database, no plugins. Markdown files you own.

## Start

```bash
git clone https://github.com/Elliott331/claude-os-starter.git my-os
cd my-os
claude
```

Say hello. It sees the folder is new and starts the interview on its own. About fifteen minutes. At the end it writes one short piece in your voice, so you can hear the difference before you've done anything else.

*Using Cursor, Codex or another agent? `AGENTS.md` points it at the same instructions. Rather not use a terminal at all? The same voice interview runs in the browser at [sovereigntystandard.com/voice-dna](https://sovereigntystandard.com/voice-dna).*

## What's in it

```
CLAUDE.md    what your AI reads first, every session
VOICE.md     how you sound: eight patterns, each with your own lines as evidence
ME.md        who you are, what you're building, who it's for, how you work best
work/        one file per project
notes/       ideas, research, anything worth remembering
inbox/       drop anything here; ask it to file
LOG.md       one line per session, which is how it builds up over time
```

Every folder has a `_README.md` that tells you, and your AI, what belongs there.

## Why voice first

Ask an AI to write for you and you get the average of everyone. Telling it "be warm and direct" doesn't help, because that describes half the internet. What it can copy is a pattern with your real line behind it: how you open, where you turn, how you land it, the words you'd never use. `VOICE.md` holds exactly that, and it's the file that makes everything else sound like you.

## What this is, and what it isn't

This is the base: the files your AI needs to know you, and the habit of logging each session so it builds up.

When you want the whole thing, there's the **[Solo OS](https://sovereigntystandard.com/solo-os)** ($97). Same idea, built out as a **10-level quest**: each level walks you through one piece of a one-person business, from your audience to your offer to your content, and a second quest for running it day to day opens once the first is done. It comes with the full folder structure and skills that draft and check your work in your voice. Your `VOICE.md` carries straight over; it uses the same eight dimensions.

More at **[The Sovereignty Standard](https://sovereigntystandard.com/start)**: operating systems for people who'd rather own their tools than rent their attention.

---
*© 2026 CYBERZEN LLC (Charles Kemp). MIT licensed; see [LICENSE](LICENSE). Built by [Charles Kemp](https://charleselliottkemp.com).*
