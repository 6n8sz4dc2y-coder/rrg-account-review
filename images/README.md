# Vehicle photos

Drop real photos in here, named to match the `vehicles` list near the top of the
`<script>` block in `index.html`:

- `aygo.jpg` — Toyota Aygo X
- `yaris.jpg` — Toyota Yaris
- `yariscross.jpg` — Toyota Yaris Cross
- `urbancruiser.jpg` — Toyota Urban Cruiser
- `rav4.jpg` — Toyota RAV4
- `landcruiser.jpg` — Toyota Land Cruiser

To add or rename a model, edit that one list in `index.html` — no other HTML or
CSS needs to change, the dropdown builds itself from it.

Any image size works (it scales to fit with `object-fit: contain`), though for
consistent print results it's worth roughly matching the aspect ratio across the
set — landscape 3–4:2 works well. No compression needed; GitHub Pages serves
these as static files like any other site asset.

If a photo is missing, the page shows a small dashed "Add photo: images/xyz.jpg"
box instead of a broken image icon, naming exactly which file it's waiting on.
