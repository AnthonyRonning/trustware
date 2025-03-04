# CLAUDE.md - Guidance for AI Assistants

## Project Overview
Trustware is a protocol fiction novel written with LLM assistance. It explores a near-future world where the Open Enclave Protocol (OEP) requires all internet-facing services to run within secure hardware enclaves with open-source code.

## Build/Test Commands
- **Check spelling/grammar**: `aspell check <file>.md`
- **Word count**: `wc -w chapters/*.md`
- **Preview in markdown**: `grip <file>.md`
- **Run a consistency check**: `grep -r "OEP" --include="*.md" .` (replace OEP with any term)

## Style Guidelines

### Content Style
- **Protocol-centric**: Focus on the system/rules rather than individual heroes
- **Multi-perspective**: Include viewpoints from regulators, corporations, citizens, and rogue actors
- **Epistolary elements**: Incorporate fictional documents (memos, specifications, news articles)
- **Technical accuracy**: Maintain consistency in the protocol's rules and implementation

### Formatting
- Use markdown for all content files
- Chapter files in the `chapters/` directory, named `ch##.md`
- Research notes in the `research/` directory
- Section breaks with `---` (three hyphens)
- Dialog formatting: `> **@Username:** Message content`

### World Details
- Timeline: Set in 2035-2040
- Central concept: Open Enclave Protocol (OEP) and Global Enclave Compliance Act (GECA)
- Key tension: Trust vs. surveillance in a transparent computing world

Remember that all files produced should align with protocol fiction principles: focus on systems, rules, and their consequences rather than individual heroes or magical solutions.