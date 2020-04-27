# Quick Launch VSCode

Adds a button to MacOS Finder to launch the currently-selected directory in VSCode. Saves time versus dragging the directory to VSCode's dock icon or right clicking and selecting "Open With".

## Installation

1. Download [Quick Launch VSCode.app.zip](https://github.com/jasongitmail/quick-launch-vscode/releases/download/v1.0/Quick.Launch.VSCode.app.zip), unzip it, & move into `~/Applications`.
2. In Finder, hold `option command` and drag this app from your Applications directory onto the top bar of Finder. It will add itself as an icon.

## Usage

When using Finder, click this icon to open the currently-selected directory in VSCode.

_Note: When using this the first time, MacOS will prompt you that the application cannot be verified. Visit System Preferences > Security & Privacy, and click "open anyway"._

## Building

If you prefer to build the app yourself:
1. Double click `Quick Launch VSCode.scpt` to open it in Apple's Script Editor.
2. In Script Editor, use File > Export > "as application" and save to `~/Applications`.
3. To add your desired icon, right click on `Quick Launch VSCode.app` that was just created and select "Show Package Contents". Replace `Contents/Resources/droplet.icns` with your desired icons file.
4. Lastly, follow installation instructions above.
