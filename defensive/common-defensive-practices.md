# Common Defensive Practices (Learning Summary)

Personal summary of defensive approaches encountered while studying public vulnerability reports.

## High-Level Practices
1. **Input validation & sanitization** — consistently appears as a primary control against injection-style issues.
2. **Least privilege** — limiting permissions reduces impact when a vulnerability is present.
3. **Dependency hygiene** — tracking and updating third-party libraries is critical (illustrated by multiple supply-chain cases).
4. **Logging & monitoring** — good telemetry helps detect exploitation attempts early.
5. **Secure defaults** — systems that ship with safer configurations reduce exposure.

## Personal Learning Goal
Improve ability to quickly identify which defensive control would have mitigated a given public vulnerability, and document the reasoning clearly.
