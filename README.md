# cmdbook

cmdbook is a desktop command launcher for people who work in the terminal.
Keep your frequently used commands in folders, run them with one click, and
watch their output in an integrated terminal.

## Features

- Organize commands into folders
- Run commands with a configurable working directory and environment
- Interactive terminal output with ANSI colors and stdin support
- Stop running commands from the app
- Pre-run and post-run scripts
- Command variables and environment presets
- Search, keyboard shortcuts, and quick access to frequently used commands
- Optional schedules, health checks, notifications, and HTTP capture
- Import and export your command collection as JSON

## Download

Download the latest release for your platform from
[GitHub Releases](https://github.com/printfapp/cmdbook/releases/latest):

| Platform | Package |
| --- | --- |
| macOS (Apple Silicon and Intel) | `.dmg` |
| Windows 10/11 | `.exe` or `.msi` |
| Linux x64 | `.AppImage` or `.deb` |

cmdbook is currently distributed as pre-built desktop installers. No Node.js,
Rust, or other runtime dependencies are required to use the released app.

### First launch

- **macOS:** If macOS shows a Gatekeeper warning, right-click the app and
  choose **Open**.
- **Windows:** If SmartScreen appears, choose **More info** and then
  **Run anyway** when you trust the downloaded release.
- **Linux:** Make the AppImage executable before launching it:
  `chmod +x cmdbook_*.AppImage`

## Feedback and bug reports

Please [open an issue](https://github.com/printfapp/cmdbook/issues/new/choose)
with your platform, cmdbook version, and steps to reproduce the problem.
For Windows process and terminal issues, including the diagnostic log from
cmdbook's data directory is especially helpful.

## License

Proprietary software. This repository contains release binaries only. Use and
distribution are subject to the proprietary terms stated by the publisher.
