# Things Quick Entry for Helium browser
A Chrome extension that sends the current tab's title and URL to **Things 3** for Mac. This is meant for users of [Helium](https://helium.computer/) and Ungoogled Chromium browsers.

## Why this exists
Helium does not have an AppleScript interface so that Autofill can access a selection within it. Specifically, the developers need to support linking to objects in the app via URLs: for example, Mail uses message:// and Safari uses http:// or https://. This extension bypasses that by using the official `things:///add` URL scheme to ensure your tasks always include the page title and link.

## Features
- **One-Click Entry:** Send any webpage to your Things Inbox instantly.
- **Pre-filled Data:** Automatically sets the task title to the webpage title and the notes to the URL.
- **Customizable Shortcut:** Defaulted to `Ctrl+T`. This can be mapped to the default ⌃⌥␣ via [BetterTouchTool](https://folivora.ai/).
- **Manifest V3:** Modernized for long-term compatibility and performance.

## Installation
Currently, this is a personal fork. To install it:
1. Download the repo and extract the zip file.
2. Open the extensions page, `helium://extensions/`.
3. Click **Load unpacked** and select the extracted folder.

## Configuration
You can adjust behavior in the extension options.
- **Show Quick Entry:** Toggle whether the Things Quick Entry dialog appears or if the task is sent silently.
- **List selection** Choose where the task should appear (Inbox, Today, etc.) when Quick Entry dialog is set not to be shown.
- **Select newly created task:** Choose whether to highlight/select the newly created task in Things 3 or not. Things window will still become active regardless of this setting.

Put together with Claude by **Sridhar Katakam**.

## License
This project is licensed under the **Mozilla Public License 2.0**. See the `LICENSE` file for details.
