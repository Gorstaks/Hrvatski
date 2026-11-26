# Hrvatski

Croatian keyboard layout (*Hrvatski raspored tipkovnice*) for Windows, packaged as installers.

## Contents

| File | Description |
| --- | --- |
| `setup.exe` | Installer launcher. Picks the package that matches your system. |
| `Hrvatski_amd64.msi` | Package for 64-bit Windows (x64). |
| `Hrvatski_i386.msi` | Package for 32-bit Windows (x86). |
| `Hrvatski_ia64.msi` | Package for Itanium (IA-64). Not needed on current Windows. |
| `amd64\`, `i386\`, `ia64\`, `wow64\` | The layout DLL (`Hrvatski.dll`) for each platform. |

## Install

1. Run `setup.exe`.
2. Open **Settings > Time & language > Language & region**, open your language's options, and add **Hrvatski** under **Keyboards**.
3. Switch layouts with **Win + Space** or **Alt + Shift**.

If `setup.exe` fails, install the MSI for your architecture directly. On 64-bit Windows use `Hrvatski_amd64.msi`.

## Uninstall

Open **Settings > Apps > Installed apps**, find **Hrvatski** and uninstall it.

## Notes

- Layout installers of this form are the output of Microsoft Keyboard Layout Creator. Installing one writes a keyboard layout DLL to `System32` and registers it, so it needs administrator rights.
- `Releases/0.0.1/Hrvatski.zip` holds the released copy.

## Author

Gorstak
