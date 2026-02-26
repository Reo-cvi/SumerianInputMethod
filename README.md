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

![QQ20260226-171504-HD (online-video-cutter com)](https://github.com/user-attachments/assets/c38e1148-395f-4ef8-a028-fc5cffcb834b)

**𒅆𒍪𒉈𒉈𒀀 𒊮𒈬𒁀𒄾**

见到你们，我由衷地高兴。

It brings me profound joy to meet you all.

皆様にお会いできて、心より嬉しく存じます。

여러분을 만나 뵙게 되어 진심으로 기쁘게 생각합니다.

C'est avec une joie profonde que je vous accueille ici.

È con profonda gioia che vi incontro.

Es erfüllt mich mit aufrichtiger Freude, euch zu begegnen.
