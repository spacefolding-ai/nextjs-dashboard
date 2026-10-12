## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Run locally

Requires Node.js and pnpm.

```bash
pnpm install
cp .env.example .env
pnpm dev
```

The dev server runs at http://localhost:3000.

Required env vars (see `.env.example`):

- `POSTGRES_URL` is the only database variable the code reads. The other `POSTGRES_*` entries in `.env.example` are not used in the code.
- `AUTH_SECRET`: generate with `openssl rand -base64 32`.
- `AUTH_URL`: base URL of the app, e.g. `http://localhost:3000/api/auth`.

To seed the database, open `/seed` while the dev server is running.
