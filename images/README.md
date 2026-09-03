# Vehicle photos

Drop real photos in here, named to match the `vehicles` list near the top of the
`<script>` block in `index.html`:

- `aygo.png` — Toyota Aygo X
- `yaris.png` — Toyota Yaris
- `yariscross.png` — Toyota Yaris Cross
- `corolla.png` — Toyota Corolla
- `corollats.png` — Toyota Corolla Touring Sports
- `chr.png` — Toyota C-HR
- `chrplus.png` — Toyota C-HR+
- `urbancruiser.jpg` — Toyota Urban Cruiser (still needed — not uploaded yet)
- `rav4.png` — Toyota RAV4
- `prius.png` — Toyota Prius
- `proace.png` — Toyota Proace
- `hilux.png` — Toyota Hilux
- `landcruiser.png` — Toyota Land Cruiser

To add or rename a model, edit that one list in `index.html` — no other HTML or
CSS needs to change, the dropdown builds itself from it.

Any image size works (it scales to fit with `object-fit: contain`), though for
consistent print results it's worth roughly matching the aspect ratio across the
set — landscape 3–4:2 works well. No compression needed; GitHub Pages serves
these as static files like any other site asset.

If a photo is missing, the page shows a small dashed "Add photo: images/xyz.jpg"
box instead of a broken image icon, naming exactly which file it's waiting on.
