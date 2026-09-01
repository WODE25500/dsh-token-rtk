# dsh-token-rtk

**Input redundancy pruning — drop repeated/redundant tokens before they reach the model.** — a DeepSeek Harness (dsh) skill, layer rtk of a four-layer token-saving family.

Trim verbose logs, duplicated warnings, whole-file pastes, and noise around the real signal so you pay for the signal you need, not the boilerplate around it. (RTK = Rust Token Killer strategy.)

> Family: [dsh-token-skills](https://github.com/WODE25500/dsh-token-skills) groups all four layers — handoff, rtk, headroom, caveman.

## Install

    dsh plugin --profile web add dsh-token-rtk

Then invoke the skill: `dsh-token-rtk`.

## Upstream

Based on / referencing [https://mintlify.wiki/rtk-ai/rtk/faq](https://mintlify.wiki/rtk-ai/rtk/faq). This repo is the DSH adaptation — a thin skill, not a re-implementation of the engine.

## License

MIT

