# Agentic Payments Cheatsheet

[![Pages](https://img.shields.io/badge/read%20it-mariano--aguero.github.io-2e5e4e)](https://mariano-aguero.github.io/agentic-payments-cheatsheet/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A one-page field guide to how AI agents pay for things on the open web: the x402 protocol, payment facilitators, EIP-3009 and Permit2 settlement, CAIP-2 networks, and the AP2 mandate layer above it all.

**Read it here: [mariano-aguero.github.io/agentic-payments-cheatsheet](https://mariano-aguero.github.io/agentic-payments-cheatsheet/)**

## What's inside

- The whole protocol in one annotated HTTP exchange
- The four-layer stack: money, settlement, protocol, authorization
- The three roles (client, resource server, facilitator) and their exact jobs
- HTTP headers, payment schemes, CAIP-2 network ids and USDC addresses
- EIP-3009 vs Permit2, and why buyers never pay gas
- Hosted vs self-hosted facilitators and their trust model
- AP2 mandates in two paragraphs
- The package ecosystem plus minimum viable seller and buyer snippets

Everything is verified against the x402 v2 packages. If something drifts out of date, corrections via PR are welcome.

## Related

- [arbitrum-agent-payments](https://github.com/mariano-aguero/arbitrum-agent-payments): runnable end-to-end kit (Claude agent buying from an x402 API on Arbitrum Sepolia)
- [`@mariano-aguero/x402-self-facilitator`](https://www.npmjs.com/package/@mariano-aguero/x402-self-facilitator)
- [`@mariano-aguero/anthropic-x402-tools`](https://www.npmjs.com/package/@mariano-aguero/anthropic-x402-tools)

## License

[MIT](LICENSE)
