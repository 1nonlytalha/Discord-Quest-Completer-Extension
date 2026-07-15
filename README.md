<p>
  <h1 align="center">Discord Quest Completer</h1>
</p>

![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/TALHA/discord-quest-completer/rust-check.yml?branch=main&style=flat&label=build%20artifacts)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/TALHA/discord-quest-completer/build-release.yaml?branch=main&style=flat&label=build%20(release))

> A quest completer for Discord. Discord Quest Completer. I don't know what to call this, but there it is.

A Windows desktop application for Discord Rich Presence and completing Discord Quest for games without needing to install the full actual games/applications. Perfect for completing Discord Quests and showing off your gaming status without the storage burden.

---

## 📥 Installation

### Windows

You can download manually pre-built release binaries on the [Releases](https://github.com/TALHA/discord-activity/releases) page.

Alternatively, you can follow the [development setup instructions](#-development-setup) to build the app from source.

> [!IMPORTANT]
> Make sure you place or extract in a location where you have write or execute permissions.
> 
> The reason for this is that the app will create dummy game file in the same directory.
> By default, the app will not need to be run as administrator, unless if it was installed in a directory that requires elevated permissions. (e.g. `C:\Program Files\`, root of `C:\`, etc.)


> [!NOTE]
> Webview2 is required to run the app. WebView2 comes preinstalled on Windows 11. On versions older than Windows 11 you may need to install it manually.
> If you don't have it installed, you can download it from [here](https://developer.microsoft.com/en-us/microsoft-edge/webview2).


## Uninstall

To uninstall the app, simply go to the folder where you extracted or placed the app and delete it's folder and thats it.

The content of the folder may look like this:

```text
discord-quest-completer/
├── discord-quest-completer.exe (main app)
├── data/ 
│   ├── src-win.exe (runner dummy template)
├── games/
│    ├── <game-id>/
