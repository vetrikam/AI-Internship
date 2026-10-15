# Write-up

**Plan mode.** Name the task, say you used plan mode, explain why, and give one thing the plan changed. Example: the test glob changed after you checked the file names.

**Direct.** Name the task, say you did it directly, explain why a plan wasn’t needed, and say how you checked it. Example: adding .mcp.json was one file with a fixed format, and you checked it with /mcp.

**Skill rather than CLAUDE.md.** Running /codebase-analysis tests showed that only one of the five test files is a real pytest suite, the customer-support skeleton’s test_enforcement.py. The other four are manual scripts that need a live server or API, and none follows the test rule I wrote. That is the next thing to fix.