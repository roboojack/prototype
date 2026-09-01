# VAERS Modernized Reporting — Proposal Prototype

Interactive proposal prototype prepared by **Attention Systems LLC** for RFQ **75D301-26-Q-00146**.

## Purpose

This intentionally lightweight prototype demonstrates representative UX concepts for a modernized VAERS reporting application:

- guided consumer and healthcare-professional entry paths
- conditional/branching questions
- required-field validation and accessible error messaging
- vaccination-error/no-adverse-event path for healthcare professionals
- synthetic supporting-document selection
- review-before-submit workflow
- responsive, keyboard-friendly semantic web UI

## Important safety boundary

**Synthetic data only. Do not enter or upload real patient information, PHI, PII, medical records, CUI, credentials, or production VAERS data.**

This static prototype has no backend. It does not store, transmit, or submit form data. The final Submit action is simulated.

## Production distinction

The prototype is an evaluation artifact, not a proposed production hosting architecture. A production implementation would be deployed within the Government-authorized environment and implement the complete CDC-furnished business rules, integration contracts, security/privacy controls, records requirements, accessibility testing, monitoring, and authorization activities.

## Accessibility demonstrated

The prototype uses native form controls, explicit labels, keyboard-visible focus, responsive layout, error messages with alert semantics, and a review step. Formal Section 508 conformance testing and ACR/VPAT production deliverables are outside this static demonstration.

## Hosting

The repository is designed to be published as a static GitHub Pages site from `main` / repository root.
