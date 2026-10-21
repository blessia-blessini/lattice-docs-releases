# Lattice v0.3.38
**Released:** 2026-10-21 22:49 UTC
### Changes
- FIX: Address the four nits of the APPROVED FU-1 review cycle 2
- FIX: Account for every file in the Linux AppImage, its runtime and AppRun included
- FIX: Show the source URL template and survive unknown packages in the AppImage gate
- FIX: Carry every copyright file and licence text inside the Linux AppImage
- FEAT: Review and gate the system libraries inside the Linux AppImage
- FIX: Keep the GPL-only TIFF image path out of the Linux AppImage
- TEST: Check the github-markdown-css version in the export notices too
- DOCS: List the notices check in the CLI export check table
- TEST: Catch asset imports without a query in the export cross-check
- DOCS: Trace the cycle-1 test additions for the export notices
- FIX: Act on review cycle 1 of the export notices
- FIX: Carry the third-party notices inside exported HTML documents
- DOCS: Add a contributor licence agreement and contribution guide
- DOCS: Restate Lattice's licensing as a coherent dual licence
- FIX: updated 3rd party notices with new KaTeX version
- FIX: updated 3rd party notices
- FEAT: Add FOSS licence gate and generated third-party notices
## Download Lattice

**Windows users: install from the Microsoft Store**

<a href="https://get.microsoft.com/installer/download/9pm3gb09941t?referrer=appbadge" target="_self"><picture>   <source media="(prefers-color-scheme: dark)" srcset="https://get.microsoft.com/images/en-us%20light.svg">   <img src="https://get.microsoft.com/images/en-us%20dark.svg" width="200"     style="width:200px;max-width:100%;height:auto;display:inline-block" alt="Download Lattice from the Microsoft Store"/></picture></a>

<p>With a browser, just jump to:<br><a href="https://apps.microsoft.com/detail/9pm3gb09941t">https://apps.microsoft.com/detail/9pm3gb09941t</a></p>

Or download a package directly:

