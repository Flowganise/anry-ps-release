# Anry for PrestaShop

Anry tells you where your store is losing money and hands you the fix. This module prints the Anry tracker on your front office and reports orders server side, so visitor analytics, session replays, and revenue attribution all come from the same sessions.

This repository is the distribution channel for the module. It holds published releases only; the module source lives in Anry's private monorepo.

**[Download the latest version](https://github.com/Flowganise/anry-ps-release/releases/latest/download/anry.zip)**

## Requirements

- PrestaShop 1.7.6.0 or higher
- An Anry account (get one at [anry.io](https://anry.io))

## Installation

1. Download `anry.zip` from the link above, or from the [Releases page](https://github.com/Flowganise/anry-ps-release/releases/latest).
2. In your PrestaShop back office, go to Modules, Module Manager, Upload a module.
3. Drop the zip in and wait for the install to finish.
4. Open the module's Configure page.
5. Click "Connect with Anry" and pick the site to link this shop to.

That is the whole setup. There is no tracking code to paste and nothing to configure afterwards.

## What it does

- Loads the Anry tracker on every front office page
- Records session replays and heatmaps
- Reports each validated order server side, attributed to the session that produced it
- Deduplicates orders so a refreshed confirmation page never double counts revenue

## Updating

Download the latest zip and upload it again through the Module Manager. Your connection is preserved across updates.

The module does not update itself. Watch this repository's releases, or check the Anry dashboard, to know when a new version is out.

## Uninstalling

Uninstalling from the Module Manager removes the connection and every table the module created. Data already collected stays in your Anry account.

## Support

[hello@anry.io](mailto:hello@anry.io)

## License

MIT
