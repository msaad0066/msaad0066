# Cursor Portfolio Project Factory

This workspace is designed to make Cursor repeatedly discover and build portfolio-quality software projects.

## Workflow

```text
Reddit / Communities
        ↓
Problem Discovery
        ↓
20+ Candidates
        ↓
Scoring
        ↓
Adversarial Review
        ↓
One Selected Idea
        ↓
PRD + Architecture
        ↓
GitHub Repository
        ↓
Incremental Development
        ↓
Testing
        ↓
Deployment
        ↓
Showcase
        ↓
Next Project
```

## How to use

### 1. Open this workspace in Cursor

Make sure Cursor has the `.cursor/rules/project-factory.mdc` rule loaded.

### 2. Run discovery

Open:

`prompts/01-discover.md`

Give the prompt to Cursor.

Cursor should research ideas and stop after selecting one.

### 3. Review the selected idea

Check:

`research/selected-idea.md`

If the idea is strong, continue.

### 4. Build

Use:

`prompts/02-build.md`

Cursor should create the project repository and implement it incrementally.

### 5. Repeat

After the project is finished, use:

`prompts/03-next-project.md`

The second project should intentionally explore a different problem and technical area.

## Rules

The system should favor:

- real problems
- evidence
- originality
- technical depth
- strong demos
- realistic MVPs
- production-quality engineering

Avoid:

- tutorial clones
- generic CRUD apps
- fake AI wrappers
- over-engineered MVPs
- invented market evidence

## Goal

Build a portfolio that demonstrates the ability to:

1. discover problems
2. evaluate opportunities
3. design software
4. architect systems
5. build production-quality applications
6. integrate external services
7. test software
8. deploy software
9. explain engineering decisions
