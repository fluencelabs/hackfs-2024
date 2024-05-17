# HackFS 2024

[Fluence](https://fluence.network/) is excited to sponsor another edition of HackFS and we are looking forward to hack with you May 15 - June 7, 2024.

## About Fluence


[Fluence](https://fluence.dev/docs/learn/overview), the cloudless off-chain compute protocol, enables a decentralized serverless compute and infrastructure (DePin) platform allowing developers to create compute functions and deploy them to Tier 4 data centers providing provable, decentralized CPU and RAM resources. The Fluence on-chain compute marketplace, built on [IPC](https://www.ipc.space/), facilitates the trustless matching of applications' demand for and providers' supply of capacity, respectively. The Fluence compute marketplace allows developers to deploy applications comprised of just one or many Fluence Compute Functions.


## Hacking With Fluence

The Fluence protocol offers developers for both off- and on-chain hacks. Off-chain projects should use the Fluence cloudless compute stack to create apps or building blocks for app. On-chain projects, on the other hand, should improve the UX of the marketplace and related tooling, such as indexers and explorers, or extend the functionality of the marketplace, e.g., add a spot auction to facilitate cheaper but possibly short(er) lived deals between providers and application developers. 


### Best Use Of Fluence Compute -- USDC 3000, 2500, 1500

Create a decentralized application from Fluence cloudless functions. Your application should use at least three serverless functions (deployed to three different peers) composed and choreographed with Aqua. Alternatively, create a reusable Marine library with at least three distinct API functions and the matching (reusable) Aqua bindings. For either approach, provide ample test coverage with Aqua. 

Need some ideas?

* Get your AI on with Fluence and port the [openai-chagpt-api](https://github.com/uiuifree/rust-openai-chatgpt-api) crate to Marine and implement a demo application using Aqua or
* Embrace cryptography and port a (Rust) MPC TSS library to Marine and implement a demo application covering key generation, signing and key refresh with Aqua

If your application or library requires RPC, consider using [fRPC](https://github.com/fluencelabs/fRPC-Substrate) for bonus points.

### Best Contributions To Improving The Fluence Marketplace -- 3 x USDC 1,000.00

Improve or expand on Fluence [indexing](https://github.com/fluencelabs/deal/tree/main/subgraph), [dashboard(s)](https://github.com/fluencelabs/ops/tree/main/kras/jobs/fluence/blockscout) or [marketplace](https://github.com/fluencelabs/deal/). For a link to the current explorers and dashboards see the [dar network](https://dar.fluence.dev/) page.


For a little inspiration, consider:

* Improve the marketplace by extending/complementing the [matcher](https://github.com/fluencelabs/deal/blob/main/src/core/modules/market/Matcher.sol) with a spot auction or
* Implement (liquid) staking pools to delegators
* Implement a new [faucet](https://faucet.dar.fluence.dev/) using a Web3 auth approach such as [SIWE](https://github.com/spruceid/siwe)


## Submission Guidelines

In addition to the [HackFS Rules & Regulations](https://ethglobal.com/events/hackfs2024), teams need to fork this repo and add their submission. Keep this repo private until the end of the event.

When the number of valid, eligible and equally accomplished submissions exceeds the number of prizes, as determined by the Judge(s), the timestamp of the last change of the submitted repo will serve as the tie-breaker.

An eligible submission requires teams to

* generously document their solution with one or more readme files and, when applicable, code documentation
* commit the complete project scaffold to your forked repo including the .fluence directory
* submit a two (2) to five (5) minute (linked) video shilling your masterpiece. Youtube is penty good enough.
* submit as a Github or GitLab repo with MIT or Apache 2.0 license


## Resources

* [Home](https://fluence.network/)
* [Documentation](https://fluence.dev)
* [Fluence Github](https://github.com/fluencelabs)
* [Fluence Discord](https://fluence.chat/)
* [Fluence Telegram](https://fluence.chat/)


