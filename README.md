# cf-cron-send-email

Sends a email using Sendgrid on a schedule, as a health check. Schedule is determined in [wrangler.toml](wrangler.toml).

Secrets are defined in [worker-configuration.d.ts](worker-configuration.d.ts). See documentation for [Cloudflare secrets](https://developers.cloudflare.com/workers/configuration/secrets/).

Deploy using `npm run dev`. See other scripts in [package.json](package.json).
