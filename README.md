# Structural Framing for Autodesk Fusion 360

[![Download the latest release](https://img.shields.io/github/v/release/sylvanoMTL/fusion360-structural-framing-releases?label=Download&style=for-the-badge)](https://github.com/sylvanoMTL/fusion360-structural-framing-releases/releases/latest)

**[Download the latest release](https://github.com/sylvanoMTL/fusion360-structural-framing-releases/releases/latest)**
(open the release, then click the `StructuralFraming-Setup-….exe` file under *Assets*)
· [Product page](https://www.mecafrog.com/f360-addins/structural-framing/index.html)
· [Download guide](https://www.mecafrog.com/f360-addins/structural-framing/download.html)
· [Pricing](https://www.mecafrog.com/f360-addins/structural-framing/pricing.html)

This repository holds the **installers** of the Structural Framing add-in, published by
[mecafrog.com](https://www.mecafrog.com/f360-addins/structural-framing/index.html).
It contains no source code.

## What it does

Structural Framing brings aluminium extrusion, weldment and timber framing into one
Fusion 360 workflow:

1. **Design the frame** with sketch lines or model edges.
2. **Choose the profile.** The add-in creates and orients the beam components along the
   geometry you picked.
3. **Assign the manufacturing details:** joints, machining, connectors and weld beads. The
   frame stays organised as ordinary Fusion 360 components.
4. **Generate the cut list:** lengths, quantities and the available profile information.

Change a profile or resize the design, then edit and refresh: no need to rebuild the frame.

## Free and paid

**Free for personal use.** No account, no licence key, no trial period, and it does not
expire. The free tier includes, within the free project limits:

- generic and V-Slot aluminium profiles,
- a starter weldment set (six generic tube sizes and one IPE 80 steel I-beam),
- a generic timber set.

**Pro modules** are licensed separately, one per framing type (Aluminium Extrusion,
Weldment, Wood Framing). They raise the project limits and add larger or
manufacturer-specific profile libraries, for example the Bosch Rexroth library (from
MGE 15) with part numbers, finishes and connection holes in Aluminium Extrusion Pro.

What each module includes today, packages and prices are on the
[pricing page](https://www.mecafrog.com/f360-addins/structural-framing/pricing.html).
A purchased licence is activated inside the add-in, from **Settings**.

## Requirements

- Windows 64-bit. There is no macOS build.
- Autodesk Fusion 360, current release recommended.
- No administrator rights: it installs for the current user only.

## Install

1. **Close Fusion 360.** The installer stops if Fusion is still running.
2. Download `StructuralFraming-Setup-<version>-nsis.exe` from the
   [latest release](https://github.com/sylvanoMTL/fusion360-structural-framing-releases/releases/latest)
   and run it.
3. Start Fusion 360 and accept the licence agreement when asked.
4. The **Structural Framing** tab appears on the toolbar. If it does not, open
   **Utilities › Scripts and Add-Ins › Add-Ins**, select **Structural Framing**, click
   **Run** and tick **Run on Startup**.

> **Windows will warn you: this is expected.** The installer is not code-signed yet.
> - Your browser may say the file "isn't commonly downloaded": in the downloads list, open
>   the **…** menu on the file and choose **Keep**, then **Keep anyway**.
> - Windows may say "Windows protected your PC": click **More info**, then **Run anyway**.
>
> If **Smart App Control** is switched on in Windows 11, Windows can block the installer
> with no *Run anyway* option. Read the
> [download guide](https://www.mecafrog.com/f360-addins/structural-framing/download.html)
> before buying a licence.

## Updates

Nothing updates by itself. To check for a newer version, open **Settings › About ›
Check for Updates** in the add-in: it compares your version with the latest release here
and offers to open its page.

To upgrade, close Fusion 360 and run the new installer over the old one; there is no
need to uninstall first. Your preferences, logs and licence are kept.

## Uninstall

Close Fusion 360, then remove **Structural Framing for Fusion 360** from
**Windows › Apps & features**. Moving to another computer? Deactivate your licence first
in **Settings › Licence › Deactivate**, or contact us and we will free it for you.

## Help and feedback

- **Report a bug or suggest an improvement:** the
  [feedback page](https://www.mecafrog.com/f360-addins/structural-framing/feedback.html),
  also opened by the **Send Feedback** button in the add-in's Settings panel.
- **E-mail:** [info@mecafrog.com](mailto:info@mecafrog.com). Include your add-in version
  (shown in **Settings › About**), the command, what happened and what you expected.

## Licence

Structural Framing is commercial software. Using it means accepting the
[licence agreement (EULA)](https://www.mecafrog.com/f360-addins/structural-framing/eula.html).
See also the [privacy policy](https://www.mecafrog.com/f360-addins/structural-framing/privacy).

---

Structural Framing is not affiliated with, endorsed by, or sponsored by Bosch Rexroth AG.
Bosch Rexroth and MGE are trademarks of their respective owners, used here only to
identify genuine parts.
