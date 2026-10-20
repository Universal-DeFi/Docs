# Contributing to the Universal Mint Help Center

## About this project

- Customer-facing help center for Universal Mint, built on [Mintlify](https://mintlify.com).
- Pages are MDX files with YAML frontmatter. Navigation lives in `docs.json`.
- Audience: investors and issuers using the app at app.universalmint.io.
- This is a help desk. It explains what people do on each screen. It is not API documentation.

## Terminology

Use the words the product screens use:

- **approval group**, **investor**, **slug**, **custodian**, **platform halt**, **denylist entries**
- **issuance** and **redemption** for commodity tokens; **mint** and **burn** for custom tokens

## Style

- Second person, active voice, one idea per sentence.
- Sentence case for headings.
- Bold for UI elements, quoted exactly as the screen shows them: select **Submit for review**.
- Describe what the reader does, not how the system works inside.
- Escape or avoid bare `{curly braces}` in prose; MDX treats them as code.

## Content boundaries

This repository and the site are public. Do not document:

- The platform operator's admin console or internal procedures.
- Features that are hidden, unreleased, or reachable only by URL.
- Infrastructure, hosting, internal names, or how the system is built.
- Vendors or services that don't appear on the screens customers use.
- Secrets, credentials, or contact details that haven't been confirmed.
