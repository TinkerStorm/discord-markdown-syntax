# channel-backup-template

A template for [channel-backup](https://npm.im/channel-backup).

## Instructions to run

```sh
npm install
# add webhook to env or 'config.json'
# add your files within the repository and specify them directly or use globs
npm run sequence
```

---

> This environment is configured to run in our [community server](https://discord.gg/https://discord.gg/Bb3JQQG) as part of our tools and resources for Developers and Community Managers.

- *Only languages referred to as 'Common' by Highlight.js are posted due missing a lot of languages and not having a finalized structure.*

If you use this on your own server, please wipe the environment cache before running it yourself - check which files you are posting before having it run.

### Community specific files

- `./content/credits.md` - Credits for the content
  > Referring to two channels in our own server, Wolfri's Highlight.js Server and this repository.

## Contributor Notes

> Before you ask, yes... I do make a joke of light theme in the [additional notes](./content/additional.md).

This environment may intend to use features that it could have had implemented before the package was rewrittten (i.e. raw send).

All examples attempt to use figurative descriptions where possible, but any `**/quick.md` will use colour descriptions with literals if absolutely necessary. Unsupported formatting is not included, but a note may be added (either in a local README or in the file itself).

~~Any file by itself or a folder containing a `**/quick.md` file is more likely to be the most consistent file for that langauge, but it may prioritise colour description over anything else due to it being focused on colour rather than 'functionally correct syntax'.~~

The configuration setup here uses a different file structure to the one originally intended from [channel-backup-template](https://github.com/RocketDragon/channel-backup-template) or [community-backup](https://github.com/TinkerStorm/community) - relying on a config folder instead of bundling with the given channel content as a `**/config.json`.