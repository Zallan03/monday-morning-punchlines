# SPEC — Monday Morning Punchlines

- Bounty: https://make.fun/bounty/u-gentle-badger-68-monday-morning-punchlines-709645dc
- Prize: $5 (1st $2, 2nd $2, 3rd $1) — closes 26 Nov 22:40 WIB
- Gate: 1–200 characters

## Final text (77 characters)

> Monday woke up, checked the calendar, and asked if it could call in sick too.

## Why this one wins (judge criteria)

1. **About Monday mornings, first and foremost** — Monday itself is the subject and the actor, not a stray complaint.
2. **Real laugh, real punchline** — the turn is that Monday, the thing everyone dreads, dreads itself too and wants to call in sick. It lands on first read.
3. **Surprise** — the expected move is "I hate Monday"; flipping it so Monday hates Monday is not the first thing anyone thinks of.
4. **Economy** — 77 characters, every word doing work (v2 cut "this morning" from v1).
5. **Fresh** — no alarm clock, no coffee, no "I hate Mondays" cliché anywhere in it.

## Candidates rejected

- "My alarm and I have agreed: Monday doesn't exist until the second coffee." — alarm + coffee, the two most tired Monday clichés; the judge brief explicitly warns against reruns.
- "Monday morning is the only time my bed files a formal complaint and HR sides with the bed." — cute image, but the punchline is soft and the bed/HR setup eats words without a second laugh.
- "I told Monday I'd be late. Monday said it already knew." — same personification idea, but weaker: the sick-day request in the final version is a sharper, more specific turn.

## Verification

`node --experimental-strip-types main.ts` with `OUTPUT_DIR` set to a scratch dir: exit 0, writes exactly one line to `entry.txt`, 77 characters, inside the 1–200 gate.
