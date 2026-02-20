# x1-app

Scaffold for a Solana/Anchor-based application with clients, off-chain services, infrastructure, and operational documentation.

## Repository layout

- `docs/`: product, protocol, threat model, schemas, and runbooks.
- `programs/core/`: Anchor on-chain program.
- `clients/`: TS SDK, web app, and optional mobile app.
- `services/`: API, indexer, and keeper bots.
- `infra/`: CI, Docker, and Terraform definitions.
- `scripts/`: deployment and smoke-test helpers.

## Getting started

1. Fill out the documents in `docs/`.
2. Implement and test the Anchor program in `programs/core/`.
3. Build SDK and apps in `clients/`.
4. Add runtime components under `services/` and `infra/`.
