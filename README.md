# Cxbx-Reloaded game-compatibility
This project is intended to gather all compatibility reports for [Cxbx-Reloaded](https://github.com/Cxbx-Reloaded/Cxbx-Reloaded).

*This project is NOT intended for issues that are emulation-related, or tech support.*

*Emulation-related issues must be submitted to [the Cxbx-Reloaded project itself](https://github.com/Cxbx-Reloaded/Cxbx-Reloaded/issues).*

***Tech support belongs on the [Discord](https://discord.gg/26Xjx23).***

## Unique reports
* All compatibility reports must be reported [here, in this issue tracker](https://github.com/Cxbx-Reloaded/game-compatibility/issues).
* In this game-compatibility project, each title is assigned ONE issue per version.
* Do not create duplicate issues. Search if a title already has an issue first.
* Duplicate reports will be merged into an already existing one, then closed.

## Issue titles
Issue titles MUST mention the XBE title, optionally followed by an alternative title in square brackets, followed by a mandatory Title ID in square brackets, then lastly followed by a mandatory version number in square brackets. Nothing else.

Example: [FROM RUSSIA WITH LOVE (TM) \[007: From Russia with Love\] \[EA-121\] \[1.01\]](https://github.com/Cxbx-Reloaded/game-compatibility/issues/10)
  * *Note:* [Some software has a different title ID](https://github.com/Cxbx-Reloaded/Cxbx-Reloaded/blob/ed57ca978803cfc722260fe4c2d611361d640f7e/src/core/kernel/support/Emu.cpp#L71-L77)

Verify titles against [this spreadsheet](https://docs.google.com/spreadsheets/d/1e33LTPD6TCuLqszv6orQzzlkHRFuSnIlk-OQWn5M2y8/edit#gid=347627117).

## Compatibility attribute labels
Use [the pre-defined GitHub issue labels](https://github.com/Cxbx-Reloaded/game-compatibility/labels) to indicate compatibility attributes.

Request new labels via a separate issue. They will be closed afterwards.

Issue labels should show the compatibility for the latest tested build.

### Labels:
| Label                                                                               | Amount    | Additional info
| -----                                                                               | ------    | ---------------
| [issue-](https://github.com/Cxbx-Reloaded/game-compatibility/labels?q=issue-)       | 0 or more |
| [region-](https://github.com/Cxbx-Reloaded/game-compatibility/labels?q=region-)     | 0 or more | Sourced from dumped XBE Game Region flags 1, 2, 4
| [language-](https://github.com/Cxbx-Reloaded/game-compatibility/labels?q=language-) | 0 or more |
| [state-](https://github.com/Cxbx-Reloaded/game-compatibility/labels?q=state-)       | 1         |
| [type-](https://github.com/Cxbx-Reloaded/game-compatibility/labels?q=type-)         | 1         |
| [xbe-](https://github.com/Cxbx-Reloaded/game-compatibility/labels?q=xbe-)           | 0 or more |
| [xdk-](https://github.com/Cxbx-Reloaded/game-compatibility/labels?q=xdk-)           | 1 or more | XDK versions sourced from dumped XBE library versions

## Description
If available, start with a title-specific link to one of [Wikipedia](https://wikipedia.org/wiki/List_of_Xbox_games)'s List of Xbox games.

### Screenshots
Adding screenshots to issues is allowed, but don't add more than 8 unless more are absolutely required.

## In closing
Don't flood reports with long discussions. All chit-chat is subject to removal.

Maintainers will be appointed to enforce these guidelines to all issues.

These rules are subject to change.

Our thanks go out to everyone showing an interest and/or investing time and effort in our project: Thank you very much!

* The Cxbx-Reloaded dev team.
