# Git rules for this repo

This repo belongs to the GitHub account `tangerine0000`. It does not belong to `tannguyen-innomize`.

## Commits and pull requests

- Make `tangerine0000` the only author of every commit.
- Never add a `Co-Authored-By` trailer for Claude or any other AI.
- Never add a "Generated with Claude Code" line to a commit message or a pull request.
- Use the local git identity of this repo: `tangerine0000 <81902276+tangerine0000@users.noreply.github.com>`.

## Before a push

- Run `gh auth status`. Make sure that `tangerine0000` is the active account.
- If `tannguyen-innomize` is active, run `gh auth switch --hostname github.com --user tangerine0000`.
