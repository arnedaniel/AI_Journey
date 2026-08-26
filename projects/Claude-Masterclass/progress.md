# Progress Log

A running log of my AI journey. Newest entries at the top.

Currently working through the Udemy course **"The Complete Claude Code & Claude Cowork Masterclass [2026]"** by Prof. Ryan Ahmed (158 lessons, ~22h).

---

## 2026-08-26 (Wed) — Day 21: Memory vs. no memory, and letting Claude Code build the agent

- **L107 — Build a Personal Finance AI Agents with No Memory - Code Walkthrough** (11 min) — Walked through the stateless version of the finance agent line by line: every turn starts from nothing, so the agent re-asks for context it was already given and can't build on earlier answers.
- **L108 — Build a Personal Finance AI Agents with Memory - Code Walkthrough** (3 min) — The same agent with memory added, so prior turns are carried into the next call — a small code change that visibly changes how coherent the conversation feels.
- **L109 — Automate AI Agent Building with Claude Code & OpenAI SDK - Part 1** (11 min) — Started using Claude Code as the thing that *writes* the agent: scaffolding an OpenAI Agents SDK project from a spec instead of hand-writing the boilerplate.
- **L110 — Automate AI Agent Building with Claude Code & OpenAI SDK - Part 2** (9 min) — Continued the build, having Claude Code fill in the agent's tools and instructions and then iterate on what it produced rather than accepting the first pass.
- **Course total: 84/158 lessons — Section 8 at 12/20**

**Next up:** L111 — Automate AI Agent Building with Claude Code & OpenAI SDK - Part 3.

---

## 2026-08-24 (Mon) — Day 20: Kicked off the Personal Finance AI agent project

- **L106 — Build a Personal Finance AI Agents with Memory - Overview** (4 min) — Set up the next project: a personal finance agent that keeps memory across turns, with an overview of what it will do and why memory changes the behaviour compared to a stateless agent.
- **Course total: 80/158 lessons — Section 8 at 8/20**

**Next up:** L107 — Build a Personal Finance AI Agents with No Memory - Code Walkthrough.

---

## 2026-08-20 (Thu) — Day 19: Finished Section 7's Calorie Tracker and opened Section 8 on AI agents

- **L93 — Calorie Tracker Phase 1 - Build a basic app first phase** (18 min) — Built the first working version of the Calorie Tracker with Claude Code: basic app scaffolding and UI, getting something running before layering any AI on top.
- **L94 — Calorie Tracker Project - Phase 2 - Add Gemini AI** (6 min) — Wired the Gemini API into the app so it can actually interpret food input and return calorie estimates instead of relying on manual entry.
- **L95 — Calorie Tracker Project - Phase 2 - Build API Routes plan** (6 min) — Planned the API routes before writing any of them, having Claude lay out the endpoints and data flow first so the implementation had a spec to follow.
- **L96 — Calorie Tracker Project - Phase 2 - Build API Routes in action** (8 min) — Executed that plan, letting Claude Code implement the routes and then testing them against the front end.
- **L97 — Calorie Tracker Project - Phase 3 - Improve with Ralph Loops Plan** (5 min) — Learned the Ralph Loop idea: pointing Claude at the app in a repeated plan-fix-verify cycle so it keeps improving the codebase autonomously, and drafted the plan for it.
- **L98 — Calorie Tracker Project - Phase 3 - Improve with Ralph Loops Implementation** (11 min) — Ran the loop for real and watched it iterate on the app — catching issues and refining features across passes without me prompting each fix.
- **L99 — The AI Agents Revolution and state** (8 min) — Opened Section 8 with why agents are the next step past one-shot prompting: they hold state across turns, so they can pursue a goal over many steps instead of answering once and forgetting.
- **L100 — AI Agents 101** (4 min) — The basic anatomy of an agent — a model plus tools, memory and a loop — and what actually separates one from a plain chatbot.
- **L101 — AI Agents Walkthrough in Action** (10 min) — Watched an agent run end to end: reasoning about the goal, choosing tools, reading results and adjusting on the next pass.
- **L102 — MCP 101** (5 min) — Refresher on the Model Context Protocol as the standard plug for connecting a model to external tools and data, and why it matters once agents need real capabilities.
- **L103 — AI Agentic Frameworks** (3 min) — Quick survey of the agent framework landscape and when reaching for a framework beats wiring the loop yourself.
- **L104 — OpenAI Agents SDK 101** (5 min) — Introduction to the OpenAI Agents SDK: how it models agents, tools and handoffs, and what it handles so you don't have to write the orchestration loop.
- **L105 — Define and Run an AI Agent Using OpenAI Agents SDK** (5 min) — First hands-on with the SDK: defined an agent with its instructions and tools, then ran it and traced what it did.
- **Course total: 79/158 lessons — Section 7 complete at 9/9, Section 8 at 7/20**
- Section 7 "Claude Code for Building Apps" is done ✅ — and Section 8 on AI agents is underway.

