# Universal Mint Help Center

The customer-facing help center for [Universal Mint](https://universalmint.io), built with [Mintlify](https://mintlify.com).

It covers the Universal Mint app for investors and issuers. It's a help desk, not API documentation. Guides for the platform operator's admin console are kept internally, not in this public repo.

## Structure

| Folder | Covers |
| --- | --- |
| `get-started/` | What Universal Mint is, creating an account, signing in |
| `account/` | Passkeys, recovery, identity verification, wallets, delivery addresses |
| `investors/` | Requesting, redeeming, and tracking tokens |
| `issuers/` | Organizations, teams, approval groups, listing and running tokens |
| `trust/` | How records work, public pages |
| `support/` | FAQ, troubleshooting, glossary, contact |

Navigation lives in `docs.json`.

## Preview locally

```sh
npm i -g mint
mint dev
```

Open http://localhost:3000. Run `mint broken-links` before you push.

## Publishing

Pushes to `main` deploy automatically through the Mintlify GitHub app.

## Writing guidelines

See [CONTRIBUTING.md](CONTRIBUTING.md) for vocabulary, style, and what must stay out of these pages.
