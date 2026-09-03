# RRG Group — Account Review

Internal, fillable "account review" letter template used for finance customer
equity updates. Open `index.html` (or the live GitHub Pages link, once enabled)
in a browser, fill in the customer's details, then use **Print / Save as PDF**.

- All fields are plain editable text — click into any value and type over it.
- Nothing is saved anywhere (no localStorage, no cookies). Every fresh page
  load starts from the same sample values, and the form also blanks itself out
  automatically right after you print/save, so one customer's details can't
  carry into the next.
- Vehicle photos live in [`images/`](images/) — see that folder's README for
  how to add or rename models.

## Publishing this on GitHub Pages

This repo has no workflow permissions to enable Pages automatically. To turn
on the live link (one-time setup):

1. Go to **Settings → Pages** in this repository.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Branch: `main`, folder: `/ (root)` → **Save**.

The site will be live at `https://6n8sz4dc2y-coder.github.io/rrg-account-review/`
a minute or two after saving, and re-deploys automatically on every push to
`main`.
