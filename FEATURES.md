# Built-in features for colorwell-os

Purpose: digital painting

1. **organize a personal routine** — run colorwell-os-workspace. It creates ~/Documents/colorwell-os-workspace/ with Plans, Journal, Reference folders.
2. **plan a personal session** — run colorwell-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/colorwell-os-session-plans/.
3. **check routine readiness** — run colorwell-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/colorwell-os-workspace features/colorwell-os-plan features/colorwell-os-check "$HOME/.local/bin/"
