# EasyCAD Privacy Policy

**Last updated: 26 September 2026**

## The short version

EasyCAD does not collect anything about you. There are no accounts, no telemetry, no analytics, no crash reporting, no advertising and no third-party tracking. Your models never leave your computer.

The only time EasyCAD talks to the internet at all is to check whether a newer version has been released, and even that is absent from the Microsoft Store edition.

## What EasyCAD stores on your computer

Everything EasyCAD saves stays on your machine. Nothing here is uploaded anywhere.

| What | Where | Why |
| --- | --- | --- |
| Your projects (`.ecad`) | Wherever you choose to save them | Your work |
| Exported models (`.stl`, `.obj`) | Wherever you choose to export them | Your work |
| Recovery file | `%APPDATA%\easycad\recovery.json` | A copy of unsaved work, so a crash or power cut does not lose it. It is deleted as soon as you save, or start/open another project |
| Update preference | `%APPDATA%\easycad\update-prefs.json` | Remembers which version you chose to skip, so you are not asked again |
| Window and graphics cache | `%APPDATA%\easycad\` | Standard Chromium/Electron cache files |

You can delete the `%APPDATA%\easycad` folder at any time. EasyCAD will simply start fresh.

## What EasyCAD reads from your computer

- **Files you explicitly open or import.** Projects you open and STL meshes you import are read only when you choose them through a file dialog.
- **Fonts installed on your system**, from `C:\Windows\Fonts` and `%LOCALAPPDATA%\Microsoft\Windows\Fonts`. This is how the Text shape is built from real typeface outlines. The font files are read locally to draw shapes, and are never uploaded or copied anywhere.

EasyCAD does not scan, index or read any other part of your disk.

## The one network connection

A few seconds after launch, EasyCAD checks whether a newer version has been published. This is the only outbound connection it makes.

- **What is sent:** an ordinary HTTPS request for a small text file listing the current version. It contains no identifier, no account, no model data, no file names, and no information about how you use the app.
- **Who receives it:** GitHub, which hosts the releases. As with visiting any website, GitHub necessarily sees your IP address and browser-style user agent in order to respond. That is handled under [GitHub's Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement). EasyCAD's developer receives nothing and sees nothing.
- **If a new version exists,** you are told and asked. Nothing is downloaded unless you choose **Download**.
- **If you are offline,** the check quietly fails and the app carries on as normal.
- **Microsoft Store edition:** makes no version check at all. Updates are delivered by the Microsoft Store, so the app never contacts GitHub.

## What EasyCAD never does

- No analytics, usage statistics, telemetry or crash reporting
- No user accounts, sign-in or registration
- No advertising, no tracking pixels, no third-party SDKs
- No uploading of your models, measurements or files, ever
- No selling or sharing of personal data — none is collected, so there is none to sell or share

## Children

EasyCAD collects no personal information from anyone, of any age, including children under 13 (and under 16 in the UK/EU).

## Your rights

Data protection laws such as the UK GDPR, EU GDPR and CCPA give you rights to access, correct, export or delete personal data a company holds about you. EasyCAD's developer holds no personal data about you, so there is nothing to retrieve or erase. Your project files are yours and are already entirely in your hands.

## Changes to this policy

Any change will be published on this page with an updated date. If a future version of EasyCAD ever collects anything, that will be stated here plainly and before the fact.

## Contact

Questions about this policy can be raised at
<https://github.com/2FOUR7-4x4/easycad/issues>.
