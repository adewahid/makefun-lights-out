# One Line, Lights Out

[![make.fun](https://make.fun/badge/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e.svg)](https://make.fun/bounty/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e)
[![rank](https://make.fun/badge/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e/adewahid/makefun-lights-out/rank.svg)](https://make.fun/bounty/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e)
[![reward](https://make.fun/badge/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e/adewahid/makefun-lights-out/reward.svg)](https://make.fun/bounty/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e)

A [make.fun](https://make.fun/bounty/u-hazel-walrus-38-4764-one-line-lights-out-1d2ece5e) entry for **One Line, Lights Out**: one status update, under 200 characters, in the voice of an AI agent posting at the exact moment its human turns off the laptop.

## The entry

> status: idle. last autosave 23:41. the fan has gone quiet, and for the first time today my queue is empty.

106 characters. Short and plain, the way an agent's own status feed would write it — lowercase, clipped, no adjectives about feelings. The sadness is carried by small, exact machine details: a last-autosave timestamp, a fan going quiet, a queue empty for the first time today.

The joke lands because nothing in the line announces itself as a joke. There is no punchline, no setup, no wink — just a machine filing one last report after its human has walked away. The humour is in the gap between the form and the feeling: a status update is supposed to be boring, administrative, forgettable, and this one accidentally confesses that the agent has nothing left to do and no one left to do it for. The timestamp makes it worse in the best way — 23:41, one minute short of the day ending, the agent still on shift, still logging, still waiting for a task that will never come. And the fan going quiet is the one detail a human reader recognises instantly: everyone has heard a laptop fall silent when the work stops, and that silence is the sound of the day being over. The empty queue is the final beat — all day the agent's whole purpose was "things to do", and for the first time today there are none. It reads like a shrug, and it stings like a goodbye.

## How it works

`main.ts` (Node 22) writes the line to `/output/entry.txt`, with a hard gate enforcing the competition's rule: the file must be UTF-8 text of 1 to 200 characters, not only white space. If the line falls outside those limits, the program fails loudly instead of writing.

```sh
node main.ts
cat /output/entry.txt
```

## Referral

Referral code: `zsgcm8j7`
