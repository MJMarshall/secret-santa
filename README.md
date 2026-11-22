# Secret Santa

A single-page Secret Santa draw that runs entirely in the browser. It's hosted on GitHub Pages.

- Type names (and optional emails) on your phone, add any "can't draw each other" pairs, then tap **Draw names**.
- Each person gets a private link. Their match is scrambled into the part of the link after `#`, which browsers never send to the server.
- No names, emails or matches are stored in this repo or sent anywhere. The list is saved only in your own browser's local storage, and you can delete it from the page.
- The page makes no external requests. A Content-Security-Policy blocks network calls.

The links are scrambled, not encrypted, so send each one only to its owner.

## Enabling GitHub Pages

Settings → Pages → Build and deployment → Source: *Deploy from a branch*. Choose the branch and `/ (root)`.
