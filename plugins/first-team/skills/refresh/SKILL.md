---
name: refresh
description: "Build My First Team this week every Monday: where the team's time went, what it talked about, where we overlap, and what to do about it. On the schedule I chose, it also updates each First Team file."
---

# Refresh First Team

## What this skill does

It turns the week into one dashboard I can read in a minute, and on the schedule I chose it brings the First Team files up to date without me touching them. Priorities move, and the person still working to last month's version is the last to find out. The dashboard shows what each of my peers spent the week on, what the whole team kept coming back to, and where their work and my team's work meet, then ends in a few things I can actually do.

## What it reads first

Work these out before step 1, then tell me what you found in one line so I can correct you.

1. **Where my First Team files live.** Read the Settings line in the project instructions. If there are no files yet, stop and tell me to run the files skill.
2. **What you can actually reach,** and the dates it covers. The window is the last full week, Monday to Friday, unless I name another. Say the exact dates.
3. **Whether the files are due.** Read how often the files update from the Settings line, and each file's Last updated line. If the Settings line says files update only when I ask, they are due only when I ask in this chat; a scheduled run leaves them alone and says there is no due date. Otherwise they are due when that much time has passed, or when I ask. Say whether they are due this time.

## Steps

1. **Read the week** across chat, email, calendar, meeting notes and documents, for each person on the file list. Do not search the web.

2. **If the files are due, bring each one up to date** from everything since its Last updated date, in the same shape as before. Change only what moved, update the Last updated line, and add one line to the top of Changes: the date and what changed, in eight words or fewer, for example "18 Oct · New priority: Q4 hiring plan". If nothing moved, add "18 Oct · No change". Then keep only the newest ten lines of Changes. Where the files live decides how:
   - **Notion, OneDrive or SharePoint, or a folder on my computer:** edit each file in place.
   - **Google Drive:** it can create files but not edit them, so add a new version of each file with the date and time in its name (About NAME 2026-10-18 0930.md), so two updates on one day never share a name. Every First Team skill reads only the newest copy of each person's file, by that date and time, and if two copies share a name, the one Drive shows as modified most recently, as the Settings line says. Tell me how many older versions there are, so I can clear them out.

   If the files are not due, leave them alone and say when they will be.

3. **Build My First Team this week** as one page I can open, in the tool's own page builder: an artifact in Claude, a site in ChatGPT. If neither is available, write it as one HTML file I can open in a browser. Update the same dashboard every week rather than making a new one, and say where it is. Three charts at most, each one easy to read in a few seconds, each in clear distinct colours, each with its numbers written under it and shown on hover:
   - **Where the time went:** for each person, the share of their week by area (for example planning, hiring, a launch, customers), as one stacked bar per person. Estimate it from their calendar and the threads they were active in, and label it as an estimate.
   - **What the team talked about:** the topics and keywords that came up most across the whole First Team this week, one bar each, with the count.
   - **Where we overlap:** each area, how many of my peers are working in it, and whether my team touches it. This is the chart that shows where we should be working together.

4. **End with what to do, four at most.** Each one names a person or an area, the evidence, and one action for me this week. For example: "Three of four peers spent the week on Q4 planning. Bring your team's numbers to Thursday."

5. **Tell me what changed since last week** in one line per person, whether the files were updated, and where the dashboard and the files are.

## Rules

- Read only meetings and threads where at least one person on my First Team is present. Leave out everything else in my sources: client calls, other jobs, interviews, personal meetings and classes, even when they are the most recent thing there.
- One person can show up under more than one account or email. Merge them into one person and say which accounts you merged.
- Measure what was said and done. Never score anyone's tone, mood, effort or how engaged they seem.
- A quiet week is not proof of anything. Say "not found in what I could see" instead.
- A share of time is an estimate from what you could see. Say what it was built from, and never present it as a timesheet.
- Shared channels, shared documents and meetings I was in only. Leave out direct messages between other people, anything said in confidence, health or family details, anything my company's AI policy rules out, and passwords or logins.
- Never send, post or share the dashboard or the files. They are mine to read.
- Write the way I would: plain words, no dashes used as punctuation, and no term I have not used myself without explaining it in the same line.
