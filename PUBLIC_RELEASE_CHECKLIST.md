# Public release checklist

## Current review status

The README and selected conventional root files were inspected. A full repository tree, commit history, and all historical blobs have **not** been audited. No claim of a complete secrets scan is made.

## Before changing visibility

- [ ] Review every file in the repository, including hidden files and large assets.
- [ ] Scan the entire Git history for API keys, passwords, tokens, private addresses, and confidential information.
- [ ] Remove any exposed secrets from history and rotate them at the provider.
- [ ] Confirm that linked projects and portfolio statements are accurate.
- [ ] Add verified screenshots and demos if available.
- [ ] Confirm the repository contains only material you have permission to publish.
- [ ] Decide whether to add a license.
- [ ] Change visibility only after these checks pass.

**Note:** A .gitignore prevents accidental future tracking; it does not remove previously committed secrets or files.
