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

Windows will likely show a *"Windows protected your PC"* warning on first run, because the installer is not code-signed. Click **More info → Run anyway**. Code signing requires a paid certificate.

**Requires:** Windows 10 or later, 64-bit.

## Updates

Installed copies check here for new versions and offer them — nothing downloads without you agreeing. Skip a version and it stops asking about that one.

## Releases only

This repository hosts the published builds. The source is not part of it.
