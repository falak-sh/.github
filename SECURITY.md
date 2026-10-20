# Security policy

Falak runs an agent with root privileges on your servers, so we take security reports seriously.

## Reporting a vulnerability

**Please do not open a public issue.** Report privately through GitHub:
open the repository's **Security** tab → **Report a vulnerability**
(for Falak: https://github.com/falak-sh/falak/security/advisories/new).

Include what you found, how to reproduce it, and the version (`falak-ctl status` or the release tag).
You will get an acknowledgement within 3 days and a fix or plan within 14 days for confirmed issues.
We credit reporters in the release notes unless you prefer otherwise.

## Supported versions

Only the latest minor release gets security fixes. Update with `falak-ctl update`.
