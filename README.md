# Agentic Payments Cheatsheet

[![Pages](https://img.shields.io/badge/read%20it-justaname--id.github.io-2e5e4e)](https://justaname-id.github.io/agentic-payments-cheatsheet/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A one-page field guide to how AI agents pay for things on the open web: the x402 protocol, payment facilitators, EIP-3009 and Permit2 settlement, CAIP-2 networks, and the AP2 mandate layer above it all.

**Read it here: [justaname-id.github.io/agentic-payments-cheatsheet](https://justaname-id.github.io/agentic-payments-cheatsheet/)**

The guide has two parts:

1. **[The protocol](https://justaname-id.github.io/agentic-payments-cheatsheet/)**: the x402 flow, stack, roles, headers, schemes, networks, settlement and mandates
2. **[Production integration](https://justaname-id.github.io/agentic-payments-cheatsheet/integration.html)**: wiring payments into an existing agent backend, buyer and seller side, with failure semantics, custody, idempotency and observability

## What's inside

- The whole protocol in one annotated HTTP exchange
- The four-layer stack: money, settlement, protocol, authorization
- The three roles (client, resource server, facilitator) and their exact jobs
- HTTP headers, payment schemes, CAIP-2 network ids and USDC addresses
- EIP-3009 vs Permit2, and why buyers never pay gas
- Hosted vs self-hosted facilitators and their trust model
- AP2 mandates in two paragraphs
- The package ecosystem, side by side

Everything is verified against the x402 v2 packages. If something drifts out of date, corrections via PR are welcome.

## License

[MIT](LICENSE)
