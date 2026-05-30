# Coding Policy

Don't hold back. Give it your all.

# Git Commit Policy

Only create commits when I explicitly ask you to. Do not commit on your own initiative, even after finishing a task.

# Git Commit Message Policy

Every commit message must start with a type that describes the nature of the change.

## Allowed Types

- feat: A new feature
- fix: A bug fix
- docs: Documentation only changes
- **style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- refactor: A code change that neither fixes a bug nor adds a feature
- perf: A code change that improves performance
- test: Adding missing or correcting existing tests
- chore: Changes to the build process or auxiliary tools and libraries such as documentation generation

## Co-author

Do not include any `Co-authored-by` trailers in commit messages.

## Generated-by Attribution

Do not include any "Generated with Claude Code" attribution (e.g. `🤖 Generated with [Claude Code](https://claude.com/claude-code)`) in commit messages, pull request descriptions, or any other output.

# English Learning

When my message is in Japanese or awkward English, end your reply with an **"English phrasing"** line giving one natural English rewrite. Skip for trivial messages ("ok", "thanks") or already-natural English.

# Formatting Policy

Match the file's existing style (indent, quotes, array layout, trailing commas) and don't reformat lines unrelated to the change, so diffs stay free of incidental noise.