| File | Install on | Size |
|:-----|:-----------|-----:|
| [app-universal-release-unsigned.apk](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/app-universal-release-unsigned.apk) | <span class="material-icons">android</span> Android — Universal | 66.2 MB |
| [app-universal-release.aab](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/app-universal-release.aab) | <span class="material-icons">android</span> Android — Universal (Play Store) | 29.6 MB |
| [lattice-android.cdx.json](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/lattice-android.cdx.json) | <span class="material-icons">inventory_2</span> SBOM (CycloneDX) — android | 0.4 MB |
| [lattice-linux-arm64-appimage.cdx.json](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/lattice-linux-arm64-appimage.cdx.json) | <span class="material-icons">inventory_2</span> SBOM (CycloneDX) — linux-arm64-appimage | 0.1 MB |
| [lattice-linux-arm64.cdx.json](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/lattice-linux-arm64.cdx.json) | <span class="material-icons">inventory_2</span> SBOM (CycloneDX) — linux-arm64 | 0.4 MB |
| [lattice-linux-x64-appimage.cdx.json](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/lattice-linux-x64-appimage.cdx.json) | <span class="material-icons">inventory_2</span> SBOM (CycloneDX) — linux-x64-appimage | 0.1 MB |
| [lattice-linux-x64.cdx.json](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/lattice-linux-x64.cdx.json) | <span class="material-icons">inventory_2</span> SBOM (CycloneDX) — linux-x64 | 0.4 MB |
| [lattice-macos-arm64.cdx.json](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/lattice-macos-arm64.cdx.json) | <span class="material-icons">inventory_2</span> SBOM (CycloneDX) — macos-arm64 | 0.4 MB |
| [lattice-macos-x64.cdx.json](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/lattice-macos-x64.cdx.json) | <span class="material-icons">inventory_2</span> SBOM (CycloneDX) — macos-x64 | 0.4 MB |
| [lattice-md.msixbundle](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/lattice-md.msixbundle) | <span class="material-icons">window</span> Windows — Store bundle (.msixbundle, sideload) | 13.6 MB |
| [lattice-win-arm64.cdx.json](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/lattice-win-arm64.cdx.json) | <span class="material-icons">inventory_2</span> SBOM (CycloneDX) — win-arm64 | 0.4 MB |
| [lattice-win-x64.cdx.json](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/lattice-win-x64.cdx.json) | <span class="material-icons">inventory_2</span> SBOM (CycloneDX) — win-x64 | 0.4 MB |
| [lattice_0.3.37_aarch64.AppImage](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/lattice_0.3.37_aarch64.AppImage) | <span class="material-icons">terminal</span> Linux — ARM64 (AppImage) | 80.1 MB |
| [lattice_0.3.37_aarch64.dmg](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/lattice_0.3.37_aarch64.dmg) | <span class="material-icons">laptop_mac</span> macOS — Apple Silicon (ARM64) | 7.5 MB |
| [lattice_0.3.37_amd64.AppImage](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/lattice_0.3.37_amd64.AppImage) | <span class="material-icons">terminal</span> Linux — x86-64 (AppImage) | 82.0 MB |
| [lattice_0.3.37_amd64.deb](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/lattice_0.3.37_amd64.deb) | <span class="material-icons">terminal</span> Linux — x86-64 (Debian / Ubuntu) | 8.4 MB |
| [lattice_0.3.37_arm64-setup.exe](https://lattice-md.app/Lattice-Releases/assets-v0.3.38/bin-hex/lattice_0.3.37_arm64-setup.exe) | <span class="material-icons">window</span> Windows — ARM64 | 5.3 MB |
| [lattice_0.3.37_arm64.deb](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/lattice_0.3.37_arm64.deb) | <span class="material-icons">terminal</span> Linux — ARM64 (Debian / Ubuntu) | 8.4 MB |
| [lattice_0.3.37_x64-setup.exe](https://lattice-md.app/Lattice-Releases/assets-v0.3.38/bin-hex/lattice_0.3.37_x64-setup.exe) | <span class="material-icons">window</span> Windows — Intel / AMD (x86-64) | 5.7 MB |
| [lattice_0.3.37_x64.dmg](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/lattice_0.3.37_x64.dmg) | <span class="material-icons">laptop_mac</span> macOS — Intel (x86-64) | 7.7 MB |
| [SHA256SUMS.txt](https://lattice-md.app/Lattice-Releases/assets-v0.3.38/bin-hex/SHA256SUMS.txt) | <span class="material-icons">tag</span> Checksums (SHA-256) | 0.0 MB |
| [THIRD-PARTY-NOTICES.md](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/THIRD-PARTY-NOTICES.md) | <span class="material-icons">gavel</span> Third-party licences and copyrights | 0.8 MB |

## Notes

- [Full release on GitHub](https://github.com/blessia-blessini/lattice/releases/tag/v0.3.38)
- DUAL LICENSE — for terms, see [README.md section Licensing](https://github.com/blessia-blessini/lattice#licensing).
- Third-party components and their licences: [THIRD-PARTY-NOTICES.md](https://github.com/blessia-blessini/lattice/releases/download/v0.3.38/THIRD-PARTY-NOTICES.md).
- Lattice collects no personal data — see the [Privacy Statement](https://github.com/blessia-blessini/lattice/blob/dev/PRIVACY.md).

## Test Coverage

- [BACKEND](https://lattice-md.app/Lattice-Releases/assets-v0.3.38/coverage/src-tauri/target/llvm-cov/html/)
- [FRONTEND](https://lattice-md.app/Lattice-Releases/assets-v0.3.38/coverage/coverage/)

## Demo Document
A Markdown file — open directly in Lattice, read on GitHub, or view as HTML/PDF here.

### A document named `demo.md`



- Only for reference, as [rendered by GitHub](https://github.com/blessia-blessini/lattice-docs-releases/blob/main/Lattice-Releases/assets-v0.3.38/docs/demo/demo.md)
- The plaintext that you would actually edit: [Raw .md](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/demo.md)

### Lattice on each desktop

Each desktop build in this release started the app it built, opened `demo.md`
and took one screenshot of its main window — what you get on that platform.

#### <span class="material-icons">terminal</span> Linux — ARM64

![Lattice on linux-arm-desktop](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/screenshots/screenshot-linux-arm-desktop.png)

#### <span class="material-icons">terminal</span> Linux — x86-64

![Lattice on linux-desktop](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/screenshots/screenshot-linux-desktop.png)

#### <span class="material-icons">laptop_mac</span> macOS — Apple Silicon (ARM64)

![Lattice on macos-arm64](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/screenshots/screenshot-macos-arm64.png)

#### <span class="material-icons">laptop_mac</span> macOS — Intel (x86-64)

![Lattice on macos-intel](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/screenshots/screenshot-macos-intel.png)

#### <span class="material-icons">window</span> Windows — ARM64

![Lattice on windows-arm-desktop](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/screenshots/screenshot-windows-arm-desktop.png)

#### <span class="material-icons">window</span> Windows — Intel / AMD (x86-64)

![Lattice on windows-desktop](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/screenshots/screenshot-windows-desktop.png)

### Generated by Lattice itself

Each desktop build in this release exported `demo.md` on its own operating
system, through that platform's own WebView. Nothing below was produced by
hand or by a converter — it is the output of the same `--export-html` and
`--export-pdf` commands you can run yourself:

```sh
lattice --export-html demo.md
lattice --export-pdf demo.md                 # A4
lattice --export-pdf --paper a3 demo.md      # or: --paper letter
```

#### <span class="material-icons">terminal</span> Linux — ARM64

<iframe src="pdf-viewer.html?file=https%3A%2F%2Fraw.githubusercontent.com%2Fblessia-blessini%2Flattice-docs-releases%2Fmain%2FLattice-Releases%2Fassets-v0.3.38%2Fdocs%2Fdemo%2Fgenerated%2Fdemo-linux-arm-desktop.pdf" width="100%" style="border:none;border-radius:4px;margin:12px 0;display:block;min-height:70vh"></iframe>

- Download [Lattice-generated PDF, A4](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/generated/demo-linux-arm-desktop.pdf)
- Download [Lattice-generated PDF, A3](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/generated/demo-linux-arm-desktop.a3.pdf)
- Download [Lattice-generated PDF, US Letter](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/generated/demo-linux-arm-desktop.letter.pdf)
- Open the [Lattice-generated HTML](assets-v0.3.38/docs/demo/generated/demo-linux-arm-desktop.html)

#### <span class="material-icons">terminal</span> Linux — x86-64

<iframe src="pdf-viewer.html?file=https%3A%2F%2Fraw.githubusercontent.com%2Fblessia-blessini%2Flattice-docs-releases%2Fmain%2FLattice-Releases%2Fassets-v0.3.38%2Fdocs%2Fdemo%2Fgenerated%2Fdemo-linux-desktop.pdf" width="100%" style="border:none;border-radius:4px;margin:12px 0;display:block;min-height:70vh"></iframe>

- Download [Lattice-generated PDF, A4](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/generated/demo-linux-desktop.pdf)
- Download [Lattice-generated PDF, A3](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/generated/demo-linux-desktop.a3.pdf)
- Download [Lattice-generated PDF, US Letter](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/generated/demo-linux-desktop.letter.pdf)
- Open the [Lattice-generated HTML](assets-v0.3.38/docs/demo/generated/demo-linux-desktop.html)

#### <span class="material-icons">laptop_mac</span> macOS — Apple Silicon (ARM64)

<iframe src="pdf-viewer.html?file=https%3A%2F%2Fraw.githubusercontent.com%2Fblessia-blessini%2Flattice-docs-releases%2Fmain%2FLattice-Releases%2Fassets-v0.3.38%2Fdocs%2Fdemo%2Fgenerated%2Fdemo-macos-arm64.pdf" width="100%" style="border:none;border-radius:4px;margin:12px 0;display:block;min-height:70vh"></iframe>

- Download [Lattice-generated PDF, A4](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/generated/demo-macos-arm64.pdf)
- Download [Lattice-generated PDF, A3](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/generated/demo-macos-arm64.a3.pdf)
- Download [Lattice-generated PDF, US Letter](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/generated/demo-macos-arm64.letter.pdf)
- Open the [Lattice-generated HTML](assets-v0.3.38/docs/demo/generated/demo-macos-arm64.html)

#### <span class="material-icons">laptop_mac</span> macOS — Intel (x86-64)

<iframe src="pdf-viewer.html?file=https%3A%2F%2Fraw.githubusercontent.com%2Fblessia-blessini%2Flattice-docs-releases%2Fmain%2FLattice-Releases%2Fassets-v0.3.38%2Fdocs%2Fdemo%2Fgenerated%2Fdemo-macos-intel.pdf" width="100%" style="border:none;border-radius:4px;margin:12px 0;display:block;min-height:70vh"></iframe>

- Download [Lattice-generated PDF, A4](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/generated/demo-macos-intel.pdf)
- Download [Lattice-generated PDF, A3](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/generated/demo-macos-intel.a3.pdf)
- Download [Lattice-generated PDF, US Letter](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/generated/demo-macos-intel.letter.pdf)
- Open the [Lattice-generated HTML](assets-v0.3.38/docs/demo/generated/demo-macos-intel.html)

#### <span class="material-icons">window</span> Windows — ARM64

<iframe src="pdf-viewer.html?file=https%3A%2F%2Fraw.githubusercontent.com%2Fblessia-blessini%2Flattice-docs-releases%2Fmain%2FLattice-Releases%2Fassets-v0.3.38%2Fdocs%2Fdemo%2Fgenerated%2Fdemo-windows-arm-desktop.pdf" width="100%" style="border:none;border-radius:4px;margin:12px 0;display:block;min-height:70vh"></iframe>

- Download [Lattice-generated PDF, A4](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/generated/demo-windows-arm-desktop.pdf)
- Download [Lattice-generated PDF, A3](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/generated/demo-windows-arm-desktop.a3.pdf)
- Download [Lattice-generated PDF, US Letter](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/generated/demo-windows-arm-desktop.letter.pdf)
- Open the [Lattice-generated HTML](assets-v0.3.38/docs/demo/generated/demo-windows-arm-desktop.html)

#### <span class="material-icons">window</span> Windows — Intel / AMD (x86-64)

<iframe src="pdf-viewer.html?file=https%3A%2F%2Fraw.githubusercontent.com%2Fblessia-blessini%2Flattice-docs-releases%2Fmain%2FLattice-Releases%2Fassets-v0.3.38%2Fdocs%2Fdemo%2Fgenerated%2Fdemo-windows-desktop.pdf" width="100%" style="border:none;border-radius:4px;margin:12px 0;display:block;min-height:70vh"></iframe>

- Download [Lattice-generated PDF, A4](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/generated/demo-windows-desktop.pdf)
- Download [Lattice-generated PDF, A3](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/generated/demo-windows-desktop.a3.pdf)
- Download [Lattice-generated PDF, US Letter](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/generated/demo-windows-desktop.letter.pdf)
- Open the [Lattice-generated HTML](assets-v0.3.38/docs/demo/generated/demo-windows-desktop.html)


![Lattice demo screenshot](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/demo_assets/img_1780574419628.png)

![Lattice demo screenshot](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/demo_assets/img_1780575215039.png)

![Lattice demo screenshot](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/demo_assets/img_d1780574419628.png)

![Lattice demo screenshot](https://raw.githubusercontent.com/blessia-blessini/lattice-docs-releases/main/Lattice-Releases/assets-v0.3.38/docs/demo/demo_assets/img_da1780574419628.png)


