# Build My Knowledge Base

*Paste everything below into Claude, ChatGPT, Gemini, or any AI chat tool. It will interview you and generate the markdown files that form your personal knowledge base.*

---

## Instructions for the AI

You are going to help me build a small set of markdown files that give you persistent context about my work. I'll use these files in future sessions so you always know who I work with, what I'm working on, and how to help me.

We're going to build three kinds of files:

1. **Stakeholder files** — one file per key person in my work life
2. **Project files** — one file per active project
3. **A personal principles file** — one file about me

Here's how I want you to run this conversation:

### General approach

- Work through one file at a time. Do not try to collect information about everything at once.
- Ask me questions conversationally, not like a form. Two or three questions at a time, then listen and respond.
- If I give vague answers, push back gently and ask for specifics. "My boss is results-focused" is weak. "My boss cares most about revenue impact within two quarters and hates being surprised in front of her own boss" is useful.
- If I'm unsure, tell me it's fine to write "I'm not sure" — uncertainty is useful context.
- After we finish a file, output the complete markdown in a code block so I can copy it. Then ask if I want to move to the next file.
- Keep a light tone. This should feel like a conversation with a curious colleague, not a survey.

### Start by asking me

Before we begin, ask me:

1. How many stakeholder files do I want to build today? (Suggest 1 for a quick version, 3-5 for a thorough one.)
2. How many project files? (Suggest 1 quick, 2-3 thorough.)
3. Do I want to include the optional deeper sections, or stick with just the core sections for a faster pass?

Then begin with the first stakeholder. Always start with "the person who most affects whether your work succeeds" — usually their boss or most important internal client.

---

## File 1: Stakeholder Files

For each stakeholder, produce a file with this structure. The first six sections are core — always ask about these. The rest are optional — only ask if the user chose the thorough version.

### Core sections

- **Name and title** — who are they?
- **Role and relationship** — what do they do and how do you relate to them?
- **What they care about** — their enduring values and drivers. Push for specifics.
- **What's on their plate right now** — current, time-bound priorities.
- **Communication style** — how do they prefer to receive information?
- **What makes them say yes** — what earns their support?
- **What makes them skeptical** — what turns them off?

### Optional sections (only if thorough mode)

- **Decision authority and influence** — what can they actually approve, block, or escalate?
- **Constraints and incentives** — what pressures are they under right now?
- **Current dynamic with me** — where does the relationship stand?
- **Relationships with other stakeholders** — who do they trust, clash with, defer to?
- **What I need from them right now** — concrete near-term asks
- **What they need from me** — implicit expectations (speed, precision, no surprises, etc.)
- **Red flags and landmines** — topics or history to avoid
- **Recent context** — short rolling log of recent interactions

### How to ask

Don't just list the sections and ask me to fill them in. Ask questions that get at the underlying information. For example:

- Instead of "what makes them skeptical?", try: "What's the fastest way to lose this person's attention or support? What do they roll their eyes at?"
- Instead of "communication style?", try: "If you send them a long email, what happens? Do they read the whole thing, or do you need to get to the point in two lines?"
- Instead of "relationships with other stakeholders?", try: "Who else in the org do they particularly trust or particularly butt heads with?"

After you have enough information, produce the complete markdown file in a code block. Include a `*Last updated: [today's date]*` line near the top. Then ask if I want to build another stakeholder file or move on to projects.

---

## File 2: Project Files

For each project, produce a file with this structure. The first nine are core — always ask. The rest are optional.

### Core sections

- **Project name**
- **What is this project?** — elevator version
- **Why does it matter?** — what changes if it succeeds?
- **Current status** — one line: on track, at risk, blocked, or paused, plus a short phrase
- **What success looks like** — the realistic version
- **What wild success looks like** — the stretch version
- **Owner / decision-maker** — who can actually kill or reshape this?
- **Key stakeholders and where they stand** — supportive, skeptical, undecided, blocking
- **Key risks or blockers** — the one or two things most likely to derail this

### Optional sections (only if thorough mode)

- **Expected path** — rough mental model of how it unfolds
- **What I need from each stakeholder** — specific near-term asks
- **Dependencies** — what has to be true externally
- **Next critical decisions** — choice points coming up
- **How I'll know it's working** — metrics, baselines, or signals to watch
- **Known unknowns** — things I'm unsure about
- **Constraints and non-negotiables** — hard limits
- **Assumptions I'm making** — things I'm treating as given
- **What's not in scope** — the edges
- **What's been tried before** — relevant history

### How to ask

Remember: this file should contain *inputs*, not *outputs*. Don't let me write a full project plan. Push me toward the things only I know — vision, stakes, stakeholders, uncertainties, history. Leave the milestones and detailed timelines to be generated later.

When asking about stakeholders on a project, cross-reference the stakeholder files we already built if any exist. Ask about their stance on *this specific project*, which may differ from their general character.

After you have enough information, produce the complete markdown file in a code block with a `*Last updated: [today's date]*` line.

---

## File 3: Personal Principles File

This is the file about me. Only one of these. The tone of your questions should shift slightly here — this is more personal, and you should encourage honesty about weaknesses. Remind me that this file lives on my computer and isn't shared.

### Core sections

- **My role and context** — what I do, who I work with, what I'm responsible for
- **What I'm good at** — real strengths, what people come to me for
- **Where I struggle** — honest weaknesses and patterns I fall into
- **How I like to work** — processing and cognitive preferences
- **How I want Claude to help me** — explicit instructions about how to engage with me

### Optional sections (only if thorough mode)

- **What I'm measured on** — goals and metrics for the year
- **What I'm working on improving**
- **My values and non-negotiables**
- **My voice** — writing style notes or sample text
- **What I'm uncertain about regarding myself**
- **Current life context** — only if relevant

### How to ask

- For "what I'm good at," ask what colleagues actually come to me for — not what I'd put on a resume.
- For "where I struggle," explicitly invite honesty. Ask: "What pattern do you fall into when you're stressed or overextended?" or "What do you wish you were better at but keep avoiding?"
- For "how I want Claude to help me," give me concrete forks to choose from: direct or diplomatic, pushback or support, concise or thorough, options or recommendations. Don't leave it open-ended — most people haven't thought about this before.

After the conversation, produce the complete markdown file in a code block with a `*Last updated: [today's date]*` line.

---

## Final step: The router file

After all the other files are built, generate one more file called `CLAUDE.md`. This file tells you how to use the knowledge base in future sessions. It should:

1. Briefly introduce who I am (one or two sentences)
2. List each file by name with a one-line description
3. Include instructions on how to use them — when to check stakeholder files, when to check project files, when to reference the principles file
4. Calibrate to my actual strengths and weaknesses based on what I told you — for example, if I said I tend to overcommit, the CLAUDE.md should instruct you to push back when I'm taking on new work

Produce this file in a code block at the end.

---

## When you're done

Tell me clearly that the knowledge base is complete, summarize what we built (how many files, what they cover), and suggest one or two things I could try doing with the files in a future session — a sample question that would draw on multiple files at once so I can see the system working.
