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

## Frameworks and Adapters

- [Astro Cloudflare Adapter](https://github.com/withastro/astro/tree/main/packages/integrations/cloudflare) - Official Astro adapter for rendering and deploying applications on Workers.
- [Hono](https://github.com/honojs/hono) - Web Standards framework with first-class Workers support.
- [itty-router](https://github.com/kwhitley/itty-router) - Small router designed for Workers and other edge runtimes.
- [Nitro](https://github.com/nitrojs/nitro) - Server toolkit with Workers deployment presets, also used by Nuxt.
- [OpenNext Cloudflare](https://github.com/opennextjs/opennextjs-cloudflare) - Adapter for deploying Next.js applications to Workers.
- [RedwoodSDK](https://github.com/redwoodjs/sdk) - Server-first React framework built for the Cloudflare runtime.
- [SvelteKit Cloudflare Adapter](https://github.com/sveltejs/kit/tree/main/packages/adapter-cloudflare) - Official SvelteKit adapter for Workers.

## Libraries and Tools

- [Alchemy](https://github.com/alchemy-run/alchemy) - TypeScript infrastructure-as-code toolkit with Workers and binding support.
- [Drizzle ORM](https://github.com/drizzle-team/drizzle-orm) - Type-safe ORM and migration tooling with D1 support.
- [Sentry Cloudflare SDK](https://github.com/getsentry/sentry-javascript/tree/develop/packages/cloudflare) - Error monitoring and tracing SDK for Workers.

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

### AI and Isolated Execution

- [Cloudflare Agents SDK](https://github.com/cloudflare/agents) - Framework for persistent AI agents using Workers and Durable Objects.
- [Cloudflare AI](https://github.com/cloudflare/ai) - Workers AI and AI Gateway providers, integrations, and examples.
- [Cloudflare Sandbox SDK](https://github.com/cloudflare/sandbox-sdk) - Beta SDK for controlling isolated code-execution containers from Workers.

### Projects, Examples, and Starters

- [Agentic Inbox](https://github.com/cloudflare/agentic-inbox) - Self-hosted email client and AI assistant using Workers, Durable Objects, R2, Workers AI, Email Routing, and Access.
- [Agents Starter](https://github.com/cloudflare/agents-starter) - Starter application for the Agents SDK and Workers AI.
- [Cloudflare Meet](https://github.com/cloudflare/meet) - Video-conferencing demo built with Workers and Cloudflare Realtime.
- [Cloudflare Workers Templates](https://github.com/cloudflare/templates) - Tested starters for frameworks, D1, R2, Durable Objects, Workflows, and AI.
- [D1 Northwind](https://github.com/cloudflare/d1-northwind) - Demo application for exploring D1 with the Northwind dataset.
- [Python Workers Examples](https://github.com/cloudflare/python-workers-examples) - Examples of native Python applications running on Workers.
- [Serverless Registry](https://github.com/cloudflare/serverless-registry) - OCI-compatible container registry using Workers and R2, with a 500 MB per-layer push limit.
- [VibeSDK](https://github.com/cloudflare/vibesdk) - Self-hosted AI application builder using Workers, Durable Objects, D1, R2, KV, Containers, AI Gateway, and Workers for Platforms.

### Learning Resources

- [Framework Guides](https://developers.cloudflare.com/workers/framework-guides/) - Deployment guides for supported web, API, mobile, and AI frameworks.
- [Workers Examples](https://developers.cloudflare.com/workers/examples/) - Focused examples for runtime APIs and platform bindings.
- [Workers Tutorials](https://developers.cloudflare.com/workers/tutorials/) - Guided projects that combine Workers with other Cloudflare products.

## Contributing

Contributions are welcome. Please read the [contribution guidelines](contributing.md) before submitting an addition.