**Next up:** L106 — Build a Personal Finance AI Agents with Memory - Overview.

---

## 2026-08-19 (Wed) — Day 18: Started Section 7 — CLAUDE.md, context management, and the Calorie Tracker project

- **L90 — CLAUDE.md Best Practices** (11 min) — Learned how to write a `CLAUDE.md` that actually helps: keeping project context, conventions and commands documented in one place so Claude Code picks them up automatically instead of being re-told every session.
- **L91 — Context Window Management in Claude Code** (10 min) — Practical techniques for keeping the context window under control on longer sessions — being deliberate about what gets loaded, compacting or clearing when it fills up, and structuring work so Claude doesn't lose the thread.
- **L92 — Calorie Tracker Phase 1 - Setup Gemini Key** (9 min) — Kicked off the Calorie Tracker build project by setting up a Gemini API key and wiring it into the project's environment config, ready for the AI features in later phases.
- **Course total: 66/158 lessons — Section 7 at 3/9**

**Next up:** L93 — Calorie Tracker Phase 1 - Build a basic app first phase.

---

## 2026-08-16 (Sun) — Day 17: Finished Section 6 with the plugin competitor-assessment project

- **L85–L87 — Project - Claude Plugin and competitor assessment, Parts 1–3** (29 min) — Built a plugin that runs a competitor assessment end to end: scoped what the plugin should analyse and set up its structure, wrote the skills and instructions that drive the research and comparison, then ran it on real competitors and reviewed the output.
- **L88–L89 — Practice: Competition and Brand Positioning with Plugins** (question + solution, 16 min) — Practised using a plugin to assess competition and map brand positioning on my own, then compared my approach against the walkthrough solution.
- **Course total: 63/158 lessons — Section 6 complete at 23/23**
- Section 6 "Claude Code Foundations" is done ✅ — next stop, building actual apps with Claude Code.

**Next up:** L90 — CLAUDE.md Best Practices.

---

## 2026-08-12 (Wed) — Day 16: Finished slash commands, started Claude Code Plugins

- **L82–L83 — Practice Opportunity Question & Solution - Create a slash command for your brand** (14 min) — Built a brand-specific slash command as a practice exercise, then compared my version against the walkthrough solution to see where the instructions could be tighter.
- **L84 — Claude Code Plugins** (14 min) — Learned what Plugins are in the Claude Code context: bundles that package skills, slash commands and MCP servers together, how to install them from a marketplace, and when a plugin beats a standalone Skill.
- **Course total: 58/158 lessons — Section 6 at 18/23**

**Next up:** L85 — Project - Claude Plugin and competitor assessment - Part 1.

---

## 2026-08-10 (Mon) — Day 15: Slash commands in Claude Code

- **L78 — Claude Slash Commands** (12 min) — Learned what slash commands are in Claude Code: reusable prompt shortcuts stored as markdown files that you invoke with `/name`, and how they differ from Skills.
- **L79–L81 — Project 2. Create Your slash command in Claude Code, Parts 1–3** (34 min) — Built my own slash command end to end: set up the command file and its instructions, wired in arguments, then tested and refined it until it produced consistent output.
- **Course total: 55/158 lessons — Section 6 at 15/23**

**Next up:** L82 — Practice Opportunity Question - Create a slash command for your brand.

---

## 2026-08-05 (Wed) — Day 14: Finished the pet grooming landing page project

- **L77 — Practice Opportunity Solution - Build a Pet Grooming Landing Page with AI** (11 min) — Walked through the solution to yesterday's practice exercise, building the pet grooming landing page end to end with the front-end design Skill and comparing it against my own attempt.
- **Course total: 51/158 lessons — Section 6 at 11/23**

**Next up:** L78 — Claude Slash Commands.

---

## 2026-08-04 (Tue) — Day 13: Claude Code landing pages & the front-end design skill

- **L70 — Intro to Claude Code** (12 min) — Proper introduction to Claude Code: what it is, how the terminal-based agentic loop works, and how it differs from chatting with Claude.
- **L71 — Project 1. Build Landing Pages with Claude Code - No Skill (Part A)** (16 min) — Built a landing page with Claude Code using plain prompting only, to see what the baseline output looks like before adding any Skill.
- **L72 — Understanding Claude Skills & Front-end Design Skill** (11 min) — Revisited how Skills work in the Claude Code context and what the front-end design Skill specifically brings to the table.
- **L73 — Install the front-end design skill** (9 min) — Walked through actually installing the front-end design Skill so Claude Code can pick it up.
- **L74 — Project 1. Building Landing Pages with Front-end Design Skills (Part B)** (12 min) — Rebuilt the same landing page with the Skill active — noticeably better structure and visual quality for the same prompt.
- **L75 — Why Agents and Claude folders containing the same skill.md** (3 min) — Cleared up why the same `skill.md` shows up in both the agents and Claude folders, and which location gets used when.
- **L76 — Practice: Build a Pet Grooming Landing Page with AI** (question, 3 min) — Set up the practice exercise: build a pet grooming landing page end to end on my own.
- **Course total: 50/158 lessons — Section 6 at 10/23**

