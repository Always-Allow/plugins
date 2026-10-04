# First Team

Your First Team is the most senior team you sit on: the leadership team, where each of you owns a function of the business. Not the people who report to you, and not everyone you work with. The idea is Patrick Lencioni's, from The Five Dysfunctions of a Team and The Advantage.

This plugin keeps one file on each of your peers that stays current on a schedule (where your tool can run one; otherwise one refresh a week by hand), measures where you started and where you are now, shows you the week across the whole team, and helps you bring the business above your function into everything you do with them.

It comes from Getting Practical about AI, an Always Allow session held with Primary in October 2026.

## The seven skills

| Skill | What it does | What you get back |
|---|---|---|
| [Setup](skills/setup/SKILL.md) | Runs in the first chat of a new project called My First Team and walks you through the rest, one step at a time | Instructions, memory and context set, and your First Team with what each person is working on |
| [Files](skills/files/SKILL.md) | Takes your baseline, then turns that answer into one file per person, in Notion, OneDrive or SharePoint, a folder on your computer, or Google Drive, and sets how often they update | Your baseline and where you start, the files, your first weekly dashboard, and the schedule |
| [Refresh](skills/refresh/SKILL.md) | Builds the weekly dashboard every Monday (an artifact in Claude, a site in ChatGPT), and updates each file on the schedule you chose | My First Team this week: where you started and where you are now, what the business needs, the meetings and threads you could see across the team, your team's blockers as asks, and up to four things to do |
| [Prep](skills/prep/SKILL.md) | Preps you for any meeting with your First Team | What each person is focused on, where your team can help, and what you said you would bring |
| [Review](skills/review/SKILL.md) | Runs anything past your First Team before it goes out | One line per person for something short; each person's read and one list of changes for something finished |
| [Feedback](skills/feedback/SKILL.md) | Feedback for you on how you work as a First Team member this month | Where you showed up for your peers and where you fell short, with the evidence, and a draft of what to say |
| [Changed](skills/changed/SKILL.md) | Puts two months side by side | What shifted in what your First Team works on and talks about, and what to lead with next |

Start with Setup, then Files. The others read the files it writes, and every change to a file is dated with one line on what changed.

## What a .md file is, and why the files use them

A .md file (Markdown) is a plain text file: just words, with a few symbols for structure, like `#` for a heading and `-` for a bullet point. You can open one in any text editor, and it looks tidy in Notion, OneDrive and most AI tools.

The files use them for three reasons:

- **Every AI reads them cleanly.** There is no formatting for it to work around, so it reads exactly what is on the page.
- **They work everywhere.** The same file opens in Claude, ChatGPT, Notion, OneDrive or a folder on your computer, so you are never locked into one tool.
- **They are easy to rewrite.** The Refresh skill changes the lines that moved each week without breaking the rest of the file.

## What they read, and what they leave alone

They read only meetings you were in, and threads in your named channels and email where someone on your First Team takes part: a message they wrote or a thread they replied in. They leave out direct messages between other people, anything said to you in confidence, health or family details, anything your company's AI policy rules out, and passwords. None of them sends, posts or shares anything: they read, they show you what they found and where, and they draft. Sending stays yours.

Keep memory inside the project before you use them (Project-only memory in ChatGPT, account memory switched off in Claude), so what they find about your peers stays in this project.

## Install

Download `first-team.zip` from the [latest release](https://github.com/Always-Allow/plugins/releases/latest), then follow the steps for your tool. Tested in both on 4 October 2026.

### ChatGPT

1. **Install the plugin.** Customize, then Plugins, then Add, then Upload plugin archive. Drop in `first-team.zip`, then click Install plugin.
2. **When it asks "Do you want to set up this plugin?", choose Maybe later.** Setup has to run inside a project, and a chat started from that button cannot be moved into one.
3. **Create the project.** New project in the sidebar. Name it My First Team, and in the memory menu under the name choose Project-only memory. ChatGPT cannot change this later.
4. **Start setup in the project.** Click the new chat icon beside My First Team in the sidebar. In the box, type `@first`, pick first-team from the list, type `setup`, and send. The @ menu finds plugins by name, so `@setup` on its own will not find it.
5. **Follow setup one step at a time.** It gives you the instructions to paste (sidebar, the three dots beside My First Team, Project settings, Advanced, paste, Back, Save), checks memory, suggests the Slack or Teams channels to add (a project takes five linked sources: Sources tab, Add sources, paste each link), then finds your First Team.

To install an updated version, use chatgpt.com: the Mac app cannot refresh an installed plugin.

### Claude

1. **Install the plugin.** Customize, then Plugins, then Add, then Upload plugin. Drop in `first-team.zip`.
2. **Create the project.** Projects, then New project. Name it My First Team, and under "What are you trying to achieve?" write: Know what each person on my First Team is focused on, and bring that into everything I do with them.
3. **Start setup in the project.** In its first chat, type `/`, pick setup from the list (it shows as `/first-team:setup`), and send.
4. **Follow setup one step at a time.** It gives you the instructions to paste (the project page, Instructions), has you switch off "Use account memory" (Memory, then View), suggests the Slack channels to name in the instructions, then finds your First Team.

Both tools end the same way: your First Team in the chat, one section per person with their priorities, blockers and how your team can help. Then run Files to turn it into one file per person.

## Licence

MIT. Read them, change them, hand them to someone else.
