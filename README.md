# Awesome Cloudflare Workers

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of projects, libraries, tools, and resources for [Cloudflare Workers](https://developers.cloudflare.com/workers/).

## Contents

- [Projects](#projects)
- [Frameworks and Adapters](#frameworks-and-adapters)
- [Libraries and Tools](#libraries-and-tools)
- [Official Resources](#official-resources)
- [Contributing](#contributing)

## Projects

Open-source applications that use Workers as a core part of their architecture.

- [Cloud Mail](https://github.com/maillab/cloud-mail) - Multi-user email service using Workers, D1, KV, R2, Workers AI, and Email Routing.
- [Cloudflare ImgBed](https://github.com/MarSeventh/CloudFlare-ImgBed) - File hosting and personal cloud drive with a Workers deployment using Static Assets, R2, and D1 or KV.
- [Cloudflare Temp Email](https://github.com/dreamhunter2333/cloudflare_temp_email) - Temporary email service using Workers, Pages Functions, D1, Email Routing, KV, and optional R2 and Workers AI.
- [Counterscale](https://github.com/benvinegar/counterscale) - Self-hosted web analytics using Workers and Analytics Engine, with long-term event storage in R2.
- [Flare Stack Blog](https://github.com/du2333/flare-stack-blog) - Full-stack blog CMS using Workers, D1, R2, KV, Durable Objects, Workflows, Queues, Workers AI, and Images.
- [FlareDrive](https://github.com/longern/FlareDrive) - Self-hosted R2 file manager with a browser interface and WebDAV access, using Workers and Pages.
- [Hacker Podcast](https://github.com/miantiao-me/hacker-podcast) - Daily Hacker News podcast generator using Workers, R2, KV, Workflows, and Browser Rendering.
- [LetterDrop](https://github.com/i365dev/LetterDrop) - Self-hosted newsletter manager using Workers, Email Workers, D1, KV, R2, and Queues.
- [microfeed](https://github.com/microfeed/microfeed) - Self-hosted CMS for podcasts, blogs, media, and curated links using Pages Functions, D1, R2, and Access.
- [MoeMail](https://github.com/beilunyang/moemail) - Multi-user temporary email service using Pages, D1, KV, Email Workers, and scheduled cleanup Workers.
- [NodeWarden](https://github.com/shuaiplus/nodewarden) - Bitwarden-compatible password vault running on Workers with D1 and R2, or KV as an alternative.
- [Pastebin Worker](https://github.com/SharzyL/pastebin-worker) - Encrypted paste and file-sharing application using Workers, KV, and R2.
- [R2 Explorer](https://github.com/G4brym/R2-Explorer) - Self-hosted file manager for R2 with previews, multipart uploads, sharing, and Access support.
- [Rin](https://github.com/openRin/Rin) - Serverless blogging platform using Workers, Pages, D1, and R2.
- [Serverless QR Code Hub](https://github.com/xxnuo/serverless-qrcode-hub) - QR-code and short-link manager using Workers, D1, Static Assets, and scheduled triggers.
- [Sink](https://github.com/miantiao-me/Sink) - Self-hosted link shortener using Workers, D1, KV, Analytics Engine, and optional R2 and Workers AI.
- [UptimeFlare](https://github.com/lyc8503/UptimeFlare) - Self-hosted uptime monitoring and status pages using Workers, D1, Pages, and scheduled triggers.
- [Web Archive](https://github.com/Ray-D-Song/web-archive) - Self-hosted webpage archiving and sharing service using Workers, D1, R2, and Workers AI.
- [Bark Worker](https://github.com/cwxiaos/bark-worker) - Self-hosted Bark push notification server using Workers with D1 or KV storage.
- [free4.chat](https://github.com/i365dev/free4chat) - Voice, chat, screen-sharing, and file-sharing application using Workers, RealtimeKit, KV, Durable Objects, AI Gateway, and Turnstile.
- [InsightFlare](https://github.com/RavelloH/InsightFlare) - Privacy-focused web analytics using Workers, Durable Objects, D1, KV, optional R2 archiving, and Analytics Engine.
- [mail2telegram](https://github.com/tbxark/mail2telegram) - Telegram bot that forwards messages from Email Routing using Workers, KV, and optional Workers AI summaries.
- [Serverless Cloud Notepad](https://github.com/s0urcelab/serverless-cloud-notepad) - Self-hosted browser notepad using Workers and KV, with deployment through GitHub Actions.
- [SonicJS](https://github.com/SonicJs-Org/sonicjs) - Beta headless CMS using Workers, D1, R2, and KV, with an administrative interface and content APIs.
- [D1 Manager](https://github.com/JacobLinCool/d1-manager) - Web interface and API for managing D1 databases, deployed on Pages with Access and optional Workers AI semantic queries.
- [YAOS](https://github.com/kavinsood/yaos) - Self-hosted real-time Obsidian synchronization using Workers, Durable Objects, WebSockets, and optional R2 attachments and snapshots.
- [EdgeEver](https://github.com/tianma-if/edgeever) - Self-hosted notes workspace using Workers, D1, R2, Pages, Static Assets, and a remote MCP endpoint.
- [Second Brain for AI](https://github.com/rahilp/second-brain-cloudflare) - Self-hosted shared memory service for AI clients using Workers, D1, Vectorize, Workers AI, KV, and MCP.
- [2FA](https://github.com/wuzf/2fa) - Self-hosted two-factor authentication secret manager using Workers and KV, with encrypted storage, PWA offline access, and backup and restore.
- [Discohook](https://github.com/discohook/discohook) - Discord webhook composer and bot using Workers, Durable Objects, Hyperdrive, PostgreSQL, and Valkey.
- [ShareHTML](https://github.com/jonesphillip/sharehtml) - Collaborative document sharing using Workers, Durable Objects, R2, WebSockets, and optional Access authentication.
- [git-on-cloudflare](https://github.com/zllovesuki/git-on-cloudflare) - Git Smart HTTP server using Workers, Durable Objects, D1, R2, and Queues, with a browser interface and personal access tokens.
- [Codra](https://github.com/devarshishimpi/codra) - Self-hosted AI pull request reviewer using Workers, Queues, Workflows, Hyperdrive, and KV.
- [AwaitStep](https://github.com/awaitstep/awaitstep) - Visual Cloudflare Workflows builder using Workers, D1, and sandboxed container builds.
- [Weft](https://github.com/jonesphillip/weft) - Self-hosted AI task board using Workers, Durable Objects, Workflows, Sandbox, and optional Access authentication.
- [SaaSMail](https://github.com/choyiny/saasmail) - Self-hosted team email platform using Workers, Email Routing, D1, R2, Queues, Durable Objects, and WebSockets.
- [Auth Inbox](https://github.com/TooonyChen/AuthInbox) - Self-hosted verification-code inbox using Workers, Email Routing, D1, optional Workers AI extraction, and KV-backed MCP authentication.
- [CattoPic](https://github.com/Yuri-NagaSaki/CattoPic) - Self-hosted image hosting with format conversion, tagging, and APIs using Workers, R2, D1, KV, optional Queues, and Images.
- [workers-firecrawl](https://github.com/G4brym/workers-firecrawl) - Self-hosted Firecrawl-compatible search endpoint using Workers and Browser Rendering.

## Frameworks and Adapters

- [Astro Cloudflare Adapter](https://github.com/withastro/astro/tree/main/packages/integrations/cloudflare) - Official Astro adapter for rendering and deploying applications on Workers.
- [Hono](https://github.com/honojs/hono) - Web Standards framework with first-class Workers support.
- [itty-router](https://github.com/kwhitley/itty-router) - Small router designed for Workers and other edge runtimes.
- [Nitro](https://github.com/nitrojs/nitro) - Server toolkit with Workers deployment presets, also used by Nuxt.
- [OpenNext Cloudflare](https://github.com/opennextjs/opennextjs-cloudflare) - Adapter for deploying Next.js applications to Workers.
- [RedwoodSDK](https://github.com/redwoodjs/sdk) - Server-first React framework built for the Cloudflare runtime.
- [SvelteKit Cloudflare Adapter](https://github.com/sveltejs/kit/tree/main/packages/adapter-cloudflare) - Official SvelteKit adapter for Workers.
- [PartyKit](https://github.com/cloudflare/partykit) - Real-time application libraries built on Workers and Durable Objects, including WebSocket server and client packages.
- [vinext](https://github.com/cloudflare/vinext) - Beta Vite-based implementation of the Next.js API surface with Workers as its primary deployment target.
- [tldraw Sync for Cloudflare](https://github.com/tldraw/tldraw-sync-cloudflare) - Collaboration backend for tldraw using Workers, WebSockets, Durable Object SQLite storage, and R2 assets.
- [Slack Cloudflare Workers](https://github.com/slack-edge/slack-cloudflare-workers) - TypeScript framework for Slack applications on Workers with request verification, listeners, and lazy execution.
- [django-cf](https://github.com/G4brym/django-cf) - Django integration for Python Workers with D1 and Durable Object database backends, R2 storage, and Access authentication.
- [Ohkami](https://github.com/ohkami-rs/ohkami) - Rust web framework with first-class support for Workers, Durable Objects, WebSockets, and OpenAPI generation.
- [Better Auth Cloudflare](https://github.com/zpg6/better-auth-cloudflare) - Better Auth integration for Workers with D1, Hyperdrive, KV, R2, and Cloudflare geolocation support.
- [Spiceflow](https://github.com/remorses/spiceflow) - Type-safe API and React Server Components framework with Workers runtime integration, bindings, and KV page caching.

## Libraries and Tools

- [Alchemy](https://github.com/alchemy-run/alchemy) - TypeScript infrastructure-as-code toolkit with Workers and binding support.
- [Drizzle ORM](https://github.com/drizzle-team/drizzle-orm) - Type-safe ORM and migration tooling with D1 support.
- [Sentry Cloudflare SDK](https://github.com/getsentry/sentry-javascript/tree/develop/packages/cloudflare) - Error monitoring and tracing SDK for Workers.
- [Denoflare](https://github.com/skymethod/denoflare) - Tooling for developing, testing, and deploying Workers with Deno.
- [workers](https://github.com/syumai/workers) - Experimental Go package for running standard HTTP handlers on Workers through WebAssembly.
- [workers-qb](https://github.com/G4brym/workers-qb) - Query builder for D1, Durable Object SQLite, and PostgreSQL from Workers.
- [Takumi](https://github.com/kane50613/takumi) - Rust and WebAssembly image renderer for Workers that generates Open Graph images, SVG, GIFs, and video frames without Browser Rendering.
- [cfworker](https://github.com/cfworker/cfworker) - Collection of Workers-optimized packages for Web Crypto, JSON Schema, streaming CSV, error reporting, UUIDs, and HTTP utilities.
- [Turborepo Remote Cache Cloudflare](https://github.com/AdiRishi/turborepo-remote-cache-cloudflare) - Self-hosted Turborepo remote cache using Workers, R2 or KV storage, and scheduled artifact cleanup.
- [hostc](https://github.com/akazwz/hostc) - HTTP and WebSocket tunnel tooling using Workers and Durable Objects.
- [Ducklings](https://github.com/tobilg/ducklings) - DuckDB WebAssembly packages for Workers with Iceberg and DuckLake support.
- [OpenTelemetry for Cloudflare Workers](https://github.com/evanderkoogh/otel-cf-workers) - OpenTelemetry-compatible tracing for Workers, Durable Objects, KV, D1, service bindings, and outgoing requests.
- [effect-cf](https://github.com/danieljvdm/effect-cf) - Pre-1.0 Effect primitives for Workers, Durable Objects, KV, Email, Analytics Engine, Workers AI, and Browser Rendering.
- [workers-zig](https://github.com/nilslice/workers-zig) - Early-stage Zig SDK for Workers, Durable Objects, Workflows, D1, R2, KV, Queues, Workers AI, Vectorize, and Hyperdrive.
- [Cloudflare Email Kit](https://github.com/JacobLinCool/cloudflare-email-kit) - Composable Email Workers packages with R2, D1, and Queues integrations.
- [Sayiir](https://github.com/sayiir/sayiir) - Durable workflow engine with a dedicated Workers WebAssembly runtime and D1-backed persistence.
- [Cloudflare Browser CDP](https://github.com/miantiao-me/cf-browser-cdp) - Early-stage authenticated Chrome DevTools Protocol proxy for the Browser Rendering binding.

---

## Official Resources

### Documentation

- [Changelog](https://developers.cloudflare.com/changelog/?product=Workers) - Product updates, runtime changes, and deprecation notices.
- [Cloudflare Workers Documentation](https://developers.cloudflare.com/workers/) - Official documentation for the runtime and Developer Platform.
- [Platform Limits](https://developers.cloudflare.com/workers/platform/limits/) - Current limits for Workers and related resources.
- [Workers Playground](https://workers.cloudflare.com/playground) - Browser-based editor for trying Workers without a local setup.
- [Workers Runtime APIs](https://developers.cloudflare.com/workers/runtime-apis/) - Reference for runtime APIs, bindings, and Web Platform support.

### Development and Testing

- [Cloudflare Vite Plugin](https://github.com/cloudflare/workers-sdk/tree/main/packages/vite-plugin-cloudflare) - Runs and builds Vite applications against the Workers runtime.
- [Create Cloudflare](https://github.com/cloudflare/workers-sdk/tree/main/packages/create-cloudflare) - Official project and framework scaffolder.
- [Miniflare](https://github.com/cloudflare/workers-sdk/tree/main/packages/miniflare) - Local Workers simulator powered by workerd.
- [workerd](https://github.com/cloudflare/workerd) - Open-source JavaScript and WebAssembly runtime that powers Workers.
- [Workers Vitest Integration](https://github.com/cloudflare/workers-sdk/tree/main/packages/vitest-pool-workers) - Runs unit and integration tests inside workerd with Workers bindings.
- [workers-rs](https://github.com/cloudflare/workers-rs) - Rust SDK for Workers and Durable Objects.
- [Wrangler](https://github.com/cloudflare/workers-sdk/tree/main/packages/wrangler) - Official CLI for developing, testing, and deploying Workers.
- [Wrangler GitHub Action](https://github.com/cloudflare/wrangler-action) - Official GitHub Action for Wrangler deployments.

### Libraries and SDKs

- [Cap'n Web](https://github.com/cloudflare/capnweb) - TypeScript-native RPC library that interoperates with Workers RPC.
- [Chanfana](https://github.com/cloudflare/chanfana) - OpenAPI schema generation and validation for Hono and itty-router applications.
- [Cloudflare Puppeteer](https://github.com/cloudflare/puppeteer) - Puppeteer fork for the Browser Rendering binding.
- [Workers OAuth Provider](https://github.com/cloudflare/workers-oauth-provider) - OAuth 2.1 provider framework with PKCE and KV-backed token management.
- [Cloudflare Containers SDK](https://github.com/cloudflare/containers) - Official library for controlling Containers from Workers through container-enabled Durable Objects, with lifecycle, routing, WebSocket, and load-balancing helpers.
- [Cloudflare Playwright](https://github.com/cloudflare/playwright) - Official Playwright fork for driving the Browser Rendering binding from Workers through the Chrome DevTools Protocol.
- [Cloudflare Actors](https://github.com/cloudflare/actors) - Beta framework for Durable Objects with persistent properties, RPC, SQLite migrations, alarms, placement, lifecycle hooks, and retries.
- [Cloudflare MCP](https://github.com/cloudflare/mcp) - Token-efficient MCP server for the Cloudflare API using isolated Dynamic Worker Loader execution.
- [Saffron](https://github.com/cloudflare/saffron) - Cron parser that powers Cron Triggers in Workers.

### AI and Isolated Execution

- [Cloudflare Agents SDK](https://github.com/cloudflare/agents) - Framework for persistent AI agents using Workers and Durable Objects.
- [Cloudflare AI](https://github.com/cloudflare/ai) - Workers AI and AI Gateway providers, integrations, and examples.
- [Cloudflare Sandbox SDK](https://github.com/cloudflare/sandbox-sdk) - Beta SDK for controlling isolated code-execution containers from Workers.
- [LangChain Cloudflare](https://github.com/cloudflare/langchain-cloudflare) - Official Python integrations for LangChain and LangGraph using Workers AI, AI Search, Vectorize, and D1 checkpoint storage.
- [Cloudflare Playwright MCP](https://github.com/cloudflare/playwright-mcp) - Browser-automation MCP server using Workers, Browser Rendering, and Cloudflare Playwright.

### Projects, Examples, and Starters

- [Agentic Inbox](https://github.com/cloudflare/agentic-inbox) - Self-hosted email client and AI assistant using Workers, Durable Objects, R2, Workers AI, Email Routing, and Access.
- [Agents Starter](https://github.com/cloudflare/agents-starter) - Starter application for the Agents SDK and Workers AI.
- [Cloudflare Meet](https://github.com/cloudflare/meet) - Video-conferencing demo built with Workers and Cloudflare Realtime.
- [Cloudflare Workers Templates](https://github.com/cloudflare/templates) - Tested starters for frameworks, D1, R2, Durable Objects, Workflows, and AI.
- [D1 Northwind](https://github.com/cloudflare/d1-northwind) - Demo application for exploring D1 with the Northwind dataset.
- [Python Workers Examples](https://github.com/cloudflare/python-workers-examples) - Examples of native Python applications running on Workers.
- [Serverless Registry](https://github.com/cloudflare/serverless-registry) - OCI-compatible container registry using Workers and R2, with a 500 MB per-layer push limit.
- [VibeSDK](https://github.com/cloudflare/vibesdk) - Self-hosted AI application builder using Workers, Durable Objects, D1, R2, KV, Containers, AI Gateway, and Workers for Platforms.
- [Moltworker](https://github.com/cloudflare/moltworker) - Experimental OpenClaw deployment using Workers, Sandbox containers, Access, and optional R2 persistence.
- [Cloudflare Prometheus Exporter](https://github.com/cloudflare/cloudflare-prometheus-exporter) - Beta Prometheus exporter using Workers, Durable Objects, KV, and alarms to collect and cache Cloudflare account and zone metrics.
- [DMARC Email Worker](https://github.com/cloudflare/dmarc-email-worker) - DMARC report processor using Email Workers, R2, and Analytics Engine for storage and aggregate analysis.
- [Cloudflare Identity and Access Help Page](https://github.com/cloudflare/cf-identity-dynamic) - Customizable Access denial interface using Workers and KV to display identity and policy context.
- [OpenAI Workers Relay](https://github.com/cloudflare/openai-workers-relay) - WebSocket relay for connecting applications to OpenAI's Realtime API from Workers.
- [Cloudflare Workflows Starter](https://github.com/cloudflare/workflows-starter) - Deployable starter for durable, multi-step applications using Workflows and Workers.

### Learning Resources

- [Framework Guides](https://developers.cloudflare.com/workers/framework-guides/) - Deployment guides for supported web, API, mobile, and AI frameworks.
- [Workers Examples](https://developers.cloudflare.com/workers/examples/) - Focused examples for runtime APIs and platform bindings.
- [Workers Tutorials](https://developers.cloudflare.com/workers/tutorials/) - Guided projects that combine Workers with other Cloudflare products.

## Contributing

Contributions are welcome. Please read the [contribution guidelines](CONTRIBUTING.md) before submitting an addition.
