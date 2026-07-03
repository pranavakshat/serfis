# AI Stock Analyst

Multi-model daily market analyst with live scoring and portfolio simulation.

## Summary

AI Stock Analyst is a daily market-analysis system that asks multiple AI models to make session-based stock picks from the same market briefing, then tracks how each model performs over time.

The product turns AI financial predictions into a measurable competition: morning and evening jobs collect market context, ask several models for conviction-weighted long or short ideas, score the results, update a simulated portfolio, and publish the results to a dashboard and email digest.

## Problem

AI models are often discussed as if their financial reasoning is useful, but the claims are rarely tested consistently. A single impressive answer does not prove decision quality. To learn whether models can reason through market context, the system needs repeatable prompts, equal inputs, scheduled evaluation, and a live scoreboard.

AI Stock Analyst solves that by creating a structured evaluation loop for market-prediction behavior.

## Product

The system runs two market sessions each trading day: one for the regular day session and one for overnight moves. Each session gathers a live market briefing, asks each configured model for its top picks, records the reasoning and allocation, scores the picks after the session, and updates each model's accuracy and simulated portfolio value.

Users can view results on a live dashboard and receive polished email digests.

## Core Capabilities

- Morning and evening scheduled analysis cycles.
- Multiple AI models compared under the same market context.
- Market context assembled from macro, sector, sentiment, news, earnings, technical, options, short-interest, analyst, mover, and overnight modules.
- Long and short stock picks with conviction-weighted allocations.
- Day-session and overnight-session scoring.
- Simulated portfolio tracking with compounding performance.
- Per-model accuracy leaderboard.
- Email digest for each market session.
- CSV backup and restore behavior for deployment-safe persistence.
- Live dashboard for predictions, results, and model performance.

## Technical Scope

This project combines data engineering, AI orchestration, scheduled jobs, financial data normalization, scoring logic, dashboard design, email delivery, and deployment reliability.

The interesting challenge is the evaluation loop. Every model must receive the same briefing, produce structured outputs, and be scored in a consistent way so performance can be compared over time instead of judged by anecdote.

## My Role

I designed and built the product workflow, model comparison loop, scoring model, dashboard, email digest, scheduled jobs, and deployment flow.

## Recruiter Takeaway

AI Stock Analyst shows practical AI evaluation, data-pipeline thinking, automation, analytics, and productization. It is especially useful as proof that I can turn AI output into measurable systems instead of one-off prompts.

## Source Code

The public copy should focus on this case study, dashboard, and product behavior. Any implementation details are intentionally omitted here so recruiters can understand the system without reading source code.