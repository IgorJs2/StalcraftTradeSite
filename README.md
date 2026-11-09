# Stalcraft Trade

A player-to-player marketplace for the game STALCRAFT: buy and sell orders, real-time auction data, price analytics and Discord deals.

[stalcraft.trade](https://stalcraft.trade)

> Source code is private (Stalcraft-Dev-Team). This repository describes the project and my role.

## At a glance
| | |
|---|---|
| My role | Co-founder and lead backend developer, Stalcraft LAB |
| Releases | 1.0 (Jul 2024) · 2.0 (Oct 2024) · 2.1 (Jan 2025) |
| Status | In September 2026 the site became a microservice and its features moved into [Stalcraft Wiki](https://github.com/IgorJs2/StalcraftWikiSite) |

![screenshot](https://github.com/user-attachments/assets/8bd8837c-c963-44f4-8a72-d6b3a3725615)

## What I built
- Backend in NestJS and MongoDB from scratch: authorization (including EXBO OAuth), users and settings, offers and orders, WebSocket chat, email and web-push notifications, seller ratings, subscriptions and limits, scheduled cleanup jobs, admin features.
- Angular client and admin panel.
- Sync of the item and character catalog with official EXBO data; Stalcraft X items; custom items; auction history from real data; reCAPTCHA.
- Analytics and Discord Deals: a discord.js bot creates a dedicated channel for every trade and bridges events to Kafka.

![screenshot](https://github.com/user-attachments/assets/1e873b04-7ab2-414d-8702-20ccdbeacadb)

## Infrastructure
Docker Compose environments, GitHub Actions deploys, nginx and Cloudflare with SSL, Prometheus and Grafana monitoring, Sentry, backups to S3.

## Tech stack
| Area | Stack |
|---|---|
| Backend | TypeScript, Node.js, NestJS, WebSocket |
| Frontend | Angular, Taiga UI, Chart.js |
| Data | MongoDB, Redis, Kafka |
| Integrations | EXBO API, Discord API, reCAPTCHA |
| Infrastructure | Docker, Docker Compose, GitHub Actions, nginx, Cloudflare |

![](https://github.com/user-attachments/assets/1f54042e-8a65-430f-9812-a6543b38e683)