**Next up:** L77 — Practice Opportunity Solution - Build a Pet Grooming Landing Page with AI.

---

## 2026-08-03 (Mon) — Day 12: Finished Claude Chat, jumped into Claude Code

- **L35 — Extract Financial Data from PDF to Excel and PowerPoint** (7 min) — Pulled structured financial figures out of a PDF and had Claude push them straight into a spreadsheet and a deck, skipping the manual retyping step.
- **L36 — Financial Data Analysis and One Pager Summary Generation with PPTX Skills** (6 min) — Used the PPTX Skill to turn a financial analysis into a clean one-pager summary slide instead of formatting it by hand.
- **L37 — Learn with Claude Chat** (5 min) — How to use Claude as a study partner: asking it to explain concepts at the right level, quiz me, and break down material step by step.
- **L38 — Code with Claude Chat** (4 min) — Using plain chat for coding help — writing, explaining and debugging snippets without needing a full dev setup.
- **L39 — Write with Claude Chat** (6 min) — Writing workflows in chat: drafting, tightening and adapting tone for different audiences.
- **L40 — Claude for Image generation Vs. Gemini** (4 min) — Compared Claude's approach to visuals against Gemini's image generation and where each one is the better tool.
- **L67 — Getting Started with Claude Code in the Desktop App (Method 1)** (8 min) — Started Section 6 by getting Claude Code running through the desktop app — the quickest way in, no terminal setup required.
- **L68 — Claude Code in VS Code: Full Setup + First Workflow (Method 2)** (12 min) — Set up Claude Code inside VS Code and ran a first end-to-end workflow directly in the editor.
- **L69 — Installation and Setup Guide for Mac and Windows** (1 min) — Short reference lesson with the platform-specific install steps and downloadable setup guide.
- **Course total: 43/158 lessons — Section 3 complete at 13/13, Section 6 at 3/23**
- Section 3 "Claude Chat Mastery" is done ✅. Skipped ahead past Sections 4 (Excel) and 5 (PowerPoint) for now to get into Claude Code.

**Next up:** L70 — Intro to Claude Code.

---

## 2026-07-31 (Fri) — Day 11: Prompt engineering, deep research & dashboards

- **L29 — Prompt Engineering Fundamentals Explained** (9 min) — Learned what actually makes a prompt work: giving clear context, a defined role, explicit instructions and a stated output format instead of vague one-liners.
- **L30 — Prompt Engineering Techniques** (8 min) — Covered the practical techniques — few-shot examples, step-by-step reasoning, structured/XML-style sections and iterative refinement — and when each one is worth reaching for.
- **L31 — Deep Research Mode in Claude** (10 min) — Used Claude's deep research mode to run a multi-source investigation on a topic and get back a synthesized, cited report rather than a single-shot answer.
- **L32 — Claude Chat for Creative Writing** (6 min) — Worked with Claude as a writing partner: setting tone and voice, drafting, and iterating on the text instead of accepting the first draft.
- **L33 — Claude For Brainstorming ideas** (3 min) — Short lesson on using Claude to generate and pressure-test ideas quickly, pushing for volume first and then narrowing down.
- **L34 — Develop Dashboards Using Claude Front End Design Skill** (9 min) — Used the front-end design Skill to turn data into a working, good-looking HTML dashboard without writing the UI code myself.
- **Course total: 34/158 lessons — Section 3 at 7/13**

**Next up:** L35 — Extract Financial Data from PDF to Excel and PowerPoint.

---

## 2026-07-30 (Thu) — Day 10: Into Claude Chat Mastery

- **L28 — Using Claude Chat to Perform Research and Data Visualization** (8 min) — Started Section 3 by using plain Claude Chat as a research assistant: gathering and structuring information on a topic, then having Claude turn the findings into charts and visual summaries without leaving the conversation.
- **Course total: 28/158 lessons — Section 3 at 1/13**

**Next up:** L29 — Prompt Engineering Fundamentals Explained.

---

## 2026-07-29 (Wed) — Day 9: Building a finance plugin from scratch

