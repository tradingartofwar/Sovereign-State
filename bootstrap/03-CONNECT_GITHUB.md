# Step 3 — Connect GPT Directly to GitHub

The ordinary bootstrap uses ChatGPT's direct GitHub plugin or connector. It does not use a terminal or `gh` CLI.

## Connection sequence

1. Open the Plugins area in ChatGPT on the web, desktop app, or mobile app.
2. Find and install the GitHub plugin if it is available to the person's account.
3. Connect GitHub when prompted.
4. The person completes GitHub authentication and reviews the requested permissions themselves.
5. Limit access to the intended account and repositories when GitHub offers that choice.
6. Start a new ChatGPT Work chat after installation if needed.

Official product guidance: [Plugins in ChatGPT and Codex](https://learn.chatgpt.com/docs/plugins)

## Harmless verification

Ask GPT to:

1. Read the private repository's README.
2. Report the repository name and confirm that it is private without repeating personal content.
3. Create or update `state/BOOTSTRAP_STATE.md` using the public template.
4. Read the written file back and confirm the exact bootstrap stage.

Successful read and successful write are separate proofs. Establish both.

## Failure behavior

If the direct GitHub connection is not available or lacks the needed permission:

- explain the precise missing capability;
- help the person check plugin installation, connection, repository selection, or permissions;
- preserve a clear resume point;
- offer manual copy-and-paste as a temporary fallback if appropriate;
- do not install or configure `gh` CLI unless the person explicitly chooses a developer workflow outside this ordinary bootstrap.
