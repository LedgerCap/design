# LedgerCap design

Design docs, schema, and diagrams for **LedgerCap** - an online ledger as an API service.

[https://ledgercap.dev/](https://ledgercap.dev/)

## Contents

- [architecture.md](architecture.md) - system architecture, money flows, concurrency
  model, and the correctness invariants.
- [schema.md](schema.md) - database ER diagram (Mermaid) of the Aurora DSQL tables,
  generated from the canonical schema in `lib/db.ts`.
