<p align="center">
  <img src="https://raw.githubusercontent.com/Kastle-Five/.github/807a9f1dbed51b178d3ca848919d9bb9feebd283/profile/banner.png" alt="AI writes the code. K5 tests, hunts and guards it. Kastle Five" width="100%">
</p>

<br>

K5 is a private developer workspace that runs on your Mac. Your code passes ten systems in turn, from what may leave your Mac to sealed evidence of what happened.

Kastle Five makes software in Rotterdam, around cybersecurity and privacy.

<br>

### The work

**Bearing** · Security  
Secret scanning, with the access-control, cookie, header and third-party findings seen in the browser. Its static audit, Armory, flags weak cryptography, unsafe uploads, script and SQL injection, open redirects, unthrottled logins, download-and-execute steps, and lockfile entries with no integrity hash or from git, http or an unknown host.

**Ghost** · Virtual users  
Drives real Chrome sessions as each of your test users. On your own test targets it checks cross-user data access, session invalidation on sign-out, forms without CSRF protection, login throttling after failed attempts, and what remains once a test account is deleted.

**BugDog** · Bugs  
Reproduces each failure in a fresh, isolated session and replays it to verify the fix. A replay it can't make faithful is reported, never passed.

**Oracle** · Private AI  
Investigates findings and proposes patches with a model you choose: local, or remote with your own key. The plan comes before any action, and each run's context is on record.

**Hisn** · Permissions  
An approval gate on every file write, command and remote-model call. An approved change is applied exactly as shown.

### The privacy

**Veil** · Remote AI  
Inspects each request bound for a remote model for secrets, personal data and internal endpoints, and sends only what you approve.

**Clear 5** · Network  
Records every request Kastle Five makes before it leaves, and every request its test browsers made once their run ends. Drift diffs a run against a saved baseline.

**WindShell** · Private modes  
Three egress levels: Standard, Private AI, and WindShell, in which nothing leaves the Mac. Lowering the level takes a macOS authorisation dialog, and the mode is verified by live checks.

**PeakSilica** · Private architecture  
Maps where personal data flows through your code and runs checks on a sealed copy with the network closed. The project itself changes only through a change approved in Hisn.

**Arc** · Evidence  
Seals findings, runs and changes into an encrypted, signed file that only the people you choose can open, and anyone can verify.

### Your live site

**KryWire** · Site health  
Checks your live site from the outside, as a visitor sees it: certificate, security headers and cookie flags, CORS, files that should never be public, secrets in shipped code, publicly listable storage, libraries with known vulnerabilities, scripts changed against what you approved, and uptime. Each issue comes with the fix for your host. GET requests only; it reports problems, it doesn't block attacks.

**Kry4help** · Monitoring  
A monitor in plain JavaScript with no dependencies, written for you to run on your own server: checks around the clock with no Kastle Five server in between, seven days of history, reports sealed and signed, and alerts to your phone through ntfy or your own Twilio account, or to Slack, Discord or a webhook.

<br>

**K5**  ·  [kastlefive.dev](https://kastlefive.dev)

**ActivePray**  ·  daily prayer for Judaism, Christianity and Islam, on iPhone  ·  [activepray.com](https://activepray.com)
