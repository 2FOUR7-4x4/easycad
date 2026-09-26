# EasyCAD

A Tinkercad-style 3D solid modelling editor for Windows that runs entirely on your PC. No account, no cloud, no subscription.

**[⬇ Download the latest release](https://github.com/2FOUR7-4x4/easycad/releases/latest)**

---

## What it does

Build solid models by dropping shapes on a workplane and combining them — the way Tinkercad works, but local.

- **Eleven shapes** — box, cylinder, sphere, half sphere, cone, pyramid, torus, wedge, roof, tube and text
- **Solid and Hole** — mark any shape a hole, group it with a solid, and it cuts. Bolt holes, slots, pockets
- **Ungroup puts it back** exactly as it was, so grouping is never a one-way door
- **Tape measure** that snaps to real features — corners, edge midpoints, face centres — and reports distance plus per-axis ΔX/ΔY/ΔZ
- **Ruler** you plant on the workplane, after which positions read as offsets from it
- **Align, mirror, duplicate**, marquee select, full undo/redo
- **Text** extruded from any TrueType font installed on your machine
- **STL and OBJ export**, STL import

Everything is in millimetres with Z up — the conventions a slicer expects.

## Not losing work

Closing with unsaved changes asks first. Separately, every edit is autosaved to a recovery file, so if the app is killed or the machine loses power, the next launch offers your work back.

## Installing

Download **`EasyCAD Setup x.y.z.exe`** from the [latest release](https://github.com/2FOUR7-4x4/easycad/releases/latest) and run it.

A **portable** build is also published if you would rather not install — it runs straight from the exe, though it starts slower because it unpacks itself each time.

### If Windows blocks it

The installer is not yet code-signed, so Windows may object in one of two ways:

**"Windows protected your PC"** — this is SmartScreen. Click **More info → Run anyway**.

**Smart App Control blocks it outright**, with no "Run anyway" option. This is a different, stricter feature than SmartScreen and there is genuinely no per-app override.

You have two choices:

- **Wait for the Microsoft Store release**, which is signed by Microsoft and installs normally. This is the better option and it is being worked on.
- **Turn Smart App Control off temporarily**, install, then turn it back on. On current Windows 11 this is reversible — Microsoft added the ability to toggle SAC without a clean install in KB5079391 (26 March 2026). It is under Settings › Privacy & security › Windows Security › App & browser control › Smart App Control settings. If your Windows predates that update the switch is still one-way, so check your build first.

Signing is being sorted out. Until then, you can verify your download is genuine by checking it against `SHA256SUMS.txt` on the release:

```powershell
Get-FileHash .\EasyCAD-Setup-1.0.0.exe -Algorithm SHA256
```

**Requires:** Windows 10 or later, 64-bit.

## Updates

Installed copies check here for new versions and offer them — nothing downloads without you agreeing. Skip a version and it stops asking about that one.

## Releases only

This repository hosts the published builds. The source is not part of it.
