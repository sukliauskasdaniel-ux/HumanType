# HumanType

A lightweight Windows app that types your text into other applications at a natural, adjustable pace.

HumanType retypes your text—it does not rewrite or paraphrase it.

## Features

- Adjustable typing speed and natural pauses
- Optional typing mistakes with automatic backspace corrections
- Four profiles: Average, Relaxed, Fast, and Accurate
- Built-in typing preview
- Import UTF-8 `.txt` files
- Copy or save completed previews
- Pause, resume, and stop using keyboard shortcuts
- Automatically remembers your typing preferences

## Requirements

- Windows 10 or Windows 11
- 64-bit Windows

No installation or additional software is required.

## Download

1. Open this repository’s **Releases** section.
2. Download **HumanType-2.0.0-Windows-x64.zip** under **Assets**.
3. Extract all files.
4. Open **HumanType.exe**.

## How to use

1. Paste your text into the source box or select **Open .txt**.
2. Choose a profile or customize your settings.
3. Select **Preview here** to try it inside HumanType.
4. Select **Start typing into another app**.
5. Click the destination text field during the countdown.

The default settings are **40 WPM**, **2% mistakes**, and a **5-second countdown**, with corrections and natural pauses enabled. Set mistakes to **0%** for accurate typing.

## Keyboard shortcuts

| Key | Action |
| --- | --- |
| F7 | Pause or resume an active run |
| F8 | Stop an active run |
| Ctrl+O | Import a text file |

Switching to another window automatically pauses typing. Return to the original destination, click the intended text field, and press **F7** to resume.

## Tips

Try a new Notepad document first. Enter and Tab can submit forms, send messages, or move focus in other applications.

Editors with autocorrect or automatic formatting may change the resulting text. Some protected applications may reject simulated typing.

## Settings

Typing preferences are saved in:

`%APPDATA%\HumanType\settings.json`

Pasted and preview text are not saved automatically between launches.

## Feedback

Report bugs or suggest improvements through this repository’s **Issues** section.
