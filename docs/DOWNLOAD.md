<!--
OWNER NOTE (hidden in the rendered page): the links below assume the public,
installers-only repository RuiYamasaki/synaptaxis-releases (docs/RELEASES_SETUP.md).
If you named it differently, replace that part of the three URLs. The file
names after /download/ never change from release to release, so the links
always serve the newest PUBLISHED (non-draft, non-pre-release) version.
The text between the release-notes markers is also copied into every
release's notes.
-->
# Download Synaptaxis

**Windows 10 or 11:**
[Synaptaxis-Setup.exe](https://github.com/RuiYamasaki/synaptaxis-releases/releases/latest/download/Synaptaxis-Setup.exe)

**Mac (macOS 14 or newer):**
[Synaptaxis-arm64.dmg](https://github.com/RuiYamasaki/synaptaxis-releases/releases/latest/download/Synaptaxis-arm64.dmg)
for Macs with Apple silicon (M1 or newer, which covers most Macs bought since 2021).
For an older Mac with an Intel processor, use
[Synaptaxis-x86_64.dmg](https://github.com/RuiYamasaki/synaptaxis-releases/releases/latest/download/Synaptaxis-x86_64.dmg).
To check which you have, open the Apple menu  > *About This Mac*:
**Chip: Apple M…** means Apple silicon, and **Processor: Intel** means Intel.

<!-- release-notes:start -->
## Installing on Windows

1. Download `Synaptaxis-Setup.exe` (the Windows link) and open it. If the browser asks, choose **Keep**.
2. If a blue box says **"Windows protected your PC"**, click **More info**, then **Run anyway**.
3. Click **Next**, then **Next**, then **Install**. No administrator password is needed.
4. Click **Finish**. Synaptaxis starts. Next time, open it from the Start menu or the desktop icon.
5. In Synaptaxis, click **Open a microscopy volume** and type or paste the path of your Leica `.lif` file.

## Installing on a Mac

1. Download the Mac `.dmg` (the Mac link for your kind of Mac) and open it.
2. Drag **Synaptaxis** onto the **Applications** folder in the window that opens.
3. Open **Applications** and double-click **Synaptaxis**. macOS says it "could not verify" the app. Click **Done**.
4. Open **System Settings > Privacy & Security**, scroll down, click **Open Anyway** next to Synaptaxis, enter your Mac password, and click **Open Anyway** again.
5. Synaptaxis opens. From now on, a double-click is enough.

Steps 3 and 4 are needed only once, and only because this version is not yet
signed with an Apple Developer ID. On macOS 14 (Sonoma) you can instead
Control-click the app and choose **Open**. Full details, including a Terminal
alternative, are in the Mac install guide (INSTALL_MAC.md) and in the "How to
open Synaptaxis" note inside the `.dmg`.
<!-- release-notes:end -->

Synaptaxis works offline. It does not upload your data anywhere.
