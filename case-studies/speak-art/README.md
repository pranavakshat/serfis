# Speak ART

Realtime voice-to-editable-presentation builder.

## Summary

Speak ART is a realtime presentation builder where the user speaks and the system turns settled speech into a structured, editable slide deck.

The visible product is intentionally minimal: a blank canvas, a microphone, and an export action. The complex work happens behind the scenes: speech is transcribed, interpreted into validated deck operations, applied to a hidden artifact model, and exported as an editable presentation file.

## Problem

Creating a presentation interrupts the flow of thinking. People often know what they want to say before they know how to arrange it visually. Existing slide tools force users to stop, click, format, and organize while ideas are still forming.

Speak ART explores a different workflow: speak naturally, let the system build structure in real time, then export an editable deck when the thought is ready.

## Product

Speak ART listens during a session, builds a hidden representation of the deck, supports focus and editing operations, and exports a presentation where text, shapes, and images remain editable.

The product is local-first today, with a static frontend deployed separately from the realtime backend. The backend slice includes realtime session handling, speech-provider abstraction, validation, undo/redo behavior, and editable export.

## Core Capabilities

- Realtime speech session shell.
- Speech transcription provider abstraction.
- Mock provider for no-cost local testing.
- Hidden editable deck model.
- Validated operations for slide changes.
- Focus, undo, redo, and reducer-based artifact updates.
- Editable presentation export.
- Minimal UI that keeps attention on the act of speaking.
- Deployment readiness checks for separating static frontend and realtime backend hosting.

## Technical Scope

Speak ART required realtime systems thinking, event contracts, provider abstractions, artifact modeling, validation, export generation, and launch readiness. The architecture keeps the visible UI from becoming the source of truth. The deck model lives behind the interface, so speech and editing operations can safely update a structured artifact before export.

The hardest part is preserving creative flow while keeping the output editable. The product is not just speech to text. It is speech to validated design operations.

## My Role

I designed the product direction, built the minimal UI, backend session model, operation pipeline, validation layer, export behavior, and launch-readiness checks.

## Recruiter Takeaway

Speak ART shows product imagination, realtime architecture, AI interface design, and the ability to turn ambiguous creative workflows into structured software.

## Source Code

The real source repository remains private. This public copy is a no-code case study designed to explain the product and engineering work without exposing implementation details.