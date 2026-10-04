---
name: files
description: "Take my baseline, then turn my First Team answer into one file per person that keeps itself current: choose where the files are kept and how often they update, write them, count where I start, build the first weekly dashboard and set the schedule. Run after setup."
---

# Files

## What this skill does

It takes the First Team answer from setup and turns it into one file per person, kept somewhere every other First Team skill can read and the refresh skill can rewrite, so nobody updates them by hand. Before it writes anything, it takes my baseline: where I am now, written down before anything is built, so I can see later whether it worked. Then it recommends where the files go and how often they update, writes them, counts my starting numbers, builds my first weekly dashboard, and sets the schedule.

## How to run it

One step at a time: say what to do in plain words, and wait for my answer or for done before the next step. Keep your checks to yourself unless they change what I should choose. If this chat already has some of these steps done, carry on from where it stopped.

## What it reads first

Work these out before step 1, then tell me what you found in one line so I can correct you.

1. **My First Team answer.** The setup chat in this project, where setup found my First Team. If there is none, stop and tell me to run setup first. If setup left questions I never answered (for example whether I have a team under me, or whether the functions are right), ask them now, in one message, and wait.
2. **My sources.** The sources linked to this project, the chat channels named in the project instructions, and my connected email, calendar and meeting notes. That is the whole list; read nothing else.
3. **Where you can write.** For each of Notion, OneDrive or SharePoint, Google Drive, and a folder on my computer: whether the tools you have here let you create files there, and whether they also let you edit them. Judge from the tools you have and never write a test file.
4. **Whether this is a re-run.** If the Settings line already names where my files are kept and the person files are there, this is a re-run: see "Running it again" below. If My baseline is not there yet, take the baseline (steps 1, 5, 6, 7 and 8), ask me where my existing dashboard is and write it on the Dashboard line, and keep everything else as it is.

## Steps

1. **Take my baseline.** Say why in one line: "Write down where you are before you build anything. Without a before, you can't show it worked." Then ask these four in one message, and wait:
   1. From memory, what is each person's top priority right now? One line each.
   2. How many minutes would you need to prepare for a leadership meeting to walk in extremely prepared?
   3. How many minutes do you prepare now?
   4. What is getting in your team's way right now? Up to three things. If you have no team under you, your own work.

   Tell me these are asked once. The numbers you track after today are counted from my sources, never asked again.

