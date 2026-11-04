<img alt="KALTEC · FG FALCON CARPLAY UNIT · FREE BRACKET" src="https://raw.githubusercontent.com/kalteclabs/.github/main/brand/fg/kaltec-fg-bracket-header.png" width="100%">

### Free 3D print files for the FG and FG MkII FALCON CarPlay bracket. Download, print and fit it yourself, all provided free by KALTEC.

**Jump to:** [Download](#download) · [Filament](#filament) · [Print settings](#print-settings) · [After printing](#after-printing) · [Change it](#change-it)

---

## DOWNLOAD
### The bracket replaces your tissue box (the tray in the dash). No screws, no DIN sleeve: the head unit presses straight in.

<sub>IMAGE COMING SOON: 3D render of the bracket.</sub>

**[Spin the 3D preview](bracket/kaltec-fg-bracket-v1.0.stl)** to see it before you print.

| Where | Link |
| --- | --- |
| GitHub | [Download v1.0](https://github.com/kalteclabs/fg-falcon-carplay-unit/releases/latest) |
| Printables | Coming soon |
| MakerWorld | Coming soon |

| File | Use it for |
| --- | --- |
| `kaltec-fg-bracket-v1.0.stl` | **Start here.** The model, for any slicer. Use the settings below. |
| `kaltec-fg-bracket-v1.0.step` | The CAD file, for changing the design. |
| `kaltec-fg-bracket-v1.0.3mf` | Coming soon: ready to print, with my settings already set. |

> [!TIP]
> Don't have a 3D printer? KALTEC brackets come with the clips already fitted. Kits are coming soon, stick around!

---

## FILAMENT

Print in **PETG or ASA**.

| | PETG | ASA |
| --- | --- | --- |
| Good for | Test fits, and daily use in a shaded cabin | The final bracket. The best finish, and it handles sun and heat best |
| Printing | Easy on any printer, no enclosure needed | Needs an enclosed printer and good ventilation |
| In the car | Softens at about 75–80 °C. If your car sits in the sun or has no tint, use ASA or give it a [UV clear coat](parts-list.md#optional) | Ready as is |

> [!WARNING]
> **Don't print it in PLA.** It softens in a hot car and the bracket sags.

---

## PRINT SETTINGS

Tested on a Bambu Lab H2S with a 0.4 mm nozzle, sliced in Bambu Studio. Start from your printer's standard profile for the filament, then set these.

| Setting | PETG | ASA |
| --- | --- | --- |
| Orientation | Front face (the lip you see in the car) flat on the bed | Same |
| Supports | Off | Off |
| Layer height | 0.2 mm | 0.2 mm |
| Walls | 5 | 5 |
| Top / bottom layers | 5 / 5 | 5 / 5 |
| Infill | 40% gyroid | 40% gyroid |
| Nozzle temp | Profile + 10 °C (250–255 °C) | Your ASA profile |
| Part cooling fan | 30–40% | Your ASA profile's low setting |
| Enclosure | Not needed | Chamber heat on, door shut |
| Print time | TODO | TODO |
| Filament used | TODO g | TODO g |

No supports needed: everything rises straight up or leans less than 45°, and the KALTEC lettering is recessed. Footprint is 225 × 95.8 mm, 58 mm tall. **Print it at 100% scale.** Scaling it changes the fit for the head unit and the clips.

> [!NOTE]
> ASA settings are a starting point, I'm test printing them next. ASA shrinks more than PETG as it cools, so the fit can come out slightly tighter. Check the first print: the unit should push in by hand.

<sub>IMAGE COMING SOON: the bracket on the print bed, front face down.</sub>

---

## AFTER PRINTING

1. Pull it off the plate and clean off any strings.
2. Slide the two plastic Ford interior clips off your tissue box onto the bracket's two tabs at the top corners. Broken clips? They're cheap, see the [parts list](parts-list.md#everyone).
3. Test fit the head unit before it goes in the car. It should press in firmly and stay put.

**Too tight?** That's intended, sanding beats a wiggle. Take off any metal sleeve the unit came with, then sand the **ceiling ribs** inside the bracket a little at a time, then the floor ribs, until it pushes in by hand.
**Too loose?** Add thin inserts or tape inside the bracket so it fits tight.
**Painting or clear coating?** Mask the cutout, the ribs and the tabs first.

<sub>IMAGE COMING SOON: clips fitted on the bracket tabs.</sub>

Ready? Fit it with the [install guide](install-guide.md).

---

## CHANGE IT

Got an odd-sized head unit? Open the STEP file and adjust the bracket to suit. As long as it's single DIN, the rest of the build stays the same.

As designed, the cutout is **179.0 × 52.62 mm**, for a **178 × 51.82 mm** head unit with its sleeve removed. Four ribs on the floor and four on the ceiling grip it top to bottom, with one rib on each side wall.

The bracket design is free to build, change and sell under [CERN-OHL-S-2.0](LICENSE.md). If you share a changed version, credit KALTEC with a link to this repo and release it under the same licence.

---

**KALTEC · CC BY-SA 4.0 · [github.com/kalteclabs/fg-falcon-carplay-unit](https://github.com/kalteclabs/fg-falcon-carplay-unit)**

This guide and its photos are free to share and adapt under CC BY-SA 4.0: credit KALTEC with a link to this repo. The bracket design is free to build, change and sell under CERN-OHL-S-2.0.

FG FALCON SINGLE-DIN Head Unit Free Bracket v1.0
