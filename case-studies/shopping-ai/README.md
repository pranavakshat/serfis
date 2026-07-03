# Shopping AI

Barcode-first grocery and beauty recommendation app.

## Summary

Shopping AI is a mobile-friendly PWA that helps users understand grocery and beauty products by scanning or entering a barcode. It looks up public product data, applies deterministic scoring, and can generate an AI explanation that turns raw ingredient and nutrition data into a clear recommendation.

The MVP includes a scanner/manual barcode experience, public product lookup, subscription checkout, legal pages, and production smoke checks.

## Problem

Shopping decisions are crowded with confusing labels, hidden tradeoffs, and inconsistent product information. Consumers often want a quick answer: is this product a good fit for my goals, and why?

Most recommendation apps either require manual searching or provide opaque scores. Shopping AI starts from the object in the user's hand: the barcode.

## Product

Users open the installable web app, scan or enter a barcode, and receive a source-backed product result. The system combines deterministic scoring with AI explanation so the answer is both consistent and understandable.

The product is designed as a lightweight consumer subscription MVP with a public landing site, app surface, checkout flow, webhook verification, privacy pages, and live production checks.

## Core Capabilities

- Installable PWA experience.
- Barcode scanner and manual barcode entry.
- Public product lookup from open product-data sources.
- Deterministic scoring for consistent recommendations.
- Optional AI-generated explanation for human-readable guidance.
- Stripe Checkout subscription flow.
- Webhook verification for payment events.
- Privacy, terms, open-data, and download pages.
- Production checks for app routes, product analysis, AI availability, checkout, and webhook safety.

## Technical Scope

Shopping AI combines frontend product design, public-data integration, AI explanation, deterministic scoring, payments, webhook security, and production deployment.

The key product decision is separating the score from the explanation. The app can provide a stable result from deterministic logic while using AI to make the reasoning easier to understand.

## My Role

I designed and built the MVP, product flow, scoring approach, AI explanation surface, checkout integration, legal/support pages, and production verification.

## Recruiter Takeaway

Shopping AI shows the ability to ship a consumer-facing AI product with payments, public data, mobile UX, and production safety checks.

## Source Code

The real source repository remains private. This public copy is a no-code case study designed to explain the product and engineering work without exposing implementation details.