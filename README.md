# ACE Life OS Onboarding Survey

A static, local-first onboarding survey adapted from the PAI / Personal AI Infrastructure interview model.

## Purpose

Capture high-signal context an AI assistant needs to operate as a durable family-office / life-OS assistant:

- identity and operating style
- mission, goals, problems, strategies
- constraints and risk posture
- current state vs. ideal state
- preferences, relationships, projects, and recurring rhythms
- instructions the assistant should remember

## Privacy model

No backend is included. Answers stay in the browser via `localStorage` until the user exports them.

Exports:

- JSON profile packet
- Markdown profile summary
- "Copy for Hermes" packet for ingestion into assistant memory/processes

## Source inspiration

- Daniel Miessler's Personal_AI_Infrastructure repository, especially the PAI `/interview` phases and `InterviewScan.ts` prompt registry.
- Adapted for ACE / Hermes workflows rather than copied wholesale.
