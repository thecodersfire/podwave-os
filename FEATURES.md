# Built-in features for podwave-os

Purpose: podcast production

1. **organize project files** — run podwave-os-workspace. It creates ~/Documents/podwave-os-workspace/ with Inbox, Projects, Archive folders.
2. **draft a session plan** — run podwave-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/podwave-os-session-plans/.
3. **check task readiness** — run podwave-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/podwave-os-workspace features/podwave-os-plan features/podwave-os-check "$HOME/.local/bin/"
