# Step 1 — Secure the Accounts

The goal is safe recovery and adequate protection without turning security into a barrier.

## GPT rules

- Explain one action at a time.
- Inspect the person's available devices and supported recovery options before recommending a method.
- The person performs password and authentication steps directly on the provider's screen.
- Never ask to see or receive passwords, QR secrets, one-time codes, recovery codes, passkeys, or tokens.
- Confirm completion, not the secret value.
- Do not ask a trusted helper to receive or retain the person's secrets.
- Preserve a non-secret resume point before switching devices or applications.
- Pause if the person becomes uncertain or overloaded.

## Assisted default path

For an ordinary assisted GitHub setup, the recommended sequence is:

1. Confirm that the person can access their primary email and understands its recovery method.
2. Confirm that their ChatGPT account is accessible and appropriately protected.
3. Create or sign in to the person's own GitHub account using a unique password or supported passwordless method.
4. Enable GitHub two-factor authentication using the least burdensome supported method the person can understand and recover. A passkey, security key, authenticator application, or another currently supported method may be appropriate.
5. Download the GitHub recovery codes.
6. Have the person store the recovery codes somewhere secure, separate from chat and repositories, that they understand and can reach if a device is lost.
7. Add another supported recovery method when appropriate.
8. Confirm that losing the current phone or computer would not permanently block account recovery.

Follow GitHub's current interface and official guidance rather than relying on old button names:

- [Configure GitHub two-factor authentication](https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa/configuring-two-factor-authentication)
- [Configure recovery methods](https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa/configuring-two-factor-authentication-recovery-methods)

## Completion check

Ask only:

- Can you sign in to ChatGPT?
- Can you sign in to GitHub?
- Is GitHub two-factor authentication active?
- Have you stored the recovery codes somewhere you can find if your current device is lost?
- Do you understand which person, if anyone, is helping with account setup and whether they retain any access?

Do not record secret contents. When complete, preserve the resume point and proceed to private repository creation.
