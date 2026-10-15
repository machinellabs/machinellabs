# Carlos Lopez

I build small tools, automation scripts, and web apps that solve practical problems.

## Recently shipped

- **[diff-review v0.4.0](https://github.com/machinellabs/diff-review/releases/tag/v0.4.0)** — a `--security` mode that checks diffs against an application-security ruleset (injection, secrets, authz, unsafe deserialization) and runs a local secrets scan before the model ever sees the code.
- **[coffee-timer](https://github.com/machinellabs/coffee-timer)** — a study timer shaped like a mug of coffee, with session stats and a regression test suite.

## Next up

- A prompt-injection test harness for LLM agents
- Python QA tools — a log checker and an API health checker, both with test suites

## Projects

### [diff-review](https://github.com/machinellabs/diff-review)

A command-line tool that reviews git diffs with Claude.

- Works with local diffs, saved patch files, and GitHub pull requests
- Splits larger diffs into file-level chunks and reviews them in parallel
- Optional `--security` mode with a local secrets pre-scan
- Returns terminal, JSON, or Markdown output
- Tracks token usage and estimated cost

### [coffee-timer](https://github.com/machinellabs/coffee-timer)

A Pomodoro-style study timer in Python and Tkinter. The coffee drains as the session runs, and it chimes when the mug is empty.

- Per-activity time tracking with crash-safe JSON storage
- Keyboard-driven controls
- Built-in performance and debug view
- 15 regression tests that run without the GUI or personal data

### [HousePoints](https://github.com/machinellabs/HousePoints)

A self-hosted chore scoreboard for two people.

- Express API with flat-file JSON storage
- Mobile-friendly single-page UI
- Setup wizard, custom stakes, history, schedule, and backup flow
- Designed to run on a trusted local network

## Current Focus

- Security tooling — code review, secrets detection, testing LLM-based apps
- Python and JavaScript tools, with tests
- Developer workflows and local automation
- Small full-stack apps
- Practical uses of LLMs in day-to-day coding work

## Tech

Python, JavaScript, Node.js, Express, LangGraph, Claude API, Pydantic, Tkinter, unittest, GitHub Actions, HTML, CSS

## Links

- [LinkedIn](https://www.linkedin.com/in/juan-carlos-lopez-4125b1162/)
- [GitHub](https://github.com/machinellabs)
