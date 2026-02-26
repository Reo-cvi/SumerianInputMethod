# Sumerian (ePSD2) IME

A system-level Sumerian Cuneiform Input Method Editor (IME) developed based on the underlying Windows TSF (Text Services Framework) architecture and the ORACC Global Sign List (OGSL).

**Version:** Demo 0.1  
**Platform:** Currently Windows 10 / 11 only. (Stability on other Windows versions is not guaranteed).

## Overview

Written in pure C++, this IME integrates directly into the Windows Language Bar via COM interfaces. It is designed to convert phonetic transliteration input directly into cuneiform signs.

> **Alpha Stage Notice:** > Currently, text output is exclusively supported within `Notepad.exe`.

**Examples:**
* `u4` ➔ `𒌓`
* `szeg3` or `sheg3` ➔ `𒀀𒀭`

## Installation

Download the `.dll` file from the Releases page and register it via the Command Prompt with **Administrator privileges**:

```cmd
regsvr32 SumerianIME.dll
```

## Usage

1.After successful registration, go to Windows Settings and switch your keyboard to Sumerian (ePSD2) IME.

2.Type the phonetic transliteration (e.g., lugal).

3.Press the Space key to complete the transcription into cuneiform.

## Roadmap & To-Do

[x] Bug fixes and existing feature refinement (Ongoing)

[ ] Improved keystroke capture mechanics (In Progress)

[ ] Active candidate window implementation (In Progress)

[ ] Input optimization based on word frequency statistics (TBD)

[ ] Highly customizable IME configurations (TBD)

...and much more.
