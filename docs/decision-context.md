# Decision Context

This document tracks major and minor decisions for the profile repository.

## 2026-05-11 IST

### D-001: GitHub Profile Positioning Narrative
- Decision: Position profile around full-stack product engineering with React ecosystem depth and backend system ownership.
- Alternatives considered:
  - Generic software engineer summary.
  - Frontend-only narrative.
- Rationale: This aligns better with target roles (Frontend Engineer, Full Stack Engineer, Product Engineer) and portfolio strengths.
- Impact: Profile README now presents one consistent recruiter-facing story across skills and projects.

### D-002: Project Selection for Featured Section
- Decision: Feature `tamales-commerce`, `chill-zone`, and `PursueIt-Scroller` as primary public proof points.
- Alternatives considered:
  - Keep mixed older projects.
  - Feature only two larger projects.
- Rationale: These repositories represent frontend architecture, backend APIs, data persistence, and interactive UI storytelling.
- Impact: Recruiters get clear signal breadth across SaaS-style systems and UI engineering.

### D-003: Keep Profile Repository Scope Focused
- Decision: Exclude nested local project clones from the profile repository via `.gitignore`.
- Alternatives considered:
  - Keep nested project directories unignored.
  - Move all nested repositories immediately before profile commit.
- Rationale: Prevents accidental inclusion of unrelated repositories in profile-repo commits.
- Impact: Profile repository remains clean and dedicated to profile documentation files.
