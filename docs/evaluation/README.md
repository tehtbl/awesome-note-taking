# Project Evaluation Framework

This directory contains tools to systematically evaluate all projects
in the awesome-note-taking list.

## Files

- `parameters.md` — The 30 evaluation parameters used to compare projects
- `evaluator-prompt.md` — Claude/LLM system prompt to run the evaluation
- `projects.txt` — Auto-generated list of all projects (pipe-delimited)

## How to run an evaluation

1. Copy the system prompt from `evaluator-prompt.md`
2. Paste `projects.txt` as the input data
3. Follow the instructions in the prompt for batched or single-pass processing
4. Save results to `results/` directory

## When to re-evaluate

- Before major refactors
- Quarterly (to catch abandoned projects)
- When adding a large batch of new tools
