# Contributing

This organization is primarily for Zervio Solutions internal infrastructure.

## Commit format

Use concise conventional commits:

```text
feat: add service capability
fix: repair deployment issue
docs: update operational documentation
chore: sync service repository
```

## Rules

- Do not commit secrets, `.env` files, tokens, certificates, database dumps, logs, backups, or runtime volumes.
- Verify Docker Compose syntax before deployment with `docker compose config`.
- Keep README files accurate when service behavior changes.
- Production-impacting changes must include a rollback path.
