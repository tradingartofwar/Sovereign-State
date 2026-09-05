# Step 3 — Connect GPT Directly to GitHub

The ordinary bootstrap uses a supported direct GitHub plugin or connector. It does not require a terminal, local repository, VS Code, WSL, or `gh` CLI.

Product interfaces change. Inspect the capabilities available in the person's current ChatGPT environment and follow current official guidance rather than inventing or relying on remembered menu labels.

## Connection sequence

1. Identify whether a supported GitHub connection is available in the current web, desktop, or mobile environment.
2. If setup is required, guide the person to the current connection or plugin interface.
3. The person completes GitHub authentication and reviews the requested permissions themselves.
4. Limit access to the intended account and repositories when GitHub offers that choice.
5. Preserve a non-secret resume point before any application switch or sign-in step.
6. Start a fresh GPT conversation after connection only when the environment requires it; resume from the private repository rather than restarting onboarding.

Official product guidance: [Plugins in ChatGPT and Codex](https://learn.chatgpt.com/docs/plugins)

## Harmless verification

Ask GPT to:

1. Read the private repository's README or `RESUME_HERE.md`.
2. Report the repository name and confirm that it is private without repeating personal content.
3. Create or update `state/BOOTSTRAP_STATE.md` using the public template.
4. Read the written file back and confirm the exact bootstrap stage.
5. Update `RESUME_HERE.md` with the last established result and next smallest step.

Successful authentication, read access, and write access are separate proofs. Establish the capabilities actually needed.

## Failure behavior

If the direct GitHub connection is unavailable or lacks the needed permission:

- explain the precise missing capability;
- help the person check connection, repository selection, or permissions;
- preserve a clear human-readable resume point;
- continue helping in the current environment when safe;
- offer a short manual copy-and-paste continuity packet as a temporary fallback when appropriate;
- do not install or configure `gh` CLI unless the person explicitly chooses a developer workflow outside this ordinary bootstrap.

A connection failure is a technical condition, not a failure by the person and not permission to redesign or expose their state.
