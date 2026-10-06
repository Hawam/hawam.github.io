---
name: Botbat
tools: [NestJS, TypeScript, PostgreSQL, Prisma, Redis, RabbitMQ, BullMQ, AWS SES, React, React Native, Expo, Keycloak, Docker, GitHub Actions, ASP.NET Core]
image: /assets/botbat/feature.png
description: Multi-tenant CPaaS platform for businesses to run WhatsApp, Instagram, Messenger, Telegram, SMS, email and web chat from one inbox.
---

# Botbat

[Botbat](https://botbat.io) is a multi-tenant Communications Platform as a Service (CPaaS). Businesses connect their messaging channels, handle every conversation from one shared inbox, run broadcast campaigns, and automate replies with visual workflows and an AI chatbot.

![Botbat omni-channel customer engagement lifecycle](/assets/botbat/feature.png)

## What I worked on

- **Campaign engine** - contributed to timezone-aware scheduling on BullMQ, campaign execution over RabbitMQ, per-channel rate limiting and multi-day distribution, delivery, bounce and reply tracking, and goal-based conversion attribution.
- **Email platform on AWS SES** - multi-tenant sending, domain and sender verification, an inbound email pipeline into the shared inbox, RFC 2369 one-click unsubscribe, MJML templates and AI-assisted email generation.
- **WhatsApp Business Platform** - Meta Embedded Signup onboarding, template submission and approval, interactive buttons and lists, rich messages and reactions, business profile and phone health, plus Instagram and Messenger channels.
- **Mobile app** - built the React Native (Expo) app from scratch: Keycloak PKCE sign-in, a live inbox over Server-Sent Events, push notifications, an offline cache and Arabic RTL support, with API types generated from the OpenAPI spec.
- **ASP.NET Core** - delivered backend tasks in C# alongside the main TypeScript stack.

## Stack

NestJS 11, TypeScript, Prisma, PostgreSQL, Redis, RabbitMQ, BullMQ, Socket.IO, React, MobX, Tailwind CSS, React Native (Expo), Next.js, Keycloak, AWS (ECS, SES, S3), Docker, GitHub Actions, ASP.NET Core.
