# Claude Skills — mwright-com

A collection of installable skills for [Claude](https://claude.ai) (Cowork and Claude Code).

## What are skills?

Skills are installable bundles that give Claude specialized knowledge and capabilities. Install a skill once and Claude automatically uses it whenever your question matches.

---

## Skills in this repo

### 📚 Ringing Cedars of Russia

**File:** `ringing-cedars-anastasia.skill`

A complete reference skill for the *Ringing Cedars of Russia* book series by Vladimir Megre — all 10 books plus structured indexes for characters, glossary, chapter summaries, quotes, parables, cross-references, and a timeline.

**Ask it things like:**
- *"What is the doctor seed ritual?"*
- *"Which books discuss the kin domain concept?"*
- *"Tell me the parable of In Which Temple Should God Dwell"*
- *"What does Anastasia say about raising children?"*
- *"Find a quote from Book 7 about the energy of love"*

---

## Installing a skill

### In Claude Cowork (desktop app)

1. Download the `.skill` file from this repo
2. Open Claude Cowork
3. Go to **Settings → Capabilities → Skills**
4. Click **Install skill** and select the downloaded `.skill` file
5. The skill activates immediately — just start asking questions

### In Claude Code (CLI)

1. Download the `.skill` file from this repo
2. Run:
```bash
claude skill install /path/to/ringing-cedars-anastasia.skill
```
3. Claude confirms installation and the skill is ready to use

---

## What's inside a `.skill` file

A `.skill` file is a ZIP archive containing:
- `SKILL.md` — instructions and trigger description for Claude
- `references/` — bundled reference files (indexes, full book text, etc.)

You can inspect any `.skill` file by renaming it to `.zip` and unzipping it.
