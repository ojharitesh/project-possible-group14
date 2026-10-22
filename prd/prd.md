# PRD: [OPEN — project name]

Team: Ritesh Ojha (Leader), Zhiyang Lin, Ziyi Lian, Aaryan Atreya | Date: 2026-10-22 | Status: Living draft

One-liner: We help students at club fairs, socials, campus events, classes, and other group settings solve starting and maintaining conversations with new people, and we'll know it works when their conversations go beyond generic small talk because they found real common ground and they feel less anxious / more confident afterwards.

## Problem

When students meet new people, they can struggle to identify common ground and start or maintain conversations because of fear of judgment, rejection, or embarrassment. This can cause them to avoid interactions or miss opportunities to build meaningful social connections.

Today, at a club fair, social, or campus event, they stick to friends they already came with, wait for a mutual friend to introduce them, fall back on generic small talk like major/hometown, or look at their phone.

## Target user

Any student at a club fair, social, or campus event trying to talk to strangers — broadened by the team to also include classes and other group settings.

## What we learned from research

- Brainstorming in the team's Oct 19 session surfaced: mutual friends, making the first connection, getting over fear of rejection / eliminating awkward situations, feeling judged, embarrassment to share experiences, and finding common interest getting harder as you get older. — Source: [2026-10-22-problem-space-group-14-updated.md](../research/2026-10-22-problem-space-group-14-updated.md)
- Early takeaway (hypothesis, not yet a research finding): the difficult part is not simply meeting people; the harder part may be knowing how to begin an interaction, discovering common ground, and feeling confident enough to continue the conversation. — Source: [2026-10-22-problem-space-group-14-updated.md](../research/2026-10-22-problem-space-group-14-updated.md)
- [OPEN] No completed user interview findings were shared — the Research Findings section of the source doc was blank.

## Product goals

Help students identify common ground fast, maintain conversation, and connect with others outside the classroom.

We'll know it worked when:
- A student's conversation lasts beyond generic small talk because they found a real common interest (team choice "B").
- The student reports feeling less anxious / more confident afterwards (team choice "D").
- [OPEN] How exactly to check/count "beyond generic small talk" and the confidence measure (scale, threshold, sample) are not yet defined.

## Solutions we considered

1. **Before you talk:** share interests ahead of time and see common ground before approaching — kept for consideration; tradeoffs [OPEN — not discussed].
2. **In the moment:** prompt/starter helper based on context or shared interest — considered, not selected by team.
3. **Structured activity:** low-pressure ice-breaker activity that pairs/groups strangers around shared interest — team favorite; good: everyone expects to join so it feels less awkward and common ground comes out of the activity; hard: there will always be outliers who don't engage.
4. **Introduction broker:** host/mutual friend/system introduces two students with something in common — considered, not selected by team.
5. **After the first hello:** confidence/follow-up helper to keep conversation going and follow up — kept for consideration; tradeoffs [OPEN — not discussed].

## Proposed solution

Leading candidate (not final — to be narrowed Thursday): a structured, low-pressure ice-breaker activity students can use at the start of an event, a class, or other group setting, so they don't have to invent an opener themselves. If a student doesn't vibe with the person they're connected with, they can be matched with someone else.

Elements from options 1 and 5 remain in the potential features below.

## User stories

- As a student at an event, in a class, or in another group setting, I want to join a low-pressure ice-breaker activity, so that I can start talking to someone new without having to invent an opener.
- As a student at an event, in a class, or in another group setting, I want to discover common ground during the activity, so that my conversation can go beyond generic small talk.
- As a student at an event, in a class, or in another group setting, I want to be re-matched with someone else if I'm not vibing with my pair, so that I don't feel stuck.
- As a student at an event, in a class, or in another group setting, I want help keeping the conversation going afterwards, so that I feel more confident.

## Potential features

- A quick way to join a session/activity in that setting.
- A brief way to share interests so pairing or topics can use them.
- Pairing/grouping with someone, plus a re-match option if you're not vibing.
- The ice-breaker activity or prompts themselves, adaptable to event vs. class vs. other settings.
- Timed rounds/rotation so you meet more than one person.
- After-activity prompts to keep talking, and a way to exchange contact/follow up if both want to.

_Prioritization is deferred to Thursday's sprint._

## Key assumptions and risks

- Students are willing to join a structured ice-breaker activity in the setting. Risk: outliers opt out or find ice-breakers cringe — team noted there will always be outliers.
- Joining the same activity leads to genuine common ground. Edge case probed: a student may participate but find nothing they want to keep talking about — team's answer is re-matching with someone else.
- Re-matching is possible (enough other people / time in the setting). [OPEN — not yet confirmed]
- The setting allows the activity (e.g., time/permission in a class). [OPEN — who runs it in each setting not yet decided]
- The hypothesis in "What we learned" holds for target users. [OPEN — awaits user interviews]

## Out of scope

- Dating or romantic matching.
- A general social-media feed / posting platform.
- Guaranteeing lasting friendships or providing mental-health support/counseling.
- Discovering or booking events/classes themselves — this runs within a setting someone else organized.

## Open questions

- [OPEN] Project name.
- [OPEN] Completed user interview findings — do they confirm the early-takeaway hypothesis?
- [OPEN] How to check/count "beyond generic small talk" and how to measure confidence change.
- [OPEN] Who runs/hosts the activity in each setting (event organizer, teacher, student)?
- [OPEN] Tradeoffs for options 1 and 5; whether they are part of the built product or cut Thursday.
- Research to do: run the planned user interviews from the source doc and compare against the hypothesis.
