# Changelog

All notable changes to Rudrabha Mukherjee's Build Checklist are recorded here.
The release history is taken from the application's own "What has changed" screen.

Versions follow [Semantic Versioning](https://semver.org/).
This file uses [Keep a Changelog](https://keepachangelog.com/) section headings.

## [1.9.0] — 18 September 2026

### Changed

- The recovery question on the lock screen is now optional. You can choose to rely on your PIN alone for stronger security, or set a question as a safety net.

### Added

- Support for PIN-only locks, with the ability to add, change, or remove a recovery question at any time while locked.

## [1.8.0] — 18 September 2026

### Changed

- Editorial minimalism and typographic authority: updated the interface typography stack anchored by the clean Inter font family and tracked uppercase section headers.
- Refined monochrome precision palette: implemented a pure Obsidian Black (`#15171A`), crisp Pure White (`#FFFFFF`), and Dijon Yellow (`#F2C94C`) mark accent palette with verified WCAG contrast compliance across all themes.
- Streamlined stage cards, 1px crisp dividers, and tracked uppercase stage numbers for enhanced clarity across phones and widescreen displays.

## [1.7.0] — 18 September 2026

### Fixed

- The top bar layout now uses three robust columns so the full product name never collides with navigation buttons.
- The Saved mark has moved to a floating toast near the bottom of the screen, leaving the top bar clear.

### Added

- Single-stage view with clear Previous stage and Next stage navigation, keeping the complete stage overview in Progress.
- An explicit Save button on checklist screens for immediate peace of mind.
- A 5-step text size slider with live resizing from extra small to extra large.
- A "Forgot PIN?" recovery link on the lock screen that leads directly to your recovery question.
- Export your checklist to plain text (.txt) and Markdown (.md) with creation timestamps.
- Collapsible sections for the Word list and prompt groups to make scanning faster.
- In-app install guidance and home screen install banner.

## [1.6.0] — 17 September 2026

### Changed

- The bar at the top is much smaller, so you see more of your work straight away. The buttons you use most have moved to the bottom of the screen, where your thumb reaches them.
- Settings are grouped into tidier lists with small pictures beside each row, so they are quicker to scan.
- Small, quiet movement when screens and messages appear. If your device is set to reduce motion, nothing moves.

### Added

- The app now follows your phone's own light or dark setting, unless you pick one yourself in Settings.

## [1.5.1] — 17 September 2026

### Fixed

- Installing the app did not actually work in the last version. The part that keeps a copy on your device could not save its files, so the app could not be installed properly, could not open without the internet, and could not tell you when a new version was ready. It works now.

### Changed

- New icons, drawn to stay clear at the small size a phone actually shows them.
- The Updates screen now tells you plainly whether you have the newest version, when it last checked, and offers the new version when there is one.

## [1.5.0] — 17 September 2026

### Added

- Installable on your phone, tablet or computer.
- Works offline once installed.
- A newer-version banner appears with your consent before updating; your work is unaffected.
- A setting to check for updates, or to switch off the automatic check.

### Changed

- The page used to make no connection once open; it now asks the host whether a newer version exists unless you switch that off. The privacy notice explains.
- The Content-Security-Policy now allows this app's own worker, manifest and icons. connect-src is 'self' for same-origin worker caching only; your work is never sent to a third party.

## [1.4.0] — 16 September 2026

### Added

- The official pages: About, Licence, Privacy, Terms of use, Notices and this release history, each one readable on screen and saveable as a file.
- Settings, gathering the screen, the lock, your work and the official pages in one place.
- A way to move your work to another web address or another device, keeping it scrambled the whole way if your lock is on.
- You can now save this page itself, so your copy keeps working whatever happens to any website.

## [1.3.0] — 16 September 2026

### Removed

- The Undo button. It could not undo ticking or typing, so it said there was nothing to undo far more often than it helped.

### Changed

- Messages now clear themselves instead of staying on screen.
- The privacy wording now separates what this page does from what a website recorded when it served the page to you.

## [1.2.0] — 16 September 2026

### Added

- A lock: a PIN scrambles your checklist on this device, with a question of your own as the way back in.

### Fixed

- A tick on the stage you were standing on that could not be seen against the circle behind it.
- Long labels pushing the page sideways on small screens.

## [1.1.0] — 16 September 2026

### Fixed

- A file opened from somebody else can no longer carry hidden instructions of its own.
- The keyboard now stays inside a question box, and goes back to the button that opened it.

### Changed

- Consistent creator attribution and a version on every copy.

## [1.0.0] — 15 September 2026

### Added

- First release. Thirteen stages, every step worth ticking off, the words to give an AI, and a word list.
