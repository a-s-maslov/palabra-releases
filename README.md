# Palabra

A desktop vocabulary companion for Windows. Illustrated word cards appear during your working day, with translations, examples and pronunciation.

## Install

1. Download **[Palabra-Setup.exe](https://github.com/a-s-maslov/palabra-releases/releases/latest/download/Palabra-Setup.exe)** from the latest application release.
2. On first launch, choose the vocabularies you want and click Install selected.
3. Click Start learning. You can adjust translations and review intervals afterwards.

The catalogue is always available in Vocabularies. Each vocabulary has adjacent Learning and Progress tabs in the same screen. Configure translations and review intervals there; display interval, working hours, auto-hide and pause are app-wide Settings. There are no daily card limits. Show cards enables or disables a vocabulary independently of its settings. Each installation or reinstallation opens the library with existing vocabularies and saved progress; downloading them again is not required.

No source checkout or developer tools are required. The installer checks for Microsoft WebView2 and installs it if necessary. The installer is currently unsigned.

## Optional language packages

[Language packages and offline downloads](https://github.com/a-s-maslov/palabra-releases/releases/tag/packages)

- German: 100 words / 100 cards, Russian and English translations, approximately 15 MB.
- Spanish: 1050 words / 1291 cards, Russian and English translations, approximately 226 MB.

All packages use the same `.palabra-pack` format. For offline import, choose Install from file in Vocabularies. Once installed, learning works offline. Fully offline application setup requires WebView2 to be available beforehand.

The interface supports English, Russian, Spanish and German. Any number of installed packages can be enabled; settings and learning progress are independent. Removing a package keeps its progress for reinstallation. Updating the application keeps your packages and progress.

Package sources and attribution are included in the files. German frequency selection uses DeReWo (CC BY-NC 3.0); German pronunciation includes adapted CC BY-SA data. No native-speaker expert review is claimed.

This repository contains release downloads and instructions. Application source code is maintained separately. macOS installers and automatic application updates are not part of this release.
