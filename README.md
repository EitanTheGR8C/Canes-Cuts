# Canes Cuts

Typed with the wrong keyboard layout? Select the text and press **Alt+Shift** to convert it between your chosen pair of layouts. For example, `akuo` typed on an English layout becomes `שלום` with the Hebrew layout.

Canes Cuts maps keyboard positions, not meanings. It is not a translation tool. It uses copy and paste to replace selected text, so behavior depends on the app you are typing in.

## Download

1. Open the [latest release](https://github.com/EitanTheGR8C/Canes-Cuts/releases/latest).
2. Download **CanesCuts-Setup.exe** to install the app, or **CanesCuts.exe** to run it without installation.

Windows may show a security warning for new app downloads. Check that the file came from this repository's release page.

## Install or update

1. If Canes Cuts is already running, right-click its tray icon and choose **Quit**.
2. Run **CanesCuts-Setup.exe**.
3. Choose **Install for me only (recommended)** and finish the wizard.
4. Launch Canes Cuts from the Start menu.

You can uninstall it from Windows Settings > Apps.

## Run without installing

Quit any running copy, then double-click **CanesCuts.exe**.

## Use it

1. Check that the status shows **Running** with a green dot. If it says Stopped, click **Start**.
2. Pick your two languages. Ten are available: English, Hebrew, Arabic, Spanish, Russian, German, French, Greek, Italian and Portuguese. Your choice applies right away; the app starts with Hebrew and English again on the next launch.
3. Select the mistyped text, then press and release **Alt+Shift**. Canes Cuts attempts to replace the selection with the converted text and restore your earlier clipboard content afterward.
4. Closing the window keeps the shortcut running in the system tray. Right-click the tray icon to reopen the window or choose **Quit** to exit.

Pressing **Esc** does not stop the shortcut listener.

Always select text first. Without a selection, some editors copy the current line instead, and clipboard restoration may be skipped if the target app changes the clipboard.

## Clipboard behavior and limits

- Restoration supports plain text, HTML/RTF formatted text and Windows DIB images. It is best effort, not a backup.
- Copied files and unsupported clipboard formats are not preserved. Keep important clipboard content elsewhere before using the shortcut.
- Avoid copying anything else during a flip. The app checks for clipboard changes before restoring in the normal path, but that check is not a guarantee against overwriting a newer copy.
- Canes Cuts marks its own clipboard writes to stay out of Windows clipboard history (**Win+V**) and cloud clipboard sync. The selection copied from the target app during a flip may still appear in history.

## Notes

- For Windows. A Mac version is planned.
- No account needed; works offline.
- This repository is for downloads. It does not contain the app's source code.
