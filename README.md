# Solana Security Reference — Documentation Site

Documentation site for the [Solana Security Reference](https://github.com/danielAsaboro/solana_badger), powered by [Mintlify](https://mintlify.com).

## Local Development

```bash
npx mintlify dev
```

The site runs at `http://localhost:3000` by default.

## Content

- **6 vulnerability guides** — signer checks, owner checks, type cosplay, arbitrary CPI, PDA sharing, reinitialization attacks
- **2 framework comparisons** — Anchor vs Pinocchio, security trade-offs
- **Video deep dive** — walkthrough of the Security Matrix approach
- **Quickstart** — setup instructions for the parent repo

## File Structure

```
.
├── mint.json                              # Mintlify site configuration
├── index.mdx                              # Landing page & Security Matrix
├── quickstart.mdx                         # Setup & build instructions
├── vulnerabilities/
│   ├── signer-checks.mdx
│   ├── owner-checks.mdx
│   ├── type-cosplay.mdx
│   ├── arbitrary-cpi.mdx
│   ├── pda-sharing.mdx
│   └── reinitialization-attacks.mdx
├── comparisons/
│   ├── anchor-vs-pinocchio.mdx
│   └── security-tradeoffs.mdx
├── videos/
│   └── security-deep-dive.mdx
├── logo/
│   ├── light.svg
│   └── dark.svg
└── favicon.svg
```

## Parent Repository

This docs site is a submodule of [danielAsaboro/solana_badger](https://github.com/danielAsaboro/solana_badger), which contains the vulnerable and secure program implementations, test suites, and build scripts.
