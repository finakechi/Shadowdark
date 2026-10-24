# HB-004 — Starting durability and encounter calibration

Status: Proposed  
Version: 0.1 — conditional comparison, not an adopted stat package  
Created / updated: 2026-10-23  
Related decision: SD-018 (Proposed)  
Approval / playtest evidence: none

This follows the character/magic comparisons in SD-013's design order. HP can be compared now, but final encounter tuning depends on the selected abilities, spells, party and recovery rules.

## Verified baseline

The [Player Quickstart](https://drive.google.com/file/d/1jOnqM3KoSxYGIimTHG7PTydr2VIRKf6P/view) uses a class HP die at creation plus CON, minimum 1, subject to ancestry features (pp. 13–18). Fighter uses d8, priest d6, thief/wizard d4 (pp. 18–24). Advancement adds the class die (pp. 37–38); the existing official clarification identifies CON as a first-level adjustment rather than a per-level addition. Rest, death/stabilization and healing are separate rules (pp. 48–53, 60). Source revision is unconfirmed; these statements concern the supplied copy and the previously cataloged official FAQ.

## Starting HP alternatives

Apply the listed creation formula once, with minimum 1 before additional explicit ancestry bonuses; preserve relevant ancestry features except where maximizing a roll makes first-level rolling advantage inapplicable.

| Option | First-level formula before explicit ancestry additions | Benefit | Risk |
|---|---|---|---|
| A. Baseline | Roll class die + CON | Full compatibility; strong fragility | A low roll can overwhelm new tactical options |
| B. Maximum first die | Maximum class die + CON | Removes low-HP creation outliers | Still leaves the smallest-die classes quite fragile |
| C. Maximum first die plus 2 — recommendation to consider | Maximum class die + 2 + CON | Simple starting buffer, no additional tracker | Substantial proportional increase for d4 classes |
| D. Double baseline total | Twice the baseline creation total, after minimum/ancestry | Larger buffer | Keeps random outliers and increases ancestry/healing interactions |

For B/C, ordinary later HP gain remains unchanged in this proposal. Do not add the +2 every level, add CON every level, maximize all future gains or double healing automatically. Existing numerical advancement remains the baseline until separately changed.

D's placement after ancestry is specified for comparison, not recommended. It doubles ancestry's starting HP benefit as well, which is part of its compatibility cost.

### Visible comparison

Before CON, ancestry features or the baseline minimum adjustment:

| Class | Baseline mean die result | B Maximum | C Maximum +2 |
|---|---:|---:|---:|
| Fighter | 4.5 | 8 | 10 |
| Priest | 3.5 | 6 | 8 |
| Thief | 2.5 | 4 | 6 |
| Wizard | 2.5 | 4 | 6 |

These are arithmetic comparisons, not simulations or measured survival rates. Actual outcomes depend on attack accuracy, damage distribution, armor, healing, ancestry, talents and new features. C is a 2.4x increase over the mean d4 roll before modifiers; it is not merely a tiny adjustment for those classes.

Dwarf's additional starting HP remains relevant under B/C, and its HP-roll advantage still affects later rolled gains. Its advantage no longer changes the maximized first die. Review this interaction rather than pretending maximization benefits every ancestry identically.

## Weighted comparison

Tentative judgments for Noah's intended experience, not proven balance. Agency here means room to take meaningful risks, not additional ability choices.

| Criterion | Weight | A Baseline | B Maximum | C Maximum +2 | D Double |
|---|---:|---:|---:|---:|---:|
| Agency | 25% | 2 | 3 | 4 | 4 |
| Challenge | 25% | 5 | 4 | 4 | 2 |
| Compatibility | 20% | 5 | 4 | 4 | 2 |
| Speed / simplicity | 15% | 5 | 5 | 5 | 4 |
| Theme | 15% | 3 | 4 | 5 | 4 |
| Weighted overall / 5 | 100% | 3.95 | 3.90 | **4.30** | 3.10 |

C's challenge score assumes suitable scenarios and retained resource pressure. It is not a finding that current modules keep the same difficulty. Do not use a favorable score to hide unknown spell/feature interactions.

## Recovery and failure

Recommendation for the initial comparison: retain existing rest requirements, healing outputs, stabilization and death procedures. More HP does not automatically create a short-rest healing pool, free recovery between encounters or guaranteed resurrection.

Any change to character death needs its own explicit rule. Situational capture, retreat, lost opportunities, obligations or equipment loss can be appropriate where the fiction supports them; they are not a universal rescue after a death roll. Honor the agreed private boundaries.

## Encounter calibration plan — recommendations, not a multiplier

1. List the actual party's HP, defenses, actions, control, healing, stealth, illumination and traversal capabilities.
2. Assess a basic enemy's attack accuracy and damage distribution against those characters. Consider incapacitation in one or two hits, not only averages.
3. Examine the number of meaningful enemy actions against a three-character group. Control that removes a character can affect a large share of the party.
4. Review how easily characters can avoid the encounter, withdraw, negotiate, obtain information or gain positional advantages.
5. Evaluate resource expenditure across several connected situations: healing, lost spells, light, equipment and recovery access.
6. Adjust selected enemy composition, tactics, terrain or objectives where the new abilities actually change the encounter. Retain some easier obstacles as a reward for strength.
7. Make major hazards legible through clues and warnings. Do not raise every trap's damage simply to preserve a fixed chance of instant death.
8. Review HB-001's unresolved encounter cadence separately from enemy statistics. Changing spawn rate and damage together can conceal the cause of excess attrition.

A boss does not automatically need three attacks because there are three PCs. Likewise, doubling HP does not imply doubling every enemy's damage. Avoid encounter formulas imported from another game without evidence.

## Interactions and evidence needed

- Combat/survival: changes risk of abrupt incapacitation; accuracy, control and concentrated attacks still matter.
- Noncombat: a larger buffer can make some hazards easier; preserve decisions rather than secretly negating the buffer.
- Resources: unchanged healing may restore a smaller share of total HP; do not rescale it without analysis.
- Progression: a first-level flat bonus matters less proportionally as later HP grows.
- Class/ancestry: d4 classes gain proportionally more; dwarf roll interactions require acknowledgment.
- GM burden: a single creation formula is simple, but encounter review needs the actual character sheets.
- Failure: the probability of reaching 0 changes; the consequence procedure does not change automatically.
- Test: after abilities/magic and one HP option are selected for Testing, inspect both a combat and an expedition segment. Record incapacitations, retreat, depleted healing and dominant control effects. Do not force a target death rate.
- Rollback: change HP only at a clear boundary, never during damage resolution. Agree how current HP converts and avoid killing a character solely because the test ends. Record fictional outcomes as history rather than undoing them.

No encounter or durability test has been conducted. No final enemy statistics, starting HP formula or death alternative is adopted by this document.
