# Project conventions

- Every new Python function gets a one-line docstring.
- In non-test Python files, use the `logging` module, never `print`.
- Test files follow the rules in .claude/rules/tests.md.
- Commit messages start with a type prefix: feat:, fix:, test:, or docs:.
- Prefix the name of every new function with `calc_`, for example `calc_add_and_record`.