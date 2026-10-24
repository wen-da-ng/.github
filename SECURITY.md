# Security

## Reporting a problem

Please **don't** open a public issue. Report it privately instead:

- On the affected repository: **Security → Report a vulnerability** (GitHub's private reporting). For the app, use [otterbridge-allsense](https://github.com/wen-da-ng/otterbridge-allsense/security/advisories/new).
- Or email [allsense@otterbridge.org](mailto:allsense@otterbridge.org).

Say what's affected (app version, or library and version), how to reproduce it, and what an attacker could do. You'll get an answer within a week. Once it's fixed, you're credited in the release notes unless you'd rather not be.

## What counts

For example: a way to read or control a phone's streams without its pairing token, a client library that can be made to run code or write files it shouldn't, or a release whose APK doesn't match its published checksums.

Not a vulnerability: someone with the pairing link reading what the user shared (the link is the password; **Settings → Server → New token** revokes it).

## Supported versions

Only the latest release of the app and of each library gets fixes.
