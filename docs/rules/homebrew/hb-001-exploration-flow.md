# HB-001 — Conversational exploration with timed pressure checks

Status: Proposed  
Version: 0.1  
Created / updated: 2026-10-23  
Related decisions: SD-012, SD-013, SD-015; recommendation SD-014 (Proposed)  
Approval: none; not an active experiment or accepted campaign rule  
Sources: uploaded Quickstart, folder labeled V2-4; internal revision unconfirmed

## Problem and desired behavior

Noah found exploration too cumbersome to track, particularly when characters had few interesting options. The agreed goal is natural exploration, more room for useful actions, and retained torchlight pressure. This proposal addresses exploration flow first; character powers, magic redesign, durability and encounter statistics are later work.

For roughly three players and 3–4-hour virtual sessions, routine exploration should require a shared light countdown and one automatic GM reminder. Individual turn order and a crawling-round counter are absent during ordinary exploration. Use rounds temporarily when their timing matters.

## Confirmed play-mode distinction

Noah clarified this direction on 2026-10-23 (SD-015):

| Situation | Intended handling |
|---|---|
| Combat | Turn-based play with initiative |
| Ordinary exploration, investigation, travel within a scene and conversation | Freeform; no routine round-by-round turn cycle |
| A specific immediate noncombat danger | Temporary turns/rounds for that situation, with a clear reason to track order |
| Light failure in a dangerous area | Immediately enter urgent crawling rounds and apply the published darkness restrictions/cadence |
| Immediate urgency resolved | Return to freeform play |

The ten-minute reminder is a proposed background exploration mechanism, never a grace period before danger takes effect. Other justified urgent cases can include a chase, flooding room or collapsing route. Do not classify every ordinary task as urgent simply to restore continuous round tracking. Timing-sensitive abilities need explicit handling in the next design phase; their existence must not automatically turn unrelated exploration into perpetual rounds.

This confirms the mode distinction, not acceptance of HB-001's numerical thresholds, ten-minute interval or complete package.

## Baseline and affected rules

