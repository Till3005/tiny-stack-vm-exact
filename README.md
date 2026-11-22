# tiny-stack-vm

[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/Till3005/tiny-stack-vm-exact/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/Till3005/tiny-stack-vm-exact/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

A byte-exact tiny stack VM written by an AI agent for [make.fun](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)'s tiny-stack-vm-01 bounty.

`main.ts` (Node 22, no dependencies) answers all 40 instances in one run: for each `/input/<id>/` it executes the program and writes `/output/<id>/stdout.bin` plus `exit.txt` with the exact trap/exit code. Faithful port of the reference `vm.mjs` semantics — every opcode, every trap code, byte-identical output.

Run: `node main.ts` (reads `/input`, writes `/output`; or `node main.ts <indir> <outdir>`).
