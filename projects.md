# Projects

These descriptions focus on the purpose, approach, current contribution, and realistic next steps. Both projects are evolving engineering prototypes; read their repository documentation for implementation details and limitations.

## Project 1: AI Agent Firewall — agent-boundary

- **Problem:** AI coding agents can read files, run commands, and attempt network access. Prompt instructions alone are not a reliable security boundary.
- **Solution:** A Linux-first local CLI prototype exploring OS-enforced sandboxing, policy-based network mediation, scoped approval gates, and reviewable session audit evidence.
- **Technologies:** Python, Bubblewrap, Linux namespaces, Seccomp-BPF, YAML policies, HTTP proxying, pytest, Ruff, mypy, and GitHub Actions (see the repository README for the full stack).
- **My contribution:** Building and documenting the project, its policy boundaries, tests, and limitations in the public repository.
- **Current status:** Educational security prototype. It is not production endpoint protection and has not received an independent professional security audit.
- **Possible improvement:** Expand independent security review, validate behavior across more Linux environments, and continue adversarial testing.
- **Repository:** https://github.com/worksomaganesh/ai-agent-firewall

## Project 2: AI PR Verification Agent

- **Problem:** A pull-request review can look green without enough trustworthy evidence that important behaviors were actually verified.
- **Solution:** An evolving verification system designed to separate deterministic conclusions from model-suggested risk hypotheses and to preserve evidence about what was or was not verified.
- **Technologies:** Python, FastAPI, SQLite/PostgreSQL concepts, GitHub API integration, pytest, Ruff, mypy, and GitHub Actions (see the repository README for current implementation details).
- **My contribution:** Developing the repository incrementally and documenting architecture, verification semantics, testing, and phase status.
- **Current status:** Work in progress. The repository README and open pull requests are the source of truth for the current phase and merge/CI status.
- **Possible improvement:** Complete and verify platform-authenticated CI evidence ingestion and reconciliation, then document the limitations with reproducible tests.
- **Repository:** https://github.com/worksomaganesh/ai-pr-verification-agent

## Project 3: Student Portfolio Website

- **Problem:** Students need a simple place to present their learning, projects, and public links without overstating their experience.
- **Solution:** A responsive, static HTML/CSS portfolio with separate Markdown files for profile, skills, projects, education, and contact information.
- **Technologies:** HTML, CSS, Markdown, Git, and GitHub.
- **My contribution:** Personalizing the pages, documenting genuine project work, and practising branch/commit/pull-request workflows as part of the Git & GitHub practical assessment.
- **Possible improvement:** Improve accessibility checks, add a simple automated HTML validation step, and keep content updated as projects mature.
- **Repository:** https://github.com/worksomaganesh/Student-Portfolio
