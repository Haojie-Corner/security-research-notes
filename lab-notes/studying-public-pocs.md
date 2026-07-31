# Studying Public Proof-of-Concepts (Safely)

## Purpose of These Notes
When learning about vulnerabilities, public PoCs and write-ups are useful for understanding how an issue works. This document records my personal approach to studying them in a responsible way.

## Principles I Follow
- Only use publicly released PoCs and write-ups
- Run any experiments strictly inside isolated virtual machines or containers
- Never point tools or PoCs at systems I do not own or have explicit written permission to test
- Focus on understanding the root cause and the corresponding defensive controls
- Document what I learned about detection and mitigation, not just the exploit steps

## Typical Study Flow
1. Read the official advisory / CVE description first
2. Read 1–2 high-quality public technical write-ups
3. If a PoC is available, review the code to understand the technique
4. In a local lab, observe the behavior (where safe and legal)
5. Write down:
   - Root cause
   - Preconditions required for exploitation
   - What defensive measures would block or detect it
   - How to recognize similar issues in the future

## Why This Matters for Learning
Understanding public cases builds pattern recognition. The goal is to get better at identifying weak points and thinking about defenses, not to collect working exploits.

*These notes support personal defensive learning only.*
