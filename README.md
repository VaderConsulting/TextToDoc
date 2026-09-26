# TextToDoc

VB6 text-to-Word converter (`TextToDoc.exe`): browse for a `.txt` source and a `.doc` destination, then Create opens the text in Word via Automation (`Word.Application`, hidden) and saves it with `SaveAs` in Word document format, with status shown on the form. Open `TextToDoc.vbp` in the VB6 IDE.

**Source last updated:** 2002-04-09 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `TextToDoc` (`TextToDoc.vbp`) | VB6 | WinForms exe | Convert .txt to .doc via Word Automation |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `TextToDoc.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Common Dialog control (COMDLG32.OCX)
- Microsoft Word installed (late-bound Automation)

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/TextToDoc`.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
