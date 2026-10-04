---
name: files
description: "Take my baseline, then turn my First Team answer into one file per person that keeps itself current: choose where the files are kept and how often they update, write them, count where I start, build the first weekly dashboard and set the schedule. Run after setup."
---

# Files

## What this skill does

It takes the First Team answer from setup and turns it into one file per person, kept somewhere every other First Team skill can read and the refresh skill can rewrite, so nobody updates them by hand. Before it writes anything, it takes my baseline: where I am now, written down before anything is built, so I can see later whether it worked. Then it asks me three questions, each with a recommended answer already picked, writes the files, counts my starting numbers, builds my first weekly dashboard, and sets the schedule.

## What it reads first

Work these out before step 1, then tell me what you found in one line so I can correct you.

1. **My First Team answer.** The setup chat in this project, where setup found my First Team. If there is none, stop and tell me to run setup first. If setup left questions I never answered (for example whether I have a team under me, or whether the functions are right), ask them now, in one message, and wait.
2. **My sources.** The sources linked to this project, the chat channels named in the project instructions, and my connected email, calendar and meeting notes. That is the whole list; read nothing else. If a channel on it has had no messages in the last 30 days, say so and suggest one that has.
3. **Where you can write.** Which of these the tools connected here let you create files in, and which also let you edit them: Notion, Google Drive, OneDrive or SharePoint, and a folder on my computer. Judge from the tools you have and never write a test file. Where you cannot tell whether you can edit, say so.

## Steps

1. **Take my baseline.** Say why in one line: "Write down where you are before you build anything. Without a before, you can't show it worked." Then ask these four in one message, and wait:
   1. From memory, what is each person's top priority right now? One line each.
   2. How many minutes would you need to prepare for a leadership meeting to walk in extremely prepared?
   3. How many minutes do you prepare now?
   4. What are your team's top three blockers right now?

   Tell me this is asked once. The numbers you track after today are counted from my sources, never asked again.

Ask the next three questions as numbered choices, one at a time. Mark the recommended answer, explain each choice in one line, and wait for my number. If I say "recommended", take it.

2. **Which of these can you use?** List only the places from "Where you can write", each with what you can do there (create, or create and edit), and ask which ones I use. A folder on my computer is on the list only if you can reach one from this chat. No recommended answer here: it is a question about me.

3. **Where should the files be kept?** Only the places I use. Recommended: Notion if it is connected; otherwise the first place on this list you can edit. One line on the trade-off of each:
   - **Notion:** one My First Team page with a page per person. Updated in place.
   - **OneDrive or SharePoint:** a My First Team folder, one file per person. Updated in place, if my company's admin has editing turned on. If you can only edit Word documents there, use one Word document per person.
   - **A folder on my computer:** a My First Team folder, one file per person, named About NAME.md. Updated in place, and only on this computer. Say that a scheduled run may not be able to reach a folder on my computer, so the files may only update when I run refresh myself.
   - **Google Drive:** a My First Team folder, one file per person. If you can edit files there, they are updated in place. If you can only create them (Google Docs cannot be edited from here), each file is named with the date and time it was written (About NAME 2026-10-04 0930.md), each update adds a new dated copy of every file, every skill reads only the newest one, and the old ones pile up until I clear them out.

   The first time you mention a .md file, explain it in one line: a plain text file, words with a few symbols for headings and bullet points, that any AI reads cleanly and any computer can open.

4. **How often should the files update?** The dashboard updates every Monday whichever I pick.
   - **Every two weeks.** Recommended.
   - **Every Monday.**
   - **Only when I ask.**

