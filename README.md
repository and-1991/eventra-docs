# Eventra Documentation

Eventra is a feature tracking platform for SaaS products.

Track feature usage, understand adoption, and identify underused functionality.

Eventra helps you understand how users interact with your product and make better product decisions based on real usage data.

---

# Getting Started

- Getting Started
- Installation
- Quick Start

---

# JavaScript SDK

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

# Concepts

## Events

Events represent user interactions with your product.

Examples:

- feature_used
- button_clicked
- project_created
- dashboard_opened

## Users

Each event can be associated with a unique user.

This helps you understand feature adoption and user behavior.

## Projects

Projects allow you to organize events across different applications or environments.

---

# API

## Ingest API

Eventra provides an ingestion API for sending events directly.

Use this when:

- You want server-side tracking
- You need custom integrations
- You're not using the SDK

---

# Quick Example

Install SDK:

```bash
npm install @eventra_dev/eventra-sdk
