# Source Of Truth

Current source-of-truth notes:

Python source, pyproject.toml, repo README, and browser automation docs.

Rules:

- Source code is the source of truth unless this file names an external system.
- If the real truth lives outside the repo, document the safe inspection path before changing behavior.
- Do not assume planned systems exist until code or docs confirm them.
- Do not read or print secret values from env files or credential-bearing config.
