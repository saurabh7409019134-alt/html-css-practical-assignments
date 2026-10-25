# Task 2 — Setup verification checklist

This is a prepared checklist, not proof that software is installed. Run the checks on your computer and capture your own screenshots.

## Check VS Code

- Open Visual Studio Code and confirm the application launches.
- In the integrated terminal, run `code --version` if the command is available. If it is not, record that and verify the version from **Help → About** (macOS: **Code → About Visual Studio Code**).
- Screenshot: the VS Code window with **About** open, plus the project folder visible in Explorer.

## Check Node.js and npm

Run `node --version` and `npm --version`. Each should print a version number. If the shell says the command is not found, install the current LTS version from the official Node.js site and reopen the terminal.

- Screenshot: terminal showing both commands and their actual output.

## Check Live Server

- In VS Code Extensions, search for **Live Server** and verify the extension is installed and enabled.
- Open an HTML practical, right-click and choose **Open with Live Server** (or use **Go Live** in the status bar).
- Confirm the page opens in a browser at a local address and that editing/saving the HTML refreshes the page.
- Screenshot: browser page and local address, with the VS Code Live Server status visible if possible.

Keep screenshots in `assets/screenshots/`. Do not include passwords, tokens, or private browser data.
