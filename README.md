# PerfectScreenShot

English | [한국어](README.ko.md)

![PerfectScreenShot logo](assets/logo.png)

A free Windows screenshot tool. Capture an area, add annotations, and copy or save the result.

**[Download v2.1.0 for Windows x64](https://github.com/lbs-twtt/PerfectScreenShot-Releases/releases/download/v2.1.0/PerfectScreenShot-v2.1.0-Windows-x64.zip)** · [Release notes](RELEASE_NOTES.md) · [Report an issue](https://github.com/lbs-twtt/PerfectScreenShot-Releases/issues)

v2.1.0 is a **preview release**. Scrolling capture is experimental: its complete automatic-capture-to-save workflow in Chrome/NAVER has not yet been verified. Check the preview before using a scrolling-capture result.

## New in v2.1.0

- Open recent captures with **Ctrl+Alt+V**. Select an image for a larger preview; use **Fit**, **100%**, or **Ctrl+mouse wheel** to inspect it.
- **Delete selected** removes one capture; **Delete all** asks for confirmation. Saved files and clipboard content are unchanged.
- **Edit** opens the selected image with the existing annotation tools. **Finish editing** keeps the result as a new recent capture without copying or saving a file. Copy/save/pin also retain the edited result.
- The original is kept subject to the normal limit of 10 captures. Repeated outputs from the same edit session update that session's entry. Earlier annotations are part of the image; you can add new marks or crop it.
- **Ctrl+Enter** finishes editing. While typing text, it first finishes the text entry. **Esc** or the editor's close button discards changes made since the last output.

## Get started

1. Download the application ZIP above. Windows 10/11 **64-bit (x64)** is supported.
2. Extract the entire ZIP to a folder, keeping the included `licenses` folder. If another version is running, exit it first.
3. Run `PerfectScreenShot.exe`. No separate .NET installation is needed.
4. Press **Ctrl+Alt+S**, select an area and annotate it. Press **Enter** to copy and finish, then **Ctrl+V** to paste elsewhere. Use **Ctrl+S** to save a PNG or JPG file.

GitHub's automatic **Source code (zip/tar.gz)** downloads contain this repository's documentation, not the application. Choose the named application ZIP instead.

Closing the welcome window keeps the program running in the Windows notification area. Use **Exit** to quit completely. Automatic launch with Windows is optional and OFF by default.

## Main features

- Rectangle, window, full-screen and freehand selection, including multiple monitors.
- Arrows, boxes, ellipses, lines, pen, highlighter, text, mosaic, solid redaction and numbered markers.
- Editable text boxes with background color, bold, italic and underline.
- Movable editing toolbar, precision magnifier and adjustable crosshairs.
- Copy to clipboard, save as PNG/JPG, or pin a capture above other windows.
- Optional history of the 10 most recent captures, with thumbnail selection.
- Korean and English interfaces, built-in help and offline third-party notices.

By default, **left-button selection opens the editor** and **right-button selection copies immediately without editing**. The selection menu's **Swap mouse buttons** button reverses these roles. Quick copy copies to the clipboard; it does not save a file.

## Useful shortcuts

These are the defaults. Most capture/tool shortcuts can be changed in Settings.

| Action | Shortcut |
|---|---|
| Start capture | Ctrl+Alt+S |
| Recent captures | Ctrl+Alt+V |
| Rectangle / Window / Full screen / Freehand | 1 / 2 / 3 / 4 during selection |
| Select / Arrow / Box / Text | V / A / R / T |
| Increase / decrease line width or text size | Repeat the tool key / Shift+tool key |
| Bold / Italic / Underline in text mode | Ctrl+B / Ctrl+I / Ctrl+U |
| Copy and finish / Copy and continue editing | Enter / Ctrl+C |
| Save file / Pin on screen | Ctrl+S / F2 |
| Undo / Redo | Ctrl+Z / Ctrl+Y |
| Change crosshair size / Magnifier zoom | F1 / Ctrl+wheel during selection |
| Cancel current action or close an idle capture | Esc |

While typing text, **Enter adds a line** and **Ctrl+Enter finishes typing**. Letter shortcuts do not interrupt text input.

## Language

In Settings, choose **Auto / 한국어 / English**. Auto uses Korean when the Windows display language is Korean, and English otherwise. **Save the setting, fully exit and reopen the app** to apply the change. Translations work offline; your annotations and filenames are not translated.

## Experimental scrolling capture

Choose **Scrolling capture**, select a visible window, and set the number of screens to keep (default 5, range 1–20). The app scrolls down, captures up to one extra screen and discards that extra last screen. Then choose the top and bottom boundaries in the preview and copy or save the selected range. **Esc** stops collection.

Automatic stitching can misalign or repeat content, especially with fixed banners, popups or moving content. Excluding the extra last screen does not repair earlier overlaps. Review the full preview; the complete Chrome/NAVER workflow remains unverified.

## Free use and privacy

PerfectScreenShot is free to use. Basic capture, editing and saving take place on your PC without an account or Internet connection. The app does not separately collect captured images or personal information, or automatically send them to external servers.

Recent-capture history is optional and can be turned ON/OFF from the welcome screen or Settings. When ON, up to 10 images are kept temporarily **in your PC's memory**, not as history files on the drive. Larger images use more memory. Turning the option OFF clears the list; exiting or restarting also clears it. Files you saved and images copied to the Windows clipboard may remain independently.

Read bundled component licenses in **Settings → About → Open-source information**, or in the included `licenses` folder. [Third-party notices](licenses/README.md) apply to those components; they do not grant an open-source license to PerfectScreenShot itself.

## Feedback

[Open an issue](https://github.com/lbs-twtt/PerfectScreenShot-Releases/issues) with the app version, Windows version/display scaling, and steps to reproduce the problem. This is a public issue tracker; remove personal or sensitive information from screenshots before attaching them.
