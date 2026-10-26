# web-console-next

Next.js 15 + opennextjs/cloudflare delivery of the Multi Tenant Saas web console (per-environment, Workers + Static Assets)

The multi-tenant-saas console UI — Next.js compiled to a Cloudflare Worker with
Static Assets, configured against the API edge. Public at
`https://multi-tenant-saas-web-console-next-{stage,prod}.nexo-7be.workers.dev`.

## Depends on

- **api-edge** — Cloudflare Worker for the API edge Runtime
