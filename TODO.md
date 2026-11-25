# TODO

Everything unfinished in this repo, as of 24 November 2026. Each item matches a `> **TODO (…):**` marker in the file listed, except where it says "outside the repo". Delete the marker when the item is done.

**Order from here:** finish the repo, then update the MakerWorld and Printables listings, then the instruction images, then rebuild the PDF last with all the photos in it.

## Gaps to fill

| # | File | What's needed | Who supplies it |
| --- | --- | --- | --- |
| 1 | README.md (Download the bracket) | Confirm the Printables listing is live and the link is right | Aaron |
| 2 | README.md (Download the bracket) | Paste the MakerWorld and Printables descriptions so they can be matched to this copy, and switch the MakerWorld print profile to ASA (after the repo is done) | Aaron pastes, repo project rewrites |
| 3 | README.md (Kits and parts) | Photos: the carbon fibre finish bracket and the wireless head unit, both ready 1 December | Aaron (wireless photo waits on DOMAIN) |
| 4 | install-guide.md (top) | Video links for the install guide (cigarette power and fuse tap power) | Aaron |
| 5 | kit-guide.md (every step) | A video for each of the 8 steps (each step has `> **Video:** coming soon`) | Aaron |
| 6 | Outside the repo: kalteclabs/.github | Upload the 7 new kit guide photos to `fg-falcon-carplay-unit/images/` before the kit guide update is pushed (`fuse-lead-ends.jpg` replaces the old one) | Aaron |
| 7 | Outside the repo: the `kaltec.au/guide` redirect | Point `kaltec.au/guide` (the QR card in the box) at `kit-guide.md` on GitHub, in Cloudflare (being set up now) | DOMAIN |
| 8 | install-guide.md (bottom) | The repo PDF (`kaltec-fg-install-guide.pdf`) is the 10 Nov edition with the old kit price, email and PETG wording. Rebuild it last with the photos and replace it under the same name (the release stays bracket files only) | Repo project |

## The launch switch

Do all of this in one edit when DOMAIN says the full kaltec.au site with checkout is live:

- [ ] Delete the A$20-off line everywhere it appears. It's only in `README.md`: the "Rather not build it?" tip near the top, and the "A$20 off before launch" paragraph in Kits and parts.
- [ ] In `README.md`, make the Kits and parts table link to kaltec.au to buy (each product name or a "Buy" column linking to its kaltec.au page), and drop "Kits are ready from 1 December 2026".
- [ ] Bump the README footer version and date.
