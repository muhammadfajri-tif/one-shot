# Agent Instructions for SRS & SDD Project

This repository is dedicated to creating Software Requirements Specification (SRS) and Software Design Document (SDD) for a restaurant system. The creation is a phased "grand design", multi-phases process.

## Core Rules

1. **NEVER GO WITH ASSUMPTION**: All work must be strictly based on the provided reference materials.
2. **ASK WHEN UNCLEAR**: Always ask the user if there is missing, unclear, or conflicting information. Do not guess.
3. **SOURCE OF TRUTH**: Always refer to the documents in `ref/` and the diagrams in `diagrams/`.
4. **LANGUAGE**: Always deliver output in proper and correct Indonesian (Bahasa Indonesia) according to EYD and KBBI.
   - **ENGLISH TERMS**: Keep English terms in their original form but format them in _italics_ (e.g., do NOT translate 'server' to 'peladen', write it as '_server_').
   - **AVOID**: the `--` symbol, arrow symbols (->, =>), emojis, or similar informal characters.
5. **AUDIENCE**: The goal is to provide these documents to external parties (professional tone is required).
6. **OUTPUT FILES**: The generated SRS and SDD must be saved to `SRS.md` and `SDD.md` respectively.
7. **DIAGRAMS**: If a diagram is needed, reference the existing images in `diagrams/`. If a required diagram does not exist, CREATE IT USING MERMAID FORMAT in the markdown.
8. **STANDARDS**: The SRS and SDD must follow the IEEE format and templates provided in `template/`.

## Directory Structure

- `ref/`: Contains all raw requirements, breakdowns, use cases, and reference PDFs for the restaurant system.
- `diagrams/`: Contains existing domain models, use case diagrams, sequence diagrams (sdd), ERD, and architecture diagrams.
- `template/`: Contains IEEE templates for SRS and SDD (e.g., IEEE 1016-2009 for SDD, IEEE SRS template).
- `SRS.md`: Target file for the Software Requirements Specification.
- `SDD.md`: Target file for the Software Design Document.

