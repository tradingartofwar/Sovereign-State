# Step 1 — Secure the Accounts

The goal is safe recovery and adequate protection without turning security into a barrier.

## GPT rules

- Explain one action at a time.
- The person performs password and authentication steps directly on the provider's screen.
- Never ask to see or receive passwords, QR secrets, one-time codes, recovery codes, passkeys, or tokens.
- Confirm completion, not the secret value.
- Pause if the person becomes uncertain or overloaded.

## Assisted default path

For an ordinary assisted GitHub setup, the recommended sequence is:

1. Confirm that the person can access their primary email and its recovery method.
2. Confirm that their ChatGPT account is accessible and appropriately protected.
3. Install or open a time-based one-time-password authenticator. Google Authenticator is the default example in this bootstrap, but another suitable authenticator may be used.
4. Create or sign in to the person's own GitHub account using a unique password.
5. Enable GitHub two-factor authentication with the authenticator.
6. Download the GitHub recovery codes.
7. Have the person store the recovery codes somewhere secure and separate from ordinary chat and repositories, preferably in a password manager or another recovery location they understand.
8. Add another recovery method when appropriate and supported.

Follow GitHub's current interface and official guidance rather than relying on old button names:

- [Configure GitHub two-factor authentication](https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa/configuring-two-factor-authentication)
- [Configure recovery methods](https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa/configuring-two-factor-authentication-recovery-methods)

## Completion check

Ask only:

- Can you sign in to ChatGPT?
- Can you sign in to GitHub?
- Is GitHub two-factor authentication active?
- Have you stored the recovery codes somewhere you can find if your phone is lost?

Do not record the answers' secret contents. When complete, proceed to private repository creation.
