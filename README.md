# KPI 2026 Requirements to GitHub Pages Skill

This repository contains the source files for the `requirements-to-github-pages` skill.

## Purpose

The skill takes an existing markdown requirements document as input and helps implement a small web application that is feasible on GitHub Pages.

It is designed for the 2026 KPI coursework format where students:
- write requirements first,
- analyze feasibility and constraints,
- implement a small web app,
- deploy it to GitHub Pages.

## What the skill does

- analyzes feasibility of existing requirements for GitHub Pages;
- warns about requirements that need a backend or sensitive data handling;
- chooses a suitable frontend stack after requirements analysis;
- decides between `localStorage` and `IndexedDB` as part of architecture design;
- records architecture decisions as SDRs;
- generates demo data and a `Reset demo data` capability by default;
- implements the application in the repository;
- updates GitHub Pages deployment workflow.

## Repository contents

- `SKILL.md` - main skill instructions
- `agents/openai.yaml` - UI metadata
- `references/` - supporting guidance and templates
- `assets/` - GitHub Pages workflow templates

## Notes

This repository is the source of truth for the skill itself.
For starting application repositories, use a separate template repository.