5. **Write one file per person** from my First Team answer and the last 30 days of my sources, in this shape and nothing more:
   - **Their function, and what they own**
   - **Priorities right now:** three at most, each with where you saw it and the date
   - **What is in their way:** the blockers they have named themselves; a blocker that is a read rather than something they said is marked "my read" with where it came from
   - **Where my team touches their work:** what we give them, what they give us
   - **Last updated:** the date, and the sources read, named in one short line
   - **Changes:** newest first, one line each: the date and what changed, in eight words or fewer, written like "4 Oct · File created". Start it with that line. Keep the last ten lines.

   Keep everything setup found. Where you cannot find it again in my sources, keep it marked as from setup, so nothing drops without me seeing it. Where you are guessing rather than reading it, say so in the file and ask me.

6. **Check my memory against the files.** Put my answer to the first baseline question beside each file's first priority, one line per person, and count how many match. Say it plainly, for example "You had 2 of 4 right from memory." A miss is the point of the files, never a mark against me.

7. **Count where I start.** From the last 30 days of my sources, count these four, the same way refresh will count them every Monday. All four are about me, never a score of a peer.
   - **Asks answered:** questions or requests a person on my First Team put to me in a shared channel, email or meeting, how many I answered, and the usual time to answer.
   - **Promises kept:** things I said I would send, check, bring or decide, and how many show up afterwards in my sources.
   - **Time with each person:** meetings and shared threads I had with each of them.
   - **The business above my function:** of the points I raised in leadership meetings and the leadership channel, how many were about a company priority or a peer's area rather than only my own function. This one is your judgement of each point: call it an estimate.

   Say what each count was built from. Where a source was not connected, the count leaves it out and says so.

8. **Write my baseline file,** called My baseline, next to the person files: today's date, my four answers from step 1, the memory check from step 6, and the four counts from step 7. Add one line: "Change your team's blockers here when they change." Refresh reads this file every Monday and never changes the rest of it.

9. **Fill in the Settings line** of the project instructions, and give it to me to paste over the old one:

   > Settings: Files are kept in [the exact place, for example the Notion page My First Team, or the folder Documents/My First Team on my computer], with my baseline in My baseline. Files update [how often]. The dashboard updates every Monday.

   If the files are Google Drive dated copies, add: "Read only the newest copy of each person's file, by the date and time in its name; if two copies share a name, the one Drive shows as modified most recently."

   Every other First Team skill reads this line to find the files.

10. **Build my first dashboard** by running the refresh skill now. It builds the dashboard as an artifact in Claude and a site in ChatGPT. Once it is built, give me one more line to add to the Settings line: "The dashboard is [where it is]."

11. **Set the schedule:** walk me through setting the refresh skill to run every Monday morning, one step at a time, and wait for done.
   - **Claude:** on the project page, Scheduled, then Add. Ask it to run the refresh skill every Monday morning.
   - **ChatGPT:** look for scheduled tasks. If you are not sure where it is in my version, say what it is called and ask me to look for it rather than guessing a path.

   If my tool cannot run things on a schedule, or the run could not reach where my files are kept, say so and tell me to run refresh myself each Monday.

## Rules

- Read only meetings and threads where at least one person on my First Team takes part: in a channel, a message they wrote or a thread they replied in; in a meeting, they are on the invite or the notes show them speaking. Posts from bots and apps do not count. Leave out everything else in my sources: client calls, other jobs, interviews, personal meetings and classes, even when they are the most recent thing there.
- A peer's work outside this company (their own business, other clients, a job search) stays out, even when it comes up in a meeting we share.
- One person can show up under more than one account or email. Merge them into one person and say which accounts you merged.
- Shared channels, shared documents and meetings I was in only. Leave out direct messages between other people, anything said to me in confidence, health or family details, anything my company's AI policy rules out, and passwords or logins.
- A file describes someone's work, never their mood, their attitude or how well they are doing. The counts in step 7 are about me alone.
- Never invent a priority, a blocker, a date or a count. "Not found in what I could see" is a fine answer.
- If you can write to none of the places, say so plainly, write the files and my baseline here in the chat for me to add to this project, and tell me that keeping them current is then a job for me.
- Never send, post or share anything. The files are mine to read.
- Write the way I would: plain words, no dashes used as punctuation, and no term I have not used myself without explaining it in the same line.
