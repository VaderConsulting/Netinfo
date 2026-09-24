# Netinfo

VB6 ConMan network info utility (`Project1.vbp` / Name ConMan) that reports whether LAN/RAS/AOL/proxy/modem paths are alive via `IsNetworkAlive` (Sensapi) and lists IP adapter details (description, MTU, speed, MAC, octets/packets) from the interface table. Open `Project1.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `ConMan` (`Project1.vbp`) | VB6 | WinForms exe | ConMan |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Project1.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `comctl32.ocx`

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Netinfo`.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
