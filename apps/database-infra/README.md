# Database Infra

This project contains the database infrastructure for the onepercentr project, managed with Cloudflare D1.

## Migrations

To apply migrations, use the `wrangler` CLI.

### Apply migrations to a local database

```bash
npx wrangler d1 migrations apply onepercentr-db --local
```

### Apply migrations to the production database

```bash
npx wrangler d1 migrations apply onepercentr-db --remote
```
