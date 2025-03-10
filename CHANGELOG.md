# Changelog

## [v1.6.0](https://github.com/Automattic/simplenote-electron/releases/tag/v1.6.0) (2019-07-01)

### Features
- Add custom tooltips to toolbar buttons [#1214](https://github.com/Automattic/simplenote-electron/pull/1214)
- Improve search performance on long notes [#1218](https://github.com/Automattic/simplenote-electron/pull/1218)

### Fixes

- Extract text manipulation helpers ( [#1212](https://github.com/Automattic/simplenote-electron/pull/1212) )
- Refactor settings state ( [#1216](https://github.com/Automattic/simplenote-electron/pull/1216) )
- Remove hacky focus manipulation in DraftJS ( [#1219](https://github.com/Automattic/simplenote-electron/pull/1219) )
- Remove unused build files ( [#1173](https://github.com/Automattic/simplenote-electron/pull/1173) )
- Keep editor in sync with selected note in NoteList ( [#1220](https://github.com/Automattic/simplenote-electron/pull/1220) )
- Fix large tag-list squashing note-list ( [#1227](https://github.com/Automattic/simplenote-electron/pull/1227) )
- Updated GitHub templates
- Updated most dependencies
- Fix Prettier Errors ( [#1343](https://github.com/Automattic/simplenote-electron/pull/1343) )
- Use md5 node module ( [#1308](https://github.com/Automattic/simplenote-electron/pull/1308) )
- Remove ajv peer dependency ( [#1360](https://github.com/Automattic/simplenote-electron/pull/1360) )
- Fix linting warning in tag-chip ( [#1314](https://github.com/Automattic/simplenote-electron/pull/1314) )
- Fix linting warning in lib/app ( [#1313](https://github.com/Automattic/simplenote-electron/pull/1313) )
- Fix linting warning in lib/auth/index ( [#1311](https://github.com/Automattic/simplenote-electron/pull/1311) )
- Docs update: Additional step in installing ( [#1252](https://github.com/Automattic/simplenote-electron/pull/1252) )

## [v1.5.0](https://github.com/Automattic/simplenote-electron/releases/tag/v1.5.0) (2019-02-21)

### Features

- Add a sync indicator in the Navigation Bar that shows the last synced time, as well as a list of unsynced notes when edits are made while disconnected from the server [#1201](https://github.com/Automattic/simplenote-electron/pull/1201)

### Fixes

- Fix issue where in short or empty notes, the clickable area did not expand to the height of the editor [#1199](https://github.com/Automattic/simplenote-electron/pull/1199)
- Fix a Dark Mode color glitch in the Note List on Ubuntu [#1202](https://github.com/Automattic/simplenote-electron/pull/1202)
- Change the Insert Checklist shortcut to <kbd>Ctrl+Shift+C</kbd> (<kbd>Cmd+Shift+C</kbd> on macOS) to avoid a conflict with Polish keyboards [#1210](https://github.com/Automattic/simplenote-electron/pull/1210)
- Tweak the dropzone color to preserve the dashed border in Light Mode [#1211](https://github.com/Automattic/simplenote-electron/pull/1211)
- Remove unneeded border when printing [#1206](https://github.com/Automattic/simplenote-electron/pull/1206)
- Fix wrong icon in the “Check for Updates” dialog on Linux [#1172](https://github.com/Automattic/simplenote-electron/pull/1172)
- Fix CJK-related text duplication bugs after a tab character [#1172](https://github.com/Automattic/simplenote-electron/pull/1172)
- Make “Select All” work in the Markdown Preview [#1172](https://github.com/Automattic/simplenote-electron/pull/1172)

## [v1.4.1](https://github.com/Automattic/simplenote-electron/releases/tag/v1.4.1) (2019-02-08)

### Enhancements

- Keep approximate cursor position when a remote change comes in from the server [#1193](https://github.com/Automattic/simplenote-electron/pull/1193) [@qualitymanifest](https://github.com/qualitymanifest)

### Fixes

- Verify last used monitor availability when restoring window position [#1176](https://github.com/Automattic/simplenote-electron/pull/1176)
- Fix erratic cursor jumps to last line [#1193](https://github.com/Automattic/simplenote-electron/pull/1193)

## [v1.4.0](https://github.com/Automattic/simplenote-electron/releases/tag/v1.4.0) (2019-01-29)

### Features

- Checklists! Markdown-style checkboxes (`- [ ]` and `- [x]`) will now be rendered in the Editor as a clickable checkbox. Checklists can also be added from the Format ▸ Insert Checklist menu item [#1145](https://github.com/Automattic/simplenote-electron/pull/1145) [#1154](https://github.com/Automattic/simplenote-electron/pull/1154) [#1159](https://github.com/Automattic/simplenote-electron/pull/1159) [#1166](https://github.com/Automattic/simplenote-electron/pull/1166) [#1168](https://github.com/Automattic/simplenote-electron/pull/1168)

### Enhancements

- Change the button icon in the top left corner from a tag to a hamburger menu [#1106](https://github.com/Automattic/simplenote-electron/pull/1106)
- Improve accessibility of the tab panels in the Settings and Share dialogs [#1109](https://github.com/Automattic/simplenote-electron/pull/1109)
- Add a Tools panel (containing the Import/Export functions) to the Settings dialog [#1111](https://github.com/Automattic/simplenote-electron/pull/1111)
- Add ability to toggle checkboxes in the Markdown preview [#1133](https://github.com/Automattic/simplenote-electron/pull/1133)
- Show Published icon in Condensed view [#1110](https://github.com/Automattic/simplenote-electron/pull/1110)
- Add a “Check for Updates” menu item [#1090](https://github.com/Automattic/simplenote-electron/pull/1090)
- Improve alphabetical note sorting to ignore accents, diacritics, and leading `#` characters [#1144](https://github.com/Automattic/simplenote-electron/pull/1144)
- Improve contrast in Dark Mode [#1062](https://github.com/Automattic/simplenote-electron/pull/1062)

### Fixes

- Prevent the Search Bar from shrinking when there are no notes [#1108](https://github.com/Automattic/simplenote-electron/pull/1108)
- In narrow screen sizes, correctly close the note after a “Trash” or “Restore from Trash” command [#1131](https://github.com/Automattic/simplenote-electron/pull/1131)
- Make the text in the Markdown preview selectable [#1132](https://github.com/Automattic/simplenote-electron/pull/1132)
- Update the selected note when notes have reloaded [#1130](https://github.com/Automattic/simplenote-electron/pull/1130)
- Prevent Note List excerpts from being to short [#1104](https://github.com/Automattic/simplenote-electron/pull/1104)
- Fix an issue where a local change to a note’s content would reselect that note in the Editor, even when the user had already navigated away to a different note [#1141](https://github.com/Automattic/simplenote-electron/pull/1141)
- Fix lag when renaming tags [#1127](https://github.com/Automattic/simplenote-electron/pull/1127)
- Remove unnecessary left border in Focus Mode [#1149](https://github.com/Automattic/simplenote-electron/pull/1149) [@qualitymanifest](https://github.com/qualitymanifest)
- Prevent Markdown list prefixes from multiplying when hitting Return [#1148](https://github.com/Automattic/simplenote-electron/pull/1148)
- When copying a note, ensure that the raw text is copied to the clipboard instead of rich text [#1155](https://github.com/Automattic/simplenote-electron/pull/1155)
- Fix line break behavior in the Markdown preview to match common Markdown implementations, as well as the other Simplenote apps [#1169](https://github.com/Automattic/simplenote-electron/pull/1169)
- Fix CJK-related crashes after a tab character [#1171](https://github.com/Automattic/simplenote-electron/pull/1171)
- Various security and under-the-hood improvements 

## [v1.3.4](https://github.com/Automattic/simplenote-electron/releases/tag/v1.3.4) (2018-12-18)

### Fixes

- Prevent a performance issue that can occur when there is a lot of whitespace in a Markdown note [#1078](https://github.com/Automattic/simplenote-electron/pull/1078) [#1088](https://github.com/Automattic/simplenote-electron/pull/1088)
- Restore tags correctly when restoring a revision [#1085](https://github.com/Automattic/simplenote-electron/pull/1085)
- Ensure that the note selected on launch is updated [#1093](https://github.com/Automattic/simplenote-electron/pull/1093)
- Improve tag field styles to accommodate notes with many tags [#1084](https://github.com/Automattic/simplenote-electron/pull/1084)
- Ensure that offline changes are synced to the server once the app is back online, even if the app was quit before syncing [#1098](https://github.com/Automattic/simplenote-electron/pull/1098) [#1103](https://github.com/Automattic/simplenote-electron/pull/1103)
- Add rate limiter to Importer to prevent overloading the server [#1101](https://github.com/Automattic/simplenote-electron/pull/1101)

## [v1.3.3](https://github.com/Automattic/simplenote-electron/releases/tag/v1.3.3) (2018-12-06)

### Fixes

- Prevent unnecessary server calls when logged out [#1067](https://github.com/Automattic/simplenote-electron/pull/1067) [#1068](https://github.com/Automattic/simplenote-electron/pull/1068) [#1071](https://github.com/Automattic/simplenote-electron/pull/1071)

## [v1.3.2](https://github.com/Automattic/simplenote-electron/releases/tag/v1.3.2) (2018-12-05)

### Enhancements
- Add support for sorting the tags list [#1042](https://github.com/Automattic/simplenote-electron/pull/1042)

### Fixes
- Add `:focus` outline to dropzone [#989](https://github.com/Automattic/simplenote-electron/pull/989)
- Fix tag entry in Chinese, Japanese, and Korean [#999](https://github.com/Automattic/simplenote-electron/pull/999)
- Make tag entry and removal smoother [#1000](https://github.com/Automattic/simplenote-electron/pull/1000)
- Fix padding for trash toolbar in Mac Electron [#1005](https://github.com/Automattic/simplenote-electron/pull/1005)
- Fix password change handling [#1022](https://github.com/Automattic/simplenote-electron/pull/1022)
- Simplify printing [#1013](https://github.com/Automattic/simplenote-electron/pull/1013)
- Fix incorrect menu labels in note sorting options [#1023](https://github.com/Automattic/simplenote-electron/pull/1023) [@tonytettinger](https://github.com/tonytettinger)
- Never launch in fullscreen mode [#1002](https://github.com/Automattic/simplenote-electron/pull/1002)
- Fix button styles in the tag drawer [#1031](https://github.com/Automattic/simplenote-electron/pull/1031)
- Fix app description [#1030](https://github.com/Automattic/simplenote-electron/pull/1030)
- Fix errors in app menus [#1004](https://github.com/Automattic/simplenote-electron/pull/1004)
- Delete AppData on uninstall (Windows) [#1029](https://github.com/Automattic/simplenote-electron/pull/1029)
- Fix app icon in Windows Store build [#1065](https://github.com/Automattic/simplenote-electron/pull/1065)

## v1.3.1

This release is only intended for distribution in the Windows Store. It fixes a login issue that only affected the build available there.

## [v1.3.0](https://github.com/Automattic/simplenote-electron/releases/tag/v1.3.0) (2018-11-28)

### New features

- Importers for Evernote (.enex) exports, Simplenote (.json) exports, and plain text files [#922](https://github.com/Automattic/simplenote-electron/pull/922) [#940](https://github.com/Automattic/simplenote-electron/pull/940) [#952](https://github.com/Automattic/simplenote-electron/pull/952) [#957](https://github.com/Automattic/simplenote-electron/pull/957) [#975](https://github.com/Automattic/simplenote-electron/pull/975) [#1033](https://github.com/Automattic/simplenote-electron/pull/1033)

### Enhancements

- Revamp auto updater [#869](https://github.com/Automattic/simplenote-electron/pull/869)
- Disable checkboxes and hide bullets in Markdown preview of task lists [#897](https://github.com/Automattic/simplenote-electron/pull/897) [@rakhi2104](https://github.com/rakhi2104)
- Add preview styling for `<kbd>` tags [#901](https://github.com/Automattic/simplenote-electron/pull/901) [@rakhi2104](https://github.com/rakhi2104)
- Add `markdown` property to the JSON file of exported notes [#938](https://github.com/Automattic/simplenote-electron/pull/938)
- Improve keyboard support for modal dialogs [#950](https://github.com/Automattic/simplenote-electron/pull/950)
- Show focus outlines on buttons and other controls when navigating with a keyboard [#962](https://github.com/Automattic/simplenote-electron/pull/962)
- Strip Markdown in note list excerpts (with the exception of ordered and unordered lists) [#996](https://github.com/Automattic/simplenote-electron/pull/996) [@ksdme](https://github.com/ksdme)

### Fixes

- Fix a crash bug that occurred when clicking the Share button immediately after selecting a tag in the tag drawer [#884](https://github.com/Automattic/simplenote-electron/pull/884)
- Remove outdated help text in the Share dialog [#919](https://github.com/Automattic/simplenote-electron/pull/919) [@rakhi2104](https://github.com/rakhi2104)
- Fix “bad quality package” error on Ubuntu [#933](https://github.com/Automattic/simplenote-electron/pull/933)
- Fix the Sidebar toggle button not working immediately after launch [#945](https://github.com/Automattic/simplenote-electron/pull/945)
- Make the Revisions selector full-width when in Focus Mode [#960](https://github.com/Automattic/simplenote-electron/pull/960) [@clayreimann](https://github.com/clayreimann)
- Fix issues with some buttons that were not friendly to screen readers [#961](https://github.com/Automattic/simplenote-electron/pull/961)
- Add a Back button for trashed notes in single-column view [#984](https://github.com/Automattic/simplenote-electron/pull/984) [@vadimnicolai](https://github.com/vadimnicolai)
- Fix line spacing when printing a Markdown note [#992](https://github.com/Automattic/simplenote-electron/pull/992) [@vadimnicolai](https://github.com/vadimnicolai)
- Fix margin on Publish icons in the note list [#997](https://github.com/Automattic/simplenote-electron/pull/997) [@vadimnicolai](https://github.com/vadimnicolai)
- Various security and under-the-hood improvements.

## [v1.2.1](https://github.com/Automattic/simplenote-electron/releases/tag/v1.2.1) (2018-10-16)

This is a rebuild of the faulty packages released as [v1.2.0](https://github.com/Automattic/simplenote-electron/releases/tag/v1.2.0). (Please refer to v1.2.0 for the changes)

## [v1.2.0](https://github.com/Automattic/simplenote-electron/releases/tag/v1.2.0) (2018-10-16)

_Update: There was a problem somewhere in the automated build system, and these packages will not work on Windows or Ubuntu. Please use the rebuilt packages from [v1.2.1](https://github.com/Automattic/simplenote-electron/releases/tag/v1.2.1)_

### New features
* [Focus Mode](https://github.com/Automattic/simplenote-electron/pull/881) to hide the note list pane. This can be toggled from the sidebar button, View menu, or shortcut ⌘⇧F.
* [Line Length](https://github.com/Automattic/simplenote-electron/pull/815) setting to wrap the note content to Full or Narrow widths.
* [Spell checker](https://github.com/Automattic/simplenote-electron/pull/821) (can be [toggled](https://github.com/Automattic/simplenote-electron/pull/872) on/off).

### Enhancements
* New user setting to [opt out](https://github.com/Automattic/simplenote-electron/pull/867) of analytics sharing.
* When exporting notes (File menu ▸ Export Notes), the Date Modified of each note file in the zip will reflect the [last modified date](https://github.com/Automattic/simplenote-electron/pull/826) of the note (props to @ianmorti).
* “Font Size” is renamed “Zoom” to match standard convention, and is now more discoverable at the [root level of the View menu](https://github.com/Automattic/simplenote-electron/pull/863) (props to @gie3d).
* The modification date will now [be updated](https://github.com/Automattic/simplenote-electron/pull/889) when adding or removing note tags (props to @hanhmchau).
* [Web] The [tag drawer will close](https://github.com/Automattic/simplenote-electron/issues/146) after opening the Settings dialog.

### Fixes
* [Mac] “Bring All to Front” is now in the [correct menu](https://github.com/Automattic/simplenote-electron/pull/813).
* Various security fixes.

## [v1.1.7](https://github.com/Automattic/simplenote-electron/releases/tag/v1.1.7) (2018-08-17)

Bug and security fixes.

## [v1.1.6](https://github.com/Automattic/simplenote-electron/releases/tag/v1.1.6) (2018-06-22)

Bug and security fixes.

## [v1.1.5](https://github.com/Automattic/simplenote-electron/releases/tag/v1.1.5) (2018-06-15)

Fixes a blank screen issue that could occur at smaller resolutions.

## [v1.1.4](https://github.com/Automattic/simplenote-electron/releases/tag/v1.1.4) (2018-06-15)

- You can now sign in with a WordPress.com account.
- Bug and security fixes.

## [v1.1.3](https://github.com/Automattic/simplenote-electron/releases/tag/v1.1.3) (2018-02-09)

- To save on editor space, the markdown Edit/Preview toggle has been moved to the toolbar. Look for the 👁
- Safety first! The app checks for any unsynced notes before logging out and warns if it finds any.
- Security fixes.

## [v1.1.2](https://github.com/Automattic/simplenote-electron/releases/tag/v1.1.2) (2018-01-10)

- Fixes an issue where new accounts could not sign in to the web app.
- Security fixes.

## [v1.1.1](https://github.com/Automattic/simplenote-electron/releases/tag/v1.1.1) (2017-12-12)

- Improved support for Markdown tables.
- Fixes issue where tags could become duplicated.

## [v1.1.0](https://github.com/Automattic/simplenote-electron/releases/tag/v1.1.0) (2017-11-21)

- UI improvements.
- Search for multiple tags in the search bar (type `tag:nameoftag`).
- Performance and reliability fixes.

## [v1.1.0-rc3](https://github.com/Automattic/simplenote-electron/releases/tag/1.1.0-rc3) (2017-11-17)

Even more bug fixes from RC2, and now includes 'no notes' placeholder.

## [v1.0.8](https://github.com/Automattic/simplenote-electron/releases/tag/v1.0.8) (2017-02-01)

- Search improvements: Match highlighting and clear search button added.
- You can now export your notes from the file menu.
- Performance and reliability improvements.

## [v1.0.7](https://github.com/Automattic/simplenote-electron/releases/tag/v1.0.7) (2016-12-03)

- Sync reliability fixes. Note: If the app is still out of sync after updating, try signing out and back in again.
- New notes now always open in edit mode.
- Syntax highlighting added in the Markdown preview.

## [v1.0.6](https://github.com/Automattic/simplenote-electron/releases/tag/v1.0.6) (2016-11-03)

Fixes Page Up/Down keys from showing the info panel erroneously.

## [v1.0.5](https://github.com/Automattic/simplenote-electron/releases/tag/v1.0.5) (2016-10-20)

Bug fixes, including:

- Fixes search bug and refactors `filterNotes()` [@dmsnell](https://github.com/dmsnell).
- Replace value link in tag list for controlled state changes [@dmsnell](https://github.com/dmsnell).
- Fix access to wrong variable name [@nfcampos](https://github.com/nfcampos).


## [v1.0.4](https://github.com/Automattic/simplenote-electron/releases/tag/v1.0.4) (2016-10-12)

- Replaced textarea-based note editor with Draft.js [@nfcampos](https://github.com/nfcampos)
- Fix revision slider where it was loading the oldest version of a note by default
- Add menu mnemonics [@bostrt](https://github.com/bostrt)
- Remove global Markdown setting
- Additional minor bug fixes.
  - Fix word counter with non ASCII characters
  - Find note when `state.note` doesn't exist
  - Replace search RegExp with simple string search [@nfcampos](https://github.com/nfcampos)

## [v1.0.3](https://github.com/Automattic/simplenote-electron/releases/tag/v1.0.3) (2016-08-26)

- Larger title in the note editor.
- Fix for username not displaying in settings.
- Additional minor bug fixes.

## [v1.0.2](https://github.com/Automattic/simplenote-electron/releases/tag/v1.0.2) (2016-06-28)

Bug fixes.

## [v1.0.1](https://github.com/Automattic/simplenote-electron/releases/tag/v1.0.1) (2016-04-30)

- Add selection to markdown preview.
- Title attribute tooltips.
- Open link on external browser.
- Submit login form on `enter`.
- Better exception management.
- Design updates.


## [v1.0.0](https://github.com/Automattic/simplenote-electron/releases/tag/v1.0.0) (2016-03-30)

Simplenote Desktop

## [v1.0.0-rc.2](https://github.com/Automattic/simplenote-electron/releases/tag/v1.0.0-rc.2) (2016-03-30)

- Merge pull request #262 from Automattic/fix/simperium-npm-version
- Fixes the Simperium version

## [v1.0.0-rc.1](https://github.com/Automattic/simplenote-electron/releases/tag/v1.0.0-rc.1) (2016-03-26)

## [v1.0.0-rc.0](https://github.com/Automattic/simplenote-electron/releases/tag/v1.0.0-rc.0) (2016-03-23)

Last version without updates notifications.
