# Repbook

[Open the gym tracker](https://sujan-repbook.sujanparajuli786.chatgpt.site)

A mobile-friendly beginner workout journal: exercises, individual sets, weights, reps, lb/kg, private saved history, and heaviest-set progress charts. Source is in `source/`. Hosted with Cloudflare Workers and D1 through Sites; GitHub Pages entry redirects to the private app because Pages cannot run a database backend. No personal workout data is stored in this repository.

Gym image source: https://elitefitnesspr.co/hero_background.png

Install with pnpm install. Configure a logical D1 DB binding, generate migrations with pnpm db:generate, and build with pnpm build. Deployment configuration and authentication are managed by Sites.
