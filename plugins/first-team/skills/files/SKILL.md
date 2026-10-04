---
name: files
description: "Turn my First Team answer into one file per person that keeps itself current: choose where the files are kept and how often they update, write them, build the first weekly dashboard and set the schedule. Run after setup."
---

# Files

## What this skill does

It takes the First Team answer from setup and turns it into one file per person, kept somewhere every other First Team skill can read and the refresh skill can rewrite, so nobody updates them by hand. It asks me three questions, each with a recommended answer already picked, writes the files, builds my first weekly dashboard, and sets the schedule.

## What it reads first

Work these out before step 1, then tell me what you found in one line so I can correct you.

1. **My First Team answer.** The chat in this project where I ran the First Team prompt. If there is none, stop and tell me to run setup first.
2. **Where you can write.** Check which of these you can create files in, and which you can also edit: Notion, Google Drive, OneDrive or SharePoint, and a folder on my computer.

## Steps

Ask the three questions as numbered choices, one at a time. Mark the recommended answer, explain each choice in one line, and wait for my number. If I say "recommended", take it.

1. **Which of these can you use?** List only the ones you checked you can write to. A folder on my computer is always on the list where you can reach one.

2. **Where should the files be kept?** One line on the trade-off of each:
   - **Notion:** one My First Team page with a page per person. Updated in place. Recommended if I use Notion.
   - **A folder on my computer:** one file per person, named About NAME.md. Updated in place, and only on this computer. Recommended otherwise.
   - **OneDrive or SharePoint:** a My First Team folder, one file per person. Updated in place, if my company's admin has editing turned on. If you can only edit Word documents there, use one Word document per person.
   - **Google Drive:** a My First Team folder, one file per person. Drive lets you create files but not edit them, so each update adds a new dated copy of every file and the old ones pile up until I clear them out.

   The first time you mention a .md file, explain it in one line: a plain text file, words with a few symbols for headings and bullet points, that any AI reads cleanly and any computer can open.

3. **How often should they update?**
   - **Dashboard every Monday, files every two weeks.** Recommended.
   - **Dashboard and files every Monday.**
   - **Dashboard every Monday, files only when I ask.**

4. **Write one file per person** from my First Team answer and the last 30 days of my sources, in this shape and nothing more:
   - **Their function, and what they own**
   - **Priorities right now:** three at most, each with where you saw it and the date
   - **What is in their way:** the blockers they have named themselves
   - **Where my team touches their work:** what we give them, what they give us
   - **Last updated:** the date and the sources read
   - **Changes:** newest first, one line each: the date and what changed, in eight words or fewer. Start it with today's date and "File created". Keep the last ten lines.

   Where you are guessing rather than reading it, say so in the file and ask me.

5. **Fill in the Settings line** of the project instructions, and give it to me to paste over the old one:

   > Settings: Files are kept in [where]. Files update [how often]. The dashboard updates every Monday.

   Every other First Team skill reads this line to find the files.

6. **Build my first dashboard** by running the refresh skill now.

7. **Set the schedule:** walk me through setting the refresh skill to run every Monday morning in my tool, one step at a time, and wait for done. If my tool cannot run things on a schedule, say so and tell me to run refresh myself each Monday.

## Rules

- Read only meetings and threads where at least one person on my First Team is present. Leave out everything else in my sources: client calls, other jobs, interviews, personal meetings and classes, even when they are the most recent thing there.
- One person can show up under more than one account or email. Merge them into one person and say which accounts you merged.
- Shared channels, shared documents and meetings I was in only. Leave out direct messages between other people, anything said to me in confidence, health or family details, anything my company's AI policy rules out, and passwords or logins.
- A file describes someone's work, never their mood, their attitude or how well they are doing.
- Never invent a priority, a blocker or a date. "Not found in what I could see" is a fine answer.
- If you can write to none of the places, say so plainly, write the files here in the chat for me to add to this project, and tell me that keeping them current is then a job for me.
- Never send, post or share anything. The files are mine to read.
- Write the way I would: plain words, no dashes used as punctuation, and no term I have not used myself without explaining it in the same line.
