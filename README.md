# Release Radar feed

Signed catalogue files for the **Release Radar** Salesforce package by InspireAI.

- `manifest.json` lists the catalogue version and the SHA-256 hash of every language file.
- `manifest.json.sig` is an RSA-SHA256 signature of the manifest. The package verifies it with the public key it
  ships with before it uses any content; unsigned or modified files are ignored.

This repository is published automatically from a reviewed pull request. Please don't open issues or PRs here.
