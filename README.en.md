# Scavenging Expansion / 拾荒拓展

[简体中文](README.md) | **English**

A **Probably Stolen** mod featuring a skill tree, a multifunction Inventor Backpack, and a furnace.

This repository provides **stable release downloads and issue reporting**. Source code is not published here.

- **[Download the latest stable release](https://github.com/eotn00/ProbablyStolen-ScavengerSkills/releases/latest)** — Under Assets, download `ScavengerSkills-<version>.zip`, not GitHub's automatically generated Source code archives.
- **[Report a bug in English](https://github.com/eotn00/ProbablyStolen-ScavengerSkills/issues/new?template=bug-report.en.yml)** — Describe what happened and attach the `Player.log` from the affected game session.
- [Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3832768562)
- [Recommended companion mod: Retrofit Rights](https://github.com/eotn00/ProbablyStolen-RetrofitRights/blob/main/README.en.md)

## Installation and updates (Windows)

1. Exit the game and back up your saves.
2. Download the mod ZIP from Releases. Extract its `ScavengerSkills` folder into the game's `Mods` directory.
3. Check that the paths are `Mods/ScavengerSkills/manifest.xml` and `Mods/ScavengerSkills/ScavengerSkills.dll`. Avoid an extra nested folder with the same name.
4. Enable the mod in the game's mod menu and restart if prompted. Press **F8** in game to open the menu. See the included `README.txt` for detailed gameplay instructions.

In Steam, use **Manage → Browse local files** to find the game installation directory. Alternatively, subscribe through Steam Workshop.

**Do not keep Workshop, local release, and test copies with the same mod ID installed together.** A local copy may take precedence over the Workshop version. Back up saves before switching sources, and exit the game before removing duplicate mod copies. When updating a local installation, replace the mod files, not your personal saves.

## Reporting a problem

Search existing Issues first, then use the **[English bug report form](https://github.com/eotn00/ProbablyStolen-ScavengerSkills/issues/new?template=bug-report.en.yml)**. A GitHub account is required to submit a report. Include:

- Your game version, mod version, installation source, and other enabled mods.
- What actually happened, what you expected, and the steps leading to the problem.
- **The complete `Player.log` from the session in which the problem occurred.** Screenshots or videos are helpful, but do not replace the log.

You do not need to know which mod caused the problem. Describe the symptoms and list the enabled mods.

### Finding Player.log (Windows)

1. Launch the game and reproduce the problem.
2. Press `Win + R`, paste the following path, and press Enter:

   ```text
   %USERPROFILE%\AppData\LocalLow\Questing Goose Studio\Probably Stolen
   ```

3. Immediately copy `Player.log` somewhere safe, then drag it into the form's log field. **Collect it before launching the game again**, as a new session may overwrite it. If relevant, also attach `Player-prev.log` and identify which session it belongs to.
4. If GitHub rejects `.log` files, ZIP the log or rename a copy to `.txt` and upload that instead. Wait for the upload to finish before submitting. Do not provide only a few error lines or a screenshot of the log.

Issues and attachments are public. Check for personal information such as usernames and local paths before uploading. If necessary, redact only sensitive information while keeping the relevant errors and context. Do not upload passwords, tokens, or unrelated personal files. If you cannot obtain the log, explain why and which location you checked in the log field.

## Important notes

Empty the tool pockets before resetting skills. Nuclear waste can cause a lethal explosion by default. Refer to the release's included documentation for gameplay, settings, and compatibility notes; not every third-party mod combination is guaranteed to work.
