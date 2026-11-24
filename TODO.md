# TODO

Everything unfinished in this repo, as of 24 November 2026. Each item matches a `> **TODO (…):**` marker in the file listed, except where it says "outside the repo". Delete the marker when the item is done.

**Order from here:** finish the repo, then update the MakerWorld and Printables listings, then the instruction images, then rebuild the PDF last with all the photos in it.

## Gaps to fill

| # | File | What's needed | Who supplies it |
| --- | --- | --- | --- |
| 1 | README.md (Download the bracket) | Confirm the Printables listing is live and the link is right | Aaron |
| 2 | README.md (Download the bracket) | Paste the MakerWorld and Printables descriptions so they can be matched to this copy, and switch the MakerWorld print profile to ASA (after the repo is done) | Aaron pastes, repo project rewrites |
| 3 | README.md (Kits and parts) | Photos: the wireless head unit (only once DOMAIN confirms it's available) and the carbon fibre finish bracket | Aaron (wireless photo waits on DOMAIN) |
| 4 | Outside the repo: photos | Better cigarette power lead photos, to replace `kit-parts-cig.jpg`, `cig-harness.jpg` and the `cig-lead*.jpg` set | Aaron |
| 5 | install-guide.md (top) | Video links for the install guide (cigarette power and fuse tap power) | Aaron |
| 6 | kit-guide.md (every step) | A video for each of the 8 steps (each step has `> **Video:** coming soon`) | Aaron |
| 7 | kit-guide.md (header) | A kit guide header image (uses the main repo header for now) | Aaron |
| 8 | kit-guide.md (step 4) | How a buyer tells the ALWAYS ON tap from the KEY ON tap (no labels in the photos), and which fuse values ship in each tap | Aaron |
| 9 | kit-guide.md (help) | aaron@kaltec.au as the main contact (being set up now) | DOMAIN |
| 10 | Outside the repo: the `kaltec.au/guide` redirect | Point `kaltec.au/guide` (the QR card in the box) at `kit-guide.md` on GitHub, in Cloudflare (being set up now) | DOMAIN |
| 11 | install-guide.md (bottom) | Rebuild the install guide PDF last, with the photos, and attach it to a new release with both 3MFs (ASA `kaltec-fg-bracket-v1.0.3mf` and `kaltec-fg-bracket-v1.0-petg.3mf`), the STL and the STEP. The current v1.1 PDF has the old copy | Repo project |
| 12 | Outside the repo: v1.1 release notes | Still have the old fitment line, old kit price and old contact email. Replace on the next release (draft below) | Repo project, with Aaron's OK |

### Draft release notes for the next release (item 12)

> The full install guide as a one-click A4 PDF, plus the new kit guide for KALTEC kit owners.
>
> - A4 install guide PDF: cigarette power (about 10 minutes) and fuse tap power (about 30–45 minutes), parts list with links, fuse box layout, troubleshooting, and the free bracket print settings.
> - Bracket model unchanged (v1.0): STL and STEP, plus Bambu Studio projects for ASA (recommended) and PETG, all attached here.
>
> FG, MkII and FG-X. Not FPV.
> Ready-made kits: [kaltec.au](https://kaltec.au) · [preorder@kalteclabs.com](mailto:preorder@kalteclabs.com)
>
> Guides and images: CC BY-SA 4.0. Bracket: CERN-OHL-S-2.0.

## The launch switch

Do all of this in one edit when DOMAIN says the full kaltec.au site with checkout is live:

- [ ] Delete the A$20-off line everywhere it appears. It's only in `README.md`: the "Rather not build it?" tip near the top, and the "A$20 off before launch" paragraph in Kits and parts.
- [ ] In `README.md`, make the Kits and parts table link to kaltec.au to buy (each product name or a "Buy" column linking to its kaltec.au page), and drop "Kits are ready from 1 December 2026".
- [ ] In `kit-guide.md`, switch the help contact to aaron@kaltec.au if it's live (item 9).
- [ ] Bump the README footer version and date.
