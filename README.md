# cmdbook

cmdbook helps you save and run the command-line work you repeat.

Shell history remembers what you typed. cmdbook keeps the command with the
working directory, variables, prompts, and other setup it needs, so you can
find it and run it again without rebuilding the context.

- [Website](https://printf.app/cmdbook/)
- [Watch the demo](https://youtu.be/Gk1C4Pjz03g)
- [Download the latest release](https://github.com/printfapp/cmdbook/releases/latest)

## Quick start

1. Open cmdbook and create a command.
2. Enter the command you run repeatedly, such as `git status` or a build script.
3. Set its working directory and add variables or prompts when the command
   needs them.
4. Run it from the command tree.
5. Find it again in its folder or with search instead of reconstructing it
   from shell history.

cmdbook does not replace your terminal. Use your normal terminal for ad-hoc
sessions; use cmdbook for commands and scripts you want to save, organize, and
run again.

## What you can do

- Organize commands into folders.
- Keep working directories, variables, prompts, and hooks with commands.
- Run interactive commands and send input to them.
- Keep long-running commands in one place and inspect their output.
- Search commands and use keyboard shortcuts.
- Add Quick Access entries for related URLs, files, or applications.
- Import and export your command collection as JSON.
- Run on macOS, Windows, and Linux.

The Free plan covers the core command workflow. Pro adds advanced workflow
features such as automations, command dependencies, remote run, and other
features listed on the [website](https://printf.app/cmdbook/#pricing).

## Download

Download the latest release for your platform from
[GitHub Releases](https://github.com/printfapp/cmdbook/releases/latest).

| Platform | Package |
| --- | --- |
| macOS Apple Silicon | `aarch64` DMG |
| macOS Intel | `x64` DMG |
| Windows 10/11 | `.exe` or `.msi` |
| Linux x64 | `.AppImage` or `.deb` |

The macOS Apple Silicon and Intel packages are separate downloads. Choose the
one that matches your Mac. Released installers do not require Node.js, Rust, or
another runtime.

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
