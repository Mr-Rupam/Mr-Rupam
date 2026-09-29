# GTM & Growth Masterclass Prompt

One prompt that turns Claude into a complete Go-To-Market and Growth course, from absolute zero to operator-level mastery. The prompt itself is in [PROMPT.md](PROMPT.md).

## What it does

- **13 levels in 4 phases:** foundations, the engines (positioning, pricing, channels, PLG, sales), the science and the money (experimentation, causal inference, unit economics), and strategy, scale, and the frontier (moats, org design, AI-era GTM). Then a capstone: a GTM simulation game and a board defense.
- **An 8-rung Depth Ladder for every concept:** hook, intuition, mechanism (who pays whom and why), math, evidence, practitioner layer, research and debate, application.
- **Visual teaching:** Explainer Reels (animated, captioned, optionally narrated, video-like artifacts), interactive simulators, scrollytelling case studies, games, cheat sheets, and flashcards.
- **Rigor rules:** tagged and sourced claims, benchmark ranges instead of magic numbers, primary sources (S-1s, DRHPs, research papers), steelmanned debates, and failures taught alongside successes.
- **Learning science:** mastery gating, retrieval practice, spaced repetition, boss fights, field assignments, and a portable Progress Ledger for continuity across chats.
- **23 commands,** including `/reel`, `/sim`, `/deeper`, `/case`, `/boss`, `/interview`, and `/save`.

## Setup

1. On claude.ai, create a Project (for example, "GTM & Growth Masterclass") and choose the latest Opus model.
2. Paste the full contents of `PROMPT.md` into the Project instructions. If the field is too short, add the prompt to the Project knowledge (upload `PROMPT.md` or paste it as text content) and set the instructions to: `Follow PROMPT.md exactly. It is the spec for my course.`
3. Make sure artifacts, web search, and code execution / file creation are enabled, and turn on extended thinking if it is available.
4. Start a chat and send `/start`. To skip the calibration questions, fill in the Learner Profile at the end of the prompt first.

## Tips

- One level per chat keeps responses fast. End each session with `/save` and paste the ledger into the next chat, or add it to the Project files.
- When anything feels surface level, send `/deeper`. When a mechanism feels abstract, send `/reel` or `/sim`.
- Pick a running case early. By the capstone you will have a full GTM dossier for it.
