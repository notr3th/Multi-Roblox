# Multi Roblox 🎮🔓

RoViewer is a windows application designed to manage and control multiple Roblox instances. It provides a convenient way to open multiple instances for different accounts and offers a variety of options to manage them efficiently.

[![License][shield-repo-license]][repo-license]
[![Downloads][shield-repo-releases]][repo-releases]
[![Version][shield-repo-latest]][repo-latest]
[![Stars][shield-repo-stargazers]][repo-stargazers]
[![Issues][shield-repo-issues]][repo-issues]
[![Pulls][shield-repo-pulls]][repo-pulls]
[![Forks][shield-repo-forks]][repo-forks]

## Key Features 🌟
- No installation needed with a single file executable.
- Runs in the background with quick access via a system tray icon.
- Supports multiple languages.
- Easily pause and resume mutex with advanced control.
- Shows actions if Roblox is already open and can remember your choice.
- Uses about 3 MB of RAM and 0% CPU.
- Configurable settings saved in the same folder as the .exe file.
- Works with both Bloxstrap and the original bootstrapper.

## Getting Started 🚀
1. Download the `RoViewer.exe` from the [latest release](https://github.com/notr3th/Multi-Roblox/releases/latest).
2. To ensure RoViewer starts automatically with Windows, click <kbd>Win</kbd> + <kbd>R</kbd>, run the path `%ALLUSERSPROFILE%\Microsoft\Windows\Start Menu\Programs\StartUp`, and drop the `RoViewer.exe` file here.
3. Launch `RoViewer.exe`.
### For more detailed instructions see [GETTING_STARTED.md](https://github.com/notr3th/Multi-Roblox/blob/main/GETTING_STARTED.md)

## How It Works ⚙️
Roblox uses a singleton mutex named `ROBLOX_singletonEvent` to ensure that only one instance of the game is running at a time. RoViewer creates this mutex before Roblox does, allowing you to run as many instances of Roblox as you want.

## Is This a Virus? 🛡️
RoViewer is completely safe and not a virus. If you encounter a "Windows Protected Your PC" message, it appears because the application is unsigned, and obtaining a certificate can be costly. You can safely ignore it and run the program anyway. Here's how:

1. **Click on "More info"** in the warning message.
2. **Click on "Run anyway"** to proceed with running RoViewer.

For those who are still skeptical, you can compile the program yourself using [Visual Studio Community](https://visualstudio.microsoft.com/vs/). Alternatively, you can decompile the current executable file to ensure that it is completely safe.

## Is This Bannable? 🚫
RoViewer is not bannable as long as you do not break Roblox's rules. The tool is designed to help running multiple Roblox instances and does not interfere with the game's mechanics or provide any unfair advantages. Always ensure that your usage complies with Roblox's terms of service.

## License 📜
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for using RoViewer! 😊

[shield-repo-license]: https://img.shields.io/github/license/notr3th/Multi-Roblox?style=flat&labelColor=c80064&color=c80064
[repo-license]: https://github.com/notr3th/Multi-Roblox/blob/main/LICENSE

[shield-repo-releases]: https://img.shields.io/github/downloads/notr3th/Multi-Roblox/total?style=flat&labelColor=007ec6&color=007ec6
[repo-releases]: https://github.com/notr3th/Multi-Roblox/releases

[shield-repo-latest]: https://img.shields.io/github/v/release/notr3th/Multi-Roblox?style=flat&labelColor=4c1&color=4c1
[repo-latest]: https://github.com/notr3th/Multi-Roblox/releases/latest

[shield-repo-stargazers]: https://img.shields.io/github/stars/notr3th/Multi-Roblox?style=flat&labelColor=ffd700&color=ffd700
[repo-stargazers]: https://github.com/notr3th/Multi-Roblox/stargazers

[shield-repo-issues]: https://img.shields.io/github/issues/notr3th/Multi-Roblox?style=flat&labelColor=ff4500&color=ff4500
[repo-issues]: https://github.com/notr3th/Multi-Roblox/issues

[shield-repo-pulls]: https://img.shields.io/github/issues-pr/notr3th/Multi-Roblox?style=flat&labelColor=8a2be2&color=8a2be2
[repo-pulls]: https://github.com/notr3th/Multi-Roblox/pulls

[shield-repo-forks]: https://img.shields.io/github/forks/notr3th/Multi-Roblox?style=flat&labelColor=00008b&color=00008b
[repo-forks]: https://github.com/notr3th/Multi-Roblox/network/members
