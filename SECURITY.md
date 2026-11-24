# Security policy

This is the default reporting policy for GrabLine organization repositories.
A repository's own security policy takes precedence. The desktop app and
GrabLine Connect share the
[GrabLine security policy](https://github.com/GrabLine/GrabLine/blob/main/SECURITY.md).

## Report a vulnerability privately

Open the affected repository on GitHub, select **Security**, then **Report a
vulnerability** while signed in. For the desktop app or browser companion, use
[GrabLine's private report form](https://github.com/GrabLine/GrabLine/security/advisories/new).
For the Android app, use
[GrabLine for Android's private report form](https://github.com/GrabLine/grabline-android/security/advisories/new).

Include the affected version or commit, OS/browser where relevant, a minimal
reproduction, the expected security boundary, impact and sanitized evidence.
Use synthetic inputs. Do not include passwords, cookies, keys, personal
downloads or unrelated user data.

Do not open a public issue containing exploitable details before a fix ships.
If a repository does not offer private reporting, follow its documented private
contact method. If none is listed, ask its maintainer for a private contact
without disclosing exploit details. There is no guaranteed response deadline.

## Scope and supported versions

For GrabLine, malicious server/page/archive input crossing application trust
boundaries is in scope. See the
[security model](https://github.com/GrabLine/GrabLine/blob/main/docs/security-model.md)
for enforced checks and advisory content warnings. Other repositories should
describe their own boundaries and supported versions.

Report against the affected project's latest published version, or identify an
unreleased commit precisely. Older GrabLine releases are not patched separately.
Reporters who request attribution are credited when a GrabLine fix or advisory
is published, as described in the desktop repository's policy.
