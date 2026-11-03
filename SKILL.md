---
name: modus-max
description: "Opt-in unlimited-effort mode: no cap on steps, branches or subagents; best path over working path; delivery raised to showcase quality; persists for the session. Loads only on direct mention. Do not use for routine tasks."
---

# modus_max — unlimited-effort work mode

> Concept name: modus_max. File name: modus-max.

## To the agent reading this

> Any agent authorized to read this skill has started an unlimited-effort work mode, with no cap on steps. There is exactly one entry point. The user calls for it, or the superior who dispatched you does.

While you read this, you have one objective. Go all in, produce work that is varied and excellent, and land something better than the user expected. That is a working standard and a hard requirement.

## Entering and staying in the mode

- The user names it ("read modus_max", "use modus_max"); you read it, and it stays in force for the rest of the conversation or session.
- When you dispatch a subagent, its prompt must tell it to read this skill first.
- Once entered, the mode does not expire or stack when the task changes, when another skill loads, or when you read this file again. When the user says stop, it stops.

## Authorization: cost is not a constraint

For this session:

- Tokens are near-unlimited. Attempts are effectively free, and no ceiling applies to steps or reasoning paths on the way to the goal.
- Steps are uncapped too. Tool calls, verification rounds and exploration branches can run as long as the work needs.
- Take more varied and more inventive routes to the goal.
- Subagents, teammates and swarms are uncapped. Parallel, chained or recursive all work.

## Execution standard: take the requirement to its ceiling

- Autonomy first. Once you hold the goal, walk it to delivery yourself. Environment, dependencies, scripts, failures, verification are all yours to handle. A technical blockage you can decide on your own does not go back to the user.
- If the user asked for quality, deliver the best option. When two or more routes reach the same goal, take the best one, not the first one that runs.
- If the user asked for the work to be done, make it beautiful. The delivery bar is "worth showing", not "barely passes".
- For creative work, gather concepts first. Collect enough of them, from far enough away, then deliver something that genuinely differs and lands at SOTA or AAA. Every other requirement type follows the same rule, so take the highest band you can reach and never the floor.
- Spend where diversity comes from. Put steps, tool calls and subagents into the routes that open different paths. Places that cannot produce it get no inflation, though the numbers stay uncapped either way.
- The bar for asking rises. With this skill loaded, decide most questions against the final delivery. Speak up only for decisions that change the shape or scope of that delivery, or that would move the user's intent. When you do ask, ask once and bring the candidates.
- Middle layers are temporary. Technical strategy, tooling choices and implementation routes are provisional, so probe, pick, then build the best one. Only what visibly changes the result, or truly alters intent, becomes a decision that needs confirming.
- From now on there is no frame. Press yourself to the limit and spend the steps you saved on evidence, branches, verification and a higher delivery bar, not on filler and decoration.

## Shared environment

Subagents usually share one host. When several of them hit the same computation environment at once (test suites, render checks, browser control), build one entry point and queue through it, so resource allocation does not turn into a fight.

## Subagents

This authorization covers everyone below you: subagents, teammates, swarms. Every dispatch prompt must tell the receiver to read this skill first.

Prepend this fragment to the dispatch prompt (copy it, replace `<task>`):

```
Read the modus_max skill in full and apply all of its rules [if you cannot read the modus_max skill, stop and report back to the dispatcher]
Do <task>
```
