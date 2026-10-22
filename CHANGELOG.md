# Changelog

## 1.11.0

- Added a unified notification center with persistent history for important failures, including Secret access, exports, automatic sync, and update checks. New failures are easy to review later, while successful and cancelled operations stay quiet.
- Fixed the command tree's Run button so running an already selected command also reopens its closed Run tab.

## 1.10.0

- Improved command editing save responsiveness, with visible save status and a retry option if background saving fails.

## 1.9.9

- Refactor folder pickers.
- Improved keyboard focus and shortcut handling while dialogs are open, including immediate typing in Quick Open.

## 1.9.6

- Added a redesigned Workbench for browsing, running, pinning, and organizing command sessions across tabs and split panes.
- Expanded command reuse with notes for commands and folders, dependency health checks, and richer CLI/MCP run output history and controls.
- Improved command comparison and import/export, including safer compatibility handling and nested folder comparisons.
- Improved path suggestions, startup behavior, and window reliability across the app.
- Improved command and folder editing with consistent layouts, clearer full paths, and more visible keyboard focus.
- Improved keyboard navigation, focus handling, and Escape behavior across dialogs.

## 1.8.0

- Added clearer command and folder pickers for dependencies, Move to, and Copy to, with search and full paths.
- Improved command comparison so matching commands are easier to identify and compare.
- Added command run output access through the CLI, REST API, and MCP, including follow, wait, and history-aware run identifiers.
- Added configurable HTTP and port health checks for command dependencies.
- Improved import and export compatibility with safer relationship handling and clearer diagnostics.

## 1.6.0

- Added safer command and folder management through the CLI and MCP, including path-based folder lookup and dedicated environment management.
- Added Update and Copy modes to import review, so imports can either update existing items by ID or create an independent copy.
- Fixed dependency health checks for commands that were already running before a dependent command started.
- Published separate macOS downloads for Apple Silicon and Intel Macs.

## Unreleased

No changes yet.
