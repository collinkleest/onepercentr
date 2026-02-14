# Backend

This is the Node.js/TypeScript backend for the onepercentr project, built for Cloudflare Workers.

## Development server

Run `nx serve backend` for a dev server. The worker will be available at http://localhost:8787.

## Build

Run `nx build backend` to build the project. The build artifacts will be stored in the `dist/apps/backend` directory.

## Linting

Run `nx lint backend` to execute the linter.

## Testing

Run `nx test backend` to execute the unit tests.

**Note on Cloudflare Workers Testing:**
Currently, there is a known incompatibility between the installed `vitest` version and `@cloudflare/vitest-pool-workers`. For comprehensive Cloudflare Workers testing, please refer to the official Cloudflare Workers documentation and consider alternative testing strategies or check for updates to `@cloudflare/vitest-pool-workers` that support `vitest` v4+.

