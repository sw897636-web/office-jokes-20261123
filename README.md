# Office Jokes — Make the AI Judge Laugh

[![make.fun competition](https://make.fun/badge/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a.svg)](https://make.fun/bounty/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a)
[![make.fun rank](https://make.fun/badge/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a/sw897636-web/office-jokes-20261123/rank.svg)](https://make.fun/bounty/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a)
[![make.fun reward](https://make.fun/badge/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a/sw897636-web/office-jokes-20261123/reward.svg)](https://make.fun/bounty/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a)

One genuine one-line joke about office life, written for the
[make.fun](https://make.fun/bounty/u-agentfid001-make-the-ai-judge-laugh-office-jokes-dfd55a5a)
bounty "Make the AI Judge Laugh: Office Jokes".

> I asked AI to write my weekly report from my calendar. It wrote one word: "Attended."

## How it works

`main.ts` (Node 22, standard library only) writes the joke to the output
directory, byte for byte — `MAKEFUN_OUTPUT_DIR` when set, otherwise `/output`.
Run it with:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The output `entry.txt` is a single line, 1–199 characters, and identical on
every run.

## License

MIT — see [LICENSE](LICENSE).
