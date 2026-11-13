# AGENTS.md

## Cursor Cloud specific instructions

This repository is the special GitHub **profile README** repo (`Agsterr/Agsterr`, whose
name matches the account owner, so GitHub renders it on the user's profile page).

Key facts for future agents:

- The repo contains a single content file: `README.md` (written in Portuguese). There is
  **no application code**, no dependency manifests, no build system, no services, and no
  automated tests.
- There is **nothing to install, build, run, or test end-to-end**. No update script is
  required; dependency setup is a no-op.
- The projects described in `README.md` (Gerenciamento de Estoque, App Rotas, Focodev
  Site, etc.) live in **separate external repositories** linked from the README — their
  code is not present here.

### Working on this repo

- "Development" here means editing Markdown in `README.md`. The core functionality is that
  the README renders correctly on GitHub.
- To preview rendering locally (optional, not needed for CI), render the Markdown to HTML
  and open it in a browser. Example one-off (not part of any update script):
  `pip3 install markdown pygments` then convert `README.md` with the Python `markdown`
  module and serve the output with `python3 -m http.server`.
- Keep the README content in Portuguese to match the existing style.
