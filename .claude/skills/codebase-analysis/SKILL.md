---
name: codebase-analysis
description: Produce a full analysis of this repo's structure, test layout, dependencies and risks. Use when asked for a codebase analysis or an onboarding overview.
context: fork
allowed-tools: Read, Glob, Grep, Bash(git log:*)
argument-hint: [focus-area]
---

Analyse this repository. If a focus area was given, weight it heavily: $ARGUMENTS

1. Map the top-level folders, and note that each bootcamp folder is its own project.
2. Locate every test file (test_*.py, *_test.py, and tests/ folders) and report how tests are organised.
3. List external dependencies from the manifest files and flag anything outdated or unpinned.
4. Use git history to find the most-changed files in the last 90 days.
5. Return a summary under 400 words: structure, test health, top three risks, top three recommended actions.