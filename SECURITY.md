# Security Policy

## Supported Versions

This repository contains a small browser-only web game.

There is no backend, account system, leaderboard, payment flow, or server-side data storage connected to this project.

| Version | Supported |
| --- | --- |
| Latest deployed version | Best-effort |
| Older versions or forks | Not supported |

## Reporting a Vulnerability

If you find a security issue, please report it privately instead of opening a public issue.

You can report issues by using GitHub's private vulnerability reporting feature if it is available for this repository, or by contacting the maintainer through the contact information listed on the GitHub profile.

Please include:

- A clear description of the issue
- Steps to reproduce it
- The affected file, page, or deployment URL
- The expected impact
- Any proof of concept, screenshots, or logs that help verify the issue

## What Counts as a Security Issue

Valid security issues may include:

- Cross-site scripting or script injection
- Malicious files or unsafe third-party assets
- Exposed secrets, tokens, credentials, or private data
- Unsafe redirects or links to malicious content
- Vulnerabilities that affect users visiting the deployed game page
- Supply chain issues in dependencies, build tooling, or hosted assets

## What Does Not Count as a Security Issue

The following are not considered security vulnerabilities for this project:

- Modifying the local score in the browser
- Changing JavaScript, HTML, CSS, or game state through DevTools
- Automating clicks or manipulating gameplay locally
- Bypassing game logic that only affects the local browser session
- Requests for anti-cheat, account protection, or leaderboard integrity

This project has no competitive system, no user accounts, and no server-side score validation. Local gameplay manipulation does not create a security impact.

## Security Expectations

This project is maintained as a small experimental game. Security fixes may be reviewed and handled on a best-effort basis.

Please do not publicly disclose a confirmed vulnerability until it has been reviewed and, where appropriate, fixed.
