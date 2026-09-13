# Lattice v0.3.22
**Released:** 2026-09-13 13:27 UTC

### Changes
  <!-- INSERT BULLETS UNDER THIS LINE -->
- FIX: Put the Microsoft Store URL on its own line
- FIX: Skip Android project init outright on windows-11-arm
- FIX: Don't abort winget bootstrap on a harmless VCLibs version conflict
- CHORE: install winget on windows arm to be equivelent
- FEAT: Build and test windows-arm-desktop natively on windows-11-arm
- FEAT: Added Windows ARM build
- CHORE: Extract MSIX packaging into shared script, build it in CI
- CHORE: bumped version to v0.3.22
## Download Lattice

**Windows users: install from the Microsoft Store**

<a href="https://get.microsoft.com/installer/download/9pm3gb09941t?referrer=appbadge" target="_self"><picture>   <source media="(prefers-color-scheme: dark)" srcset="https://get.microsoft.com/images/en-us%20light.svg">   <img src="https://get.microsoft.com/images/en-us%20dark.svg" width="200"     style="width:200px;max-width:100%;height:auto;display:inline-block" alt="Download Lattice from the Microsoft Store"/></picture></a>

<p>With a browser, just jump to:<br><a href="https://apps.microsoft.com/detail/9pm3gb09941t">https://apps.microsoft.com/detail/9pm3gb09941t</a></p>

Or download a package directly:

| File | Install on | Size |
|:-----|:-----------|-----:|
| [app-universal-release-unsigned.apk](https://github.com/blessia-blessini/lattice/releases/download/v0.3.22/app-universal-release-unsigned.apk) | <span class="material-icons">android</span> Android — Universal | 63.7 MB |
| [app-universal-release.aab](https://github.com/blessia-blessini/lattice/releases/download/v0.3.22/app-universal-release.aab) | <span class="material-icons">android</span> Android — Universal (Play Store) | 28.6 MB |
| [lattice_0.3.22_aarch64.dmg](https://github.com/blessia-blessini/lattice/releases/download/v0.3.22/lattice_0.3.22_aarch64.dmg) | <span class="material-icons">laptop_mac</span> macOS — Apple Silicon (ARM64) | 6.9 MB |
| [lattice_0.3.22_amd64.AppImage](https://github.com/blessia-blessini/lattice/releases/download/v0.3.22/lattice_0.3.22_amd64.AppImage) | <span class="material-icons">terminal</span> Linux — x86-64 (AppImage) | 79.0 MB |
| [lattice_0.3.22_amd64.deb](https://github.com/blessia-blessini/lattice/releases/download/v0.3.22/lattice_0.3.22_amd64.deb) | <span class="material-icons">terminal</span> Linux — x86-64 (Debian / Ubuntu) | 7.7 MB |
| [lattice_0.3.22_arm64-setup.exe](https://lattice-md.app/Lattice-Releases/assets-v0.3.22/bin-hex/lattice_0.3.22_arm64-setup.exe) |  <span class="material-icons">window</span> Windows — Intel / (ARM 64) | 4.8 MB |
| [lattice_0.3.22_x64-setup.exe](https://lattice-md.app/Lattice-Releases/assets-v0.3.22/bin-hex/lattice_0.3.22_x64-setup.exe) | <span class="material-icons">window</span> Windows — Intel / AMD (x86-64) | 5.1 MB |
| [lattice_0.3.22_x64.dmg](https://github.com/blessia-blessini/lattice/releases/download/v0.3.22/lattice_0.3.22_x64.dmg) | <span class="material-icons">laptop_mac</span> macOS — Intel (x86-64) | 7.0 MB |
| [SHA256SUMS.txt](https://lattice-md.app/Lattice-Releases/assets-v0.3.22/bin-hex/SHA256SUMS.txt) | <span class="material-icons">tag</span> Checksums (SHA-256) | 0.0 MB |

## Notes

- [Full release on GitHub](https://github.com/blessia-blessini/lattice/releases/tag/v0.3.22)
- DUAL LICENSE — for terms, see [README.md section Licensing](https://github.com/blessia-blessini/lattice#licensing).
- Lattice collects no personal data — see the [Privacy Statement](https://github.com/blessia-blessini/lattice/blob/dev/PRIVACY.md).

## Test Coverage

- [BACKEND](https://lattice-md.app/Lattice-Releases/assets-v0.3.22/coverage/src-tauri/target/llvm-cov/html/)
- [FRONTEND](https://lattice-md.app/Lattice-Releases/assets-v0.3.22/coverage/coverage/)

## Demo Document
A Markdown file — open directly in Lattice, read on GitHub, or view as HTML/PDF here.

### A document named `demo.md`



Here is a PDF that Lattice generated as a print-out.

Please scroll down to see how Lattice looks on Windows.

<iframe src="pdf-viewer.html?file=https%3A%2F%2Fraw.githubusercontent.com%2Fblessia-blessini%2Flattice-docs-releases%2Fmain%2FLattice-Releases%2Fassets-v0.3.22%2Fdocs%2Fdemo%2Fdemo.md.pdf" width="100%" style="border:none;border-radius:4px;margin:12px 0;display:block;min-height:70vh"></iframe>

- Download [Lattice-generated PDF](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.22/docs/demo/demo.md.pdf)
- Only for reference, as [rendered by GitHub](https://github.com/blessia-blessini/lattice-docs-releases/blob/main/Lattice-Releases/assets-v0.3.22/docs/demo/demo.md)
- The plaintext that you would actually edit: [Raw .md](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.22/docs/demo/demo.md)

![Lattice demo screenshot](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.22/docs/demo/demo_assets/img_1780574419628.png)

![Lattice demo screenshot](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.22/docs/demo/demo_assets/img_1780575215039.png)

![Lattice demo screenshot](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.22/docs/demo/demo_assets/img_d1780574419628.png)

![Lattice demo screenshot](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.22/docs/demo/demo_assets/img_da1780574419628.png)
