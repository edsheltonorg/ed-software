# Ed Software

A list of all the software I use.

Unless otherwise mentioned, tools listed are open source.

Key Chart:

```
[✨] - Always Installed

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
  - [Editor Extensions](#editor-extensions)
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

| Program                                   | Description |
| ----------------------------------------- | ----------- |
| 🪟🐧🍎🔒 [**VSCode**][vscode]           | GUI text editor. ✨ |
| 🪟🐧🍎 [**nvim**][nvim] / [**vim**][vim] | Terminal text editor. ✨ |

### IDEs

| Program                                    | Description |
| ------------------------------------------ | ----------- |
| 🪟🔒 [**Visual Studio Community**][vside] | Building native windows programs. ✨ |
| 🪟🐧🍎 [**IntelliJ IDEA**][intellij]      | Excellent IDE, especially for JVM & Android dev. ✨ |

### Code Management

| Program                    | Description |
| -------------------------- | ----------- |
| 🪟🐧🍎 [**git**][git]     | Popular version control software. ✨ |
| 🪟🐧🍎 [**dploy**][dploy] | Config file symlink management. |

### Database Tools

| Program                                      | Description |
| -------------------------------------------- | ----------- |
| 🪟🐧🍎 [**SQLite Tools**][sqlite-tools]     | SQLite. ✨ |
| 🪟🐧🍎 [**SQLite Browser**][sqlite-browser] | GUI SQLite editor. Can also use a VSCode [Editor][vsc-sqlite-ed] / [Viewer][vsc-sqlite-view]. |
| 🪟🐧🍎 [**DBeaver**][dbeaver]               | GUI extendable DB editor. Can also use a VSCode extendable [DB tool][vsc-sqlite-view]. ✨ |
| 🪟🔒 [**SSMS**][ssms]                       | GUI SQL Server editor. ✨ |
| 🪟🐧🍎 [**go-ycsb**][go-ycsb]               | SQL benchmarking tool w/ focus on NoSQL. |
| 🪟🍎 [**HammerDB**][hammerdb]               | TPC-C and TPC-H benchmarking for common SQL dbms. |

### Compilers and Interpreters

| Program                                    | Description |
| ------------------------------------------ | ----------- |
| 🪟🐧🍎 **OpenJDK / [Adoptium][Adoptium]** | Java. ✨ |
| 🪟🐧🍎 [**Python 3**][python3]            | Python. ✨ |
| 🪟🐧🍎 [**Miniconda**][miniconda]         | Python env and dependency management system. ✨ |
| 🪟🐧🍎 [**nvm**][nvm]                     | Node version manager. ✨ |
| 🪟🐧🍎 [**Node.js**][nodejs]              | Javascript. ✨ |
| 🪟🐧🍎 [**.NET Core**][netcore]           | .NET Core. ✨ |
| 🪟🐧🍎 [**Texlive / MacTeX**][texlive]    | Fully featured LaTeX installation. ✨ |
| 🪟🐧🍎 [**PowerShell**][powershell]       | PowerShell. |
| 🪟🐧🍎 [**Go**][go]                       | Go. |
| 🪟🐧🍎 [**Rust**][rust]                   | Rust. |
| 🪟🐧🍎 [**PHP**][php]                     | PHP. |
| 🪟🐧🍎 **gcc + mingw-gcc**                | GNU C & C++ with Windows cross-compiler. |
| 🪟 [**Msys2**][msys2]                      | Mingw64 package manager. |

### Game Development

| Program                         | Description |
| ------------------------------- | ----------- |
| 🪟🐧🍎 [**Godot**][godot]      | 2d & 3d game engine w/ many language bindings. |
| 🪟🐧🍎 [**Blender**][blender]  | Great for nearly everything 3d, extremely versatile. |

### Testing Tools

| Program                                                     | Description |
| ----------------------------------------------------------- | ----------- |
| 🪟🐧🍎 [**mkcert**][mkcert]                                | Simple local certs for development. ✨ |
| 🪟🐧🍎 [**Playwright**][playwright]                        | Browser automation E2E testing. ✨ |
| 🪟🐧🍎 [**curl**][curl]                                    | Tool used for testing REST and other protocols. |
| 🪟🐧🍎 [**HTTP Toolkit**][http-toolkit]                    | REST analysis tool. |
| 🪟🐧🍎 [**Insomnia**][insomnia]                            | REST creation, mapping, and testing tools. Alt VSCode [httpYac][vsc-httpyac]. |
| 🪟🐧🍎 [**JMeter**][jmeter]                                | Load testing & benchmarking. |
| 🪟🐧🍎 [**OWASP ZAP**][owasp-zap]                          | Web application security testing suite. |
| 🪟🐧🍎 [**Ghidra**][ghidra]                                | Software reverse engineering framework. |
| 🪟 [**POSH-acme**][posh-acme] / 🐧🍎 [**acme.sh**][acmesh] | ACME clients for certs. |

### Virtualization

| Program                                 | Description |
| --------------------------------------- | ----------- |
| 🪟🐧 [**VirtualBox**][vbox]            | Virtual machine platform. ✨ |
| 🍎 [**UTM**][utm]                       | Hardware accelerated virtual machine and emulation platform. ✨ |
| 🪟🐧 [**Docker**][docker]              | Container platform at near-native speed (WSL2 for Windows). ✨ |
| 🪟🐧🍎 [**Rancher Desktop**][rancher]  | Easy dev docker & kubernetes using the host's native VM capabilities. ✨ |
| 🪟🐧🍎 [**Podman Desktop**][podman]    | Easy dev podman using the host's native VM capabilities. |
| 🪟🐧🍎 [**Vagrant**][vagrant]          | Fast VM instantiation platform for testing. |
| 🪟🐧🍎 [**GNS3**][gns3]                | Network virtualization and testing tool. |

### Fonts

| Program                              | Description |
| ------------------------------------ | ----------- |
| [**JetBrains Mono**][jetbrains-mono] | Sharp & wide, meaning normal width and more lines when zoomed out. ✨ |
| [**Comic Mono**][comic-mono]         | Fun and unexpectedly legible monospace, inspired by Comic Sans. ✨ |
| [**Inter**][inter]                   | Variable width sans, gitlab's default font. Easy to read. ✨ |
| [**Iosevka SS14**][iosevka-jb]       | Narrow yet legible and JetBrains Mono inspired. Alt monospace. |

## Editor Extensions

### VSCode

#### Development Tools

| Program                                     | Description |
| ------------------------------------------- | ----------- |
| 🔒 [**Remote Development**][vsc-remote-dev] | Extremely useful remote development tools for WSL, SSH, and Containers. ✨ |
| [**Jupyter Notebook**][vsc-jupyter]         | Live notebook editing. ✨ |
| [**Polyglot Notebook**][vsc-polyglot]       | Jupyter for other languages. ✨ |
| [**Playwright Test**][vsc-playwright]       | E2E testing suite. ✨ |
| [**Live Preview**][vsc-live-preview]        | Fairly basic built-in web server w/ live reloading. ✨ |
| [**GitLens**][vsc-gitlens]                  | Extra Git tools for VSCode, nice to have. ✨ |
| [**SFTP**][vsc-sftp]                        | Well featured FTP/SFTP editing / syncing / exploring tool. |
| [**httpYac**][vsc-httpyac]                  | Extensive REST testing tool w/ code generation. Alt [**REST Client**][vsc-rest-client]. |
| [**Live Server**][vsc-live-server]          | Live reloading webpages w/ support for dynamic languages. |
| [**Markdown PDF**][vsc-markdown-pdf]        | Export Markdown to PDF/HTML/Image w/ customizations. |
| [**Color Manager**][vsc-color-manager]      | Integrated color picker and palette management tool. |
| [**Serial Monitor**][vsc-serial-monitor]    | Serial management and interfacing tool. |
| [**vscode-random**][vsc-vscode-random]      | Generate random data. |

#### Media Viewers

| Program                               | Description |
| ------------------------------------- | ----------- |
| [**Hex Editor**][vsc-hex]             | Easy to use Hex Editor. ✨ |
| [**Draw.io Integration**][vsc-drawio] | Editor for diagrams.net files. ✨ |
| [**Data Preview**][vsc-data-preview]  | Visualization tool for structured data. ✨ |
| [**Excel Viewer**][vsc-excel]         | Excel and CSV table visualization tool. ✨ |
| [**LaTeX Workshop**][vsc-latex]       | PDF Viewer + Watcher & *TeX tools. If no need for *TeX, use [vscode-pdf][vsc-vscode-pdf]. ✨ |
| [**RSS**][vsc-rss]                    | RSS Reader if you prefer in code editor. |

#### Code Management

| Program                                | Description |
| -------------------------------------- | ----------- |
| [**Project Manager**][vsc-project-man] | Efficiently add and manage projects. ✨ |
| [**Partial Diff**][vsc-partial-diff]   | Allows custom selection diffs. ✨ |
| [**gitignore**][vsc-gitignore]         | Quickly append official gitignore templates to project. ✨ |
| [**DotENV**][vsc-dotenv]               | Syntax highlighting for .ENV files. ✨ |
| [**Peacock**][vsc-peacock]             | Workspace theme engine for easier context switching. ✨ |

#### Formatting Tools

| Program                                    | Description |
| ------------------------------------------ | ----------- |
| [**Easy Snippet**][vsc-easy-snippet]       | Efficiently manage & logically edit language snippets. ✨ |
| [**Code Spell Checker**][vsc-spell-check]  | Unobtrusive spell checker. ✨ |
| [**Rewrap**][vsc-rewrap]                   | Hard wrapping & unwrapping tool. ✨ |
| [**Better Align**][vsc-better-align]       | Operator and comment alignment tool. ✨ |
| [**Paste Image**][vsc-paste-image]         | Makes pasting images to markup formats very easy. ✨ |
| [**:emojisense:**][vsc-emojisense]         | Insert emojis quickly. ✨ |
| [**Path Intellisense**][vsc-path]          | Makes path completion faster. ✨ |
| [**Remove Empty Lines**][vsc-remove-empty] | Configurable empty line handler. ✨ |

#### Editor Personalization

| Program                                      | Description |
| -------------------------------------------- | ----------- |
| [**Vim**][vsc-vim]                           | Native Vim binds. ✨ |
| [**Material Icon Theme**][vsc-material-icon] | More legible icon theme. ✨ |
| [**Word Count**][vsc-word-count]             | Counts words in markdown files. ✨ |
| [**filesize**][vsc-filesize]                 | Shows file information, including size, gzip size, and time of creation. ✨ |
| [**Rainbow CSV**][vsc-rainbow-csv]           | Provides clarity to CSV files and filtering/sorting tools. ✨ |
| [**Color Highlight**][vsc-color-highlight]   | Global Hex and RGBA color preview.✨  |
| [**indent-rainbow**][vsc-indent-rainbow]     | Preferred over the native indention highlighter. ✨ |
| [**Error Lens**][vsc-error-lens]             | Inline error codes. ✨ |
| [**Better Comments**][vsc-better-comments]   | Applies custom highlighting to different types of comments. ✨ |
| [**Todo Tree**][vsc-todo-tree]               | Keeps track of todo comments in code. ✨ |
| [**Color Highlight**][vsc-color-highlight]   | Inline colors. ✨ |
| [**Docs View**][vsc-docs-view]               | Read documentation on side instead of scrolling hover. |

### Visual Studio Extensions

| Program                                                         | Description |
| --------------------------------------------------------------- | ----------- |
| [**VsVim**][vside-vsvim]                                        | Vim keybinds. ✨ |
| [**Visual Studio Iconizer**][vside-iconizer]                    | Adds easier to identify symbols to buttons. ✨ |
| [**Editor Guidelines**][vside-guidelines]                       | Add graphical ruler to editor. ✨ |
| [**NuGet Package Manager**][vside-nuget]                        | Graphical browser for NuGet. ✨ |
| [**Output Enhancer**][vside-output-enhancer]                    | Colorizes output of terminal and debug log. ✨ |
| [**Trailing Whitespace Visualizer**][vside-trailing-whitespace] | Visualizes whitespace if not automatically truncating. ✨ |
| [**SideScroller**][vside-sidescroller]                          | Allows shift scroll. ✨ |
| [**Time Stamp Margin**][vside-timestamp]                        | Gives time upon execution or event in log. ✨ |
| [**Shrink Empty Lines**][vside-shrink-empty]                    | Frees vertical space by slightly shrinking unused lines. ✨ |
| [**Solution Error Visualizer**][vside-solution-error]           | Hover file to see error in solution. ✨ |
| [**Add New File**][vside-add-new-file]                          | Simple tool to add a file of whatever type. ✨ |
| [**CodeMaid**][vside-codemaid]                                  | Adds easier source + object navigation to C# and C++. |
| [**Dummy Text Generator**][vside-dummy-text]                    | Lorem Ipsums. |
| [**Visual Studio Spell Checker**][vside-spell-check]            | Spell checker. |
| [**Align Assignments**][vside-align]                            | Alignment tool for assignments. |

### IntelliJ IDEA Extensions

| Program                                           | Description |
| ------------------------------------------------- | ----------- |
| [**IdeaVim**][jb-vim]                             | Vim keybinds. ✨ |
| [**Rainbow Brackets**][jb-rainbow-brackets]       | Rainbow syntax for nested code. ✨ |
| [**Indent Rainbow**][jb-indent-rainbow]           | Rainbow indents for nested code. ✨ |
| [**Extra Icons**][jb-extra-icons]                 | Easier to identify symbols. ✨ |
| [**String Manipulation**][jb-string-manipulation] | Quickly change string formatting. |
| [**Restful Fast Request - API Buddy**][jb-rest]   | REST testing tools. |
| [**GitToolBox**][jb-gittoolbox]                   | Advanced git tools. |
| [**Maven Helper**][jb-maven-helper]               | Advanced MVN tools. |
| [**Randomness**][jb-randomness]                   | Random generator. |

## Network

### Browsers

| Program                                 | Description |
| --------------------------------------- | ----------- |
| 🪟🐧🍎 [**Firefox**][firefox]          | Favorite browser, tag based bookmarking. ✨ |
| 🪟🐧🍎 **Chromium / Edge 🔒 / Brave** | Blink browsers (for testing). ✨ |

### Browser Extensions

| Program                                                | Description |
| ------------------------------------------------------ | ----------- |
| 🦊👁️‍ [**uBlock Origin**][web-ublock]                  | Blocks ads and useful webpage analysis tools. ✨ |
| 🦊👁️‍ [**Dark Reader**][web-dark-reader]               | Globally injected dark theme. ✨ |
| 🦊👁️‍ [**Video Speed Controller**][web-video-speed]    | Control video playback speed. ✨ |
| 🦊👁️‍ [**Highlight or Hide Search Engine Results**][web-search-engine-hide]  | Block domains from search results. ✨ |
| 🦊👁️‍ [**Channel Blocker**][web-channel-block]         | Block channels from recommendations. ✨ |
| 🦊👁️‍ [**Vimium-FF / Vimium**][web-vim]                | Vi binds for webpage navigation. ✨ |
| 🦊👁️‍ [**Wayback Machine**][web-wayback]               | Archive web pages to the Wayback Machine. ✨ |
| 🦊👁️‍ [**Archive Page**][web-archive]                  | Archive web pages to archive.is ✨ |
| 🦊👁️‍ [**User-Agent Switcher**][web-user-agent]        | Faster user agent changing. ✨ |
| 🦊👁️‍ [**Decentraleyes**][web-decentraleyes]           | Stubs CDN calls, reduces spying surface. ✨ |
| 🦊👁️‍ [**Old Reddit Redirect**][web-old-reddit]        | Redirects to old format reddit. ✨ |
| 🦊👁️‍ [**ClearURLs**][web-clearurls]                   | Removes trackers and PII from URLs automatically. ✨ |
| 🦊👁️‍ [**Fast Forward**][web-fast-forward]             | Skips link shortening services. ✨ |
| 🦊👁️‍ [**SponsorBlock**][web-sponsorblock]             | Crowdsourced video annotation and skipping. ✨ |
| 🦊👁️‍ [**Violentmonkey**][web-violentmonkey]           | Userscripts manager. ✨ |
| 🦊👁️‍ [**DF YouTube**][web-df-youtube]                 | Reduces visual distractions on YouTube. ✨ |
| 🦊👁️ [**Feedbro**][web-feedbro]                       | RSS Client. ✨ |
| 🦊 [**cookies.txt**][web-cookies]                      | Exports cookies for other tools. |
| 🦊👁️‍ [**Search by Image**][web-search-by-image]       | Reverse image search anything quickly. |
| 🦊👁️‍ [**Center Pages**][web-center-pages]             | Condense HTML pages if too wide. |
| 🦊👁️‍ [**Bypass Paywalls Clean**][web-bypass-paywalls] | Skips paywalls from articles. |
| 🦊👁️‍ [**SoundFixer**][web-soundfixer]                 | Allows audio amplification for low sources. |
| 🦊 [**Limit Tabs**][web-limit-tabs]                    | Blocks tabs after user-set max is reached. |
| 🦊👁️‍ [**LeechBlock NG**][web-leechblock]              | Customizable site blacklist and time-gate software. |

#### Userscripts

| Program                                                    | Description |
| ---------------------------------------------------------- | ----------- |
| 🦊👁️‍ [**Youtube Music fix volume ratio**][uscript-yt-fix] | More granular volume slider. |
| 🦊👁️‍ [**VGMLoaderX**][uscript-vgmloaderx]                 | Gets past annoying roadblocks. |

### Communication

| Program                           | Description |
| --------------------------------- | ----------- |
| 🪟🍎🔒 [**Outlook**][outlook]    | Email and calendar client. FOSS option [**Thunderbird**](thunderbird). ✨ |
| 🪟🐧🍎🔒 [**Discord**][discord] | Current popular chat platform. ✨ |
| 🪟🍎🔒 [**OneDrive**][onedrive]  | Native-ish SharePoint file browser integration. ✨ |
| 🪟🍎🔒 [**Teams**][teams]        | Business VOIP & IM platform. |

### VPN

| Program                                | Description |
| -------------------------------------- | ----------- |
| 🪟🐧🍎 [**OpenVPN**][openvpn]         | OpenVPN client and server. ✨ |
| 🪟🐧🍎 [**WireGuard**][wireguard]     | WireGuard client and server. |
| 🪟🐧🍎 [**SoftEther**][softether]     | Client and server for SSTP, IPSec, WireGuard, and OpenVPN. |
| 🪟🐧🍎 [**OpenConnect**][openconnect] | Client and server for AnyConnect. |

### File Downloading

| Program                                 | Description |
| --------------------------------------- | ----------- |
| 🪟🐧🍎 [**yt-dlp**][yt-dlp]            | Download video and audio from most websites. ✨ |
| 🪟🐧🍎 [**gallery-dl**][gallery-dl]    | Download social media and gallery data. ✨ |
| 🪟🐧🍎 [**qbittorrent**][qbittorrent]  | Torrent client and search engine. ✨ |
| 🪟🍎 [**Cyberduck**][cyberduck]        | GUI for nearly all protocols and cloud platforms. Does nag. ✨ |
| 🪟 [**winscp**][winscp]                 | GUI client for SFTP, S3, WebDAV, and more. Doesn't nag. |
| 🪟🐧🍎 [**wget**][wget]                | Download websites. |
| 🪟🐧🍎 [**aria2**][aria2]              | Sophisticated threaded downloading tool. |
| 🪟🐧🍎 [**rclone**][rclone]            | Mount & sync shares from many cloud vendors. |
| 🪟 [**winfsp**][winfsp]                 | Dependency for rclone on Windows. |

### Analysis

| Program                            | Description |
| ---------------------------------- | ----------- |
| 🪟🐧🍎 [**nmap/Zenmap**][nmap]    | Network analysis. ✨ |
| 🪟🐧🍎 [**Wireshark**][wireshark] | Packet analysis. ✨ |

## Media

### Documents

| Program                                 | Description |
| --------------------------------------- | ----------- |
| 🪟🔒 [**OneNote 2016**][onenote-2016] / 🍎🔒 [**OneNote**][onenote]  | Preferred personal / team note system. ✨ |
| 🪟 [**OneMore**][onemore]              | Quality-of-life extension for OneNote 2016. ✨ |
| 🪟🐧🍎 [**LibreOffice**][libreoffice] | Microsoft Office viewer & editor. ✨ |
| 🪟🐧🍎 [**pandoc**][pandoc]           | Text media conversion tool. ✨ |
| 🪟🐧🍎 [**pdftk-java**][pdftk-java]   | PDF transformation tool (Rewrite of [**pdftk**][pdftk]). ✨ |
| 🪟🐧 [**Okular**][okular]              | PDF and eBook reader / editor. |
| 🪟🐧🍎 [**Koodo**][koodo]             | Modern ebook desktop app. |
| 🪟🐧🍎 [**Calibre**][calibre]         | Tools for ebooks. |
| 🪟🐧🍎 [**Tesseract**][tesseract]     | Text OCR tool. |

### Images

| Program                                 | Description |
| --------------------------------------- | ----------- |
| 🪟🐧🍎 [**GIMP**][gimp]               | Full fledged editing and drawing software. Alt [**Krita**][krita]. ✨ |
| 🪟🐧🍎 [**DarkTable**][darktable]     | Raw & batch processing photography. ✨ |
| 🪟 [**ZoomIt**][zoomit]                | Fast screenshot markup & live magnification tool. ✨ |
| 🪟🐧🍎 [**ImageMagick**][imagemagick] | CLI tool for automated editing. ✨ |
| 🪟🐧🍎 [**Asesprite**][asesprite]     | Pixel art software. ✨ |
| 🪟🐧🍎 [**Ksnip**][ksnip]             | Advanced screenshot tool. |
| 🪟🐧🍎 [**Inkscape**][inkscape]       | Full vector editing suite. |
| 🪟🐧🍎 [**exiftool**][exiftools]      | Remove or edit EXIF data. |

### Audio

| Program                                   | Description |
| ----------------------------------------- | ----------- |
| 🪟🐧🍎🔒 [**FL Studios**][fl-studios]   | Fully featured DAW. FOSS Alt [**Ardour**][ardour]. ✨ |
| 🪟🐧🍎 [**Audacity**][audacity]         | GUI Audio editing software. ✨ |
| 🪟🐧🍎 [**Mixxx**][mixxx]               | DJ mixing software and audio analysis tool. ✨ |
| 🪟🐧 [**Soundux**][soundux]              | Sampler / Soundboard. |
| 🪟🐧🍎 [**Quod Libet**][quod-libet]     | Dedicated audio library and player. |
| 🪟🐧🍎 [**MusicBrainz Picard**][picard] | Automated music meta tagging software. |
| 🪟 **[Equalizer APO][equalizer-apo] & [Peace Equalizer][peace-equalizer]**  | System-wide VST applier for audio IO. |
| 🪟🐧🍎 [**Spleeter**][spleeter]         | AI Vocal / Instrumental isolation tool. |

### Video

| Program                                         | Description |
| ----------------------------------------------- | ----------- |
| 🪟🐧🍎 [**VLC**][vlc]                          | Fully featured media player. ✨ |
| 🪟🐧🍎 [**OBS**][obs]                          | Allows livestreaming, easy screen recording, and overlays. ✨ |
| 🪟🐧🍎 [**FFmpeg**][ffmpeg]                    | Fully featured CLI media conversion tool and editor. ✨ |
| 🪟🐧🍎🔒 [**DaVinci Resolve**][davinci]       | Graphical non-linear video editing software. ✨ |
| 🪟🐧🍎 [**Kdenlive**][kdenlive]                | Preferred FOSS graphical non-linear video editing software. ✨ |
| 🪟 [**MPV.NET**][mpvnet]  / 🍎 [**MPV**][mpv]  | Fast and customizable media player. |

### Video Server

| Program                           | Description |
| --------------------------------- | ----------- |
| 🪟🐧🍎 [**Jellyfin**][jellyfin]  | Media server. |

## System Tools

### Backups

| Program                                             | Description |
| --------------------------------------------------- | ----------- |
| 🪟🐧🍎🔒 [**Synology Utilities**][synology-utils] | Tools for my NAS. ✨ |
| 🪟🐧🍎 [**TestDisk & PhotoRec**][testdisk]         | Partition and File recovery tool. ✨ |
| 🪟🐧🍎 [**ddrescue**][ddrescue]                    | Failing drive recovery and backup tool. ✨ |
| 🪟🐧🍎🔒 [**Veeam Agent**][veeam-agent]           | Free incremental block and file level backup + replication tool. |
| 🪟🐧🍎 [**Restic**][restic]                        | File level backup tool. |

### File Management

| Program                                             | Description |
| --------------------------------------------------- | ----------- |
| 🪟🐧🍎 [**7-Zip**][7-zip]                         | Full featured archive manager, easy encryption. ✨ |
| 🪟🐧🍎 [**DupeGuru**][dupeguru]                   | Duplicate file finder. ✨ |
| 🪟🐧🍎 [**ripgrep**][rg] + [**ripgrep-all**][rga] | Recursive file and string finder. ✨ |
| **🪟 [WinDirStat][windirstat] / 🐧 [QDirStat][qdirstat] / 🍎 [GrandPerspective][grandperspective]** | GUI storage analysis. ✨ |
| 🪟🐧🍎 [**buku**][buku]                           | Bookmark and tag system. |
| 🪟 [**wincdemu**][wincdemu]                        | Virtual disk mounter & creator. |
| 🐧🍎 [**rsync**][rsync]                            | Fully featured copying tool. |
| 🪟🐧🍎 [**dua**][dua]                             | CLI storage analysis. |

### Security

| Program                                      | Description |
| -------------------------------------------- | ----------- |
| 🪟🐧🍎 [**Bitwarden**][bitwarden]          | Multi-user synced secrets. ✨ |
| 🦊👁️‍ [**Bitwarden-Browser**][web-bitwarden] | Browser plugin for Bitwarden. |
| 🪟🐧🍎 [**Veracrypt**][veracrypt]          | Portable encrypted volumes. |
| 🪟 [**Gpg4win**][gpg4win]                   | PGP keychain and tools. |

### Installation Media

| Program                       | Description |
| ----------------------------- | ----------- |
| 🪟🐧 [**Ventoy**][ventoy]    | Multiboot USB tool. ✨ |
| 🪟🐧🍎 [**Etcher**][etcher]  | Easy to use alternative to prepare installation media. ✨ |

### Automation

| Program                         | Description |
| ------------------------------- | ----------- |
| 🪟 [**AHK**][ahk] / 🐧 [**sxhkd**][sxhkd] / 🍎 [**karabiner**][karabiner] | Rebind and map keyboard(s). ✨ |
| 🪟🐧🍎 [**espanso**][espanso] | Quick variable compatible keyboard templates. |

### Productivity

| Program                          | Description |
| -------------------------------- | ----------- |
| 🪟🐧 [**Qalculate**][qalculate] | Full featured calculator. ✨ |
| 🪟🐧🍎 [**Anki**][anki]         | SRS and flashcard tool. |

### Terminal

| Program                     | Description |
| --------------------------- | ----------- |
| 🪟🐧🍎 [**PuTTY**][putty] | Serial console, putty gen, and terminal logging. VScode alt [**Serial Monitor**][vsc-serial-monitor]. |
| 🪟🐧🍎 [**tio**][tio]     | CLI serial console. |

### Input

| Program                                    | Description |
| ------------------------------------------ | ----------- |
| 🪟🔒 [**VoiceMeeter Potato**][voicemeeter-p] / 🍎 [**BlackHole**][blackhole] | Virtual audio routing. |
| 🪟🐧🍎 [**KDE Connect**][kde-connect]     | Desktop <-> Smartphone input and notifications. |
| 🪟🐧🍎 [**Barrier**][barrier]             | Cross-platform keyboard and mouse KVM software. |

### Window Management

| Program                         | Description |
| ------------------------------- | ----------- |
| 🍎 [**Rectangle**][rectangle]   | Sane window management keybind program. ✨ |
| 🍎 [**AltTab**][alttab]         | Sane window switching behavior. ✨ |
| 🍎 [**Swift Quit**][swift-quit] | Sane window closing behavior. ✨ |

### Runtimes

| Program                                    | Description |
| ------------------------------------------ | ----------- |
| 🪟🔒 [**.NET 3.5**][net-3.5]              | Older .NET Framework that old software depends on. ✨ |
| 🪟🔒 [**DirectX**][directx]               | DirectX 9 and above. Dependency for many games. ✨ |
| 🪟🔒 [**MSVC Redist 2015-2022**][msvc-15] | Microsoft Visual C++ 2015-2022. ✨ |
| 🪟🔒 [**MSVC Redist 2013**][msvc-13]      | Microsoft Visual C++ 2013. ✨ |
| 🪟🔒 [**MSVC Redist 2012**][msvc-12]      | Microsoft Visual C++ 2012. ✨ |
| 🪟🔒 [**MSVC Redist 2010**][msvc-10]      | Microsoft Visual C++ 2010. ✨ |
| 🪟🔒 [**MSVC Redist 2008**][msvc-08]      | Microsoft Visual C++ 2008. ✨ |
| 🪟🔒 [**MSVC Redist 2005**][msvc-05]      | Microsoft Visual C++ 2005. ✨ |

### Debug

| Program                                          | Description |
| ------------------------------------------------ | ----------- |
| 🪟🔒 [**Sysinternals Suite**][sysinternals]     | Extended official tools for debugging. ✨ |
| 🪟🔒 [**Windows SDK**][windows-sdk]             | Lots of important debug and development tools. ✨ |
| 🪟 [**diskspd**][diskspd] / 🐧🍎 [**fio**](fio) | Detailed disk performance metrics. ✨ |
| 🪟 [**CrystalDiskInfo**][crystaldiskinfo] / 🐧🍎 [**smartmontools**][smartmontools]  | SMART and other disk health metrics. ✨ |
| 🪟🍎🔒 [**iTunes**][itunes]                     | Dependency for certain Apple device procedures. |
| 🪟🐧🍎 [**adb**][adb]                           | Interface and automate android. |
| 🐧🍎 [**sysbench**][sysbench]                   | CPU, Memory, IO, and basic SQL benchmarking tools. |

### Services

| Program              | Description |
| -------------------- | ----------- |
| 🪟 [**NSSM**][nssm]  | Create services from binaries and scripts. |

### Management

| Program                                | Description |
| -------------------------------------- | ----------- |
| 🪟🐧🍎 [**MeshCentral**][meshcentral] | Remote desktop server and client software w/ AMT support. |
| 🪟🐧🍎 [**Guacamole**][guacamole]     | SSH/RDP/VNC server gateway. |
| 🪟🐧🍎 [**TigerVNC**][tigervnc]       | VNC client (& server options). |
| 🐧 [**XRDP**][xrdp]                    | RDP server for Linux. |

## Gaming

### Platforms

| Program                       | Description |
| ----------------------------- | ----------- |
| 🪟🐧🍎🔒 [**Steam**][steam] | Common platform for PC games and utilities. ✨ |
| 🪟🍎🔒 [**GOG Galaxy**][gog] | Dependency to play some network multiplayer GOG games. |

### Peripherals

| Program                          | Description |
| -------------------------------- | ----------- |
| 🪟 [**DS4Windows**][ds4windows] | Allows PS4 to be functional on non-supporting platforms. |

### Emulation

| Program                            | Description |
| ---------------------------------- | ----------- |
| 🪟🐧🍎 [**Retroarch**][retroarch] | Emulator platform. ✨ |
| 🪟🐧🍎 [**Dolphin**][dolphin]     | Emulator for GCN / Wii + netplay. |

### Games

| Program                              | Description |
| ------------------------------------ | ----------- |
| 🪟🐧🍎 [**Nullpomino**][nullpomino] | All sorts of falling block games and styles. |
| 🪟🐧🍎🔒 [**Minecraft**][minecraft] | Fun for everyone! |

# Mobile

## System Tools

| App                                       | Description |
| ----------------------------------------- | ----------- |
| 🤖 [**F-Droid**][f-droid]                 | FOSS app store. ✨ |
| 🤖 [**Termux**][termux]                   | Android terminal for phone w/ package manager. ✨ |
| 🤖 [**Ghost Commander**][ghost-commander] | File explorer w/ network mounting ability. ✨ |
| 🤖🍏 [**Bitwarden**][cell-bitwarden]     | Secrets manager. ✨ |
| 🤖🍏 **TOTP**                            | Anything will do. ✨ |
| 🤖 [**Easer**][easer]                     | Event based automation platform. |

## Web Browsers

| App                               | Description |
| --------------------------------- | ----------- |
| 🤖🍏 [**Firefox**][cell-firefox] | General purpose web browser. ✨ |
| 🤖🍏 [**Brave**][cell-brave]     | Ad-blocking browser, good for iOS. ✨ |

## Communication

| App                                 | Description |
| ----------------------------------- | ----------- |
| 🤖🍏🔒 [**Outlook**][cell-outlook] | Preferred calendar and email system. ✨ |
| 🤖🍏🔒 [**Discord**][cell-discord] | Popular chat platform. ✨ |
| 🤖🍏🔒 [**Teams**][cell-teams]     | Business IM platform. |

## Network Tools

| App                                     | Description |
| --------------------------------------- | ----------- |
| 🤖 [**DNS66**][dns66]                   | Quick adblocking DNS. ✨ |
| 🤖🍏 [**OpenVPN**][cell-openvpn]       | OpenVPN client. ✨ |
| 🤖 [**WiFiAnalyzer**][wifianalyzer]     | WiFi analysis tool. ✨ |
| 🤖 [**primitive ftpd**][primitive-ftpd] | FTP/SFTP server. ✨ |
| 🤖 [**PCAPdroid**][pcapdroid]           | PCAP capture for device. |
| 🤖 [**Ning**][ning]                     | Layer 2-4 discovery tool. |
| 🤖 [**LibreTorrent**][libretorrent]     | Torrent client. |
| 🤖🍏 [**WireGuard**][cell-wireguard]   | WireGuard client. |
| 🤖 [**FTPClient**][ftpclient]           | FTP client. |

## User Tools

| App                                           | Description |
| --------------------------------------------- | ----------- |
| 🤖🍏🔒 [**Google Maps**][google-maps]        | Navigation & GPS software. ✨ |
| 🤖 [**Calculator-inator**][calculator-inator] | Full calculator ✨ |
| 🤖 [**Audio Recorder**][audio-recorder]       | Record audio. ✨ |
| 🤖 [**omWeather**][omweather]                 | Weather application. ✨ |
| 🤖 [**Compass**][compass]                     | Compass application. ✨ |
| 🤖 [**Markor**][markor]                       | Basic text editor. ✨ |
| 🤖 [**Simple Draw Pro**][simple-draw-pro]     | Basic drawing program. ✨ |
| 🤖 [**Semitone**][semitone]                   | Tuner, keyboard, and metronome. ✨ |
| 🤖 [**Open Note Scanner**][open-note-scanner] | Document scanning & PDF appending tool. |
| 🤖 [**Acode**][acode]                         | Programming focused text editor. |
| 🤖 [**BetterCounter**][bettercounter]         | Counter app. |

## Media

| App                                      | Description |
| ---------------------------------------  | ----------- |
| 🤖 [**NewPipe**][newpipe]               | Youtube frontend, download videos as well. ✨ |
| 🤖🍏🔒 [**Audible**][audible]          | Amazon's audiobook store. ✨ |
| 🤖 [**Voice**][voice]                   | Audiobook player. ✨ |
| 🤖🍏 [**VLC**][cell-vlc]                | Fully featured media player. ✨ |
| 🤖 [**AntennaPod**][antennapod]         | Podcast player & tracker. ✨ |
| 🤖 [**Metro**][metro]                   | Music player. |
| 🤖 [**Librera Reader**][librera-reader] | eBook reader. |
| 🤖 [**Spotube**][spotube]               | Spotify frontend. |

## Media Tools

| App                            | Description |
| ------------------------------ | ----------- |
| 🤖 [**VES**][ves]             | Photo comparison tool. |
| 🤖🔒 [**Snapseed**][snapseed] | Photo editing tool, including RAW processing. |

## Productivity

| App                                      | Description |
| ---------------------------------------- | ----------- |
| 🤖🍏 [**OneNote**][cell-onenote]        | Preferred personal / team note system. ✨ |
| 🤖 [**Track & Graph**][track-graph]      | Graphing tool. |
| 🤖 [**Goodtime Productivity**][goodtime] | Pomodoro timer. |
| 🤖 [**TimeR Machine**][timer-machine]    | Interval timer. |
| 🤖🍏 [**AnkiDroid**][ankidroid]         | SRS and flashcard tool. |

## Gaming

| App                                   | Description |
| ------------------------------------- | ----------- |
| 🤖 [**Open Sudoku**][open-sudoku]    | Sudoku. ✨ |
| 🤖 [**Antimine**][antimine]          | Minesweeper. ✨ |
| 🤖🍏 [**Retroarch**][cell-retroarch] | Emulator platform. ✨ |

[vscode]: https://code.visualstudio.com/download
[nvim]: https://github.com/neovim/neovim/releases
[vim]: https://www.vim.org/download.php
[vside]: https://visualstudio.microsoft.com/vs/compare/
[intellij]: https://www.jetbrains.com/idea/download/
[git]: https://git-scm.com/downloads
[dploy]: https://github.com/arecarn/dploy
[sqlite-tools]: https://www.sqlite.org/download.html
[sqlite-browser]: https://github.com/sqlitebrowser/sqlitebrowser
[vsc-sqlite-ed]: https://marketplace.visualstudio.com/items?itemName=yy0931.vscode-sqlite3-editor
[vsc-sqlite-view]: https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools
[dbeaver]: https://github.com/dbeaver/dbeaver/releases
[go-ycsb]: https://github.com/pingcap/go-ycsb
[hammerdb]: https://www.hammerdb.com/download.html
[ssms]: https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16
[Adoptium]: https://adoptopenjdk.net/releases.html
[python3]: https://www.python.org/downloads/
[miniconda]: https://docs.conda.io/en/latest/miniconda.html
[nvm]: https://github.com/nvm-sh/nvm
[nodejs]: https://nodejs.org/en/download/
[netcore]: https://dotnet.microsoft.com/download/dotnet
[texlive]: https://www.tug.org/texlive/acquire-iso.html
[powershell]: https://github.com/PowerShell/Powershell
[go]: https://go.dev/dl/
[rust]: https://www.rust-lang.org/tools/install
[php]: https://windows.php.net/download/
[msys2]: https://www.msys2.org/
[godot]: https://godotengine.org/download
[blender]: https://www.blender.org/download/
[curl]: https://curl.se/download.html
[http-toolkit]: https://github.com/httptoolkit/httptoolkit-desktop/releases
[insomnia]: https://insomnia.rest/download
[jmeter]: https://jmeter.apache.org/download_jmeter.cgi
[owasp-zap]: https://www.zaproxy.org/download/
[ghidra]: https://github.com/NationalSecurityAgency/ghidra
[mkcert]: https://github.com/FiloSottile/mkcert
[vbox]: https://www.virtualbox.org/wiki/Downloads
[utm]: https://github.com/utmapp/UTM
[docker]: https://dev.to/bowmanjd/install-docker-on-windows-wsl-without-docker-desktop-34m9
[rancher]: https://rancherdesktop.io/
[podman]: https://podman-desktop.io/downloads
[vagrant]: https://www.vagrantup.com/downloads
[gns3]: https://github.com/GNS3/gns3-gui/releases
[jetbrains-mono]: https://github.com/JetBrains/JetBrainsMono
[iosevka-jb]: https://github.com/be5invis/Iosevka/blob/v21.0.0/doc/PACKAGE-LIST.md
[comic-mono]: https://github.com/dtinth/comic-mono-font
[inter]: https://github.com/rsms/inter
[vsc-remote-dev]: https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack
[vsc-gitlens]: https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens
[vsc-sftp]: https://marketplace.visualstudio.com/items?itemName=Natizyskunk.sftp
[vsc-jupyter]: https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter
[vsc-polyglot]: https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode
[vsc-live-preview]: https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server
[vsc-httpyac]: https://marketplace.visualstudio.com/items?itemName=anweber.vscode-httpyac
[vsc-playwright]: https://marketplace.visualstudio.com/items?itemName=ms-playwright.playwright
[vsc-live-server]: https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer
[vsc-markdown-pdf]: https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf
[vsc-color-manager]: https://marketplace.visualstudio.com/items?itemName=RoyAction.color-manager
[vsc-serial-monitor]: https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-serial-monitor
[vsc-vscode-random]: https://marketplace.visualstudio.com/items?itemName=jrebocho.vscode-random
[vsc-hex]: https://marketplace.visualstudio.com/items?itemName=ms-vscode.hexeditor
[vsc-drawio]: https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio
[vsc-data-preview]: https://marketplace.visualstudio.com/items?itemName=RandomFractalsInc.vscode-data-preview
[vsc-excel]: https://marketplace.visualstudio.com/items?itemName=GrapeCity.gc-excelviewer
[vsc-latex]: https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop
[vsc-rss]: https://marketplace.visualstudio.com/items?itemName=luyuhuang.rss
[vsc-project-man]: https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager
[vsc-partial-diff]: https://marketplace.visualstudio.com/items?itemName=ryu1kn.partial-diff
[vsc-gitignore]: https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore
[vsc-dotenv]: https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv
[vsc-peacock]: https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock
[vsc-easy-snippet]: https://marketplace.visualstudio.com/items?itemName=inu1255.easy-snippet
[vsc-spell-check]: https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker
[vsc-rewrap]: https://marketplace.visualstudio.com/items?itemName=stkb.rewrap
[vsc-better-align]: https://marketplace.visualstudio.com/items?itemName=Chouzz.vscode-better-align
[vsc-paste-image]: https://marketplace.visualstudio.com/items?itemName=mushan.vscode-paste-image
[vsc-emojisense]: https://marketplace.visualstudio.com/items?itemName=bierner.emojisense
[vsc-path]: https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense
[vsc-remove-empty]: https://marketplace.visualstudio.com/items?itemName=usernamehw.remove-empty-lines
[vsc-vim]: https://marketplace.visualstudio.com/items?itemName=vscodevim.vim
[vsc-material-icon]: https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme
[vsc-word-count]: https://marketplace.visualstudio.com/items?itemName=ms-vscode.wordcount
[vsc-filesize]: https://marketplace.visualstudio.com/items?itemName=mkxml.vscode-filesize
[vsc-rainbow-csv]: https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv
[vsc-color-highlight]: https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight
[vsc-indent-rainbow]: https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow
[vsc-error-lens]: https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens
[vsc-better-comments]: https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments
[vsc-todo-tree]: https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree
[vsc-docs-view]: https://marketplace.visualstudio.com/items?itemName=bierner.docs-view
[vside-vsvim]: https://marketplace.visualstudio.com/items?itemName=JaredParMSFT.VsVim
[vside-iconizer]: https://marketplace.visualstudio.com/items?itemName=OlegTarasov.VisualStudioIconizerforVisualStudio15
[vside-guidelines]: https://marketplace.visualstudio.com/items?itemName=PaulHarrington.EditorGuidelines
[vside-nuget]: https://marketplace.visualstudio.com/items?itemName=NuGetTeam.NuGetPackageManager
[vside-codemaid]: https://marketplace.visualstudio.com/items?itemName=SteveCadwallader.CodeMaidVS2022
[vside-dummy-text]: https://marketplace.visualstudio.com/items?itemName=MadsKristensen.DummyTextGenerator
[vside-spell-check]: https://marketplace.visualstudio.com/items?itemName=EWoodruff.VisualStudioSpellCheckerVS2022andLater
[vside-output-enhancer]: https://marketplace.visualstudio.com/items?itemName=NikolayBalakin.Outputenhancer
[vside-trailing-whitespace]: https://marketplace.visualstudio.com/items?itemName=MadsKristensen.TrailingWhitespaceVisualizer
[vside-sidescroller]: https://marketplace.visualstudio.com/items?itemName=drewnoakes.SideScroller
[vside-timestamp]: https://marketplace.visualstudio.com/items?itemName=VisualStudioPlatformTeam.TimeStampMargin2022
[vside-shrink-empty]: https://marketplace.visualstudio.com/items?itemName=VisualStudioPlatformTeam.SyntacticLineCompression2022
[vside-solution-error]: https://marketplace.visualstudio.com/items?itemName=VisualStudioPlatformTeam.SolutionErrorVisualizer2022
[vside-align]: https://marketplace.visualstudio.com/items?itemName=VisualStudioPlatformTeam.AlignAssignment2022
[vside-add-new-file]: https://marketplace.visualstudio.com/items?itemName=MadsKristensen.AddNewFile64
[jb-vim]: https://plugins.jetbrains.com/plugin/164-ideavim
[jb-string-manipulation]: https://plugins.jetbrains.com/plugin/2162-string-manipulation
[jb-rest]: https://plugins.jetbrains.com/plugin/16988-restful-fast-request--api-buddy
[jb-rainbow-brackets]: https://plugins.jetbrains.com/plugin/10080-rainbow-brackets
[jb-indent-rainbow]: https://plugins.jetbrains.com/plugin/13308-indent-rainbow
[jb-gittoolbox]: https://plugins.jetbrains.com/plugin/7499-gittoolbox
[jb-maven-helper]: https://plugins.jetbrains.com/plugin/7179-maven-helper
[jb-extra-icons]: https://plugins.jetbrains.com/plugin/11058-extra-icons
[jb-randomness]: https://plugins.jetbrains.com/plugin/9836-randomness
[firefox]: https://www.mozilla.org/en-US/firefox/all/
[web-ublock]: https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/
[web-dark-reader]: https://addons.mozilla.org/en-US/firefox/addon/darkreader/
[web-limit-tabs]: https://addons.mozilla.org/en-US/firefox/addon/rudolf-fernandes/
[web-leechblock]: https://addons.mozilla.org/en-US/firefox/addon/leechblock-ng/
[web-video-speed]: https://addons.mozilla.org/en-US/firefox/addon/videospeed/
[web-search-engine-hide]: https://addons.mozilla.org/en-US/firefox/addon/hohser/
[web-channel-block]: https://addons.mozilla.org/en-US/firefox/addon/youtube-cleaner/
[web-vim]: https://addons.mozilla.org/en-US/firefox/addon/vimium-ff/
[web-wayback]: https://addons.mozilla.org/en-US/firefox/addon/wayback-machine_new/
[web-archive]: https://addons.mozilla.org/en-US/firefox/addon/archive-page/
[web-user-agent]: https://addons.mozilla.org/en-US/firefox/addon/uaswitcher/
[web-decentraleyes]: https://addons.mozilla.org/en-US/firefox/addon/decentraleyes/
[web-old-reddit]: https://addons.mozilla.org/en-US/firefox/addon/old-reddit-redirect/
[web-clearurls]: https://addons.mozilla.org/en-US/firefox/addon/clearurls/
[web-fast-forward]: https://addons.mozilla.org/en-US/firefox/addon/fastforwardteam/
[web-cookies]: https://addons.mozilla.org/en-US/firefox/addon/cookies-txt/
[web-search-by-image]: https://addons.mozilla.org/en-US/firefox/addon/search_by_image/
[web-center-pages]: https://addons.mozilla.org/en-US/firefox/addon/center-pages/
[web-sponsorblock]: https://addons.mozilla.org/en-US/firefox/addon/sponsorblock/?src=external-website
[web-bypass-paywalls]: https://gitlab.com/magnolia1234/bypass-paywalls-clean-filters
[web-df-youtube]: https://addons.mozilla.org/en-US/firefox/addon/df-youtube/
[web-soundfixer]: https://addons.mozilla.org/en-US/firefox/addon/soundfixer/
[web-violentmonkey]: https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/
[uscript-yt-fix]: https://greasyfork.org/en/scripts/397686-youtube-music-fix-volume-ratio
[uscript-vgmloaderx]: https://forgejo.sny.sh/sun/userscripts/src/branch/main/user/VGMLoaderX.user.js
[outlook]: https://apps.microsoft.com/detail/9NRX63209R7B?ocid=cmmdoli6tgo&hl=en-us&gl=US
[teams]: https://www.microsoft.com/en-us/microsoft-teams/download-app
[discord]: https://discord.com/download
[onedrive]: https://www.microsoft.com/en-us/microsoft-365/onedrive/download
[openvpn]: https://openvpn.net/community-downloads/
[wireguard]: https://www.wireguard.com/install/
[softether]: https://github.com/SoftEtherVPN/SoftEtherVPN/
[openconnect]: https://www.infradead.org/openconnect/packages.html
[wget]: https://eternallybored.org/misc/wget/
[aria2]: https://github.com/aria2/aria2
[yt-dlp]: https://github.com/yt-dlp/yt-dlp
[winscp]: https://winscp.net/eng/download.php
[cyberduck]: https://cyberduck.io/download/
[rclone]: https://github.com/rclone/rclone/releases
[winfsp]: https://github.com/billziss-gh/winfsp
[qbittorrent]: https://www.qbittorrent.org/download.php
[nmap]: https://nmap.org/download.html
[wireshark]: https://www.wireshark.org/download.html
[onenote-2016]: https://www.onenote.com/download/win32/x64/en-US
[onenote]: https://www.onenote.com/download
[onemore]: https://github.com/stevencohn/OneMore
[libreoffice]: https://www.libreoffice.org/download/download/
[okular]: https://okular.kde.org/download/
[koodo]: https://github.com/troyeguo/koodo-reader
[pandoc]: https://pandoc.org/installing.html
[tesseract]: https://github.com/UB-Mannheim/tesseract/wiki
[pdftk-java]: https://gitlab.com/pdftk-java/pdftk
[gimp]: https://www.gimp.org/downloads/
[darktable]: https://www.darktable.org/install/
[ksnip]: https://github.com/ksnip/ksnip
[inkscape]: https://inkscape.org/release/
[imagemagick]: https://imagemagick.org/script/download.php
[exiftools]: https://exiftool.org/
[asesprite]: https://store.steampowered.com/app/431730/Aseprite/
[fl-studios]: https://www.image-line.com/fl-studio-download/
[audacity]: https://www.audacityteam.org/download/
[mixxx]: https://mixxx.org/download/#stable
[quod-libet]: https://quodlibet.readthedocs.io/en/latest/downloads.html
[picard]: https://picard.musicbrainz.org/downloads/
[equalizer-apo]: https://sourceforge.net/projects/equalizerapo/
[peace-equalizer]: https://sourceforge.net/projects/peace-equalizer-apo-extension/
[mpvnet]: https://github.com/stax76/mpv.net/releases
[mpv]: https://mpv.io/installation/
[vlc]: https://www.videolan.org/vlc/#download
[obs]: https://obsproject.com/download
[ffmpeg]: https://ffmpeg.org/download.html
[davinci]: https://www.blackmagicdesign.com/products/davinciresolve
[kdenlive]: https://kdenlive.org/en/download/
[spleeter]: https://github.com/deezer/spleeter
[jellyfin]: https://jellyfin.org/downloads/
[veeam-agent]: https://www.veeam.com/virtual-server-management-one-free.html
[synology-utils]: https://www.synology.com/en-uk/support/download/DS923+?version=7.2#utilities
[restic]: https://github.com/restic/restic
[testdisk]: https://www.cgsecurity.org/wiki/TestDisk_Download
[ddrescue]: https://sudonull.com/post/115150-Saving-data-in-windows-using-ddrescue
[7-zip]: https://www.7-zip.org/download.html
[wincdemu]: https://wincdemu.sysprogs.org/download/
[rsync]: https://linux.die.net/man/1/rsync
[windirstat]: https://windirstat.net/download.html
[qdirstat]: https://github.com/shundhammer/qdirstat/releases/
[grandperspective]: https://grandperspectiv.sourceforge.net/
[dua]: https://github.com/Byron/dua-cli
[dupeguru]: https://github.com/arsenetar/dupeguru/releases
[bitwarden]: https://bitwarden.com/
[web-bitwarden]: https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager/
[veracrypt]: https://www.veracrypt.fr/en/Downloads.html
[gpg4win]: https://gpg4win.org/download.html
[ventoy]: https://github.com/ventoy/Ventoy/releases
[etcher]: https://etcher.balena.io/
[ahk]: https://autohotkey.com/download/
[sxhkd]: https://github.com/baskerville/sxhkd
[karabiner]: https://github.com/pqrs-org/Karabiner-Elements/releases
[espanso]: https://github.com/espanso/espanso
[qalculate]: https://github.com/Qalculate/qalculate-gtk/releases
[anki]: https://apps.ankiweb.net/
[putty]: https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html
[tio]: https://github.com/tio/tio
[kde-connect]: https://kdeconnect.kde.org/download.html
[barrier]: https://github.com/debauchee/barrier/releases
[rectangle]: https://github.com/rxhanson/Rectangle/releases
[alttab]: https://github.com/lwouis/alt-tab-macos
[swift-quit]: https://github.com/onebadidea/swiftquit
[net-3.5]: https://www.microsoft.com/en-us/download/details.aspx?id=25150
[directx]: https://www.microsoft.com/en-us/download/details.aspx?id=35
[msvc-15]: https://learn.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170
[msvc-13]: https://support.microsoft.com/en-us/topic/update-for-visual-c-2013-redistributable-package-d8ccd6a5-4e26-c290-517b-8da6cfdf4f10
[msvc-12]: https://www.microsoft.com/en-us/download/details.aspx?id=30679
[msvc-10]: https://www.microsoft.com/en-us/download/details.aspx?id=26999
[msvc-08]: https://www.microsoft.com/en-us/download/details.aspx?id=26368
[msvc-05]: https://www.microsoft.com/en-us/download/details.aspx?id=26347
[sysinternals]: https://learn.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite
[windows-sdk]: https://developer.microsoft.com/en-us/windows/downloads/windows-sdk/
[itunes]: https://support.apple.com/downloads/itunes
[adb]: https://developer.android.com/studio/releases/platform-tools
[diskspd]: https://github.com/microsoft/diskspd
[crystaldiskinfo]: https://crystalmark.info/en/software/crystaldiskinfo/
[smartmontools]: https://www.smartmontools.org/
[sysbench]: https://github.com/akopytov/sysbench
[nssm]: https://nssm.cc/download
[meshcentral]: https://meshcentral.com/downloads.html
[guacamole]: https://guacamole.apache.org/doc/gug/guacamole-docker.html
[tigervnc]: https://github.com/TigerVNC/tigervnc/releases
[xrdp]: https://github.com/neutrinolabs/xrdp
[steam]: https://store.steampowered.com/about/
[gog]: https://www.gog.com/galaxy
[ds4windows]: https://github.com/Ryochan7/DS4Windows/releases
[retroarch]: https://retroarch.com/?page=platforms
[dolphin]: https://dolphin-emu.org/download/
[nullpomino]: https://github.com/nullpomino/nullpomino/releases
[minecraft]: https://www.minecraft.net/en-us/download
[f-droid]: https://f-droid.org/en/
[termux]: https://f-droid.org/en/packages/com.termux/
[ghost-commander]: https://f-droid.org/en/packages/com.ghostsq.commander/
[cell-bitwarden]: https://play.google.com/store/apps/details?id=com.x8bit.bitwarden&hl=en_US&gl=US
[easer]: https://f-droid.org/en/packages/ryey.easer/
[cell-outlook]: https://play.google.com/store/apps/details?id=com.microsoft.office.outlook&hl=en_US&gl=US
[cell-teams]: https://play.google.com/store/apps/details?id=com.microsoft.teams&hl=en_US&gl=US
[pcapdroid]: https://f-droid.org/en/packages/com.emanuelef.remote_capture/
[ning]: https://f-droid.org/en/packages/de.csicar.ning/
[libretorrent]: https://f-droid.org/en/packages/org.proninyaroslav.libretorrent/
[dns66]: https://f-droid.org/en/packages/org.jak_linux.dns66/
[cell-openvpn]: https://f-droid.org/en/packages/de.blinkt.openvpn/
[cell-wireguard]: https://f-droid.org/en/packages/com.wireguard.android/
[wifianalyzer]: https://f-droid.org/en/packages/com.vrem.wifianalyzer/
[ftpclient]: https://f-droid.org/en/packages/de.qwerty287.ftpclient/
[primitive-ftpd]: https://f-droid.org/en/packages/org.primftpd/
[bettercounter]: https://f-droid.org/en/packages/org.kde.bettercounter/
[calculator-inator]: https://f-droid.org/en/packages/com.inator.calculator/
[audio-recorder]: https://f-droid.org/en/packages/com.github.axet.audiorecorder/
[omweather]: https://f-droid.org/en/packages/org.woheller69.omweather/
[compass]: https://f-droid.org/en/packages/com.bobek.compass/
[markor]: https://f-droid.org/en/packages/net.gsantner.markor/
[acode]: https://f-droid.org/en/packages/com.foxdebug.acode/
[simple-draw-pro]: https://f-droid.org/en/packages/com.simplemobiletools.draw.pro/
[open-note-scanner]: https://f-droid.org/en/packages/com.todobom.opennotescanner/
[semitone]: https://f-droid.org/en/packages/mn.tck.semitone/
[metro]: https://f-droid.org/en/packages/io.github.muntashirakon.Music/
[newpipe]: https://f-droid.org/en/packages/org.schabi.newpipe/
[audible]: https://play.google.com/store/apps/details?id=com.audible.application&hl=en_US&gl=US
[voice]: https://f-droid.org/en/packages/de.ph1b.audiobook/
[cell-vlc]: https://f-droid.org/en/packages/org.videolan.vlc/
[antennapod]: https://f-droid.org/en/packages/de.danoeh.antennapod/
[librera-reader]: https://f-droid.org/en/packages/com.foobnix.pro.pdf.reader/
[spotube]: https://f-droid.org/en/packages/oss.krtirtho.spotube/
[ves]: https://f-droid.org/en/packages/com.vincentengelsoftware.vesandroidimagecompare/
[snapseed]: https://play.google.com/store/apps/details?id=com.niksoftware.snapseed&hl=en_US&gl=US
[track-graph]: https://f-droid.org/en/packages/com.samco.trackandgraph/
[goodtime]: https://f-droid.org/en/packages/com.apps.adrcotfas.goodtime/
[timer-machine]: https://f-droid.org/en/packages/io.github.deweyreed.timer.other/
[ankidroid]: https://f-droid.org/en/packages/com.ichi2.anki/
[open-sudoku]: https://f-droid.org/en/packages/org.moire.opensudoku/
[antimine]: https://f-droid.org/en/packages/dev.lucanlm.antimine/
[cell-retroarch]: https://play.google.com/store/apps/details?id=com.retroarch&hl=en_US&gl=US
[cell-discord]: https://play.google.com/store/apps/details?id=com.discord&hl=en_US&gl=US
[fio]: https://github.com/axboe/fio
[ardour]: https://community.ardour.org/download
[krita]: https://krita.org/en/download/krita-desktop/
[pdftk]: https://www.pdflabs.com/tools/pdftk-server/
[calibre]: https://calibre-ebook.com/download
[thunderbird]: https://www.thunderbird.net/en-US/thunderbird/all/#
[vsc-rest-client]: https://marketplace.visualstudio.com/items?itemName=humao.rest-client
[vsc-vscode-pdf]: https://marketplace.visualstudio.com/items?itemName=tomoki1207.pdf
[voicemeeter-p]: https://vb-audio.com/Voicemeeter/potato.htm
[soundux]: https://github.com/Soundux/Soundux
[blackhole]: https://github.com/ExistentialAudio/BlackHole
[google-maps]: https://play.google.com/store/apps/details?id=com.google.android.apps.maps&hl=en_US&gl=US&pli=1
[cell-brave]: https://play.google.com/store/apps/details?id=com.brave.browser&hl=en_US&gl=US
[cell-firefox]: https://play.google.com/store/apps/details?id=org.mozilla.firefox&hl=en_US&gl=US
[zoomit]: https://learn.microsoft.com/en-us/sysinternals/downloads/zoomit
[playwright]: https://playwright.dev/docs/intro
[rg]: https://github.com/BurntSushi/ripgrep
[rga]: https://github.com/phiresky/ripgrep-all
[buku]: https://github.com/jarun/buku
[web-feedbro]: https://addons.mozilla.org/en-US/firefox/addon/feedbroreader/
[posh-acme]: https://github.com/rmbolger/Posh-ACME
[acmesh]: https://github.com/acmesh-official/acme.sh
[gallery-dl]: https://github.com/mikf/gallery-dl
[cell-onenote]: https://play.google.com/store/apps/details?id=com.microsoft.office.onenote&hl=en_US&gl=US
