*Last updated: November 7th, 2020*

We greatly appreciate investigative work into security vulnerabilities carried out
by well-intentioned, ethical, security researchers. We follow the practice of
[responsible disclosure](https://en.wikipedia.org/wiki/Responsible_disclosure) in order
to best protect our user base from the impact of security issues. On our side, this
means:

* We will respond to security incidents as a priority.
* We will fix the issue as soon as is practical, keeping in mind that not all risks are
  created equal.
* We will always transparently let our community know about any incidents that affect
  them.

If you have found a security vulnerability in t2bot.io, we ask thay you disclose it
reponsibly by messaging [@travis:t2l.io](https://matrix.to/#/@travis:t2l.io) on Matrix.
Please do not discuss potential vulnerabilities in public on near-public without first
validating with us.

On receipt, we will:

* Review the report, verify the vulnerability, and respond with confirmation or for
  more information. We typically reply within 24 hours.
* Once the security bug has been addresses we will notify the reporter, who is then
  welcome to optionally disclose publicly.

Please note that although t2bot.io is built off Matrix, we cannot reasonably take the
lead on resolving incidents relating to the protocol. If an issue is determined to be
an issue with the Matrix protocol, we will report it upstream to the Matrix team per
their [security disclosure policy](https://matrix.org/security-disclosure-policy/). We
will respond to the original reporter to indicate that their report has been proxied
to the Matrix team, and, if desired, disclose the reporter to the Matrix team for
appropriate credit. Similar programs apply for software t2bot.io depends on, such as
bridges and bots not authored by us directly.

We do not currently provide a bug bounty program. We do, however, maintain a Hall of Fame
to recognize those who have responsibly disclosed security issues to us in the past.

# Hall of Fame

* *March 4th, 2021* - matrix-media-repo - [jomat](https://jmt.gr/)<br />
  An issue where short audio files could crash the process. Fixed in [v1.2.3](https://github.com/turt2live/matrix-media-repo/releases/tag/v1.2.3)
* *April 15th, 2021* - matrix-media-repo - [Muhammad Zaid Ghifari](https://twitter.com/Zheev1)<br />
  Memory exhaustion through thumbnailing crafted media. Described as [CVE-2021-29453](https://github.com/turt2live/matrix-media-repo/security/advisories/GHSA-j889-h476-hh9h)
  and fixed in [v1.2.7](https://github.com/turt2live/matrix-media-repo/releases/tag/v1.2.7).
* *April 30th, 2021* - matrix-media-repo - [jomat](https://jmt.gr/)<br />
  An issue where malicious APNGs files could crash the process. Fixed in [v1.2.8](https://github.com/turt2live/matrix-media-repo/releases/tag/v1.2.8)

If you think we missed you, sorry - please let us know by messaging
[@travis:t2l.io](https://matrix.to/#/@travis:t2l.io) on Matrix.
