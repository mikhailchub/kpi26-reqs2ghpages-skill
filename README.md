# kpi26-reqs2ghpages-skill

Skill-only repository for the **Requirements To GitHub Pages** skill.

This skill takes an existing markdown requirements file for a small web application and helps implement it as a GitHub Pages project. It is intended for coursework where the topic and requirements already exist, and the implementation must stay within GitHub Pages constraints.

## What the skill does

- reads an existing markdown requirements document
- checks feasibility against GitHub Pages constraints
- warns about requirements that need compromises or an external backend
- chooses the simplest viable architecture
- documents architecture decisions as SDR files
- decides between `localStorage` and `IndexedDB`
- adds demo data and a `Reset demo data` control by default
- updates an existing repository and prepares GitHub Pages deployment via GitHub Actions

## What the skill does not do

- does not invent a project theme
- does not write requirements from scratch
- does not silently rewrite requirements
- does not pretend that secure auth, payments, or sensitive transactions belong in a pure GitHub Pages app

## Repository contents

- `SKILL.md` - main skill instructions
- `agents/openai.yaml` - UI metadata
- `references/` - decision and deployment guidance
- `assets/` - GitHub Pages workflow templates

## Suggested use

1. Create a new project repository from a template repository.
2. Add the student's markdown requirements file.
3. Invoke the skill in that repository.
4. Let the skill analyze feasibility, document SDRs, implement the app, and prepare Pages deployment.

## Notes

This repository stores the source of the skill. Packaged `skill.zip` distributions can be generated from the source when needed.
