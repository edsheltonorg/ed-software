# Ed Software

A list of all the software I use.

Unless otherwise mentioned, tools listed are open source.

Key Chart:

```
[🔒] - Closed Source

[🪟] - Windows
[🐧] - Linux
[🍎] - MacOS

[🤖] - Android
[‍️🍏] - iOS

[🦊] - Firefox
[‍️👁️] - Chrome
```

## Categories

Split into Desktop and Mobile.

### [Desktop](#desktop-1)
  - [Development](#development)
  - [VSCode Extensions](#vscode-extensions)
  - [Network](#network)
  - [Media](#media)
  - [System Tools](#system-tools)
  - [Gaming](#gaming)

### [Mobile](#mobile-1)
  - [System Tools](#system-tools-1)
  - [Network Tools](#network-tools)
  - [User Tools](#user-tools)
  - [Media](#media-1)
  - [Media Tools](#media-tools)
  - [Productivity](#productivity-1)
  - [Gaming](#gaming-1)

# Desktop

## Development

### Text Editors

- 🪟🐧🍎🔒
[**VSCode**](https://code.visualstudio.com/download) -
GUI text editor.

- 🪟🐧🍎
[**nvim**](https://github.com/neovim/neovim/releases) -
Terminal text editor.

### IDEs

- 🪟🐧🍎
[**Intellij Idea**](https://www.jetbrains.com/idea/download/) -
Excellent IDE, especially for JVM & Android dev.

- 🪟🔒
[**Visual Studio Community**](https://visualstudio.microsoft.com/vs/compare/) -
Building native windows programs.

### Code Management

- 🪟🐧🍎
[**git**](https://git-scm.com/downloads) -
Popular version control software.

- 🪟🐧🍎
[**dploy**](https://github.com/arecarn/dploy) -
Config file symlink management.

### Database Clients

- 🪟🐧🍎
[**usql**](https://github.com/xo/usql/releases) -
CLI SQL and NoSQL client.

- 🪟🐧🍎
[**DBeaver**](https://github.com/dbeaver/dbeaver/releases) -
GUI SQL client and visualizer.

### Compilers and Interpreters

- 🪟🐧🍎
**OpenJDK / [Adoptium](https://adoptopenjdk.net/releases.html)**
Java.

- 🪟🐧🍎
[**Python 3**](https://www.python.org/downloads/) -
Python.

- 🪟🐧🍎
[**Miniconda**](https://docs.conda.io/en/latest/miniconda.html) -
Popular Python env and package management system.

- 🪟🐧🍎
[**Node.js**](https://nodejs.org/en/download/) -
Javascript.

- 🪟🐧🍎
[**Go**](https://go.dev/dl/) -
Go.

- 🪟🐧🍎
[**Rust**](https://www.rust-lang.org/tools/install) -
Rust.

- 🪟🐧🍎
[**PHP**](https://windows.php.net/download/) -
PHP.

- 🪟🐧🍎
**[.NET Core](https://dotnet.microsoft.com/download/dotnet) & [Powershell](https://github.com/PowerShell/Powershell)**
.NET and Powershell.

- 🪟🐧🍎
[**Texlive / MacTeX**](https://www.tug.org/texlive/acquire-iso.html) -
Fully featured LaTeX installation.

- 🪟🐧🍎
**gcc + mingw-gcc**
GNU C & C++ w/ Windows cross-compiler.

- 🪟
[**Msys2**](https://www.msys2.org/) -
Mingw64 package manager.


### Game Development

- 🪟🐧🍎
[**Godot**](https://godotengine.org/download) -
2d & 3d game engine w/ many language bindings.

- 🪟🐧🍎
[**Blender**](https://www.blender.org/download/) -
Great for nearly everything 3d, extremely versatile.

### Web Tools

- 🪟🐧🍎
[**curl**](https://curl.se/download.html) -
Tool used for testing REST and other protocols.

- 🪟🐧🍎
[**HTTP Toolkit**](https://github.com/httptoolkit/httptoolkit-desktop/releases) -
REST analysis tool.

- 🪟🐧🍎
[**Insomnia**](https://insomnia.rest/download) -
REST creation, mapping, and testing tools.

### Virtualization

- 🪟🐧🍎
[**Vagrant**](https://www.vagrantup.com/downloads) -
Fast VM instantiation platform for testing.

- 🪟🐧🍎
[**VirtualBox**](https://www.virtualbox.org/wiki/Downloads) -
Most common VM host for Vagrant.

- 🐧
[**Docker**](https://dev.to/bowmanjd/install-docker-on-windows-wsl-without-docker-desktop-34m9)
Modern container platform.

- 🪟🐧🍎
[**GNS3**](https://github.com/GNS3/gns3-gui/releases) -
Network virtualization and testing tool.

### Fonts

- [**JetBrains Mono**](https://github.com/JetBrains/JetBrainsMono) -
Sharp & wide, meaning normal width and more lines when zoomed out.

- [**Iosevka SS14**](https://github.com/be5invis/Iosevka/blob/v21.0.0/doc/PACKAGE-LIST.md) -
Narrow yet legible and JetBrains Mono inspired. Alt monospace.

## VSCode Extensions

### Development Tools

- 🔒 [**Remote Development**](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack) -
Extremely useful remote development tools for WSL, SSH, and Containers.

- [**GitLens**](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) -
Extra Git tools for VSCode, nice to have.

- [**SFTP**](https://marketplace.visualstudio.com/items?itemName=Natizyskunk.sftp) -
Well featured FTP/SFTP editing / syncing / exploring tool.

### Web Tools

- [**Live Server**](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) -
Live reloading webpages w/ support for dynamic languages.

- [**Live Preview**](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server) -
Fairly basic built-in web server w/ live reloading.

- [**REST Client**](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) -
Quick REST method testing tool.

- [**Markdown PDF**](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf) -
Export Markdown to PDF/HTML/Image w/ customizations.

- [**Color Manager**](https://marketplace.visualstudio.com/items?itemName=RoyAction.color-manager) -
Integrated color picker and palette management tool.

### Media Viewers

- [**Hex Editor**](https://marketplace.visualstudio.com/items?itemName=ms-vscode.hexeditor) -
Easy to use Hex Editor.

- [**Draw.io Integration**](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio) -
Editor for diagrams.net files.

- [**Data Preview**](https://marketplace.visualstudio.com/items?itemName=RandomFractalsInc.vscode-data-preview) -
Visualization tool for structured data.

- [**Excel Viewer**](https://marketplace.visualstudio.com/items?itemName=GrapeCity.gc-excelviewer) -
Excel and CSV table visualization tool.

- [**LaTeX Workshop**](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) -
PDF Viewer + Watcher & *TeX tools. If no need for *TeX, use [vscode-pdf](https://marketplace.visualstudio.com/items?itemName=tomoki1207.pdf).

### Code Management

- [**Project Manager**](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager) -
Efficiently add and manage projects.

- [**Partial Diff**](https://marketplace.visualstudio.com/items?itemName=ryu1kn.partial-diff) -
Allows custom selection diffs.

- [**gitignore**](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore) -
Quickly append official gitignore templates to project.

- [**Peacock**](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock) -
Workspace theme engine for easier context switching.

### Formatting Tools

- [**Easy Snippet**](https://marketplace.visualstudio.com/items?itemName=inu1255.easy-snippet) -
Efficiently manage & logically edit language snippets.

- [**Code Spell Checker**](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) -
Unobtrusive spell checker.

- [**Rewrap**](https://marketplace.visualstudio.com/items?itemName=stkb.rewrap) -
Hard wrapping & unwrapping tool.

- [**Better Align**](https://marketplace.visualstudio.com/items?itemName=Chouzz.vscode-better-align) -
Operator and comment alignment tool.

- [**Paste Image**](https://marketplace.visualstudio.com/items?itemName=mushan.vscode-paste-image) -
Makes pasting images to markup formats very easy.

- [**:emojisense:**](https://marketplace.visualstudio.com/items?itemName=bierner.emojisense) -
Insert emojis quickly.

- [**Path Intellisense**](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) -
Makes path completion faster.

### Editor Personalization

- [**Vim**](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim) -
Native Vim binds.

- [**Material Icon Theme**](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) -
More legible icon theme.

- [**Word Count**](https://marketplace.visualstudio.com/items?itemName=ms-vscode.wordcount) -
Counts words in markdown files.

- [**filesize**](https://marketplace.visualstudio.com/items?itemName=mkxml.vscode-filesize) -
Shows file information, including size, gzip size, and time of creation.

- [**Rainbow CSV**](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv) -
Provides clarity to CSV files and filtering/sorting tools.

- [**Color Highlight**](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) -
Global Hex and RGBA color preview.

- [**indent-rainbow**](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow) -
Preferred over the native indention highlighter.

- [**Error Lens**](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens) -
Inline error codes.

- [**Better Comments**](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) -
Applies custom highlighting to different types of comments.

- [**Todo Tree**](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree) -
Keeps track of todo comments in code.


## Network

### Browsers

- 🪟🐧🍎
[**Firefox**](https://www.mozilla.org/en-US/firefox/all/) -
Favorite browser, tag based bookmarking.

- 🪟🐧🍎
**Chromium / Edge 🔒 / Brave**
Blink browsers (for testing).

### Browser Extensions

- 🦊👁️‍
[**uBlock Origin**](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) -
Block URLs and user-defined JS, CSS, and HTML from loading.

- 🦊👁️‍
[**Dark Reader**](https://addons.mozilla.org/en-US/firefox/addon/darkreader/) -
Globally injected dark theme.

- 🦊
[**Limit Tabs**](https://addons.mozilla.org/en-US/firefox/addon/rudolf-fernandes/) -
Blocks tabs after user-set max is reached.

- 🦊👁️‍
[**LeechBlock NG**](https://addons.mozilla.org/en-US/firefox/addon/leechblock-ng/) -
Customizable site blacklist and time-gate software.

- 🦊👁️‍
[**Video Speed Controller**](https://addons.mozilla.org/en-US/firefox/addon/videospeed/) -
Control video playback speed.

- 🦊👁️‍
[**Highlight or Hide Search Engine Results**](https://addons.mozilla.org/en-US/firefox/addon/hohser/) -
Block domains from search results.

- 🦊👁️‍
[**Channel Blocker**](https://addons.mozilla.org/en-US/firefox/addon/youtube-cleaner/) -
Block channels from recommendations.

- 🦊👁️‍
[**Vimium-FF / Vimium**](https://addons.mozilla.org/en-US/firefox/addon/vimium-ff/) -
Vi binds for webpage navigation.

- 🦊👁️‍
**[Wayback Machine](https://addons.mozilla.org/en-US/firefox/addon/wayback-machine_new/) & [Archive Page](https://addons.mozilla.org/en-US/firefox/addon/archive-page/)**
Archive web pages with a button.

- 🦊👁️‍
[**User-Agent Switcher**](https://addons.mozilla.org/en-US/firefox/addon/uaswitcher/) -
Faster user agent changing.

- 🦊👁️‍
[**Decentraleyes**](https://addons.mozilla.org/en-US/firefox/addon/decentraleyes/) -
Stubs CDN calls, reduces spying surface.

- 🦊👁️‍
[**Old Reddit Redirect**](https://addons.mozilla.org/en-US/firefox/addon/old-reddit-redirect/) -
Redirects to old format reddit.

- 🦊👁️‍
[**ClearURLs**](https://addons.mozilla.org/en-US/firefox/addon/clearurls/) -
Removes trackers and PII from URLs automatically.

- 🦊👁️‍
[**Fast Forward**](https://addons.mozilla.org/en-US/firefox/addon/fastforwardteam/) -
Skips link shortening services.

- 🦊
[**cookies.txt**](https://addons.mozilla.org/en-US/firefox/addon/cookies-txt/) -
Exports cookies for other tools.

- 🦊👁️‍
[**Search by Image**](https://addons.mozilla.org/en-US/firefox/addon/search_by_image/) -
Reverse image search anything quickly.

- 🦊👁️‍
[**Center Pages**](https://addons.mozilla.org/en-US/firefox/addon/center-pages/) -
Condense HTML pages if too wide.

- 🦊👁️‍
[**SponsorBlock**](https://addons.mozilla.org/en-US/firefox/addon/sponsorblock/?src=external-website) -
Crowdsourced video annotation and skipping.

- 🦊👁️‍
[**Bypass Paywalls Clean**](https://addons.mozilla.org/en-US/firefox/addon/bypass-paywalls-clean/) -
Skips paywalls from articles.

### Communication

- 🪟🐧🍎
[**Thunderbird**](https://www.thunderbird.net/en-US/thunderbird/all/#E) -
Email and calendar client.

- 🪟🐧🍎🔒
[**Discord**](https://discord.com/download) -
Current popular chat platform.

- 🪟🐧🍎
[**Element**](https://element.io/download) -
Federated self-hostable discord alternative.

### VPN
- 🪟🐧🍎
[**OpenVPN**](https://openvpn.net/community-downloads/) -
OpenVPN client and server.

- 🪟🐧🍎
[**WireGuard**](https://www.wireguard.com/install/) -
WireGuard client and server.

- 🪟🐧🍎
[**SoftEther**](https://github.com/SoftEtherVPN/SoftEtherVPN/) -
Client and server for SSTP, IPSec, WireGuard, and OpenVPN.

- 🪟🐧🍎
[**OpenConnect**](https://www.infradead.org/openconnect/packages.html) -
Client and server for AnyConnect.

### File Downloading

- 🪟🐧🍎
[**wget**](https://eternallybored.org/misc/wget/) -
Download websites.

- 🪟🐧🍎
[**aria2**](https://github.com/aria2/aria2) -
Sophisticated threaded downloading tool.

- 🪟🐧🍎
[**yt-dlp**](https://github.com/yt-dlp/yt-dlp) -
Download video and audio from most websites.

- 🪟🐧🍎
[**rclone**](https://github.com/rclone/rclone/releases) -
Mount & sync shares from many cloud vendors.

- 🪟
[**winfsp**](https://github.com/billziss-gh/winfsp) -
Tool needed for rclone to work on windows.

- 🪟
[**winscp**](https://winscp.net/eng/download.php) -
GUI client for SFTP, S3, WebDAV, and more.

- 🪟🐧🍎
[**qbittorrent**](https://www.qbittorrent.org/download.php) -
Torrent client and search engine.


### Analysis

- 🪟🐧🍎
[**nmap/Zenmap**](https://nmap.org/download.html) -
Network analysis.

- 🪟🐧🍎
[**Wireshark**](https://www.wireshark.org/download.html) -
Packet analysis.

## Media

### Documents

- 🪟🐧🍎
[**LibreOffice**](https://www.libreoffice.org/download/download/) -
Microsoft Office viewer & editor.

- 🪟🐧
[**Okular**](https://okular.kde.org/download/) -
PDF and eBook reader.

- 🪟🐧🍎
[**Koodo**](https://github.com/troyeguo/koodo-reader) -
Modern ebook desktop app.

- 🪟🐧🍎
[**pandoc**](https://pandoc.org/installing.html) -
Text media conversion tool.

- 🪟🐧🍎
[**Tesseract**](https://github.com/UB-Mannheim/tesseract/wiki) -
Text OCR tool.

- 🪟🐧🍎
[**pdftk-java**](https://gitlab.com/pdftk-java/pdftk) -
PDF transformation tool (Rewrite of [**pdftk**](https://www.pdflabs.com/tools/pdftk-server/)).

- 🪟🐧🍎
[**Xournalpp**](https://github.com/xournalpp/xournalpp/releases) -
Drawing pad note-taking platform

### Images

- 🪟🐧🍎
[**Krita**](https://krita.org/en/download/krita-desktop/) -
Full fledged editing and drawing software.

- 🪟🐧🍎
[**DarkTable**](https://www.darktable.org/install/) -
Raw & batch processing photography.

- 🪟🐧🍎
[**Ksnip**](https://github.com/ksnip/ksnip/releases) -
Advanced screenshot tool.

- 🪟🐧🍎
[**Inkscape**](https://inkscape.org/release/) -
Full vector editing suite.

- 🪟🐧🍎
[**ImageMagick**](https://imagemagick.org/script/download.php) -
CLI tool for automated editing.

- 🪟🐧🍎
[**exiftool**](https://exiftool.org/) -
Remove or edit EXIF data.

### Audio

- 🪟🐧🍎
[**Ardour**](https://community.ardour.org/download) -
Fully featured DAW.

- 🪟🐧🍎
[**Audacity**](https://www.audacityteam.org/download/) -
GUI Audio editing software.

- 🪟🐧🍎
[**Mixxx**](https://mixxx.org/download/#stable) -
DJ mixing software and audio analysis tool.

- 🪟🐧🍎
[**Quod Libet**](https://quodlibet.readthedocs.io/en/latest/downloads.html) -
Dedicated audio library and player.

- 🪟🐧🍎
[**MusicBrainz Picard**](https://picard.musicbrainz.org/downloads/) -
Automated music meta tagging software.

- 🪟
**[Equalizer APO](https://sourceforge.net/projects/equalizerapo/) & [Peace Equalizer](https://sourceforge.net/projects/peace-equalizer-apo-extension/)**
System-wide VST applier for audio IO.

### Video

- **🪟
[MPV.NET](https://github.com/stax76/mpv.net/releases) /
🐧🍎
[MPV](https://mpv.io/installation/)** -
Fast and customizable media player.

- 🪟🐧🍎
[**VLC**](https://www.videolan.org/vlc/#download) -
Fully featured media player.

- 🪟🐧🍎
[**OBS**](https://obsproject.com/download) -
Allows livestreaming, easy screen recording, and overlays.

- 🪟🐧🍎
[**ffmpeg**](https://ffmpeg.org/download.html) -
Fully featured CLI media conversion tool and editor.

- 🪟🐧🍎
[**Kdenlive**](https://kdenlive.org/en/download/) -
GUI video editing software.

### Video Server

- 🪟🐧🍎
[**Jellyfin**](https://jellyfin.org/downloads/) -
Media server.

## System Tools

### Backups

- 🪟🐧🍎🔒
[**Veeam Agent**](https://www.veeam.com/virtual-server-management-one-free.html) -
Block and file level backup + replication tool.

- 🪟🐧🍎
[**Restic**](https://github.com/restic/restic) -
File level backup tool.

- 🪟🐧🍎
[**TestDisk & PhotoRec**](https://www.cgsecurity.org/wiki/TestDisk_Download) -
Partition and File recovery tool.

### File Management

- 🪟🐧🍎
[**7-Zip**](https://www.7-zip.org/download.html) -
Full featured archive manager, easy encryption.

- 🪟
[**wincdemu**](https://wincdemu.sysprogs.org/download/) -
Virtual disk mounter.

- 🐧🍎
[**rsync**](https://linux.die.net/man/1/rsync) -
Fully featured copying tool.

- **🪟
[WinDirStat](https://windirstat.net/download.html) /
🐧
[QDirStat](https://github.com/shundhammer/qdirstat/releases/) /
🍎
[GrandPerspective](https://grandperspectiv.sourceforge.net/)**
GUI storage analysis.

- 🪟🐧🍎
[**dua**](https://github.com/Byron/dua-cli) -
CLI storage analysis.

- 🪟🐧🍎
[**DupeGuru**](https://github.com/arsenetar/dupeguru/releases) -
Duplicate file finder.

### Security

- 🪟🐧🍎
[**Bitwarden**](https://bitwarden.com/) -
Multi-user synced secrets.

- 🦊👁️‍
[**Bitwarden-Browser**](https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager/) -
Browser plugin for Bitwarden.

- 🪟🐧🍎
[**Veracrypt**](https://www.veracrypt.fr/en/Downloads.html) -
Portable encrypted volumes.

- 🪟
[**Gpg4win**](https://gpg4win.org/download.html) -
PGP keychain and tools.

### Installation Media

- 🪟🐧
[**Ventoy**](https://github.com/ventoy/Ventoy/releases) -
Multiboot USB tool.

### Automation

- **🪟
[AHK](https://autohotkey.com/download/) /
🐧
[sxhkd](https://github.com/baskerville/sxhkd) /
🍎
[karabiner](https://github.com/pqrs-org/Karabiner-Elements/releases)**
Rebind and map keyboard(s).

### Productivity

- 🪟🐧
[**Qalculate**](https://github.com/Qalculate/qalculate-gtk/releases) -
Full featured calculator.

- 🪟🐧🍎
[**Anki**](https://apps.ankiweb.net/) -
SRS and flashcard tool.

### Input

- 🪟🐧🍎
[**KDE Connect**](https://kdeconnect.kde.org/download.html) -
Desktop <-> Smartphone input and notifications.

- 🪟🐧🍎
[**Barrier**](https://github.com/debauchee/barrier/releases) -
Cross-platform keyboard and mouse KVM software.

### Window Management

- 🍎
[**Rectangle**](https://github.com/rxhanson/Rectangle/releases) -
Sane window management keybind program.

### Runtimes

- 🪟🔒
[**.NET 3.5**](https://www.microsoft.com/en-us/download/details.aspx?id=25150) -
Older .NET Framework that old software depends on.

- 🪟🔒
[**DirectX**](https://www.microsoft.com/en-us/download/details.aspx?id=35) -
DirectX 9 and above. Dependency for many games.

- 🪟🔒
Microsoft Visual C Runtimes:
    - [**MSVC Redist 2015-2022**](https://learn.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170)
    - [**MSVC Redist 2013**](https://support.microsoft.com/en-us/topic/update-for-visual-c-2013-redistributable-package-d8ccd6a5-4e26-c290-517b-8da6cfdf4f10)
    - [**MSVC Redist 2012**](https://www.microsoft.com/en-us/download/details.aspx?id=30679)
    - [**MSVC Redist 2010**](https://www.microsoft.com/en-us/download/details.aspx?id=26999)
    - [**MSVC Redist 2008**](https://www.microsoft.com/en-us/download/details.aspx?id=26368)
    - [**MSVC Redist 2005**](https://www.microsoft.com/en-us/download/details.aspx?id=26347)

### Debug

- 🪟🔒
[**Windows SDK**](https://developer.microsoft.com/en-us/windows/downloads/windows-sdk/) -
Lots of important debug and development tools.

- 🪟🐧🍎
[**adb**](https://developer.android.com/studio/releases/platform-tools) -
Interface and automate android.

### Services

- 🪟
[**NSSM**](https://nssm.cc/download) -
Create services from binaries and scripts.

## Gaming

### Peripherals

- 🪟
[**DS4Windows**](https://github.com/Ryochan7/DS4Windows/releases) -
Allows PS4 to be functional on non-supporting platforms.

### Emulation

- 🪟🐧🍎
[**Retroarch**](https://retroarch.com/?page=platforms) -
Emulator platform.

- 🪟🐧🍎
[**Dolphin**](https://dolphin-emu.org/download/) -
More recent engine for playing GCN / WII + online.

### Native Games

- 🪟🐧🍎
[**Nullpomino**](https://github.com/nullpomino/nullpomino/releases) -
All sorts of falling block games and styles.

# Mobile

## System Tools

- 🤖
[**F-Droid**](https://f-droid.org/en/) -
FOSS app store.

- 🤖
[**Termux**](https://f-droid.org/en/packages/com.termux/) -
Android terminal for phone w/ package manager.

- 🤖
[**Ghost Commander**](https://f-droid.org/en/packages/com.ghostsq.commander/) -
File explorer w/ network mounting ability.

- 🤖🍏
[**Bitwarden**](https://play.google.com/store/apps/details?id=com.x8bit.bitwarden&hl=en_US&gl=US) -
Browser plugin for Bitwarden.

- TOTP -
Anything will do.

- 🤖
[**Easer**](https://f-droid.org/en/packages/ryey.easer/) -
Event based automation platform.

## Network Tools

- 🤖
[**PCAPdroid**](https://f-droid.org/en/packages/com.emanuelef.remote_capture/) -
PCAP capture for device.

- 🤖
[**Ning**](https://f-droid.org/en/packages/de.csicar.ning/) -
Layer 2-4 discovery tool.

- 🤖
[**LibreTorrent**](https://f-droid.org/en/packages/org.proninyaroslav.libretorrent/) -
Torrent client.

- 🤖
[**DNS66**](https://f-droid.org/en/packages/org.jak_linux.dns66/) -
Quick adblocking DNS.

- 🤖🍏
[**OpenVPN**](https://f-droid.org/en/packages/de.blinkt.openvpn/) -
OpenVPN client.

- 🤖🍏
[**WireGuard**](https://f-droid.org/en/packages/com.wireguard.android/) -
WireGuard client.

- 🤖
[**WiFiAnalyzer**](https://f-droid.org/en/packages/com.vrem.wifianalyzer/) -
WiFi analysis tool.

- 🤖
[**FTPClient**](https://f-droid.org/en/packages/de.qwerty287.ftpclient/) -
FTP client.

- 🤖
[**primitive ftpd**](https://f-droid.org/en/packages/org.primftpd/) -
FTP/SFTP server.

## User Tools

- 🤖
[**BetterCounter**](https://f-droid.org/en/packages/org.kde.bettercounter/) -
Counter app.

- 🤖
[**Calculator-inator**](https://f-droid.org/en/packages/com.inator.calculator/) -
Full calculator

- 🤖
[**Audio Recorder**](https://f-droid.org/en/packages/com.github.axet.audiorecorder/) -
Record audio.

- 🤖
[**omWeather**](https://f-droid.org/en/packages/org.woheller69.omweather/) -
Weather application

- 🤖
[**Compass**](https://f-droid.org/en/packages/com.bobek.compass/) -
Compass application.

- 🤖
[**Markor**](https://f-droid.org/en/packages/net.gsantner.markor/) -
Basic text editor.

- 🤖
[**Acode**](https://f-droid.org/en/packages/com.foxdebug.acode/) -
Programming focused text editor.

- 🤖
[**Simple Draw Pro**](https://f-droid.org/en/packages/com.simplemobiletools.draw.pro/) -
Basic drawing program.

- 🤖
[**Open Note Scanner**](https://f-droid.org/en/packages/com.todobom.opennotescanner/) -
Document scanning & PDF appending tool.

- 🤖
[**Semitone**](https://f-droid.org/en/packages/mn.tck.semitone/) -
Tuner, keyboard, and metronome.

## Media

- 🤖
[**Metro**](https://f-droid.org/en/packages/io.github.muntashirakon.Music/) -
Music player.

- 🤖
[**NewPipe**](https://f-droid.org/en/packages/org.schabi.newpipe/) -
Youtube frontend, download videos as well.

- 🤖🍏🔒
[**Audible**](https://play.google.com/store/apps/details?id=com.audible.application&hl=en_US&gl=US) -
Amazon's audiobook store.

- 🤖
[**Voice**](https://f-droid.org/en/packages/de.ph1b.audiobook/) -
Audiobook player.

- 🤖🍏
[**VLC**](https://f-droid.org/en/packages/org.videolan.vlc/) -
Fully featured media player.

- 🤖
[**Slide**](https://f-droid.org/en/packages/me.ccrama.redditslide/) -
Reddit frontend.

- 🤖
[**AntennaPod**](https://f-droid.org/en/packages/de.danoeh.antennapod/) -
Podcast player & tracker.

- 🤖
[**Librera Reader**](https://f-droid.org/en/packages/com.foobnix.pro.pdf.reader/) -
eBook reader.

- 🤖
[**Spotube**](https://f-droid.org/en/packages/oss.krtirtho.spotube/) -
Spotify frontend.

## Media Tools

- 🤖
[**VES - Image and Photo Compare**](https://f-droid.org/en/packages/com.vincentengelsoftware.vesandroidimagecompare/) -
Photo comparison tool.

- 🤖🔒
[**Snapseed**](https://play.google.com/store/apps/details?id=com.niksoftware.snapseed&hl=en_US&gl=US) -
Photo editing tool, including RAW processing.

- 🤖
[**FFShare**](https://f-droid.org/en/packages/com.caydey.ffshare/) -
Video and audio conversion tool and compression tool using ffmpeg.

## Productivity

- 🤖
[**Track & Graph**](https://f-droid.org/en/packages/com.samco.trackandgraph/) -
Graphing tool.

- 🤖
[**Goodtime Productivity**](https://f-droid.org/en/packages/com.apps.adrcotfas.goodtime/) -
Pomodoro timer.

- 🤖
[**TimeR Machine**](https://f-droid.org/en/packages/io.github.deweyreed.timer.other/) -
Interval timer.

- 🤖🍏
[**AnkiDroid**](https://f-droid.org/en/packages/com.ichi2.anki/) -
SRS and flashcard tool.

## Gaming

- 🤖
[**Open Sudoku**](https://f-droid.org/en/packages/org.moire.opensudoku/) -
Sudoku.

- 🤖
[**Antimine**](https://f-droid.org/en/packages/dev.lucanlm.antimine/) -
Minesweeper.

- 🤖🍏
[**Retroarch**](https://play.google.com/store/apps/details?id=com.retroarch&hl=en_US&gl=US) -
Emulator platform.
