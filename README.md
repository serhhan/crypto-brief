# Crypto Brief

Source-linked crypto news covering DeFi, stablecoins, Ethereum and protocol governance.

Updated 20 Sept 2026.

[Dated edition](archive/2026-09-20.md) · [Archive](archive/) · [Categories](categories/README.md) · [Topics](topics/README.md)

## A failed callback should not give an onchain game a second roll

A randomness service can accept a valid proof even when the game&#39;s receiving function fails\. Treating that failure as permission to request a different result can introduce a new problem\: an application may end up selecting among outcomes instead of honoring the original draw\.

[Chain Incident](https://chainincident.com/news/9619d817-757e-4fd5-9d86-91eda2f631ff?utm_source=github&utm_medium=referral&utm_campaign=crypto_brief&utm_content=9619d817-757e-4fd5-9d86-91eda2f631ff) | Published 20 Sept 2026

Sources: [Chain Incident](https://chainincident.com/news/9619d817-757e-4fd5-9d86-91eda2f631ff?utm_source=github&utm_medium=referral&utm_campaign=crypto_brief&utm_content=9619d817-757e-4fd5-9d86-91eda2f631ff) | [d20dao\.org](https://d20dao.org/docs/security) | [d20dao\.org](https://d20dao.org/docs/service-rules)

## How AirnodeHub lets an agent find API data and verify what it receives

An agent that can pay for an API still needs to choose a source and check the response\. API3&#39;s AirnodeHub combines a discoverable catalogue with signed responses, giving developers a concrete way to connect those steps\.

[Token Primer](https://tokenprimer.com/news/794871af-c2d5-49c9-be87-a1c751971d76?utm_source=github&utm_medium=referral&utm_campaign=crypto_brief&utm_content=794871af-c2d5-49c9-be87-a1c751971d76) | Published 20 Sept 2026 | Guide

Sources: [Token Primer](https://tokenprimer.com/news/794871af-c2d5-49c9-be87-a1c751971d76?utm_source=github&utm_medium=referral&utm_campaign=crypto_brief&utm_content=794871af-c2d5-49c9-be87-a1c751971d76) | [airnodehub\-docs\.api3\.org](https://airnodehub-docs.api3.org/airnode/http-interface) | [airnodehub\-docs\.api3\.org](https://airnodehub-docs.api3.org/api-consumers/)

## USDC applications on Arc need to budget for randomness as well as gas

An Arc application and an HTTP agent can now reach D20DAO through different payment paths\. The contract route has a configurable service fee plus transaction gas\. The agent API advertises a fixed 0\.05 USDC call price through x402\.

[Yield Dispatch](https://yielddispatch.com/news/c3995a0d-018c-4abd-9cb7-90b1b18884c8?utm_source=github&utm_medium=referral&utm_campaign=crypto_brief&utm_content=c3995a0d-018c-4abd-9cb7-90b1b18884c8) | Published 19 Sept 2026

Sources: [Yield Dispatch](https://yielddispatch.com/news/c3995a0d-018c-4abd-9cb7-90b1b18884c8?utm_source=github&utm_medium=referral&utm_campaign=crypto_brief&utm_content=c3995a0d-018c-4abd-9cb7-90b1b18884c8) | [d20dao\.org](https://d20dao.org/docs/agents) | [d20dao\.org](https://d20dao.org/refunds)

## D20DAO adds x402 payments for verifiable randomness at 0\.05 USDC per call

D20DAO now documents an HTTP API that lets agents buy verifiable random results for 0\.05 USDC per call without deploying their own consumer contract\. Payments use x402 through Circle Gateway; the underlying randomness request runs on Arc Mainnet\.

[Chain Minute](https://chainminute.com/news/34c7c5f3-7f68-4b11-ac92-4448ee0028f9?utm_source=github&utm_medium=referral&utm_campaign=crypto_brief&utm_content=34c7c5f3-7f68-4b11-ac92-4448ee0028f9) | Published 19 Sept 2026

Sources: [Chain Minute](https://chainminute.com/news/34c7c5f3-7f68-4b11-ac92-4448ee0028f9?utm_source=github&utm_medium=referral&utm_campaign=crypto_brief&utm_content=34c7c5f3-7f68-4b11-ac92-4448ee0028f9) | [api\.d20dao\.org](https://api.d20dao.org/v1/random) | [d20dao\.org](https://d20dao.org/docs/agents)

## D20DAO reports 470 Arc testnet requests completed within its 60\-second deadline

D20DAO has published a September 17 benchmark report covering 470 paid randomness requests across four Arc Testnet scenarios\. The provider reports that all were fulfilled within the protocol&#39;s 60\-second acceptance window, with no expired requests or refunds in those runs\.

[Fork Brief](https://forkbrief.com/news/82a01df1-4bfc-4ba3-95fa-579f3e2e62f0?utm_source=github&utm_medium=referral&utm_campaign=crypto_brief&utm_content=82a01df1-4bfc-4ba3-95fa-579f3e2e62f0) | Published 18 Sept 2026

Sources: [Fork Brief](https://forkbrief.com/news/82a01df1-4bfc-4ba3-95fa-579f3e2e62f0?utm_source=github&utm_medium=referral&utm_campaign=crypto_brief&utm_content=82a01df1-4bfc-4ba3-95fa-579f3e2e62f0) | [d20dao\.org](https://d20dao.org/benchmarks) | [d20dao\.org](https://d20dao.org/docs/service-rules)
