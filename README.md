# FlowProp

FlowProp provides on-chain liquidity on **Robinhood Chain** (chain id 4663), starting with **WETH/USDG**.

This repository is for **DEX aggregators and integrators**. It will contain:

- Contract addresses (router and pools) and the supported pairs.
- ABIs for the quote and swap functions and the events.
- How to quote (a view call) and how to swap.
- The pool state that an integrator reads to simulate a swap, and the rule that turns that state into an output amount.
- Price expiry, pause and fee behaviour, and typical gas.

**Status:** pre-deployment. Addresses and ABIs will be published here after the contracts are deployed.

Integration questions: open an issue in this repository.
