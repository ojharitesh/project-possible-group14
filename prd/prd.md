# PRD: WarmUp

Team: Ritesh Ojha (Leader), Zhiyang Lin, Ziyi Lian, Aaryan Atreya | Date: 2026-10-22 | Status: Living draft

One-liner: We help students at campus club events and socials solve starting and maintaining conversations with new people, and we'll know it works when participants report discovering a genuine shared interest and their self-reported confidence (1–5 scale, before vs. after) improves.

## Problem

When students meet new people, they can struggle to identify common ground and start or maintain conversations because of fear of judgment, rejection, or embarrassment. This can cause them to avoid interactions or miss opportunities to build meaningful social connections.

Today, at a club fair, social, or campus event, they stick to friends they already came with, wait for a mutual friend to introduce them, fall back on generic small talk like major/hometown, or look at their phone.

## Target user

First version: students attending campus club events and socials, trying to talk to strangers.

Later expansion (out of first-version scope): classes and other group settings. The team initially broadened the scope to include classes/other settings on 2026-10-22, then narrowed the first use case back to club events and socials the same day.

Secondary user: the club leader / event host (organizer) who starts the activity — see Proposed solution.

## What we learned from research

- Brainstorming in the team's Oct 19 session surfaced: mutual friends, making the first connection, getting over fear of rejection / eliminating awkward situations, feeling judged, embarrassment to share experiences, and finding common interest getting harder as you get older. — Source: [2026-10-22-problem-space-group-14-updated.md](../research/2026-10-22-problem-space-group-14-updated.md)
- Early takeaway (hypothesis, not yet a research finding): the difficult part is not simply meeting people; the harder part may be knowing how to begin an interaction, discovering common ground, and feeling confident enough to continue the conversation. — Source: [2026-10-22-problem-space-group-14-updated.md](../research/2026-10-22-problem-space-group-14-updated.md)
- [OPEN] No completed user interview findings were shared — the Research Findings section of the source doc was blank.

## Product goals

Help students identify common ground fast, maintain conversation, and connect with others outside the classroom.

We'll know it worked when:
- A participant reports they discovered a genuine shared interest (team choices "B" + review recommendation adopted 2026-10-22).
- A participant's self-reported confidence improves on a 1–5 scale measured before and after participating (team choice "D" + review recommendation adopted 2026-10-22).
- [OPEN] What counts as a meaningful improvement (threshold, sample size, response rate) is not yet defined.

## Solutions we considered

1. **Before you talk:** share interests ahead of time and see common ground before approaching — kept for consideration; tradeoffs [OPEN — not discussed].
2. **In the moment:** prompt/starter helper based on context or shared interest — considered, not selected by team.
3. **Structured activity:** low-pressure ice-breaker activity that pairs/groups strangers around shared interest — team favorite; good: everyone expects to join so it feels less awkward and common ground comes out of the activity; hard: there will always be outliers who don't engage, and students might feel an organized ice-breaker is awkward or forced.
4. **Introduction broker:** host/mutual friend/system introduces two students with something in common — considered, not selected by team as a standalone option; note the chosen organizer-led model uses the host to start the activity.
5. **After the first hello:** confidence/follow-up helper to keep conversation going and follow up — kept for consideration; tradeoffs [OPEN — not discussed].

## Proposed solution

Leading candidate (not final — to be narrowed Thursday): a structured, low-pressure, **organizer-led** ice-breaker activity at campus club events and socials. A club leader or event host starts the activity that everyone can join, so students don't have to invent an opener themselves. The goal is not simply to introduce two people — it is to help them discover genuine common ground and feel comfortable continuing the conversation. If a student doesn't vibe with the person they're connected with, they can be matched with someone else.

Student-led initiation was considered and not chosen for the first version (decision 2026-10-22).

Elements from options 1 and 5 remain in the potential features below.

## User stories

- As a student at a campus club event or social, I want to join a low-pressure ice-breaker activity, so that I can start talking to someone new without having to invent an opener.
- As a student at a campus club event or social, I want to discover common ground during the activity, so that my conversation can go beyond generic small talk.
- As a student at a campus club event or social, I want to be re-matched with someone else if I'm not vibing with my pair, so that I don't feel stuck.
- As a student at a campus club event or social, I want help keeping the conversation going afterwards, so that I feel more confident.
- As a club leader or event host, I want to start an ice-breaker activity for my event, so that attendees can join in and meet each other without me having to introduce everyone personally. [Derived from the organizer-led decision 2026-10-22 — team to confirm wording]

## Potential features

Core (from review, team to confirm Thursday):
- A quick way to join a session/activity in that setting.
- Discovering common interests / interest-based conversation activities.
- Participating in conversation rounds (including timed rounds/rotation so you meet more than one person).

Secondary:
- Pairing/grouping with someone, plus a re-match option if you're not vibing.
- A brief way to share interests so pairing or topics can use them.
- After-activity prompts to keep talking, and a way to exchange contact/follow up if both want to.

_Prioritization is deferred to Thursday's sprint._

## Key assumptions and risks

- Students are willing to join a structured, organizer-led ice-breaker activity. Biggest risk (from review): students might feel participating in an organized ice-breaker is awkward or forced, or outliers opt out — team noted there will always be outliers. [To be validated in user interviews]
- Organizers (club leaders / event hosts) are willing to start and run the activity at their events. [OPEN — not yet validated]
- Joining the same activity leads to genuine common ground. Edge case probed: a student may participate but find nothing they want to keep talking about — team's answer is re-matching with someone else.
- Re-matching is possible (enough other people / time in the setting). [OPEN — not yet confirmed]
- The hypothesis in "What we learned" holds for target users. [OPEN — awaits user interviews]

## Out of scope

- Dating or romantic matching.
- A general social-media feed / posting platform.
- Guaranteeing lasting friendships or providing mental-health support/counseling.
- Discovering or booking events/classes themselves — this runs within a setting someone else organized.
- First version: classes and other non-club-event settings (later expansion).

## Open questions

- [OPEN] Completed user interview findings — do they confirm the early-takeaway hypothesis, and would students actually participate in a structured, organizer-led activity?
- [OPEN] What confidence improvement on the 1–5 scale counts as success (threshold/sample)?
- [OPEN] Tradeoffs for options 1 and 5; whether they are part of the built product or cut Thursday.
- Research to do: run user interviews with students who attend club events/socials (and, if possible, club leaders/hosts) and compare against the hypothesis.