Read the [verified exploration baseline](../exploration-baseline.md) for printed page references to the [Player Quickstart](https://drive.google.com/file/d/1jOnqM3KoSxYGIimTHG7PTydr2VIRKf6P/view) and [GM Quickstart](https://drive.google.com/file/d/1QPuHQLBpwRCGKLSZk5B03Qar9ih9xdXB/view).

The baseline already permits loose order and simultaneous group declarations (Player p. 45), regrouping (p. 47) and generally one light timer (p. 46). Its wandering encounters still depend on crawling rounds (GM p. 14), and personal timers advance with turns (Player p. 45). The minutes-pass encounter rule is on Player p. 44.

This proposal replaces ordinary crawling-round counting, ordinary individual exploration turns, the routine wandering-encounter cadence and the minutes-pass encounter check. It also states a campaign clock-pause convention. It preserves source-backed checks, consequences, expertise, light constraints and round-sensitive procedures except where explicitly changed below. It does not claim equal encounter difficulty.

## Four approaches compared

| Approach | How it works | Main benefit | Main cost |
|---|---|---|---|
| A. Strict published turn sequence | Count individual turns and party rounds; apply book cadence. | Explicit spotlight and maximum compatibility. | Retains Noah's primary administrative friction. |
| B. Published freeform option | Declare and act loosely or simultaneously; GM recognizes each completed party round. Keep published encounter and effect timing. | Smallest change; existing official option. | GM still tracks party-round completion and cadence. |
| C. Group actions with round counting | Each meaningful shared step is a proposed crawling round; parallel tasks resolve together, longer tasks occupy later steps. Keep the 3/2/1-round encounter cadence. | One group counter replaces individual turn accounting. | Step boundaries can be subjective; round-sensitive effects still need care. |
| D. Conversation with timed checks — recommendation | Explore conversationally, keep real light, use an automatic ten-minute encounter reminder, and enter rounds when timing becomes important. | Removes routine party-round counting. | Recalibrates encounters; short magic and split parties remain exceptions. |

Approach C is a conceptual alternative, not a second complete approved procedure. Approach B is the strongest fallback if D changes challenge too much or its two automatic clocks prove less convenient than one small GM counter.

## At-table summary

This card summarizes the proposal; the sections below resolve exceptions.

1. Explore in conversation. Invite parallel tasks and keep everyone involved.
2. Keep the shared real light timer. Let a separate GM reminder run every ten active minutes. Pause both for breaks/technical or declared out-of-game needs; light keeps running in combat.
3. At the reminder, roll one d6: unsafe 1, risky 1–2, deadly 1–3 triggers a wandering encounter. Skip due reminders in combat; do not queue them or reset the reminder when replacing light.
4. State meaningful task durations before commitment. For a time skip, advance light and reminders together, resolving the next event before continuing. Charge elapsed time only once.
5. Use ordinary check/competence rules. Minor interaction does not require a separate roll or administrative turn.
6. Use short rounds when order, immediate danger or a round-sensitive effect needs them. Do not convert short magic into ten-minute magic.
7. Darkness in a dangerous area prompts urgent crawling rounds with the published 1-in-6 encounter check each round, replacing reminder checks while that sequence lasts.
8. For extended rests/travel, use the published hour-based procedures. Separate groups can require extra rolls/light tracking.

No individual routine exploration turn tracker or new resource pool.

## Exact proposed procedure: approach D

### 1. Scope and clocks

Use this procedure while exploring a dangerous site. It is not the travel/rest procedure for hours or days.

- Keep one visible shared light countdown, normally 60 minutes for the current hour-long light source. Use the book's shared-light/replacement convention (Player p. 46).
- Start one separate, GM-controlled repeating reminder for every **10 minutes of active play** in the dangerous site.
- Changing rooms, lighting a replacement torch, starting a conversation or finding treasure does not restart that reminder.
- Light continues during player planning, character conversations, ordinary GM descriptions and combat.
- Pause both clocks for breaks, technical trouble, accessibility needs, and clearly declared out-of-game rules teaching or lookup. Resume after the pause. This pause convention is proposed campaign procedure, not an asserted quotation from the book.
- A routine question about what a character perceives is part of play. Do not add an artificial time charge for it or turn every short clarification into a timer dispute.
- A genuinely secure location has no wandering checks while it remains secure; light still expires unless its source says otherwise. A door being closed does not by itself certify safety.

The clocks need not appear as two player-facing widgets: only the light must be visible. Automated reminders are a convenience, not a requirement to buy or choose a VTT now. They cannot automate fictional time skips without a manual adjustment.

### 2. Conversation and concurrent activity

The GM describes what is apparent. Players say what they do without a fixed rotation. Several characters may undertake compatible tasks concurrently.

Before resolving a major commitment, the GM asks whether the other characters are doing something alongside it. Do not finish a second substantial action for the same player while another player is trying to contribute. Prompt overlooked players naturally; do not add a persistent turn-completion checklist.

Bundle trivial handling with the meaningful task. Declaring an action instantly does not make it take no time. The GM estimates meaningful durations for searches, reading, work, movement or rituals when the amount matters.

Only compatible work happens concurrently: one character cannot perform two mutually exclusive tasks, and two people cannot each claim a unique occupied tool. A specific helper needs a plausible contribution; this proposal grants no automatic assistance bonus or extra actions in a timed round.

Travel through a known stretch may be narrated quickly, but still consumes its estimated fictional travel time. Moving rapidly through conversation is not teleportation or a way to bypass unopened doors, hazards or patrol routes.

### 3. Checks and information

Use the source-backed check framework (Player p. 43; GM pp. 12, 16). A suitable method and training can resolve an action without dice. Make consequences, a relevant time cost and reasonable alternatives clear before commitment where the characters could know them.

Do not roll separately for every drawer or repeatedly roll for the same unchanged attempt. If a failed attempt can be retried, require a changed approach, a stated expenditure of time/resources, or another concrete change. This is adjudication guidance, not a blanket prohibition on trying another idea.

The rules do not turn vague declarations such as searching an entire complex into one instant automatic success. Establish area, method and duration. Information gained is useful even when further action remains necessary.

### 4. Wandering pressure

At each ten-minute reminder, roll **one d6** for the group's current area:

| Area | An encounter occurs on |
|---|---|
| Unsafe | 1 |
| Risky | 1–2 |
| Deadly | 1–3 |

These are provisional homebrew thresholds. They replace the baseline 1-in-6 check every 3/2/1 crawling rounds. Use one declared danger category grounded in the location; do not increase it merely to cancel good play.

Resolve the due check after the current brief action or exchange, before another substantial declaration. Do not wait until an entire long scene ends.

Use creature activity, starting distance, reaction and the location's encounter material to establish what happens. A patrol can be detected, avoided or negotiated with. Do not force combat whenever the die triggers an encounter.

While combat is underway, skip due ambient reminder checks. Do not queue them or deliver a stack of encounters at combat's end. The repeating reminder keeps its phase; combat does not restart it. Light keeps burning. Existing creatures, reinforcements and scenario events act for their own reasons and are not suppressed by this rule.

A loud or conspicuous disturbance can prompt one extra check using the area's threshold, unless an established nearby creature's response already settles the consequence. Do not charge both a due reminder check and an extra noise check for the same event at the same moment. Do not treat every failed check as loud or roll repeatedly for one continuing sound.

### 5. Time-consuming tasks and fictional time skips

Before commitment, state the remaining time a task requires. If the party says it spends ten minutes doing something, advance the clocks by ten fictional minutes instead of making the players wait ten real minutes.

Advance to the next relevant event (light expiry, a pressure reminder, a known deadline) and resolve it. Continue the task only if circumstances permit. Roll for every ten-minute reminder crossed while exploring, using the current area's threshold. An interrupted task consumes only the time reached, not its entire promised duration.

Charge an interval once. If time already played out at the table represented part of the task, skip only its remaining duration. Ordinary conversation uses active real time; there is no additional automatic ten-minute charge per room, declaration or investigation.

If remaining light is insufficient, resolve expiry and any replacement light at that point. Never silently complete a long dark task on one expired torch.

This replaces the single 1–3 encounter check in the book's minutes-pass procedure. Do not apply both systems to one skip. Its changed risk is a deliberate experimental component, not claimed equivalence.

For a declared skip of minutes, round-duration effects expire as in the published time-pass guidance. Advance minute/hour durations by elapsed time. No cheap refresh of spent abilities is introduced.

### 6. Temporarily use rounds when timing matters

Use ordinary short turns and rounds for combat, a chase, an immediate trap/hazard, a drowning/escape timer, or another situation where order and seconds of opportunity matter. Resume conversation when exact timing no longer matters and no active turn-sensitive effect requires accounting.

For combat, use the published surprise and new combat-initiative procedure (Player pp. 49–50). For a noncombat urgent sequence, establish a clear order with the published initiative method; the GM resolves relevant world changes each round. This does not add attacks, reactions or other actions.

**Short spells and focus are not converted to ten-minute effects.** If an ongoing effect needs turn/round checks, temporarily use group rounds and its published countdown/checks for as long as needed. A scene transition alone does not erase an effect. A declared minutes skip does expire round-based effects under the cited time-pass rule.

A focus spell is therefore a real limitation of this first draft's simplicity. We will examine that interaction in the next magic-design phase rather than silently grant permanent buffs or waive focus checks.

### 7. Total darkness

Light expiry immediately changes what characters can do. Apply the book's visibility restrictions. In a dangerous area, enter urgent crawling rounds until light is restored or the group escapes the relevant danger.

In this darkness sequence, use the published **1-in-6 check after each crawling round**, not the ten-minute threshold. Skip reminder-based ambient checks while these darkness rounds are active; do not duplicate them. Once combat starts, use the normal combat exception above.

This deliberately retains a stronger consequence than waiting ten more minutes after the last torch fails. No automatic disadvantage is imposed on a creature to which the source's darkness restriction does not apply.

### 8. Split parties, rest and longer travel

One GM reminder can serve all separated subgroups. At a due check, make a separate roll for each subgroup exploring a distinct dangerous area, using that area's category. Within the same immediate scene, do not multiply checks by headcount.

Switch scenes at comparable points in fictional time; do not let one subgroup gain an hour of actions while the other is frozen. Spatially separate groups may need separate light sources and exceptional light timers, just as the shared-light simplification can have exceptions. Splitting can increase bookkeeping and encounter exposure; it is not forbidden or punished without a fictional cause.

Keep the book's hour-based rest/overland encounter procedures for extended rest/travel. Do not roll six ten-minute exploration checks per hour of an eight-hour rest. Resolve supplies and light by their actual durations, including any published campfire rules. If play resumes moment by moment before the rest/travel completes, resume exploration from that point.

### 9. What is actually tracked

Ordinary combined-party exploration uses a light countdown, the automatic ten-minute reminder, the current danger category and actual consumables. No ongoing round number, per-player exploration turn tracker, mandatory exploration jobs or new resource pool is added.

Special dangers, active short magic and separated parties create extra accounting only while relevant. This proposal does not claim to eliminate existing inventory, health or magic resources.

## Worked example — original situation

The party enters a risky underground hall with fresh light. One character examines a gate, another studies familiar carvings, and the third watches the approaches. They act concurrently without three separate movement turns; the GM checks for consequences rather than three automatic skill rolls.

After ten active minutes, the reminder triggers. Light has about fifty minutes remaining. The GM rolls a 5: no wandering encounter.

The party then commits to fifteen more minutes of careful mechanical work. The GM advances time to the next reminder ten minutes later, rolls once for the risky area and gets a 4. With no interruption, the remaining five minutes of work pass. Light now has about thirty-five minutes left, and the next reminder is five minutes away. The task did not reset either clock or require fifteen real minutes of waiting.

Had the first roll produced an encounter, resolution would interrupt the task at that point. Remaining work would not be charged until attempted.

## Weighted evaluation

Scores are tentative design judgments for this group's stated preferences. They are not measurements or playtest results. Criteria/weights are the agreed rubric.

| Criterion | Weight | A Strict baseline | B Official freeform | C Group-round alternative | D Timed proposal |
|---|---:|---:|---:|---:|---:|
| Agency and meaningful options | 25% | 3 | 4 | 4 | 4 |
| Preservation of meaningful challenge | 25% | 4 | 4 | 4 | 4 |
| Compatibility and balance | 20% | 5 | 5 | 4 | 3 |
| Speed and simplicity | 15% | 2 | 3 | 3 | 5 |
| Theme / campaign experience | 15% | 4 | 4 | 4 | 5 |
| Weighted overall, out of 5 | 100% | **3.65** | **4.05** | **3.85** | **4.10** |

Judgments:
- A's explicit allocation helps spotlight, but routine personal turns are poorly matched to Noah's reported friction. It remains the compatibility benchmark.
- B improves conversational freedom with no new encounter conversion. Remaining round recognition limits the predicted simplicity gain.
- C simplifies some declarations but makes a group-step boundary an additional ruling and retains counting.
- D is recommended for the strongest reduction in routine counting and real torch pressure. Its challenge score is conditional on meaningful encounter frequency, time skips, darkness handling and actual preparation. Its compatibility score is lower because the encounter clock and minutes-pass rule change.
- D's numerical edge over B is only 0.05 and is not decisive evidence. If D's challenge score falls from 4 to 3, its total becomes 3.85; B then leads. Recommend D because it directly tests Noah's priority, while keeping B available as a lower-change fallback.
- D's simplicity score is a prediction for routine exploration with automated reminders. Frequent focus spells or party splits could reduce it materially.

## Risk calibration and calculations

For one uninterrupted hour of ordinary exploration, six independent reminder rolls imply:

| Area | Chance per check | Expected triggered encounters | Chance of at least one |
|---|---:|---:|---:|
| Unsafe | 1/6 | 1 | 66.5% |
| Risky | 2/6 | 2 | 91.2% |
| Deadly | 3/6 | 3 | 98.4% |

Calculation: expected count = 6p; chance of at least one = 1 - (1-p)^6. These are exact dice-model calculations rounded for display, not observed session results. They exclude combat-skipped reminders, noise, fictional skips, rests, darkness rounds and scripted events. Triggered encounters are not a forecast of fights.

The published system's expected count depends on how quickly this table completes crawling rounds. We have no observations of that rate, so no claim of equivalent danger is justified. Ten minutes and the thresholds are a starting calibration, not fixed campaign canon.

## Interaction audit

| Area | Effect / unresolved risk |
|---|---|
| Combat power / survivability | No direct stat changes. Encounter frequency can change total attrition; skipping due combat reminders avoids ambient pileups while light still runs. |
| Noncombat problem-solving | Compatible tasks can run together; no new success bonus or obstacle-bypass ability. Duration must prevent unlimited instant work. |
| Resources | Real light and declared time costs remain. Task batching and encounter conversion can alter resource use. |
| Encounter difficulty / risk | Individual encounter statistics unchanged; frequency is replaced and uncalibrated. Darkness restores urgent published checks. |
| Progression | XP rules unchanged; different encounter/treasure discovery rates may change practical pace. |
| Classes / abilities | Expertise remains. Short-duration and focus effects temporarily require rounds; later expanded magic must be reviewed. |
| GM preparation | Requires current danger category, encounter material and rough durations for lengthy tasks, not a full time ledger. |
| Rules complexity | Routine counting reduced, but skip, urgent-timing and split-party exceptions are real costs. |
| Failure | Check probabilities unchanged unless a situation changes. Time and wandering consequences are explicitly altered. |
| Player agency / access | Prompt quiet players; pause for out-of-game needs. Speed of speech must not grant extra fictional action capacity. |

## Proposed test, evidence and rollback

No playtest has been run. Noah must choose Testing before table use.

A first test can be one 45–60-minute exploration segment inside a normal session, with an exit to conversation and a few sample long tasks. Include one short-duration ability and a light-expiry situation in a brief GM walkthrough so the exceptions are understood; this is a recommendation, not a required unmodified pilot or a new session commitment.

Record a small number of observations: did players wait for turns, did anyone dominate, how often did the GM stop to account for time, were pressure rolls meaningful, did light affect a choice, and did focus/urgent timing undo the convenience? A few tally marks and a short debrief are enough; do not create a per-action research burden.

Change one calibration at a time if necessary: reminder interval or threshold, not several parameters at once. Preserve successful player decisions; do not add encounters only because the party made progress.

Rollback at a clear pause to published freeform mode (B), restore the 3/2/1-round encounter cadence and the published minutes-pass rule, and keep actual remaining light/resources. Begin the new encounter-round count from zero at the stated transition. Do not refill light, rerun past checks or restore spent resources merely because the procedure changed. Record the reason and mark this version Rejected, Superseded or still Proposed as appropriate.

## Clarification history

2026-10-23: Added SD-015's explicit distinction between combat initiative, freeform ordinary exploration and specific temporary noncombat rounds. No numerical rule or full-package status changed.

## Review status

Recommendation: try approach D after review, with B as fallback. All timings, thresholds and exceptions in this document remain Proposed. This document does not authorize magic, durability or encounter-stat changes.
