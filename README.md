# Cxbx-Reloaded game-compatibility project

This project is intended to gather all compatibility reports for Cxbx-Reloaded.

(Cxbx-Reloaded is an original Xbox emulator, see [the Cxbx-Reloaded project on GitHub](https://github.com/Cxbx-Reloaded/Cxbx-Reloaded).)


*This project is NOT intended for issues that are emulation-related.*

*(Emulation-related issues must be submitted to [the Cxbx-Reloaded project itself](https://github.com/Cxbx-Reloaded/Cxbx-Reloaded/issues).)*

## Unique reports

* All compatibility reports must be reported [here, in this issue tracker](https://github.com/Cxbx-Reloaded/game-compatibility/issues).
* In this game-compatibility project, each title is assigned ONE issue.
* Do not create duplicate issues (first, search if a title already has an issue).
* Duplicate reports will be merged into one, duplicates will be closed.
* Unique game-compatibility issues are kept open forever, regardless of state.


## Issue titles

Issue titles MUST mention the XBE title, optionally followed by an alternative title in square brackets, followed by a mandatory Title ID in square brackets, then lastly followed by a mandatory version number in square brackets. Nothing else.

Example : [FROM RUSSIA WITH LOVE (TM) \[007: From Russia with Love\] \[45410079\] \[1.01\]](https://github.com/Cxbx-Reloaded/game-compatibility/issues/10).

Verify titles against [the Xbox-Games database](http://www.xbox-games.org/) and [this Xbox1 name lookup](https://github.com/roman5566/i360gm/blob/master/Xbox1NameLookup.csv) list.


## Compatibility attribute labels

Use [the pre-defined GitHub issue labels](https://github.com/Cxbx-Reloaded/game-compatibility/labels) to indicate compatibility attributes.

Request new labels via a separate issue (these issues *will* be closed afterwards).

Issue labels should show the compatibility for the latest tested build.

### Label categories:

* issue-, zero or more of : audio, files, input, kernel, memory, regression, timing, video
* region-, zero or more of : us-canada, japan, other (sourced from dumped XBE Game Region flags 1, 2, 4)
* state-, one of : perfect, working, partially-working, interactive, booting, crashes, unresponsive, unsupported or unverified (see below)
* type-, one of : arcade, coverdisk, demo, homebrew, retail, sample, unreleased or xbla
* xbe-, zero or more of : dump-needed, linked-to-debug-xdk, tampered-with
* xdk-, one or more XDK versions (sourced from dumped XBE library versions)

#### State labels :

|State|Meaning|
|:---|:---|
|**state-perfect**|Functions identical to real hardware, no observable issues|
|**state-working**|Usable with minor issues not preventing gameplay/functioning of the title|
|**state-partially-working**|Partially working, but has serious issues that prevent progression/use of important features|
|**state-interactive**|Shows menus, responds to input, but main functionality does not work|
|**state-booting**|Shows visuals like splash screens, logos, intros, etc and/or has audible effects, but does not progress further|
|**state-crashes**|Crashes during startup, no visual or audible output|
|**state-unresponsive**|Hangs during startup|
|**state-unsupported**|Title uses Linked-Time-Code-Generation, which cannot be HLE'ed, will require LLE|
|**state-unverified**|Unverified prior state, possibly regressed|


## Description

If available, start with a title-specific link to one of [Wikipedia](https://en.wikipedia.org/wiki/List_of_Xbox_games)'s List of Xbox games.

### Screenshots

Adding screenshots to issues is allowed.

Don't add more than 8 screenshots per issue (unless more are absolutely required).

## On closing

Don't flood reports with long discussions (all chit-chat is subject to removal).


Maintainers will be appointed to enforce these guidelines to all issues.

These rules are subject to change.

Our thanks go out to everyone showing an interest and/or investing time and effort in our project : Thank you very much!

- The Cxbx-Reloaded dev team.