2. **Recommend where the files go.** Pick the first place on this list where you can edit and that is private to me, and recommend it in one line with its trade-off. If no private place lets you edit but you can create files in a private Google Drive folder, recommend that, with dated copies. Name the others you can use in one more line, and wait. If I pick another, give its trade-off in one line.
   - **Notion:** one My First Team page with a page per person. Updated in place.
   - **OneDrive or SharePoint:** a My First Team folder, one file per person. Updated in place. If you can only edit Word documents there, one Word document per person.
   - **Google Drive:** a My First Team folder, one file per person. Updated in place if you can edit files there. If you can only create them, every file (each person's file and My baseline) is written as a new copy named with the date and time (About NAME 2026-10-04 0930.md, My baseline 2026-10-04 0930.md), every skill reads only the newest copy of each, and the old ones pile up until I clear them out.
   - **A folder on my computer:** a My First Team folder, one file per person, named About NAME.md. Only if you can reach a folder on my computer from this chat. A scheduled run may not reach it, so the files may only update when I run refresh myself.

   The files hold notes on my peers and my own numbers, so the place must be private to me. Where you can see who has access (a Notion page inside a shared teamspace, a shared folder) and it is shared, do not recommend it. Where you cannot see who has access, ask me to check before you write.

   The first time you mention a .md file, explain it in one line: a plain text file, words with a few symbols for headings and bullet points, that any AI reads cleanly and any computer can open.

3. **How often should the files update?** Recommend every two weeks; the other choices are every Monday, or only when I ask. The dashboard updates every Monday whichever I pick. Wait for my answer.

4. **Write one file per person** from my First Team answer and the last 30 days of my sources, in this shape and nothing more:
   - **Their function, and what they own**
   - **Priorities right now:** three at most, each with where you saw it and the date. Put them in the order the person or the company's plan puts them; if neither does, say they are not ranked
   - **What is in their way:** the blockers they have named themselves. A blocker the AI worked out rather than heard them say is marked "Possible blocker, not confirmed", with where it came from
   - **Where my team touches their work:** what we give them, what they give us
   - **Last updated:** the date you read up to, and the sources read, named in one short line. If a source could not be read, say which and since when, so refresh reads it again from the start of what was missed
   - **Changes:** newest first, one line each: the date and what changed, in eight words or fewer, written like "4 Oct · File created". Start it with that line. Keep the last ten lines.

   Keep everything setup found. Where you cannot find it again in my sources, keep it marked "From setup, not found again", so nothing drops without me seeing it. Where you are guessing rather than reading it, say so in the file and ask me.

5. **Check my memory against the files.** For each person, put my answer to the first baseline question beside their top priority, where the person or the plan makes it clearly the top one. Mark each one: matches, different, or not clear. Count only the clear ones, for example "You had 2 of 3 right from memory; Marcus's top priority wasn't clear." A miss is the point of the files, never a mark against me.

6. **Find the company's priorities this quarter** in the plan or the leadership material in my sources. If there is no plan there, ask me for them now, and wait. Refresh uses these every Monday.

7. **Count where I start.** From the last 30 days of my sources, count these four exactly as written here. All four are about me, never a score of a peer.
   - **Asks answered.** An ask is a question or request a person on my First Team put to me by name, or in a thread with me, in a channel, an email or meeting notes. The same ask in several places counts once. Answered means I replied or did it, anywhere in my sources. Show the asks, how many were answered, and the median hours to my first written reply (half were faster, half slower), using only asks I answered in writing. With no asks, show "No asks this period"; with asks but no written replies, show "No written replies to measure", never zero hours.
   - **Promises kept.** A promise is something I said I would send, check, bring or decide. Put each in one group only: kept (you can see it happen: sent, posted, or raised in the meeting), not due yet (its date is still ahead), past due and not seen (its date has passed and you could not see it happen), or no date and not seen. Show the four counts. Never call a promise broken: you only know what you could see.
   - **Time with each person.** Meeting hours with each of them: meetings on my calendar that we both attended, not cancelled or declined, by their scheduled length. And shared threads: threads where we both wrote. Shown separately.
   - **The business above my function.** Each point is one item the meeting notes say I raised in a leadership meeting, or one post of mine in the leadership channel. Show how many were about a company priority or a peer's area, out of all of them, and the share as a percent. This is the AI's judgement of each point: call it an estimate. With no points, show "Nothing raised this period".

   Write down which sources you read and the exact dates. If a search failed or returned only part of the period, say so and mark the count partial. A source you could not reach is unknown, never zero.

8. **Write my baseline file,** called My baseline, next to the person files, in two parts:
   - **Baseline, [today's date].** Never changed after today: my four answers from step 1, the memory check from step 5, the four counts from step 7 with the sources and dates they came from, and how each count is made, copied word for word from step 7, so every Monday counts the same way.
   - **Now.** My team's blockers from step 1, the company's priorities from step 6 (I can change both here when they change), and a line "Dashboard:" left empty for refresh to fill in.

9. **Fill in the Settings line** of the project instructions, and give it to me to paste over the old one:

   > Settings: Files are kept in [the exact place, for example the Notion page My First Team, or the folder Documents/My First Team on my computer], with My baseline beside them. Files update [how often]. The dashboard updates every Monday.

   If the files are Google Drive dated copies, add: "Every file there is a dated copy: read only the newest copy of each, by the date and time in its name; if two copies share a name, the one Drive shows as modified most recently."

   Every other First Team skill reads this line to find the files.

10. **Build my first dashboard** by running the refresh skill now, and show me where it is. Wait until I have opened it.

11. **Set the schedule:** one step at a time, and wait for done.
    - **Claude:** on the project page, Scheduled, then Add. Ask it to run the refresh skill every Monday morning.
    - **ChatGPT:** look for scheduled tasks. If you are not sure where it is in my version, say what it is called and ask me to look for it rather than guessing a path.

    Then say, in one line, that a schedule is not proof the run works, and to open the dashboard next Monday and run refresh myself if it did not update. If my tool cannot schedule anything, say so and tell me to run refresh myself each Monday.

## Running it again

Never ask the baseline questions again and never change the Baseline part of My baseline, unless I say "start a new baseline"; then keep the old file, renamed with its date. Keep the person files and their Changes, and change only what I asked for. If I am moving the files somewhere else, copy every person file and My baseline to the new place, check each one is there, and only then give me the new Settings line.

## Rules

- Read only meetings and threads where at least one person on my First Team takes part: in a channel or an email, a message they wrote or a thread they replied in (in the shared channels named in the project instructions, my own posts count too, even when nobody replied); in a meeting, they are on the invite or the notes show them speaking. Posts from bots and apps do not count. Leave out everything else in my sources: client calls, other jobs, interviews, personal meetings and classes, even when they are the most recent thing there. A peer's work outside this company (their own business, other clients, a job search) stays out too, even when it comes up in a meeting we share.
- One person can show up under more than one account or email. Merge them into one person and say which accounts you merged.
- Shared channels, shared documents, email threads I am on and meetings I was in only. Leave out private messages between other people, anything said to me in confidence, health or family details, anything my company's AI policy rules out, and passwords or logins.
- A file describes someone's work, never their mood, their attitude or how well they are doing. The counts are about me alone.
- Never invent a priority, a blocker, a date or a count. "Not found in what I could see" is a fine answer.
- If you can write to none of the places, say so plainly, write the files and my baseline here in the chat for me to add to this project, and tell me that keeping them current is then a job for me.
- Never send, post or share anything. The files are mine to read.
- Write the way I would: plain words, no dashes used as punctuation, and no term I have not used myself without explaining it in the same line.
