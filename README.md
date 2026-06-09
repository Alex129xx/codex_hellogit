# codex_hellogit

A small practice repository for learning how Codex works with Git, GitHub, worktrees, feature branches, and pull requests.

## What is inside

- `hello_world.py`: a tiny Python script created as the first Codex + GitHub experiment.

## Basic usage

Run the script with:

```powershell
python hello_world.py
```


## Development workflow

- Keep `main` as the stable branch that reflects reviewed, ready-to-use project changes.
- Create a feature branch for each focused change so work stays isolated until it is ready for review.
- Use Git worktrees when you want separate working directories for multiple branches at the same time without constantly switching context.
- Open a pull request back to `main` when a feature branch is complete, describe the change, and wait for review before merging.
