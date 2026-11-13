# Palabra

A desktop vocabulary companion for Windows. Illustrated word cards appear during your working day, with translations, examples and pronunciation.

## Install

1. Download **[Palabra-Setup.exe](https://github.com/a-s-maslov/palabra-releases/releases/latest/download/Palabra-Setup.exe)** from the latest application release.
2. On first launch, choose the vocabularies you want and click Install selected.
3. Click Start learning. Set translation languages in each vocabulary; set the shared working-set size in Settings.

The catalogue is always available in Vocabularies. Each vocabulary has adjacent Learning and Progress tabs in the same screen. Configure translations there; working-set size, display interval, working hours, auto-hide and pause are app-wide Settings. There are no daily card limits. Show cards enables or disables a vocabulary independently of its settings. Each manual installation or reinstallation opens the library with existing vocabularies and saved progress; downloading them again is not required.

No source checkout or developer tools are required. The installer checks for Microsoft WebView2 and installs it if necessary. The installer is currently unsigned.

## Optional language packages

[Language packages and offline downloads](https://github.com/a-s-maslov/palabra-releases/releases/tag/packages)

- German: 300 words / 300 cards, Russian and English translations, approximately 48 MB.
- Spanish: 1050 words / 1291 cards, Russian and English translations, approximately 226 MB.

All packages use the same `.palabra-pack` format. For offline import, choose Install from file in Vocabularies. Once installed, learning works offline. Fully offline application setup requires WebView2 to be available beforehand.

The interface supports English, Russian, Spanish and German. Any number of installed packages can be enabled; settings and learning progress are independent. Removing a package keeps its progress for reinstallation. Updating the application keeps your packages and progress.

Package sources and attribution are included in the files. German frequency selection uses DeReWo (CC BY-NC 3.0); German pronunciation includes adapted CC BY-SA data. No native-speaker expert review is claimed.

This repository contains release downloads and instructions. Application source code is maintained separately. macOS installers are not part of this release.

## Learning and application updates

The shared working set defaults to 10 cards across enabled vocabularies. New admissions alternate with random practice. A full set keeps practising until you explicitly mark a card known or exclude it. The set size and next turn persist across restarts; progress is retained for cards waiting outside the set. There are no future review dates.

Settings → Application → Check for updates → Update and restart. Availability is checked at startup and once a day; installation always requires a click. In-app downloads are verified with the updater signing key before installation. This is separate from Windows Authenticode signing. Application updates preserve vocabularies and progress and do not download new vocabulary versions. Install the current release manually once when upgrading from a version without the updater.
