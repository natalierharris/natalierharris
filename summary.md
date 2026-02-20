I did this. It works

# Summary

**Date:** 2026-02-20  
**User:** natalierharris

## Overview

This document summarises a conversation about the difference between GitHub's generic **code quality** tooling and **Copilot code review**.

## Key points

- **Generic GitHub code quality** refers to deterministic, rule-based checks: linters, unit tests, static-analysis tools, and security scans. These run as GitHub Actions checks or through Code Scanning / Dependabot and produce consistent, repeatable findings based on fixed rules.

- **Copilot code review** is AI/LLM-based. When a pull request is opened, Copilot analyses the diff using a large language model and generates contextual, natural-language feedback that goes beyond what static rules can detect.

- **"Code Quality has standard findings and AI findings, 100% powered by AI"** — this statement likely refers to a specific product surface labelled *Code Quality* inside the Copilot code review experience. Within that surface:
  - *Standard findings* are AI-generated comments that map to a fixed, standardised set of categories (e.g. performance, security, correctness).
  - *AI findings* are free-form, AI-generated observations that do not fit a predefined category.
  - Both types are produced by the AI/LLM, hence "100% powered by AI", but they differ in how the findings are classified and presented.

## Open questions / next steps

- **Where exactly is "Code Quality" seen?** The label may appear in different contexts:
  - Inside a pull request's *Copilot code review* panel.
  - Under the repository's *Security* tab or *Code scanning* section.
  - As a named check in the *Checks* tab of a pull request.
- Clarifying which surface displays this label will help determine whether it refers to the Copilot code review product, a third-party code-quality action, or a GitHub-native static-analysis feature.
- Once the surface is identified, the distinction between "standard findings" and "AI findings" can be confirmed against the relevant product documentation.
