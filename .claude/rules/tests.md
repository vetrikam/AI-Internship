---
paths:
  - "**/test_*.py"
  - "**/*_test.py"
  - "**/tests/**/*.py"
---

# Test conventions

- Name each test `test_<unit>_<expected_behaviour>`.
- Use Arrange / Act / Assert comments in every test body.
- Mock external services at the boundary, never inside the unit under test.