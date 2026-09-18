# Pi for VS Code

[简体中文](README.zh-CN.md)

<p align="center">
  <img src="assets/icon.png" width="128" alt="Pi for VS Code">
</p>

A VS Code extension that brings the [Pi coding agent](https://github.com/earendil-works/pi) into the VS Code Activity Bar.

Pi for VS Code provides a focused sidebar chat for working with Pi while keeping your editor, Explorer, source control, and project context close at hand.

## Screenshots

### Chat

![Pi chat](./assets/screenshots/chat.jpg)

### Session tree

![Pi session tree](./assets/screenshots/session-tree.jpg)

## Features

- Chat with Pi in a dedicated VS Code sidebar.
- Create and switch between persistent Pi sessions.
- Send editor selections and Explorer paths to Pi.
- Queue or steer follow-up prompts while Pi is working.
- Review tool activity, confirmations, questions, and task progress.
- Navigate the Pi session tree and switch to earlier branches.
- Generate Git commit messages from staged changes.
- Follow the VS Code display language.

## Install

Install **Pi for VS Code** from the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=boki.pivs).

You also need a working Pi installation with a configured model and API key.

See the [Pi documentation](https://github.com/earendil-works/pi) for more information.

## Usage

1. Install and configure [Pi](https://github.com/earendil-works/pi), including a model and API key.
2. Install **Pi for VS Code** from the Marketplace.
3. Open the **Pi** view from the Activity Bar.
4. Enter a prompt and submit it to start a session.

Use the Command Palette for these commands:

- `pivs: Open Chat` — Open or focus the Pi chat.
- `pivs: New Session` — Create a separate persistent session.

### Add context

Use the following shortcuts to send context to the chat composer:

- `Ctrl+J` on Windows and Linux, or `Cmd+J` on macOS, from the editor to send the current selection.
- `Ctrl+J` on Windows and Linux, or `Cmd+J` on macOS, from Explorer to send the selected file or folder path.

The same actions are also available from the editor and Explorer context menus.

### Continue while Pi is working

- Press `Enter` to queue a follow-up prompt for after the current response.
- Press `Ctrl+Enter` on Windows and Linux, or `Cmd+Enter` on macOS, to steer the running response.

### Settings

Search for `PiVS` in VS Code Settings to configure notifications, the Pi resource directory, enabled tools, session tabs, interface radius, and AI Git commit behavior.

## Project status

Pi for VS Code is currently in an early stage of development.

The extension is usable, but it is not yet considered mature. Features, behavior, and the user interface may change between releases.

If you encounter a problem or have a suggestion, please open an issue in this repository. When reporting a problem, please include:

- Your VS Code version
- Your operating system
- The extension version
- Your Pi version
- Steps to reproduce the problem

Please do not include API keys, tokens, passwords, or other sensitive information in issue reports.

## Source code

The source code is not publicly available at this time.

This repository currently provides project information, documentation, release updates, and support resources. The source code may be published here in the future, but there is no current commitment or planned release date.

## Disclaimer

Pi for VS Code is an independent project and is not affiliated with or endorsed by the Pi project or its maintainers.
Because Pi supports highly flexible extensions, Pi for VS Code cannot guarantee compatibility with every Pi extension.

## License

The extension is distributed under the [MIT License](LICENSE).
