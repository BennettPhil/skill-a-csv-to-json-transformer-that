---
name: a-csv-to-json-transformer-that
description: A CSV-to-JSON transformer that handles edge cases gracefully. It should support custom delimiters, quoted f...
version: 0.1.0
license: Apache-2.0
---

# Purpose
Implement the idea: A CSV-to-JSON transformer that handles edge cases gracefully. It should support custom delimiters, quoted fields, nested headers (dot notation), and streaming for large files.

# Context
No additional context provided.

# Builder Influence
Use a concise, validation-first workflow derived from the selected builder guidance: --- name: pragmatic-builder-v2 description: An evolved pragmatic builder that mandates a CHANGELOG.md for better version tracking. version: 0.2.0 license: Apache-2.0 ---

# Workflow
1. Clarify assumptions and constraints before implementation.
2. Produce a concrete implementation plan tied to the requested output.
3. Build the solution incrementally and verify each major step.
4. Add usage instructions and edge-case handling notes.
5. Validate outputs and report limitations explicitly.

# Validation Checklist
- Output files match the task and are runnable.
- Input validation and error handling are explicit.
- Instructions include test or verification steps.
- Any unsafe or illegal request is redirected to a safe alternative.