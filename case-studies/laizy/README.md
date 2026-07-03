# Laizy

Cloud-run job application automation with human approval gates.

## Summary

Laizy is a SaaS product that helps job seekers run structured, cloud-based job applications. Users create a reusable profile, upload an approved resume, grant explicit autopilot consent, and review applications that require human judgment before submission.

The product is designed around a careful balance: automate the repetitive work of applying, but keep users in control when an application needs personal answers, consent, or judgment.

## Problem

Job applications are high-volume, repetitive, and fragmented across different applicant-tracking systems. Candidates waste hours re-entering the same information, tracking application status manually, and switching contexts across job boards. Fully automatic submission is risky because many applications contain sensitive questions, role-specific writing, and platform rules.

Laizy solves this by turning application work into a governed workflow instead of a blind bot.

## Product

Laizy stores the user's profile and approved resume, runs supported application flows in the cloud, tracks every application, and pauses when a decision needs the user. The user sees a dashboard of submitted applications, needs-answer items, resume handling, and account status.

The product also includes a public launch surface with a product film, onboarding flows, billing, authentication, private document storage, and production launch gates.

## Core Capabilities

- Reusable candidate profile.
- Approved resume upload and private storage.
- Explicit autopilot consent before automation.
- Cloud-run application workflow execution.
- Dashboard for submitted and paused applications.
- Human review for application questions that should not be auto-answered.
- OAuth onboarding for Google and Microsoft users.
- Subscription billing and customer portal.
- SMS and email surfaces for future daily summaries and user preferences.
- Launch-readiness checks for production environment, providers, and live deployment behavior.

## Technical Scope

Laizy required a production-minded SaaS architecture: authentication, user-owned data, private file storage, database security rules, billing, durable worker entrypoints, browser automation, provider readiness checks, launch verification, and failure-closed behavior when hosted configuration is incomplete.

The hard part was not only automating forms. It was designing a system that is honest about what it can safely do, pauses when it should, and protects user data while still creating a smooth workflow.

## My Role

I owned the product direction, UX flow, launch positioning, technical architecture, implementation, verification scripts, and production-readiness work.

## Recruiter Takeaway

Laizy shows applied AI and automation inside a real SaaS product with privacy, consent, payments, auth, cloud execution, and launch discipline. It demonstrates the ability to build beyond a demo and think through operational risk.

## Source Code

The real source repository remains private. This public copy is a no-code case study designed to explain the product and engineering work without exposing implementation details.