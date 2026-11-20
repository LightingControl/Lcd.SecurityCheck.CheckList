# Security Check check list

The list of checks the LCD Security Check driver for Crestron Home downloads, with its signature.

- `checklist.json`: the list
- `checklist.json.sig`: an RSA SHA-256 signature of it, which the driver checks before it uses the list

This branch is published by a workflow in the driver's repository. Don't edit it by hand: a change here would
fail the signature check on every processor.
