# Eventra Documentation

Feature tracking for SaaS products.

- 📦 npm: https://www.npmjs.com/package/@eventra_dev/eventra-sdk  
- 🌐 Website: https://eventra.dev  
- 📚 Examples: https://github.com/and-1991/eventra-docs/tree/main/examples

---

Eventra is a feature tracking platform for SaaS products.

Track feature usage, understand adoption, and identify underused functionality.  
Eventra helps you understand how users interact with your product and make better product decisions based on real usage data.

---

## Getting Started

- Getting Started
- Installation
- Quick Start

---

## JavaScript SDK

Eventra provides a lightweight JavaScript SDK that works in:

- Browser environments
- Node.js environments
- Frontend frameworks
- Backend frameworks
- Serverless environments

Supported environments include:

- Vanilla JavaScript
- Node.js
- React
- Next.js
- Vue
- Angular
- Svelte
- NestJS
- Express
- Serverless (Vercel, AWS Lambda, Cloudflare Workers)

---

## Concepts

### Events

Events represent user interactions with your product.

Examples:

- feature_used
- button_clicked
- project_created
- dashboard_opened

### Users

Each event can be associated with a unique user.

This helps you understand feature adoption and user behavior.

### Projects

Projects allow you to organize events across different applications or environments.

---

## API

### Ingest API

Eventra provides an ingestion API for sending events directly.

Use this when:

- You want server-side tracking
- You need custom integrations
- You're not using the SDK

---

## Quick Example

## Install

### npm

```bash
npm install @eventra_dev/eventra-sdk
```

### pnpm

```bash
pnpm add @eventra_dev/eventra-sdk
```

### yarn

```bash
yarn add @eventra_dev/eventra-sdk
```

---

### Initialize

```javascript
import { Eventra } from "@eventra_dev/eventra-sdk";

const eventra = new Eventra({
  apiKey: "YOUR_API_KEY"
});
```

---

### Track Event

```javascript
eventra.track("feature_used", {
  userId: "user_123",
  properties: {
    feature: "dashboard"
  }
});
```

---

## Documentation Structure

- Getting Started
- Installation
- Quick Start
- JavaScript SDK
- Concepts
- API Reference

---

## Links

Website: https://eventra.dev  
SDK: https://github.com/and-1991/eventra-sdk  
Examples: https://github.com/and-1991/eventra-docs/tree/main/examples