- **L23 — Practical Demo: Create Finance Plugin - Part 1** (13 min) — Started building my own finance plugin, scaffolding the structure and defining what the plugin should be able to do.
- **L24 — Practical Demo: Create Finance Plugin - Part 2** (6 min) — Filled in the plugin's skills and instructions so Claude knows how to handle finance-specific tasks.
- **L25 — Practical Demo: Create Finance Plugin - Part 3** (8 min) — Installed and tested the finished plugin, running it against real finance data to check the output.
- **L26–L27 — Practice: Analyze data plugin** (question + solution, 11 min) — Practiced using a data plugin end to end, then compared my approach against the walkthrough solution.
- **Course total: 27/158 lessons — Section 2 complete at 23/23**
- Section 2 "Mastery for Workflow Automation" is done ✅ — on to Claude Chat Mastery.

**Next up:** L28 — Using Claude Chat to Perform Research and Data Visualization.

---

## 2026-07-28 (Tue) — Day 8: Statistical analysis & financial forecasting

- **L21 — Practical Demo: Data Plugin - Part 4 - Statistical Analysis & PowerPoint** (10 min) — Took the data plugin one step further: ran statistical analysis on the dataset and had Claude turn the results straight into a finished PowerPoint deck.
- **L22 — Financial Forecasting with Claude Cowork with Skills** (14 min) — Used a Skill to build a financial forecast in Cowork, projecting future numbers from historical data instead of modelling it all by hand.
- **Course total: 22/158 lessons — Section 2 at 18/23**

**Next up:** L23 — Practical Demo: Create Finance Plugin - Part 1.

---

## 2026-07-27 (Mon) — Day 7: Plugins & Data Plugin

- **L14 — Practical Demo: Using Skills and LinkedIn posts** (15 min) — Saw a Skill in action, using it to generate ready-to-post LinkedIn content.
- **L15 — Claude Plugins** (7 min) — Learned what Plugins are: bundles that package Skills, commands and tools together, and how they differ from a single Skill.
- **L16–L18 — Practical Demo: Data Plugin, Parts 1–3** (27 min) — Used a data plugin to load, clean and explore a dataset step by step directly with Claude.
- **L19–L20 — Practice: Data Visualization** (question + solution, 8 min) — Practiced turning a dataset into clear charts/visualizations.
- **Course total: 20/158 lessons — Section 2 at 16/23**
- Big day: knocked out 7 lessons and got ahead of my study plan 🎉

**Next up:** L21 — Practical Demo: Data Plugin Part 4 (Statistical Analysis & PowerPoint).

---

## 2026-07-26 (Sun) — Day 6: Agent Skills + Repo setup

- **L13 — Agent Skills** (17 min) — Learned what Skills are: packaged instructions that give Claude reusable, specialized abilities, and when to reach for one.
- Set up my `AI_Journey` GitHub repo: installed Git, cloned it, built the folder structure, learned the `add` → `commit` → `push` workflow.

---

## 2026-07-25 (Sat) — Day 5: Tokens & context

- **L10 — Tokens and Context Window Fundamentals** (10 min) — Understood what tokens and the context window are, and why they limit how much Claude can hold in mind at once.
- **L11–L12 — Practice: Understanding Tokens & Context** (question + solution, 5 min) — Short exercise to lock in the tokens/context concept.

---

## 2026-07-24 (Fri) — Day 4: MCP & Gmail

- **L8 — Model Context Protocol (MCP) and Connectors** (7 min) — Learned what MCP is and how connectors let Claude plug into outside apps and tools.
- **L9 — Practical Demo: Connect Gmail and Sending Emails** (8 min) — Connected Gmail via a connector and had Claude draft and send emails.

---

## 2026-07-23 (Thu) — Day 3: First Cowork demo

- **L7 — Practical Demo: Organizing Files and Using Excel Skills** (15 min) — First hands-on demo: let Cowork tidy up a messy folder and use a Skill to work with Excel data.

---

## 2026-07-22 (Wed) — Day 2: Cowork basics

- **L5 — Introduction to Claude Cowork** (11 min) — What Cowork is: a desktop agent that works directly on your computer, and how it differs from normal Claude chat.
- **L6 — Claude Cowork Capabilities & How it works** (7 min) — Overview of what Cowork can do (files, tasks, sandbox) and the basic mechanics of how it operates.

---

## 2026-07-21 (Tue) — Day 1: Started the course

- **Section 1 complete (L1–L4)** — Masterclass Introduction, Success Tips & Welcome (19 min) — Got oriented, downloaded the course resources, and learned the difference between Claude Cowork, Code, Skills and Plugins.

---

<!-- Template for new entries — copy this above:

## YYYY-MM-DD (Day) — Short title

- **L## — Lesson title** (min) — 1–2 sentences on what I learned.

**Next up:** ...

-->
